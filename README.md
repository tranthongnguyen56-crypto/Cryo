# Cyro

> **A promise that doesn't expire.**

Cyro is a digital time capsule app that lets you lock messages, photos, and predictions until an exact future date you choose. Nothing can be opened early — not by the user, not by us. On the day you chose, it unlocks.

Built by **Bread Studios**, founded by Gleb and Manthan.

---

## What it does

| Step | Action |
|------|--------|
| ✍️ **Write** | A message, photo, or prediction — anything that matters now |
| 🔒 **Seal** | Choose the exact unlock date and recipient. Once sealed, it's immutable |
| ✨ **Reveal** | On the chosen date, the capsule unlocks and delivers itself |

---

## Brand

| Property | Value |
|----------|-------|
| **Name** | Cyro |
| **Tagline** | *A promise that doesn't expire.* |
| **Mascot** | Cy — a calm, frost-blue capsule creature who holds every sealed message |
| **Brand words** | Reliable · Trusted · Endless |

### Color palette

| Role | Light | Dark |
|------|-------|------|
| Background | `#F4F8FB` | `#0B1620` |
| Surface | `#FFFFFF` | `#121F2C` |
| Primary text | `#101D2B` | `#EAF3F8` |
| Secondary text | `#5B6F80` | `#8AA1B0` |
| Accent | `#2F6A8F` | `#7FC4E6` |
| Accent light | `#8FC3DD` | `#A9DAF0` |
| Border | `#DDE8EF` | `#1E2C3A` |

### Typography

| Role | Font |
|------|------|
| Headline | Fraunces (Google Fonts) — warm, considered serif |
| Body / UI | Inter (Google Fonts) — clean, neutral sans |

---

## Repository contents

```
/
├── cyro-website.html          # Full marketing landing page
├── cyro-prototype-v2.html     # Interactive app prototype (all screens wired)
├── cyro-app-home.html         # App home screen mockup
├── cyro-onboarding-flow.html  # Onboarding flow mockups (5 screens)
├── cyro-flow-mockups.html     # Create & seal flow mockups (5 screens)
├── cyro-brand-reference.html  # Brand reference sheet (logo, palette, type)
├── cyro-app-icon.png          # Square app icon (1024×1024)
└── README.md                  # This file
```

---

## Prototype screens

The interactive prototype (`cyro-prototype-v2.html`) covers the full user flow:

**Onboarding**
1. Welcome splash
2. How Cyro works
3. Sign up
4. Meet Cy
5. First capsule prompt

**Create & seal flow**
1. Write (message / photo / prediction tabs)
2. Choose recipient (yourself or someone else)
3. Pick unlock date (calendar + year input + quick picks)
4. Review before sealing
5. Sealing animation
6. Sealed confirmation with countdown

**Main app**
- Home screen with capsule shelf and urgency hierarchy
- Capsules list with reveal banner
- Reveal screen (the unlock moment — dark, atmospheric)
- Alerts
- Profile

---

## Key design decisions

**Urgency hierarchy on capsule cards** — capsules opening soon are visually distinct (gold chip, warm background) from long-horizon ones (18 years). A user should never have to read dates to know what's urgent.

**Reveal screen on dark background** — the unlock moment is the emotional heart of the product. It gets its own visual register: dark, glowing, cinematic.

**Recipient flow built in** — the create flow includes a dedicated screen to choose between "just me" and "someone else," with email input appearing contextually.

**Backup note on sealed confirmation** — directly addresses the trust question the 18-year parent persona will silently ask: *will this still exist?*

**Year input with +/− controls** — for long-horizon capsules (child at 18, retirement) scrolling a calendar is not viable. The year control solves this without a modal.

---

## Target personas

| Persona | Use case | Retention hook |
|---------|----------|----------------|
| **New parent** | Message for child at 18 | 18-year emotional investment |
| **Friend group** | Predictions before going separate ways | Group unlock — everyone returns |
| **Founder / maker** | Goals at start of year | New Year occasion trigger |
| **Long-distance / deployed** | Timed messages during separation | Paced delivery during a hard stretch |
| **TechTutor student** | Letter to future self at course end | Built-in curriculum moment |

---

## Brand rules (quick reference)

**DO**
- Use Fraunces only for the wordmark and section headings
- Let frost blue fill buttons and icons only — never large background areas
- Keep every button verb-first: *Seal*, *Open*, *Start* — never *Submit*
- Confirm every seal instantly — never leave the user wondering if it worked
- Make the unlock moment feel earned — a pause, then reveal

**DON'T**
- Use pure black (`#000`) for text — always the deep ink navy
- Use urgency language anywhere — no *hurry*, *limited*, or *don't miss out*
- Notify someone more than once about the same unsealed capsule
- Let the mascot's expression change — same calm face, always

---

## Company

Cyro is a product of **Bread Studios**, a digital studio focused on educational and productivity platforms, founded by Gleb and Manthan.

---

*README last updated: August 2026*
