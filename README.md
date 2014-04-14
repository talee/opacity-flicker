opacity-flicker
===============

Example of opacity transition flickering in Chrome in nested iframes

Solved by adding the following CSS rule to the element:

        -webkit-backface-visibility: hidden;                                                                     
