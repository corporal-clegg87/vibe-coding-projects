# Mission 4: Continuous Integration

## Objective

Automate your tests to run every time you push code to GitHub.

## Key Concepts

- **CI/CD:** Continuous Integration / Continuous Deployment.
- **GitHub Actions:** Free automation that runs in the cloud.
- **Build Pipeline:** Automated steps that validate code before deployment.

## The Task

Set up GitHub Actions to run your tests automatically.

## Steps

1.  **Push to GitHub:**
    - Create a GitHub repository and push your Message Board code.
    - **Prompt:** "Show me the git commands to add a remote GitHub repository and push my code."
2.  **Create Workflow File:**
    - **Prompt:** "Create a GitHub Actions workflow file at `.github/workflows/test.yml` that: 1. Runs on every push and pull request, 2. Sets up Python 3.11, 3. Installs dependencies from `requirements.txt`, 4. Runs pytest."
3.  **Push and Watch:**
    - Push the workflow file to GitHub.
    - Go to the "Actions" tab in your repository.
    - Watch your tests run in the cloud.
4.  **Break Something:**
    - Intentionally break a test (change an assertion).
    - Push. Watch the CI fail.
    - Fix it. Watch it pass.

## Vibe Check

- CI catches mistakes before they reach production.
- Red ❌ on GitHub = do not merge.
- Green ✅ = safe to proceed.

## Success Criteria

Your GitHub repository has a green checkmark on the latest commit. Tests run automatically on every push.

