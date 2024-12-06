# Unexpected Width Calculation with calc() in CSS

This repository demonstrates an uncommon issue related to the CSS `calc()` function when subtracting pixel values from percentage widths.  The problem is more likely to occur when the parent element's width is also defined using percentages.

The `bug.css` file contains the problematic code, while `bugSolution.css` offers a workaround.

## Problem

The `calc(50% - 10px)` expression may not render correctly in all browsers if the parent element's width is not explicitly defined in pixels.

## Solution

The solution involves ensuring that the parent container has a defined pixel width or using a different approach to achieve the desired layout.