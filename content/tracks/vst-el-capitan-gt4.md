---
title: "El Capitan GT4"
meta_title: ""
description: "El Capitan GT4 (El Capitan) by vastchapa1980"
date: 2025-05-20T14:35:00Z
thumb: IcHTIWB
trackmainimage: c0KBGZC
categories: ["Track"]
author: "Theodora"
tags: ["Circuit", "vastchapa1980", "ACF", "USA", "Gran Turismo", "GT", "Loop"]
draft: false
tracklink: https://mods.to/Y1P0682d838206378
tracklocation: "USA"
trackimage: grand-turismo
trackcity: California
trackhosted: ["USA"]
tracktype: ["Circuit", "Loop"]
trackclass: "-" 
layoutversion: "-"
tracklayout: 4
trackLength: "4.780"
trackwidth: "7-16"
trackpitboxes: 20
trackcreator: vastchapa1980
trackversion: "0.1"
trackcsp: "0.2.5"
trackname: "El Capitan"
trackfolder: "El Capitan"
trackhost: mods
---

To add brightness adjustments to trees, etc., add the following to the end of ext_config.

```ini
[SHADER_REPLACEMENT_...]
ACTIVE=1
DESCRIPTION=trees
MATERIALS= pinos, 1
BLEND_MODE=ALPHA_TEST
CAST_SHADOWS = 1
CULL_MODE = OFF
IS_TRANSPARENT = 0
DOUBLE_FACE_SHADOW_BIASED = 1
PROP_... = ksAmbient, 0.15
PROP_... = ksDiffuse, 0.1
PROP_... = ksSpecular, 0.0
PROP_... = ksSpecularEXP, 15

[SHADER_REPLACEMENT_...]
ACTIVE=1
DESCRIPTION=trees2
MATERIALS= GREES, 22.001, 23
BLEND_MODE=ALPHA_TEST
CAST_SHADOWS = 1
CULL_MODE = OFF
IS_TRANSPARENT = 0
DOUBLE_FACE_SHADOW_BIASED = 1
PROP_... = ksAmbient, 0.2
PROP_... = ksDiffuse, 0.1
PROP_... = ksSpecular, 0.0
PROP_... = ksSpecularEXP, 15

[SHADER_REPLACEMENT_...]
ACTIVE=1
DESCRIPTION=glass
MATERIALS= 5, 4
PROP_... = ksAmbient, 0.18
PROP_... = ksDiffuse, 0.15
PROP_... = ksSpecular, 0.03
PROP_... = ksSpecularEXP, 15

[SHADER_REPLACEMENT_...]
ACTIVE=1
DESCRIPTION=glass2
MATERIALS= salta
PROP_... = ksAmbient, 0.3
PROP_... = ksDiffuse, 0.3

[SHADER_REPLACEMENT_...]
ACTIVE = 1
MATERIALS = grove
SHADER = ksPerPixelAlpha
BLEND_MODE = ALPHA_BLEND
IS_TRANSPARENT = 1
CAST_SHADOWS = 0
PROP_0 = alpha,1
PROP_1 = ksSpecularEXP, 25
PROP_2 = ksDiffuse, 0.1

[SHADER_REPLACEMENT_...]
ACTIVE = 1
MATERIALS = LINIAS AMRILLAS
SHADER = ksPerPixelAT
BLEND_MODE = ALPHA_TEST

[SHADER_REPLACEMENT_...]
ACTIVE=1
DESCRIPTION=spectators
MATERIALS= gente
CAST_SHADOWS = 1
CULL_MODE= OFF
DOUBLE_FACE_SHADOW_BIASED = 1
SHADER = ksPerPixelAT
BLEND_MODE = ALPHA_TEST
```