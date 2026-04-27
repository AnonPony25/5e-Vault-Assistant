---
obsidianUIMode: preview
cssclasses:
  - json5e-background
tags:
  - ttrpg-cli/compendium/src/5e/phb
  - Category/Background
aliases:
  - "Background Name"
source: "phb"
---
<%*
const bgName = await tp.system.prompt("Background Name", tp.file.title);
const src = await tp.system.prompt("Source code (e.g. xphb)", "xphb");
if (!bgName) return;
await tp.file.rename(bgName.toLowerCase().replace(/ /g,"-") + "-" + src);
setTimeout(() => {
  const f = tp.file.find_tfile(tp.file.path(true));
  if (!f) return;
  app.fileManager.processFrontMatter(f, fm => {
    fm["aliases"] = [bgName];
    fm["source"] = src;
    fm["tags"] = [`ttrpg-cli/compendium/src/5e/${src}`, "Category/Background"];
  });
}, 100);
-%>

# <% tp.file.title %>

*Source: <!-- source book -->*

## Description

<!-- Background description -->

## Skill Proficiencies

**Skill Proficiencies:** <!-- skills -->

## Tool Proficiencies

**Tool Proficiencies:** <!-- tools or None -->

## Languages

**Languages:** <!-- languages or None -->

## Equipment

**Equipment:** <!-- starting gear -->

## Feature: <!-- Feature Name -->

<!-- Feature description -->

## Suggested Characteristics

### Personality Traits

| d8 | Personality Trait |
|----|------------------|
| 1 | - |
| 2 | - |
| 3 | - |
| 4 | - |
| 5 | - |
| 6 | - |
| 7 | - |
| 8 | - |

### Ideals

| d6 | Ideal |
|----|-------|
| 1 | - |
| 2 | - |
| 3 | - |
| 4 | - |
| 5 | - |
| 6 | - |

### Bonds

| d6 | Bond |
|----|------|
| 1 | - |
| 2 | - |
| 3 | - |
| 4 | - |
| 5 | - |
| 6 | - |

### Flaws

| d6 | Flaw |
|----|------|
| 1 | - |
| 2 | - |
| 3 | - |
| 4 | - |
| 5 | - |
| 6 | - |
