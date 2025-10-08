# Timestamp Microservice

**Status:** Not Passed

## Overview
An API that returns a timestamp in both UNIX and UTC formats when a date string or UNIX timestamp is provided.

## Tech
- Node.js
- Express

## How to Run
```bash
npm install
npm start
```
Visit: http://localhost:3000/api/:date?

What Didn't Pass

Invalid date strings returned incorrect error messages.

No fallback for empty parameters (should return current timestamp).

Missing error handling for edge formats (e.g. "2015-12-25T00:00:00Z").

TODO

Fix input parsing using Date.parse() or new Date() consistently.

Add proper {"error":"Invalid Date"} response handling.

Validate and sanitize input parameters.

Learning Outcome

Learned API parameter handling, working with dates in JS, and proper API responses.
