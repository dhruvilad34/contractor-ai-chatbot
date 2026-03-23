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
