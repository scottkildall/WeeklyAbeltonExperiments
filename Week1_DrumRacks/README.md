# Week1_DrumRacks

The idea here is to explore the drum kits in Ableton and develop some templates for play and use


## History

[History of the 808]()





## Online Tutorials

[Building a starter drum kit](https://www.youtube.com/watch?v=oVeds9wvMcI
)


[This is a great tutorial](https://www.youtube.com/watch?v=MJ8fUDoHAQ8
), but is for Ableton Live 11, so there are some changes with the UI that don't really make sense.


Like the sound of something?
[Here is a guide on how to extract the samples as a drum kit](https://www.youtube.com/watch?v=4DxXi1DQO7k). This isn't the best tutorial with it's portrait view and I was able to replicate the steps in Create Your Own Drum Kit


[Copy to siblings feature](
https://www.youtube.com/watch?v=QhPMuOLZCSg)


[MIDI Fighter for performance
]()

[Add effects to chain list](https://www.youtube.com/watch?v=-fqovGQ0Bqk
)

## Controllers

You can play these without controllers, but the one that I have been developing these from is the MIDI Fighter Twister, which has knobs that also function as switches 


## Useful things I learned

#### Drum rack chain list

Each pad can have its own chain list, so that one pad can trigger multiple samples at once.

You can have a drum rack with empty slots, so for example, a kick drum can have another chained drum effect on that, leaving empty slots elsewhere.

Or an instrument, so that you can have multiple notes playing on one pad, alongside the drum kit

[You can also add effects to the chain list](https://www.youtube.com/watch?v=-fqovGQ0Bqk
), but I don't entirely get it.

#### Using .adg files

I didn't get this fully, but .adg files are an Ableton Device Group, this is a "rack", in can be an instrument rack, audio effect rack, any kind of modular rack. They can be dragged onto specific drum pads, too, so that your instrument racks can be treated like a drum pad. 


#### Timing Shifting

Add a delay effect to one of the drum pads, this gives it a slightly more human feel.

#### Copy to Siblings

Change one effect on a drum pad, and you can copy that change to all of its silbings (same vid linked above)

[https://www.youtube.com/watch?v=QhPMuOLZCSg
](https://www.youtube.com/watch?v=QhPMuOLZCSg)

#### Chaining

I think I just got the tip of the iceberg here, but you can chain kits together, so that one hit will trigger on multiple kits.

What seems useful here is that one kit could contain a 16-pad drum rack, and other could just have 1 pad for, say the kick.


## Live Sets


### DrumKit_Template

Simple drum kit, no effects. Drag a drum kit on top of this one.

The patterns themselves are super not interesting.


#### Tips

You can copy the sound from a kit into another kit, click on the pad for that

### DrumKit_Minimum

Just four samples, with on the bottom rack, with the top buttons controlling mixes and effects. Use with MIDI Fighter Twister



### DrumKit_PadShift

Simple 16-pad drum kit with one beat. The lower-left knob of the MIDI Twister Fighter is mapped to the Pitch MIDI effect, which changes the note pattern of the entire drum rack. 

Could add more channels for a pretty fun little performance-thing.

### DrumKit_KickEffect

This shows how you can have an effect on one pad, so I have one kick without an effect, and a 2nd kick which has an echo effect timed to an LFO, to create the start of a fun rhythm.


### DrumKit_Chaining

Shows two full drum kits, chained together to produce different effects.

Note the beat pattern is sloppy, 540 bpm with lots of space between the beats. I did it wrong in the first place, but don't want to re-do it. 

AG_Techno is the first kit
DK 2 is the second one, and *only* uses the kick pad.

### DrumKit_Psycho

This uses the a custom kit I bough from Beat Tools, so it mayt not work properly if you don't have the Beat Tools Drum Kit.

It has the some problem as the 540bpm above. Oooops.


### DrumKit_LoopRandom

A randomizer that affects the entire kit, so this goes behind all the pads.

It's ugly and has the 540bpm problem above.

### DrumKit_Adv

This uses Ableton Device Presets (.adv) for single drum pads. 

Acid Kick
Kick Complex
Plate Kick
Bells Sun

These are all .adv files.

I don't entirely get how this works, but it's pretty great, you can just drag the .adv files a pad, and presto

### Create Unique Drum Kit

From a small segment of music, like 5 seconds or so, you can extract the samples from this, and then use Ableton's AI to get "Similar" sounds from your drum kit library.

Not only this, but you can get the beat pattern, too! Whoa.

Also has the 540bpm problem.

#### Steps 

Import an mp3 into Arrangement View
	(note: you could even break these out into stems to do those)

Double-click on title bar to show the clip in the lower pane

Set start end and points in lower frame

Right-click and choose "Crop Sample" to get the segment you want

Control-click in upper pane and choose "Consolidate"

Control-click and choose "Slice to new MIDI Track"

You should see a drum kit with whatever number of slices are in that short clip

Switch to Session View, and the drum kit is active!

Weird double-reverse trick to get the actual sound

To get the Beat Pattern, after you Slice to MIDI, double-click on the title bar to get the beat pattern, then you can get beat pattern.

You can copy and paste the actual beat pattern into Session View

**could you use this with DJ-stem separation software? 
** maybe?

### Other files

173_cantons-retro-bleepy-DnB.wav

I use this in the Create Unique Drum Kit Live Set, this is from [Canton Becker's Sample Swap library](https://sampleswap.org/artist/canton)



Questions:
• Why is Next Similar Grayed out?
• Would there be a way to get a drum pattern from this

• Convert Drums to New MIDI Track, always seems to make it into a 606
• Convert Harmony to New MIDI Track, always seems the same
• Convert Melody to New MIDI Track, always seems the same





## Nice Features

The similar swap button will load samples that are like yours into the kit, so if you find something you like, then you can work with that idea and develop it.

## Questions



How to swap between drum kits?

How to get a pre-existing beat pattern?

How do you get notes with a drum kit, for example an 808?


Some 808 stuff

https://www.youtube.com/watch?v=PqN3qcarcuY

https://www.youtube.com/watch?v=h0Z3MFLLEdA


 
### Things I never really figured out



What does Extract grooves do?

Should be able to transpose pitches of different drum pads


What are .alc files and what do they do? 
ALC = Ableton Live Clip, you could tie the MIDI clip to tempo, color, etc. that is lnked to Ableton. Check out the Clip Library is advicesed for this.

How to use a controller to actually perform. I programmed some of the MIDI maps to select different sequences, but this seemed pretty clunky, and I couldn't get the beats to align properly from one pattern to the next when I did this.

I still don't quite understand .adv and .adg files. I know they are presets and racks, but don't get how to make these on my own yet. Future areas of investigation for sure.

### More Links


Drum Machine: just the samples themselves, with the effects

How to play a bass-line


Good rundown on the drum rack
https://unison.audio/ableton-drum-rack/

Add effects to a drum rack
https://www.youtube.com/watch?v=-fqovGQ0Bqk
