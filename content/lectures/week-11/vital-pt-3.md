---
title: "Vital Pt 3 - Modulation"
---

# Matrix and Modulation, LFO and Envelopes

## LFO

As you play any note notice that the LFO is actively moving through a triangle oscillator. It isn't having an effect yet because we need to connect it to a parameter.

Drag the LFO icon down to the cutoff frequency control of Filter 1. Now notice that you can control this cutoff frequency parameter with the LFO. Notice the circle that now connects the two parts of the synth. This allows you to change the amount of modulation. You can also think of this as the _strength_ of the modulation. Now experiment with the frequency of the LFO.

As with our audible oscillators, we're not limited to basic oscillator shapes for our LFOs. Experiment with some of the other oscillator shapes that can give the sound a more rhythmic quality.

Currently, our modulation only acts in a positive direction, from the start of the parameter upward. We can change that and modulate +/- from our starting position by right clicking on the amount icon and choosing "make bipolar."

> All of these options can be more clearly seen in the matrix tab. Click on that now.

## Envelopes

Reinitialize the patch.

If we want a modulation that has a fixed duration and shape we can use the envelopes. We can either reuse the amplitude envelope, or use envelopes 2 or 3. For this example we'll use envelope 2 and connect it to the filter cutoff. Now the filter opens every time we trigger a note, creating an interesting effect.

## Random

Similar to LFOs with a noise oscillator.

## Keyboard section

MIDI note parameters can be mapped to synthesis parameters in Vital. This includes note, velocity, lift, oct note, pressure, slide, stereo, and random.

## Macros

Allow you to control multiple parameters with one knob. Useful when you start making your own patches.

## Advanced tab - Unison settings

In the advanced tab you can control more aspects of how the unison spread works.
