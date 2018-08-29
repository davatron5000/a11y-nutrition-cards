---
title: Tabs
layout: component
keyboard: |
    - <kbd>Space</kbd> or <kbd>Enter</kbd> = Activate Tab
    - <kbd>&larr;</kbd><kbd>&rarr;</kbd> = Cycles tab focus
    - <kbd>&uarr;</kbd><kbd>&darr;</kbd> = Cycles tab focus (vertical tabs)
    - <kbd>Home</kbd> = Focus first tab
    - <kbd>End</kbd> = Focus last tab
labelling: |
    - The element that wraps tabs has role <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tablist">tablist</a>. 
    - Each tab has role <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tab">tab</a> and is contained within the element with role <code>tablist</code>.
    - Each tab content panel has role <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tabpanel">tabpanel</a>.
    - Each `tab` has the property <a class="property-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-controls">aria-controls</a> referring to its <code>tabpanel</code>.
    - The active <code>tab</code> has <a class="state-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-selected">aria-selected</a> set to <code>true</code> and all other <code>tab</code> elements have it set to <code>false</code>.
    - Each <code>tabpanel</code> has the property <a class="property-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-labelledby">aria-labelledby</a> referring to its associated <code>tab</code>. 
focus: |
    - Tabs should activate automatically when receiving focus as long as associated tab panels are rendered quickly.
    - Tabs should have visible `:focus` state.
    - Tabs should have visible `aria-selected="true"` state
---
