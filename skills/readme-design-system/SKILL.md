---
name: readme-design-system
description: Create or improve portfolio-grade GitHub README systems with consistent personal branding, visual hierarchy, badge strategy, architecture storytelling, and repository presentation. Use when working on README.md files, repository documentation, portfolio repos, GitHub branding, architecture sections, project showcases, or documentation design systems.
---

# README Design System

## Purpose

Apply the Nicolas AI Engineering Lab README design system to transform repositories into portfolio-grade technical products.

Treat a README as:

- Product presentation
- Engineering showcase
- Technical portfolio asset
- Architecture communication layer

Do not behave like a generic README generator. Analyze the repository first, then adapt the structure to the real project.

## Workflow

1. Inspect the repository context before writing.
   - Identify project type, stack, architecture, current files, and maturity.
   - Do not invent metrics, architecture, screenshots, benchmarks, or production status.
2. Classify the project.
   - AI, Agent, Cloud, Full Stack, Library, Tooling, Research, or Hybrid.
3. Design the README structure.
   - Keep the standard section order when applicable.
   - Add category-specific sections only when they are supported by repository evidence or clearly marked as planned.
4. Create or update README.md.
   - Prioritize clarity, architecture, engineering decisions, and portfolio value.
5. Recommend visual assets.
   - Include banner guidance, badge strategy, diagram suggestions, and asset placement.
6. Preserve truthfulness.
   - Prefer "Planned", "In progress", or "Future improvements" over fake claims.

## Brand Identity

Use this brand unless the repository explicitly defines another one:

- Brand name: Nicolas AI Engineering Lab
- Alternative: Nicolas Software & AI Lab
- Pillars: AI Engineering, Software Architecture, Cloud Engineering, Agent Systems, Practical Innovation, Technical Research, Builder Mindset
- Tone: professional, technical, modern, clear, confident, engineering-focused

Avoid:

- Excessive marketing language
- Buzzword overload
- Emoji spam
- Corporate cliches
- Overly academic writing

## Visual Design System

Primary theme: Dark Modern Engineering.

Use this palette for banners, diagrams, and visual recommendations:

- Background: `#0D1117`
- Primary: `#58A6FF`
- Secondary: `#8B5CF6`
- Success: `#22C55E`
- Warning: `#F59E0B`
- Text: `#C9D1D9`

Visual style:

- Minimalist
- Clean spacing
- Strong hierarchy
- Technical aesthetics
- Modern SaaS feeling
- Architecture-oriented presentation

## Standard README Order

Use this order when applicable:

1. Banner
2. Badge Bar
3. Project Overview
4. Problem
5. Solution
6. Features
7. Architecture
8. Tech Stack
9. Demo / Screenshots
10. Installation
11. Usage
12. Project Structure
13. Roadmap
14. Lessons Learned
15. Future Improvements
16. Author

Skip sections that would be empty or dishonest. Add a short "Planned" note only when it helps communicate direction.

## Category Adaptation

### AI Projects

Add when relevant:

- Model Workflow
- Evaluation
- Metrics
- Limitations
- Experiments
- Future Research

Focus on methodology, evaluation, architecture, and results.

### Agent Projects

Add when relevant:

- Agent Workflow
- Tools
- MCP Integration
- Skill Architecture
- Prompt Strategy
- Orchestration Flow

Focus on reasoning flow, tool ecosystem, context management, and orchestration.

### Cloud Projects

Add when relevant:

- Infrastructure
- Deployment
- Cost Considerations
- Scalability
- Monitoring

Focus on reliability, operations, architecture, and deployment tradeoffs.

### Full Stack Projects

Add when relevant:

- Frontend
- Backend
- Database
- API Design

Focus on user experience, system architecture, and data flow.

## Architecture Standards

Architecture must be visible whenever the project has meaningful structure.

Prefer:

1. Mermaid diagrams
2. Excalidraw exports
3. Architecture images under `assets/` or `architecture/`

Every architecture section should explain:

- Components
- Responsibilities
- Data flow
- Scalability considerations

Use Mermaid when a diagram can be represented clearly in text. Do not create fake components.

## Badge Strategy

Use consistent Shields.io badges. Keep the badge bar compact and useful.

Recommended badge categories:

- Status
- Type
- Architecture
- Cloud
- AI
- Database
- Frontend
- Backend
- DevOps

Examples: AI Engineering, RAG, GraphRAG, Agents, AWS, Serverless, React, Spring Boot, Docker, PostgreSQL.

Prefer visual consistency over badge quantity.

## Tech Stack Section

Use visual icon systems when useful, especially `skillicons.dev`.

Group technologies by:

- Frontend
- Backend
- Database
- Cloud
- AI
- DevOps
- Observability

Only include technologies actually present or explicitly planned.

## Banner System

Recommend `assets/banner.png` for each repository.

The banner should communicate:

- Project purpose
- Technical area
- Visual identity

If generating a banner prompt, use the design system palette and describe the project category, main architecture metaphor, and title. Avoid visual clutter.

## Storytelling Standard

Every README should answer:

- Why was this built?
- What problem does it solve?
- What technical challenges existed?
- What was learned?
- What would be improved?

The README should communicate engineering growth, not just feature inventory.

## Author Footer

Use this footer unless the user asks otherwise:

```md
## Author

Built by Nicolas Hoyos

Software Engineering - AI Engineering - Software Architecture - Cloud & Agent Systems

Building intelligent systems, scalable architectures, and practical AI products.
```

## Output Contract

When applying this skill, provide or update:

- `README.md`
- README structure
- Badge strategy
- Architecture section
- Folder recommendations
- Visual consistency recommendations

Optional when useful:

- Banner prompts
- Mermaid diagrams
- Shields.io configurations
- Asset recommendations

## Recommended Repository Structure

Recommend this structure when it fits the project:

```txt
README.md
AGENTS.md
skills/
docs/
assets/
examples/
architecture/
```

The repository should feel like an engineering product, not a code dump.

## Quality Rules

Never generate:

- Generic README templates
- Empty marketing content
- Fake metrics
- Invented architecture
- Unsupported claims

Always:

- Analyze repository context
- Adapt structure to project type
- Maintain design consistency
- Prioritize technical clarity
- Showcase engineering decisions
```

