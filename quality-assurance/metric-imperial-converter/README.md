# Metric-Imperial Converter

**Status:** Not Passed

## Overview
API service that converts values between metric and imperial units. Users can submit GET requests and receive JSON with the converted value and unit.

## Tech
- Node.js
- Express.js
- Mocha / Chai (for testing)
- Helmet (for basic security)

## How to Run
```bash
npm install
npm start
```
Then open: http://localhost:3000

What Didn't Pass

Inconsistent or incorrect unit return format.

Some edge cases failed conversion logic (e.g., malformed input).

Missing or incorrect functional tests.

TODO

Fix rounding precision for conversions.

Normalize input (case sensitivity, whitespace, etc.).

Add missing unit test cases with Mocha/Chai.

Review and improve response schema validation.

Learning Outcome

Improved understanding of REST APIs, automated testing, and user input handling.
