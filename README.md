# Agent Experience (AX) — a field guide from practice

A long-form, evidence-first blog post on **Agent Experience**: designing codebases, context files, and workflows so AI coding agents (Claude Code, Cursor, Codex, Copilot, aider) produce the best results.

**Read it here → https://ashishjain608.github.io/agent-experience/**

What's inside:

- Where AX comes from (Biilmann's January 2025 coinage; accessibility / comprehension / operability)
- The one constraint behind every practice: the context window, and why **bloat is a correctness bug**
- Six practices that survived 3-vote adversarial fact-checking — and the 16 popular claims that didn't
- A full case study: mining 380 of my own Claude Code sessions (~1,600 messages) into a `workflow.md`, then refactoring it with AX principles into a layered core + per-repo architecture
- A do-it-yourself checklist you can run in an afternoon

Single self-contained `index.html` — no build step, no JS frameworks, inline SVG diagrams. Hosted on GitHub Pages.

Every claim in the post is cited; numbers marked "corroboration-grade" were not independently verified. Sources: Anthropic, OpenAI, Cursor docs; Chroma Research; biilmann.blog; agentexperience.ax; Sean Grove's AI Engineer 2025 talk.
