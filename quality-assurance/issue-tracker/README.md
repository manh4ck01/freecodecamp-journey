
**📄 Content:**
```markdown
# Issue Tracker

**Status:** Not Passed

## Overview
A full-stack web app that lets users create, update, and delete issues in a project board — similar to GitHub Issues.

## Tech
- Node.js, Express
- MongoDB (Mongoose)
- Mocha + Chai for testing

## How to Run
```bash
npm install
npm start

Then visit: http://localhost:3000

What Didn't Pass

PATCH endpoint failed for optional updates.

Missing status updates for resolved issues.

Some fields didn't persist correctly in MongoDB.

Tests were incomplete or failing on PUT/DELETE routes.

TODO

Refactor PATCH logic to handle partial updates.

Fix MongoDB schema field validation.

Add comprehensive test coverage using Chai HTTP.

Add input sanitization and error-handling middleware.

Learning Outcome

Great hands-on experience with CRUD API design, database logic, and test-driven development.
