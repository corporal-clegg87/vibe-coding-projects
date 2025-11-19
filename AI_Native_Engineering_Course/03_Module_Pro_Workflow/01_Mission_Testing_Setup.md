# Mission 1: Writing Your First Tests

## Objective

Create automated tests that verify your API works correctly.

## Key Concepts

- **Unit Test:** Tests a single function in isolation.
- **Integration Test:** Tests how multiple parts work together.
- **Test Coverage:** Percentage of your code that is tested.
- **pytest:** The most popular Python testing framework.

## The Task

Write tests for your Message Board API endpoints.

## Steps

1.  **Install Testing Tools:**
    - **Prompt:** "I want to add tests to my FastAPI project. Show me what packages to install for testing."
2.  **Create Test File:**
    - **Prompt:** "Create a file called `test_main.py`. Write tests for: 1. GET /messages returns a list, 2. POST /messages adds a message, 3. POST with empty content fails gracefully."
3.  **Run Tests:**
    - Follow the AI's instructions to run pytest.
    - Watch some tests *fail* (this is intentional if your code doesn't validate input).
4.  **Make Tests Pass:**
    - **Prompt:** "My test for empty messages is failing. Update `main.py` to reject messages with empty or whitespace-only content."

## Vibe Check

- Tests failing is *good* if they catch real bugs.
- If all tests pass immediately, your tests might not be strict enough.
- Run tests after every change to catch regressions early.

## Success Criteria

Running `pytest` shows at least 3 passing tests. Your API now rejects invalid messages.

