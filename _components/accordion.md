---
title: Accordion
layout: component
description: 
keyboard: |
    - <kbd>Enter</kbd> or <kbd>Space</kbd> = Expands/Collapses Panel
    - <kbd>Tab</kbd> = Move to next focusable element
    - <kbd>Shift + Tab</kbd> = Move to previous focusable element
    - <kbd>&uarr;</kbd> <kbd>&darr;</kbd> = Cycle headers when header focused
    - <kbd>Home</kbd> (Optional) = Focus first header
    - <kbd>End</kbd> (Optional) = Focus last header
labelling: |
    - Each accordion header title is contained in an element with role [button](https://w3c.github.io/aria/#button) (e.g. `<button>`). 
    - Each accordion header button wrapped with role [heading](https://w3c.github.io/aria/#heading) set to appropriate [aria-level](https://w3c.github.io/aria/#aria-level). 
        - HTML `heading` elements can be used.
        - Only one `button` element is allowed in the `heading`. Other visual elements must be outside the `heading` element.
    - If the accordion panel is visible, the header button element should have [aria-expanded](https://w3c.github.io/aria/#aria-expanded) set to true. If the panel is not visible, `aria-expanded` is set to false. 
    - Accordion header buttons have [aria-controls](https://w3c.github.io/aria/#aria-controls) set to the ID of the associated accordion panel content.
focus: |
    - Headers should have visible keyboard focus state
    - All keyboard interactions relate to when headers are focused
---