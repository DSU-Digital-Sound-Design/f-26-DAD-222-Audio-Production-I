---
title: "More Vital Synth"
---

Last time we worked with the ADSR envelope. Today: thicker sounds from
multiple oscillators, the sampler, and Vital's effects. We'll build three
patches along the way.

## More oscillators

Turn on oscillators 2 and 3 and listen to what changes. They work exactly
like oscillator 1; the point is layering.

## Patch 1: Ghostly Choir

1. Set every oscillator to a sine wave (the first option under basic shapes).
2. Detune oscillators 2 and 3 slightly above and below oscillator 1.
3. Turn on the filters.
4. Save the patch. Export it if you want to share it.

What to notice:

- Does the sound match what you expected?
- Look at the spectrogram. Not much visible change, right? Most of the
  detuning effect is psychoacoustic; your ears hear more than the meter shows.

## Patch 2: Chorus Bass

1. Start from a fresh patch.
2. Sawtooth wave on both oscillators.
3. Set oscillator 2's pitch to -12, an octave down.
4. Route oscillator 2 to Filter 1.

## Patch 3: Adding the sampler

1. Open the sampler.
2. Pick a built-in sample or load your own.
3. Try the playback buttons: loop, play-then-reverse, play from the previous
   stop point.

Two practical uses: textural samples add grit under a synth, and a percussive
sample gives your envelope a click at the front.

## Parameters worth knowing

- **Voices**: how many notes can sound at once
- **Bend**: pitch bend range for a MIDI keyboard
- **Vel Trk**: makes Vital respond to velocity
- **Spread**: stereo width
- **Glide**: slides one note into the next over the glide time

## Effects

**Chorus** is a delay with pitch modulation added. The delay modulation
frequency sets how long before the modulation repeats; Delay 1 and Delay 2
set the delay times for the separate chorus voices.

**Multi-band compressor** compresses different frequency bands separately.

**Flanger and phaser** are cousins of chorus that modulate filters instead of
pitch. The flanger plays the sound against a slightly delayed copy of itself.
The phaser plays it against a filtered copy.

For each one: turn the knobs and listen. The parameter names matter less than
hearing what they do.
