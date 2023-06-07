![alt text](https://github.com/tobinja1/floopEngine/blob/main/floopenginelogo.PNG "floopEngine Logo")

# floopEngine
An audio looping abstraction for Max/MSP

floopEngine is the engine powering [live.floop](https://jaytobin.gumroad.com/l/livefloop?layout=profile), my Max for Live device for quick, jittery audio looping and playback.

## download instructions

download the floopEngine.maxpat file and put it somewhere safe. Should you have trouble downloading only the file, you can always **double-click floopEngine.maxpat, tap the "raw" button towards the top-right of the code box, hit ctrl+A** (or cmd, if that's more your thing) **to copy all text, head to File in Max, and tap "new from clipboard" then save the resulting patch as "floopEngine."**

To get floopEngine to show up when you type it in, **open Max, tap File -> Show File Browser, then tap the "Add Files to Search Path" button.**
Go to wherever you've saved floopEngine.maxpat, double-click it, and you should be good to go!

## operation

here's a quick rundown of the inlets that make floopEngine work:

![alt text](https://github.com/tobinja1/floopEngine/blob/main/floopEngineClip.PNG "floopEngine screenshot")

**inlet 1:** loads an audio file after being banged

**inlet 2:** plays through the sample once after being banged, but **only if floopEngine is in oneshot mode**!

**inlet 3:** controls playback direction, with 0 playing the sample backwards at rate, and 1 playing forwards

**inlet 4:** controls where the loop playback starts from, from 0-1 (0 being the beginning of the sample, 1 being the end)

**inlet 5:** controls where the loop playback ends, from 0-1

**inlet 6:** controls stereo panning, with 0 being total left panning, and 1 being total right panning

**inlet 7:** controls playback speed, with the base starting at 1, with 2 being double speed, and 0.5 being half

**inlet 8:** toggles between oneshot or loop mode (0 for loop, 1 for oneshot)

## licensing and contact info

please mess with this and do with it as you will, floopEngine's guts are made to be mangled! This maxpat is shared under the MIT Creative Commons License to be both used,
edited, and redistributed, but do be a mensch and mention me if you're sharing it with folks!

any questions regarding this or getting it to properly work, feel free to reach out to me at tobinja1@gmail.com.
