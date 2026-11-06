# AI Competitive Intelligence Dashboard

## Live tool

**Try it:** https://emresenturer.github.io/ai-competitive-intelligence/

A working version of this case study, in a single `index.html`:

1. Enter your company (and optionally what you offer), then add up to 6 competitors and paste their updates: launches, partnerships, hiring, notes. Or click **Load sample** (fictional companies).
2. Add your own Anthropic API key and click **Generate report**. No key yet? Click **See example report**.
3. Get a competitive intelligence report: signals per competitor, threat level with rationale, a positioning map table, opportunities, and recommended responses with priority and owner, each signal cited to the update it came from.
4. **Copy Markdown**, **Download .md**, or **Print / PDF** (print stylesheet included).

It only analyzes what you paste. It does not browse the web, open links, or check facts.

- **Run locally:** `python3 -m http.server 8000`, then open http://localhost:8000/.
- **Privacy:** your key stays in this browser (localStorage) and is sent only to api.anthropic.com with your pasted text. There is no server.
- **Stack:** plain HTML, CSS and JavaScript, Anthropic Messages API called from the browser. The system prompt builds on [prompts.md](prompts.md).

---

## Overview

This project demonstrates how AI can automate competitor monitoring
and generate strategic intelligence reports.

---

## Problem

Product teams and executives need constant visibility into
competitor product launches, partnerships, and strategy.

Tracking this manually is time consuming.

---

## Solution

This AI workflow:

1. Collects competitor news and updates
2. Identifies strategic signals
3. Summarizes developments
4. Produces executive intelligence briefings

---

## Tools Used

Claude
ChatGPT
Notion
Python

---

## Example Output

Weekly competitor briefing containing:

• Product launches
• Strategic partnerships
• Market positioning shifts

---

## Business Impact

Provides leadership with continuous strategic intelligence.
