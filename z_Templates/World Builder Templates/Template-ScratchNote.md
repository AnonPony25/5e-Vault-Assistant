---
tags:
  - Category/Scratch
NoteStatus: ❓
obsidianUIMode: source
---
<%*
const title = await tp.system.prompt("Scratch Note Title", tp.file.title);
if (title) await tp.file.rename(title);
-%>

# <% tp.file.title %>

> [!NOTE]- Created
> **Date:** <% tp.date.now("YYYY-MM-DD") %>
> **Time:** <% tp.date.now("HH:mm") %>

## Raw Notes

Write anything here - ideas, reminders, raw observations.

## Needs Action?

- [ ] Refine and move to proper folder
- [ ] Link to relevant notes
- [ ] Archive or delete if no longer needed

## Tags / Links

Related:
