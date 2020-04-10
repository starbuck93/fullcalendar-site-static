---
title: longPressDelay
---

For touch devices, the amount of time the user must hold down before an event becomes draggable or a date becomes selectable.

<div class='spec' markdown='1'>
Integer, *default*: `1000` (1 second)
</div>

This value is specified in milliseconds.

Only applicable when the calendar is being used on a touch device. Otherwise, there is no delay.

This setting controls event dragging **and** date selecting. For further granularity, please see the following settings:

- [eventLongPressDelay](eventLongPressDelay)
- [selectLongPressDelay](selectLongPressDelay)
