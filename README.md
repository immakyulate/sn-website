# SN International Group — Front-End Redesign

**Live site:** https://sn-website-sand.vercel.app/

A four-page front-end redesign of [sngroup.com.au](https://www.sngroup.com.au/) for the SN International Group internship assessment. Built mobile-first with HTML + Tailwind CSS, deployed on Vercel.

---

## What's included

| Deliverable | Where |
|---|---|
| Live working front-end | https://sn-website-sand.vercel.app/ |
| Source code | This repository |
| Design rationale (8-page document) | `SN_Group_Redesign_Explanation.docx` |

## Pages

| Page | File | What it covers |
|---|---|---|
| Home | `index.html` | Hero, services bento, process, stats, testimonial, contact form |
| Services | `services.html` | Deep-dives on the four service tracks, engagement models, FAQ |
| About Us | `about.html` | Story, values, hiring process, stats |
| Meet the Team | `team.html` | 17-person team with executive poster cards and 6 staff cards |

## Design highlights

- **Brand-anchored palette** — built around SN's actual brand colour `#19414D` with a fun blue/cyan/amber/coral accent system that keeps the page lively while feeling native to the brand.
- **ClickUp-inspired visuals** — bold gradients, asymmetric bento layouts, big punchy typography, Caveat-script accent words for personality.
- **Real team, real photos** — all 8 team members shown with their actual portraits. Steven and May have personalised "doodle poster" cards built from their real fun facts.
- **Conversion-driven** — persistent gradient CTA in the nav, four service quick-chips in the hero, structured contact form with role + hours + workflow pre-qualification, and "Request this service" deep-links from every service card.
- **Fully responsive** — mobile-first with sensible breakpoints; layout adapts cleanly from 360 px phones up to 1440 px desktops.
- **Accessible** — semantic HTML, aria labels, WCAG-AA contrast, visible focus states, `prefers-reduced-motion` respected.

## Tech

- HTML + Tailwind CSS (CDN)
- Vanilla JavaScript (mobile menu, intersection-observer reveals, form handler)
- Google Fonts: Plus Jakarta Sans + Inter + Caveat
- Lucide icons + inline SVG for the LinkedIn brand mark
- Hosted on Vercel with auto-redeploy on every push

## Notes

- The contact form is front-end only — submissions confirm inline but aren't wired to a backend. Easy fix later via Formspree, Netlify Forms, or a Vercel serverless function.
- A few footer values (phone number, ABN) are placeholders.
- See `SN_Group_Redesign_Explanation.docx` for the full design rationale, current-site analysis, and improvement breakdown.
