# Mission 0: The Quality Problem

## Objective

Understand why "it works on my machine" is not enough, and why professional developers use tests.

## Key Concepts

- **Technical Debt:** Code that works now but will cause problems later.
- **Regression:** When adding a feature breaks old features.
- **Test-Driven Development (TDD):** Write the test *before* writing the code.

## The Task

Return to your Message Board from Module 2 and prepare it for enhancement.

## Steps

1.  **Clone Your Project:** If you don't have it anymore, recreate the basic Message Board (GET and POST messages).
2.  **The Problem:**
    - Try manually testing: Add 5 messages, then refresh the page. Do they persist?
    - Add a message with just spaces. Does it save?
    - Add a 10,000-character message. Does it break?
3.  **Document the Issues:**
    - **Prompt:** "I'm about to refactor my message board. Help me create a `KNOWN_ISSUES.md` file documenting edge cases and bugs I should fix."

## Success Criteria

You have a running Message Board and a document listing at least 3 potential problems with the current implementation.

