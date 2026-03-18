# JARVIS
**A personal AI assistant. One HTML file. No backend. No subscription.**

Open it in your browser. Talk to it. Done.

---

## What it does

- Manage tasks and projects using plain English
- AI silently updates your board as you chat — no forms, no buttons
- Everything stored locally on your device — nothing sent to any server except Anthropic for AI responses
- Auto-compresses long conversations to stay fast and cost-efficient
- Works on mobile and desktop browsers

---

## How to use

**1. Get the file**
Download or copy `jarvis.html` from this repo.

**2. Get an Anthropic API key**
- Go to [console.anthropic.com](https://console.anthropic.com)
- Sign up → API Keys → Create Key
- Copy the key (starts with `sk-ant-...`)

**3. Open the file**
Open `jarvis.html` in any browser. Paste your key on first launch. That's it.

> On mobile: open in Chrome → tap the menu → *Add to Home Screen* for a full app-like experience.

---

## Cost

Uses Claude Haiku — Anthropic's fastest and cheapest model.

Typical usage: **₹1–3 per day** for normal personal use. Heavy use won't exceed ₹10/day.

Your API key is stored only on your device. You pay Anthropic directly — nothing goes through anyone else.

---

## Privacy

- No backend, no database, no analytics
- All your tasks, projects, and notes live in your browser's localStorage
- The only external call is to `api.anthropic.com` for AI responses
- Deleting your browser data wipes everything completely

---

## Example commands

```
Add task: review FLUX PCB assembly
Create project called Irrigation System
What's pending?
Mark done: review FLUX
What should I do next?
Add a note: check solenoid valve specs
Delete project Irrigation System
```

---

## Tech

- Single HTML file (~1000 lines)
- Vanilla JS, no frameworks, no dependencies
- Anthropic Messages API (`claude-haiku-4-5`)
- localStorage for persistence
- No build step, no npm, no server

---

## Built by

[Logic Studio](https://logicstudio.co.in) — Ahmedabad, India  
Built with Claude AI.
