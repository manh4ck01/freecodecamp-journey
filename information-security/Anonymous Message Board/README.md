# Anonymous Message Board

**Status:** Not Passed

## Overview
A simple anonymous message board supporting posting and viewing messages. Built with a focus on sanitization, rate-limiting, and authentication-less/anonymous posting flows.

## Tech
- Backend: Node.js + Express
- Database: MongoDB (or file-based store for demo)
- Security: input sanitization, helmet, rate limiting

## How to run (local)
1. `git clone https://github.com/manh4ck01/your-repo.git`
2. `cd anonymous-message-board`
3. `npm install`
4. `npm run dev`
5. Open `http://localhost:3000`

## What didn't pass
- Tests flagged unsanitized message rendering (XSS risk).
- No persistent throttling/rate-limiting implemented to prevent spam.
- Authentication/design allowed trivial injection via crafted payloads.

## Next steps / TODO
- Add server-side sanitization (e.g., DOMPurify on rendering or sanitize-html).
- Implement rate limiting (express-rate-limit) and basic moderation queue.
- Add Content Security Policy and secure headers (helmet).
- Create integration tests for sanitization and spam scenarios.

## Notes / Learning
Good practice with sanitization, DB integration, and secure defaults for public-facing input fields.
