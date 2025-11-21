# Mission 3: Integration Hell

## Objective

Fix the communication breakdown between Frontend and Backend.

## Key Concepts

- **CORS (Cross-Origin Resource Sharing):** A security guard that stops website A from talking to server B unless server B says it's okay.
- **Network Tab:** The truth detector in the browser.

## The Task

Configure the backend to allow the frontend to talk to it, and build the "Submit" form.

## Steps

1.  **Fix CORS:**
    - **Prompt:** "I am getting a CORS error when my html file tries to fetch from the API. Please modify `main.py` to enable CORS for all origins."
    - **Action:** Update backend code. Restart server. Refresh page. You should see messages!
2.  **The Input:**
    - **Prompt:** "Update `index.html`. Add a text input and a 'Post' button. When clicked, use JavaScript to POST the text to `http://localhost:8000/messages`, then reload the list of messages."
3.  **Refine:**
    - Ask the AI to make it look "modern and dark mode" using CSS.

## Success Criteria

You can type a message in your HTML page, click submit, and see it appear in the list. The page refreshes with new messages automatically.

```
    ┌────────────────────────────────────────────┐
    │  🎉 MODULE 2 COMPLETE! 🎉                  │
    │                                            │
    │  Rewards:                                  │
    │  • +2500 XP (Total Module Bonus)           │
    │  • Badge Unlocked: [🏗️] Full Stack Master │
    │  • Badge Unlocked: [⚡] API Architect      │
    │  • Badge Unlocked: [🔌] Integration Expert │
    │                                            │
    │  Your Level: 2 → 3                         │
    │                                            │
    │  Next Module: Professional Workflow →      │
    └────────────────────────────────────────────┘
    
         🎊 Congratulations! 🎊
         
    You've built a working full-stack app!
    Time to make it bulletproof...
```

