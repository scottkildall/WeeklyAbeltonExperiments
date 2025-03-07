# Week7_Operator




### Concept



A synth like WaveTable that seems incredibly useful

Concept of Audible Oscillators and Inaudible Oscillators — ones that you can and you cannot hear.

You basically have 4 oscillators.

FM Modulation is what Operator is based on. This produces additional frequencies or sidebands. And ALSO uses subtractive synthesis.

Think about these operators like wires.

### Tutorials

shorter

[https://www.youtube.com/watchapp=desktop&v=Gn0JEtOdmb8&t=309s](https://www.youtube.com/watch?app=desktop&v=Gn0JEtOdmb8&t=309s)

longer


[
https://www.youtube.com/watch?v=rXrRdaRrvjU](https://www.youtube.com/watch?v=rXrRdaRrvjU)

### Basics

Operator has four oscillators (also called operators).
 
### Understanding the Algorithm

You have different algorithms for how the Oscillator works — the algorithm defines the connection between the oscillators.

The Audible Oscillators are the ones that at the bottom of the algorithm chain.

The Inaudible Oscillators are the ones that modify the audible. For example, in the leftmost chain, D-C-B-A

### Envelopes

Each Oscillator has an envelope. The ADSR isn't seeming too active to me.

Time < Vel and Velocity settings get into the weeds a bit.

Key is keyboard-tracking, recommendation is to use it for the modulating oscillator, from the sad german guy


### Detuning

Coarse and Fine will let you detune the pitch from each oscillator, as ratios.

The fine can be subtle and we could add LFOs to it.

### Oscillator itself

You can make your own drawings. Also left-click to choose even or odd harmonics. Even supposedly sounds a bit better.

Can choose different numbers on the harmonics

Phase is just the starting point on the oscilator wave. Maybe could be useful with an LFO

R will be the retrigger, where the oscillator starts, probably good to have this on in most every case.

Osc < Vel makes the oscillator to response to different velocities of notes.

Q = quantize, usually keep it on

Feedback, will use itself as a modulation

Loop:Beat and Sync will issues stacatto notes
Trigger mode will bypass the sustain

### Global settings on the right

#### LFO and Filter

You can apply these to any number of operators.

The LFO doesn't seem to do what I want it to.

The tutorial does one thing and my experiments do something else.

#### Pitch Envelope Shell

Is a bit confusing, but you can apply pitch envelopes to any number of 

### Live Sets

#### Operator_Template

A simple one with a nice sound

#### Operator_Fine

LFO use with the Fine control.

#### Operator_PitchEnvelope

Applies pitch envelope shell to one of the operators.


### Workflow

There are a lot of pre-built Operators out there. I think I'll just make use what's out there and modify them slightly for harmonics, rather than building them from scratch.

Probably will work with the keyboard for figuring out an Operator sound design

### Tips

Work with sine waves at first
Could work with your own sound libraries — custom operators, etc.

### Questions

Well, as with a lot of synthesis, this gets quite techy.



