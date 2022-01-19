# JA#

JA# is a fork of JA++ developed to return to a form closer to JA+ while adding a few elements that are intended more for the roleplaying community that still frequents the game.

The mod will intend to address the following shortcomings that JA+ and JA++ had in common.

## Server-Side

* Ability to auto-login all players into the 'clan chat'
* Ability to grant particular commands, like /ammerc and /amtele, to all players regardless of admin login level
* Alternatively, auto-login all players into the admin level that has these commands
* Ability to set the clan tag
* Ability to use some GalaxyRP-esque features, like a /me text emote
* Expose more animations to the /am system
* Customize the submittable length of text in the server


## Client-side
* Dramatically increase the customization selection limitation based on the player's hardware or desires.
* Tie text triggers to colors via .cfg
* * Player can link an inline phrase or symbol that would automatically trigger a temporary change in color or a permanent one.
* 

## compilation

* Python 3.9.1
* [Scons](https://github.com/SCons/scons)

e.g. `scons debug=1 force32=1`

Windows

* [TDM-GCC](https://jmeubank.github.io/tdm-gcc/) for non-MSVC
* If you wish to use MSVC with JA++, specify `tools=default` to scons

Options

* `force32` 1 to build a 32-bit binary on a 64-bit machine
* `debug` 1 to generate debug information, 2 to also optimise code
* `no_sql` 1 to disable MySQL/SQLite support 
* `no_crashhandler` 1 to disable the crash handler/logger functionality

Environment Variables

* `NO_SSE` 1 to not generate SSE2 instructions - closer to basejka. This is used for official builds
* `MORE_WARNINGS` 1 to enable more compiler warnings

## contributors
* JesseLeeHumphry (lead)

## credits
* JK2MV
* loda
* OJP
* OpenJK
* JA++
