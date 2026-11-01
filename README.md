# GrowthOffice — Technical SEO & Organic Visibility

**Public case study · React / TypeScript · Technical SEO · Search discoverability**

**Website analyzed:** https://growthoffice.com.br/

> This is a sanitized, documentation-only portfolio case. The original application and its Git history remain private. The case does not include credentials, customer information, production assets or proprietary source code.

## Context

GrowthOffice is a Brazilian growth consulting business. Its public website presents services, editorial content, case studies and conversion-focused pages. The private development repository uses React, TypeScript and Vite, with SEO-related documentation covering metadata, crawlers, sitemaps and search verification.

## Technical challenge

Websites rendered through JavaScript frameworks require deliberate control over crawlability, indexing, metadata delivery and accessible page structure. Social sharing crawlers may not execute client-side JavaScript, so metadata delivery needs separate verification.

## Scope of the technical SEO review

| Dimension | Review focus | Validation criteria |
| --- | --- | --- |
| Crawlability | HTTP responses, navigation, robots rules | Intended URLs crawlable and internally linked |
| Indexability | Canonicals, status codes, XML sitemap | Consistent index signals |
| Rendering | Response HTML versus rendered DOM | Primary content accessible to intended crawlers |
| Metadata | Titles, descriptions and social preview tags | Relevant tags delivered in server response |
| Structured data | Context-appropriate Schema.org markup | Valid and consistent with visible content |
| UX & accessibility | Semantic structure, keyboard access, forms | Usable with keyboard and assistive technologies |
| Performance | LCP, CLS, INP and asset delivery | Measurements recorded with date and device |

## Process

1. Map public routes and search intent.
2. Compare source HTML, rendered pages and crawler-visible metadata.
3. Prioritize risks to discovery, rendering and indexation.
4. Define acceptance criteria for implementation.
5. Revalidate technical outcomes, then measure search performance over time.

## Documentation and example

- [Architecture and SEO considerations](architecture.md)
- [Technical validation checklist](validation-checklist.md)
- [Demonstration: metadata review](metadata-review.md)
- [Privacy and security scope](SECURITY.md)

## Evidence and outcomes

This portfolio documents **technical review areas and implementation considerations**, not a verified increase in organic traffic, rankings, impressions or AI citations. Such claims require dated evidence from Search Console or another appropriate source.

## Maintainer

Technical review and case-study curation by **Priscilla Simoni** — Technical SEO, GEO/AEO and web engineering.

[Professional portfolio](https://priscillasimoni.com/) · [LinkedIn](https://www.linkedin.com/in/priscillasimoni/)

## Rights

All original case-study text is reserved. No general license to reuse it is granted. No production code or third-party libraries are redistributed.
