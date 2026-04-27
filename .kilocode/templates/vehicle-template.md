---
obsidianUIMode: preview
cssclasses:
- json5e-vehicle
tags:
- ttrpg-cli/compendium/src/5e/{{SOURCE_CODE}}
- ttrpg-cli/vehicle/size/{{SIZE}}
- ttrpg-cli/vehicle/terrain/{{TERRAIN}}
- ttrpg-cli/vehicle/type/{{VEHICLE_TYPE}}
aliases:
- "{{NAME}}"
---
# {{NAME}}
%%-- Embedded content starts on the next line. --%%
*Source: {{SOURCE_FULL}}*  

```ad-statblock
title: {{NAME}}
![]({{TOKEN_URL}}#token)
*{{SIZE_TITLE}} vehicle; {{TERRAIN}}*

- **Creature Capacity** {{CREW}} crew, {{PASSENGERS}} passenger(s)
- **Armor Class** {{AC}}
- **Hit Points** {{HP}}
- **Speed** {{SPEED}}

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|{{STR}} ({{STR_MOD}})|{{DEX}} ({{DEX_MOD}})|{{CON}} ({{CON_MOD}})|{{INT}} ({{INT_MOD}})|{{WIS}} ({{WIS_MOD}})|{{CHA}} ({{CHA_MOD}})|

- **Damage Immunities** {{DAMAGE_IMMUNITIES}}

{{VEHICLE_DESCRIPTION}}

**{{TABLE_NAME}}**

| Lever | Up | Down |
|---|---|---|
| {{CONTROL_1}} | {{EFFECT_UP_1}} | {{EFFECT_DOWN_1}} |
| {{CONTROL_2}} | {{EFFECT_UP_2}} | {{EFFECT_DOWN_2}} |
```
^statblock
