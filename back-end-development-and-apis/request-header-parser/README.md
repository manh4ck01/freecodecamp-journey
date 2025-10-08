# Request Header Parser Microservice

**Status:** Not Passed

## Overview
Parses incoming HTTP request headers to return information about the client's IP address, language, and software.

## Tech
- Node.js
- Express

## How to Run
```bash
npm install
npm start
```
Visit: http://localhost:3000/api/whoami

What Didn't Pass
Did not return the correct format (missing software field or wrong field name).

Headers not accessed correctly (case-sensitive or undefined).

Some test cases failed for invalid or missing headers.

TODO
Use req.headers['user-agent'], req.ip, and req.headers['accept-language'] properly.

Ensure response is in this format:

json
Copy code
{
  "ipaddress": "...",
  "language": "...",
  "software": "..."
}
Learning Outcome
Learned how to extract headers and return structured JSON via Express.
