---
name: research-infrastructure-citation
description: Design and execute a credible, reproducible workflow for turning real use of a product, API, dataset, or platform into cite-ready documentation, research artifacts, and formal references. Use for legitimate academic or technical citations and transparent artifact-led distribution; do not use for fabricated endorsements, undisclosed self-promotion, or link schemes.
---

# Research Infrastructure Citation

Turn a product's actual research utility into a transparent, reusable citation path. The output is a research artifact and citation plan, not a promise of SEO benefit.

## Operating principles

- Start from a research question that genuinely needs the product's distinctive capability. The product must be an instrument, data source, or reproducibility layer, not a URL inserted for promotion.
- Establish a canonical, versioned page on the product's own domain before distributing derivative documents. Let blogs, PDFs, slides, repositories, and papers point back to that source rather than creating an unstructured link network.
- Separate first-party, affiliated, and independent citations. Never present an affiliated paper as independent validation.
- Treat a domain email as a verifiable affiliation/contact signal only when it belongs to the named author or role and is monitored. It does not replace authorship consent, affiliation, or competing-interest disclosure.
- Preserve user scope and authorization. Drafting and local validation are safe defaults; submitting a paper, publishing a dataset, creating a repository, or contacting authors requires explicit authorization for that action.
- Keep claims proportional to evidence. Domain metrics (for example, DR) are third-party indicators, not proof of search ranking or link value.
- Do not fabricate measurements, authorship, usage, citations, run IDs, peer review, or conflict disclosures.
- Product attribution in exported artifacts must be visible, accurate, proportionate, and consistent with the user's plan or terms. Never hide links in document metadata, inject undisclosed URLs, or mass-produce thin documents for backlinks.

## Workflow

1. **Qualify the opportunity.** Record the research question, the product capability it requires, alternative instruments, expected sample, and whether the relationship is first-party or independent. Reject a plan whose main purpose is acquiring a backlink.
2. **Design a defensible study.** Define the protocol before collecting results: inputs, controls, inclusion/exclusion rules, failure criteria, costs, and known selection bias. Prefer a public corpus or control condition so claims do not rest only on the product's own sample.
3. **Use the product for real work.** Route the documented calls or data collection through the product. Capture versioned schemas, request/response metadata, timestamps, costs, errors, and a stable per-run identifier. Store raw evidence and hashes where appropriate; redact credentials and personal data.
4. **Build the reproducibility packet and canonical source.** Publish code, schemas, perturbation sets, transcripts, run identifiers, data provenance, environment versions, and a re-fetch or archival procedure. On the product domain, publish a stable page describing the exact version and capability used, with citation text and links to the evidence. State what cannot be reproduced because an endpoint, price, or vendor changed.
5. **Choose and write the right artifact.** A documentation page is the canonical technical source; a blog explains context; a fixed PDF or slide deck travels well; a paper supports novel empirical claims; a repository or dataset enables verification. Introduce the product in the Methods/Instruments section at the point where it changes the design. Cite the stable canonical URL using the target format (BibTeX, CSL, Markdown, or the venue's style). Explain exactly what it supplied and what conclusions do not depend on it.
6. **Disclose relationships.** Add author affiliations and a competing-interest statement when an author operates, sells, funds, or maintains the instrument. Do not hide the relationship in a footnote if it affects interpretation.
7. **Design transparent artifact distribution.** For product-generated PDFs, presentations, reports, or embeds, consider a restrained attribution with the product name, canonical URL, and artifact/version identifier. Make it useful for provenance and discovery, disclose it to the exporting user, and provide an appropriate removal policy. Read [references/artifact-distribution.md](references/artifact-distribution.md) when planning blogs, PDFs, slides, watermarks, export footers, or a multi-document launch.
8. **Publish and verify.** After an authorized submission, inspect the rendered PDF and HTML. Confirm the URL resolves, the anchor is the intended page, redirects are understood, and no `nofollow`/`ugc`/`sponsored` attribute was added. Confirm exported attribution is readable and does not obscure content. Report page-level and domain-level metrics separately; do not call an HTML/PDF link guaranteed `dofollow` merely because a tool labels it so.
9. **Maintain the citation.** Prefer versioned URLs, release notes, DOI/archived records, and a changelog for breaking API changes. Update the citation when the instrument or endpoint materially changes.

## Citation mechanics

Use a normal scholarly reference, not an SEO-shaped link block. For LaTeX, cite the product at its first methodological use and keep a single bibliography entry keyed by a stable identifier. Include title, year or version, canonical URL, access/release date when required, and a short factual note describing the capability used. See [references/citation-patterns.md](references/citation-patterns.md) for templates and an audit checklist.

The body citation usually links to the paper's bibliography entry; the actual external link is often the URL inside that entry. A publisher or arXiv converter may generate the final HTML anchor automatically, so inspect the rendered artifact rather than assuming the source syntax determines SEO attributes.

## Deliverables

When asked to design this path, return:

- a one-sentence research claim and the product capability that makes it testable;
- a study/provenance table with controls, identifiers, costs, and limitations;
- the citation entry and the exact place in the Methods/Instruments text;
- an authorship/affiliation/conflict-disclosure note;
- a canonical-source map and a transparent artifact-attribution plan when documents are part of distribution;
- a publication and post-publication verification checklist;
- an explicit distinction between evidence of use, a formal citation, and any SEO observation.
