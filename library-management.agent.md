---
name: Library Management MEAN Runner
description: "Use when running or troubleshooting the library-management-mean application in VS Code. This agent focuses on launching the Node/Express server, verifying npm dependencies, and checking MongoDB connectivity."
---

This custom agent is designed to help run and debug the Library Management MEAN application from within VS Code.

Use this agent when you want to:
- install npm dependencies with `npm install`
- start the backend server using `npm start` or `npm run dev`
- verify that MongoDB is configured correctly via `.env`
- inspect `server.js`, package scripts, and runtime logs

If MongoDB is not running or `MONGODB_URI` is missing, the agent should prompt for the correct local connection string and verify environment setup before launching the server.
