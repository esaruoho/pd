# pd == Pure Data / PD action

A small selection of simplistic patches for Pure Data Extended (not PD Vanilla). All of these aim to be standalone and cleaned up so that they make sense and could be used in projects.

None of this would be possible without the extended PD family / Pure Data communities / Telegram PD etc helping out a great deal.

# midimetro.pd - Eats external Midi-sync clock into bangs

A simple Pure Data patch that splices at least Ableton Live Midi-sync clock into a bang - plug this into your wheelworks and your Ableton Live tempo will be accessible in your patches.

# delay4896~.pd - Simplistic stereo delay

Stereo delay with panning, echo volume control, delay length control, left and right feedback controls.
Hard-set to use 80ms for delay-length change, will see if 80 can be changed with a third inlet, later. Probably?

The first inlet is for audio, second inlet is for delay length (0-1000). 
Panning, echovolume set to 0.5, time set to uhh nothing i guess.

Created with `delwrite~` and `vd~`.

# rotkno.pd

Abstraction for taking information from rotary knobs and rendering them usable.
