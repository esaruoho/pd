# pd
Pure Data / PD action

A smattering of simplistic Pure Data patches. These are fairly modular and fairly cleaned up. Hope these help.


# midimetro.pd

A simple Pure Data patch that splices at least Ableton Live Midi-sync clock into a bang - plug this into your wheelworks and your Ableton Live tempo will be accessible by your patches.

# delay4896~.pd

Stereo delay with panning, echo volume control, delay length control, left and right feedback controls.
Hard-set to use 80ms for delay-length change, will see if 80 can be changed with a third inlet, later. Probably?

The first inlet is for audio, second inlet is for delay length (0-1000). 
Panning, echovolume set to 0.5, time set to uhh nothing i guess.

Created with delwrite~ and vd~ .
I think I had assistance from the internets on creating this, but can't find the forums anywhere right now. 

# rotkno.pd

Abstraction for rotary knobs - again with help from the Pure Data community - too many people to mention.
