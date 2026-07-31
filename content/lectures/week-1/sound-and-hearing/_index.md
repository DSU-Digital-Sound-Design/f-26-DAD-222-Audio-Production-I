+++
title = "Sound and hearing"
outputs = ["Reveal"]
[reveal_hugo]
theme = "moon"
margin = 0.2
separator = "##"
+++

## Introduction to Sound and Hearing

### What You'll Learn
- Basics of sound: amplitude, frequency, phase, and harmonics
- How the ear processes sound
- Introduction to psychoacoustics: How we perceive sound
- Practical implications for audio production

{{% note %}}
This slide sets the stage for the presentation by outlining what students will learn and why it's important. Emphasize that these fundamentals will be referenced throughout their studies and careers.
{{%/ note %}}


---

## Sound areas

- The basics of sound
- The characteristics of the ear
- How a sound stimulates the ear
- The psychoacoustics of hearing

---

The Transducer

device -> energy conversion -> resulting energy

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Django_Reinhardt_%28Gottlieb_07301%29.jpg" width="50%" alt="https://commons.wikimedia.org/wiki/File:Django_Reinhardt_(Gottlieb_07301).jpg">


{{% note %}}
ex:
guitar - vibrations -> amplified by wood -> converted into sound pressure waves that we perceive as sound

What types of devices could be considered transducers?

- microphone
- etc

{{%/ note %}}

---

![](transducers.png)

---

## The basics of sound

![](the-daily-show-john-oliver.gif)

{{% note %}}
Sound arrives at the ear as periodic variations in atmospheric pressure called sound-pressure waves. This atmospheric pressure is the same as the weather service measures. The changes in pressure heard by the ear are too small in magnitude and fluctuate too rapidly to be observed on a barometer.

It is sort of like when you pop a balloon!

{{%/ note %}}

---

![](wave-prop.jpg)

{{% note %}}
Any vibrating mass, such as the voice or guitar, causes compression and rarefaction creating areas of high and low-pressure states. These pressure states move the sound wave out from the source, allowing us to hear it.

This diagram is helpful, but this is not usually how we visualize sound. We do it with a waveform, a graphic representation of the sound-pressure level. Looking at the waveform, we can tell if the sound is quiet or loud and sometimes the frequency of the sound.
{{%/ note %}}

---

## Understanding Amplitude

### Key Concepts
- Amplitude measures the strength or intensity of a sound wave.
- It directly relates to perceived loudness.

{{% note %}}
Introduce the concept of amplitude here. Stress that amplitude is a fundamental aspect of how we perceive sound, and it directly affects the loudness we hear.
{{%/ note %}}

---

## Amplitude

![](amplitude.png)

{{% note %}}
The distance above or below the centerline of a waveform (such as a pure sine wave) represents the amplitude level of that signal. The greater the distance or displacement from that centerline, the more intense the pressure variation, electrical signal level or physical displacement will be within a medium.
{{%/ note %}}

---

## Amplitude in the Real World

- **Example:** Think about the difference in loudness between a whisper and a shout.
- **Interactive Example** [amplitude](https://contrib.pbslearningmedia.org/WGBH/buac20/buac20-int-wavesamplitude/index.html)
- **Tip:** When recording, always monitor amplitude levels to avoid distortion.

{{% note %}}
Use this slide to connect the concept of amplitude to everyday experiences. Play the sound clip and ask students to describe what they hear. Reinforce the importance of monitoring levels in recording.
{{%/ note %}}

---

## Understanding Frequency

### Key Concepts
- Frequency refers to the number of cycles per second in a sound wave.
- It determines the pitch of the sound.

![](frequency.png)

{{% note %}}
Transition into the concept of frequency. Explain that frequency is crucial for understanding pitch, which is another fundamental aspect of sound.

The rate at which an acoustic generator, electrical signal, or vibrating mass repeats within a cycle of positive and negative amplitude is known as the frequency of that signal.

We can also measure a frequency in cycles per second; (Hz) or hertz (Hz). An "A" note is 440 Hz.
{{%/ note %}}

---

## Frequency in Action

- **Example:** A bass note versus a high-pitched whistle.
- **Interactive Example** [frequency](https://contrib.pbslearningmedia.org/WGBH/buac20/buac20-int-wavesfreq/index.html)
- **Tip:** Different frequencies interact in complex ways in a mix. 

{{% note %}}
Play the sound clip and discuss how low and high frequencies differ in sound. Highlight the importance of understanding frequency when working with EQ and other audio tools.
{{%/ note %}}

---

## Phase Relationships

- **Key Concept:** Phase refers to the timing relationship between two sound waves.
- **Impact:** Out-of-phase waves can cancel each other out, leading to a reduction in sound.
- **Sound Demo:** [Phase](https://youtu.be/bc1Z1ck9hKQ)

![](phase.png)

{{% note %}}
Discuss the concept of phase, emphasizing how out-of-phase signals can lead to issues like phase cancellation. Use the demo to show this effect in practice.
{{%/ note %}}

---

[Random phases - square and sawtooth](https://tomasboril.cz/fourierseries3d/en/)

---


## Harmonic Content

- **Key Concept:** Harmonics are additional frequencies in a sound that define its timbre.
- **Real-World Example:** Why a guitar and piano sound different, even when playing the same note.
- **Sound Clips:** [Fourier Series 3D interactive demonstration](https://tomasboril.cz/fourierseries3d/en/)
  
{{% note %}}
Explain harmonics and how they contribute to the unique sound of different instruments. Use the sound clips to demonstrate these differences in timbre.

Most real life sounds are much more complex than a sine wave.

The factor that helps us differentiate between instrumental “voicings” is the presence of frequencies (called partials) that exist in addition to the fundamental pitch that’s being played. Partials that are higher than the fundamental frequency are called upper partials or overtones. If the overtones are whole-number multiples of the fundamental frequency, they are called harmonics.

Harmonics also form the basis of synthesis.
{{%/ note %}}

---

# The Decibel

![](db.webp)

{{% note %}}
Variations in sound pressure level or SPL and is measured on a logarithmic scale in decibels (dB).
{{%/ note %}}

---

# The Ear

![](Anatomy-of-the-Ear2.jpg)

{{% note %}}
* Sound is collected by the pinna. 
* Then it travels through the eardrum, which vibrates, converting sound-pressure waves into mechanical vibrations. 
* The sound then goes to the cochlea, this snail looking organ covered in tiny hair receptors. It is here that we perceive frequencies of a sound.
{{%/ note %}}

---

## Introduction to Psychoacoustics

- **What Is It?** Psychoacoustics explores how our brain interprets sound.
- **Key Concepts:** Pitch perception, loudness perception, and spatial hearing.

{{% note %}}
Introduce the concept of psychoacoustics and explain why it's important in audio production. Stress that this field helps us understand how listeners perceive the sounds we create.
{{%/ note %}}

---

## Psychoacoustic Masking

- **Key Concept:** One sound can make another harder to hear, especially if they are close in frequency.  
- **Example:** Kick drum and bass guitar often mask each other.  
- **Why It Matters:** MP3 and AAC compression rely on masking to discard “inaudible” sounds.  

**Interactive Demo:** [Auditory Masking Experiment (Music Perception Lab)](https://auditoryneuroscience.com/index.php/scene_analysis/masking_tone_noise/)  

{{% note %}}
Play a steady low-frequency tone, then add a second tone slightly above it.  
Ask students if they can hear both equally. Often, the first tone seems to fade or disappear.  
Relate this to mixing challenges and codec design.  
{{%/ note %}}

---

## Binaural Beats

- **Key Concept:** Two slightly different frequencies, one to each ear, produce a perceived “beat” at the difference frequency.  
- **Example:** 440 Hz in the left ear and 446 Hz in the right ear produces a 6 Hz beat.  
- **Why It Matters:** Shows how the brain constructs sound beyond the ear.  

**Interactive Demo:** [Binaural Beats Generator](https://mynoise.net/NoiseMachines/binauralBrainwaveGenerator.php/)  

{{% note %}}
Use headphones!  
This demo highlights how perception emerges in the brain, not just in the ears.  
Connect it to psychoacoustics concepts like spatial hearing and pitch perception.  
{{%/ note %}}

---

## Auditory Perception

![](fm-curve.png)

{{% note %}}
This is the **equal-loudness contour graph** (also called Fletcher–Munson curves).  

**What it shows:**  
- **X-axis (Hz):** frequency, from bass (20 Hz) to treble (20,000 Hz).  
- **Y-axis (dB SPL):** physical loudness level.  
- **Curves:** each line shows tones judged as equally loud by listeners.  
- The numbers on the curves are in **phons**, matched to the loudness of a 1,000 Hz tone at that level.  

**Why multiple lines?**  
- Each curve starts with a different **reference loudness** at 1,000 Hz.  
- Example: a 40-phon contour = 1,000 Hz tone at 40 dB SPL used as the reference.  
- An 80-phon contour = 1,000 Hz tone at 80 dB SPL.  
- Listeners adjusted other frequencies until they sounded equally loud, producing this family of curves.  

**Key takeaways for students:**  
- At low levels (20–40 phons), bass and treble need much more level to be perceived as equally loud.  
- At higher levels (80–100 phons), the curves flatten — the ear is more balanced across the spectrum.  
- This explains why music sounds “thin” when quiet but “full” when louder.  
- It’s also why old stereos had a “loudness” button — to boost bass and treble at low volumes.  
{{%/ note %}}


---

## Equal-Loudness Contours in Action

- **Key Concept:** Our ears don’t hear all frequencies equally well.  
- **Example:** Bass must be louder than midrange to be perceived equally loud.  
- **Why It Matters:** Mixing at low volume often makes bass and treble feel weak.  

**Interactive Demo:** [Equal Loudness Experiment](https://www.phys.unsw.edu.au/jw/hearing.html)  

{{% note %}}
Play tones of different frequencies at the same level.  
Ask students: which sounds louder? They’ll notice midrange tones stand out more.  
Use this to reinforce why engineers check mixes at multiple levels and why Fletcher–Munson curves matter.  
{{%/ note %}}
