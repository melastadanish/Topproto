# Design Reference

## Brand
- Business: CNC Machining focused
- Reference sites: rapiddirect.com, hubs.com, elimold.com
- Old site: topprotomachining.com

---

## Design Decisions
- Background alternates: White → Light Grey → White → Dark (for RS-01) → White
- No gradients. Clean, technical aesthetic.
- Typography: Bold for headings, regular for body. No decorative fonts.
- Accent colour: to be confirmed (reference: RapidDirect uses orange-red)
- Cards: white card on light grey background. Subtle shadow. No heavy borders.

---

## Component Library

### Service Card
*(Used on Home Section 2, Service overview pages, Service main pages)*
- Top: real part photo (not icon)
- Bold service name
- Subtitle: what's included (1 line)
- 2 bullet points: tolerance spec + lead time
- Bottom: "See our [service name] →" text link (accent colour)
- Background: white card on light grey page background
- Reference: Hubs.com

### Material Pill / Chip
*(Used on Service pages — Materials sections)*
- Inline pill/chip button with material name
- Links to material sub-page
- Wraps on mobile, horizontal scroll on desktop
- Accent colour border or background tint on hover

### Finish Card
*(Used on Service pages — Surface Finishes section)*
- Finish name (bold)
- 1-line description
- Compatible materials tag (small, grey)
- Links to finish sub-page
- 4-column grid desktop / 2-column mobile

### Industry Icon Card
*(Used on Service pages + Home Section 6)*
- Icon (line style) + industry name + 1-line descriptor
- 5-column grid desktop / 2-column mobile
- Links to industry silo page

### Stats Bar
*(Used on Service pages Section 2)*
- 4 numbers in a row
- Bold large number + label below
- Light grey background, full width
- No icons — numbers only

---

## Page Templates

### Service Page (Main) — 16 Sections
Applied to: custom-cnc-machining-services, cnc-milling-services, cnc-turning-services, 5-axis-cnc-machining-services, cnc-turn-mill-services, surface-finishing-services

| # | Section | Layout | Background |
|---|---|---|---|
| 1 | Hero | 50/50 split — text left, image right | White |
| 2 | Why TOP PROTO (Stats Bar) | 4-number row | Light grey |
| 3 | What is [Service] | 2-column — text left, image right | White |
| 4 | Our Services (sub-service cards) | 2×3 card grid | Light grey |
| 5 | Capabilities & Tolerances Table | Full-width table | White |
| 6 | Materials — Metals | Pill/chip row | Light grey |
| 7 | Materials — Plastics | Pill/chip row | White |
| 8 | Surface Finishes | 4-column card grid | Light grey |
| 9 | Design Guidelines | 2-column — DFM rules left, table right | White |
| 10 | Industries Served | 5-column icon grid | White |
| 11 | Quality & Certifications | RS-01 3-column | Dark (navy/charcoal) |
| 12 | Gallery | Masonry grid 6–8 images | Light grey |
| 13 | Why Choose TOP PROTO | 2-column — 6 points left, image right | White |
| 14 | FAQ | Accordion, first item open | White |
| 15 | Blog / Resources | 3-card grid | Light grey |
| 16 | Final CTA + Form | RS-03 2-column split | White or accent |

**Hero detail:**
- Label tag above H1: `[SERVICE NAME]` in small caps
- H1: pure target keyword
- Subheading: 2 lines max, technical detail
- 3 trust badges inline: ISO 9001:2015 | ±0.005mm | Quote in 24 Hours
- CTA Primary: Get an Instant Quote | CTA Secondary: View Our Capabilities
- Right: hero image — real machined part or machining in action

---

## Reusable Sections

### RS-01: Quality Process
3-column: Pre-Production | In-Production | Final-Production
Dark background (navy/charcoal). White text.
Used on: Home, Quality Assurance, all Service pages.
Always followed by link: → View our full Quality Assurance process

### RS-02: How It Works
6-step horizontal timeline with dot connectors.
Light blue or light grey background.
Used on: Home, Get a Quote page.

### RS-03: Final CTA + Contact Form
2-column split — left: label + heading + subtext + bullets + CTA button. Right: contact form.
Form fields: Name | Email | Company | Service (dropdown) | Message | reCAPTCHA | Submit
Used on: All pages as final section.

### RS-04: Testimonials
3-card grid. 5-star rating + quote + name + job title.
White cards on light grey background.
Used on: Home, About Us, service pages where relevant.

### RS-05: Prototyping vs Production
2-column cards — left white, right accent background.
Each: title + 3 bullets + CTA button.
Used on: Home, Custom CNC Machining Services.

---

## CTA Strategy

| Page type | Primary CTA | Secondary CTA |
|---|---|---|
| Home | Get an Instant Quote | Explore Our Services |
| Service pages | Get an Instant Quote | View Our Capabilities |
| Industry pages | Get a Quote for [Industry] Parts | View Our Services |
| Material pages | Get a Quote | View All Materials |
| Location pages | Get a Quote | Learn More |
| Case studies | Have a Similar Part? Get a Quote | — |
| Knowledge Base | Get a Quote | — |
| Alternatives | Get a Free Quote | — |
