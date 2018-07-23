---
title: Tabs
layout: component
keyboard: |
    - <kbd>Space</kbd> of <kbd>Enter</kbd> = Activate Tab
    - <kbd>&larr;</kbd><kbd>&rarr;</kbd> = Cycles tab focus
    - <kbd>&uarr;</kbd><kbd>&darr;</kbd> = Cycles tab focus (vertical tabs)
    - <kbd>Home</kbd> = Focus first tab
    - <kbd>End</kbd> = Focus last tab
labelling: |
    - The element that serves as the container for the set of tabs has role  <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tablist">tablist</a>. 
    - Each element that serves as a tab has role <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tab">tab</a> and is contained within the element with role <code>tablist</code>.
    - Each element that contains the content panel for a <code>tab</code> has role <a class="role-reference" href="https://www.w3.org/TR/wai-aria-1.1/#tabpanel">tabpanel</a>.
    - Each element with role <code>tab</code> has the property <a class="property-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-controls">aria-controls</a> referring to its associated <code>tabpanel</code> element.
    - The active <code>tab</code> element has the state <a class="state-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-selected">aria-selected</a> set to <code>true</code> and all other <code>tab</code> elements have it set to <code>false</code>.
    - Each element with role <code>tabpanel</code> has the property <a class="property-reference" href="https://www.w3.org/TR/wai-aria-1.1/#aria-labelledby">aria-labelledby</a> referring to its associated <code>tab</code> element. 
focus: |
    - It is recommended that tabs activate automatically when they receive focus as long as their associated tab panels are displayed without noticeable latency.
---