---
name: research-infrastructure-citation
description: Design and execute a credible, reproducible workflow for citing a product, API, dataset, or platform as research infrastructure. Use when a user wants legitimate academic or technical references that arise from real product use; do not use for fabricated endorsements, undisclosed self-promotion, or link schemes.
---

# Research Infrastructure Citation

Turn a product's actual research utility into a transparent, reusable citation path. The output is a research artifact and citation plan, not a promise of SEO benefit.

## Operating principles

- Start from a research question that genuinely needs the product's distinctive capability. The product must be an instrument, data source, or reproducibility layer, not a URL inserted for promotion.
- Separate first-party, affiliated, and independent citations. Never present an affiliated paper as independent validation.
- Preserve user scope and authorization. Drafting and local validation are safe defaults; submitting a paper, publishing a dataset, creating a repository, or contacting authors requires explicit authorization for that action.
- Keep claims proportional to evidence. Domain metrics (for example, DR) are third-party indicators, not proof of search ranking or link value.
- Do not fabricate measurements, authorship, usage, citations, run IDs, peer review, or conflict disclosures.

## Workflow

1. **Qualify the opportunity.** Record the research question, the product capability it requires, alternative instruments, expected sample, and whether the relationship is first-party or independent. Reject a plan whose main purpose is acquiring a backlink.
2. **Design a defensible study.** Define the protocol before collecting results: inputs, controls, inclusion/exclusion rules, failure criteria, costs, and known selection bias. Prefer a public corpus or control condition so claims do not rest only on the product's own sample.
3. **Use the product for real work.** Route the documented calls or data collection through the product. Capture versioned schemas, request/response metadata, timestamps, costs, errors, and a stable per-run identifier. Store raw evidence and hashes where appropriate; redact credentials and personal data.
4. **Build the reproducibility packet.** Publish code, schemas, perturbation sets, transcripts, run identifiers, data provenance, environment versions, and a re-fetch or archival procedure. State what cannot be reproduced because an endpoint, price, or vendor changed.
5. **Write the paper or technical report.** Introduce the product in the Methods/Instruments section at the point where it changes the design. Cite a stable documentation or product URL using the target format (BibTeX, CSL, Markdown, or the venue's style). Explain exactly what it supplied and what conclusions do not depend on it.
6. **Disclose relationships.** Add author affiliations and a competing-interest statement when an author operates, sells, funds, or maintains the instrument. Do not hide the relationship in a footnote if it affects interpretation.
7. **Publish and verify.** After an authorized submission, inspect the rendered PDF and HTML. Confirm the URL resolves, the anchor is the intended page, redirects are understood, and no `nofollow`/`ugc`/`sponsored` attribute was added. Report page-level and domain-level metrics separately; do not call an HTML/PDF link guaranteed `dofollow` merely because a tool labels it so.
8. **Maintain the citation.** Prefer versioned URLs, release notes, DOI/archived records, and a changelog for breaking API changes. Update the citation when the instrument or endpoint materially changes.

## Citation mechanics

Use a normal scholarly reference, not an SEO-shaped link block. For LaTeX, cite the product at its first methodological use and keep a single bibliography entry keyed by a stable identifier. Include title, year or version, canonical URL, access/release date when required, and a short factual note describing the capability used. See [references/citation-patterns.md](references/citation-patterns.md) for templates and an audit checklist.

The body citation usually links to the paper's bibliography entry; the actual external link is often the URL inside that entry. A publisher or arXiv converter may generate the final HTML anchor automatically, so inspect the rendered artifact rather than assuming the source syntax determines SEO attributes.

## Deliverables

When asked to design this path, return:

- a one-sentence research claim and the product capability that makes it testable;
- a study/provenance table with controls, identifiers, costs, and limitations;
- the citation entry and the exact place in the Methods/Instruments text;
- an authorship/affiliation/conflict-disclosure note;
- a publication and post-publication verification checklist;
- an explicit distinction between evidence of use, a formal citation, and any SEO observation.
