# Week 4 — Usability Testing Report
SocialConnect | DevelopersHub Corporation Internship

---

## Testing Plan

**Tool:** Google Forms  
**Sample size:** 3 testers  
**Target audience:** Ages 18–30, smartphone users, any social media usage frequency  
**Prototype shared:** Figma interactive prototype link

### Testing Scenarios
| # | Scenario | Task | Success metric |
|---|----------|------|----------------|
| 1 | Create a post | Add text and image, tap Post | Completed + ease ≥ 4/5 |
| 2 | Browse home feed | Find and scroll the feed | Found immediately + ease ≥ 4/5 |
| 3 | Update profile | Locate and edit profile info | Located + ease ≥ 4/5 |

---

## Tester Responses

### Tester 1
- **Age:** 25–30 | **Usage:** Multiple times a day
- **Post creation:** Yes, easily — 5/5
- **Feed navigation:** Yes, immediately — 3/5
- **Profile update:** Yes, easily — 5/5
- **Overall rating:** 3/5
- **Most confusing screen:** Navigation / Bottom Bar
- **Liked most:** Nothing specific mentioned
- **Would improve:** Nothing mentioned
- **Would use:** Yes, definitely

### Tester 2
- **Age:** 18–24 | **Usage:** A few times a week
- **Post creation:** Yes, but with some difficulty — 2/5
- **Feed navigation:** Yes, immediately — 4/5 | Unclear: share button on post
- **Profile update:** Yes, easily — 5/5
- **Overall rating:** 4/5
- **Most confusing screen:** No one specific
- **Liked most:** Typography
- **Would improve:** App theme (possibly because of dummy data)
- **Would use:** Yes, definitely

### Tester 3
- **Age:** 18–24 | **Usage:** Multiple times a day
- **Post creation:** Yes, easily — 4/5
- **Feed navigation:** Yes, after looking around — 3/5
- **Profile update:** Yes, easily — 3/5 | Everything is working fine
- **Overall rating:** 3/5
- **Most confusing screen:** Navigation / Bottom Bar
- **Liked most:** Login screen (easy)
- **Would improve:** Navigation bar
- **Would use:** Maybe

---

## Aggregated Scores

| Task | T1 | T2 | T3 | Average |
|------|----|----|-----|---------|
| Create post ease | 5 | 2 | 4 | 3.7 |
| Feed navigation ease | 3 | 4 | 3 | 3.3 |
| Profile update ease | 5 | 5 | 3 | 4.3 |
| Overall design rating | 3 | 4 | 3 | 3.3 |

**Task completion rate:** 100% (all 3 testers completed all 3 tasks)  
**Would use app:** 3/3 positive (2 yes, 1 maybe)

---

## Key Pain Points

### 1. Bottom Navigation Bar — HIGH PRIORITY
- **Flagged by:** 2/3 testers (T1, T3)
- **Issue:** Icon-only inactive tabs gave no context; active state not prominent enough
- **Impact:** Tester 3 could not immediately find the home feed
- **Resolution:** Added text labels below all icons; stronger purple active state

### 2. Share Button on Post Card — MEDIUM PRIORITY
- **Flagged by:** 1/3 testers (T2)
- **Issue:** Icon too visually subtle in the post engagement row
- **Resolution:** Increased icon size, added spacing, clearer tap target boundary

### 3. App Theme / Placeholder Content — MEDIUM PRIORITY
- **Flagged by:** 1/3 testers (T2)
- **Issue:** Dummy data made the design look incomplete
- **Resolution:** Used realistic placeholder content in updated screens

### 4. Profile Edit Discoverability — LOW PRIORITY
- **Signal:** Average profile ease 4.3/5 (lowest completion confidence)
- **Issue:** Edit CTA not obvious above fold for all users
- **Resolution:** Pencil icon overlay on avatar + visible "Edit Profile" button

---

## Design Iterations Implemented

| Issue | Before | After |
|-------|--------|-------|
| Bottom nav | Icons only | Icons + text labels, purple active state |
| Share button | Small, low contrast | Larger, increased spacing |
| Logo | Single orange variant | 3 variants: purple bg, gray bg, transparent |
| Theme | Light mode only | Full dark mode across all 5 screens |
| Profile edit | No obvious CTA | Pencil icon + Edit Profile button |
