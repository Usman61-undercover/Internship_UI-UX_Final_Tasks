# Internship_UI-UX_Final_Tasks
# SocialConnect — UI/UX Design (Weeks 4–6)
Internship Final Submission | DevelopersHub Corporation  
Final Deadline: 28 April 2026

---

## Project Overview
SocialConnect is a mobile social media app designed across 6 weeks of UI/UX work — from wireframes to developer-ready handoff.

## Screens Delivered
| # | Screen      | Light | Dark |
|---|-------------|-------|------|
| 1 | Login       | ✓     | ✓    |
| 2 | Feed        | ✓     | ✓    |
| 3 | Profile     | ✓     | ✓    |
| 4 | Create Post | ✓     | ✓    |
| 5 | Settings    | ✓     | ✓    |

**Design tool:** Figma  
**Brand color:** #7F77DD (Purple)  
**Fonts:** SF Pro Display / SF Pro Text

---

## Week 4 — Usability Testing

**Tool:** Google Forms  
**Testers:** 3 participants (ages 18–30)  
**Task completion rate:** 100%  
**Average design rating:** 3.8 / 5  

### Key Pain Points & Fixes
| Issue | Severity | Resolution |
|-------|----------|------------|
| Bottom nav icon-only, no labels | High — 2/3 testers | Added text labels, stronger active state |
| Share button too subtle | Medium — 1/3 testers | Increased size and spacing |
| App theme with dummy data | Medium — 1/3 testers | Refined visual polish, real-looking content |
| Profile edit not obvious | Low | Pencil icon on avatar + edit button above fold |

---

## Week 5 — Advanced Design

### Logo (3 variants)
- `logo-purple-bg.png` — Primary app icon (purple background)
- `logo-gray-bg.png` — For light surfaces
- `logo-transparent.png` — For dark surfaces and overlays

**Concept:** Node-and-connection motif communicating social connectivity. Scalable from 16px favicon to 512px app icon.

### Color Palette
| Token | Hex | Usage |
|-------|-----|-------|
| Brand primary | #7F77DD | Buttons, active states |
| Brand light | #EEEDFE | Ghost buttons, hover |
| Brand dark | #534AB7 | Pressed states, headers |
| Text primary | #1A1A1A | Headings, body |
| Text secondary | #555555 | Captions, meta |
| Background | #F8F7F5 | Page background |
| Surface | #FFFFFF | Cards, modals |
| Dark surface | #1A1A2E | Dark mode page |
| Dark card | #16213E | Dark mode cards |

### Typography Scale
| Role | Size | Weight |
|------|------|--------|
| Page title | 24px | 700 |
| Section heading | 18px | 600 |
| Body text | 15px | 400 |
| Label / caption | 13px | 500 |
| Micro / badge | 11px | 500 |

### Microinteractions (Figma Smart Animate)
| Component | Animation | Duration |
|-----------|-----------|----------|
| Primary button | Scale 1→0.97→1, color deepen | 120ms ease |
| Follow button | Text switches, fill toggles | 200ms |
| Like / heart | Scale pop 1→1.3→1, turns red | 150ms spring |
| FAB button | Rotates 45°, sub-actions appear | 220ms ease-out |
| Bottom nav tab | Icon lifts 2px, label fades in | 160ms ease |
| Screen transitions | Horizontal slide (iOS) | 300ms ease-in-out |
| Feed loading | Skeleton shimmer | Loop 1.2s |

### Empty States
- **No posts yet** — Camera icon, "Nothing here yet", CTA: Create Post
- **No followers yet** — Silhouettes icon, "No followers yet", CTA: Share Profile
- **All caught up** — Bell icon, "All caught up", no CTA

### Accessibility — WCAG 2.1 AA
- Body text contrast: 18.1:1 ✓
- Brand purple on white: 4.5:1 ✓
- All touch targets: 48px minimum ✓
- Dark mode: all 5 screens ✓
- Minimum font size: 13px ✓
- Form labels above inputs ✓
- Error states use icon + color, not color alone ✓

---

## Week 6 — Developer Handoff

### Frame Specifications
| Element | Value |
|---------|-------|
| Base frame | 390 × 844px (iPhone 14) |
| Horizontal margin | 24px |
| Card padding | 16px |
| Top bar height | 56px |
| Bottom nav height | 83px (incl. 34px safe area) |
| Feed avatar | 40px circle |
| Profile avatar | 88px circle |
| FAB button | 56px circle |
| Primary button height | 52px |
| Input field height | 52px |

### Border Radius Scale
| Token | Value | Usage |
|-------|-------|-------|
| sm | 8px | Tags, badges |
| md | 12px | Inputs, inner cards |
| lg | 16px | Main cards, modals |
| pill | 100px | Buttons, chips |
| circle | 50% | Avatars, FAB |

### Layer Naming Convention
```
Pattern: Screen/Component/Variant

Examples:
  Feed/PostCard/Default
  Feed/PostCard/WithImage
  Feed/PostCard/Dark
  Global/BottomNav/Light
  Global/BottomNav/Dark
  Auth/InputField/Empty
  Auth/InputField/Filled
  Auth/InputField/Error
  Settings/ToggleRow/On
  Settings/ToggleRow/Off
```


## 🚀 Final Deliverables
1.  **Interactive Figma Prototype:** https://www.figma.com/design/loslJWaseSD0lLASCeqGsr/social-connect-app?node-id=23-538&p=f&t=PcRcx9wOTBlZY2nj-0
2.  **Figma Design File:** https://www.figma.com/design/loslJWaseSD0lLASCeqGsr/social-connect-app?node-id=23-538&p=f&t=PcRcx9wOTBlZY2nj-0
3.  **Video Walkthrough:**
4.  **Usability Report:** https://docs.google.com/forms/d/109cOaRcqltcn8T-S2yx0S9V9YsyiBR9Y44E3kuH4Cd0/edit?usp=forms_home&ouid=107080289095429478817&ths=true

**Project Status:** Completed & Handoff Ready
**Submission Date:** April 28, 2026
