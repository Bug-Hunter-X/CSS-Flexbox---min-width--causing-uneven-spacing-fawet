# CSS Flexbox `min-width` Issue

This repository demonstrates a subtle bug related to using `min-width` within a flexbox container.  The problem arises when the content of a flex item exceeds its `min-width`, leading to uneven spacing despite the use of `justify-content: space-between`.  The solution shows how to address this by leveraging `flex-shrink` or `flex-basis`.

## Problem

The `bug.css` file contains CSS code that produces an uneven flexbox layout. The expected behavior is equal spacing between three items. However, because one item's content width surpasses its `min-width`, the spacing becomes distorted.

## Solution

The `bugSolution.css` file demonstrates two approaches to solve this issue: using `flex-shrink` to allow items to shrink and maintain even spacing, or using `flex-basis` to control the initial size of flex items and better manage space distribution.