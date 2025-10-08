# Stock Price Checker

**Status:** Not Passed

## Overview
A small web app that fetches and displays stock price information from a public API. The project focuses on secure input handling and protecting against common web issues (e.g., XSS from query parameters).

## Tech
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js / Express (optional)
- API: [example public stock API] (replace with actual)
- Security focus: input validation, output encoding

## How to run (local)
1. `git clone https://github.com/manh4ck01/your-repo.git`
2. `cd stock-price-checker`
3. `npm install`
4. `npm start` (or open `index.html` for static version)
5. Visit `http://localhost:3000`

## What didn't pass
- Failed automated validation for proper input sanitization and error handling.
- Some responses were not consistently encoded, leaving potential XSS surface.

## Next steps / TODO
- Add server-side validation for API queries.
- Use a proper API key storage (env vars) — do not hardcode keys.
- Implement CSP and output encoding for displayed data.
- Add unit tests for input validation and error cases.

## Notes / Learning
This project taught me API integration basics and reinforced secure output/input handling for user-provided data.
