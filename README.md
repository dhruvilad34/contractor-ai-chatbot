# ContractorAI – On-Site Q&A Assistant

An AI-powered chatbot that answers real questions for contractors and tradespeople — permits, materials, timelines, building codes, and safety compliance. Built in one day as a demonstration of applied AI for non-developer users.

## Problem it solves
Contractors waste hours Googling permits, material costs, and building codes. ContractorAI gives them instant, practical answers in plain language — no technical knowledge needed.

## Features
- AI answers powered by Claude (Anthropic)
- Topic shortcuts: Permits, Materials, Timelines, Subcontractors, Building Codes, Safety
- Remembers conversation context across multiple questions
- No installation required — runs directly in the browser

## How to run
1. Clone or download this repo
2. Open `contractor-qa-chatbot.html` in your browser
3. Add your Anthropic API key in the fetch headers:
```js
   'x-api-key': 'YOUR_ANTHROPIC_API_KEY_HERE'
```
4. Get a free API key at https://console.anthropic.com

## Tech used
- HTML / CSS / JavaScript (vanilla, no frameworks)
- Anthropic Claude API (claude-sonnet)

## Built for
Scelta Systems – AI R&D Engineer application demo
```

---

### 2. Enable GitHub Pages (live demo link)
This is the most impressive thing you can do — Scelta can click a link and see it live.

1. Go to your repo → **Settings**
2. Scroll down to **Pages** (left sidebar)
3. Under "Source" → select **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)** → click **Save**
5. Wait 2 minutes → your live link will be:
```
https://dhruvilad34.github.io/contractor-ai-chatbot/contractor-qa-chatbot.html
