---
title: "Delay, Chorus, and Flanger"
date: 2025-10-07
description: "A deep dive into delay effects using REAPER’s ReaDelay plugin—covering slapback, rhythmic echoes, ADT, flanging, chorus, and creative routing."
tags: ["audio production", "delay", "reaper", "sound design", "teaching"]
---

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
| Very short            | 1–10               | Comb filtering; flanging zone                          | 1/64–1/32 (≈ 31–63 ms)                |
| Short (ADT/Haas)      | 10–40              | Thickening, width; watch mono compatibility            | —                                     |
| Slapback              | 75–150             | Single audible echo; classic rockabilly vocal feel     | 1/16 ≈ 125 ms; dotted-1/16 ≈ 187.5 ms |
| Rhythmic/long         | 250–800+           | Distinct rhythmic repeats; ambient/spatial echoes      | 1/8 = 250 ms; dotted-1/8 = 375 ms; 1/4 = 500 ms |
| Very long             | 800+               | Sound design; evolving textures; looping                | —                                     |


**Formula for Delay Time:**  
`delay (ms) = 60000 / BPM × note_value`

Example: At 120 BPM, a dotted eighth note equals 375 ms.

---

## Listening Examples

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

<iframe width="560" height="315" src="https://www.youtube.com/embed/EqP3wT5lpa4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

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

## In-Class REAPER Exercise

**Goal:** Explore how different delay times affect perception and space.

1. Download the practice files [here](../delay-files.zip).  
   Listen to each file individually.
2. Create three FX return tracks: *Short Delay*, *Medium Delay*, *Long Delay*.
3. Insert **ReaDelay** on each FX track.  
   Set **Dry** to *-inf dB* (so only the delayed signal is heard).
4. Start with:
   - Short Delay: 15–25 ms  
   - Medium Delay: 120–150 ms  
   - Long Delay: 300 ms+ or tempo-synced (⅛, ¼, dotted-⅛)
5. Add sends from your audio tracks to the delay buses.  
   Adjust send levels to taste.
6. Add **ReaEQ** to roll off highs (LP ~6–8 kHz) and **ReaComp** for optional ducking.

---

## Beyond Basic Delay

Both **flanger** and **chorus** are based on *short modulated delays*, but they differ in delay times, modulation depth, and the way they shape tone and movement.

| Effect | Typical Delay Time | Core Concept | Audible Character |
|---------|-------------------:|---------------|-------------------|
| **Flanger** | 0.5–10 ms | Mixes the dry signal with a *very short, modulated delay*. The constantly changing time offset causes moving *comb-filter peaks* in the frequency spectrum. | Sweeping, “jet plane” or “whooshing” sound as frequencies phase in and out. |
| **Chorus** | 15–30 ms | Mixes the dry signal with one or more *slightly longer, modulated delays*. These delays simulate small timing/pitch variations between performers. | Smooth, shimmering thickening effect—like multiple instruments playing together. |


### Flanger in REAPER
Try **JS: Flanger** or use **ReaDelay** as a flanger:
- Delay: 2–5 ms  
- Feedback: 30–60%  
- Mod Rate: 0.2–0.5 Hz  


---

### Chorus in REAPER
Use REAPER’s built-in Chorus or JS: Chorus:
- Delay: 20–30 ms  
- Mod Rate: 0.3–0.6 Hz  
- Depth: 5–10 ms modulation  

---

## Creative Delay Techniques

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


