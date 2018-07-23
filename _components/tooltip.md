---
title: Tooltip
layout: component
description: 
keyboard: |
    - <kbd>ESC</kbd> = Dismisses tooltip
labelling: |
    - The element that serves as the tooltip container has role <code>tooltip</code>
    - The element that triggers the tooltip references the tooltip element with <code>aria-describedby</code>
focus: |
    - Focus stays on the triggering element while the tooltip is displayed.
    - If the tooltip is invoked when the trigger element receives focus, then it is dismissed when it no longer has focus (onBlur). If the tooltip is invoked with mouseIn, then it is dismissed with on mouseOut.
---
