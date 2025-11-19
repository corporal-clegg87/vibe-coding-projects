# Mission 2: The Face

## Objective

The API works, but it's ugly. We need a website.

## Key Concepts

- **HTML/CSS:** Structure and Style.
- **JavaScript (Fetch API):** How the browser makes phone calls to your server.
- **DOM Manipulation:** changing what is on the screen.

## The Task

Create an `index.html` file that loads the messages from your API and displays them.

## Steps

1.  **Prompt:** "I have a FastAPI backend running on localhost:8000. I need a simple `index.html` file. It should have a title 'The Board' and a container `div` to hold messages. Write a script that fetches the messages from `GET http://localhost:8000/messages` and displays them on the page when it loads."
2.  **Action:** Create the file. Open it in Chrome.
3.  **The Failure:** You will likely see... nothing. Or an error in the Console.
4.  **Discovery:** Right-click -> Inspect -> Console. You will see a red error about "CORS".
    *   *Note: This is intentional. Every developer hits this.*

## Success Criteria

You have an HTML file. It creates a CORS error in the browser console.

