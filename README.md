# VehicleControlAddon for Farming Simulator 2019

## Status
Since some versions there are problems if you use VCA and sleep on dedi server. My plan was to finish this mod as farewell present for you. But with this bug on the dedi server it is impossible to publish VCA on ModHub. So I took my consequences and stopped now. In German we say "Lieber ein Ende mit Schrecken als Schrecken ohne Ende!"

## VehicleControlAddon is the new KeyboardSteer
Please check section status why I renamed the mod. Please use VCA as abreviation.

You will have to choose the new mod after replacing it in the mods folder. But settings in old save games are still read.

## Developer version
Please be aware you're using a developer version, which may and will contain errors, bugs, mistakes and unfinished code. 

You have been warned.

If you're still ok with this, please remember to post possible issues that you find in the developer version. 
That's the only way we can find sources of error and fix them. 
Be as specific as possible:

* tell us the version number
* only use the vehicles necessary, not 10 other ones at a time
* which vehicles are involved, what is the intended action?
* Post! The! Log! to [Gist](https://gist.github.com/) or [PasteBin](http://pastebin.com/)

From today on I will close all new issues without the above information!

## Motivation
Although I have a steering wheel, but almost always play with the keyboard. On winding roads, I am again and again landed in the ditch in front of nights or power poles.

## Description
This script varies the steering speed depending on the speed you are driving, and it rotates the camera to match the steering angle and direction.
Shift-Left limits throttle, cruise control and maximum rounds per minute to 75%. With Shift-right and the cursor keys you can peek in the corresponding direction.
If you press Ctrl left together with W then the driving direction snaps to fixed directions.
Additionally, there is a simple gear box. It was never planned to make a super realistic gearbox. The following transmisions are available:
* off: the standard gearbox without customization
* IVT: Still the standard gearbox but with little adjustments to the allowed RPM range. More to come...
* 4X4: An old fashioned transmissoin with 4 gears in 4 groups and shuttle control. Shifting gears takes time and you might lose momentum.
* 4PS: The same transmissoin as above but with power shift for the gears
* 2X6: Two groups with 6 gears. This transmission is useful for G27/G29 gear shifters. There is a low and a high range. The 6 gears in each range do not overlap with the 6 gears in the other range
* FPS: Full Power Shift: The transmission has 12 gears and shifts without interuption. 
* 6PS: 6 gears with power shift: This transmission has 6 gears. Each gear can be reduced by about 80%

All functions are switchable with the following default key combinations:
* Ctrl Left + C: Settings
* Ctrl Left + W: Snap Angle
* Shift Left: Throttle limiter / reduced cruise control speed
* Shift Right + Cursor: look forward, backwards, left right
* Space: Change direction (aka shuttle control)
* Please check the keys for shifting. G27/G29 gear shifters are supported.
* The 7th gear of the gear shifter is special. If you use action binding ksmShifter7 please make sure that shuttle control is enabled. This action binding will swtich into 1st reverse gear. 
* Best transmission in combination with a gear shifter are 2X6, FPS and 6PS. 

## Developer version
Please be aware you're using a developer version, which may and will contain errors, bugs, mistakes and unfinished code. 

You have been warned.

If you're still ok with this, please remember to post possible issues that you find in the developer version. 
That's the only way we can find sources of error and fix them. 
Be as specific as possible:

* tell us the version number
* only use the vehicles necessary, not 10 other ones at a time
* which vehicles are involved, what is the intended action?
* Post! The! Log! to [Gist](https://gist.github.com/) or [PasteBin](http://pastebin.com/)

## Credits
* Stefan Biedenstein
