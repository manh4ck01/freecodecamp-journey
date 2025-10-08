
**📄 Content:**
```markdown
# Personal Library

**Status:** Not Passed

## Overview
A secure API-based app for managing books — supports adding, viewing, and deleting books with their comments.

## Tech
- Node.js + Express
- MongoDB
- Mocha / Chai for functional testing

## How to Run
```bash
npm install
npm start

What Didn't Pass

Comment POST endpoint failed with invalid book IDs.

Delete logic sometimes failed when no _id provided.

Returned object schema didn’t match required format.

No error handling for empty input.

TODO

Fix route validation and return standard error messages.

Improve schema validation in Mongoose.

Complete all user stories with passing tests.

Add rate-limiting or basic auth.

Learning Outcome

Helped understand database-backed APIs, validation, and route testing with Mocha/Chai.
