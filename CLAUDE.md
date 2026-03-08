# Auto Tidy Tuesday

## Project Purpose

This project serves two purposes:
1. **Academic presentation** — A RevealJS slide deck (.qmd) providing a high-level overview of how to think about and reason about agentic AI for academic audiences
2. **Research demonstration** — A live, interactive Tidy Tuesday analysis where audience members pick a dataset and watch iterative agentic questioning and development unfold

## Sister Projects

Thin routes link to two ongoing projects in the same `repos/` folder:
- `ayr-town-centre-vitality` — Applied, GIS-heavy: choropleths, comprehensive spatial data acquisition and processing workflows
- `economic_inactivity` — Academic, technical: statistical modelling of economic inactivity patterns, demographic/regional variation

Both are potential live demo candidates alongside Tidy Tuesday — the audience can choose which to explore.

## Technical Conventions

- **Primary format**: Quarto (.qmd) with RevealJS output for slides
- **Languages**: R primary, but Python should be shown too (especially for GIS where Python has comparative advantages)
- **References**: Stored in `refs/` as .bib files; cite from .qmd using standard Quarto/Pandoc citation syntax
- **Audience**: Academics with interest in data science, GIS, and visual reasoning
- **Key theme**: Visual reasoning as an area where humans and AI have complementary strengths

## Project Structure

```
auto-tidy-tuesday/
├── CLAUDE.md
├── _quarto.yml          # Quarto project config
├── .gitignore
├── refs/
│   └── references.bib   # Shared bibliography
├── slides/
│   └── index.qmd        # Main RevealJS slide deck
└── demos/               # Live demo scripts (R and Python)
```

## Commands

- `quarto preview slides/index.qmd` — Preview the slide deck
- `quarto render` — Render all outputs
