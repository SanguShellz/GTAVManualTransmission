[comment]: # (GitHub README.md)

# Manual Transmission

**NOTE:** This Project has been necroed to work with GTA V Legacy 1.0.3788. Some issues may remain. This does not have feature parity with updated versions on [Patreon](https://www.patreon.com/ikt). 

This project aims to expand the driving immersion of Grand Theft Auto V, with many features and options:

* Complete steering wheel support
  * DirectInput interfacing
  * Force feedback from scratch
  * Multiple devices supported
* Transmission replacement with custom modes and more
  * Manual sequential
  * Manual H-pattern
  * Automatic
  * Working clutch
* Tunable driving assists
  * Launch control
  * Traction control
  * Stability control
  * Custom anti-lock braking
* Synchronized steering wheel and animations
  * Match your actual wheel 1:1
  * First person hand-over-hand animations

And much more. The [user README.md](doc/README.md) has a more complete overview.

## Game requirements

* Grand Theft Auto V (build 1604+)
* [ScriptHookV by Alexander Blade](http://www.dev-c.com/gtav/scripthookv/)

## Downloads

* [GitHub releases](https://github.com/SanguShellz/GTAVManualTransmission/releases)

## Building requirements

* Visual Studio 2022+

The solution builds two files:

* `Gears.asi`, the actual script. This goes in Grand Theft Auto V's root folder.
* `WheelSetup.exe`, which is a companion program for debugging wheel inputs. Can also write configurations.

## Scripting API  

Some convenience functions are exposed by the script.

Check [ManualTransmission.h](https://github.com/E66666666/GTAVManualTransmission/blob/master/Gears/ManualTransmission.h) for available API functions.

* [C# Example](https://gist.github.com/E66666666/d11cdbd9800ad73efeff612374349347)
* [C++ Example](https://gist.github.com/E66666666/59390733b366cad4638901ae5fcfd046)


