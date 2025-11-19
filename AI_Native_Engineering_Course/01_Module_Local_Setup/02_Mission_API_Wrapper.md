# Mission 2: The API Wrapper CLI

## Objective

Build a command-line tool that fetches data from a public API and saves it locally.

## Key Concepts

- **API (Application Programming Interface):** A way for programs to talk to other programs over the internet.
- **Environment Variables:** Secret values (like API keys) stored outside your code.
- **Dependencies:** External libraries your code needs to run.

## The Task

Create a Python script that fetches a random NASA Astronomy Picture of the Day and saves the image URL to a file.

## Steps

1.  **Get an API Key:**
    - Go to [NASA API Portal](https://api.nasa.gov/) and get a free API key.
2.  **Create `.env` File:**
    - **Prompt:** "Create a `.env` file to store my NASA API key securely. Show me the format."
    - Add your actual key to the file: `NASA_API_KEY=your_key_here`
3.  **Build the Script:**
    - **Prompt:** "Create a Python script called `fetch_apod.py`. It should: 1. Load the NASA_API_KEY from the `.env` file using `python-dotenv`, 2. Make a GET request to the NASA APOD API, 3. Print the image URL and explanation, 4. Save the data to a JSON file called `apod_data.json`."
4.  **Install Dependencies:**
    - **Prompt:** "What packages do I need to install for this script?"
    - Run the `pip install` commands the AI provides.
5.  **Create `requirements.txt`:**
    - **Prompt:** "Generate a `requirements.txt` file for this project."

## Vibe Check

- If you get `ModuleNotFoundError`, you forgot to install dependencies.
- If the API call fails, check that your `.env` file is in the same directory as your script.
- **Test:** Delete `apod_data.json` and run the script again. The file should regenerate.

## Success Criteria

Running `python fetch_apod.py` creates a JSON file with NASA data. Your API key is in `.env` (not in the Python file), and `.env` is listed in `.gitignore`.

