# Research Infrastructure Citation Skill

A Codex skill for designing credible, reproducible research in which a product,
API, dataset, or platform is cited because it is genuinely used as research
infrastructure.

The workflow covers study design, provenance, reproducibility artifacts,
scholarly citation mechanics, relationship disclosure, publication, and
rendered-link verification. It also covers canonical product documentation,
domain-email identity signals, and transparent attribution in blogs, PDFs,
presentations, and product-generated exports. It explicitly distinguishes a
formal citation from independent endorsement or guaranteed SEO value.

## Install

Install from this repository with Codex's skill installer, or place this
directory under your Codex skills directory as
`research-infrastructure-citation`.

## Use

Invoke `$research-infrastructure-citation` when you want to design or audit a
product-as-research-instrument citation path.

## Structure

- `SKILL.md`: workflow and operating constraints
- `agents/openai.yaml`: Codex UI metadata
- `references/citation-patterns.md`: LaTeX/BibTeX patterns and link-audit notes
- `references/artifact-distribution.md`: canonical content, domain identity, and export-attribution patterns
