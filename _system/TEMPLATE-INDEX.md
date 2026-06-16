# TOP PROTO — Template Index

> Use this file to find the correct template before writing any new page.
> Every page type has exactly one template. Do not write freehand — always start from the template.

---

## How to Use a Template

1. Find the page type in the table below
2. Copy the template file to the correct folder
3. Rename it to the target slug (e.g. `stainless-steel-cnc-machining-services.md`)
4. Fill in every `[PLACEHOLDER]` — replace with real content
5. Remove all template guidance comments before publishing
6. Run the 5-pass QA from `WritingSystem.md` before marking ✅

---

## Template Map

### Services — CNC Machining

| Page Type | Template File | Example Output File |
|---|---|---|
| CNC material hub page (e.g. Aluminium, Stainless Steel) | `Services/Custom CNC Machining Services/_cnc-material-template.md` | `aluminium-cnc-machining-services.md` |
| CNC grade sub-page (e.g. 6061, 7075) | Use CNC material template — shorter version | `aluminium-6061-cnc-machining-services.md` |
| CNC Milling material sub-page | Use CNC material template — adapt for milling context | `cnc-milling-aluminium.md` |
| CNC Turning material sub-page | Use CNC material template — adapt for turning context | `cnc-turning-aluminium.md` |
| 5-Axis material sub-page | Use CNC material template — adapt for 5-axis context | `5-axis-aluminium-cnc.md` |

**Folder locations:**
- CNC material hubs: `Services/Custom CNC Machining Services/Metals/` or `.../Plastics/`
- CNC Milling materials: `Services/CNC Milling Services/Materials/`
- CNC Turning materials: `Services/CNC Turning Services/Materials/`
- 5-Axis materials: `Services/5-Axis CNC Machining Services/Materials/`

**Reference pages (already written — read before starting):**
- Best example: `Services/Custom CNC Machining Services/Metals/aluminium-cnc-machining-services.md` (294 lines, complete)
- Second example: `Services/Custom CNC Machining Services/Plastics/abs-cnc-machining-services.md` (282 lines, complete)

---

### Services — 3D Printing

| Page Type | Template File | Example Output File |
|---|---|---|
| 3D Printing hub | Written — see `Services/3D Printing Services/3d-printing-services.md` | (done) |
| 3D Printing technology page (SLA, SLS, MJF, FDM) | `Services/3D Printing Services/_3d-printing-technology-template.md` | `stereolithography-sla-3d-printing-services.md` |
| 3D Printing material sub-page | `Services/3D Printing Services/Materials/_3d-printing-material-template.md` | `pa12-nylon-sls-3d-printing.md` |

**Folder locations:**
- Technology pages: `Services/3D Printing Services/`
- Material sub-pages: `Services/3D Printing Services/Materials/`

**Technology page slugs to create:**
- `stereolithography-sla-3d-printing-services.md`
- `selective-laser-sintering-sls-3d-printing-services.md`
- `hp-multi-jet-fusion-mjf-3d-printing-services.md`
- `fdm-3d-printing-services.md`

---

### Services — Sheet Metal

| Page Type | Template File | Example Output File |
|---|---|---|
| Sheet Metal hub | `Services/Sheet Metal Services/_sheet-metal-hub-template.md` | `sheet-metal-fabrication-services.md` |
| Sheet Metal process page (Laser Cutting, Bending) | `Services/Sheet Metal Services/_sheet-metal-process-template.md` | `laser-cutting-services.md` |
| Sheet Metal material sub-page | `Services/Sheet Metal Services/Materials/_sheet-metal-material-template.md` | `aluminium-sheet-metal-fabrication.md` |

**Folder location:** `Services/Sheet Metal Services/`

**Process pages to create:**
- `laser-cutting-services.md`
- `metal-bending-services.md`

---

### Services — Formative Manufacturing

| Page Type | Template File | Example Output File |
|---|---|---|
| Vacuum Casting hub | `Services/Vacuum Casting Services/_vacuum-casting-template.md` | `vacuum-casting-services.md` |
| Vacuum Casting resin sub-page | `Services/Vacuum Casting Services/Materials/_vacuum-casting-resin-template.md` | `rigid-pu-vacuum-casting.md` |
| Injection Molding hub | `Services/Injection Molding Services/_injection-molding-template.md` | `injection-molding-services.md` |
| Injection Molding material sub-page | `Services/Injection Molding Services/Materials/_injection-molding-material-template.md` | `abs-injection-molding.md` |
| Injection Molding process sub-page | `Services/Injection Molding Services/Process/` (check folder) | `overmolding-services.md` |

**Folder locations:**
- Vacuum Casting: `Services/Vacuum Casting Services/`
- Injection Molding: `Services/Injection Molding Services/`

---

### Services — Wire EDM

| Page Type | Template File | Example Output File |
|---|---|---|
| Wire EDM hub | `Services/Wire-EDM Services/_wire-edm-template.md` | `wire-edm-services.md` |
| Wire EDM material sub-page | `Services/Wire-EDM Services/Materials/_wire-edm-material-template.md` | `tool-steel-wire-edm.md` |

**Folder location:** `Services/Wire-EDM Services/`

---

### Services — Surface Finishing

| Page Type | Template File | Example Output File |
|---|---|---|
| Surface Finishing process page (Anodizing, Powder Coating, etc.) | `Services/Surface Finishing Services/_surface-finishing-template.md` | `anodizing-services.md` |

**Folder location:** `Services/Surface Finishing Services/`

**Note:** Surface finishing hub already written: `Services/surface-finishing-services.md`

---

### Industries

| Page Type | Template File | Example Output File |
|---|---|---|
| Industry hub (v2 — multi-service) | `Industries/_industry-template-v2.md` | `aerospace-manufacturing.md` |

**Folder location:** `Industries/`

**Important:** Industry pages use v2 template — cross-service (CNC + 3D printing + sheet metal + injection molding + vacuum casting + wire EDM). Do NOT use old v1 CNC-only structure.

**Industry slugs to create (or rewrite to v2):**
- `aerospace-manufacturing.md`
- `medical-devices-manufacturing.md`
- `automotive-manufacturing.md`
- `electronics-manufacturing.md`
- `robotics-manufacturing.md`
- `consumer-products-manufacturing.md`
- `industrial-equipment-manufacturing.md`
- `defense-manufacturing.md`
- `energy-manufacturing.md`
- `marine-manufacturing.md`

---

### Alternatives Pages

| Page Type | Template File | Example Output File |
|---|---|---|
| Competitor alternative page | `_alternatives-page-template.md` | `protolabs-alternative.md` |

**Folder location:** Root (`/`) — same level as `sitemap.md`

**Alternatives pages to create:**
- `xometry-alternative.md` (file exists, currently empty — use template)
- `protolabs-alternative.md`
- `hubs-alternative.md`
- `rapiddirect-alternative.md`
- `fictiv-alternative.md`

⚠️ **RapidDirect warning:** They are a direct competitor. Focus on TOP PROTO differentiators — do not publish negative claims about their quality. Keep comparison factual and fair.

---

### Locations

| Page Type | Template File | Example Output File |
|---|---|---|
| Country page | `Locations/_location-country-template.md` | `cnc-machining-usa.md` |
| City page | `Locations/_location-city-template.md` | `cnc-machining-los-angeles.md` |

**Folder location:** `Locations/` (country pages may also live at root — check `sitemap.md`)

**Note:** `cnc-machining-usa.md` exists at root — check if it needs updating to v2 multi-service format.

---

### Blog Posts

| Page Type | Template File | Example Output File |
|---|---|---|
| Blog post (educational) | `Blogs/_blog-template.md` | `sla-vs-sls-3d-printing.md` |

**Folder location:** `Blogs/`

---

### Case Studies

| Page Type | Template File | Example Output File |
|---|---|---|
| Case study | `Case Studies/_case-study-template.md` | `aerospace-bracket-cnc.md` |

**Folder location:** `Case Studies/`

⚠️ **Blocked:** Case studies need real client project data. Do not write without verified project details.

---

### General Pages

| Page | File | Status |
|---|---|---|
| Home | `General Pages/home.md` | ✅ Written |
| About Us | `General Pages/about-us.md` | ✅ Written |
| Contact | `General Pages/contact.md` | ✅ Written |
| Get a Quote | `General Pages/get-a-quote.md` | ✅ Written |
| FAQ | `General Pages/faq.md` | ✅ Written |
| Quality Assurance | `General Pages/quality-assurance.md` | ✅ Written |

General pages do not have a shared template — each is unique. Reference the written pages for structure.

---

## Priority Writing Order

Write pages in this sequence. Do not skip levels — hub pages must exist before sub-pages.

### Tier 1 — Hubs (must exist before sub-pages)
1. `sheet-metal-fabrication-services.md` — Phase 3
2. `vacuum-casting-services.md` — Phase 3
3. `injection-molding-services.md` — Phase 3
4. `wire-edm-services.md` — Phase 3

### Tier 2 — High-Value Technology / Process Pages
5. `stereolithography-sla-3d-printing-services.md` — Phase 3
6. `hp-multi-jet-fusion-mjf-3d-printing-services.md` — Phase 3
7. `laser-cutting-services.md` — Phase 3
8. `metal-bending-services.md` — Phase 3

### Tier 3 — CNC Material Sub-Pages (high SEO value)
9. `stainless-steel-cnc-machining-services.md` — Phase 2
10. `titanium-cnc-machining-services.md` — Phase 2
11. `brass-cnc-machining-services.md` — Phase 2
12. All remaining CNC metal stubs (Phase 2)
13. All CNC plastic stubs (Phase 2)

### Tier 4 — Alternatives
14. `xometry-alternative.md` — Phase 7
15. `protolabs-alternative.md` — Phase 7
16. `hubs-alternative.md` — Phase 7
17. `rapiddirect-alternative.md` — Phase 7
18. `fictiv-alternative.md` — Phase 7

### Tier 5 — Industry Hubs
19. All industry pages — audit first (v1 or v2?) then rewrite to v2

### Tier 6 — Location Pages
20. Country pages, then city pages — Phase 8

---

## Reusable Sections Reference

When writing any page, check these blocks before writing from scratch:

| Block | ID | Where to Find |
|---|---|---|
| Quality Process (Pre/In/Final) | RS-01 | `reusablesections.md` |
| How It Works (6-step) | RS-02 | `reusablesections.md` |
| Final CTA + Contact Form | RS-03 | `reusablesections.md` |
| Testimonials | RS-04 | `reusablesections.md` |
| Prototyping vs Production | RS-05 | `reusablesections.md` |
| All Services Grid | RS-06 | `reusablesections.md` |
| Certifications & Trust Block | RS-07 | `reusablesections.md` |
| Industries Grid | RS-08 | `reusablesections.md` |
| Instant Quote CTA Bar (inline) | RS-09 | `reusablesections.md` |
| How Ordering Works (3-step) | RS-10 | `reusablesections.md` |
| Technology Comparison Table | RS-11 | `reusablesections.md` |

---

## Template Update Log

| Date | Change |
|---|---|
| 2026-06-08 | Created `_cnc-material-template.md` — for all CNC material sub-pages |
| 2026-06-08 | Created `_sheet-metal-hub-template.md` — hub page for sheet metal service |
| 2026-06-08 | Created `_alternatives-page-template.md` — for all competitor comparison pages |
| 2026-06-08 | Created this `TEMPLATE-INDEX.md` |
| 2026-06-08 | Written `3d-printing-services.md` — Phase 3 hub, 3D printing |
