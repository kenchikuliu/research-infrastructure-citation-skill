# Artifact-Led Distribution

Read this reference when a launch uses first-party web content, blogs, PDFs,
presentations, reports, embeds, or product-generated exports as citation and
distribution surfaces.

## Build a source hierarchy

Use one canonical source and give each derivative artifact a distinct job:

| Surface | Primary job | Minimum contents |
| --- | --- | --- |
| Product-domain documentation | Authoritative capability and version reference | Stable URL, version/date, factual capability description, evidence links, citation snippet |
| Blog or research note | Explain the problem and findings to practitioners | Context, method summary, limitations, canonical source link |
| PDF or white paper | Preserve a fixed, portable record | Title, authors, affiliations, date/version, canonical URL, references |
| Slide deck | Support presentation and forwarding | Concise findings, source notes, unobtrusive product attribution, canonical URL |
| Academic paper | Establish and test a novel claim | Methods, controls, results, limitations, disclosures, formal bibliography |
| Repository or dataset | Make the claim inspectable | Code/data versions, provenance, run IDs, license, `CITATION.cff` or BibTeX |

Do not duplicate the same thin text across many files to manufacture links. A
small number of useful, internally consistent artifacts is stronger than a large
document count.

## Use identity signals correctly

A real email on the product domain can help readers verify an author's
affiliation and contact the responsible party. Use it only with the person's
consent, keep the mailbox active, and state the corresponding affiliation in the
artifact. A domain email is not evidence that the work is independent and is not
a substitute for a competing-interest statement.

For role-owned documentation, a monitored address such as `research@` or
`docs@` may be more durable than a personal mailbox. Do not invent people,
credentials, or institutional relationships.

## Design product-native attribution

Product-generated artifacts can carry their provenance into the places where
they are viewed, similar to a presentation tool placing a "Created with"
attribution on exported slides. A useful attribution may contain:

- the product name or mark;
- one canonical product or artifact URL;
- an artifact/version ID or generation date when it helps verification;
- a short citation or source label when the artifact reports research.

Keep attribution visible but subordinate to the user's content. Explain it
before export and define when it can be removed (for example, by plan, policy,
or an explicit export control). Do not disguise advertising as authorship,
inject invisible links, overwrite the user's author metadata, or claim that the
product produced conclusions it only helped format.

## Connect the artifacts

Use a directed source graph rather than a circular link exchange:

```text
canonical product documentation
        |-- evidence repository or dataset
        |-- blog / research note
        |-- PDF / white paper
        |-- presentation
        `-- paper bibliography
```

Derivative artifacts may link to the evidence and canonical documentation.
Avoid making every artifact link to every other artifact solely to inflate link
counts.

## Verify and measure

Before publication, check names, affiliations, domain email, canonical URL,
version, disclosures, and link targets. After publication, verify rendered links
and redirects on each surface.

Measure useful outcomes separately: artifact exports/views, qualified referral
traffic, documentation use, reproductions, formal citations, and independent
citations. Do not combine them into a single "backlink" success metric or infer
scientific endorsement from traffic.
