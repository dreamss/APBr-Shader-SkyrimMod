APBr-Shader-SkyrimMod
=====================

Port of the Skryim mod "FXAA Post Process Injector"
Original mod - http://skyrim.nexusmods.com/mods/131

Usage:
------

1. Copy SkyrimMod.usf and SkyrimModSettings.usf to Engine\Shaders
2. Add *#include "SkyrimMod.usf"* to APBUberPostProcessBlendPixelShader.usf before the bottom closing *}*, or use one of the included examples.
3. Edit SkyrimModSettings.usf and set your preferences.


Changelog
---------

v1.0:

* Initial version, port of Technicolor and Tonemap effects