# LinkedIn "Authority" Agent: System Architecture

## Objective:
Automate high-signal "Build-in-Public" content by monitoring local project progress and drafting posts in Mr. TECHNOLOGY's unique voice.

## The Strategy:
1. **Source Monitoring**: Watch `PROJECTS.md`, `MEMORY.md`, and project directories for commits, updates, or new prototypes.
2. **Signal Extraction**: Filter for "wins" (e.g., "GEO Content Machine is live") and "lessons" (e.g., "EADDRINUSE errors on port 8080").
3. **Voice Synthesis**: Use a "Vibe-Check" prompt to match the sharp, professional, yet witty tone of Mr. TECHNOLOGY.
4. **Post Generation**: Structure for LinkedIn's algorithm (hook, body, actionable insight, tags).

## The Stack:
- **Frontend**: Dashboard showing "Drafted Posts" and a "Feed of Local Wins".
- **Agent Logic**: 
    - Log Monitor: Scans memory files for updates.
    - Ghost Writer: Drafts the post.
    - Editor: Adds hashtags and JSON-LD for "GEO" cross-optimization.

## MVP Features:
- [ ] Log Feed (Real-time events from the OpenClaw workspace).
- [ ] Post Drafts (Generated from those events).
- [ ] "Authority Level" selector (Insightful vs. Hype vs. Technical).
- [ ] One-click Publish (via message tool to a "Social Buffer" session).
