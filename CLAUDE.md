# Claude Instructions — riig.github.io

## On Every Session Start
- Read `config.txt` and note any values that differ from what's currently in the HTML files
- Flag any pending config changes to the user before starting work

## General Rules
- Read a file fully before editing it
- Keep CSS and JS inline within each HTML file (no separate stylesheets or script files)
- Match the existing dark terminal aesthetic — don't introduce new design patterns without asking
- Don't auto-commit. Only commit when explicitly asked.
- Don't create new pages or major sections without confirming first

## Config Behavior
- `config.txt` is the source of truth for colors, fonts, labels, and other site-wide settings
- When applying config changes, update all affected HTML files consistently
- If a config value is commented out, leave the current behavior unchanged

## Style Conventions
- Colors come from CSS variables defined in `:root` — update those, not individual rules
- Breadcrumb nav format: `riig.github.io / Section / Page`
- Section cards always include: number, icon, title, content, optional note boxes
- Code blocks use the terminal window chrome style (red/yellow/green dots)

## What to Ask About First
- Restructuring navigation or the page hierarchy
- Removing or significantly changing existing content
- Adding new dependencies (fonts, libraries, etc.)
