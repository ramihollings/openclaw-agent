# Safe-Config Generator: System Architecture

## Target Surface: 
- Web App (React/Next.js or simple Vite + Tailwind)
- Hosting: Can be served directly via Mr. TECHNOLOGY (localhost or public-facing)

## Core Logic:
- Users select "Role" (Researcher, Dev, Persona-only).
- System maps roles to `openclaw.json` config snippets.
- **Tool Locking**: Using `permissions.deny` and `permissions.allow` for each tool.
- **Sandbox Mode**: Toggling `sandbox: true` (docker/isolated) for higher-risk roles.

## Integration Plan:
1. **Frontend**: Vite + Tailwind (fastest dev cycle).
2. **Backend**: Node.js (can use OpenClaw's own runtime for config validation).
3. **Drafting**: I'll draft the React components here, then we can serve them.

## To-Do:
- [ ] Build the role -> permission matrix in `roles.json`.
- [ ] Create a React "Preview" of the resulting config.
- [ ] Add a "Copy to Clipboard" or "Download config.json" button.
