
## Class Exercise: Recreate That Sound — Ear Training in Synthesis

**Duration:** 50 minutes
**Software:** Vital
**Learning Focus:** Listening analysis, synthesis fluency, modulation understanding, and reverse-engineering of sounds.

---

### 1. Introduction and Setup (5 minutes)

**Goals**

* Explain: students will hear several short synthesized sounds and try to rebuild them in Vital.
* Encourage note-taking on perceived waveform, filter type, envelopes, modulation, and effects.
* Ensure everyone has Vital open in a DAW and a default patch loaded.

---

## 2. Example Round 1 – Bright Filtered Lead (10 minutes)

**Concept:** Subtractive synthesis and envelope modulation of filters.
**Reference description:** Bright sawtooth lead with filter envelope sweep and mild resonance.

**Playback sound:** 10-second phrase with one sustained note that opens in brightness over ~0.5s.

**Instructor Patch Settings (Vital)**

* **Osc 1:** Saw wave
* **Osc 2:** Off
* **Filter 1:** Low-pass 24dB

  * Cutoff: ~1.2 kHz
  * Resonance: 0.25
  * Envelope 2 → Cutoff modulation amount: +40%
* **Envelope 1 (amp):** A 0.01s / D 0.4s / S 0.8 / R 0.3s
* **Envelope 2 (mod):** A 0.01s / D 0.5s / S 0 / R 0.4s
* **Unison:** 3 voices, Detune 0.07
* **FX:** Mild chorus, small plate reverb
* **Output:** -6 dB

**Target recognition clues:**
Students should identify the saw timbre, low-pass envelope sweep, and moderate resonance.

---

## 3. Example Round 2 – LFO Wobble Bass (10 minutes)

**Concept:** LFO modulation, tempo-sync, and filter rhythm.
**Reference description:** A thick, dark bass sound with rhythmic filter movement synced to tempo.

**Playback sound:** 1-bar loop at 120 BPM with a repeating 1/4-note wobble.

**Instructor Patch Settings (Vital)**

* **Osc 1:** Square wave
* **Sub Osc:** Sine wave, -12 semitones, level ~0.5
* **Filter 1:** Low-pass 24dB

  * Cutoff: ~400 Hz
  * Resonance: 0.3
  * Drive: +2 dB
  * LFO 1 → Cutoff modulation amount: +60%
* **LFO 1:** Rate 1/4 sync, shape = smooth triangle
* **Envelope 1:** Short, tight (A 0.005s / D 0.3s / S 0.8 / R 0.2s)
* **FX:** Distortion (soft-clip ~30%), EQ with low-shelf boost +2 dB at 100 Hz
* **Output:** Mono

**Target recognition clues:**
Students should notice the tempo-locked movement, sub-layer reinforcement, and saturation.

---

## 4. Example Round 3 – Evolving Ambient Pad (10 minutes)

**Concept:** Layering oscillators, slow modulation, stereo width, and FX.
**Reference description:** Wide, slowly evolving pad with subtle motion.

**Playback sound:** 15-second held chord with gentle timbral motion.

**Instructor Patch Settings (Vital)**

* **Osc 1:** Saw wave
* **Osc 2:** Wavetable “Spectral Warp” or “Complex Square,” detuned +7 cents
* **Filter 1:** Low-pass 12 dB, cutoff ~5 kHz
* **Envelope 1 (amp):** A 1.5s / D 3s / S 0.7 / R 4s
* **LFO 1 → Filter Cutoff:** Amount 20%, rate 0.08 Hz (free-run)
* **LFO 2 → Osc1 Fine Pitch:** ±2 cents random shape, rate 0.5 Hz
* **Unison:** 7 voices, detune 0.12
* **FX Chain:**

  * Chorus: depth 40%, mix 60%
  * Reverb: large hall, mix 45%
  * Delay: 1/4 sync, feedback 25%, mix 20%
* **Output:** -8 dB

**Target recognition clues:**
Students should detect slow filter movement, lush stereo width, and evolving timbre.

---

## 5. Bonus Round – Percussive Pluck (5 minutes)

**Concept:** Short envelopes, fast attack, filter-based timbre shaping.
**Reference description:** Bright, bell-like pluck with short decay.

**Instructor Patch Settings (Vital)**

* **Osc 1:** Sine-saw morph, position 60%
* **Filter 1:** Low-pass 12 dB

  * Cutoff ~2 kHz
  * Envelope 2 → Cutoff +50%
* **Envelope 1 (amp):** A 0s / D 0.25s / S 0 / R 0.15s
* **Envelope 2:** A 0s / D 0.2s / S 0 / R 0.2s
* **FX:** Delay (ping-pong 1/8 sync), Reverb small room 25% mix
* **Output:** -6 dB

**Target recognition clues:**
Students should pick up the quick transient, sharp envelope, and bright tone that fades fast.

---

## 6. Review and Reflection (10 minutes)

**Discussion prompts**

* Which parameters changed the sound most significantly?
* How did small modulation adjustments affect realism?
* What strategies helped when reverse-engineering (e.g., matching envelope shape first)?
* Encourage them to share patches and describe their process in 2–3 sentences.

**Optional Extension:**
Assign each student to design their own “mystery sound” for the next class and swap them for peer recreation.

---

## Instructor Preparation Notes

* Prepare short audio clips (5–15 s) of each patch rendered dry and wet.
* Use a shared naming convention like “Vital_Exercise1_Lead.wav”.
* Optionally, export each Vital patch as `.vital` to share after the exercise for comparison.
* Keep playback levels consistent (~-6 LUFS) for fair listening.

