# Week3_EQ





## History



## Tutorials

Super basic starter

http://youtube.com/watch?v=XfQAxB2guOU

Fab Filter vs EQ Eight

https://www.youtube.com/watch?v=ITEHOBdGBFM

https://www.youtube.com/watch?v=jl8y51bouno

EQ Eight - focusing on the midrange — the "magic" is in the midrange

https://www.youtube.com/watch?v=0-4MBrbxmMA

## Concepts

low (bass) is what you feel
mid gives you the presence
high is the brightness/detail

We tend not to want to have competing sounds, for example, taking out the low end of a snare drum.

Reset your ears. Find what you like in terms of EQ, reset it and then set it again.

Figure out your two ends of the frequency band — when you're not doing enough and when you're doing too much. You can only do this by experimenting.

Listen for separation of the instruments and clarity.

## Tips & Terms

Having a knob selected and pressing backspace will reset it to zero

Sweep is when you move an EQ setting along the frequency bands

A/B something = testing two examples

Surgical EQ-ing is the term used for the attempt of adjusting a specific frequency without touching the frequencies next to it.

## Tools

Spectrum is a utility that you can put at the end of your instrument that shows helpful decay patterns.

## EQs

### Channel EQ

very simple, can adjust where the mids. Not complete enough though

### EQ Eight

sort of the right one.

Also has the ability to "solo" a node that you are working on. 

You can also chain EQ Eight chains to do stuff like a low-pass, mid-pass etc

Use the Freq dials for gain adjust. Could we do a MIDI Fighter mapping to these controls?

There is a good workflow with Music is the Midrange filters to focus on midrange sounds only.

Expanded View is great, can see the frequency numbers and you can dial it all in with a knob.

Here is a rundown on EQ Eight and how to use it.

[https://theaudioowl.com/ableton-live/ableton-eq-eight-how-to/#surgical-eq-ing-with-eq-eight
](https://theaudioowl.com/ableton-live/ableton-eq-eight-how-to/#surgical-eq-ing-with-eq-eight)


The Q-knob is key here, changes the slope of the filter

Audition Mode, very cool. Press the headphone icon, it turns blue and you can see that just that EQ effect.

## Dynamic EQ trick

Use an Envelope Follower with EQ Eight. You can map across racks to do this!

Sort of like a compressor, but different, more specific.

## EQ By Note

Nice little trick to get ambient frequencies going

[https://www.youtube.com/watch?v=B4rR0kNpZPU
](https://www.youtube.com/watch?v=B4rR0kNpZPU)

Downloaded their pack for $5

[https://www.subaqueousmusic.com/live-rack-for-eqing-by-notes/
](https://www.subaqueousmusic.com/live-rack-for-eqing-by-notes/)
**About each filter**

[https://ask.audio/articles/intricate-equalization-inside-ableton-lives-eq-eight
](https://ask.audio/articles/intricate-equalization-inside-ableton-lives-eq-eight)

High and Low pass filters
x4 slopes for extreme high and low pass for each

For most boosting or cutting, Bell is probably sufficient, but for complete removal at specific frequencies, Notch can eliminate selected ranges entirely. The shelving options provide full-band vintage emphasis above the selected frequency with High Shelf, or below with a Low Shelf; a slight dip before the shelf’s boost, or conversely a slight peak before a shelf is pulled down, emulates vintage shelving curves for more natural sonic results at extreme settings.


### FabFilter Pro-Q 3

Piano roll feature is kind of cool. Has a very cool node-grabbing feature, has a much more refined system than EQ Eight. 

But it is expensive, costs $179.

Has much better visual information.

Show collisions can give you an idea of where colliding frequencies work.



### Sidechain Compressors

aka Side Chaining


This one is good

[https://www.youtube.com/watch?v=YtBmWoOba8s
]()

Have a trigger sound and then that 

More complicated

[https://www.youtube.com/watch?v=f6PKAqLtXXQ
]()

## Live Sets

### EQ_DrumKit

EQ Eight is on each drum pad. Very helpful for just looking at the pads and seeing their frequencies. What I also like is that you can take the same pad an apply different EQ settings to it, to get a different feel. Each pad has it's own EQ.

Here, the MIDI Fighter Twister was very useful.

### EQ_Dynamic

This uses the Dynamic EQ trick, but for some reason, I can't see the EQ value going up and down.

### EQ_Notes

Shows this with the dynamic EQ

### EQ_SideCompression

A simple version of some beats I put together. It's not a great example but is audible.

## Questions

With videos on specific filters

Not sure how to EQ an entire mix / session. My workflow is to create notes for playback through MIDI, not a comnpleted soundscape. Need to delve into this.


What the different types of EQ are on EQ Eight? It seems a little odd to play with.


How to EQ a sample frequency that shifts. See LaunchKey_TwoTracks and the disabled EQ on the first track.

This may solve this

https://ask.audio/articles/intricate-equalization-inside-ableton-lives-eq-eight

### Things I didn't explore


Could you use a controller to map the EQ settings? Would a MIDI map copy-and-paste these okay?


Mid/Side EQing. You can EQ the mono/stereo separately. I didn't really get there, but am curious though.

Same with Oversampling.

EQing Vocals:
[
https://www.musicguymixing.com/eq-vocals-ableton/](https://www.musicguymixing.com/eq-vocals-ableton/)


## Compressors


Comprehensive Tutorial here — The first half seems to be pretty solid, but secord part goes into the weeds.

[https://www.youtube.com/watch?v=StJ1mbjqTnM
]()

Quick video, annoying guy, but helpful. Goes through the different modes of the Compressor

[https://www.youtube.com/watch?v=LEhQNUVaY70
](https://www.youtube.com/watch?v=LEhQNUVaY70)


Trying to work with these 4 things:

* Threshhold
* Ratio
* Attack
* Release
* Makeup Gain (bonus)

### Threshhold

Compressor gets engaged when you go above a certain level


### Ratio

How much compression is applied to things above that trigger point.

### Attack

Fast attack will hear more of that compression; slow attack will hear less of it, more sound will come through.

### Release


Quick release will be more punchy, slow release will be smoother

### Makeup Gain

Often good to turn this off, as it can just get louder, but not actually compressed.


### Basic Compressor

seems pretty straightforward

### Glue Compressor

Provides two things:
- Soft Compressor
- Adds "color" to your sound

Really just an alternate to the Basic Compressor. Will have similar results. Could just sound a little bit better.

One commment here...

Glue compressor emulates a feedback compressor topology, whilst stock compressor is a feedfoward design. A feedback compressor first compresses the incoming audio before sending it to the internal sidechain (none of which we hear), it then "feeds back" the compressed audio to the detection circuit, therefore the compression action (for the signal we do hear) is based on a smoother pre-compressed waveform than the one we actually put into the compressor. This all makes for a smoother, less spikey compression envelope (perfect for glueing bussed elements with each other) which doesn't clamp down on peaks as aggresivley, making it ideal for shaping your drum bus dynamics (for example) without squashing the life out of the transients.

An more advanced tutorial, here:

[http://youtube.com/watch?v=ABc4NXHLdaQ
](http://youtube.com/watch?v=ABc4NXHLdaQ)

### Multiband Compressor

Separates signal and compresses each one, more surgical.

Pretty useful for solo out different bands, and figuring out the **crossover** point.

I didn't go down the rabbit hole here, but I get it.

[https://www.youtube.com/watch?v=QmWkggkC4yM](https://www.youtube.com/watch?v=QmWkggkC4yM)


### EQ_Composition

Shows glue compressor with spectrum before and after. It's subtle, but you can see it.


### Order of operations

Do you EQ or Compress first?

[https://korneffaudio.com/do-you-put-the-damn-compressor-before-or-after-the-eq/
](https://korneffaudio.com/do-you-put-the-damn-compressor-before-or-after-the-eq/)
Should sidechain go before or after EQ? If you're using an EQ to edit a sound, it should come before sidechain compression 


