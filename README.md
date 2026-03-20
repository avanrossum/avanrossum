## Alexander van Rossum

Systems architect. AI integrator. macOS developer.

Most of the interesting problems I work on live in the gap between "the technology works" and "the organization works" — where architecture decisions become business outcomes and the unsexy stuff determines whether anything holds together at scale.

I build tools, ship them, and write about what I find along the way at [mipyip.com/blog](https://mipyip.com/blog).

---

### macOS Apps

**[SideMark](https://github.com/avanrossum/sidemark)**: A markdown editor built for working alongside AI agents. Three-way merge, per-hunk diff, git gutter, auto-save. When both you and Claude Code edit the same file, non-overlapping changes merge automatically.
*Open source · MIT · Electron*

**[Actions](https://mipyip.com/products/actions)**: Quick-action launcher from the menu bar. Scripts, shortcuts, links, folders — one click away. Built with Electron, governed by Pass@1.
*Coming soon · Closed source · [Releases](https://github.com/avanrossum/actions-releases)*

**[Panoptisana](https://github.com/avanrossum/panoptisana)**: Asana visibility from the menu bar. Tasks, projects, inbox, and detail views without opening a browser.
*Open source · Electron · TypeScript*

**[JSON Editor](https://github.com/avanrossum/a-simple-json-editor)**: Synchronized tree, form, and raw editor views. Built with Electron, React, TypeScript, and CodeMirror 6.
*Open source · MIT · Electron*

### AI & Developer Tooling

**[claude-context-monitor](https://github.com/avanrossum/claude-context-monitor)**: Monitors Claude Code context window usage. Know when auto-compaction is coming before it costs you a session.

**[mcp-anylist](https://github.com/avanrossum/mcp-anylist)**: MCP server for Anylist. Local-only, Claude-native grocery and meal planning integration.

**[nag-bot](https://github.com/avanrossum/nag-bot)**: Fuzzy reminders via Telegram. Randomized timing, escalating persistence. Built for brains that dismiss predictable notifications. Slightly insane. Still a work in progress.

### Systems & Infrastructure

**[search_s3](https://github.com/avanrossum/search_s3)** · **[search_acm_certificates](https://github.com/avanrossum/search_acm_certificates)**: AWS operational tooling for S3 object search and ACM certificate lookup across accounts.

---

### The methodology

I develop under a methodology I call **[Pass@1](https://mipyip.com/blog/what-is-pass-at-1)** — governance-first AI development — where the goal is to implement correctly on the first attempt. Not by being careful. By removing the ambiguity that causes failures in the first place.

The governance documents — architecture specs, coding standards, constraint boundaries — aren't overhead. They're the mechanism that makes AI agents productive session after session.

**Recent writing:**
- [SideMark: Building a Markdown Editor for Two Authors](https://mipyip.com/blog/sidemark-two-author-markdown): When the workflow is two authors, the editor has to be built for it.
- [Cognitive Offloading](https://mipyip.com/blog/cognitive-offloading): The system that lets me run three projects simultaneously without holding any of them in my head.
- [The Governance Documents](https://mipyip.com/blog/the-governance-documents): The boring files that make everything else possible.

> [mipyip.com](https://mipyip.com)
