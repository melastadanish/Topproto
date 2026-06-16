# Blog Archive
**Status:** Complete
**Slug:** /blog/
**Meta Title:** CNC Machining Blog | Engineering Guides & Resources | TOP PROTO
**Meta Description:** Engineering guides, material comparisons, DFM tips, and machining resources from TOP PROTO — written for engineers who design and specify precision CNC machined parts.
**Target Keyword:** CNC Machining Blog
**Secondary Keywords:** cnc machining guides, design for manufacturability, cnc machining resources, engineering blog

---
## Sections
- [x] 1. Hero
- [x] 2. Category Filter
- [x] 3. Featured Post
- [x] 4. Post Grid
- [x] 5. Inline CTA Card (every 6 posts)
- [x] 6. Newsletter / Resource CTA

---

## Section 1: Hero
**Design:** Minimal. White background. Centre-aligned text. No hero image — the content grid is the visual. Keep it tight — visitors are here for articles, not a landing page experience.
- H1: CNC Machining Resources
- Subheading: Engineering guides, material comparisons, DFM tips, and process references — written for engineers who design and specify precision CNC machined parts.
- Search bar: placeholder text "Search articles — tolerances, materials, surface finish..."
- No CTA button in hero — category tabs are immediately below

---

## Section 2: Category Filter
**Design:** Sticky horizontal tab bar. Scrolls with the page until it hits the viewport top, then sticks. Light grey background. Active tab underlined in brand colour.

**Tabs:**
- All
- Guides
- Materials
- Comparisons
- Industry
- Process

**Behaviour:**
- Clicking a tab filters the post grid below (JS filter or separate category archive pages — developer decision)
- Active category shown in URL: /blog/?category=materials
- Tab bar remains sticky while scrolling the post grid

---

## Section 3: Featured Post
**Design:** Full-width featured card. White background. Image left (60%) — text right (40%). Or full-width image with text overlay at bottom. Larger visual treatment than grid cards.

**Card elements:**
- Category tag (pill/chip — e.g. `GUIDE`)
- H2: Post title (linked)
- Excerpt: 2–3 lines of article intro text
- Meta: Author · Date · Reading time (e.g. "8 min read")
- CTA button: "Read Article →"

**Featured post selection:** Manually curated — set in CMS. Default to most recent if none set.

**Example featured post:** [[design-for-manufacturability]] — DFM Guide for CNC Machined Parts

---

## Section 4: Post Grid
**Design:** 3-column card grid. White background. Responsive: 2-col tablet, 1-col mobile.

**Each card contains:**
- Featured image (16:9 ratio, consistent crop)
- Category tag (pill — e.g. `MATERIALS`, `COMPARISON`, `GUIDE`)
- Post title (H3, linked, max 2 lines)
- Excerpt (1 line, truncated with ellipsis)
- Meta row: Date · Reading time

**Card hover state:** Subtle shadow lift. Title underlines. Entire card is clickable.

**Post order:** Most recent first (default). Category filter overrides to most recent in that category.

**Load more:** "Load More Articles" button at bottom of grid — not pagination. Loads next 9 posts.

---

## Section 5: Inline CTA Card
**Design:** Appears every 6 posts in the grid — replaces one card slot. Brand colour background (navy or dark). White text. Same card dimensions as post cards.

**Content:**
- Eyebrow: `GET A QUOTE`
- Headline: Ready to Machine Your Parts?
- Subtext: Upload a STEP file. Quote in 24 hours. DFM review included.
- CTA button: Get Instant Quote (links to /get-a-quote/)

**Frequency:** Position 7, 13, 19... (after every 6 post cards)

---

## Section 6: Newsletter / Resource CTA
**Design:** Full-width banner. Light grey background. 2-column: text left, email input right.
**Heading:** Get New Guides in Your Inbox
**Subtext:** Engineering resources on CNC machining, materials, surface finishing, and DFM — published when there's something worth saying. No marketing email. Unsubscribe any time.
**Input:** Email address field + "Subscribe" button
**Note:** If email marketing is not in scope for launch, replace this section with a second inline quote CTA (RS-03 variant).

---

## Category Pages
**Design:** Same layout as archive — hero changes to reflect category name and description. Filter tab highlights active category. Breadcrumb: Blog → [Category].

| Category | Slug | Description |
|---|---|---|
| Guides | /blog/guides/ | Step-by-step technical references for engineers designing CNC machined parts |
| Materials | /blog/materials/ | Properties, machinability, and selection guides for metals and engineering plastics |
| Comparisons | /blog/comparisons/ | Process and material comparisons to help engineers make the right specification decision |
| Industry | /blog/industry/ | Machining considerations and part examples for specific industries |
| Process | /blog/process/ | Surface finishing, tolerances, quality, and machining process deep-dives |

---

## SEO Notes
- Blog index `/blog/` should be in main navigation under Resources
- Category pages are crawlable — not filtered via JS only
- Each post has canonical URL: `/[post-slug]/` (root level — not nested under /blog/)
- Breadcrumb schema on all category and post pages
- Open Graph image: featured image per post; fallback to site OG image

---

## Internal Links (Silo)
**Up:** [[precision-machining-services]] | [[custom-cnc-machining-services]]
**Posts (initial):** [[what-is-cnc-machining]] | [[design-for-manufacturability]] | [[cnc-surface-finish-guide]] | [[cnc-tolerances-and-standards]] | [[cnc-vs-3d-printing]] | [[5-axis-vs-3-axis-cnc-machining]]
