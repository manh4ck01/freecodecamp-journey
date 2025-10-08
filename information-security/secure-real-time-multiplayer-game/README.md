
# Secure Real Time Multiplayer Game

**Status:** Not Passed

## Overview
A small real-time multiplayer web game using WebSockets for communication. The aim is to implement secure real-time features and defend against common web/socket attacks (injection, message spoofing).

## Tech
- Frontend: HTML/CSS/JS
- Backend: Node.js + Socket.IO
- Security focus: message validation, auth tokens, input sanitization

## How to run (local)
```bash
1. `git clone ...`
2. `cd secure-real-time-multiplayer-game`
3. `npm install`
4. `npm start`
```
5. Open `http://localhost:3000` in multiple tabs to test multiplayer

 What didn't pass / issues
- Socket messages were not fully validated, allowing potential spoofing.
- No token-based client authentication (used ephemeral IDs only).
- Race conditions and edge cases in game state sync produced inconsistent state.

 Next steps / TODO
- Implement signed session tokens (JWT) for socket auth.
- Validate and whitelist message schemas server-side.
- Introduce authoritative server-side game loop to avoid client-side cheating.
- Add test harness to simulate multiple clients and verify state sync.

 Notes / Learning
Great practice for real-time communication, state sync challenges, and secure message handling in WebSockets-based apps.


