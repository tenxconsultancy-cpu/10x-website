# Findings Log — B.L.A.S.T. Project

## Status: 🟢 Brand Analysis Complete

---

## Project Brief (from User)
| Field | Value |
|---|---|
| **Role** | Lead UI/UX & Motion Designer |
| **Project** | High-end scrollytelling website |
| **Client** | 10X — AI Consultancy |
| **Focus** | ROI-driven Auditing, Automations & AI Solutions |

| Question | Answer |
|---|---|
| North Star (singular desired outcome) | TBD |
| Integrations (external services + keys) | TBD |
| Source of Truth (where data lives) | TBD |
| Delivery Payload (how/where to deliver) | TBD |
| Behavioral Rules | Efficient, Visionary, Precise, Trusted. Dark high-tech aesthetic. |

---

## 🎨 Brand Analysis

### Logo Anatomy
- **"10"** — Rendered in thin geometric outline strokes (not filled). Heavy geometric sans-serif letterforms, stroke-only treatment.
- **"X"** — Replaced entirely by a 3D glossy blue arrow pointing at ~45° upper-right. The arrow acts as the X's dominant diagonal stroke.
- **Overall feel**: Minimalist outline text + bold 3D accent element. Contrast between restraint (outline) and energy (arrow).

### Typography Analysis
| Role | Style | Closest Match |
|---|---|---|
| Logo numerals "10" | Geometric sans-serif, thin/outline weight | **Montserrat ExtraBold** (outlined) or **Barlow** |
| Headlines ("OPTIMIZATION", "EXPONENTIAL AI AUTOMATION") | Ultra-bold, condensed, all-caps | **Barlow Condensed ExtraBold** or **Bebas Neue** |
| Body / Subheadings | Clean regular-weight sans-serif | **Inter** or **Roboto** |
| ⚠️ Action needed | Confirm exact font family — recommend Google Fonts for web | — |

### Color Palette
| Role | Hex | Notes |
|---|---|---|
| Primary Blue | `#007AFF` | Electric/Sky blue — CTAs, arrows, highlights |
| Deep Navy | `#0D1B2A` | Approx. (branding kit label partially obscured) — dark brand color |
| Background | `#080C12` | Near-black with cool undertone (from theme reference) |
| Neutral Gray | Neutral Gray 1 | Light gray — secondary text |
| Dark Charcoal | `#4F4F44` | Approx. (label in kit may have compression artifact) |
| ⚠️ Action needed | Confirm exact hex for navy + charcoal swatches | — |

### Background Theme
- Near-black background (`#080C12` approx.)
- Geometric glowing blue line art: chevrons/arrow shapes rendered as thin neon-blue hairlines
- Lines glow with soft bloom/halo effect — high-tech, directional energy
- Compositional placement: lines emanate from lower-left and upper-right corners, converging toward center

### Brand Voice
| Pillar | Descriptor |
|---|---|
| EFFICIENT | Trusted Industry & Precise |
| VISIONARY | Innovating the Future |

### Sections Map (confirmed by user)
1. **Splash Screen** — Logo animation (arrow pulses ×2, then shoots up → site reveals) [✅ COMPLETE]
2. **Top Nav** — Logo + nav links
3. **Hero Section**
   - **Core Message:** "Your specialized partner helping you get the most out of AI and automations to achieve business growth and ensure the highest return on investment possible. We cut through the daily AI hype and tons of tools to identify the best ai and automation solutions for your business"
   - **Tone goal:** Catchy, professional, trustworthy.
4. **What We Offer**
5. **Who We Are**
6. **Why AI & Automations — Why Now**
7. **How It Happens**
8. **Contact Us** (form → email + Google Calendar booking)

### Key Functionality
- Contact form → sends email notification
- Contact form → books meeting in Google Calendar

---

## Architecture Decisions
| Decision | Rationale | Date |
|---|---|---|
| Pure HTML/CSS/JS (no framework) | Maximum control for custom animations; no build step needed | 2026-02-23 |
| GSAP for animations | Industry standard for scroll-triggered + timeline animations | 2026-02-23 |
| Build section by section | User directive — iterative delivery | 2026-02-23 |
