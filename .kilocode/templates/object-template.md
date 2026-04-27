---
obsidianUIMode: preview
cssclasses:
- json5e-object
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/object/size/{{SIZE}}
- ttrpg-cli/object/type/{{OBJECT_TYPE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
%%-- Embedded content starts on the next line. --%%
*Source: {{SOURCE_FULL}}*  

{{OBJECT_DESCRIPTION}}

```ad-statblock
title: {{NAME}}
![]({{TOKEN_URL}}#token)
*{{SIZE_TITLE}} {{OBJECT_TYPE_DISPLAY}}*

- **Armor Class** {{AC}}
- **Hit Points** {{HP}}
- **Speed** {{SPEED}}

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|{{STR}} ({{STR_MOD}})|{{DEX}} ({{DEX_MOD}})|{{CON}} ({{CON_MOD}})|{{INT}} ({{INT_MOD}})|{{WIS}} ({{WIS_MOD}})|{{CHA}} ({{CHA_MOD}})|

{{SPECIAL_TRAITS}}

## Actions

***{{ACTION_NAME}} ({{ACTION_REQUIREMENTS}}).*** *{{ATTACK_TYPE}}:* `+{{ATTACK_BONUS}}`, range {{RANGE}} ft. *Hit:* {{DAMAGE}} {{DAMAGE_TYPE}} damage.
```
^statblock
