# Mission 4: Production Hardening

## Objective

Make your app reliable and secure for real users.

## Key Concepts

- **Rate Limiting:** Preventing abuse by limiting requests.
- **HTTPS:** Encrypted connections (Render provides this automatically).
- **Health Checks:** Endpoints that monitoring systems can ping.
- **Graceful Shutdown:** Properly closing connections when restarting.

## The Task

Add production-grade features to your chat app.

## Steps

1.  **Add Health Check:**
    - **Prompt:** "Add a GET /health endpoint that returns {status: 'ok'} and a 200 status code."
2.  **Add Rate Limiting:**
    - **Prompt:** "Add rate limiting to prevent spam. Limit each IP to 10 messages per minute using `slowapi`."
3.  **Add Username Feature:**
    - **Prompt:** "Update the chat to ask for a username when connecting. Display the username with each message."
4.  **Add Logging:**
    - **Prompt:** "Add structured logging to track: connections, disconnections, and messages sent."
5.  **Monitor:**
    - Render has built-in metrics. Check CPU and memory usage.

## Vibe Check

- Test rate limiting by spamming messages. You should get blocked.
- Refresh the page repeatedly to test if the health check responds.

## Success Criteria

Your app has a health check, rate limiting, usernames, and logs all activity. It's ready for real users.

