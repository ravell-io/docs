> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- **Ask**: A conversation thread (chat) with questions and answers.
- **Agent**: A scheduled query that runs on a recurring basis, producing reports.
- **Context**: The unified view of profiles (individual + workspace) and Memory.
- **Source**: A connected integration (Linear, Notion, Intercom, Slack, Attio).
- **Inbox**: Where proactive reports from agents land.
- **Citation**: A clickable reference linking an answer claim to its source data.
- **Template**: A pre-built agent configuration for common use cases.
- **Visibility**: Private (only you) or shared (workspace-visible) for Asks and Agents.

## Style preferences

- Use active voice and second person (you)
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- No emojis in documentation content

## Content types

### Feature docs (Guides tab)
- "What is X?" — 1 paragraph definition
- "Why it matters" — value prop
- "How to use it" — step-by-step
- "Examples" — concrete prompts and expected results
- "Tips" — power user advice in accordions

### Use-case guides (Use Cases tab)
- Role's top pain points
- Exact prompts for each workflow
- Expected output description
- Suggested agent templates
- "Getting started" section with 3-4 steps

### Scenario guides (Use Cases tab)
- The question (blockquoted)
- What you get (structured output description)
- Step-by-step or automation setup
- Before vs after comparison
- Tips for customization

### Question library
- Tables with columns: Question | What Ravell does
- Organized by source, role, and complexity
- One-line descriptions of what Ravell does

### Reference (Admin & Reference tab)
- Tables for structured data
- AccordionGroups for FAQ
- Symptom → Cause → Fix for troubleshooting

## Mintlify components to use

- `<Steps>` for procedural content
- `<CardGroup>` for navigation hubs and role-based routing
- `<AccordionGroup>` for FAQ and progressive disclosure
- `<Tip>`, `<Note>`, `<Warning>` callouts
- Mermaid diagrams for architecture and data flow
- Tables for comparisons and question examples

## Content boundaries

- Do not document internal admin features, dev tools, or Polar webhook details.
- Signal monitors are NOT shipped yet — exclude from docs. Leave room in structure for when they ship.
- Do not mention specific pricing numbers; reference "Settings → Billing" instead.
