---
title: "Angels in Amplifiers Mix"
number: "03"
weight: 3
week: 8
assigned: "2026-10-14"
due: "2026-10-23"
summary: "Complete a multitrack mix using EQ, compression, delay, and reverb. Critical listening and technical mixing."
tools: ["REAPER", "ReaEQ", "ReaComp"]
# this project carries its own rubric table in the body
rubric: false
---
 
We'll use all we have learned so far about mixing to create a rough mix of Angels In Amplifiers song _I'm Alright_. You can download the project files [here](https://mtkdata.cambridgemusictechnology.co.uk/MTK006/AngelsInAmplifiers_ImAlright.zip). Click [here](https://previews.cambridge-mt.com/ImAlright_Preview.mp3) to listen to a mixed version of this song. The engineer is using some techniques that we haven't learned yet, but the mix does show good use of balance, equalization, compression, and reverb. 

You'll follow the steps below to complete your own mix for this song. 

- Every track should use a ReaEQ
- at least two tracks should use ReaComp
- use three delays with different settings as sends
- use at least two reverbs with different settings as sends 

## Organization

**1. Set Your Project Tempo to 96 BPM:** 
   - Locate the tempo settings in the bottom right-hand corner of Reaper.
   - Change the tempo to 96 beats per minute (BPM). This helps you align recordings accurately with your project timeline.

**2. Order Your Tracks Numerically:**
   - Start with `01_Kick` and continue from there. 

**3. Group the Tracks by Type:**
   - Create three groups for your tracks: "Drums," "Chords," and "Vocals."
   - To assign tracks to these groups, simply drag and drop them into the appropriate group.

**4. Color-Code Each Group:**
   - Assign a unique color to each of the three groups: one color for "Drums," another for "Chords," and a third for "Vocals."

## Build a mix

> Tip: to get more fine-grained control over parameters press ctrl (cmd on Mac) + drag.

**1. Initialize the Mix:**
   - Start with all faders set to "-inf dB" (infinity decibels), which effectively mutes all tracks.

**2. Set Time Selection and Repeat:**
   - Set your time selection to cover the entire duration from the start to the end of measure 8 in your project.
   - Enable the "toggle repeat" function (looping) for this time selection. This ensures that the same section will play repeatedly as you work on it.

**3. Determine Element Order:**
   - Decide the order of importance for bringing in elements. Commonly, you might start with foundational elements like drums or bass and gradually introduce other instruments, vocals, or effects. The choice depends on your specific project and musical style.

**4. Bring in Elements:**
   - Gradually increase the fader levels for each element according to the order of importance you decided in step 3.
   - As you bring in each element, keep an eye on the meters in your software to ensure that you're not clipping. Ideally, aim to peak at around -3 to -6 dB to leave headroom for additional processing and prevent distortion.

**5. Monitor and Adjust Levels:**
   - Continuously monitor the meters as you add more elements to the mix.
   - If you notice any tracks peaking above your target range of -3 to -6 dB, reduce their levels using their respective faders. This helps prevent clipping and maintains a balanced mix.
   - Remember the rule from the [rough balance lesson](/lectures/week-6/rough-balance/): to make something louder, turn other things down.

**6. Pan Your Tracks:**
   - Keep the kick, bass, and lead vocal in the center.
   - Split matched pairs (like the two guitar tracks) left and right to create width.
   - Place the remaining elements off-center so the two sides stay roughly balanced.
   - Check your mix in mono to make sure nothing important disappears.

## Equalization

**1. Apply High-Pass Filters:**
   - Start with all tracks playing in your mix.
   - Identify instruments with low-frequency content that might contribute to low-frequency buildup. These are typically instruments like bass, kick drum, and potentially some piano or guitar tracks.
   - For each of these instruments, apply a high pass filter to remove unwanted low frequencies. Here's how to do it:
     - Select the track or channel of the instrument in Reaper.
     - Open a ReaEQ plugin or channel strip for that track.
     - Locate the high-pass filter option.
     - Set the filter frequency to a point where it removes unnecessary low frequencies without affecting the instrument's tone negatively. A common starting point is around 20-40 Hz for most instruments.

**2. Listen for Masking:**
   - Play your mix and listen carefully for any instances where instruments might be masking each other. Masking occurs when two or more instruments occupy the same frequency range, making it hard to distinguish them in the mix.

**3. Identify Masking Pairs:**
   - Specifically, pay attention to the following areas:
     - Guitar vs. Piano
     - Kick Drum vs. Bass Guitar
     - Vocals vs. Other Instruments

**4. Address Masking with EQ:**
   - Once you've identified masking, select the instrument that you want to reduce the frequencies of.
   - Open the EQ plugin for that instrument's track.
   - Find the frequency range where masking is occurring. You can do this by sweeping an EQ band's frequency control while listening for the most problematic frequencies.
   - Reduce the volume of the problematic frequencies in one of the instruments by lowering the corresponding EQ band. This carves out space for the other instrument in the mix.
   - Repeat this process for any other masking pairs you've identified.

**5. Adjust in Context:**
   - Judge every EQ move in the full mix, and A/B against the unprocessed version before you commit.

## Compression

**1. Listen for Inconsistent Elements:**
   - Play your mix and listen attentively for any elements that appear to stick out of the mix inconsistently. These might be instruments or vocals that sometimes become too prominent.

**2. Listen for Elements Getting Drowned Out:**
   - Similarly, identify elements that seem to get drowned out or buried in the mix at certain points. These are the elements that may benefit from compression to maintain a more consistent presence.

**3. Identify Compression Candidates:**
   - Based on your observations, determine which elements in your mix require compression. Good candidates include vocals, the drum folder, the drum overheads, and the bass guitar.

**4. Apply Compression:**
   - Start with one of the elements you identified, such as the vocals.
   - Insert a ReaComp on that track.

**5. Configure ReaComp:**
   These starting points come from Senior's compression chapter, the same book behind our rough balance lesson.
   - Begin by pinning about 6 dB of gain reduction on the peaks, so you can clearly hear what the compressor is doing. Then raise the threshold until you keep the balance with less squeeze.
   - Set the ratio between 2:1 and 3:1 for routine evening on vocals and guitars. Save high ratios of 12:1 and up for taming isolated peaks.
   - On the kick and bass, keep the attack at 50 ms or slower. Faster attacks clamp the first waveform cycles and thin out the low end.
   - On the drum folder, the attack and release decide what the drums become: a fast attack with a fast release brings up sustain, while a slow attack with a slow release sharpens the snap. Set them so the gain-reduction meter bounces in time with the song.
   - If vocal peaks still poke through, add a second ReaComp in series doing 2 to 3 dB of reduction rather than making one compressor work hard.
   - With ReaComp, the Wet slider acts as the makeup gain.

**6. Check Your Work:**
   - A/B the compressed track against the bypassed version in the full mix, and confirm the element now holds a steadier place without sounding squashed.

## Delay

- Add three delay sends with three different lengths of delays
- try them on different instruments with different amounts, use your ears. You can do this by routing the dry signal of a track to the send with the delay on it. 
- Delays on vocals can make them sound bigger without pushing them back in the mix
- Delays on chord instruments can sound great as well. Try using rhythmic delays to get an interesting movement to your mix.

**1. Add Three Delay Sends with Different Lengths:**
   - Create three separate tracks to act as your delay sends. Label them accordingly for clarity.

**2. Set Up Different Delay Lengths:**
   - On each of the delay aux tracks, insert a delay plugin.
   - Configure the settings of each delay plugin to have distinct delay lengths, measured in milliseconds:
     - Delay 1: Short delay (e.g., 1-50ms)
     - Delay 2: Medium delay (e.g., 50-400ms)
     - Delay 3: Long delay (e.g., 500-800ms)

**3. Route Dry Signal to Delay Sends:**
   - Choose the track or tracks that you want to apply delay to (e.g., vocals and chord instruments).
   - Click on the route button then drag while clicking onto the delay send you want to use. 
   - Adjust the send level to control the amount of signal sent to the delay. Start with a moderate level.
   - Note: a single track will probably only go to one delay send, but each delay send will have multiple tracks sent to it. 

**4. Idea 1: Apply Delays to Vocals:**
   - On your vocal track(s), use one of the delay sends you've created (e.g., Short Delay).
   - Play back your mix and listen to how the delay affects the vocals. Delays on vocals can create a sense of spaciousness without pushing them too far back in the mix.
   - Adjust the send level on the vocal track and fine-tune the delay settings until you achieve the desired effect. Trust your ears during this process.

**5. Idea 2: Apply Delays to Chord Instruments:**
   - On your chord instrument track(s), use another one of the delay sends (e.g., Medium Delay or Long Delay).
   - Experiment with different delay lengths to achieve unique effects, such as rhythmic delays that add movement to your mix.
   - Adjust the send level and delay settings on each chord instrument track to create an interesting and balanced sonic texture.

**6. Check Your Work:**
   - Listen to how the delays sit against the vocals and chords in the full mix, and adjust send levels or delay times until they support the balance instead of clouding it.


## Reverb

- Try reverb on instruments that you want to sound like are coming from the same space.
- Reverbs can also be used to make an instrument sound large. Be careful, as this can often push the instrument back in the mix.
- Use at least two reverb sends. 
- Follow the same guidelines to setup the sends as with the delay effects. 

### Mixing Project Rubric (45 points total)

| Criterion | Exemplary | Proficient | Developing | Emerging | Points |
| --- | --- | --- | --- | --- | --- |
| **Session Organization (5 pts)** | Tempo set, tracks ordered, groups built, and color coding applied throughout | Most organization steps done, with a few tracks left out | Some organization attempted; several steps missing | Session opened and mixed as delivered | /5 |
| **Balance and Panning (8 pts)** | Faders and panning place every element in its own space across the stereo field | Most elements balanced and placed; a few crowd the center | Balance uneven, with elements too loud, too quiet, or stacked in the center | Faders and pans left at default | /8 |
| **Equalization (8 pts)** | EQ clears low frequencies from tracks that do not need them and resolves masking between competing parts | EQ applied to several tracks to control problem frequencies | EQ present on one or two tracks with little audible effect | No EQ used | /8 |
| **Compression (6 pts)** | Compression on two or more tracks, with settings that steady the dynamics rather than flatten them | One track compressed in a way that works | Compression applied where it is not needed, or settings undo the intent | No compression used | /6 |
| **Delay (6 pts)** | Three delay sends, each with a purpose you can hear in the mix | Two or three sends created and used adequately | One send created, or a send that does not change the mix | No delay sends created | /6 |
| **Reverb (6 pts)** | Two or more reverb sends used to place elements in a shared space | One or two reverbs used reasonably well | Reverb on tracks that do not need it, or set so it muddies the mix | No reverb used | /6 |
| **Overall Mix (6 pts)** | Every part is audible and sits in a coherent space; effects serve the mix rather than decorate it | Mostly balanced, with good use of some tools | Balance and effect choices both need work | Unbalanced, with no effects used | /6 |

**Total: \_\_\_ / 45**
