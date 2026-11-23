---
sidebar_position: 3
title: Placing Notes and Events
description: Placing Notes and Events
---
Select your preferred note/event type in the event palette and click on the desired position in the timeline.

![palette notes](assets/palette_notes.png)
![placed block](assets/placed_block.png)

Overlapping events will bring up a prompt asking which should be selected.
Remember: you can also *adjust your angle snap* to place events along a greater range of angles, or *manually enter* angle & time positions in the Event editor.

![overlapping events](assets/overlapping_events.png)

Events with easings that occur at the same time for the same object (ex. a decoration with separate X and Y easings) need to be ordered using the *"order"* function to work properly.

![order property](assets/order_property.png)

The next section will go over the different note & event types you can select by default, and what their functions are. Other events may not be included but still usable by entering their respective ID in the text field of the Event palette.

# Note Types

|           |                             |                                                           |
| --------- | --------------------------- | --------------------------------------------------------- |
| Block     | ![11](assets/events/11.png) | The most basic note.                                      |
| Hold      | ![11](assets/events/12.png) | Hold notes that the paddle must follow.                   |
| Inverse   | ![11](assets/events/13.png) | Notes that must be hit on the back of the paddle.         |
| Mine      | ![11](assets/events/14.png) | Notes the player must avoid                               |
| Minehold  | ![11](assets/events/15.png) | The same as mines, but occupying an entire range of time. |
| Bounce    | ![11](assets/events/16.png) | Notes that must be hit multiple times                     |
| Side      | ![11](assets/events/17.png) | Notes that must be hit on the side of the paddle          |
| Extra Tap | ![11](assets/events/18.png) | Notes that require a button input.                        |
| Trace     | ![11](assets/events/19.png) | A decorative hold                                         |
