# AI Learning Path

An interactive mind map for tracking your understanding of the AI ecosystem -- built to be explored conversation-by-conversation with Claude.

Open `ai-mind-map.html` in any browser. Click any node to see what it covers and track your understanding level (0-5). Use Claude to discuss each topic, then update your notes directly in the file.

---

## How to use this with Claude

This repo is designed to be a living learning journal. The mind map tracks 9 clusters of AI knowledge: Foundation Models, Core Concepts, APIs & SDKs, Agents, Vector & Retrieval, Safety & Guardrails, Evals & Observability, The Fast Edge, and Augmented Coding Patterns.

Pick the prompt below that matches your background, paste it into Claude (ideally in [Cowork mode](https://claude.ai/download) with this folder selected), and let the conversation guide you.

---

### Prompt: Non-technical founder or executive

> I would like to understand AI well enough to make smart product and hiring decisions -- not to build it myself, but to know what questions to ask engineers and what tradeoffs matter. I have this mind map (`ai-mind-map.html`) that covers the AI ecosystem. Can you open it and walk me through it cluster by cluster? For each area, I want to know: what does this actually do in plain English, why does it matter for a product, and what are the 1-2 things a non-technical leader should understand about it? After we discuss each cluster: (1) update my understanding rating (0-5) in the map based on my responses, (2) add a short note summarizing what I learned to the relevant nodes, and (3) if our conversation surfaces topics or tools that are not yet in the map, add them as new nodes. Commit the changes after each session.

---

### Prompt: Technical developer new to AI

> I am a software developer who is comfortable with code but new to AI and ML. I have this mind map (`ai-mind-map.html`) that covers the AI ecosystem. Can you open it and quiz me cluster by cluster on what I already know? For each topic, start with a quick question to gauge my understanding, then fill in the gaps with clear technical explanations and concrete examples. Help me understand how these concepts connect to things I already know from software engineering. After we cover each cluster: (1) update my understanding rating (0-5) in the map, (2) add a summary of our Q&A to the relevant nodes, and (3) if our conversation surfaces topics or tools that are not yet in the map, add them as new nodes. Commit the changes after each session.

---

### Prompt: Developer actively building AI products

> I am building an AI-powered product and I want to sharpen my mental model of the ecosystem -- both the foundations and the fast-moving frontier. I have this mind map (`ai-mind-map.html`) that covers 9 clusters of AI knowledge. Can you open it, assess my current understanding cluster by cluster, and help me figure out where my gaps are most likely to hurt the product I am building? For each area, I want: an honest assessment of what I know vs. what I think I know, the concepts that matter most for production AI systems, and concrete questions I should be asking about my own codebase and architecture. After we cover each cluster: (1) update my understanding rating (0-5) in the map, (2) record our Q&A as notes on the relevant nodes, and (3) if our conversation surfaces tools, techniques, or topics not yet in the map, add them as new nodes. Commit the changes after each session.

---

## Tracking your progress

Each node in the map has:
- **Status ring** -- color-coded by priority (green = core, amber = should-know, indigo = optional, orange dashed = watch this space)
- **Understanding rating** -- click the dots in the side panel to self-rate 0-5 after discussing a topic
- **Notes and Q&A** -- your conversation summaries, recorded directly in the map

The map is a plain HTML file with all data embedded. Edit it directly or ask Claude to update it after each session.

## Version control

To track your learning journey over time, initialize a [jj](https://jj-vcs.github.io/jj/) (or git) repo in this folder and commit after each session. Ask Claude to do this: "commit the current state of the mind map with a message describing what we covered today."

---

Made with D3.js. Inspired by the [Augmented Coding Patterns](https://lexler.github.io/augmented-coding-patterns/) catalog.
