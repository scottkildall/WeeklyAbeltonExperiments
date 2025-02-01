# Week2_LaunchKey

The idea here is to explore the LaunchKey 37, but same principles apply to all MIDI keu inputs


## History

Much has been written about this, here is a short one on electronic synths. The keyboard makes electronic synths more marketable
[https://www.youtube.com/watch?v=5sjreF6H_rY
](https://www.youtube.com/watch?v=5sjreF6H_rY)

The pitch-wheel, for the mini-moog lets you do pitch-bending, and working with knobs is what makes it user-friendly, with controls going from left to right.

There is an order here to the signal flow. The microprocessor invention lets you do programable polysynths with bands like Depeche Mode and Tangerine Dream adopting this.

[Rudimentary guide on the keyboard key names
](https://www.youtube.com/watch?v=nAc509uEa68)

## Settings

Make sure to have LaunchKey MK4 37 (MIDI Out) on the MIDI track selected.

By default this is track 1

## Setup

I find this to be finnicky each time. 

Run the 1/8" Stereo Cable
Turn my SoundRover to Line Input
Run the Launchkey_Template
If it doesn't work, make sure MIDI is going out through Protokol


## Little things

I just noticed the Device View Toggle in Ableton, so you can see the synth notes and rack at the same time

You can map to a drum kit, but seems like all the hardware controls don't really work so well that way


## Pitch Transposing on samples

### One Way: Spectrum Audio Effect

The Spectrum audio effect is a nice little tool that shows the spectrum of sounds as they are being played. [Guide here at 2:12](https://www.youtube.com/watch?v=kc1UauhrQGQ) 

The [fundamental frequency](https://en.wikipedia.org/wiki/Fundamental_frequency) is the lowest freqeuncy of a waveform and defines the pitch of the note. The first large peak.

You can use the cursor on the spectrum view to see the note that is being played.

You can then use the Transpose knob on the Instrument Rack, or the Simpler to shift to the correct note.

It's extra useful to have the keyboard here at this point.

[MIDI note chart here](https://inspiredacoustics.com/en/MIDI_note_numbers_and_center_frequencies)

See LaunchKey_TwoTracks with Granultor sample to check this out


### Perhaps a better way: The Tuner

Another way is to simply use **the Tuner** I actually stumbled up on this after the video above. This can do it more quickly.

## Online Tutorials

[Getting started](https://www.youtube.com/watch?v=hkDtZLcuNLU
)

This is a fun tutorial, using the Viral Hop Hop LK project, included in the repo, downloadable from the site.

The 8x2 bank of pads in Stop mode can let you play/stop certain clips. Have fun navigating through this!

[Making Music with LaunchKey
](https://www.youtube.com/watch?v=d0Yrnrm8wcw)

[Arranging a track in LaunchKey](https://www.youtube.com/watch?v=AV9zscMDCck)

[Recording drums using Drum pad mode in Ableton Live
](https://youtu.be/oZjha_1c2os?list=PLPSFGKR8ZU4eDNdc0oeYMXdnKyNlG5L3Q
)

Less useful, but including it anyhow

[LaunchKey Demo
](https://www.youtube.com/watch?v=9FmL6Tj8yVw)




## Concepts

**Detuning** - when you slightly raise/lower the pitch of an instrument, usually in conjunction with other instruments, to create a chorus-like effect


**Instrument Rack** this is usually contained in an .adg file — a preset for Ableton. The .adg files **seem** to have 8 controls as standard, so these get mapped.

**Warping** this will let you keep the length of the sounds the same. They have different algorithms for warping.

**Mapping** ou can set up a map for effects racks, kind of like MIDI maps




## Hardware Controls

Detailed in the manual, in the repo. It took me awhile to find the right one! A lot of the online tutorials show other models, which gets confusing.


**Pitch wheel**: an immediate pitch shift, harkens back to old synths

**Modulation Wheel**: assignable control, use MIDI mapper

**Octave +/-** pretty self explanatory and just seems to work, press both to reset to 0. Shift-octave will transpose by one half step (one semitone)

**Shift** secondary selections, see notes in various places

**Settings** Navigate through different ones with up/down keys. Change values with left/right keys or the pads. Lots of global settings in there with details, check the manual

**Track <>** select different tracks, very useful, shift key does something here with track banking selections

The Encoder Mode bank: maps to default controls in that instrument rack

**Scale** Can change root note, major/minor. Still not sure how the scale settings affect Ableton.

**Chord** Perform chords that fit with the Scale you select. Not where I'm going at the moment.

**Arp** Arpeggiator, shift will Latch. This has all sorts of arpeggio controls, but I haven't gotten into 
these feaatures. Too advanced for now.

**Fixed Chord** allows you to assign a chord to the keys. More than I need for now.

**Encoder Modes** upper eight banks, hold shift key to activate these

Default encoder mode is Plug-in, which maps the eight pots to various effects in your chain. Press shift and the encoder up/down control to change the selected effect

Custom encoder modes. Each pots maps to a set of controls, so you have 4 assignable pots. Somewhere we can set these values. Keep in mind for later, for mapping more complex controls.

I don't really get the Mixer, Sends and Transport Encoder controls


### **Pad Mode**
Hold down Shift and you can choose the pad mode


Pad 9 - can go between Sequencer and Clip Mode=

**Clip Mode** is pretty great and you can trigger the clip bank with just the pads, navigating the 2 sets through the arrows to work with performance.

This could be really great for performing clips and testing them.

Remember, these are also mapped to MIDI, so we can essentially make a virtual deck in TouchDesigner as well.

Pressing the funciton key will let you go into **Stop Mode**, Mute, etc.

**Sequencer Mode** I dont really get this, need to watch some YouTube vids

**DrumPad Mode** (pad 10), can play a drum kit. It's a little weird because it goes through DAW Out, and not MIDI, but maybe I'm missing some routing information here 

up/down arrows move between the drum banks, so you could play with effects on multiple pads at once

I could see this being useful if you can link the encoder buttons to the effects racks.

The Pad Mode bank, can shift betwen tracks, you can also do this with the Track arrows

Up/down arrow keys to right of pads will let you navigate between clips in Session View, though two at a time get selected

**Capture MIDI** can capture MIDI sequences. I'm getting a little confused here. Why is this different from the record button?

**Metronome** pretty straightforward.

**Quantise** triggers quantize on last MIDI clip (still don't know what this is)


**Transport Buttons**: stop, play, record, loop, all are pretty straightforward

## LaunchKey_Template

Basic electric piano. Note that the Bluetooth speaker seems to have a lag, so plug it in.

By default, the 8 pots should control the 8 settings on the piano.

## LaunchKey_Granulator

Follows this tutorial
[Getting started](https://www.youtube.com/watch?v=hkDtZLcuNLU
)

Pretty cool, the controls automatically map to the granulator controls. That's pretty powerful for making noises!

The screen shows what's going on, too!

I don't understand how to do the tuning on the granulator synth at 3:53, but get the concepts

## LaunchKey_GranulatorModWheel 

Same as granulator, only uses the mod wheel in a MIDI map to control the echo effect

## LaunchKey_GranulatorScales

Added scales, but I cant seem to get the granulator to activate, knobs now do the scales instead.

To activate the granulator, press shift and the encoder up/down button to move between them.

## LaunchKey_GranulatorMeld

Two instruments, granulator and meld, still working on this

## LaunchKey_PianoAndDrums

Does both, so you can play in regular mode or shift to drum pad mode. Can do both at the same time, keys and pads.


## Useful things I learned

Arm tracks for recording (I already knew this)

Monitor needs to be set to **Auto** for playback to actually work.

Using the Viral Hip Hop LK template, provided in the video, I can do a fun clip mode mix and just press the pads.

## Questions


There are a a whole lot of custom modes, check out 12:00 [in this video](https://www.youtube.com/watch?v=hkDtZLcuNLU), probably more than I can get into at this point

Mostly it's applying the knowledge and practicing. Playing with templates like the [Shamaic Portals](https://www.florasynth.space/shamanic-portals) could be really fun. This would let me play with the clips live, maybe mod the parameters of the synths aloing the way.


