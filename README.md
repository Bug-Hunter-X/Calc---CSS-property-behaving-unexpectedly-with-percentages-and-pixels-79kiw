# CSS calc() Unexpected Behavior
This repository demonstrates a bug related to the unexpected behavior of the `calc()` function in CSS when combining percentages and pixels.  The issue occurs in certain scenarios, leading to incorrect calculations and layout problems.

## Bug Description
The `calc()` function, while powerful for dynamic calculations, sometimes exhibits unexpected behavior when mixing percentage and pixel units.  Specifically, the intended result of a calculation like `width: calc(50% - 10px);` might not be accurately reflected in the rendered output.

## Reproduction Steps
1. Clone this repository.
2. Open `bug.css` to see the problematic CSS.
3. Open `index.html` (if applicable) to view the rendered output and observe the discrepancy between expected and actual width.

## Solution
The solution may involve a workaround to achieve the expected layout by using different techniques instead of relying directly on `calc()` with percentage and pixel combinations in this particular way.