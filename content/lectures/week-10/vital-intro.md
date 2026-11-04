---
title: "Vital Synthesizer: First Patch Creation"
date: 2024-06-15
draft: false
---

## What you’ll accomplish

By the end of this demo you will:

* Initialize Vital to a clean state.
* Choose and morph a wavetable in Oscillator 1.
* Tune and thicken the sound with unison.
* Shape timbre with a filter.
* Sculpt dynamics with the amplitude envelope.
* Save your first custom preset.

Tip: UI labels below appear in code style (for clarity), e.g., `Osc 1`, `Filter 1`, `Cutoff`.

For November 4, follow the [guided pluck demo](/lectures/week-10/electronic-sound-production/#/pluck-demo) and save one practice patch. Turn it into a pad if time permits. The oscillator, unison, and morphing sections below are reference material for further exploration. No additional graded submission is required today.

---

## 0) Reinitialize the patch

1. Right-click the current preset name at the top.
2. Choose `Initialize Preset`. A normal left-click opens the preset browser instead.

Check the starting state: Oscillator 1 should be a sawtooth, with oscillators 2 and 3, the sampler, and effects off. Use one unison voice. If your version has a custom default preset, confirm these settings before continuing.

---

## 1) Create your first patch

### 1.1 Explore the oscillator

1. Go to `Osc 1`. You should see a default saw.
2. Click the wavetable name above Oscillator 1's waveform and load `Basic Shapes`. The initialized saw alone does not provide all the basic waveforms when you move its position slider.
3. Move the `Position` slider to the right of the waveform to audition sine, square, and triangle shapes. Listen for how the harmonic content changes.
4. For optional exploration, choose another wavetable from your installed library and move its `Position` slider. This scans through the wavetable's frames. Available wavetable names depend on the content you installed.


### 1.2 Pitch and fine tuning

1. Locate the two tuning values under `Pitch` for `Osc 1`: semitone transposition on the left and fine tuning in cents on the right.
2. Try transposing by ±12 semitones to understand range and octave placement.
3. Nudge the cents value by a few cents, then return it to zero. This shifts the pitch of the whole oscillator. Relative detuning between two oscillators, or between unison voices, creates beating and thickening. Use `Unison Detune` for the unison example below.

Guideline: Keep extreme detune for later; small offsets stack well when layering other oscillators.

### 1.3 Add a filter (timbre shaping)

1. Find `Filter 1`. If it looks greyed out, click the small activation dot next to `Filter 1`.
2. Confirm that the `OSC1` input button in Filter 1 is enabled and Oscillator 1's routing selector reads `Filter 1`.
3. Choose `Analog: 12dB` or `Analog: 24dB` and set the filter's blend control to its low-pass end. Check that the response graph passes lows and slopes down toward the highs.
4. Start with cutoff around 2 kHz and low resonance. Hold a saw note and lower cutoff to remove highs, then raise it again. If nothing changes, recheck the filter's power and `OSC1` input.
5. Raise `Resonance` to emphasize frequencies at the cutoff for more character.

Listening targets:

* Lower cutoff + moderate resonance for mellow pads.
* Higher cutoff + low resonance for brighter leads and plucks.

### 1.4 Thicken with unison

1. In `Osc 1`, set `Unison Voices` to 4–5.
2. Increase `Unison Detune` until you hear width, then back off slightly to avoid chorusing blur.
3. Watch the output meter and use `Level` to maintain headroom as the sound changes.

Rule of thumb: If your meter is peaking red, lower oscillator or master levels now to prevent clipping later.

### 1.5 Morph for motion and color

Vital offers two broad families of warp/morph behavior. Your skin/labeling may present these as spectral and wave morph modes.

1. Spectral morphing (e.g., `Form Scale`, `Smear`, similar options):
   * These reshape the harmonic spectrum.
   * Try subtle amounts first; extreme values can hollow or smear the tone.
2. Wave morphing (e.g., `Sync`, `Formant`, `Bend`, `Squeeze`):
   * These transform the waveform geometry itself.
   * Start with `Sync` for bright, harmonically rich sweeps.
   * Move the morph amount while holding a note to hear the motion.

Creative approach: Pick one spectral and one wave mode you like; note the ranges that sound musical for later modulation.

### 1.6 Shape loudness with the amplitude envelope

1. Select `Env 1`, which controls amplitude in Vital.
2. Set ADSR:
   * `Attack`: 0–10 ms for plucks, longer (100–800 ms) for pads.
   * `Decay`: time to fall from peak to sustain.
   * `Sustain`: the level held while the key is down.
   * `Release`: tail after key-up; match to the role (short for tight, long for ambient).
3. Explore `Hold` and `Delay`:
   * `Hold` maintains peak briefly before decay.
   * `Delay` postpones the envelope start for staggered or swelling entries.

Starting recipes:

* Percussive pluck: Attack ~1 ms, Decay 150–300 ms, Sustain 0–10%, Release 80–150 ms.
* Smooth pad: Attack 200–600 ms, Decay 1–2 s, Sustain 60–80%, Release 400–1200 ms.

---

## 2) Save and version your work

1. Click the save icon beside the preset name to open the preset-saving dialog.
2. Use a descriptive name and category, e.g., `DSU_FirstPatch__Pad__WarmSweep__v1`.
3. Increment versions as you iterate: `v2`, `v3`, etc.

After saving, reload the preset to confirm it recalls your settings. Save the REAPER project too; the project and the Vital preset are separate files.

---

## 3) Practice for November 4

1. Build a pluck with one saw oscillator, one unison voice, and no effects. Enable Filter 1, confirm its `OSC1` input, and use a low-pass response with cutoff around 2 kHz and low resonance.
2. In `Env 1`, set delay and hold to zero, attack to 5 ms, decay to 250 ms, sustain to 0%, and release to 100 ms. Hold a note and check that it fades while the key stays down.
3. Save as `YourName_Pluck_v1`.
4. If time permits, keep the oscillator and filter unchanged and make a pad. Set attack to 400 ms, sustain to 70%, and release to 800 ms. Leave decay at 250 ms and save as `YourName_Pad_v1`.
5. Explain how attack changes the beginning and release changes the tail. Compare both patches at a comfortable listening level.

---

## 4) Common pitfalls and quick fixes

* Sound is dull or lifeless: raise `Cutoff`, lower `Resonance`, or reduce extreme spectral morph amounts.
* Sound is harsh: lower `Cutoff`, reduce `Unison Detune`, back off morph amounts, or reduce oscillator level.
* Muddy low end: high-pass the signal using `Filter 1` or reduce unison voices; ensure `Release` isn’t too long.
* Clipping: lower `Osc 1 Level`, check master output, and avoid stacking high unison with high morph amounts at full level.

---

## 5) Stretch goals (if you finish early)

* Map the `Position` slider to a macro and move it while playing for expressive movement.
* Add `Osc 2` one octave up, lightly detuned for sheen; rebalance levels.
* Try a `Band Pass` filter for focused mid textures.
* Light reverb or delay can add depth; keep effects subtle so you can hear the core synthesis choices.

---

## Before you leave

Confirm that your pluck preset is saved and that you can explain one filter choice and one envelope choice. Save the pad too if you made one. These are practice patches that you can develop for Project 5. Modulation begins Friday, November 6.


