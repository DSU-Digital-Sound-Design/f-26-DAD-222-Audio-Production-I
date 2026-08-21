+++
title = "Mixing and EQ"
outputs = ["Reveal"]
[reveal_hugo]
+++

## Mixing and EQ

Equalization shapes the frequency content of a signal by boosting or cutting selected ranges. Today we learn one method for using it, taken from Mike Senior's *Mixing Secrets for the Small Studio*.

{{% note %}}
- The whole lesson runs on ReaEQ. Every technique here works in the stock plugin.
- Frame the goal early: EQ at mixdown exists to make room between instruments. Making any single track prettier is secondary.
{{%/ note %}}

---

## Cut first, boost last

Senior gives four reasons to make cutting your default:

1. Louder sounds better to your brain, so a boost fools you with volume alone.
2. A boost distorts phase most exactly where you boosted.
3. EQ filters ring, and cuts hide the ringing while boosts expose it.
4. Boosts eat headroom.

His rule of thumb: if you need more than one boost filter, or more than 6 dB, back off the EQ and push the fader instead.

{{% note %}}
- Demonstrate the loudness bias directly: boost a track 3 dB with a wide bell, ask if it sounds better, then match the volume back down and ask again.
- Source: Senior, ch. 11, "Equalizing for a Reason."
{{%/ note %}}

---

## High-pass almost everything

- Every track except the kick and the bass gets a high-pass filter.
- Use Roger Nichols' rule to set it: raise the cutoff until you hear the low end change, then back it off by about 15 percent.
- Keep the slope moderate, between 6 and 18 dB per octave, with no resonance.
- Be careful on drums, because the transient dulls before the tone audibly changes.

{{% note %}}
- The point of filtering everything is headroom: dozens of tracks each carrying inaudible rumble add up to real low-end mud on the mix bus.
- Have students HPF the Angels in Amplifiers guitars while watching the master meter.
- Source: Senior, ch. 11.
{{%/ note %}}

---

## Boost, sweep, cut

1. Set a narrow band and boost it 10 dB or more.
2. Sweep the frequency until the ugly resonance jumps out.
3. Return the gain to zero for ten seconds and let your ears reset.
4. Cut gently at the frequency you found.

The trap: any frequency boosted 10 dB sounds terrible. Hunt only for problems you already heard in the mix, and resist sweeping every track on principle.

{{% note %}}
- The ten-second reset step is the one students skip, and it is the one that keeps them from cutting the wrong thing. Enforce it in the lab.
- Source: Senior, ch. 11.
{{%/ note %}}

---

## Masking is EQ's real job

- Two instruments in the same range hide each other. That collision is called masking.
- Never make EQ decisions in solo, because masking only exists in the full mix.
- Check your work in mono, where clashes get more obvious.
- When two parts fight, the less important one takes the cut.

You can also brighten a track by darkening its neighbors. Senior's example is Adele's "Hello," where a deliberately dark piano makes an ordinary vocal sound brilliant.

{{% note %}}
- Play "Hello" and have students describe the piano in isolation versus in context.
- Connect this to the rough balance lesson: the order you brought tracks in is also the order of who wins a masking fight.
- Source: Senior, ch. 11. His ch. 12 covers what to do when the frequencies you want are not in the recording at all.
{{%/ note %}}

---

## Learn the landmarks

Corbett's ear-training guide to the spectrum:

| Range | What you hear |
|---|---|
| below 150 Hz | weight |
| 150 - 400 Hz | thickness, and mud when overdone |
| 400 - 500 Hz | boxiness |
| 600 - 800 Hz | honk |
| 1 - 1.6 kHz | nasal tone |
| 2 - 3 kHz | cheap, tinny tone |
| 4 kHz | harshness, but also vocal clarity |
| 8 kHz | brightness and sibilance |
| above 12 kHz | air |

These are landmarks for your ears, not recipes. Senior refuses to print a recommended-frequencies chart at all, because every key, singer, and arrangement moves the numbers.

{{% note %}}
- Source for the table: Corbett, *Mic It!*, ch. 2. Source for the refusal: Senior, ch. 11.
{{%/ note %}}

---

![](./DBS_PosterHearingVoicingRange.en.x1024.png)

{{% note %}}
This poster maps the hearing range and where common instruments sit in it. It pairs with the landmarks table on the previous slide.
{{%/ note %}}

---

## Audio frequency spectrum

| Band | Range | Characteristics |
|---|---|---|
| Low (sub and bass) | 20 Hz - 250 Hz | Adds weight and warmth |
| Low mids | 250 Hz - 500 Hz | Thickness and body |
| Mids | 500 Hz - 2 kHz | Core harmonic content |
| High mids | 2 kHz - 4 kHz | Clarity and articulation |
| Highs | 4 kHz - 20 kHz | Air and sparkle |

{{% note %}}
This is the reference table students screenshot. The ranges are guidelines; the landmarks table gives the finer vocabulary.
{{%/ note %}}

---

## Guess the range

We train the way Corey's ear-training course does:

1. The source is pink noise, which carries equal energy per octave, so a change anywhere is equally audible.
2. We start with +12 dB boosts at only three frequencies: 500 Hz, 1 kHz, and 2 kHz, at Q 2.
3. Once those land, we widen to the nine octave frequencies from 63 Hz to 16 kHz.
4. Then we switch to cuts, which are much harder to hear. Toggle bypass and listen for the band that reappears.

{{% note %}}
- Corey recommends short daily drills, 10 to 15 minutes, over long cramming sessions. Point students at TrainYourEars or SoundGym for practice between classes.
- Source: Jason Corey, *Audio Production and Critical Listening*, 2nd ed., which defines this exact drill progression.
{{%/ note %}}

---

**Frequency cheatsheet**

<iframe src="musicfrequencycheatsheet.pdf" style="width:100%; height: 700px"></iframe>

---

**Reaper effects guide**

<iframe src="https://dlz.reaper.fm/userguide/REAPEREffectsGuide2021.pdf#page=17" style="width:100%; height: 700px"></iframe>

---

## Sources

- Mike Senior, *Mixing Secrets for the Small Studio*, 3rd ed. (Focal Press, 2026), ch. 11 "Equalizing for a Reason" and ch. 12 "Beyond EQ."
- Ian Corbett, *Mic It!*, 2nd ed. (Routledge, 2020), ch. 2.
- Jason Corey, *Audio Production and Critical Listening: Technical Ear Training*, 2nd ed. (Routledge, 2016).
