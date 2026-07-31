---
title: "Modulation in Vital: Design Your Own Patches"
summary: "Learn practical modulation techniques in Vital (LFOs, envelopes, performance sources, and meta-modulation) and build original, performance-ready patches through short demos and guided labs."
tags: [synthesis, vital, modulation, sound design]
---

## What you’ll learn

* What modulation is and why it matters for musical movement
* How to assign LFOs, envelopes, and performance sources to multiple targets
* How to shape depth, polarity, and response curves with the Mod Matrix and remap
* How to build three original patches showcasing different modulation strategies

---

## Quick refresher

Modulation means changing a parameter over time. In Vital you can target almost anything: oscillator pitch, filter cutoff, wavetable position, phase, pan, FX mix, and more. Drag a mod source onto a target to assign it, then refine the amount in the Mod Matrix.

Resource: Learning Synths – LFO
[https://learningsynths.ableton.com/en/lfos/change-that-repeats](https://learningsynths.ableton.com/en/lfos/change-that-repeats)

---

## Core concepts

### LFOs for movement

* Shapes affect feel: sine is smooth, triangle is linear, saw ramps, square toggles, stepped and drawable shapes create custom patterns.
* Rate can be free (Hz) or tempo-synced (note values).
* Retrigger determines whether the LFO restarts per note or free-runs for ensemble wobble.
* Envelope mode turns an LFO into an envelope-like contour for hits and rises.
* Try routing one LFO to two different targets with different depths for correlated motion without chaos.

### Envelopes for gestures

* Use extra envelopes beyond the amp envelope for one-time gestures: filter swells, spectral sweeps, transient emphasis.
* ADSR sets the time profile. Map envelope amount to shape how dramatic the gesture is.

### Performance sources

* Velocity, key track, mod wheel, and aftertouch shape modulation in a musical, performer-driven way.
* Examples: velocity to filter envelope amount for dynamic brightness; mod wheel to LFO amount for live intensity; key track to filter cutoff for natural brightness up the keyboard.

### Mod Matrix and remap

* The Mod Matrix is where amounts, polarity, and scaling live.
* Remap curves shape how the modulator responds across its range, useful for keeping extremes playable.

### Modulating a modulation

* Meta-mods add expression: mod wheel to LFO depth, velocity to LFO amount, key track to LFO rate, envelope to filter resonance amount, and so on.

---

## Short demos to mirror in class

Each takes only a couple minutes. Follow along and save the patch version after each step.

### Demo A: Sidechain-style pump

1. Start with a simple bass or pad.
2. LFO tempo-synced to 1/4.
3. Route LFO to amp level for a gentle dip.
4. Use remap to avoid complete silence at the bottom of the dip.
5. Map mod wheel to LFO amount for live control. Or draw in mod wheel automation.

Listen for how shape and depth change groove.

### Demo B: Evolving timbre pad

1. Two different wavetables; slight detune for width.
2. Env 2 to wavetable position on both oscillators with different depths.
3. Very slow LFO to filter cutoff (2–4 bars).
4. Subtle LFO to pan for stereo bloom.
5. Aftertouch increases the filter LFO amount for expressive swells.

Listen for long-form motion plus performable intensity.

### Demo C: Pluck with bite

1. Short-decay envelope to filter cutoff for bright attack.
2. Tiny, fast LFO to fine pitch or phase for shimmer.
3. Velocity to filter envelope amount so touch changes tone.

Listen for transient character versus body.

---

## Guided practice labs

### Lab 1: Rhythmic filter bass

* Oscillator: saw or square.
* Low-pass filter around 200–600 Hz.
* LFO 1 to filter cutoff, tempo-synced. Explore shapes.
* Mod wheel to LFO 1 amount.
* Optional: light drive or compressor post-filter.

Goal: two short renders at different LFO depths using the mod wheel.

### Lab 2: Evolving texture pad

* Two wavetables; slight detune.
* Env 2 with slow attack and long release to wavetable position.
* Very slow LFO 2 to filter cutoff and small amount to chorus mix.
* Key track to filter cutoff for brightness up the keyboard.

Goal: render moving from low to high register to show key tracking.


### Lab 3: Modulate a modulation

Pick any previous lab and add one meta-mod.

* Examples: mod wheel to LFO rate; velocity to LFO amount; key track to envelope sustain.
* Use the Mod Matrix remap to keep extremes musical.

Goal: render a sweep demonstrating the controller you chose.

---

## Practice

Take the rest of class and finish the patches. Share them in class towards the end. 

