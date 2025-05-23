---
title: "Grand Valley Speedway"
meta_title: ""
description: "Grand Valley Speedway (acf_grand_valley) by ACF"
date: 2025-05-20T14:05:00Z
thumb: Mq9EjLM
trackmainimage: 6fj8W8i
trackgallery: ["iinZsdn", "GVxh2K6"]
categories: ["Track"]
author: "Theodora"
tags: ["Circuit", "ACF", "Gran Turismo", "GT", "Loop"]
draft: false
tracklink: https://mods.to/qlaS682d7cceb7e6b
tracklocation: "Gran Turismo"
trackimage: gran-turismo
trackhosted: ["Gran Turismo"]
tracktype: ["Circuit", "Loop"]
trackclass: "-" 
layoutversion: "-"
tracklayout: 4
trackLength: "4.960"
trackwidth: "10-15"
trackpitboxes: 30
trackcreator: ACF
trackversion: "0.8.7"
trackcsp: "0.2.5"
trackname: "Grand Valley Speedway"
trackfolder: "acf_grand_valley"
trackhost: mods
---

12 layouts (GP, Short, Wet, etc.)

To add shader modifications and GrassFX, create an ext_config and extension file and add the following:

```ini
[GRASS_FX]
GRASS_MATERIALS=GRASSAR, GRAS1

[SHADER_REPLACEMENT_...]
ACTIVE=1
MATERIALS=BKA
SHADER = ksPerPixelAT
BLEND_MODE = ALPHA_TEST
```