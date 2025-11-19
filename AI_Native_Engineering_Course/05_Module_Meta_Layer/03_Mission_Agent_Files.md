# Mission 3: Specialized Agent Personas

## Objective

Create agent configuration files that give the AI specific expertise and behavior patterns.

## Key Concepts

- **System Prompts:** Instructions that persist across all interactions.
- **Persona Engineering:** Defining expertise, tone, and constraints.
- **`.cursorrules`:** Project-specific AI behavior customization.

## The Task

Create reusable agent configuration files for different programming tasks.

## Steps

1.  **Create Agent Profiles:**
    - **Prompt:** "Create three agent configuration files in a folder called `agents/`: 1. `backend_expert.md` (specializes in API design and databases), 2. `frontend_expert.md` (specializes in React and UI), 3. `devops_expert.md` (specializes in Docker and deployment)."
2.  **Define Structure:**
    - Each file should include: Role, Expertise, Code Style Preferences, and Common Patterns.
3.  **Load Agents Dynamically:**
    - **Prompt:** "Update `CodeAgent` to accept an `agent_file` parameter. Load the markdown file and prepend it to every prompt as system context."
4.  **Test Specialization:**
    - Ask the backend expert to "design a REST API for a todo list."
    - Ask the frontend expert to "create a responsive navbar."
    - Compare the outputs. They should reflect different expertise.

## Vibe Check

- Good agent files produce consistent, high-quality code in their domain.
- Bad agent files are too vague and don't change behavior.

## Success Criteria

You have 3 agent files. Loading different agents produces code with noticeably different styles and approaches.

