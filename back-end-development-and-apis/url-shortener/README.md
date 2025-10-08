# URL Shortener Microservice

**Status:** Not Passed

## Overview
Takes a long URL and returns a short version, then redirects to the original when accessed.

## Tech
- Node.js
- Express
- MongoDB (optional for persistent storage)

## How to Run
```bash
npm install
npm start
```
Use POST request: /api/shorturl
Test redirect with: /api/shorturl/:id

## What Didn't Pass
Regex URL validation failed for some domains.

Redirect returned 404 or invalid location.

Short URLs not being stored/persisted properly.

## TODO
Improve URL validation (use regex or URL constructor).

Map short URLs to IDs in memory or DB.

Ensure 301 or 302 redirect with proper res.redirect().

## Learning Outcome
Built a basic redirect service and learned URL encoding/decoding, routing, and validation.
