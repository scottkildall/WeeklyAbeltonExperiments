# Week5_WaveTable




### Concept

Explained here
[https://blog.native-instruments.com/what-is-wavetable-synthesis/
](https://blog.native-instruments.com/what-is-wavetable-synthesis/)

So, instead of a sine wave, etc that to make a sound, say at 440Hz, you can use a recorded waveform.

A wavetable synth gives the user not just one waveform at a time, but a stack or “table” of different waveforms. Using digital interpolation, it’s possible to smoothly transition between the different shapes in the table, allowing us to create sounds that shift and evolve, with a liveliness not found in more basic sample-based synths.

Instead of one wave, you have a table and an index into that table to shift which waveform you will be synthesizing.



### History


[https://www.youtube.com/watch?v=_w1h4vknfow
](https://www.youtube.com/watch?v=_w1h4vknfow)


### Tutorials

Though this is like 6 years old, it still feels very thorough.

[https://www.youtube.com/watch?v=m8zYnm8dRuE](https://www.youtube.com/watch?v=m8zYnm8dRuE)

Great starter

[https://www.youtube.com/watch?v=MWuU7BqbqBU
](https://www.youtube.com/watch?v=MWuU7BqbqBU)

Jannis Le Wolff

[https://www.youtube.com/watch?v=YcANPEm858g
](https://www.youtube.com/watch?v=YcANPEm858g)

More specific?

[https://www.youtube.com/watch?v=msjAGVRCp6M
](https://www.youtube.com/watch?v=msjAGVRCp6M)

Annoying background music
[https://www.youtube.com/watch?v=9wovKSfR66A
](https://www.youtube.com/watch?v=9wovKSfR66A)


### Basic Controls


At the core of it, you have two oscillators. Each one has its own volume control.


You have two EQ filters you can use, though I don't see why you don't just use EQ Eight, which also lets you see the visual of the spectrum.

Third Tab has info below:

Also there is a sub oscillator pane on the left
And global controls on the right

#### Main Wavetable

You have categories and subcategories. Arrows will cycle through the subcategories.

You can do a stacked view or a radial view.

Has pan and volume controls as well. I could see pan controls being useful for the same wavetable and different oscillators going on.

Volume controls for each oscillator, that's nice

Other adjustments: detune, semitone, etc. Might be too much for now. Warp and Fold allow you to change the character of the waveform itself.

Sub oscillator — can enchance tone, should be easy to experiment with.

#### Mod Sources
Amplitude has an ADSR on it


Loop Mode: how the note on/offs will work. Trigger is probably best for my purposes

You have Env2 and Env3, which you can use as well. They have no minimums or maximums, so you can do weird things with them.

LFOs have all sorts of basic features to them. Can also press the note button to sync to tempo.

#### Matrix

This is where you assign the mod sources. It takes a little while to figure this out, but once you get it, makes a lot more sense.

Time global parameter will slow everything down; amount will dial it all back

#### MIDI

#### MPE


### Tricks & Techniques

Use expanded view to see more of the controls

Modulating the **position in the wavetable** (the index) is where the power of the WaveTable synth comes into play

Not really a T&T, but the way notes get played is that they are issued out

It is a poly-phonic synth, as well

In Expanded View, you can drag the title bar up and get all the wavetable view — zoning in on music view

### LiveSets

#### WaveTable_Template

Start here

#### WaveTable_LFO

Uses just one oscillator and an LFO to change the index of the oscillator. I can't say this is pleasing.

Uses the Matrix

#### WaveTable_Tuner

A good place to show the actual notes that are coming in.

#### WaveTable_ModTrigger

Shows the how to trigger with note on events, playing all the way through

#### WaveTable_PitchBend

Uses just one envelope in the Matrix to do a pitch bend, kind of weird

Uses the Matrix

#### WaveTable_MIDIKey

Shows how we can go to different notes in the key

### Mixes

**datamix.wav** a mix of the data


### What I don't get


**All the global settings on the right, what do they all do?
**

The MPE aspect of the matrix

**How long each wave file is**



Some limitations: it sounds like a synth and not an instruments.

### What I won't cover is:

FM Synthesis


Subtractive Analog Synthesis'


### Take-homes

Since you can do anything in Ableton, doing something right is what is key. Having some pre-built WaveTables, instead of just throwing in any .wav will help out a lot, maybe bundle packs like these:
[
https://hellosamples.com/sound-packs/ableton-wavetable-free-essentials/](https://hellosamples.com/sound-packs/ableton-wavetable-free-essentials/)


