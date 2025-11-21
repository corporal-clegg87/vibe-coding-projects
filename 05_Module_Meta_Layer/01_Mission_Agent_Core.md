# Mission 1: Building the Agent Core

## Objective

Create the foundational agent loop that can generate and execute code.

## Key Concepts

- **LLM API:** Calling AI models programmatically (OpenAI, Anthropic, etc.).
- **Prompt Engineering:** Crafting instructions that get reliable outputs.
- **Sandboxing:** Running untrusted code safely.

## The Task

Build an agent that generates Python code from a text description and executes it.

## Steps

1.  **Set Up API Access:**
    - Get an API key from OpenAI or Anthropic.
    - Store it in `.env` as `OPENAI_API_KEY` or `ANTHROPIC_API_KEY`.
2.  **Create Agent Class:**
    - **Prompt:** "Create a Python class `CodeAgent` with: 1. A method `generate_code(task: str)` that calls the OpenAI API and returns Python code, 2. A method `execute_code(code: str)` that runs the code and captures output/errors."
3.  **Test Basic Generation:**
    - **Prompt:** "Add a test that asks the agent to 'write a function that calculates fibonacci numbers' and verify it generates valid Python."
4.  **Safety Guardrails:**
    - **Prompt:** "Add a check to prevent the generated code from: importing `os`, `subprocess`, or `sys`. Reject code that tries to access the file system."

## Vibe Check

- Start with simple tasks like "print hello world."
- The AI will sometimes generate invalid code. That's expected—Mission 2 will fix this.

## Success Criteria

Your agent can generate Python code from a text description and execute it. Dangerous operations are blocked.

