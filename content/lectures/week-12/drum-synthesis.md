---
title: "Drum Synthesis in Vital"
---

# Crafting a Full Drum Kit in Vital Synth

### 1. **Kick Drum**

A kick drum should have a deep thump with a quick, punchy impact.

- **Oscillator**: Set Oscillator 1 to a **sine wave** around 50-60 Hz to give the kick a solid low end.
- **Pitch Envelope**: Add a quick pitch modulation envelope to simulate the “thump.” Start from a slightly higher pitch and drop rapidly to the base frequency.
  - **Attack**: Instant (0 ms).
  - **Decay**: Short (30-50 ms) for a quick drop.
- **Amplitude Envelope**:
  - **Attack**: Instant (0 ms).
  - **Decay**: Short to medium (around 100 ms).
  - **Sustain**: Zero for a punchy cutoff.
  - **Release**: Short (30-50 ms) to ensure it doesn’t linger.
- **Distortion (Optional)**: Apply a touch of distortion for extra grit.

### 2. **Snare Drum**

The snare drum combines a tonal “body” and a noisy “rattle” to create that signature snare sound.

- **Oscillator 1**: Use a **sine or triangle wave** set around 150-200 Hz for the body.
- **Noise Oscillator**: Activate a **noise oscillator** to emulate the snare’s “rattle.” Use white or pink noise.
  - **Filter**: Apply a highpass filter to the noise oscillator to focus it in the midrange (2-8 kHz).
- **Amplitude Envelope (Tonal Layer)**:
  - **Attack**: Instant (0 ms).
  - **Decay**: Short (100-150 ms).
  - **Sustain**: Zero.
  - **Release**: Short (50 ms).
- **Amplitude Envelope (Noise Layer)**:
  - **Attack**: Instant.
  - **Decay**: Medium (150-250 ms).
  - **Sustain**: Zero.
  - **Release**: Short (50 ms) for a clean fade.
- **Reverb (Optional)**: Add a slight reverb to the noise layer for a realistic snare ambiance.

### 3. **Hi-Hats (Closed and Open)**

Hi-hats are sharp and metallic, primarily driven by noise.

- **Noise Oscillator**: Set this oscillator to **white noise** to emulate the crispness of hi-hats.
- **Filter**: Use a **bandpass filter** around 4-10 kHz with slight resonance to focus on the metallic frequencies.
- **Amplitude Envelope (Closed Hi-Hat)**:
  - **Attack**: Instant.
  - **Decay**: Very short (20-50 ms).
  - **Sustain**: Zero for a tight, quick cutoff.
- **Amplitude Envelope (Open Hi-Hat)**:
  - **Attack**: Instant.
  - **Decay**: Longer (150-200 ms) to let it ring out.
  - **Sustain**: Low for a sustained effect.
  - **Release**: Short (50 ms).
- **Reverb (Optional)**: Add a small amount of reverb to the open hi-hat for depth.

### 4. **Toms (Low, Mid, and High)**

Toms require a tonal, resonant sound with a slight pitch modulation.

- **Oscillator**: Use a **sine wave** at different pitches for each tom:
  - **Low Tom**: 100 Hz
  - **Mid Tom**: 200 Hz
  - **High Tom**: 300-400 Hz
- **Pitch Envelope**: Use a fast-decaying pitch modulation envelope to add impact.
  - **Attack**: Instant.
  - **Decay**: Very short (20-30 ms) for a quick drop.
- **Amplitude Envelope**:
  - **Attack**: Instant.
  - **Decay**: Medium (150 ms).
  - **Sustain**: Zero for a clean cutoff.
  - **Release**: Short (50 ms).
- **Filter (Optional)**: Apply a lowpass filter to roll off highs, giving the toms a rounded tone.

### 5. **Clap**

A clap sound is essentially a burst of noise with a staggered decay that mimics the sound of multiple hands clapping.

- **Noise Oscillator**: Use **white noise** to simulate the “slap.”
- **Filter**: Apply a highpass filter to remove low frequencies and focus on the mid-high range (2-5 kHz).
- **Amplitude Envelope**:
  - **Attack**: Instant.
  - **Decay**: Use a staggered decay with several peaks and drops to mimic layered claps.
  - **Sustain**: Zero.
  - **Release**: Short to avoid excessive ringing.
- **Reverb (Optional)**: Add a slight reverb for an ambient effect.

### 6. **Rim Shot**

A rim shot has a quick, bright attack with a woody resonance.

- **Oscillator 1**: Set to **triangle or square wave** at a high pitch (1-2 kHz).
- **Noise Oscillator**: Add a bit of filtered noise for extra sharpness.
- **Filter**: Use a highpass filter to focus the sound on mid-high frequencies.
- **Amplitude Envelope**:
  - **Attack**: Instant.
  - **Decay**: Short (around 50-100 ms) for a clean sound.
  - **Sustain**: Zero.
  - **Release**: Short.
- **Optional Reverb**: Use minimal reverb to avoid washing out the sound.

### 7. **Cowbell**

A cowbell has a metallic, resonant sound with a longer decay.

- **Oscillators**: Use **two sine waves** to create metallic overtones:
  - **Oscillator 1**: Set to around 400-600 Hz.
  - **Oscillator 2**: An octave or a fifth above (800-1200 Hz) for metallic resonance.
- **Amplitude Envelope**:
  - **Attack**: Instant.
  - **Decay**: Medium (100-150 ms) for resonance.
  - **Sustain**: Zero.
  - **Release**: Short to avoid excessive ring.
- **Bandpass Filter**: Use a bandpass filter to focus on the mid frequencies and add resonance for metallic character.

