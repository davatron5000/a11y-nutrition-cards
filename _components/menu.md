---
title: Menu & Menu Button
layout: component
description: Menus are commonly referred to as "Dropdowns" and present a list of options to a user when activated.
keyboard: |
    - <kbd>Enter</kbd> or <kbd>Space</kbd> = Open Menu
    - <kbd>Escape</kbd> = Close Active Menu
    - <kbd>&darr;</kbd> = Open Menu (when button focused)
    - <kbd>&uarr;</kbd><kbd>&darr;</kbd> = Cycles menu option focus
    - <kbd>Home</kbd> (Optional) = Focus first Menu item
    - <kbd>End</kbd> (Optional) = Focus last Menu item
labelling: |
    - Menu Button should use [button](https://w3c.github.io/aria/#button) element to activate the menu (e.g. `<button>`).
    - Menu Button has [aria-haspopup](https://w3c.github.io/aria/#aria-haspopup) set to `true`.
    - Menu has role [menu](https://w3c.github.io/aria/#menu).
    - When menu is visible, button has [aria-expanded](https://w3c.github.io/aria/#aria-expanded) set to `true`. When menu is hidden, it is set to `false`.
    - (Optional) Menu Button has [aria-controls](https://w3c.github.io/aria/#aria-controls) attribute that refers to the Menu
    - Menu visibility should be toggled using the `hidden` attribute.
    - Menu items should use the appropriate roles, states, and properties depending their functionality. [More on that here](https://w3c.github.io/aria-practices/#menu).
focus: |
    - Menu Button and Menu options should have a visible keyboard <code>:focus</code> state
    - When escape key <kbd>Escape</kbd> is pressed and the menu is active/open, focus should be returned to the Menu Button associated with that menu.
    - (Optional) When focused on the last menu item, the down arrow key <kbd>&darr;</kbd> should move focus to the first menu item.
    - (Optional) When focused on the first menu item, the up arrow key <kbd>&uarr;</kbd> should move focus to the last menu item.
---