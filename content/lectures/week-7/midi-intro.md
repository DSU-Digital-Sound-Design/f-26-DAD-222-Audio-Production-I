---
title: "MIDI and Sitala in REAPER"
---

> Download [Sitala](https://decomposer.de/sitala/#downloads) before class.

The [drum-pattern lesson](/lectures/week-8/beatmaking/) covered what to put in
the grid. This lab concentrates on getting that pattern into REAPER, editing it,
and loading the sounds you want to use for Project 4.

## Goals for the lab

- Insert Sitala on an instrument track.
- Create, record, and edit a two-bar MIDI pattern.
- Use quantization and velocity with a musical purpose.
- Load your own samples without breaking the pattern you already made.

## Set up MIDI

1. **Create an instrument track**: Use `Track -> Insert virtual instrument on new track...` (recommended). This inserts a track, opens the FX browser, and sets the track to receive MIDI. Alternatively, create a track, set input to `MIDI > All MIDI inputs > All channels`, enable record monitoring (speaker icon), and arm the track.
2. **Connect your MIDI keyboard**: Go to `Options > Preferences > Audio > MIDI Devices`, enable your device for input, and choose it as the track input. You may choose `All MIDI inputs` instead.
3. **Use the Virtual MIDI Keyboard if needed**: Open `View > Virtual MIDI Keyboard`. Set the track input to `Virtual MIDI keyboard` or `All MIDI inputs`.
4. **Verify activity**: The track shows a small MIDI activity indicator when MIDI is received. With an instrument inserted and record monitoring on, the audio meter should move as you play.

## Work with Sitala

> Start with Sitala's factory kit so everyone can follow the same steps. Sitala
> works well for one-shot samples. Use a synth or chromatic sampler for a
> playable bass line.

1. **Add Sitala to a track**: Insert Sitala on your instrument track.
2. **Use the default kit**: Load the factory/default kit from Sitala’s preset menu if it’s not already loaded. Pads map to consecutive MIDI notes by default (often starting near C1). Use Sitala’s six controls—Shape, Compression, Tuning, Tone, Volume, and Pan—to sculpt each sound. Adjust sample start/end in the waveform view as needed.
3. **Record a MIDI pattern**:
   - Arm the track and turn record monitoring on.
   - Right‑click the track’s Record Arm button > `Record: MIDI overdub/replace` > choose `Overdub`.
   - Set a time selection and enable Repeat if you want to loop while layering.
   - Record your drum pattern.
4. **Edit MIDI**: Double‑click the MIDI item to open the MIDI editor. Draw notes with the pencil, move/resize to adjust timing and length, and set velocities.

## Quantize MIDI notes

1. **Open Quantize**: Press `Q` in the MIDI editor (or `Edit > Quantize events...`).
2. **Choose grid and strength**: Start with a sixteenth-note grid. Adjust Strength or Amount and quantize note positions. Drum-note lengths usually do not need quantization.
3. **Apply and listen**: Compare the pattern before and after. Undo if the result loses the feel you wanted. Try swing only after the straight pattern works.

## Edit velocity

1. **Select notes**: In the MIDI editor, select the notes you want to adjust. Right click on the note you want to change on the piano roll. This selects all notes with the same pitch.
2. **Open Velocity Lane**: Click the Velocity lane at the bottom of the MIDI editor to display it.
3. **Adjust velocities**: Drag the velocity bars up or down to change the velocity of each note.
4. **Filter Events**: Use `Edit > Filter events...` to isolate your selected notes for more precise editing.
   1. Click "Add to Selection" then "Set Filter from selection". Then check the box labeled "Show only events that pass filter". This will make it easier to edit the velocities of only the selected notes.

## Load your own sounds

Once your beat works with the default kit, extend the palette by adding a few external one‑shots to unused pads (e.g., pads 9–16) so your existing pattern keeps playing.

1. **Choose the sounds**: For Project 4, find at least one kick, one snare or clap, and one hi-hat or percussion one-shot. You may cut these hits from a sampled break or use files from a sample library. Keep a list of the sources.
2. **Add to the existing kit**: In Sitala, select an empty pad and drag a WAV onto it. Repeat for the other drum sounds.
3. **Keep mapping consistent**: Avoid replacing kick/snare pads you already used; adding to empty pads preserves your MIDI pattern. If you do replace, update the MIDI notes accordingly.
4. **Tweak and balance**: Use Shape, Compression, Tuning, Tone, Volume, and Pan to fit new sounds with the default kit. Optionally trim sample starts for tighter feel.
5. **Save the kit**: Save a Sitala preset so you can recall your combined default+custom kit.

## Add the other Project 4 tracks

Create separate Sitala tracks for the chordal hit, vocal sample, and found sound.
Keep the full drum kit in one Sitala instance so you can see and edit the pattern
together.

## Before the end of class

Your project should now contain:

- a two-bar drum pattern with kick, snare or clap, and hi-hat;
- at least one change in bar 2;
- velocity changes on at least one drum part; and
- separate tracks ready for the chordal hit, vocal sample, and found sound.

## Common problems

- No sound? Ensure an instrument is inserted, the track is armed, record monitoring is on, and the input is set to your MIDI device (or Virtual MIDI Keyboard).
- High latency? Lower your audio buffer size in Preferences (CoreAudio/ASIO settings) while avoiding crackles.
- Virtual MIDI Keyboard tip: The window needs focus for your computer keys to play notes.

## Optional sample sources

- [Freesound](https://freesound.org) — Community‑uploaded samples under Creative Commons. Check the license and attribution for each sound.
- [MusicRadar SampleRadar](https://www.musicradar.com/news/tech/free-music-samples-royalty-free-loops-hits-and-multis-to-download-sampleradar) — Large collection of free, royalty‑free packs organized by style. Great for augmenting your default Sitala kit.
- [99Sounds](https://99sounds.org) — Curated, high‑quality free sample packs (one‑shots and loops).
- [Bedroom Producers Blog: Free Packs](https://bedroomproducersblog.com/category/news/free-samples/) — Regularly updated roundups of free drum/sample packs.
- [Cymatics — Free Downloads](https://cymatics.fm/collections/free-downloads) — Many free drum one‑shots and kits.
- [Sample Focus](https://samplefocus.com) — User‑curated library; credit‑based downloads with clear tagging.
- [Splice Sounds](https://splice.com/sounds) — Subscription library with extensive drum one‑shots and kits.
- [Wave Alchemy — Free](https://www.wavealchemy.co.uk/free/) — High‑quality electronic drum sounds.
- [Goldbaby — Freebies](https://www.goldbaby.co.nz/freestuff.html) — Vintage drum machine samples; free taster packs.
- [LANDR Samples](https://samples.landr.com) — Subscription library with genre‑based drum kits.
