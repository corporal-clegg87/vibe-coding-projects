# Mission 3: Making It Professional

## Objective

Transform your script into a proper command-line tool with arguments and error handling.

## Key Concepts

- **Command-Line Arguments:** Letting users customize behavior when they run your script.
- **Error Handling:** Gracefully dealing with failures instead of crashing.
- **Logging:** Recording what your program is doing (better than `print()` statements).

## The Task

Enhance your API wrapper to accept command-line arguments and handle errors.

## Steps

1.  **Add Arguments:**
    - **Prompt:** "Modify `fetch_apod.py` to use the `argparse` library. Add two arguments: `--date` (optional, format YYYY-MM-DD) to fetch a specific date, and `--save-image` (flag) to download the actual image file, not just the URL."
2.  **Add Error Handling:**
    - **Prompt:** "Add try/except blocks to handle: 1. Missing API key, 2. Network errors, 3. Invalid API responses. Print helpful error messages."
3.  **Add Logging:**
    - **Prompt:** "Replace print statements with Python's `logging` module. Set up both console output and a log file called `apod.log`."
4.  **Test Edge Cases:**
    - Run with a bad date: `python fetch_apod.py --date 2050-01-01`
    - Run without the `.env` file (temporarily rename it)

## Vibe Check

- Good error messages should tell the user *what* went wrong and *how* to fix it.
- If your script crashes with a long traceback, you haven't caught that error yet.

## Success Criteria

Your script handles bad inputs gracefully, logs its actions, and can download images when the `--save-image` flag is used. Running `git log` shows multiple commits documenting your progress.

