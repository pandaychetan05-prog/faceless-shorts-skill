# Shorts Studio AI

A private local-first idea and script assistant for your faceless-shorts projects.

## Requirements
- Node.js 22+
- Ollama for Windows
- Model: `llama3.2:3b`

## Start

```powershell
cd ai-studio
node server.mjs
```

Open http://127.0.0.1:4173 and keep Ollama running.

## Privacy
- Requests go to Ollama on this laptop.
- Saved/skipped ideas stay in browser local storage.
- Generated facts and scripts require human fact-checking.
