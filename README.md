# CSS Specificity Issue: !important and Inheritance

This repository demonstrates a subtle CSS bug related to specificity and inheritance when using the `!important` flag. The bug occurs due to a conflict between the specificity of selectors and how inheritance interacts with the `!important` rule. 

## Bug Description

The CSS code attempts to style paragraphs (`<p>`) within a container element.  Unexpectedly, the paragraph's color might not be red (as intended). The inheritance order and the `!important` declaration create unexpected behavior.

## How to reproduce

1. Clone this repository
2. Open `bug.html` in your browser.
3. Observe the color of the paragraph.

## Solution

The solution demonstrates how to correctly manage specificity and avoid relying excessively on `!important`.