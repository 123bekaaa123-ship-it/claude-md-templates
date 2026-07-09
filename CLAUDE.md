# What this project is
A collection of three-tier CLAUDE.md templates for Claude Code. Helps users set up standing instructions at computer level (across all projects), project level (for one codebase), and folder level (for specific directories).

# Stack
- Markdown for all templates and documentation
- No dependencies — this is a template/documentation repo

# Commands
- No build or test process — this is a content/template repo

# Rules for this repo
- Templates go in `computer/`, `project/`, and `folder/` directories — each contains a CLAUDE.md file
- README.md explains the three-tier system and installation instructions
- DISTILL-PROMPT.md is a user-facing prompt for deeper customization
- Templates intentionally use bracketed placeholders — users fill these in
- **Keep README examples in sync with template content.** If you change a template, update its corresponding example in README.md
- Don't modify these templates to be prescriptive — they're starting points. Users customize them.
- Secrets stay in env vars — never write a real key into any file.

# Gotchas
- These are templates, not final configurations. Users should read them, not copy blindly.
- The README's "Then make them yours" section references a second prompt — clarify if you add new workflow steps.
- Template brackets should match their tier: [brackets] in computer/ are generic across all projects, project/ brackets are project-specific.
