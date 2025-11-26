# smart_personal_task_assitant
A simple concierge multi-agent system for task planning, summarization, and quick search.
# Smart Personal Task Assistant

A simple **multi-agent concierge system** built for the **Kaggle × Google 5-Day AI Agents Intensive Capstone (2025)**.

## Features
- **Planner Agent**: builds to-do lists & schedules  
- **Summarizer Agent**: summarizes notes & stores them  
- **Researcher Agent**: provides quick answers using a search tool  
- **Custom Tool**: In-session Note Store  
- **Session Memory**: InMemorySessionService  

## Architecture
[User]
↓
[Orchestrator]
├─ Planner Agent
├─ Summarizer Agent
└─ Researcher Agent
↓ ↓ ↓
Note Tool LLM Search Tool
↓
Session Memory
## How to Run
1. Open the included notebook.  
2. Run all cells.  
3. View agent outputs in the demo section.  

## License
MIT License
