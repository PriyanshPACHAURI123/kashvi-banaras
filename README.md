# Kashvi Banaras — Luxury Fashion E-Commerce Website

> *Handwoven Stories from the Heart of Banaras*

A premium, modern luxury e-commerce website for **Kashvi Banaras** — a heritage Banarasi fashion brand representing timeless elegance, handcrafted artistry, and modern luxury.

## Brand Identity
- **Heritage:** 137 years of Banarasi weaving tradition
- **Audience:** Affluent women, brides, NRIs, luxury ethnic wear buyers
- **Values:** Authenticity · Heritage · Craftsmanship · Exclusivity · Luxury · Sustainability

## Tech Stack
- HTML5 / CSS3 / Vanilla JS (production-ready, framework-agnostic)
- Google Fonts: Cormorant Garamond · IM Fell English · Jost
- Ready to migrate to **Next.js 15 + Tailwind CSS + Framer Motion**

## Design System

### Color Palette
| Token | Hex | Usage |
|-------|-----|-------|
| Deep Maroon | `#5A0F1C` | Primary brand color |
| Antique Gold | `#C8A96B` | Accents, borders, CTAs |
| Ivory | `#F8F3EB` | Background, light surfaces |
| Charcoal Black | `#1B1B1B` | Text, dark sections |

### Typography
- **Display:** Cormorant Garamond (300, 400, 500, 600)
- **Editorial:** IM Fell English (italic pullquotes)
- **Body/UI:** Jost (300, 400, 500)

## Pages & Sections
- [x] Announcement Bar
- [x] Sticky Navigation (transparent → frosted glass)
- [x] Cinematic Hero with animated motifs
- [x] Marquee brand strip
- [x] Heritage / About section
- [x] Featured Collections grid
- [x] Product Cards with hover interactions
- [x] Craftsmanship Timeline (scroll-driven)
- [x] Testimonials
- [x] Journal / Editorial Blog
- [x] Footer with newsletter

## Features
- Wishlist toggle on product cards
- WhatsApp inquiry integration
- Scroll-triggered entrance animations
- IntersectionObserver-based timeline
- Mobile-first responsive design
- SEO-optimized semantic HTML

## Getting Started

```bash
# Simply open in browser
open index.html

# Or serve locally
npx serve .
```

## Next.js Migration
Each section maps to a React component:
- `<HeroSection />` · `<CollectionsGrid />` · `<ProductCard />`
- `<CraftsmanshipTimeline />` · `<TestimonialsSection />` · `<JournalGrid />`

CSS variables translate directly into `tailwind.config.js` `extend` block.

---

**Created by:** Priyansh (pachauripriyansh2@gmail.com)  
**Brand:** Kashvi Banaras  
**License:** Private & Confidential
