+++
title = "Digital Audio Data"
outputs = ["Reveal"]
[reveal_hugo]
theme = "solarized"
# show_notes = "separate-page"
+++

## Digital Audio Data 

![](digital.png)

{{% note %}}
What happens in the ADC and DAC? The process of digitization. Analog and digital signals are different ways of representing sound. 

We can think of digital as a light switch, on or off, whereas analog is a continuous signal without discrete states. 

{{%/note %}}

---

## Sampling 

![](sampling.png)

{{% note %}}
* To convert a continuous analog signal into a series of numbers, the ADC takes samples of the acoustic signal 
* We measure the amplitude of the incoming waveform some amount of time per second measured in Hertz
* The frequency of sampling is known as the sampling rate 
* Quantization is the process of assigning an amplitude to the sample
* Sample resolution (Bit Depth) is the number of amplitude values available to the ADC

{{%/note %}}

---

## Sampling Rate

<img src="cd.jpg" width="50%">
<!-- ![](cd.jpg) -->

{{% note %}}
CD-quality audio is 44.1 kHz, the most common sampling rate. The ACD measures the amplitude of the incoming waveform 44,100 times per second for each audio channel.

We must remember that this sampling process always ignores some data coming in, but 44.1 kHz/second is high enough to capture the most critical information in the audio signal.

{{%/note %}}

---

## Nyquist Frequency

Nyquist Frequency (fN) = Sampling Rate / 2

fN = 44,100 / 2 = 22,050 Hz

{{% note %}}
The Nyquist frequency is defined as half of the sampling rate (Nyquist rate = 1/2 * Sampling Rate). In mathematical terms:

Nyquist Frequency (fN) = Sampling Rate / 2

For example, if you are sampling an analog signal at a rate of 44.1 kHz (44,100 samples per second), the Nyquist frequency for that sampling rate would be:

fN = 44,100 / 2 = 22,050 Hz

In this case, the Nyquist frequency is 22,050 Hz, which means that the highest frequency component that can be accurately represented in the digital signal is 22,050 Hz. This is why the standard sampling rate for audio CDs is 44.1 kHz, as it can accurately represent audio signals up to approximately 22 kHz, covering the entire range of human hearing.

Sampling at or above the Nyquist rate is essential to avoid aliasing, which is a phenomenon where higher-frequency components in the analog signal are incorrectly represented as lower-frequency components in the digital signal. In practice, it's common to sample at rates significantly higher than the Nyquist rate to ensure accurate representation of audio and other analog signals.

{{%/note %}}

---

## Other sample rates 

* 48 kHz - DVD format
* 96 kHz
* 192 kHz

{{% note %}}


Higher sampling rates are often used during recording to reduce the noise in the signal. They are later downsampled to 44.1kHz. 

{{%/note %}}

---

## Quantization and sample resolution

![](bit-depth.png)

{{% note %}}

Now let's focus on the y-axis, the signal's amplitude.

The ADC measures the incoming analog electrical waveform 44,100 times per second, or more for higher sampling rates. Each time the ADC performs this measurement, it must assign a numerical value to that sample’s amplitude. This assignment of a specific value to the measured amplitude is called quantizing. Don't get this quantizing confused with quantizing of MIDI data.

This is also known as bit depth, not to be confused with "bit rate", which we will talk about at another time. 

{{%/note %}}

---

## Bit depths 

![](bit-depth-chart.png)

{{% note %}}

* Common bit depths include 16-bit (65,536 discrete levels), 24-bit (16,777,216 discrete levels), and 32-bit (4,294,967,296 discrete levels).

{{%/note %}}

---

## Digital Audio File Formats

* Lossless audio formats 
    * WAV (Waveform Audio File Format)
    * AIFF (Audio Interchange File Format)

{{% note %}}

Once we convert to digital, how is it stored?


In uncompressed file formats, digital audio is stored as a series of 16- or 24-bit amplitude values or as 32-bit floating-point amplitude values—32-bit floating-point values are used for internal calculations within most audio recording software, but recording (ADC) and playback (DAC) are done with 16 or 24 bits. Chunks of data written at the beginning of the file indicate information such as the sampling rate, the resolution, the number of channels (two for stereo, six for 5.1 surround, etc.), and the length of the file. Some formats include other information as well, such as loop points for use by hardware or software samplers. Digital audio that is used by audio editing/processing/mixing software is stored in an uncompressed file format.

{{%/note %}}

---

## Compressed 

* MP3 (MPEG-1 Audio Layer 3)
* AAC (Advanced Audio Coding)
* OGG Vorbis
* WMA (Windows Media Audio)
* Opus
* M4A (MPEG-4 Audio)
* FLAC (Free Lossless Audio Codec)

{{% note %}}
Lossless compression reduces the size of audio files in such a way that the original data can be perfectly recovered. An example of lossless compression from the non-audio world is the .zip file, in which all the data from the zipped files can be fully recovered.

Lossy compression, on the other hand, reduces audio file sizes by permanently and unrecoverably eliminating some of the audio information. Lossy compression typically achieves far greater reduction in audio file sizes than lossless compression.

Most lossy compression schemes utilize perceptual encoding to achieve file size reduction without a substantial loss in quality. 

The term “perceptual encoding” encompasses a variety of techniques that use knowledge of the human auditory system to selectively remove elements that we wouldn’t hear anyway. As an example, one of the auditory phenomena utilized by perceptual encoders is frequency masking.
{{%/note %}}