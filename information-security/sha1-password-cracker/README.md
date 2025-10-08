

# SHA-1 Password Cracker

**Status:** Not Passed

## Overview
Educational tool to demonstrate how hashed passwords (SHA-1) can be brute-forced or checked against a wordlist. For learning only — intended to teach why weak hashing is risky.

## Tech
- Language: Python 3
- Libraries: `hashlib`, file I/O for wordlists

## How to run (local)
```bash
python3 crack_sha1.py --hash <sha1hash> --wordlist wordlist.txt
```

What didn't pass / issues

Performance was poor for large wordlists due to single-threaded approach.

No throttling or safe checks — needs clear warnings about ethical use.

Tests flagged missing input validation and missing rate/limit controls.

Next steps / TODO

Add multi-threading / multiprocessing to boost performance.

Add benchmarking and optional hash-salting examples to contrast proper hashing.

Add clear legal/ethical disclaimer; restrict to lab/test hashes only.

Offer demo mode with tiny test wordlist and expected hash examples.

Notes / Learning

Useful for understanding the importance of salts, strong hashing algorithms, and password policy enforcement.
