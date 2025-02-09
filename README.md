# CSS calc() Calculation Inaccuracies

This repository demonstrates a subtle bug related to the `calc()` function in CSS. The bug manifests when combining percentages and fixed units (like pixels) in calculations, leading to unexpected results across different browsers.

## The Problem

The core issue stems from the order of operations and potential rounding errors during `calc()` calculations.  The browser may interpret the calculation differently than intended, leading to layout discrepancies.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Observe the unexpected width of the `.element` compared to expectations.

## Solution

See the `bugSolution.css` for the potential solution and further explanation.