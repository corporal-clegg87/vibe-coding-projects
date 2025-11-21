# Mission 2: Containerizing the App

## Objective

Package your chat app into a Docker container so it runs the same everywhere.

## Key Concepts

- **Dockerfile:** A recipe for building a container image.
- **Image vs. Container:** Blueprint vs. running instance.
- **Docker Compose:** Tool for running multi-container apps.

## The Task

Create a Dockerfile and run your app in a container.

## Steps

1.  **Install Docker:**
    - Download Docker Desktop for your OS.
2.  **Create Dockerfile:**
    - **Prompt:** "Create a Dockerfile for my FastAPI/Socket.IO app. It should: 1. Use Python 3.11 base image, 2. Install dependencies from `requirements.txt`, 3. Expose port 8000, 4. Run the app with uvicorn."
3.  **Build Image:**
    - **Prompt:** "Show me the Docker command to build an image called `chat-app`."
4.  **Run Container:**
    - **Prompt:** "Show me the command to run the container and map port 8000."
5.  **Verify:**
    - Go to `localhost:8000`. Your app should work.

## Vibe Check

- If it fails, read the error logs with `docker logs <container_id>`.
- Common issue: Forgetting to install dependencies in the Dockerfile.

## Success Criteria

Your app runs inside a Docker container. You can stop the container, rebuild the image, and run it again.

