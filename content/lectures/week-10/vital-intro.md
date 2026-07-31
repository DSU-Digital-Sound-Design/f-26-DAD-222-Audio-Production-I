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

---

## 0) Reinitialize the patch

1. Open the preset menu (click the current preset name at the top).
2. Choose `Initialize Patch`.

Result: Vital loads a simple sawtooth with neutral routing and no effects. This gives a predictable starting point for learning and repeatable results in class.

---

## 1) Create your first patch

### 1.1 Explore the oscillator

1. Go to `Osc 1`. You should see a default saw.
2. Move the `Position` slider (right of the waveform) to audition a few basic waveforms: `Sine`, `Square`, `Triangle`. Listen for how the harmonic content changes.
3. Choose a more complex wavetable (e.g., `Quad Saw`, `Stabbed`, or `Harmonic Series`).
4. Move the `Position` slider (right of the waveform). This scans through frames of the wavetable and morphs the shape in real time.


### 1.2 Pitch and fine tuning

1. Locate `Semitone` and `Cents` for `Osc 1`.
2. Try transposing by ±12 semitones to understand range and octave placement.
3. Nudge `Cents` by ±3–10 to introduce gentle detune. This becomes more noticeable once unison is enabled.

Guideline: Keep extreme detune for later; small offsets stack well when layering other oscillators.

### 1.3 Add a filter (timbre shaping)

1. Find `Filter 1`. If it looks greyed out, click the small activation dot next to `Filter 1`.
2. Choose a type. Start with `Analog: 12dB` or `Analog: 24dB` for classic subtractive shaping.
3. Turn `Cutoff` down to remove highs; sweep to learn the range.
4. Raise `Resonance` to emphasize frequencies at the cutoff for more character.

Listening targets:

* Lower cutoff + moderate resonance for mellow pads.
* Higher cutoff + low resonance for brighter leads and plucks.

### 1.4 Thicken with unison

1. In `Osc 1`, set `Unison Voices` to 4–5.
2. Increase `Unison Detune` until you hear width, then back off slightly to avoid chorusing blur.
3. Use `Level` to maintain headroom; unison adds gain.

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

1. Go to the main amplitude envelope (often `Env 1` or clearly marked Amp envelope).
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

1. Open the preset menu and choose `Save`.
2. Use a descriptive name and category, e.g., `DSU_FirstPatch__Pad__WarmSweep__v1`.
3. Increment versions as you iterate: `v2`, `v3`, etc.

Documentation tip: In the preset comments (if available), jot key settings such as cutoff range, unison voices, and morph mode. Future you will thank present you.

---

## 3) Suggested 20-minute practice flow

1. Reinit and build a pluck (5 min): low sustain, short decay, low release, low-pass filter with moderate resonance.
2. Duplicate the patch into a pad (5 min): longer attack/release, lower cutoff, gentle unison detune.
3. Add motion (5 min): pick one spectral morph and one wave morph; move each manually to find musical ranges.
4. Commit and label (5 min): save two versions with clear names and comments.

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

## Assignment for the remainder of class

Create at least three distinct presets from this starting workflow:

* One pluck, one pad, one lead or keys-type patch.
* Each must demonstrate a different filter approach and a different morph mode.
* Save with descriptive names and categories, and include a one-line comment describing the intended musical role.


