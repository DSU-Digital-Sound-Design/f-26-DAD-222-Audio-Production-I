---
title: "Working with loops in REAPER"
summary: "Set up your timebase, fit loops with Option-drag, and glue edited clips into phrases."
---

Use this guide while working on [Project 1: Arranging Clips](/projects/project-1/).
Set up the project once, then fit and check each loop before making copies.

- [Set up the project](#set-up-the-project)
- [Fit each loop with Option-drag](#fit-each-loop-with-option-drag)
- [Cut and glue a new phrase](#cut-and-glue-a-new-phrase)
- [Repeat your phrase](#repeat-your-phrase)
- [Check common problems](#check-common-problems)

## Set up the project

1. Choose a main loop and note its BPM on Looperman. Before importing audio, set
   REAPER's project BPM to that value and use 4/4 for this exercise. Keep the
   transport's playback rate at `1.0`.
2. Open **File > Project Settings**. Set **Timebase for items/envelopes/markers**
   to **Beats (position, length, rate)**.
3. Turn on snapping with the magnet button and turn on the metronome.

This timebase keeps items at the same musical positions and lengths if you later
change the project BPM, stretching their audio to follow. Imported loops still
need to fit the project tempo. Keep the BPM fixed while adding loops, and start
with loops close to that tempo to avoid extreme stretching.

## Fit each loop with Option-drag

1. Drop the loop onto its own track, with its first beat at the start of a measure.
2. Decide how many measures it should fill. Check its description or count the
   beats while listening. In 4/4, four beats make one measure.
3. Select the item, open **Item properties** from its right-click menu, and enable
   **Preserve pitch when changing rate**.
4. Hold **Option** on Mac or **Alt** on Windows and drag the item's **right edge**
   to the intended measure boundary. A four-measure loop starting at measure 1
   should end at the start of measure 5.
5. Listen with the metronome. Check that the loop stays in time through its final
   beat and ends at the expected boundary. If it already fits and sounds in time,
   leave it as it is.

Option-drag stretches the audio to fit. Dragging the edge without Option/Alt trims
or repeats the item instead.

## Cut and glue a new phrase

Use this step when you want to keep only part of a clip or combine pieces into
one phrase. Fit loops from different tempos to the project before cutting and
combining them.

1. Select a clip, place the edit cursor at the cut, and press **S** to split.
   Remove the pieces you do not want. You can also drag an item's edge without
   Option/Alt to trim it.
2. Arrange the pieces you want to combine on the **same track**. Listen across
   the joins and fix unwanted gaps or overlaps.
3. Clear any time selection and select only the piece or pieces you want to glue.
   Right-click a selected item and choose **Glue items**.

Glue creates a new audio file and replaces the selected pieces with one item.
You can now Option-drag its right edge to stretch the whole phrase together.
Check **Preserve pitch when changing rate** on the glued item first.

You can also glue a single trimmed clip. This makes the trimmed section the new
loop source, so repeating it does not bring back the unwanted audio. Glue keeps
your edits, including gaps and overlaps; it does not correct their timing.

For example, place a two-measure section from one fitted loop immediately before
a two-measure section from another. Glue both into one four-measure phrase. You
can stretch the phrase as one item, keeping the join in proportion, or repeat it
throughout your arrangement.

## Repeat your phrase

Once the loop or glued phrase fits, duplicate it to build your arrangement.
To repeat it by dragging, enable **Loop source** in Item properties and drag the
right edge **without Option/Alt**. Listen across the repeat points with the
metronome before filling the rest of the arrangement.

## Check common problems

| What you hear or see | What to check |
| --- | --- |
| The loop drifts away from the metronome | Check its first-beat alignment and intended number of measures, then fit it again. |
| Dragging reveals more audio or repeats it | Hold Option/Alt and drag the right edge to stretch. |
| Repeating a trimmed clip brings back unwanted audio | Glue the trimmed item before repeating it. |
| A combined phrase has awkward gaps or overlaps | Fix the joins before gluing; glue preserves their timing. |
| The stretched audio sounds smeared or choppy | Try a loop closer to the project BPM. |
| The rhythm fits but the notes clash | Matching tempo does not match musical key. Try a bass or melody loop that works with the other notes. |

See the [REAPER User Guide](https://www.reaper.fm/userguide.php) for more on
project timebase, gluing items, and pitch/time manipulation.

Return to [Project 1: Arranging Clips](/projects/project-1/) for requirements,
submission instructions, and the rubric.
