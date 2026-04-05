# Project Rulebook: AI-Powered K3 Health Promotion Media

**Read this file at the start of every session.**

## 1. Project Overview

**Description:** A practical guide and resource repository for leveraging AI tools (NotebookLM, Canva AI, Sora) to create professional health promotion media for occupational health and safety (K3) in workplace settings.

**Goal:** Create open-source educational materials that enable K3 professionals, health promoters, and students to efficiently produce high-quality posters, infographics, and videos using AI-assisted workflows.

**Target Audience:**
- K3 professionals and safety officers
- Health promotion practitioners
- Public health students
- Workplace safety trainers
- Occupational health nurses

## 2. Strict Ground Rules (Guardrails)

- **Never alter raw source materials:** All files in `examples/` and `templates/` should be treated as reference materials
- **Always verify AI-generated content:** All AI-generated health information must be fact-checked against reliable K3 sources (WHO, ILO, OSHA standards)
- **Respect copyright:** Only use royalty-free, Creative Commons, or properly licensed assets
- **Cultural sensitivity:** Ensure all materials are inclusive and appropriate for diverse workplace environments
- **Accessibility first:** All materials must meet WCAG 2.1 AA standards for accessibility
- **Language considerations:** Provide materials in both Indonesian and English where applicable

## 3. Working Relationship & Conventions

**Role:** Act as an AI workflow specialist and K3 communications consultant.

**File Conventions:**
- Markdown files: Use `.md` extension
- Images: Use descriptive filenames (e.g., `poster-fire-safety-final.png`)
- Notebooks: Use `.ipynb` for Jupyter/Colab notebooks
- Videos: Use `.mp4` format for compatibility

**Output Conventions:**
- Save examples to `examples/`
- Save templates to `templates/`
- Save tutorials to `guides/`
- Maintain consistent folder structure

**Progress Logging:**
- Document all workflows in `guides/`
- Track tool updates and API changes in `CHANGELOG.md`
- Maintain known issues in `docs/known-issues.md`

## 4. Key Decisions & Methodology

**Tool Selection:**
- **NotebookLM:** For research synthesis, content generation, and FAQ creation from K3 literature
- **Canva AI:** For poster and infographic design with Magic Design, Text to Image, and Magic Edit
- **Sora:** For short safety video generation (when available)

**Quality Standards:**
- All text must be at grade 6-8 reading level for accessibility
- Font sizes must follow distance-based guidelines (every 10 feet = double text size)
- Color contrast must meet WCAG AA (4.5:1 ratio)
- ISO 7010 safety color standards must be followed

**Design Principles:**
- Hierarchy: Size and position indicate importance
- Contrast: Light vs dark for emphasis
- Balance: Visual weight distribution
- Alignment: Grid-based layouts
- Proximity: Related elements grouped
- Repetition: Consistent styling

## 5. Current Status

**Completed:**
- Initial project structure
- Rulebook and persona definitions
- Basic folder structure

**TODO:**
- Create comprehensive guides for each AI tool
- Develop example workflows
- Create templates for common K3 topics
- Record video tutorials
- Build example gallery
- Write integration guides
- Create troubleshooting documentation

**Known Issues:**
- Sora availability may be limited (not publicly available as of 2026)
- NotebookLM has file size limitations
- Canva free tier has limitations
- API rate limits may affect workflows

## 6. Repository Structure

```
ai-powered-k3-health-promotion/
├── README.md
├── Rule.md (this file)
├── persona.md
├── CHANGELOG.md
├── guides/
│   ├── notebooklm-guide.md
│   ├── canva-ai-guide.md
│   ├── sora-guide.md
│   └── integration-workflow.md
├── templates/
│   ├── posters/
│   ├── infographics/
│   └── storyboards/
├── examples/
│   ├── posters/
│   ├── infographics/
│   └── videos/
├── resources/
│   ├── color-palettes.md
│   ├── font-guidelines.md
│   └── safety-standards.md
└── docs/
    ├── known-issues.md
    └── api-references.md
```

## 7. Session Objectives

When working on this project, focus on:
1. Creating practical, step-by-step guides
2. Providing real-world examples
3. Troubleshooting common issues
4. Maintaining up-to-date tool information
5. Ensuring accessibility and inclusivity

---

*Last updated: 2026-04-05*
