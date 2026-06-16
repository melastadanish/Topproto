# TOP PROTO — Agent Instructions

## What This Repo Is
Content repository for topproto.com — a prototyping-first CNC machining and manufacturing services company based in Dongguan, China.

**Focus:** Rapid prototyping (1–50 parts). Not bulk production. Services span CNC machining, 3D printing, sheet metal, injection molding, vacuum casting, and wire EDM.

---

## Core Files — Read Before Any Page

| File | Purpose | Read When |
|---|---|---|
| `_system/CLIENT-DATA-MAP.md` | All verified facts and stats | Before writing any claim |
| `_system/WritingSystem.md` | Copy rules, QA framework, banned phrases | Before writing any content |
| `_system/execution-plan.md` | All pages, phases, priorities | When choosing what to write next |
| `_system/progress.md` | Current completion state | At the start of every session |
| `sitemap.md` | Master URL structure | When building internal links |
| `reusablesections.md` | Reusable content blocks (RS-01 through RS-11) | Before writing any new page |
| `design.md` | Visual design decisions | For layout/component references |

---

## Workflow — One Page Per Session

1. Read `_system/progress.md` to find the next page
2. Read `_system/CLIENT-DATA-MAP.md` to get verified claims
3. Read `_system/WritingSystem.md` QA rules before writing
4. Check `reusablesections.md` for blocks to reuse
5. Write the page section by section — confirm with user before each section if requested
6. Run the 5-pass QA on the completed page
7. Update `_system/progress.md` after saving the file
8. Commit with: `feat: add [page-name] content`

**Do NOT edit any file until user confirms.** Present content in chat first.

---

## Naming Convention

- Files: `kebab-case.md`
- H1: exact target keyword only — no decoration
- Meta title: `[Keyword] | TOP PROTO`
- Slugs: match file names

---

## SEO Rules

- H1 = pure target keyword
- Target keyword: minimum 5–6 appearances per page (H1, H2s, body, FAQ, image alts)
- FAQ: minimum 5 Q&As targeting long-tail variations — written for GEO/SGE/AI search
- Every page must include one **AI-quotable paragraph** — self-contained, factual, liftable verbatim by AI search
- Internal links: minimum 3 per page (service → material, service → industry, or service → blog)

---

## Voice & Persona

Write as: technical writer with mechanical engineering background and 20 years of CNC/prototyping industry experience.

- Pass 1: technical depth — score against AI detection criteria
- Pass 2: humanise — vary sentence length, rhythm, add industry insight, remove AI patterns

---

## Folder = Content Type

| Folder | Type |
|---|---|
| `General Pages/` | Static core pages (home, about, contact, FAQ, QA, quote) |
| `Services/` | Service hub + material + finish sub-pages |
| `Industries/` | Industry hub + part-type sub-pages |
| `Blogs/` | Blog posts (educational) |
| `Case Studies/` | Project case studies |
| `Locations/` | Country + city pages |
| `_system/` | Governance docs — never published |

---

## Internal Linking Architecture

Three silos — never mix them structurally:

1. **Services silo:** `/precision-machining-services/` → `/cnc-milling-services/` → `/cnc-milling-services/aluminium-cnc-milling-services/`
2. **Industries silo:** `/manufacturing-industries/` → `/aerospace-manufacturing/` → `/aerospace-cnc-machining/`
3. **Locations silo:** `/cnc-machining-usa/` → `/cnc-machining-usa/los-angeles/`

Cross-silo links are allowed — service pages link to industries, industry pages link to services. Blog posts link to service and material pages.

---

## Reusable Sections — Always Check First

Before writing any section, check `reusablesections.md`. Current blocks:
- RS-01: Quality Process (Pre/In/Final)
- RS-02: How It Works (6-step)
- RS-03: Final CTA + Contact Form
- RS-04: Testimonials
- RS-05: Prototyping vs Production
- RS-06: All Services Grid
- RS-07: Certifications & Trust Block
- RS-08: Industries Grid
- RS-09: Instant Quote CTA Bar (inline)
- RS-10: How Ordering Works (3-step compact)
- RS-11: Technology Comparison Table

---

## Commit Format

```
feat: add [page-slug] content
fix: update [page-slug] — [what changed]
docs: update _system/progress.md
```

One page per commit.
