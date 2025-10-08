# Pomodoro Clock

**Status:** Not Passed

## Overview
A 25+5 Pomodoro Timer that allows setting break and session lengths, and toggling start/stop/reset.

## Tech
- React
- HTML/CSS
- JavaScript Timing Functions

## How to Run
```bash
npm install
npm start
```
## What Didn't Pass
Timer reset logic was buggy (reset didn’t zero out all states).

Audio didn’t play consistently on session end.

Tests failed on exact timer transitions and button behaviors.

## TODO
Fix state resets using useEffect or manual state clearing.

Ensure accurate second-by-second countdown with setInterval.

Add accessible controls (keyboard + screen reader support).

## Learning Outcome
Learned time-based state management, countdowns, and component reactivity in React
