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
