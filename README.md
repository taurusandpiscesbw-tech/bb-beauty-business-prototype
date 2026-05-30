# BB Beauty Business — Phase 1 Prototype

> UI/UX design screens for the BB Beauty Business app — built for ACPF-certified beauty professionals in Malaysia.

---

## About

BB Beauty Business is a booking and broadcast platform for Malaysian beauty professionals. It replaces WhatsApp broadcast groups with a structured, bookable feed, and handles end-to-end appointment management with smart slot scheduling.

This repository contains the Phase 1 design prototype screens, built as static HTML mockups ready for developer handoff.

---

## Screen Index

| File | Description | Theme | Language |
|---|---|---|---|
| `bb-screens.html` | Registration Steps 4–6 + Merchant Public Profile | Night + Day | EN |
| `bb-booking.html` | Revised Steps 3 & 4 + 3-Step Booking Flow | Night + Day | EN |
| `bb-booking-zh.html` | Revised Steps 3 & 4 + 3-Step Booking Flow | Night + Day | 中文 |
| `bb-broadcast.html` | Broadcast Feed — Hub, Compose, Client Feed, Open Slot | Night + Day | EN |
| `bb-broadcast-zh.html` | Broadcast Feed | Night + Day | 中文 |
| `bb-broadcast-photos.html` | Broadcast Feed with Photo Upload | Night + Day | EN |
| `bb-broadcast-photos-zh.html` | Broadcast Feed with Photo Upload | Night + Day | 中文 |

---

## Design System

**Themes**
- **Night** (Pro/Merchant side) — `#0a0a0a` background, Tiffany `#0ABFB8` accent
- **Daylight** (Client side) — `#E0F7F5` background, Navy `#003B36` primary

**Core Palette**
| Token | Hex | Usage |
|---|---|---|
| Signature Tiffany | `#0ABFB8` | Primary accent, active states, CTAs |
| Robin Egg | `#81D8D0` | Day header, logo day icon |
| Pale Tiffany | `#E0F7F5` | Day screen background |
| Tiffany Dark | `#003B36` | Primary text day, nav bg night |
| Very Dark Navy | `#002B26` | Text on Tiffany buttons |
| Rose Gold | `#E8A89A` | Followers, stars, loyalty, hearts |

**Typography**
- Display / Logo: `Playfair Display` 700–800
- UI Body: `Manrope` 400–800
- Chinese: `Noto Sans SC` 400–700

**Language Bar** — EN · 中文 · BM · VI (below status bar, full width)

---

## Key Features Designed (Phase 1)

### Professional Onboarding (6 Steps)
- Basic info, profile photo, service menu with per-service buffers & deposits
- Availability — weekly hours + date overrides
- Portfolio gallery (min 3 before/after photos, +40% booking uplift banner)
- Bank account (Maybank/CIMB/etc via Billplz + Stripe Connect, 93% payout)
- New client offer (% off / RM off / free add-on)

### Smart Booking Engine
- Rules-based slot generation (not pre-placed grids)
- Per-service duration + cleanup buffer
- No-orphan-gap rule — hides times that strand unfillable gaps
- Adjacency-biased "Recommended" time ordering
- Booking rules: increment, min notice, booking window, capacity

### Broadcast Feed (WhatsApp Replacement)
- **⚡ Open Slot** — last-minute availability with result photo, urgency tag, direct Book CTA
- **✨ Spotlight** — multi-photo carousel (up to 6), before/after/healed story, wishlist save
- **📣 Broadcast** — flexible announcements, offers, closures
- Heart reaction + Book CTA (no comments — reduces friction, keeps feed clean)
- Per-post reach + conversion stats (merchant view)

### Client Experience
- Merchant public profile — ACPF Gold badge, BB Score, follower count, Follow button
- 3-step booking flow — service → recommended time → confirm + deposit payment
- Following feed — bookable cards from all followed artists
- FPX + card payment via Billplz / Stripe Connect

---

## Certification

Designed for **ACPF (Association of Certified Professional Aestheticians)** certified merchants. ACPF Gold badge auto-verified on merchant profiles.

---

## Status

| Section | EN | 中文 |
|---|---|---|
| Registration Steps 4–6 + Profile | ✅ | — |
| Booking Flow (Steps 3 & 4 + 3-step) | ✅ | ✅ |
| Broadcast Feed | ✅ | ✅ |
| Broadcast + Photos | ✅ | ✅ |
| Earnings Wallet | 🔜 | 🔜 |
| Client Home | 🔜 | 🔜 |
| Booking Management (Pro) | 🔜 | 🔜 |

---

*Prototype built in collaboration with Claude (Anthropic) · BB Beauty Business Phase 1 · 2026*
