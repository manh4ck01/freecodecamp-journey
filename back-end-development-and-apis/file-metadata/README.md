# File Metadata Microservice

**Status:** Not Passed

## Overview
Accepts file uploads and returns metadata: file name, type, and size in bytes.

## Tech
- Node.js
- Express
- `multer` for handling file uploads

## How to Run
```bash
npm install
npm start
```
Test with: POST to /api/fileanalyse using multipart/form-data

## What Didn't Pass
File not correctly parsed (multer not used or misconfigured).

Response missing one or more required fields.

Upload failed for larger files.

## TODO
Add correct multer middleware for file upload.

Return correct structure:

json
Copy code
{
  "name": "myfile.txt",
  "type": "text/plain",
  "size": 1234
}
Add size limits and upload validation.

## Learning Outcome
Learned how to work with file uploads, form data, and server-side file handling in Node.

yaml
Copy code
