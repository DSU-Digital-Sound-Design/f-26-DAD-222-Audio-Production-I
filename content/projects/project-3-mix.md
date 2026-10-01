---
title: "Angels in Amplifiers Mix"
number: "03"
weight: 3
week: 8
assigned: "2026-10-02"
due: "2026-10-23"
summary: "Complete a multitrack mix using EQ, compression, delay, and reverb. Critical listening and technical mixing."
tools: ["REAPER", "ReaEQ", "ReaComp", "ReaDelay", "ReaVerbate"]
# this project carries its own rubric table in the body
rubric: false
---

Mix Angels in Amplifiers' *I'm Alright* using the balancing, editing, and file preparation skills from Projects 1 and 2. You will add EQ, compression, delay, and reverb as we learn them. The goal is a clear rough mix with choices you can hear and explain.

Download the [multitrack recordings](https://mtkdata.cambridgemusictechnology.co.uk/MTK006/AngelsInAmplifiers_ImAlright.zip) and listen to the [reference mix](https://previews.cambridge-mt.com/ImAlright_Preview.mp3). The reference uses techniques beyond this course. Use it to compare balance and space at a similar listening level; you do not need to reproduce its polish or loudness.

## Requirements

- Organize and mix the supplied recordings for the full song.
- Insert ReaEQ on every source track and audition a high-pass filter to check for unnecessary low-frequency buildup. Preserve useful bass and body; a very low cutoff or bypassed filter is acceptable when filtering makes the track worse.
- Make and explain at least two additional EQ decisions about tone or masking, including one masking comparison. You may reject a change if the original works better.
- Use ReaComp on at least two source tracks and explain what each instance improves.
- Use at least one delay return and one reverb return, routed with sends and set fully wet. Test contrasting settings before choosing what to keep.
- Save a static balance before adding compression, tonal EQ, delay, or reverb. Compare that version with your final mix.

Additional effects returns are optional. More plugins do not earn more points; the choices must support the song.

## Checkpoints

- **October 2:** After the EQ lab, import and save the session, follow a brief fader-balance demonstration, and save your starter balance. Resolve import or alignment problems in class. Finish folder organization if needed and bring the session Monday.
- **October 5:** Finish the high-pass check and save your static balance before adding other processing. In a separate working version, try compression on one track and practice creating an effects send.
- **October 7 and 9:** Work independently through the delay and reverb lessons in this session. Keep your static balance unchanged and experiment in a separate working version.
- **October 14:** Revisit the balance in class. Compare your saved static mix with the processed version at similar loudness and identify what improved or became less clear.
- **October 16:** Bring a playable draft and your decision notes for feedback. Be ready to demonstrate one before-and-after comparison and ask about one unresolved problem.
- **October 23:** Submit the finished files to D2L by midnight.

## Set up the session

1. Unzip the recordings. In a new REAPER project, set the tempo to **96 BPM before importing audio**. In File > Project Settings, set the timebase for items to **Time** so later tempo changes do not stretch or move the recordings.
2. Import all source files onto separate tracks at the same starting position. Preserve their alignment; do not trim each track's leading silence independently. Play several tracks together to check the import.
3. Save into a new project folder using File > Save Project As. Check **Create subdirectory for project** and **Copy all media into project directory**.
4. Keep the numbered source names, beginning with `01_Kick`, and order the source tracks numerically within their instrument sections.
5. Create folder tracks named **Drums**, **Chords**, and **Vocals**. A folder is a parent track that receives audio from its child tracks. Create a track above each section, use its folder control to make it a parent, and use the last child's folder control to close that folder. Confirm the children are indented under the correct parent. Keep bass on its own clearly named track.
6. Give each instrument section a distinct color. Later, put the delay and reverb returns outside these folders so their audio does not feed back through a source folder.

## Build and save the static balance

Use faders, panning, and high-pass filtering only at this stage. Follow the [rough balance lesson](/lectures/week-6/rough-balance/) as you work.

1. Loop a representative, busy section such as a chorus. Avoid choosing the opening eight measures automatically; some instruments may not have entered yet.
2. Pull the **source-track faders** to `-inf dB`, which means silence. Leave the folder and master faders at 0 dB.
3. Rank the musical priorities. For this song, start with the lead vocal, then bring in drums, bass, chord instruments, and supporting parts one at a time. Adjust each part against what is already playing.
4. Keep kick, snare, bass, and lead vocal centered. Try matched pairs such as guitars or overheads left and right. Place supporting parts so the stereo balance feels even, and check in mono for anything important that becomes weak or disappears.
5. Complete the high-pass check below as you refine the balance. Aim for the **master meter to peak around -6 dBFS** in the loudest passage. This is a master headroom target, not a target for every individual track. Keep tracks and the master free of clipping. If the master rises too high, lower the source levels together while preserving their relative balance.
6. Listen through the whole song and adjust the static settings so quieter and busier sections both work.
7. Save `Lastname_Project3_Static.rpp` and render `Lastname_Project3_Static.wav`. Then save a separate working project as `Lastname_Project3_Final.rpp`. Keep all versions and their media in the same project folder.

## Equalization

### Check low frequencies on every source track

1. Insert **ReaEQ on every source track**. You do not need another instance on every folder or effects return to satisfy this requirement.
2. Select a band and change its type to **High Pass**. Begin with a low cutoff and raise it while listening until the instrument loses useful weight or body. Back the cutoff down until that useful sound returns.
3. Check the choice in the full mix and compare with the filter bypassed. Listen for less rumble or buildup without making the instrument thin. Vocals, guitars, and keys can contain lows that compete with kick and bass.
4. Treat kick and bass carefully because their low end supports the song. Do not apply the same cutoff to every track. Keep a very low cutoff, or bypass the high-pass band, if removing more low end damages the sound. Leave ReaEQ inserted so your session shows the check.

### Address tone and masking

After saving the static balance, identify at least two EQ decisions beyond high-pass cleanup. For one, listen to a competing pair such as kick and bass, guitars and keys, or the lead vocal and accompaniment.

Try a small cut or broad tonal adjustment on one part and compare the same passage with that EQ band enabled and disabled, leaving your high-pass setting unchanged. Keep the two versions at roughly equal loudness. Decide whether the change makes the important part clearer and what it costs the other instrument. If the change does not help, undo it and explain the comparison in your notes.

## Compression

Use the workflow from [Compression and when to use it](/lectures/week-5/compression/). Start with two source tracks whose level or transient behavior needs attention, such as the lead vocal and bass.

1. Name the problem before adding ReaComp. Does a phrase jump out, disappear, or need a different balance between its attack and sustain?
2. Insert ReaComp. Leave its Dry output at `-inf dB` for this basic insert exercise.
3. Start with a moderate ratio of **2:1 to 4:1**. Lower the threshold until you hear the effect and see roughly **2–6 dB of gain reduction on peaks**, then ease it if the result sounds flattened. These are starting points, not required final settings.
4. Use the lesson's source-specific attack and release ranges as starting points. Change one control at a time. Listen for preserved punch and a recovery that follows the phrase or groove without unwanted pumping.
5. Adjust ReaComp's Wet output level to compare processed and bypassed audio at roughly equal loudness. Judge it in the full mix, not only in solo.
6. Repeat on the second track. Explain what improved on each and any compromise you accepted.

Serial, parallel, and folder compression are optional extensions. You do not need them, a master limiter, or a mastered loudness target for this project.

## Delay

Follow [Delay, chorus, and flanger](/lectures/week-6/delay-new/) and the linked send tutorial.

1. Create a track named **Delay Return**, outside the instrument folders. Insert ReaDelay and set **Wet to 0 dB and Dry to -inf dB** so the return carries only the effect.
2. Drag from a source track's Route button to Delay Return to create a send. Use a post-fader send so the effect follows changes to the source fader. Start with the send level at `-inf dB` and raise it gradually.
3. On the same return, compare two settings, such as a short slapback and a longer rhythmic echo. Change delay time and feedback, listen to the same passage, and choose the version that supports the song. Use the lesson's timing examples or a tempo-synced note value as a starting point.
4. Check that the repeats do not obscure words or crowd the rhythm. Mute the return to compare the mix with and without delay. Keep at least one source feeding the return in the final mix.

You may share the return among several sources. A second or third delay return is optional if it serves a different audible purpose.

## Reverb

Follow [Mixing with reverb](/lectures/week-6/reverb/).

1. Create a track named **Reverb Return**, outside the instrument folders. Insert ReaVerbate and set **Wet to 0 dB and Dry to -inf dB**.
2. Add post-fader sends from selected source tracks. Begin with send levels at `-inf dB` and raise them gradually. Try a shared space for more than one instrument.
3. Compare two settings on the return, such as a smaller, shorter space and a larger, more sustained space. Adjust room size, damping, and initial delay; choose what helps the parts blend while keeping the lead clear.
4. Mute the return to compare the mix with and without reverb. Check quieter passages and the ends of phrases for tails that muddy the next sound. Keep the chosen reverb audible in the final mix, even if subtle.

A second reverb return or convolution reverb is optional.

## Listen and revise

Play the full song. Check the lead vocal, the kick-and-bass relationship, stereo balance, and the clarity of quieter passages. Revisit faders after adding processing.

Compare your final mix with your static WAV and the supplied reference at roughly equal loudness. Identify one improvement and one remaining limitation. A subtle effect can work well; make it obvious while testing, then reduce it to the amount the song needs.

## Submit

Submit these items to **D2L by midnight on October 23**:

1. **Final stereo WAV:** `Lastname_Project3_Final.wav`, rendered at **44.1 kHz / 24-bit**. Render the whole song, include the ending effects tails, and check the file for clipping and accidental silence.
2. **Static-balance stereo WAV:** `Lastname_Project3_Static.wav`, also rendered at **44.1 kHz / 24-bit**, for comparison.
3. **Zipped REAPER project folder:** Include the Static and Final `.rpp` files and all source audio. Before zipping, check that both projects open with no missing media and that the final session contains the required processing and routing.
4. **Four short decision notes:** Submit `Lastname_Project3_Notes.pdf` or `.docx`. A few sentences per note are enough:
   - **EQ:** Explain your high-pass approach, including a track where you preserved low end. Describe two additional tone or masking comparisons, including one competing pair, and say what you kept or rejected.
   - **Compression:** Name the two tracks, the problem on each, and what changed when you compared at similar loudness.
   - **Delay:** Describe the two settings you tested and why you kept your final choice.
   - **Reverb:** Describe the two spaces you tested and why the chosen setting helps the mix. Add one overall improvement over your static balance and one remaining limitation.

## Mixing project rubric (45 points total)

| Criterion | Exemplary | Proficient | Developing | Emerging | Points |
| --- | --- | --- | --- | --- | --- |
| **Session organization (4 pts)** | Sources aligned, named and ordered; folders route correctly; sections colored and returns separate | Session usable with a few organizational omissions | Alignment, folder structure, or naming needs repair | Session difficult to navigate or sources misaligned | /4 |
| **Balance and panning (9 pts)** | Musical priorities clear across the song; stereo and mono checks support the balance; no clipping and master headroom preserved | Balance works for most of the song with minor level or stereo issues | Several parts buried or dominant, or headroom inconsistent | Little balancing attempted or persistent clipping | /9 |
| **Equalization (8 pts)** | ReaEQ on every source; high-pass choices remove unnecessary lows while preserving body; two further EQ comparisons include masking and lead to justified choices | Most high-pass checks appropriate; further EQ choices generally help, with one comparison incomplete | Checks incomplete or cutoffs thin useful sounds; tone or masking decisions weak | No systematic low-frequency check or EQ choices damage the mix | /8 |
| **Compression (6 pts)** | Two source tracks processed for clear purposes; dynamics or transient shape improved without unwanted flattening | Two tracks compressed with mostly useful results | Only one track processed, or settings work against the stated goal | No compression or processing seriously harms the balance | /6 |
| **Delay (4 pts)** | Fully wet return with correct sends; contrasting settings tested and chosen delay supports clarity or rhythm | Return routed correctly and delay generally supports the song | Routing or settings unclear, or repeats crowd important parts | No functioning delay return | /4 |
| **Reverb (4 pts)** | Fully wet return with correct sends; contrasting spaces tested and chosen reverb adds cohesion or depth without masking | Return routed correctly and reverb generally supports the song | Routing or settings unclear, or reverb muddies the mix | No functioning reverb return | /4 |
| **Listening and decisions (5 pts)** | Four concise notes connect audible problems, comparisons, choices, and tradeoffs; static-to-final improvement and limitation identified | All four notes present with mostly specific reasons; comparisons or tradeoffs need detail | Notes describe controls with little listening evidence, or some notes missing | Notes absent or choices unexplained | /5 |
| **File preparation (5 pts)** | Both WAVs play correctly; zipped Static and Final projects open with all media; files named as requested | All files usable with minor naming or format issues | One required audio/project item missing or media incomplete | Multiple required files missing or unusable | /5 |

**Total: ____ / 45**
