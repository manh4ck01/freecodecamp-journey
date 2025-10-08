# Port Scanner

**Status:** Not Passed

## Overview
A small network utility that scans a target host for open TCP ports (basic SYN/CONNECT style). Intended for lab learning and internal security testing only.

## Tech
- Language: Python 3
- Libraries: `socket`, `concurrent.futures` (threading)
- Optional: `scapy` for more advanced packet handling

## How to run (local)
```bash
python3 scanner.py <target-ip-or-host> --ports 1-1024
```
What didn't pass / issues

Scanner produced false positives/negatives under certain timeouts and concurrency settings.

No safe-guards to prevent misuse (no usage/ethics warnings) and limited error handling.

Missing proper permission/notice for real network scanning.

Next steps / TODO

Improve timeout & retry logic and parameterize concurrency.

Add command-line validation, usage examples, and ethics/warning header.

Add rate-limiting and scanning delay to avoid DoS-like behavior.

Include a README section about legal/ethical use and lab-only guidance.

Notes / Learning

Practiced socket programming, concurrency, and the importance of responsible disclosure and lawful testing.
