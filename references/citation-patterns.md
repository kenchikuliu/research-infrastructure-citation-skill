# Citation Patterns and Audit Notes

Use this reference when the target document is LaTeX/ACM-like, or when a rendered citation must be checked for a real external link.

## LaTeX pattern

At the first methodological use:

```latex
The measurements were executed through the Product API~\cite{product-api},
which exposes versioned schemas and a stable run identifier for each call.
```

In the bibliography source (adapt fields to the venue):

```bibtex
@misc{product-api,
  title        = {Product API},
  year         = {2026},
  howpublished = {\url{https://example.com/docs}},
  note         = {Version 2.3; capability used: ...; accessed 2026-09-15}
}
```

Use the venue's required bibliography style. Do not add multiple duplicate entries merely to repeat a URL.

## Methods wording

State four facts in prose:

1. What the instrument aggregates or exposes.
2. What the study actually used (for example, schemas, validation, run IDs, or data).
3. What was measured independently of the instrument and what was not.
4. Which sampling, gateway, pricing, or availability limitations remain.

Avoid claims such as "trusted by researchers" unless the evidence and cited sources support them.

## Relationship disclosure

If an author is affiliated with the provider, say so in the author affiliation and in a competing-interest section. A first-party reference can be useful and valid, but it is not independent endorsement.

## Rendered-link audit

Check both artifacts after publication:

- PDF: the bibliography URL is present and its link annotation opens the canonical page.
- HTML: the bibliography contains an external `href` to the canonical page; note any redirect and inspect `rel` attributes.
- Citation location: the in-text `[n]` or author-year marker may be an internal anchor, while only the bibliography URL is an external backlink.
- SEO report: record the exact page URL, discovery date, indexability, `rel` value, and tool/domain metric separately. Never infer ranking impact from DR alone.

## Minimum evidence record

Keep a machine-readable record containing the paper/report identifier, source revision, citation key, canonical URL, rendered URLs, call/run IDs, data and code repository, author relationship, disclosure text, and verification timestamp.
