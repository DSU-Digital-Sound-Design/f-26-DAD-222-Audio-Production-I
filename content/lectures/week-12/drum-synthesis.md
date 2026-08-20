---
title: "Drum Synthesis in Vital"
---

# Building a Drum Kit in Vital

Every drum here is the same recipe: an oscillator or a noise source, an
amplitude envelope with zero sustain, and sometimes a fast pitch envelope for
the attack. Once the kick makes sense, the rest are variations.

The values below are starting points, not answers. Get each drum close, then
push the settings around until it sounds like yours.

## 1. Kick drum

A deep thump with a fast, punchy attack.

- Oscillator 1: sine wave around 50-60 Hz for the low end.
- Pitch envelope: this is the "thump." Start the pitch slightly high and drop
  it fast to the base frequency.
  - Attack: instant (0 ms)
  - Decay: 30-50 ms
- Amplitude envelope:
  - Attack: instant
  - Decay: around 100 ms
  - Sustain: zero, so it cuts off instead of hanging on
  - Release: 30-50 ms
- A touch of distortion adds grit if the kick feels too polite.

## 2. Snare drum

Two layers: a tonal "body" and a noise "rattle."

- Oscillator 1: sine or triangle around 150-200 Hz for the body.
- Noise oscillator: white or pink noise for the rattle. Highpass the noise so
  it sits in the 2-8 kHz range.
- Amplitude envelope, tonal layer:
  - Attack: instant · Decay: 100-150 ms · Sustain: zero · Release: 50 ms
- Amplitude envelope, noise layer:
  - Attack: instant · Decay: 150-250 ms · Sustain: zero · Release: 50 ms

  The noise decays slower than the body. That difference is most of what makes
  it read as a snare.
- A little reverb on the noise layer sells the room.

## 3. Hi-hats, closed and open

Almost pure noise. The envelope is the whole instrument.

- Noise oscillator: white noise.
- Filter: bandpass around 4-10 kHz with slight resonance for the metallic ring.
- Closed hat: instant attack, very short decay (20-50 ms), zero sustain.
- Open hat: instant attack, longer decay (150-200 ms), low sustain,
  50 ms release.

Same patch, two envelopes. Save both.

## 4. Toms: low, mid, high

A kick that got tuned up, basically.

- Oscillator: sine wave, one pitch per tom:
  - Low: 100 Hz · Mid: 200 Hz · High: 300-400 Hz
- Pitch envelope: instant attack, very short decay (20-30 ms) for the impact.
- Amplitude envelope: instant attack, 150 ms decay, zero sustain, 50 ms release.
- A lowpass filter rounds off the tone if the toms sound too plasticky.

## 5. Clap

A burst of noise with a staggered decay. Real claps are many hands landing at
slightly different times, and the stagger is what fakes that.

- Noise oscillator: white noise.
- Filter: highpass, keeping the 2-5 kHz range.
- Amplitude envelope: instant attack, then a decay with several small peaks and
  drops rather than one smooth slope. Zero sustain, short release.
- Slight reverb helps; claps sound wrong bone-dry.

## 6. Rim shot

Quick, bright, woody.

- Oscillator 1: triangle or square, pitched high (1-2 kHz).
- Noise oscillator: a little filtered noise for the snap.
- Filter: highpass, keeping mid-highs.
- Amplitude envelope: instant attack, 50-100 ms decay, zero sustain, short
  release.
- Keep reverb minimal or the transient washes out.

## 7. Cowbell

Metallic and resonant, with a longer decay than anything else in the kit.

- Two sine oscillators make the metallic overtones:
  - Oscillator 1: around 400-600 Hz.
  - Oscillator 2: an octave or a fifth above, 800-1200 Hz.
- Amplitude envelope: instant attack, 100-150 ms decay, zero sustain, short
  release.
- Bandpass filter with some resonance focuses the mids and pushes the metal.
