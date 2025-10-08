
**📄 Content:**
```markdown
# American ↔ British Translator

**Status:** Not Passed

## Overview
Translates text between American and British English dialects, including spelling, vocabulary, and time format.

## Tech
- Node.js
- Express
- Mocha + Chai for API test validation

## How to Run
```bash
npm install
npm start

What Didn't Pass

Some vocabulary terms weren’t translated correctly.

Time format (e.g. 12:15 → 12.15) failed in tests.

Tests failed for HTML highlighting on translated terms.

TODO

Expand translation dictionary for both directions.

Fix highlighting logic for partial matches.

Improve time format regex handling.

Pass all FCC-provided Chai tests.

Learning Outcome

Practiced regex, string manipulation, API routing, and dialect-specific edge case handling.
