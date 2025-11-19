# Mission 0: The Blueprint

```
    ┌────────────────────────────────────────────┐
    │  📋 MISSION BRIEFING                       │
    │  Module: 2  |  Mission: 0  |  XP: 300     │
    │                                            │
    │  Status: ⚪ NOT STARTED                    │
    │  Prerequisites: Module 1 Complete          │
    │  Estimated Time: 1 hour                    │
    └────────────────────────────────────────────┘
    
    ┌─────────┐          ┌─────────┐
    │ CLIENT  │  ←────→  │ SERVER  │
    └─────────┘          └─────────┘
                              │
                              ↓
                         ┌─────────┐
                         │   DB    │
                         └─────────┘
    
    "First, we design. Then, we build."
    
```

## Objective

Before writing a single line of code, we must define WHAT we are building. The AI is fast, but if you give it vague instructions, you will get garbage code.

## Key Concepts

- **Client vs. Server:** The waiter (Server) takes the order to the kitchen; the customer (Client) reads the menu.
- **JSON:** The language machines use to talk to each other.
- **Schema:** The shape of your data.

## The Task

Create a file called `architecture.md`. You will use this file to "seed" the AI's context for the rest of the project.

## Steps

1.  **Open a new chat.**
2.  **Prompt:** "I want to build a simple anonymous message board where users can post text messages and view a list of recent messages. There is no login. I need you to act as a Systems Architect. Please help me design: 1. The Data Schema (what does a 'message' look like in JSON?), 2. The API Endpoints (GET and POST)."
3.  **Review:** Does the JSON have a `timestamp`? Does it have an `id`? If not, tell the AI to add them.
4.  **Save:** Copy the final plan into `architecture.md`.

## Success Criteria

You have a Markdown file describing exactly what the `Message` object looks like and what the URLs `/messages` (GET) and `/messages` (POST) will do.

```
    ┌────────────────────────────────────────┐
    │  ✓ MISSION COMPLETE!                   │
    │                                        │
    │  Rewards:                              │
    │  • +300 XP                             │
    │  • Unlocked: System Design             │
    │                                        │
    │  Next Mission: The Backend →           │
    └────────────────────────────────────────┘
```

