# Ave-SDK

[Back to general README file](README.md)

Basically all comments in the code and version history are in English only.

## INTRO

A platform independent C++ library for developing various apps.

Main modules:
* Core library
* Basic 2D rendering
* Basic 3D rendering
* System objects (Process, threads, sync objects, ...)
* Text processing
* Basic socket networking
* I/O
* Database
* Console UI
* Graphics UI, currently including about 50 types of controls

Tools with the library:
* Code statistics and standard detection tool
* File processor for developing and compiler
* Solution/project creator
* Graphics UI test tool/example 
* Theme editor for image-based graphics UI

Currently non-public modules/tools：
* Audio library and DSP (Digital Signal Processor)
* Game engine
* Game engine editor

## ABOUT VERSIONS

Version: `major`.`minor`.`build`.`private`

Version history item format: `type` `module`: `description`

`Type`|Description
-|-
+|Added feature
-|Removed feature
!|Updated feature
\*|Fixed bug
||Other

`module`: "Avernakis" is omitted.
Example: "Avernakis-Gui" will be written as "Gui",
"Avernakis" itself will be written as "" (empty).
"Common" presents all modules.

Example:
```
+ Gui: Button control
! : Math vector
```
This means:
```
Added Button control to "Avernakis-Gui" module
Updated math vector library in "Avernakis" module
```
