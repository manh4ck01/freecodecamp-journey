# Exercise Tracker

**Status:** Not Passed

## Overview
A full-stack app that allows users to register, log workouts, and retrieve logs with optional filters (from, to, limit).

## Tech
- Node.js
- Express
- MongoDB + Mongoose

## How to Run
```bash
npm install
npm start
```
## What Didn't Pass
Failed to return correct date format (toDateString() missing).

Exercise logs were not filtered correctly by query parameters.

Missing unique user ID enforcement.

## TODO
Fix date formatting: ensure consistent UTC output.

Add query filtering logic for from, to, and limit.

Add validations for required fields (description, duration, etc.).

## Learning Outcome
Understood schema modeling, request validation, and managing user-generated content securely.
