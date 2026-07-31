---
title: Delay in Reaper
---

Delay is one of the simplest time-based effects in audio production. It takes the incoming audio, stores it in a digital buffer for a set time, and then plays it back.

- The delayed signal is mixed with the original, undelayed signal.
- The length of the delay time shapes the character of the effect:
  - **Long delays** (100ms+) create clear, audible echoes.
  - **Short delays** (10-50ms) thicken the sound without noticeable echoes.
  - **Very short delays** (a few ms) act like a comb filter, altering frequencies.
- Feeding the delay output back into the input creates repeating echoes that fade out over time.
- Adjusting the delay time with feedback can produce different creative effects.

## Examples

Here are some examples of songs that showcase various delay effects:

**Long Delay (100ms+) - Clear Echoes**
- [The Edge (U2) - I Still Haven't Found What I'm Looking For](https://www.youtube.com/watch?v=e3-5YC_oHjE) – The delay effect on the guitar is iconic and helps create the spacious, atmospheric sound U2 is known for.
- [U2 - Where The Streets Have No Name](https://www.youtube.com/watch?v=3FsrPEUt2Dg) – The guitar notes in the intro have long, echoing delays.

**Medium Delay (10-50ms) - Thickening Effect**
- [Nirvana - Smells Like Teen Spirit](https://www.youtube.com/watch?v=hTWKbfoikeg) – The vocals use medium delay to thicken the sound.

**Short Delay (Few ms) - Comb Filtering**
- [The White Stripes - Seven Nation Army](https://www.youtube.com/watch?v=0J2QdDbelmY) – The main riff uses a very short delay, creating a comb-filtered sound.
- *Note: Chorus and flanging are also forms of comb filtering.*


## In-Class Mix Exercise

We'll experiment with delay effects using three different types of sounds.

Download the practice tracks [here](../delay-files.zip) and add them to your project as separate tracks. Solo each track to listen individually. They are not meant to be played together.

Next, create three new tracks for delay sends: name them "Short Delay," "Medium Delay," and "Long Delay." These tracks will hold your delay effects and won't have any audio directly on them. We'll send audio from the other tracks to these sends, so multiple tracks can share the same delay.

1. Add a _ReaDelay_ plugin to each of the delay send tracks.
2. Set the **dry level** to **-inf dB** (so the dry signal is not included in the delay send).
3. Adjust delay times:
   - Short Delay: 10-50ms
   - Medium Delay: 100-300ms
   - Long Delay: 300ms+

Now, experiment by sending audio to the delay tracks. Adjust the send levels to fade in the delay until you get the desired sound. In real production, delays are often more subtle because they're blended with other sounds. Remember, context is key!

## Flanger

A flanger is created by modulating the delay time periodically. The delay should be short, around 20ms, with a modulation rate of around 10Hz. Reaper has two flanger effects: _Flanger_ and _Flanger Baby_. Try using both on their own send tracks to hear the differences.

Example: [Heart - Barracuda](https://www.youtube.com/watch?v=VdOkQ6THDVw)

## Chorus

A chorus effect is made by layering multiple varying delays. In real life, no two singers or instruments perform exactly in sync, creating slight variations in pitch and timing. A chorus simulates this effect by combining time-varying delays with the original signal. To keep it subtle, set the modulation rate and depth to low values.

Find the chorus effect in Reaper and test it out.

Example: [Nirvana - Come As You Are](https://www.youtube.com/watch?v=vabnZ9-ex7o)

---

Reaper has a wide range of other delay effects. Search for "delay" in the plugin menu, test different ones, and explore what they can do.