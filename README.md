# Tailwind CSS Flex Item Overlap
This repository demonstrates a common issue when using Tailwind CSS's flexbox functionality.  When not explicitly setting widths or heights on flex items, they can overlap unexpectedly. This is because flex items default to `inline` display if no dimensions are specified.  The solution shows how to fix this using various Tailwind utility classes.

## Bug
The `bug.html` file shows two divs arranged using `flex`. The blue div overlaps the red div because no width or height is specified. 

## Solution
The `solution.html` file demonstrates several ways to fix the overlapping issue, including using `w-1/2` (or other width utility classes), setting a height, or using the `flex-grow` utility to distribute space.