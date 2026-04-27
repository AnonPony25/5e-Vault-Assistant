---
name: z-markdown-templates
description: Use when inserting Markdown snippets from z_Templates/4_Markdown/. Covers ITS callout modifiers, tabbed blocks, Leaflet, ad-statblock, and rollable table syntax.
---

# Markdown Templates Skill

## ITS Theme Callout Modifiers

| Modifier | Effect |
|----------|--------|
| `no-h` | Hide callout header |
| `no-t` | Hide callout title text |
| `no-i` | Hide callout icon |
| `div-m` | Render as responsive div |
| `tabbed` | Tabbed container |
| `tabbed-box-maxh` | Tabbed box with max height |

## Tabbed Content Block
```
~~~meta-bind
INPUT[select(
option(1, Tab One),
option(2, Tab Two),
class(tabbed)
)]
~~~
>[!tabbed-box-maxh]
>>[!div-m|no-title]
>> ![[#SectionOne|no-h clean]]
>
>> [!div-m|no-title]
>> ![[#SectionTwo|no-h clean]]
```

## Rollable Table
```
`dice: [[Note Name.md#^block-id]]`

| dice: d6 | Result |
|:--------:|--------|
| 1 | - |
^block-id
```

## Leaflet Map
Always use a unique `id:` per map to avoid rendering conflicts.

## ad-statblock
Always add `^statblock` immediately after the closing fence.
