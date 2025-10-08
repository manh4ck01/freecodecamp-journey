# Roman Numeral Converter

**Status:** Not Passed

## Overview
Converts integers into their Roman numeral equivalents, up to 3999.

## Tech
- JavaScript (ES6)

## How to Run
Call `convertToRoman(num)` in browser console or Node.js terminal.

## What Didn't Pass
- Returned repeated characters instead of subtractive notation (e.g. `IIII` instead of `IV`).
- Failed for large numbers like 1987 or 3999.

## TODO
- Implement subtractive cases (`IV`, `IX`, `XL`, etc.)
- Create map of Roman numerals with descending order.
- Write unit tests for all numeral ranges.

## Learning Outcome
Learned control structures, greedy algorithms, and logic chaining in JS.
