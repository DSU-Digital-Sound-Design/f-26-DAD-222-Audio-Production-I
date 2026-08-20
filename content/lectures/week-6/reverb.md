---
title: "Mixing with reverb"
---

> Download the audio files [here](https://dakotastateuniversity-my.sharepoint.com/:f:/g/personal/tate_carson_dsu_edu/Em4CtTSSKXRDhmr9Iaxn5TIBclFmF2zb6MVO49FjPDsR3A?e=2OBZ5y).

Reverb does more jobs in a mix than most people expect. Five of them, with examples:

- **Blend**  
  Reverb helps different parts of a mix feel like they’re in the same space. For instance, on The Ronettes’ Be My Baby, chamber reverb merges dozens of instruments and vocals into one lush texture, a hallmark of Phil Spector’s “Wall of Sound.”
  <iframe width="560" height="75" src="https://www.youtube.com/embed/jSPpbOGnFgk?si=yYQiK3VljTP_DbkK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- **Size**  
  On A Day in the Life, the orchestral ‘bigness’ comes from Studio One’s natural space plus multiple orchestral overdubs; reverb contributes to a concert‑hall impression, but the heavy, obvious reverb is on Lennon’s vocal.
  <iframe width="560" height="75" src="https://www.youtube.com/embed/usNsCeOV4GM?si=c1ZvTXPjElePlG4u&amp;start=167" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- **Tone**  
  Reverb can change an instrument's timbre, not just its sense of space. Dick Dale’s use of Fender’s spring reverb on Misirlou gives his Stratocaster that bright, percussive “drip” tone that defines surf guitar.
  Another example: the Nashville Sound. Patsy Cline's recordings under Owen Bradley have a polished vocal ambience that points to plate or chamber reverb, though no session log survives to confirm exactly what was in the chain.
  <iframe width="560" height="75" src="https://www.youtube.com/embed/9UmmbF1Zyvk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  <iframe width="560" height="75" src="https://www.youtube.com/embed/YWKeuYcDAoo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- **Sustain**  
  Reverb can extend the life of a sound, making it linger beyond its natural decay. In I Will Always Love You by Whitney Houston, the long plate reverb carries her held notes and fills the silence between phrases.
  <iframe width="560" height="75" src="https://www.youtube.com/embed/3JWTaaS7LdU?si=BjqGhMiZI6nIRiWS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>  

- **Spread**  
  Reverb can make a mix feel wider and more open, especially when used with stereo or modulated algorithms. In Midnight City by M83, reverb expands the synths and vocals across the stereo field, giving the chorus its soaring, cinematic space. <iframe width="560" height="74" src="https://www.youtube.com/embed/dX3k_QDnzHE?si=q2Jg2hbBXGfFasci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Analog Reverb Techniques

Before digital plugins, reverb came from physical spaces and devices: chambers, plates, and springs.

### Inside the Reverb Chambers at Capricorn Sound Studios

<iframe width="560" height="315" src="https://www.youtube.com/embed/Am0ELIQcCgQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Spring Reverb

<iframe width="560" height="315" src="https://www.youtube.com/embed/tU7U-U-n4EQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Plate Reverb

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y58nroQ0DMw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Reaper Stock Plugins for Reverb

Reaper ships with two reverb plugins, ReaVerb and ReaVerbate.

Check out the [ReaEffects Guide](https://www.reaper.fm/guides/REAPEREffectsGuide2021.pdf) for more details on these plugins.

## ReaVerbate

We'll start with ReaVerbate on single instruments, then put it to work on the jobs listed above. Add it to your guitar track.

Here are key parameter descriptions (from the ReaEffects guide):

- **Wet**: Determines how much of the processed signal is mixed with the original.
- **Dry**: Controls how much of the original signal remains unprocessed.
- **Room Size**: Adjusts the size of the simulated room.
- **Dampening**: Simulates how much the sound is absorbed by materials in the room (e.g., curtains, carpets).
- **Stereo Width**: Controls the width of the stereo field for the reverb.
- **Initial Delay**: Adds a delay before the reverb starts, creating more space.
- **Lowpass/Highpass**: Filter controls to apply reverb to only certain frequency ranges.

### Reverb on One Instrument

Set the room size to 100, then adjust the damping. With low damping, you'll hear a brighter reverb; with more damping, the reverb becomes darker. You can further shape the sound using the high- and low-pass filters.

### Reverb on a Send

Often, you want to apply the same reverb to multiple instruments. To do this in Reaper, create a send.

1. Create a new track and name it "Reverb."
2. Route your drum tracks to this send by selecting all the drums, holding shift, and dragging them onto the Reverb track.
3. Add ReaVerbate to the Reverb track. Set the wet mix to 0 dB and the dry mix to -inf dB (since this is a send track).
4. Open the routing for the Reverb send and set all send levels to -inf dB. Then bring up the send levels for each drum one at a time. Start with the snare, then add reverb to the overheads.

> Try creating custom presets for the guitar and vocal tracks. Then apply this process to your drum editing project from earlier in the semester.

## ReaVerb

ReaVerb is the deeper of the two, and it does convolution reverb. Its modules:

- **Echo Generator**: Creates echo or delay effects.
- **Reverb Generator**: Adds traditional reverb.
- **Convolution Reverb**: Uses impulse responses to simulate different spaces.
- **High/Low Pass Filters**: Adjust the frequencies affected by the reverb.
- **Normalization**: Levels out the reverb volume.
- **Reverse**: Reverses the reverb tail.
- **Time/Gain/Stretch**: Alters the timing and pitch of the reverb.

Here are some resources for free impulse responses:
- [Open Air Library](https://www.openair.hosted.york.ac.uk/)
- [Sampled EMT140 Plate](https://oramics.github.io/sampled/IR/EMT140-Plate/)
- [Sampled Voxengo](https://oramics.github.io/sampled/IR/Voxengo/)
- [REAPER Blog's Free Reverb Impulse Response Library | The REAPER Blog](https://reaper.blog/2018/11/free_reverb_irs/)

Again, the [ReaEffects Guide](https://www.reaper.fm/guides/REAPEREffectsGuide2021.pdf) contains details on how to use each of these modules effectively.
