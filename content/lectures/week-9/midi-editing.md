---
title: "MIDI Editing"
---

Now that we've recorded our parts they need to be edited. If you double click on any MIDI item it will bring up the MIDI editor.

Notice the bar below:

![](../bar.png)



* Double click on any MIDI item to open the MIDI editor. Take note of the transport bar at the bottom which contains settings for:
    * Grid lines
    * Quantization strength
    * Note lengths
    * Key snapping
* Grid line settings are important for setting the quantization, but also for editing MIDI notes by hand. With snapping enabled, moving a note will snap it to the grid division.
* When adding new notes with the pencil tool, their length is set by the Notes setting. Currently this matches the grid size.
* To add a note at the grid length, double click. To make longer notes, hold and drag the pencil.
* To quickly add many notes at the grid size, hold down option+command and drag to use the paint tool.
* You can move notes by selecting and dragging with the mouse or using command+arrow keys. This will snap notes to the grid horizontally and change the MIDI note vertically

## Adding Variation to the loops

- Loops likely sound robotic due to lack of velocity variation. Real drummers emphasize different parts of the beat and vary strength

![](../velocity.png)

* See the velocity section above the notes. These red lines set the MIDI note strength. Velocity goes from 0-127.
* To edit velocity, select a note then hold option and drag up/down. You can also drag the red line directly.
* Select all notes of one type by right clicking its key. With notes selected, drag across velocities to draw them in.
* Set notes on weaker beats to lower velocities. For a hi-hat in eighth notes, every other one can be lower.