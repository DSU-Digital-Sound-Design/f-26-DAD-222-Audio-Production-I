---
title: "Basic Voice Recording in Reaper"
---
<!-- 
[Source](https://www.youtube.com/watch?v=eOegtqEOv1Q)

# Recording in Reaper

Create a new track and name it "voice". Click the track record button to put the track into record mode. Now you should see the track input section. Change this to the input that you want to use. If you don't have an interface plugged in it will be your build in inputs. This is usually "input 1".

Set your recording levels so that your meters are hitting between -18 dB and -12 dB. You have to do this while playing sound. There's no way of setting levels by just moving the input gain without looking at the meters.

Now you can record by clicking the record button on the transport. You can play back the sound now.

# Monitoring modes

The default is to monitor the input. You can turn it off and still record if you don't want to hear it play back as you're recording. Usually it's good to just leave this on.

The other mode is useful for punching in, or re-recording a specific part of an item. This can be done by clicking "cmd+r" at the punch-in and punch-out places. Reaper will then create takes, so that you still have your previous take. You can choose which take you like then crop to active take once you deicide which take you want to keep.

One useful thing could be to autoselect your punch in and punch of points. You can do this using "Record mode: time selection auto punch". Create a time selection then hit the record button. Reaper will only record in your time selections.

Finally you can choose "Record mode: auto-punch selected items". Now you can make multiple selections of items and re-record the ones that re selected. To make different selections you need to slipt the item first. Do this with "s" to split at cursor.

[Here's](https://stash.reaper.fm/oldsb/201374/recording_modes_INPUT-DEVICE.pdf) a good summary of the different modes and what you should expect for each. -->


### Getting Started with Recording in Reaper

**Create a New Track**  
   Start by creating a new track. Right-click in the track control panel (the left section of your track area) and select "Insert New Track."  

   **Tip**: It's a good habit to name your track. Double-click the track name area and type "Voice" or whatever is relevant for your recording.

**Enable Record Mode for the Track**  
   On the newly created track, locate the red circular **Record Arm** button and click it. This puts the track into record mode, letting Reaper know that you want to record audio here.

**Select Your Input Device**  
   Once your track is in record mode, you'll see the track input section (near the volume and pan controls).  
   - Right-click the input area and select **Input: Mono > Input 1** (or whichever input your microphone or audio interface is connected to).  
   - If you're using a built-in microphone (for example, on a laptop), this will typically be **Input 1** as well.

**Set Your Recording Levels**  
   - Before recording, make sure your levels are correct to avoid clipping or too quiet recordings. Play some sound or speak into your microphone and watch the meter.  
   - Adjust the input gain either on your audio interface until the meter shows levels between **-18 dB and -12 dB**. This gives you a good balance between loudness and headroom.  
  
   **Important**: Always adjust your input gain while monitoring the meter – never guess.

**Start Recording**  
   - With everything set up, hit the **Record** button in the transport bar at the bottom of the screen (the button with a red circle).  
   - Reaper will now start recording audio on the armed track. To stop recording, press the **Stop** button or the spacebar.

**Playback Your Recording**  
   After stopping the recording, Reaper will automatically place the recorded audio as a media item on the track. Hit **Play** to listen back to your recording.

---

### Monitoring Modes in Reaper

**Input Monitoring**  
   By default, Reaper is set to monitor your input, meaning you can hear yourself through your headphones as you record.  
   - You can toggle monitoring by clicking the small speaker icon on the track control panel.  
   - If you prefer not to hear yourself while recording, disable monitoring, but Reaper will still record your audio.

**Punch-In Recording**  
   Sometimes you need to re-record a specific section of your take, and punch-in recording is perfect for that.  
   - First, position your cursor at the start of the section you want to re-record. You can press **Cmd+R** (Mac) or **Ctrl+R** (Windows) to punch in.  
   - When Reaper reaches the punch-out point, it will stop recording and keep all the takes. You can later choose which take to keep by selecting the media item and right-clicking to choose your preferred take.

**Auto-Punch Recording**  
   - If you want to be precise with punch-in recording, use the **Time Selection Auto-Punch** feature.  
   - First, create a time selection by dragging in the timeline above your track.  
   - Then go to the transport bar, right-click the **Record** button, and select **Record Mode: Time Selection Auto-Punch**. Now, when you hit record, Reaper will only record within the selected time area.

**Auto-Punch Selected Items**  
   Another useful punch-in mode is **Record Mode: Auto-Punch Selected Items**.  
   - First, select the item(s) you want to re-record by clicking them.  
   - Then right-click the **Record** button and select **Record Mode: Auto-Punch Selected Items**. Reaper will now only record over the selected items.  
   **Tip**: To make multiple selections, split the item first by pressing **S** at the cursor where you want to split the recording.

---

### Final Thoughts on Recording

Reaper provides a lot of flexibility when it comes to recording and managing your takes. Experiment with different modes and find what works best for your workflow. Remember, Reaper will always keep your original take, so don’t worry about losing previous recordings.

For a more detailed overview of all the recording modes and their use cases, check out this helpful [recording modes summary](https://stash.reaper.fm/oldsb/201374/recording_modes_INPUT-DEVICE.pdf).

