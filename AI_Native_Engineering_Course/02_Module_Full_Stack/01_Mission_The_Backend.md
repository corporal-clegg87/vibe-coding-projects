# Mission 1: The Engine Room

## Objective

Build the API (Application Programming Interface). This is the brain of the operation. It will listen for requests and save data to a database.

## Key Concepts

- **FastAPI / Flask:** Tools to build web servers in Python.
- **HTTP Methods:** GET (Give me data) vs. POST (Take this data).
- **Localhost:** Your computer's internal web address.

## The Task

Get a server running locally that shows a "Swagger UI" (an automatic documentation page).

## Steps

1.  **Prompt:** "Reference my `architecture.md` file. I want to build the backend using Python and FastAPI. Please create a file called `main.py` that sets up the server and an in-memory list to store messages for now."
2.  **Action:** Create the file, install dependencies (`pip install fastapi uvicorn`).
3.  **Run:** Run the server command the AI gives you.
4.  **Verify:** Go to `http://localhost:8000/docs`. This is your dashboard. Try sending a message using the "Try it out" button.

## Vibe Check (Troubleshooting)

- If the terminal says `command not found`, you forgot to activate your virtual environment (from Module 1).
- If the AI writes code that looks scary, ask it: "Explain this code to me line by line like I am 12."

## Success Criteria

You can see your API documentation in the browser, and you can add a message through that interface.

