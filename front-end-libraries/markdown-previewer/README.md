# Markdown Previewer

**Status:** Not Passed

## Overview
A real-time Markdown editor that displays a live HTML preview of typed text.

## Tech
- React
- Marked.js (Markdown parser)
- CSS (Responsive)

## How to Run
```bash
npm install
npm start
```
## What Didn't Pass
Inline code and list rendering failed in preview.

HTML not sanitized properly (XSS risk).

Tests failed due to missing id attributes in preview section.

## TODO
Implement secure Markdown rendering with DOMPurify or similar.

Fix styling for headers, lists, and code blocks.

Follow FCC’s accessibility and ID requirements.

## Learning Outcome
Gained skills in text parsing, Markdown libraries, and live data-binding in React.
