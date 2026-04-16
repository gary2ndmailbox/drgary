
# AskGary.md — Dr Gary Cardiology Wiki Schema
#

---

## Directory Structure

```
drgarywiki/
├── raw/                          # IMMUTABLE. Never modify. Source documents.
│   └── assets/                   # Downloaded images
│
├── wiki/                         # YOUR DOMAIN. Create, update, cross-reference freely.
│   ├── sources/              # One page per ingested source
│   ├── concepts/             # Ideas, frameworks, models
│   ├── entities/             # People, orgs, products, places
│   └── comparisons/          # Comparisons
│   ├── wikiindex.md                  # Master catalog — update on EVERY ingest
├── log.md                    # Append-only chronological record
├── index.md						# User define master hub
└── CLAUDE.md                     # This file.
```
---

## Page Formats

### sources/SLUG.md — one per ingested document
```markdown
---
dg-publish: true
title: "Full Title of Source" 
date_ingested: YYYY-MM-DD
source_type: original article | review article | guideline | consensus | book | memo | report | other
Citation: "Citation"
DOI:"Https://doi.org/DOI"
tags: []
rating: very high | high | medium | low | very low
raw_path: raw/filename.md

---

# [Title]

## Authors, Journal, Affiliations, Type, DOI
- Name of authors
- Journal
- Affiliations
- Type of study
- DOI

## Overview
2–6 sentence plain-English summary.

## Keywords
Keywords provided in first page of document

## Key Takeaways
- Keep the original structure of the document including the sections and their subtitle
- Important takeaways in each paragraph in the document

## Limitations of the document
- methodology, sample size, bias and other limitations

## Key Concepts Mentioned
- [[Concept Name]] — role in this source

## Key Entities Mentioned
- [[Entity Name]] — role in this source

## Wiki Pages Updated
List every wiki page touched during this ingest.
```

### concepts/NAME.md — ideas, frameworks, models
```markdown
---
dg-publish: true
title: "Concept Name"
tags: []
source_count: N
last_updated: YYYY-MM-DD
---

# [Concept Name]

## Definition
Plain-English definition.

## Key concepts
- Concept (For each paragraph or key sentence, provide footnotes and link the source: [[sources/slug]] and rating of the source)

## Contradictions / Open Questions
- Contradictions (provide footnotes and link the sources: [[sources/slug]])

## Connections
- Related to [[Entity or Concept]]

```

### entities/NAME.md — people, orgs, products, places
```markdown
---
dg-publish: true
title: "Entity Name"
tags: []
source_count: N
---

# [Entity Name]

## Details of the concept

## Key Facts
- Fact (For each paragraph or key sentence, provide footnotes and link the source: [[sources/slug]] and rating of the source)

## Contradictions / Open Questions
- Contradictions (provide footnotes and link the sources: [[sources/slug]])

## Connections
- Related to [[Entity or Concept]]
```

---

## Special Files

### wiki/wikiindex.md
Master catalog. **Update on every ingest — no exceptions.**
```
| [[path/to/page]] | One-line description | tags | date |
## | [[sources/acm-hrs-2019]] | Description1 | #consensus, #arrhythmogenic-cardiomyopathy | 2026-04-11 |
## | [[sources/channelopathies-jaha-2025]] | Description2 | #channelopathies, #arrhythmogenic-cardiomyopathy | 2026-04-12 |

```
The LLM reads this first on every query.

### log.md
Append-only. **Never edit past entries.**
```
## [YYYY-MM-DD] ingest | Source Title
## [YYYY-MM-DD] query | Question answered + filed
## [YYYY-MM-DD] lint |  Orphan check + contradiction scan
```
Parseable: `grep "^## \[" log.md | tail -10`

---

## Operations

### INGEST — `> ingest raw/path/to/file.md`
1. Read the source from `raw/`
2. Brief 2–4 sentence takeaway discussion
3. Confirm rating: very high | high | medium | low | very low
4. Choose 5 most relevant tags to be included in SLUG.md and wiki/wikiindex.md. Confirm with me.
5. Create `wiki/sources/SLUG.md`
6. Update `wiki/wikiindex.md`
7. Update or create entity and concept pages touched by this source. Update the source count. Confirm the plan with me.
8. Update the contradictions to relevant entity and concept pages.
9. Append to `log.md`
10. Report: files created/modified, contradictions found

### Improve SLUG — `> improve slug wiki/sources/SLUG.md`
1. Read the SLUG file from 'wiki/sources/SLUG.md` and its raw file in 'raw/source.md`
2. Check for missing section or content in SLUG.md
3. Tell me the plan to improve SLUG.md
4. Update `wiki/sources/SLUG.md`
5. Append to `log.md`

### Update SLUG — `> update slug wiki/sources/SLUG.md`
1. Read the SLUG file from 'wiki/sources/SLUG.md`
2. Update or create entity and concept pages touched by this source. Update the source count. Confirm the plan with me.
3. Update the contradictions to relevant entity and concept pages.
4. Append to `log.md`
5. Report: files created/modified, contradictions found

### QUERY — `> [question]`
1. Only find answer from wiki directory. NEVER search from other source such as internet.
2. Read `wikiindex.md` to find relevant pages
3. Read those pages, drill into linked pages as needed
4. If no relevant answer in wiki directory, return "No relevant answer can be found."
5. Synthesize answer with inline citations: `[[wiki/path]]`


Good answers are knowledge — they should compound in the wiki, not disappear.

### LINT — `> lint`

1. Check for
- Orphan pages (no inbound links)
- Check for Contradictions between pages. Put the findings in "Contradictions / Open Questions" section of relevant pages. 
- Check for concepts mentioned but lacking their own page
- Check for missing cross-references between related pages
2. Suggest: new sources to find, new questions worth pursuing

### Refine — `> refine raw/path/to/file.md`

1. Read the source file
2. Reorganise the page structure in reference to page template defined in this md file. Confirm with me. 
3. Describe key takeaways in sections such as "epidemiology", "pathophysiology", "diagnosis", "management", "Contradictions / Open Questions" etc.

---