---
title: "MIDI and Speedrum Lite in REAPER"
---

> Download and install [Speedrum Lite](https://www.apisonic-audio.com/freeware.html)
> before class. Use the free **Lite** version for this course.

This lab introduces the tools you will use to program drums in REAPER. Set up
Speedrum Lite, try recording and drawing MIDI notes, and hear how timing, velocity,
and sample choices change the result. In the next class, the
[drum-pattern lesson](/lectures/week-8/beatmaking/) will build on these skills
with pulse, backbeat, subdivisions, and variation for Project 4.

## Goals for the lab

- Insert Speedrum Lite on an instrument track.
- Create, record, and edit a two-bar MIDI pattern.
- Use quantization and velocity with a musical purpose.
- Load your own samples without breaking the pattern you already made.

## Download and install Speedrum Lite

Speedrum Lite runs inside REAPER as an instrument plug-in. You will open it
from REAPER's FX browser after installation.

### Download

1. Open [Apisonic Audio's freeware page](https://www.apisonic-audio.com/freeware.html).
2. Under **Speedrum Lite**, click **Download**, then **Speedrum Lite (VST, VST3, AU)**
   in the popup. The newsletter subscription is optional.
3. Unzip the download. The current archive, `speedrum-lite-v1.0.3.zip`, contains
   separate `mac`, `win`, and `linux` folders.
4. Close REAPER before running the installer for your computer.

### macOS

1. Open the `mac` folder and double-click `SpeedrumLite.pkg`.
2. Follow the installer prompts. Keep the default installation location and
   install the VST3 plug-in. Enter your Mac administrator password if prompted.
3. Reopen REAPER. The Mac plug-in includes both Intel and Apple Silicon code.
4. Choose `Track > Insert virtual instrument on new track...`, search for
   `Speedrum`, and select the **VST3i** entry for Speedrum Lite.

### Windows

1. Extract the ZIP before opening the installer.
2. Open the `win` folder and run `speedrumlite-setup.exe`.
3. Install the **64-bit VST3** plug-in in its default location. Use the setup
   program for class rather than the files in the `portable` folder.
4. Reopen REAPER. Choose `Track > Insert virtual instrument on new track...`,
   search for `Speedrum`, and select the **VST3i** entry for Speedrum Lite.

### If it does not appear in REAPER

Open REAPER's Preferences, go to `Plug-ins > VST`, and use **Re-scan**. Search
for `Speedrum` again in the FX browser. The standard VST3 locations are
`/Library/Audio/Plug-Ins/VST3` on macOS and
`C:\Program Files\Common Files\VST3` on Windows. If installation requires an
administrator on a lab computer, ask the instructor or lab staff for help.

## Prepare three drum sounds

Use **99Sounds: 99 Drum Samples I** for this lab.

1. Open the [99Sounds drum samples page](https://99sounds.org/drum-samples/)
   and choose **DOWNLOAD PART 1** to get the original pack.
2. On Gumroad, enter **0** in the price field to download it for free. Payment
   is optional; you do not need to pay for this class. Complete the checkout
   with your email address to get the download.
3. Unzip the download and open `[99Sounds] 99 Drum Samples/Samples`.
4. Start with these three files so everyone can follow the same demonstration:

   | Drum part | File |
   | --- | --- |
   | Kick | `kick-808.wav` |
   | Snare | `snare-808.wav` |
   | Closed hi-hat | `hihat-808.wav` |

After the first pattern works, audition other sounds from the same pack and
choose your own combination. Record **99Sounds, 99 Drum Samples I** in your
sample source notes.

Create a folder for your REAPER project and a `Samples` folder inside it. Copy
your chosen files there before loading them into the sampler.

## Set up MIDI

1. **Create an instrument track**: If you have not already created one, use `Track > Insert virtual instrument on new track...` and select Speedrum Lite. When REAPER asks about building additional output tracks, choose **No** for this lab. Keep all pads on the main stereo output. Set the track input to your MIDI device or `MIDI > All MIDI inputs > All channels`, enable record monitoring, and arm the track.
2. **Connect your MIDI keyboard**: Go to `Options > Preferences > Audio > MIDI Devices`, enable your device for input, and choose it as the track input. You may choose `All MIDI inputs` instead.
3. **Use the Virtual MIDI Keyboard if needed**: Open `View > Virtual MIDI Keyboard`. Set the track input to `Virtual MIDI keyboard` or `All MIDI inputs`.
4. **Verify activity**: The track shows a small MIDI activity indicator when MIDI is received. With an instrument inserted and record monitoring on, the audio meter should move as you play.

## Work with Speedrum Lite

> Each pad plays a sample when it receives its assigned MIDI note. For this lab,
> use one-shot drum sounds. Use a synth or chromatic sampler for a playable bass line.

1. **Load three pads**: In the Speedrum Lite instance you opened above, drag your kick, snare or clap, and hi-hat files onto three different pads. Click each pad to check its sound. You can also audition and load files through the internal sample browser.
2. **Find the MIDI notes**: Play your controller or REAPER's Virtual MIDI Keyboard and find the notes that trigger your three pads. In the MIDI editor, click the piano keys to test the mapping before drawing notes. REAPER's octave labels can vary, so identify the notes by the sounds they trigger. Use the pad's MIDI mapping settings if you need to change its trigger note.
3. **Record a MIDI pattern**:
   - Arm the track and turn record monitoring on.
   - Right‑click the track’s Record Arm button > `Record: MIDI overdub/replace` > choose `Overdub`.
   - Set a time selection and enable Repeat if you want to loop while layering.
   - Record your drum pattern.
4. **Draw or edit MIDI**: If you prefer drawing to recording, make a two-bar time selection in REAPER and choose `Insert > New MIDI item`. Double-click the item to open the MIDI editor. Double-click in the grid to add notes on the rows that trigger your three pads. Drag notes to change their timing and adjust their velocity bars below the grid.

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

Once your three drum sounds play correctly, try another one-shot on an unused
pad so your existing pattern keeps playing.

1. **Choose the sounds**: Audition other files in the 99 Drum Samples pack. Try a different kick, snare or clap, or hi-hat or percussion sound. Keep a list of the filenames you use for Project 4.
2. **Add to the existing kit**: In Speedrum Lite, select an empty pad and drag a WAV onto it. Repeat for the other drum sounds.
3. **Keep mapping consistent**: Adding a sound to an unused pad leaves the existing drum parts alone. Replacing the sample on an existing pad keeps that pad's MIDI trigger but changes its sound. Moving a sound to a different MIDI note requires updating the pattern.
4. **Tweak and balance**: Select a pad and adjust its volume, pan, or pitch. Use the waveform's start/end points to trim the hit and its attack/decay envelope to change the onset or tail. Try the low-pass or high-pass filter, then listen to the result in the pattern. Use REAPER effects for additional EQ or compression.
5. **Save the kit and samples**: Use **Save DrumKit As...** and enable the option to save samples with the kit. Save it inside your project folder and keep the resulting sample subfolder with it. Save the REAPER project too.

### Check that your project travels

REAPER's option to copy media into the project folder does not guarantee that
files loaded inside a third-party sampler are collected. Include your saved
Speedrum Lite kit and its samples with the project. Before submission, copy the
complete project folder to another location, reopen the copied REAPER project,
and check every sampled track. If samples are missing, reload the saved kit
from the copied folder, save the project, and test again.

## Worked example: turn a vocal recording into a MIDI part

We will walk through this example during the October 28 Project 4 workshop.
You can also follow it independently after your drum track works.

1. **Choose a source**: Record yourself speaking a short phrase, or import an
   existing vocal recording you can use. Put the audio on a temporary track in
   REAPER and keep the original file in your project folder.
2. **Extract a phrase**: Split the item before and after the words you want.
   Keep a short phrase, about one or two seconds. Remove the other items from
   this temporary track and listen for a clean start and end. Adjust the edges
   and add short fades if needed.
3. **Try a transformation**: Open Item Properties with `F2` and change the take's
   pitch, for example by three semitones. Compare it with the original pitch.
   Keep a change you can describe, such as making the phrase sound lower and
   heavier. This can meet Project 4's sample-transformation requirement.
4. **Make a reusable WAV**: Select the edited item and use **Glue items** to
   create a file with the edits applied. Locate the resulting file through the
   item's source information in Item Properties. Keep it in your project folder
   and record its filename and source in your notes.
5. **Load the sampler**: Create a new Speedrum Lite instrument track named
   `Vocal`. Drag the prepared WAV onto an empty pad and click the pad to audition
   it. Check the sample start/end and adjust the envelope if the phrase cuts off.
6. **Sequence the phrase**: Find the MIDI note that triggers the pad. Create a
   MIDI item, add one trigger near the end of a two-bar drum pattern, and listen
   with the drums. Move the trigger until the phrase answers the beat. Leave
   enough space for the whole phrase to finish before another trigger.
7. **Check the result**: Mute the temporary source track so you hear only the
   sampler. Save the kit with its samples and save the REAPER project. Explain
   what your pitch change and placement contribute to the piece.

The MIDI note triggers a recorded phrase; it does not automatically stretch the
phrase to the project tempo. Adjust the audio before loading it if its timing
does not fit. A short one-shot also does not necessarily stop when the MIDI
note ends, so trim the sample or adjust its envelope to control its length.

Use the same extract, prepare, load, and trigger process for a chordal hit and a
found sound. Only one sample needs a transformation beyond trimming or level
adjustment for Project 4.

## Add the other Project 4 tracks

Create separate Speedrum Lite tracks for the chordal hit, vocal sample, and found sound.
Keep the full drum kit in one Speedrum Lite instance so you can see and edit the pattern
together.

By the October 30 checkpoint, bring your drum pattern and at least one of these
non-drum parts working with MIDI. We will use workshop time to check the
remaining tracks and answer questions.

## Before the end of class

Before you leave, demonstrate that you can:

- trigger Speedrum Lite's drum sounds with MIDI;
- record or draw notes in a two-bar MIDI item;
- move a note and change its velocity; and
- load one of your own samples onto an unused pad.

Save your session for the next class. Your pattern can be a simple experiment
today; we will work on backbeat, subdivisions, and variation in the
[drum-pattern lesson](/lectures/week-8/beatmaking/).

## Common problems

- No sound? Ensure an instrument is inserted, the track is armed, record monitoring is on, and the input is set to your MIDI device (or Virtual MIDI Keyboard).
- High latency? Lower your audio buffer size in Preferences (CoreAudio/ASIO settings) while avoiding crackles.
- Virtual MIDI Keyboard tip: The window needs focus for your computer keys to play notes.

## Optional sources for later projects

Use the 99Sounds pack above for this lab. These sources are available for later
exploration.

- [Freesound](https://freesound.org) — Community‑uploaded samples under Creative Commons. Check the license and attribution for each sound.
- [MusicRadar SampleRadar](https://www.musicradar.com/news/tech/free-music-samples-royalty-free-loops-hits-and-multis-to-download-sampleradar) — Free sample packs organized by style. Choose individual drum hits for your kit.
- [99Sounds](https://99sounds.org) — Curated, high‑quality free sample packs (one‑shots and loops).
- [Bedroom Producers Blog: Free Packs](https://bedroomproducersblog.com/category/news/free-samples/) — Regularly updated roundups of free drum/sample packs.
- [Cymatics — Free Downloads](https://cymatics.fm/collections/free-downloads) — Many free drum one‑shots and kits.
- [Sample Focus](https://samplefocus.com) — User‑curated library; credit‑based downloads with clear tagging.
- [Splice Sounds](https://splice.com/sounds) — Subscription library with extensive drum one‑shots and kits.
- [Wave Alchemy — Free](https://www.wavealchemy.co.uk/free/) — High‑quality electronic drum sounds.
- [Goldbaby — Freebies](https://www.goldbaby.co.nz/freestuff.html) — Vintage drum machine samples; free taster packs.
- [LANDR Samples](https://samples.landr.com) — Subscription library with genre‑based drum kits.
