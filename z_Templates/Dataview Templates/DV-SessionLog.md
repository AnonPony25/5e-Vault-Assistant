---
obsidianUIMode: preview
---
# Session Log

## All Sessions

```dataview
TABLE WITHOUT ID link(file.name) AS "Session", sessionDate AS "Date", OneLiner AS "Summary", sessionRoster AS "Players Present"
FROM "1-Session Journals"
SORT sessionDate DESC
```

## Recent Sessions (Last 5)

```dataview
TABLE WITHOUT ID link(file.name) AS "Session", sessionDate AS "Date", OneLiner AS "Summary"
FROM "1-Session Journals"
SORT sessionDate DESC
LIMIT 5
```

## Quest Activity by Session

```dataviewjs
const sessions = dv.pages('"1-Session Journals"').sort(p => p.sessionDate, 'desc').slice(0, 10);
for (let s of sessions) {
  const quests = dv.pages('"2-World/Quests"').where(q =>
    q.questSessionObtained && String(q.questSessionObtained).includes(s.file.name)
  );
  if (quests.length > 0) {
    dv.header(4, dv.fileLink(s.file.path));
    dv.list(quests.map(q => dv.fileLink(q.file.path) + " -- " + (q.questStatus ?? "Unknown")));
  }
}
```
