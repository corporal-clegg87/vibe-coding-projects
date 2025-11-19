# Mission 2: Adding Self-Correction

## Objective

Make the agent read its own errors and attempt fixes.

## Key Concepts

- **Error Parsing:** Extracting useful information from stack traces.
- **Feedback Loop:** Using execution results as input to the next generation.
- **Convergence:** Knowing when to stop trying.

## The Task

Implement the retry loop with error feedback.

## Steps

1.  **Add Retry Logic:**
    - **Prompt:** "Update `CodeAgent` to add a `run_with_retry(task: str, max_attempts: int = 3)` method. If execution fails: 1. Capture the error, 2. Generate a new prompt: 'The following code failed with this error: [error]. Fix it.', 3. Regenerate code, 4. Try again."
2.  **Test with a Broken Task:**
    - Ask it to "create a list of 10 random numbers and calculate their average."
    - Intentionally give it a vague prompt that might cause an error on first try.
3.  **Add Logging:**
    - **Prompt:** "Log each attempt: show the generated code, the result, and whether it succeeded or failed."
4.  **Success Detection:**
    - **Prompt:** "If code executes without errors, consider it a success. Stop retrying."

## Vibe Check

- Watch the agent fail, read its error, and fix itself. This is powerful.
- If it fails 3 times, the task might be too complex or the prompt too vague.

## Success Criteria

The agent successfully completes a task that initially generates broken code. It retries and fixes the error without human intervention.

