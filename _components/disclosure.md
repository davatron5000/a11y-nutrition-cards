---
title: Disclosure (Show/Hide)
layout: component
description: 
keyboard: |
    - <kbd>Enter</kbd> or <kbd>Space</kbd> = Toggle content
labelling: |
    - Trigger has role of [button](https://w3c.github.io/aria/#button) (e.g. `<button>`)
    - When content is visible, `button` has [aria-expanded](https://w3c.github.io/aria/#aria-expanded) set to `true`. When content is hidden, it is set to `false`.
    - (Optional) `button` references content with [aria-controls](https://w3c.github.io/aria/#aria-controls) 
focus: |
    - Trigger has visible keyboard <code>:focus</code> state
---
