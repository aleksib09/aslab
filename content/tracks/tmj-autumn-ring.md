---
title: "Autumn Ring"
meta_title: ""
description: "Autumn Ring (autumnring/autumnringmini) by Tomj"
date: 2025-05-20T13:45:00Z
thumb: I9SeF4q
trackmainimage: GNhSUwX
trackgallery: ["24u6mfG", "bdgqyRp"]
categories: ["Track"]
author: "Theodora"
tags: ["Circuit", "Tomj", "England", "Gran Turismo", "GT", "Loop"]
draft: false
tracklink: https://mods.to/FFOh682d7a98446fd
tracklocation: England
trackimage: grand-turismo
trackhosted: ["England"]
tracktype: ["Circuit", "Loop"]
trackclass: "-" 
layoutversion: "-"
tracklayout: 2
trackLength: "2.886"
trackwidth: "16-26"
trackpitboxes: 24
trackcreator: Tomj
trackversion: "0.85"
trackcsp: "Unknown"
trackname: "Autumn Ring"
trackfolder: "autumnring/autumnringmini"
trackhost: mods
---

This is a conversion of the rFactor circuit by Madcowie and Lasercutter.

Autumn Ring is a fictional circuit from the Gran Turismo series. The normal variant is 2.9km long, while the mini circuit is only 1.3km. Due to the short length It is more suited for slower cars, but there can be some good GT3 racing on the longer circuit.

This version has full working AI, track cameras and track map.

Includes 2 layouts (normal, mini).

___

*There should be autumnring.ini in extension\config\tracks\loaded, so add the following. If you are using the Mini layout, copy autumnring.ini and rename it autumnringmini.ini. Add lights and fix tire tracks.*

```ini
[SHADER_REPLACEMENT_...]
MATERIALS = roadskids
SHADER = ksPerPixelAlpha
CAST_SHADOWS = 0
IS_TRANSPARENT = 1
BLEND_MODE = ALPHA_BLEND
PROP_... = alpha, 1
PROP_... = ksDiffuse, 0.1
PROP_... = ksAmbient, 0.1

[Material_Water]
Materials = grvl_water
Type = POOL

[LIGHT_SERIES_0]
ACTIVE=1
DESCRIPTION=street lights
MATERIALS=roada191
DIRECTION=NORMAL
SPOT=180
RANGE=60
RANGE_GRADIENT_OFFSET=0.2
FADE_AT=850
FADE_SMOOTH=33
SPOT_SHARPNESS=0.25
DIFFUSE_CONCENTRATION=0.987531
CLUSTER_THRESHOLD=20
COLOR=255, 125, 70, 0.05
COLOR_OFF=0
CONDITION=NIGHT_SMOOTH

[MATERIAL_ADJUSTMENT_1]
ACTIVE=1
DESCRIPTION=street lights glow
MATERIALS=roada191
KEY_0=ksEmissive
VALUE_0=255, 100, 40, 0.24
OFF_VALUE_0=0, 0, 0
KEY_1=ksAlphaRef
VALUE_1=-193
OFF_VALUE_1=-193
CONDITION=NIGHT_SMOOTH
```