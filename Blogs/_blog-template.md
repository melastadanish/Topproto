# [Blog Post Title]
**Status:** Draft
**Slug:** /[post-slug]/
**Meta Title:** [Post Title] | TOP PROTO
**Meta Description:** [150–160 character description. Include primary keyword. Describe what the reader will learn.]
**Category:** [Guides | Materials | Comparisons | Industry | Process]
**Target Keyword:** [primary keyword]
**Secondary Keywords:** [keyword 2, keyword 3, keyword 4]
**Reading Time:** [X min read — calculate at ~200 words/min after writing]
**Author:** TOP PROTO Engineering Team
**Publish Date:** [YYYY-MM-DD]
**Featured Image:** [description of image needed — e.g. "CMM probe measuring aluminium bracket"]

---

## Page Structure Reference

```
[Breadcrumb]
[Post Hero]
[Post Meta Bar]
[Table of Contents — sticky desktop / accordion mobile]
[Article Body]
  └── [Inline CTA — at ~40% through article]
[Key Takeaways Box]
[Author Block]
[Related Articles — 3 cards]
[End CTA]
```

---

## Breadcrumb
Blog → [Category] → [Post Title]

---

## Post Hero
**Design options (developer picks based on featured image quality):**
- Option A: Full-width featured image (16:9), post title overlaid at bottom with dark gradient
- Option B: Split — image left 50%, post meta right 50% on white background
- Option C: No image — typographic hero, white background, category tag + large H1

**Elements:**
- Category tag: `[CATEGORY]` (pill/chip, brand colour)
- H1: [Post Title]
- Meta bar: [Author] · [Date] · [Reading time]
- Featured image (if Option A or B)

---

## Post Meta Bar
**Design:** Single line below H1. Light grey rule below.
- Format: `By TOP PROTO Engineering Team · [Month DD, YYYY] · [X min read]`
- Category tag links to category archive: /blog/[category]/

---

## Table of Contents
**Design:**
- Desktop: Sticky sidebar (right column, 280px). Highlights active section on scroll.
- Mobile: Collapsed accordion — "Contents" label with chevron, expands on tap.
- Auto-generated from H2 headings in article body.
- Smooth scroll to section on click.

```
Contents
├── [H2 Section 1 title]
├── [H2 Section 2 title]
├── [H2 Section 3 title]
├── [H2 Section 4 title]
└── [H2 Section 5 title]
```

---

## Article Body
**Design:** Single column, max-width 72ch (approx 700px). Left column on desktop with TOC sidebar right. Full-width on mobile.

**Typography:**
- Body: 17–18px, 1.7 line-height, generous paragraph spacing
- H2: Clear visual hierarchy — section breaks
- H3: Sub-section within H2
- Bold: Key terms and callouts only — not decorative
- No italics for emphasis — use bold sparingly instead

**Content guidelines:**
- Open with the problem or question — not "In this article we will explore..."
- H2 sections answer the question directly — no buried lede
- Use tables for comparisons and specifications — engineers scan
- Use numbered lists for processes and sequences; bullet lists for non-ordered information
- Include specific numbers, tolerances, and material properties — not vague claims
- Acknowledge trade-offs honestly — this is what engineers trust
- Write as: technical writer, mechanical engineering background, 20yr CNC industry experience

---

### Article Outline (fill in per post)

**Introduction** (no H2 — flows directly after meta bar)
[2–3 paragraphs. State the problem or question. Tell the reader what they'll know after reading. No "In this guide we'll cover..." opener — start with the engineering context.]

---

**H2: [Section 1 Title]**
[Content]

---

**H2: [Section 2 Title]**
[Content]

---

**H2: [Section 3 Title]**
[Content]

> **💡 Inline CTA — insert here (at approximately 40% through the article)**
> Design: Full-width callout block within article column. Brand colour background or light grey. Short copy + button.
> Copy: "Working on a part that needs [topic]? Upload your STEP file — we'll review it and quote within 24 hours."
> Button: Get an Instant Quote → [/get-a-quote/]

---

**H2: [Section 4 Title]**
[Content]

---

**H2: [Section 5 Title]**
[Content]

---

## Key Takeaways Box
**Design:** Styled callout box. Light blue or light grey background. Thin left border in brand colour. Placed after last H2 section, before author block.
**Heading:** Key Takeaways
**Content:** 3–5 bullet points summarising the most important points from the article. Written for the reader who scrolls to the bottom first.

- [Takeaway 1]
- [Takeaway 2]
- [Takeaway 3]
- [Takeaway 4]
- [Takeaway 5]

---

## Author Block
**Design:** Small card below key takeaways. Author avatar (photo or initials icon) left. Name and title right.
- Name: TOP PROTO Engineering Team
- Title: Technical Writing — TOP PROTO, Dongguan
- Bio (1–2 lines): Engineering and manufacturing content written by the team behind the parts. 20+ years of CNC production experience in Dongguan, China.

---

## Related Articles
**Design:** 3-column card grid. Light grey background. Same card design as blog archive grid.
**Heading:** Related Articles
**Selection:** Same category, or manually tagged in CMS. 3 articles maximum.
- [[related-post-1]]
- [[related-post-2]]
- [[related-post-3]]

---

## End CTA
**Design:** RS-03 variant — adapted to article topic. Full width. 2-column split.
**Heading:** [Topic-specific — e.g. for DFM article: "Get a DFM Review With Your Quote" | for material article: "Machine Your [Material] Parts at TOP PROTO"]
**Subtext:** Upload your STEP file. We return a quote with DFM review within 24 hours — tolerance feasibility, finish interactions, and material suitability included.
**Bullets:**
- ✅ ISO 9001:2015 certified facility
- ✅ Tolerances to ±0.005mm, CMM verified
- ✅ Material cert and dimensional report with every order
- ✅ From 3 days lead time
**CTA:** Get Instant Quote

---

## SEO Checklist (complete before publishing)
- [ ] Primary keyword in H1
- [ ] Primary keyword in first 100 words of article body
- [ ] Primary keyword in meta title and meta description
- [ ] At least 3 H2 sections contain secondary keywords naturally
- [ ] Featured image has descriptive alt text including primary keyword
- [ ] At least 3 internal links to relevant service or material pages
- [ ] At least 2 internal links from other relevant pages pointing to this post
- [ ] Breadcrumb schema added
- [ ] Open Graph image and title set
- [ ] Canonical URL set to /blog/[post-slug]/
- [ ] Reading time calculated and added to meta bar

---

## Internal Links (complete per post)
**Up:** [[blog-archive]] | [[blog/[category]/]]
**Linked service pages:** [e.g. [[cnc-milling-services]] | [[aluminium-cnc-machining-services]]]
**Linked related posts:** [e.g. [[design-for-manufacturability]] | [[cnc-surface-finish-guide]]]
