# "GEO" Content Machine: System Architecture

## Objective:
Generate content optimized for "Generative Engine Optimization" (GEO). This means content that is highly citable by AI agents (Perplexity, Gemini, SearchGPT).

## The Strategy:
1. **Deep Research**: Use `web_search` (Brave/Google) to find current, high-authority citations.
2. **Entity Density**: Structure content around specific entities and technical facts that AI models prioritize.
3. **JSON-LD Injection**: Automatically generate Schema.org JSON-LD to make the content machine-readable.
4. **Citation Mapping**: Every claim in the generated post must have a source URL mapped in the metadata.

## The Stack:
- **Frontend**: Dashboard for topic input and "AI Engine" target selection.
- **Agent Logic**: 
    - Researcher: Gathers facts.
    - SEO Architect: Maps JSON-LD entities.
    - Writer: Drafts the citable post.

## MVP Features:
- [ ] Topic Input (e.g. "Future of MCP in Retail").
- [ ] "Citation Level" slider (How many sources to include).
- [ ] Live GEO Preview (Shows how a Generative Engine might summarize the post).
- [ ] JSON-LD Code Generator.
