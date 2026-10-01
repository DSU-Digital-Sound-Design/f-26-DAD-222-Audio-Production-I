---
title: "Delay, Chorus, and Flanger"
date: 2025-10-07
description: "A deep dive into delay effects using REAPER’s ReaDelay plugin—covering slapback, rhythmic echoes, ADT, flanging, chorus, and creative routing."
tags: ["audio production", "delay", "reaper", "sound design", "teaching"]
---

Watch REAPER Mania's [Why and How to Use Delay](https://www.youtube.com/watch?v=ajHUF6VTrts) and [Creating Sends](https://www.youtube.com/watch?v=PBZvDTCtPfQ) alongside this lesson. If you want to explore the other effects, watch [Chorus & Flange FX](https://www.youtube.com/watch?v=DYqacYeUohw).

Delay is one of the simplest and most powerful time-based effects in audio production. It records an incoming signal, waits for a set amount of time, and then plays it back—either once or many times, depending on the settings.

By mixing delayed and dry signals, delay creates space, rhythm, width, and unique timbral textures. REAPER’s **ReaDelay** plugin makes it easy to explore these variations.

---

## Understanding Delay

A delay effect:
- Records the input into a short digital buffer.
- Plays it back after a defined delay time.
- Mixes that delayed signal with the dry (original) one.

By adjusting **delay time**, **feedback**, and **mix**, you can shape the character and movement of the sound.

---

## Delay Time Ranges and Their Effects

| Delay Type            | Typical Range (ms) | Sound Character                                       | Tempo-Synced Equivalents (at 120 BPM) |
|-----------------------|-------------------:|--------------------------------------------------------|---------------------------------------|
| Very short            | 1–10               | Comb filtering; flanging zone                          | Usually set in milliseconds                |
| Short (ADT/Haas)      | 10–40              | Thickening, width; watch mono compatibility            | —                                     |
| Slapback              | 75–150             | Single audible echo; classic rockabilly vocal feel     | 1/16 ≈ 125 ms |
| Rhythmic/long         | 250–800+           | Distinct rhythmic repeats; ambient/spatial echoes      | 1/8 = 250 ms; dotted-1/8 = 375 ms; 1/4 = 500 ms |
| Very long             | 800+               | Sound design; evolving textures; looping                | —                                     |


**Formula for Delay Time:**  
`delay (ms) = 60000 / BPM × number_of_quarter_notes`

Use 1 for a quarter note, 0.5 for an eighth, and 0.75 for a dotted eighth. At 120 BPM, a dotted eighth is 375 ms. At Project 3's 96 BPM, an eighth is 312.5 ms and a quarter is 625 ms.

---

## Optional listening examples

### Rhythmic and Long Delays
<iframe width="560" height="315" src="https://www.youtube.com/embed/3FsrPEUt2Dg?si=R5wCARSbeb6jybPA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

U2 – *Where the Streets Have No Name*  
The Edge’s dotted-eighth delay defines U2’s signature rhythmic guitar sound.

<iframe width="560" height="315" src="https://www.youtube.com/embed/y_Ol8avCkXg?si=TiA_I6jUpOHILc4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Pink Floyd – *Run Like Hell*  
A tempo-synced delay that locks perfectly with the groove.

---

### Slapback Delay

<iframe width="560" height="315" src="https://www.youtube.com/embed/njw2oB8oRTs?si=m2bYSVquyaN7V-qF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Elvis Presley – *Mystery Train*  
Classic Sun Studios slapback—around 130 ms, minimal feedback.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xLy2SaSQAtA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

John Lennon – *Instant Karma!*  
Short single echo for added vocal presence.

---

### Doubling / ADT
<iframe width="560" height="315" src="https://www.youtube.com/embed/m4BuziKGMy4?si=c4tHkTDr0l0ixS5W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Beatles – *Tomorrow Never Knows*  
Subtle, modulated short delays create doubled textures.

<iframe width="560" height="315" src="https://www.youtube.com/embed/hTWKbfoikeg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Nirvana – *Smells Like Teen Spirit*  
Vocal thickness comes from double-tracking and short delay blending.

---

### Ping-Pong / Stereo Delay
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZoC9_udLNeU?si=ce7lmihRor9M4hX0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

David Bowie – *Let’s Dance*  
Stereo delays bounce between left and right for width and energy.

---

### Flanger
<iframe width="560" height="315" src="https://www.youtube.com/embed/nO9DqvznjrQ?si=5R6YDtCiNODrGfBB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Small Faces – *Itchycoo Park*  
One of the earliest examples of tape flanging.

<iframe width="560" height="315" src="https://www.youtube.com/embed/HUtqdiMqof0?si=5z5lSpAnWhPOzmMW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Van Halen – *Unchained*  
Jet-like flanger sweep across Eddie Van Halen’s guitar.

---

### Chorus
<iframe width="560" height="315" src="https://www.youtube.com/embed/vabnZ9-ex7o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Nirvana – *Come As You Are*  
Watery chorus modulation on the guitar riff.

<iframe width="560" height="315" src="https://www.youtube.com/embed/zPwMdZOlPo8?si=L0yQAz8GnWgySCYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Police – *Walking on the Moon*  
Chorus and delay combine for lush, atmospheric space.

---

## Project 3 delay exercise

**Goal:** Explore how different delay times affect perception and space.

1. Open your Project 3 working session. Preserve the static balance you saved before adding processing. If you need separate practice audio, use [these files](../delay-files.zip).
2. Create one track named *Delay Return*, outside the instrument folders.
3. Insert **ReaDelay**. Set **Wet** to *0 dB* and **Dry** to *-inf dB* so only the delayed signal is heard on the return.
4. Create a post-fader send from a vocal or chord instrument to the return. Begin with the send at -inf dB, then raise it gradually.
5. Compare two settings on the same return, such as slapback around 120–150 ms and a longer tempo-synced eighth- or quarter-note echo. Adjust feedback as well as delay time. Mute the return to check whether the effect supports the full mix.
6. Keep the setting that serves the song and note what you heard in both versions. Additional returns, filtering, and ducking are optional.

---

## Optional: beyond basic delay

Both **flanger** and **chorus** are based on *short modulated delays*, but they differ in delay times, modulation depth, and the way they shape tone and movement.

| Effect | Typical Delay Time | Core Concept | Audible Character |
|---------|-------------------:|---------------|-------------------|
| **Flanger** | 0.5–10 ms | Mixes the dry signal with a *very short, modulated delay*. The constantly changing time offset causes moving *comb-filter peaks* in the frequency spectrum. | Sweeping, “jet plane” or “whooshing” sound as frequencies phase in and out. |
| **Chorus** | 15–30 ms | Mixes the dry signal with one or more *slightly longer, modulated delays*. These delays simulate small timing/pitch variations between performers. | Smooth, shimmering thickening effect—like multiple instruments playing together. |


### Flanger in REAPER
Try **JS: Flanger**. Listen as you adjust its delay, feedback, and modulation controls. Compare it with the dry track at similar loudness.


---

### Chorus in REAPER
Use REAPER’s built-in Chorus or JS: Chorus:
- Delay: 20–30 ms  
- Mod Rate: 0.3–0.6 Hz  
- Depth: 5–10 ms modulation  

---

## Optional: creative delay techniques

**Ping-Pong Delay**  
- Two taps in ReaDelay, panned left/right with slightly different times.

**Ducked Delay**  
- Sidechain a compressor (ReaComp) from the dry signal to make delay audible only between phrases.

**Feedback Loop Sound Design**  
- Enable feedback routing (Project Settings → Advanced).  
  Add EQ or distortion in the loop for evolving textures. Always use a limiter.

**Karplus–Strong Plucked Delay**  
- Delay: 8–12 ms  
- High feedback, lowpass filter  
- Excite with a short noise burst.
