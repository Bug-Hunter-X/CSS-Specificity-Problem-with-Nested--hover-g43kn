# CSS Specificity Issue with Nested :hover

This repository demonstrates a common CSS specificity problem involving the `:hover` pseudo-class on nested elements.  The issue arises because the parent's `:hover` style is more specific than the child's `:hover` style, resulting in the child's hover style being overridden.

## Problem

The provided CSS code (bug.css) shows a nested element (`.inner`) inside a parent element (`.outer`).  While the hover style is defined for both the inner and outer elements, only the parent's hover style is applied when the inner element is hovered.

## Solution

The solution (bugSolution.css) demonstrates a few ways to fix this issue using various techniques that increase the specificity of the nested element's hover style or separate the styles to prevent the conflict.  This is a common issue and highlights the importance of understanding CSS specificity.