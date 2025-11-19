# Mission 4: The Meta Project

## Objective

Use your agent to build something useful: a code review bot.

## Key Concepts

- **Static Analysis:** Analyzing code without running it.
- **Code Quality Metrics:** Complexity, duplication, style.
- **Automated Review:** What agents can critique.

## The Task

Build a tool that takes a Python file and provides a code review.

## Steps

1.  **Define Review Criteria:**
    - **Prompt:** "Create a code review checklist for Python code covering: 1. Function length, 2. Variable naming, 3. Missing docstrings, 4. Error handling, 5. Security issues (hardcoded secrets)."
2.  **Build Reviewer Agent:**
    - **Prompt:** "Create a `CodeReviewer` class that: 1. Reads a Python file, 2. Sends it to the LLM with the review checklist, 3. Returns a structured review with issues and suggestions."
3.  **Test on Real Code:**
    - Run it on your old Message Board code from Module 2.
    - See what issues it finds.
4.  **Add Auto-Fix:**
    - **Prompt:** "Add a method `apply_suggestions(file_path: str)` that: 1. Generates fixed code, 2. Shows a diff, 3. Asks for user confirmation before writing."

## Vibe Check

- The agent should find real issues, not just nitpick style.
- Some suggestions might be wrong. Agents aren't perfect.

## Success Criteria

Your code reviewer identifies at least 3 real improvements in old code and can optionally apply them automatically.

