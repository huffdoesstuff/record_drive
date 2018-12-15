# Record Player Drive
A stepper motor drive (with feedback) for a custom record player.

Currently using Trinamic TMC2208 StepStick as motor control with a cheap stepper motor from Amazon. Likely going to change to open loop control with a precision oscillator driving the step pin of the stepper controller. Motor itself will likely be upgraded as well (bearing noise is a bit of a problem).

Components:
- Longruner 17HS4401 stepper (200 steps/rev)
- Trinamic TMC2208 SilentStepStick
- Arduino Pro Mini (for protoyping / testing)

References:
- https://learn.watterott.com/silentstepstick/pinconfig/
- https://learn.watterott.com/silentstepstick/
- https://github.com/superjamie/lazyweb/wiki/3D-Printing-TMC22xx-Quick-Guide
