+++
title = "Electronic Sound Production"
outputs = ["Reveal"]
[reveal_hugo]
theme = "solarized"
# show_notes = "separate-page"
+++

## Modulation: Making the sound more dynamic

- **oscillator**: pitch and waveform;
- **filter**: filter type, cutoff frequency, and resonance;
- **amplifier**: overall level and attack-decay-sustain-release parameters.

{{% note %}}
During our previous example the timbre of the synth with not change at all. This type of synthesis sounds very artificial to use because natural sound is changing all the time.

To make our sounds more interesting we must have its parameters changing in some way all the time, which is called **modulation**.

The modulatable parameters of our model are this:
• oscillator: pitch and waveform;
• filter: filter type, cutoff frequency, and resonance;
• amplifier: overall level and attack-decay-sustain-release parameters.

There are three basic ways to control these parameters: through **direct control**, with an **envelope**, and with a **low frequency oscillator (LFO)**.

Direct control refers to the parameters being controlled directly by MIDI messages or you actually turning knobs and sliders yourself on an analogue synthesizer.
{{%/ note %}}

---

## Modulation with LFOs

[Learning Synths - LFOs](https://learningsynths.ableton.com/en/lfos/change-that-repeats)
