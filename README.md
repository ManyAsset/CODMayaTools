# Call of Duty Maya Tools
[![ManyAsset](https://img.shields.io/discord/585171589750849538?color=%23FF8711&label=ManyAsset&logo=discord&logoColor=%23FFFFFF)](https://discord.gg/v2TWkeR)
[![ManyAsset](https://img.shields.io/youtube/channel/subscribers/UCQLUoUspSxbTKnhfc6ox03w?style=flat&logo=youtube&label=ManyAsset&color=fb0335
)](https://www.youtube.com/@ManyAsset)

## Description:
Call of Duty Maya Tools supports exporting models, animations, and xcams from Maya.
The tool allows modders to export existing assets from other games or custom assets into a Call of Duty standard file format.
The plugin includes additional features such as exporting cosmetic joints and Ray's Anim Toolkit for camera animations.

### Exported Files
Models export as `.xmodel_export`  
Animations export as `.xanim_export`  
Xcams export as `.xcam_export`  

## Features:
* Support for Black Ops 3 with Export2Bin/ExportX
* Backwards compatibility with Call of Duty 1 (untested & xmodels only)
* Read notetracks from Cast, SEAnims, Wraith, tanims, and old files
* Ray's Camera Animation Toolkit included for camera animations
* Export XCams for Black Ops 3
* Cosmetic bones for use in Black Ops 3

## Requirements:
* Call of Duty Maya Tools is a plugin for Autodesk's Maya tool and designed for [Autodesk Maya 2022](http://autodesk.com/maya) or later

## Installation:
  Head this directory `Documents\maya\VERSION\scripts`, Drag and drop all files from zip. if you already have a `userSetup.mel`, open it and paste this `python("import CoDMayaTools");` then save!

## Credits:
* elfenliedtopfan5: Cast Notetracks
* Luna Ryuko: Original Fork Maintainer
* Scobalula: PyCoD implementation code
* Aidian Shafran: Original Developer 
* DTZxPorter/SE2Dev: PyCod Library
