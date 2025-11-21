# Mission 3: Professional Logging

## Objective

Replace print statements with proper logging to make debugging production issues possible.

## Key Concepts

- **Log Levels:** DEBUG, INFO, WARNING, ERROR, CRITICAL.
- **Structured Logging:** Logs that can be searched and filtered.
- **Log Rotation:** Preventing log files from growing infinitely.

## The Task

Add comprehensive logging to your Message Board.

## Steps

1.  **Set Up Logging:**
    - **Prompt:** "Configure Python logging in `main.py` with: 1. Console output for INFO and above, 2. File output to `app.log` for DEBUG and above, 3. Include timestamps and log levels."
2.  **Add Logs to Endpoints:**
    - **Prompt:** "Add logging to all endpoints: INFO for successful requests, WARNING for validation failures, ERROR for exceptions. Include relevant data like message IDs."
3.  **Add Middleware Logging:**
    - **Prompt:** "Add FastAPI middleware to log every request with: method, path, status code, and response time."
4.  **Test Logging:**
    - Make various API calls and check `app.log`.
    - Intentionally cause errors and verify they're logged.

## Vibe Check

- In development, log generously. In production, log only what you need.
- Never log sensitive data (passwords, API keys).
- Logs should answer "What happened?" and "When did it happen?"

## Success Criteria

Every API request is logged. Errors include stack traces in the log file. You can trace a specific message's lifecycle (created, deleted) through the logs.

