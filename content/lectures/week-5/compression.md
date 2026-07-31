---
title: "Compression and When to Use It"
---

Download [these audio tracks](../comp-audio.zip) to practice with in class.

> Some setup: quickly rename tracks using the `Track Manager` (shortcut: `Ctrl` + `Shift` + `M`). You can also change the color of tracks by right-clicking on the track number and selecting `Set track color`. This can help you visually organize your session.

> Compression is a technique that controls the dynamic range of an audio signal—this means balancing the loudest and quietest parts by reducing peaks and then using makeup gain so the overall level sits consistently.

![](../Figure-7.11-Dynamics-compression-and-expansion.png)

This image shows how compression affects the dynamic range, balancing the loud and quiet moments of a signal.

For more detailed definitions of compressor parameters, check out the [Reaper Effects guide](https://dlz.reaper.fm/userguide/REAPEREffectsGuide2021.pdf), specifically Chapter 2 on compression.

---

## Why use compression?

Common, musical use cases:

* Vocals: stabilize performance so quiet words don’t vanish and loud phrases don’t jump out. Use gentle ratios first.
* Drums: shape the relationship between transient and body; add punch, density, or both.
* Instruments: extend sustain (e.g., guitars), control peaks (e.g., bass), or glue layered parts.
* Buses: subtle, tempo-aware bus compression can make elements move together.

Also, when not to compress: if a track already sits naturally and feels alive, consider leaving it alone or use volume automation instead.

---

## Core parameters at a glance

* `Threshold`: level where gain reduction begins.
* `Ratio`: how much signal above threshold is reduced (4:1 means 4 dB in yields 1 dB out above threshold).
* `Attack`: time to start compressing after crossing threshold. Slower (20–30 ms) lets transients through for punch; faster (1–10 ms) smooths but can dull.
* `Release`: time to stop compressing after the signal falls below threshold. Too fast can pump; too slow can feel smeared.
* `Knee`: transition softness into compression. Soft knee is subtler; hard knee is more obvious and punchy.
* `Makeup gain`: brings level back after reduction. For fair A/B, gain-match processed vs. bypassed.

![](../Audio-Compressor-Ratio-Chart-652x435-1418756899.jpg)


> Tip: aim for 2–6 dB of gain reduction on peaks with moderate ratios (2:1–4:1). Always compare at equal loudness.

---

## Applying compression to drums (kick with ReaComp)

1. Click the FX button on the kick drum track.
2. Search for `ReaComp` in the FX browser and add it to the track.
3. You can enable Auto Make-up to keep output consistent, but for accurate A/B it’s better to set makeup manually so bypass and processed are equal loudness.

Focus first on threshold and ratio:

* Ratio: start at 4:1.
* Lower the threshold until you see about 3–6 dB of gain reduction on strong hits.

Then set attack and release:

* Attack: begin around 20–30 ms for punch. If you want a tighter, smoother hit, move toward 10 ms—but very fast attacks can choke the transient.
* Release: start near 100–200 ms, then tune by ear so the gain reduction returns to zero just before the next kick. A tempo cue helps: quarter-note (ms) ≈ 60,000 ÷ BPM; try an eighth-note release as a musical starting point.

Other tips:
* Use ReaComp’s detector high-pass (e.g., 60–90 Hz) so sub-energy doesn’t over-trigger compression.
* Keep an eye on the gain-reduction meter’s “shape.” You want the compressor to breathe with the groove, not fight it.


---

## Applying compression to other drum elements

* Snare: ratio 4:1, attack 15–25 ms, release 100–200 ms, 3–6 dB GR. If ghost notes disappear, ease the ratio, raise threshold, or soften the knee.
* Overheads/rooms (control): ratio 2:1–3:1, attack 25–40 ms, release 200–400 ms.
* Overheads/rooms (vibe/crush): higher ratios with fast times, then blend in parallel (see below).

Parallel drum compression options in Reaper:

* Create a “Drum Parallel” bus, send drums to it pre-fader, squash hard on the parallel, and blend to taste; or
* Use the FX wet/dry knob on individual ReaComp instances for quick per-track parallel.

---

## Bus compression

After compressing individual drum tracks, try bus compression to glue the kit:

1. Create a new track and name it “Drum Bus.”
2. Route all individual drum tracks (kick, snare, etc.) to this bus.
3. Add ReaComp with a gentle setup: ratio 1.5:1–2:1, attack 20–30 ms, release 100–300 ms, soft knee, aiming for 1–3 dB of gain reduction on loud sections.

If the bus audibly pumps in an unmusical way, raise the threshold, lengthen the release, or reduce the ratio.

---

## Vocals and instruments: quick starting points

* Vocals: 2–4:1, attack 5–15 ms, release 50–150 ms, soft knee, 3–6 dB GR. Use detector HPF around 100–150 Hz to avoid proximity effect driving compression.
* Bass: 4–6:1, attack 10–30 ms, release 100–200 ms for even sustain.
* Acoustic guitar: 2–3:1, attack 15–30 ms, release 100–200 ms; consider detector HPF ~120 Hz to avoid low thumps.

Remember that upward detail can be achieved more transparently via parallel compression rather than heavy downward compression.

---

## Metering and sensible targets

* Watch true peaks and integrated loudness (LUFS) in addition to gain reduction.
* Keep healthy headroom on the master during mixing (e.g., peaks below −6 dBFS) and resist “mixing into loudness.” Add a limiter only to catch stray peaks if needed.

---

## Common pitfalls

* Judging the “better” setting by loudness instead of tone: always gain-match.
* Attack too fast on transient sources: kills punch.
* Release too fast: audible pumping; too slow: smeared groove.
* Compressing by default: sometimes automation or arrangement fixes are better.


---

## Conclusion

Compression shapes the relationship between transient, body, and sustain. Start conservatively, match levels for honest A/B, and time release to the song. Add detector filtering and parallel paths when needed, and leave uncompressed tracks alone when they already serve the mix.
