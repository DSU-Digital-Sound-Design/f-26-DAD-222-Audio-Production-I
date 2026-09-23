+++
title = "Mixing and EQ"
outputs = ["Reveal"]
[reveal_hugo]
margin = 0.12
+++

## Mixing and EQ

EQ boosts or cuts selected frequency ranges.

- Describe the change you want to hear.
- Choose a filter and adjust it.
- Compare at a similar loudness, in context.

{{% note %}}
Use ReaEQ throughout. Mike Senior's subtractive approach is one useful starting method, not a ban on boosts. EQ can correct problems, shape tone, or create an effect. For mix decisions, judge whether it helps the part serve the song.
{{% /note %}}

---

## ReaEQ controls

- **Frequency:** where the adjustment acts.
- **Gain:** how much to boost or cut.
- **Bandwidth:** how wide a range it affects.
- **Output gain:** match the processed level for comparison.

{{% note %}}
Show one bell in ReaEQ. Change each control separately. ReaEQ displays bandwidth in octaves: a larger value means a wider band. Other EQs use Q, where a larger value means a narrower band. Do not use these terms interchangeably.
Reference: https://dlz.reaper.fm/userguide/REAPEREffectsGuide2021.pdf
{{% /note %}}

---

## Filter shapes

- **Bell:** boost or cut around a chosen frequency.
- **Shelf:** raise or lower a broad low or high range.
- **High-pass:** reduce frequencies below the cutoff.
- **Low-pass:** reduce frequencies above the cutoff.

{{% note %}}
Show the curves in ReaEQ and ask students which one would reduce low rumble. A high-pass passes the highs. Save detailed settings and independent experimentation for the loop exercise.
Reference: https://www.fabfilter.com/learn/equalization/introduction-to-eq
{{% /note %}}

---

## Better, or just louder?

1. Hear a short passage with EQ bypassed.
2. Add a broad boost and listen again.
3. Match the output loudness and compare.

What changed in the tone? Which version serves the mix?

{{% note %}}
Demonstrate a broad boost of roughly 3 dB on a familiar track. Get an initial vote, lower the processed output to a comparable perceived loudness, then repeat. Use the same passage. Similar peak readings alone do not guarantee equal perceived loudness. Accept either preference if students can describe the change.
{{% /note %}}

---

## Try a cut first

- Reduce an excess before adding more elsewhere.
- Boost when a useful part of the tone needs emphasis.
- Leave headroom and compare at matched loudness.
- If the whole track is too quiet, try its fader.

{{% note %}}
Senior's cut-first method helps students avoid mistaking added loudness for improvement. His boost limits are heuristics, not technical limits. Both boosts and cuts can alter phase in conventional EQ; phase shift is not automatically audible damage. Filter shape, bandwidth, and slope matter. Avoid teaching that boosts alone cause phase problems.
Sources: Senior, ch. 11; https://www.fabfilter.com/learn/equalization/linear-phase-eq
{{% /note %}}

---

## High-pass with a purpose

- Listen for rumble or low end the part does not need.
- Raise the cutoff until the sound loses useful body.
- Back it down and compare in the mix.
- Keep the filter only if it helps.

{{% note %}}
Demonstrate on an Angels in Amplifiers guitar. Move too far, identify the lost body, then back off. Senior's broad high-pass recommendation is a starting strategy, not a requirement for every non-bass track. Kick and bass may also need rumble removal. Listen to drum attacks as well as sustained tone. Do not promise a lower peak meter reading: filtering changes waveform shape and may increase peaks.
{{% /note %}}

---

## Finding a resonance

1. Identify a problem by listening first.
2. Use a narrow, temporary boost to locate it.
3. Reset the gain and listen unprocessed.
4. Try a small cut, then compare in context.

{{% note %}}
Keep monitoring comfortable during a sweep. Exaggeration is diagnostic, not the final sound. Pause about ten seconds after resetting to avoid judging only against the exaggerated version. ReaEQ uses bandwidth: reduce bandwidth to narrow the bell.
Source: Senior, ch. 11.
{{% /note %}}

---

## When a sweep misleads

- A large narrow boost can make many frequencies unpleasant.
- Search for a problem you already heard.
- Avoid cutting every peak on the analyzer.
- Bypass the cut: did the original problem return?

{{% note %}}
Ask students to explain the difference between finding an existing resonance and creating an unpleasant sound with the test filter. If they cannot hear a useful improvement after level matching, remove the adjustment.
{{% /note %}}

---

## Masking in the mix

- One sound can make another harder to hear.
- Check balance and arrangement before reaching for EQ.
- Try a cut on the part that can spare that range.
- Judge the result with both parts playing.

{{% note %}}
Masking depends on level and spectral content; shared frequency ranges do not automatically require a cut. Solo or isolated pairs can help diagnosis, but return to the full mix for the decision. Mono can reveal interactions hidden by stereo separation. EQ is one option alongside level, panning, and arrangement.
Sources: Senior, ch. 11; https://www.izotope.com/en/learn/unmasking-your-mix-with-neutron
{{% /note %}}

---

## Making room for a vocal

- Listen to the vocal with its accompaniment.
- Lower the competing instrument slightly.
- Compare that with a small EQ cut on the accompaniment.
- Which preserves the balance while helping the words?

{{% note %}}
Use a familiar multitrack passage available for demonstration. Keep the excerpt and vocal level consistent. Students describe the tradeoff instead of assuming EQ must win. If using Adele's "Hello" as a listening reference, discuss the audible piano/vocal contrast without claiming access to isolated tracks or proving a particular production technique.
{{% /note %}}

---

## Frequency landmarks: low end

| Approximate range | Listen for |
| --- | --- |
| Below 150 Hz | Weight and rumble |
| 150–400 Hz | Body or muddiness |
| 400–500 Hz | Boxiness |
| 600–800 Hz | Honk |

Treat these as places to investigate, not fixed settings.

{{% note %}}
Adapted from Corbett, Mic It!, ch. 2. Boundaries vary with the source, register, arrangement, and listener. A descriptor is a listening hypothesis, not a diagnosis. Keep body when removing mud.
{{% /note %}}

---

## Frequency landmarks: upper range

| Approximate range | Listen for |
| --- | --- |
| 1–1.6 kHz | Nasal tone |
| 2–4 kHz | Presence or harshness |
| 5–8 kHz | Brightness or sibilance |
| Above 12 kHz | Air |

The same range may help one source and hurt another.

{{% note %}}
Adapted from Corbett's listening vocabulary. These deliberately overlapping descriptions are not universal thresholds. Avoid defining 2–3 kHz as inherently "cheap" or "tinny." Let students describe an example before suggesting a label.
Further reference: https://www.fabfilter.com/learn/equalization/frequency-range-characteristics
{{% /note %}}

---

## Instrument ranges

<a href="DBS_PosterHearingVoicingRange.en.x1024.png" target="_blank" rel="noopener"><img src="DBS_PosterHearingVoicingRange.en.x1024.png" alt="Frequency-range chart for hearing, voices, and instruments" style="display:block;max-height:380px;max-width:100%;width:auto;margin:auto"></a>

[Open the full-size chart](DBS_PosterHearingVoicingRange.en.x1024.png)

{{% note %}}
This is an overview, not a chart students should read from the back of the room. Open the image to inspect details. Point out that instruments overlap and that harmonics extend above fundamentals; EQ cannot neatly separate all instruments in a mixed loop.
{{% /note %}}

---

## Guess the range

- Listen to pink noise at a comfortable level.
- Choose: **500 Hz, 1 kHz, or 2 kHz**.
- Write your answer before the reveal.
- Explain what you heard, then try again.

{{% note %}}
Use a prepared EQ with three center-frequency choices, a consistent boost and bandwidth, and a conservative output level. Begin with a labeled example of each, then give three unlabeled trials with immediate feedback. Corey's larger boosts are an ear-training exaggeration, not a mixing recommendation. Pink noise has equal energy per octave, but changes are not equally audible at every frequency or listening level.
Source: Jason Corey, Audio Production and Critical Listening, 2nd ed.
{{% /note %}}

---

## From boosts to cuts

- Repeat a familiar frequency with a cut.
- Toggle bypass and listen for what returns.
- Try the same region on a musical passage.
- Describe the change before calling it better.

{{% note %}}
Keep this a brief demonstration. Expand to more octave bands in later practice once the first three are reliable. Short regular drills are more useful than rushing through nine unfamiliar frequencies in one sitting. The loop lab applies this listening vocabulary to complete recordings; the later multitrack lab provides individual instrument control.
{{% /note %}}

---

## Before keeping an EQ move

- Can you name the problem or intended effect?
- Does the change help at a similar loudness?
- Does it work in the full mix?
- What useful tone did you lose?

{{% note %}}
Exit check: a guitar seems clearer after a 4 dB high shelf. What must you check before keeping it? Listen for level-matched bypass, mix context, and possible added harshness. Then ask why EQ on a mixed loop can affect several instruments at once. This prepares students for the limits of the next exercise without replacing it.
{{% /note %}}

---

## References for the lab

- [Music frequency cheatsheet](musicfrequencycheatsheet.pdf)
- [REAPER effects guide: ReaEQ](https://dlz.reaper.fm/userguide/REAPEREffectsGuide2021.pdf#page=17)
- [EQ exploration assignment](/lectures/week-5/eq-assignment/)

Use the chart to choose a starting region. Let listening decide the final setting.

{{% note %}}
Open PDFs separately so students can zoom and scroll. Embedded document viewers do not fit reliably on a projected slide. The upcoming loop exercise allows broad experiments; do not present its suggested ranges as guaranteed fixes for isolated instruments within a full mix.
{{% /note %}}

---

## Sources

- Mike Senior, *Mixing Secrets for the Small Studio*, ch. 11–12.
- Ian Corbett, *Mic It!*, 2nd ed., ch. 2.
- Jason Corey, *Audio Production and Critical Listening*, 2nd ed.

{{% note %}}
The original deck cites Senior's third edition, Corbett's second edition (2020), and Corey's second edition (2016). Bibliographic details are retained here as supplied, not independently checked against the books.
Technical cross-checks: FabFilter Learn, Introduction to EQ; Linear phase EQ; Frequency range characteristics. iZotope, Unmasking Your Mix with Neutron. Links appear in the relevant slide notes.
{{% /note %}}
