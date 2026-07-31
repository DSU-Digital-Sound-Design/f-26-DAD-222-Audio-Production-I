---
title: "Basic Editing in Reaper"
---

### Undoing Edits

If you make a mistake while editing, press `Cmd+Z` (Mac) or `Ctrl+Z` (Windows) to undo. For a complete list of your previous actions, open `Edit -> Undo History`. This lets you step back through your edit sequence and return to any earlier state.

### Adjusting Item Content (Slip Editing)

To adjust the timing of content inside an item without moving the entire item, hold `Alt` (Windows) or `Option` (Mac) and drag left or right. This “slip edit” is ideal for tightening dialogue or syncing effects to visuals while keeping the item anchored on the timeline.

### Splitting Items

Place the cursor where you need a cut and press `S` to split the item. This makes it easy to remove unwanted sections or rearrange dialogue. To revert multiple splits within a single item, choose `Item -> Heal splits in items`.

### Healing vs. Gluing

* **Heal** returns one item to its original, unsplit form (only if all the pieces come from the same original item).
* **Glue** merges two or more adjacent items into one continuous file, even if they were originally separate. Use this after making a series of precise edits to simplify the project.

### Crossfading Between Items

Drag one item slightly over another to create an automatic crossfade. Adjust fade length by dragging the fade handles. Short fades keep transitions smooth and avoid pops or clicks.

### Fades and Volume Envelopes

* Drag the top corners of an item to create quick fade-ins or fade-outs.
* For more detailed level control, enable track volume envelopes (`Track Envelopes -> Volume`) and add automation points for gradual changes, useful for ducking music under dialogue.

### Editing Across Multiple Tracks

To edit multiple tracks at once, right-click and drag to select items across tracks. You can then move, trim, or split them together—helpful when aligning dialogue with music or effects.

---

### Ripple Editing

Ripple editing shifts subsequent items automatically when you move or delete a section, maintaining the project’s timing.

* **Per Track**: Only items on the active track shift.
* **All Tracks**: Every track shifts together.

Toggle from the toolbar or via `Options -> Ripple Editing`. This is ideal when removing silences or rearranging dialogue sequences.

---

### Razor Editing

Razor editing lets you quickly select and edit time-based areas across one or more tracks.

* **Select a range**: Hold **Ctrl** (Windows) or **Cmd** (Mac) and drag across the timeline to create a shaded region (the “razor area”).
* **Move**: Drag the shaded area to move it.
* **Delete**: press `Delete` to remove the selected time range.
* **Multi-track work**: Razor areas can span multiple tracks, which makes it ideal for rearranging complex dialogue or music sections.

Tip: You can also combine razor editing with ripple editing (set to “per-track” or “all tracks”) so that when you cut or move a razor area, everything after it automatically shifts to stay in sync.

---

### Grouping Items

For multi-mic recordings or dialogue with music, select related items, right-click, and choose `Group Items`. Grouped items stay locked in relative position, making multi-track edits safer.

### Snap/Grid Settings

Ensure consistent timing by toggling `Snap` on (`Shift+S`) and setting the grid to an appropriate value (e.g., quarter-note for music, fine increments for dialogue). Adjust the grid from the top toolbar.

### Additional Tips for a PSA Project

* Use **Markers** (`M`) to label key sections such as intro, VO, SFX, or outro.
* Keep your session organized: name tracks clearly (VO, Music, Effects) and color-code items.
* Regularly save versions (`File -> Save As`) to maintain backups as you experiment.
