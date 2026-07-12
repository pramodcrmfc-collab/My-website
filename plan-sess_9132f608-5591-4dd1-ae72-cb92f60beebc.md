# Portfolio Website Build Plan — Pramod Kumar

**Aesthetic:** Dark & Sleek (dark bg, violet→cyan gradients, soft glows, glassmorphism)
**Stack:** Static HTML/CSS/JS — no build step, opens directly in a browser, deploys to GitHub Pages/Netlify instantly
**Location:** `C:\Users\BIT-Pramod\ZCodeProject\`

---

## File Structure
```
ZCodeProject/
├── index.html          ← single-page site, all sections
├── css/
│   └── styles.css      ← full styling, dark theme, responsive
├── js/
│   └── main.js         ← scroll animations, nav, interactivity
└── assets/
    └── favicon.svg     ← custom "PK" monogram favicon
```
(Deliberately simple — everything self-contained, no dependencies.)

---

## Content Mapping (all pulled from resume)

### Hero
- Name: **Pramod Kumar**
- Kicker: `SOLUTION LEAD · E-INVOICING · AI GENERALIST`
- Headline tagline: *"Making the complex simple"* (from your About — your stated focus)
- Sub: 11+ years bridging complex business logic & scalable digital platforms
- CTAs: **View Work** (scroll to projects) + **Get in touch** (scroll to contact)
- Decorative: animated gradient glow orbs, glassmorphism, monogram

### About
- Full narrative from your LinkedIn summary (lightly polished, not fabricated)
- Key stat chips: `11+ yrs experience`, `9 countries`, `100+ gov services delivered`, `AI-driven delivery`

### Experience (timeline)
| Role | Company | Period |
|---|---|---|
| CRM Functional Consultant | Lenorasoft Technologies | Apr 2016 – Present (10+ yrs) |
| Business Manager | GOGREEN HOUSE | Jan 2015 – Feb 2016 |
| Sales Executive | Greentek India Pvt Ltd | Jan 2013 – Jan 2015 |
| Associate Engineer | vikat software solutions | Sep 2012 – Dec 2012 |
- Current role expanded with your Solution Lead responsibilities (E-Invoicing, multi-country compliance, AI integration)

### Projects / Case Studies (crafted from your narrative — the resume has no Projects section, so I'll build these 4 from the rich detail in your About)
1. **Global E-Invoicing Platform** — multi-country regulatory compliance (KSA/ZATCA, UAE/FTA, Malaysia, Oman, Cambodia, Singapore, Japan, Australia, NZ); gap-assessment → go-live for dozens of KSA clients. *Tech: E-Invoicing compliance, regulatory frameworks.*
2. **UAE Freezones Government Services Platform** — mapped 100+ distinct government services with customized SLAs on MS Dynamics. *Tech: MS Dynamics 365, Power Platform.*
3. **Travel Aggregator Booking Engine** — Amadeus/Sabre integration, real-time markups, deals & commission logic. *Tech: travel aggregators, booking engine architecture.*
4. **AI-Powered Delivery Workflows** — Claude for multi-country data dictionaries; Gemini + NotebookLM for documentation-backed client support; reduced turnaround times. *Tech: Claude, Gemini, NotebookLM, generative AI.*
- Each card: title, description, tags, role. Visual hover glow.

### Skills (expanded from your stated top skills + inferred from work)
- **Core:** E-Invoicing, Microsoft Dynamics 365 Sales, Microsoft Power Platform, CRM Consulting
- **Domain:** Solution Architecture, Regulatory Compliance (ZATCA/FTA), Business Analysis, Digital Transformation
- **AI & Tools:** Generative AI, Claude, Gemini, NotebookLM
- **Soft:** Stakeholder Management, Client Delivery, Cross-functional Leadership
- Rendered as gradient tag pills, grouped.

### Education
- Global Certificate in Data Science & AI — INSAID (2019)
- MBA, Marketing — Principal L N Welingkar Institute (2014–2016)
- B.Tech — Samskruti College of Engineering & Technology (2008–2012)

### Certifications
- Microsoft Certified: Power Platform Fundamentals
- Global Certificate in Data Science
- Certificate in Data Science Foundation
- Salesforce CRM

### Contact
- Email: pramod.nayakoti25@gmail.com (mailto link)
- LinkedIn: linkedin.com/in/pramodnayakoti
- Location: Greater Hyderabad Area
- Languages: Telugu (native), English (full professional), Hindi (professional working)

---

## Design System (Dark & Sleek)
- **Background:** deep near-black `#0a0a0f` with subtle layered radial gradients
- **Accent gradient:** violet `#7c3aed` → cyan `#06b6d4` (used on headings, borders, buttons, glow)
- **Glass cards:** semi-transparent panels with subtle border + backdrop blur (solid rgba fallback for older browsers)
- **Glow effects:** soft radial-gradient orbs behind hero & on hover; text-gradient on key words
- **Typography:** system sans stack (or Inter via Google Fonts) — large hero type, clear hierarchy
- **Motion:** fade-up-on-scroll via IntersectionObserver; smooth-scroll nav; sticky blurred header; active-section highlight; mobile hamburger menu
- **Responsive:** mobile-first breakpoints; grids collapse to single column; nav → hamburger < 768px
- **Polish:** custom scrollbar, focus-visible states for a11y, reduced-motion media query respected

---

## Build Steps
1. Create directory structure (`css/`, `js/`, `assets/`)
2. Write `index.html` — all semantic sections with real content from resume
3. Write `css/styles.css` — dark theme, glassmorphism, gradients, responsive grid, animations
4. Write `js/main.js` — IntersectionObserver scroll reveals, smooth scroll, mobile nav, active-link tracking, footer year
5. Create `assets/favicon.svg` — "PK" monogram with gradient
6. Verify: open in browser to check rendering (and run a quick HTML validation pass)

**Result:** A complete, polished, single-file-deploy portfolio reflecting all your resume details, ready to host anywhere. No data fabricated — everything traces back to your PDF; I'll only lightly polish prose for web reading and clearly derive the 4 projects from your stated work.