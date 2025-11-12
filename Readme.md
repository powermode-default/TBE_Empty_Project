# TBE_Empty_Project

This is the empty project template for use with The Button Engine. It's usage is explained [here](https://powermode-default.com:8480/docs/TBE-Docs/LATEST/quickstart.html)

NOTE that The Button Engine is NOT YET RELEASED.

It contains the following items that are required by The Button Engine and **you must install/configure them yourself if you do not use this template**:

## Unity

* Layer: Ground
* Layer: Unit
* Renderer Feature: Decal
* Package: Localization
  * Localization Settings
* Package: Behavior
* Package: Cinemachine
* Package: Text Mesh Pro

## Open Source
* NuGet for Unity
### installed via NuGet:
* R3
* Observable Collections.R3
* ZLinq

### installed via Unity Package Manager:
* R3.Unity installed from https://github.com/Cysharp/R3.git?path=src/R3.Unity/Assets/R3.Unity
* UI Effect installed from https://github.com/mob-sakai/UIEffect.git?path=Packages/src#5.6.3


## TBE's package dependencies
(you must install these either way, no matter if you are using this template or not.)
* Odin 
* DOTween
* TBE itself

## other settings
* Make sure TbeSystemManager gets loaded before other user code (Script loading order)
