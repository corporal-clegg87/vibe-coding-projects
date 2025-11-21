# Mission 3: Deploying to the Cloud

## Objective

Get your chat app running on the public internet.

## Key Concepts

- **Platform as a Service (PaaS):** Services that run your code without managing servers.
- **Environment Variables in Production:** Never hardcode secrets.
- **Persistent Storage:** Containers are ephemeral; databases need to persist.

## The Task

Deploy your chat app to Render (a free hosting platform).

## Steps

1.  **Prepare for Deployment:**
    - **Prompt:** "I'm deploying to Render. Create a `render.yaml` file that: 1. Defines a web service, 2. Specifies the build command, 3. Specifies the start command."
2.  **Create Render Account:**
    - Go to [render.com](https://render.com) and sign up.
3.  **Connect Repository:**
    - Push your code to GitHub.
    - In Render, create a new Web Service and connect your repository.
4.  **Configure:**
    - Set environment variables (if any).
    - Deploy.
5.  **Test:**
    - Render gives you a URL like `your-app.onrender.com`.
    - Open it in multiple browsers/devices.

## Vibe Check

- First deploy always takes longer (building dependencies).
- If it crashes, check Render's logs (they're similar to Docker logs).
- Common issue: CORS not configured for the production URL.

## Success Criteria

You can share a public URL with friends, and multiple people can chat in real time from different locations.

