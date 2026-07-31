---
title: "MIDI Introduction in Reaper"
---

> Download the Sitala plugin (free): https://decomposer.de/sitala/#downloads

### Learning Objectives

- Configure MIDI input devices and use Reaper’s Virtual MIDI Keyboard.
- Insert and route a virtual instrument (Sitala, ReaSynth) on a track.
- Record MIDI in overdub mode while looping a selection.
- Edit notes and velocities in the MIDI editor; use event filtering for precision.
- Quantize note starts/ends with appropriate grid, strength, and swing.
- Program a basic drum pattern with Sitala’s default kit, then augment it by adding external samples to unused pads.

## Setting Up MIDI

1. **Create an instrument track**: Use `Track -> Insert virtual instrument on new track...` (recommended). This inserts a track, opens the FX browser, and sets the track to receive MIDI. Alternatively, create a track, set input to `MIDI > All MIDI inputs > All channels`, enable record monitoring (speaker icon), and arm the track.
2. **Connect your MIDI keyboard**: Go to `Options > Preferences > Audio > MIDI Devices`, enable your device for input (and optionally “Enable input for control messages”). Then choose it—or “All MIDI inputs”—as the track input.
3. **Use the Virtual MIDI Keyboard (optional)**: `View > Virtual MIDI Keyboard`. Set the track input to “Virtual MIDI keyboard” or “All MIDI inputs” to play from your computer keys.
4. **Verify activity**: The track shows a small MIDI activity indicator when MIDI is received. With an instrument inserted and record monitoring on, the audio meter should move as you play.

## Working with Sitala

> Start with Sitala’s built‑in default/factory kit so everyone can follow along without downloading samples. Sitala is a 16‑pad drum sampler ideal for one‑shots. For a playable bass line, use a synth (e.g., ReaSynth) or a chromatic sampler (e.g., ReaSamplomatic5000)—not Sitala.

1. **Add Sitala to a track**: Insert Sitala on your instrument track.
2. **Use the default kit**: Load the factory/default kit from Sitala’s preset menu if it’s not already loaded. Pads map to consecutive MIDI notes by default (often starting near C1). Use Sitala’s six controls—Shape, Compression, Tuning, Tone, Volume, and Pan—to sculpt each sound. Adjust sample start/end in the waveform view as needed.
3. **Record a MIDI pattern**:
   - Arm the track and turn record monitoring on.
   - Right‑click the track’s Record Arm button > `Record: MIDI overdub/replace` > choose `Overdub`.
   - Set a time selection and enable Repeat if you want to loop while layering.
   - Record your drum pattern.
4. **Edit MIDI**: Double‑click the MIDI item to open the MIDI editor. Draw notes with the pencil, move/resize to adjust timing and length, and set velocities.

## Quantizing MIDI Notes

1. **Open Quantize**: Press `Q` in the MIDI editor (or `Edit > Quantize events...`).
2. **Choose grid and strength**: Set the grid (e.g., 1/16, 1/8T), adjust Strength/Amount, and choose whether to quantize note positions, note ends, or both. Add Swing for groove if desired.
3. **Apply and listen**: Apply, listen, and tweak. Undo if needed; aim for musical feel over perfect alignment.

## Edit Velocity

1. **Select notes**: In the MIDI editor, select the notes you want to adjust. Right click on the note you want to change on the piano roll. This selects all notes with the same pitch.
2. **Open Velocity Lane**: Click the Velocity lane at the bottom of the MIDI editor to display it.
3. **Adjust velocities**: Drag the velocity bars up or down to change the velocity of each note.
4. **Filter Events**: Use `Edit > Filter events...` to isolate your selected notes for more precise editing.
   1. Click "Add to Selection" then "Set Filter from selection". Then check the box labeled "Show only events that pass filter". This will make it easier to edit the velocities of only the selected notes.

## Adding Alternative Sounds (MusicRadar Example)

Once your beat works with the default kit, extend the palette by adding a few external one‑shots to unused pads (e.g., pads 9–16) so your existing pattern keeps playing.

1. **Find sounds on MusicRadar**: Go to https://www.musicradar.com/news/tech/free-music-samples-royalty-free-loops-hits-and-multis-to-download-sampleradar and pick a drum one‑shots pack. Download and unzip.
2. **Add to the existing kit**: In Sitala, select an empty pad and drag a WAV from the pack onto it. Repeat for a few complementary sounds (e.g., an alternate snare, clap, cymbal).
3. **Keep mapping consistent**: Avoid replacing kick/snare pads you already used; adding to empty pads preserves your MIDI pattern. If you do replace, update the MIDI notes accordingly.
4. **Tweak and balance**: Use Shape, Compression, Tuning, Tone, Volume, and Pan to fit new sounds with the default kit. Optionally trim sample starts for tighter feel.
5. **Save the kit**: Save a Sitala preset so you can recall your combined default+custom kit.

## Adding More Tracks

1. **Another drum track**: Add a second Sitala for more kits or layers.
2. **Pad mapping and shaping**: Each pad triggers a specific MIDI note; adjust pad note mapping or use MIDI Learn if needed. Sculpt sounds with Shape, Compression, Tuning, Tone, Volume, and Pan; trim start/end in the waveform view.
3. **Layer parts**: Keep `Record: MIDI overdub` enabled to add elements across multiple passes.

## Common Gotchas

- No sound? Ensure an instrument is inserted, the track is armed, record monitoring is on, and the input is set to your MIDI device (or Virtual MIDI Keyboard).
- High latency? Lower your audio buffer size in Preferences (CoreAudio/ASIO settings) while avoiding crackles.
- Virtual MIDI Keyboard tip: The window needs focus for your computer keys to play notes.

## Optional: More Sample Sources

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
