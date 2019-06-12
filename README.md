# rMilliOhm-Meter
A multimeter-based milliohm meter.

This is my version of the Milliohm meter that I saw on the Electrotodos YT channel.

I can read 1mΩ resistors with this (repressented as 1mV).

## Notes:
- This will use 5-12 VDC input (batteries preffered).
- The calibration it's only that you've to set 10mA as current source using the potentiometer.
- RV1 (the potentiometer) requires to be a multi-turn pot, otherwise will be quite difficult to set (and maybe impossible).
- Q1 it's only a polarity protection it can be by-passed or just use a standard diode.
- C7 I didn't populate it and seems that works fine without it.
- R5 to R10 it's way important that its values are as close as possible between them. I selected by hand and the difference were under 10 ohms.
- R5 to R10 were meant to be 4K91 but it seems that I got 5% accuracy and close to 5K.
