# Telephone Number Validator

**Status:** Not Passed

## Overview
Validates whether a string is a valid US phone number, supporting multiple formats (e.g., `(555)555-5555`, `555-555-5555`, `1 555 555 5555`).

## Tech
- JavaScript
- Regular Expressions

## How to Run
Call `telephoneCheck(str)` in console.

## What Didn't Pass
- Some formats with country code failed (e.g., `1 (555) 555-5555`).
- Incorrectly allowed invalid formats like `555-5555`.

## TODO
- Refine regex pattern to match all valid formats exactly.
- Add conditions to ensure length and position of digits.
- Create unit tests using FCC's test suite.

## Learning Outcome
Improved understanding of regex, pattern matching, and string validation.
