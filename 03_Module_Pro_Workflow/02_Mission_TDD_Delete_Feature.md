# Mission 2: Test-Driven Development

## Objective

Learn to write tests *before* writing code. This feels backwards but is incredibly powerful.

## Key Concepts

- **Red-Green-Refactor:** Write a failing test (Red), make it pass (Green), clean up code (Refactor).
- **Specification:** Tests are documentation of what your code *should* do.

## The Task

Add a DELETE endpoint to your Message Board using TDD.

## Steps

1.  **Write the Failing Test First:**
    - **Prompt:** "I want to add DELETE /messages/{message_id} to my API. Using TDD, write the test first in `test_main.py`. The test should: 1. Create a message, 2. Delete it by ID, 3. Verify it's gone when fetching all messages."
2.  **Run the Test (It Will Fail):**
    - Run `pytest`. You should see an error like "404: Route not found."
3.  **Implement the Feature:**
    - **Prompt:** "Now implement the DELETE endpoint in `main.py` to make the test pass."
4.  **Run Tests Again:**
    - All tests should pass now.
5.  **Add Edge Cases:**
    - **Prompt:** "Add a test for deleting a non-existent message ID. It should return a 404."

## Vibe Check

- The test failing first proves the test actually works.
- If you implement code before the test, you might write a test that can never fail.

## Success Criteria

You have a working DELETE endpoint, and the test was written before the implementation. Running `pytest` shows all tests passing.

