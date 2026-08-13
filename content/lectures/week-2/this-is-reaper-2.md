---
title: "Starting a New Project in REAPER 7"
---

Based on this [video](https://www.youtube.com/watch?v=nYN45PhnCXE)

## Step 1: Check Audio Device Settings

Before starting a new project, make sure your audio device settings are correct. To do this, go to REAPER’s Preferences (`ctrl + P`, or `cmd + ,` on Mac) and navigate to `Audio -> Device -> Audio Device Settings`. Ensure the correct audio device is selected, especially if you're using external audio interfaces or microphones, as this can change when new devices are connected.

## Step 2: Start a New Project

To start a new project, select `File -> New Project`, or click the first button on the toolbar. Initially, nothing may seem to happen because you haven’t saved the project yet. To avoid this, you can set REAPER to prompt you to save every time you start a new project. 

To enable this, go to `Preferences -> Project -> Prompt` to save on new project. When prompted, save your project in a dedicated folder. Be sure to check the boxes that say "Create subdirectory for project" and "Copy all media into project directory."

![](../save.png)

After saving, you'll see a folder containing your project’s `.RPP` file, which is the main project file for REAPER.

## Step 3: Configure Project Settings

To stay organized, create a folder within your project directory called "Audio" for your media files. Then, in REAPER’s Project Settings, make sure the option to "Copy media to project path" upon importing files is enabled. This ensures that any audio or media you bring into your project is copied into your project directory automatically.

Once your project settings are configured, you can save these as your default settings by selecting "Save as default project settings," so you won’t need to repeat this process for every new project.

![](../project-settings.png)

## Step 4: Organize with a Peaks Subfolder

To further organize your project files, especially when working with larger projects, you can direct REAPER to place peak files (waveform cache files) into a separate subfolder. 

Go to `Preferences -> Media` and check the box for "Put new peak files in peaks/ subfolder relative to media."

This step helps keep your project folder tidy, especially if you’re working with many audio files, ensuring that peaks are neatly stored in their own folder.

## Step 5: Exporting (Rendering) Your Finished Work

When a project is done, you export it as a single audio file. In Reaper this is called **rendering**: `File -> Render` (`ctrl + alt + R`). The settings that matter:

- **Source:** Master mix. **Bounds:** Entire project (or a time selection if you only want part).
- **Sample rate:** match your project (44.1 kHz for music, 48 kHz for video work).
- **Format:** which file type to write. That choice is worth understanding:

{{< stats >}}
{{< stat value="WAV, 24-bit" label="For submitting and archiving" note="Full quality, uncompressed. This is what you turn in for every project in this class." >}}
{{< stat value="MP3, 320 kbps" label="For quick sharing" note="Small and convenient, but it throws data away. Never bring an MP3 bounce back into a project as source material." >}}
{{< /stats >}}

## What Happens When You Upload

One thing to know before you ever put a track online. Streaming platforms measure the loudness of everything uploaded and **turn tracks down to a common level**, so listeners don't reach for the volume knob between songs.

{{< stats >}}
{{< stat value="about -14 LUFS" label="Where most platforms level you" note="Spotify, YouTube, TIDAL, and Amazon all normalize near this point. Apple Music sits a little lower at -16." >}}
{{< stat value="-1 dB true peak" label="Ceiling before encoding distorts" note="Lossy formats like MP3 and AAC can clip on playback if your master slams 0 dB." >}}
{{< /stats >}}

The practical takeaway: **there is no prize for loud**. A master crushed with a limiter to sound loud gets turned down to the same level as everyone else and keeps only the distortion. Export clean, leave the peaks some room, and let the platform do the leveling. How to actually master toward these numbers is a DAD 322 topic; for now, just don't fight the normalizer.

- More detail: [iZotope — how streaming normalization works](https://www.izotope.com/community/blog/mastering-for-streaming-platforms)

