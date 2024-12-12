# Uncommon HTML Bug: Unexpected InnerHTML Overwrite

This repository demonstrates a subtle bug related to the use of `innerHTML` in HTML and JavaScript.

The `innerHTML` property, when used to modify the content of an element, replaces the existing content entirely instead of appending to it if you use it the wrong way.

## Bug Description
The provided HTML code contains a function that updates the content of a `div` using `innerHTML`. The issue is that attempting to append new content to the existing content using `+=` will instead replace it entirely.