---
title: Tooltip
layout: component
description: 
keyboard: |
    - <kbd>ESC</kbd> = Dismisses tooltip
labelling: |
    - Tooltip content container has role `tooltip`
    - Tooltip trigger references the tooltip element with `aria-describedby`
focus: |
    - Focus stays on tooltip trigger while the tooltip is displayed.
    - If the tooltip is invoked when the trigger receives focus, then it is dismissed when it no longer has focus (onBlur). If the tooltip is invoked with mouseIn, then it is dismissed with on mouseOut.
---
