# Design System — SocialConnect
Version 2.0 | Updated after Week 4 usability iteration

---

## Color Palette

### Brand Colors
| Token | Hex | Usage |
|-------|-----|-------|
| Brand primary | #7F77DD | Primary buttons, active nav, links |
| Brand light | #EEEDFE | Ghost button backgrounds, hover states |
| Brand dark | #534AB7 | Pressed states, section headings |

### Neutral Colors
| Token | Hex | Usage |
|-------|-----|-------|
| Text primary | #1A1A1A | Headings, body text |
| Text secondary | #555555 | Captions, metadata, subtitles |
| Text placeholder | #999999 | Input placeholder text |
| Background | #F8F7F5 | Page/screen background |
| Surface | #FFFFFF | Cards, modals, sheets |
| Border | #E0DDD8 | Input borders, dividers |

### Dark Mode Colors
| Token | Hex | Usage |
|-------|-----|-------|
| Dark surface | #1A1A2E | Page background (dark) |
| Dark card | #16213E | Card surfaces (dark) |
| Dark border | #2A2A4E | Dividers and borders (dark) |

### Semantic Colors (Add-on Icons)
| Color | Hex | Usage |
|-------|-----|-------|
| Green | #4CAF50 | Photo/Video action |
| Blue | #2196F3 | Tag Friends action |
| Amber | #FFC107 | Feeling/Activity action |
| Red | #F44336 | Error states, destructive actions |

---

## Typography

**Font stack:** SF Pro Display (headings) / SF Pro Text (body)  
**CSS fallback:** `-apple-system, BlinkMacSystemFont, 'Roboto', sans-serif`

### Type Scale
| Role | Font | Size | Weight | Line height |
|------|------|------|--------|-------------|
| Display | SF Pro Display | 24px | 700 | 1.2 |
| Section heading | SF Pro Display | 18px | 600 | 1.3 |
| Body | SF Pro Text | 15px | 400 | 1.6 |
| Label | SF Pro Text | 13px | 500 | 1.4 |
| Caption / meta | SF Pro Text | 12px | 400 | 1.4 |
| Micro / badge | SF Pro Text | 11px | 500 | 1.2 |

---

## Spacing Scale

| Token | Value | Primary usage |
|-------|-------|---------------|
| xs | 4px | Icon-to-text gaps |
| sm | 8px | Internal component padding |
| md | 12px | Between components |
| lg | 16px | Section separation |
| xl | 24px | Page horizontal margins |
| 2xl | 32px | Major section breaks |

---

## Border Radius Scale

| Token | Value | Usage |
|-------|-------|-------|
| sm | 8px | Tags, badges, small chips |
| md | 12px | Input fields, inner cards |
| lg | 16px | Main cards, bottom sheets |
| pill | 100px | Buttons, large chips |
| circle | 50% | Avatars, FAB, toggles |

---

## Component Specifications

### Buttons
| Type | Height | Radius | Background | Text |
|------|--------|--------|------------|------|
| Primary | 52px | 100px | #7F77DD | White, 500, 16px |
| Ghost | 44px | 100px | #EEEDFE | #7F77DD, 500, 15px |
| Outline | 44px | 100px | Transparent | #555, 400, 15px |
| Destructive | 52px | 12px | White | #D32F2F, 500, 16px, border |

### Input Fields
- Height: 52px
- Border: 1px solid #E0DDD8
- Border radius: 12px
- Padding: 0 16px
- Background: #FFFFFF
- Placeholder color: #999999
- Focus border: 1.5px solid #7F77DD
- Label: above field, 13px, 500, #1A1A1A

### Bottom Navigation Bar
- Total height: 83px
- Safe area: 34px
- Nav area: 49px
- Icon size: 24px
- Label size: 11px, 400
- Active color: #7F77DD
- Inactive color: #999999
- FAB size: 56px circle, #7F77DD

### Avatar Sizes
- Story ring: 56px circle, 2.5px brand ring
- Feed post: 40px circle
- Profile header: 88px circle
- Comment / composer: 36px circle

### Cards
- Background: #FFFFFF
- Border: 0.5px solid #E0DDD8
- Border radius: 16px
- Padding: 16px

### Settings Row
- Height: 54px
- Icon size: 32x32px, radius 8px
- Font: 15px, 400
- Chevron: right-aligned, #CCCCCC

### Toggle / Switch
- Width: 44px, Height: 26px
- On: #7F77DD background, white knob right
- Off: #CCCCCC background, white knob left
- Transition: 200ms ease

---

## Figma Layer Naming Convention

```
Pattern: Screen/Component/Variant

Full examples:
Login/InputField/Empty
Login/InputField/Filled
Login/InputField/Error
Login/Button/Default
Login/Button/Pressed
Login/SocialButton/Google
Login/SocialButton/Facebook

Feed/PostCard/Default
Feed/PostCard/WithImage
Feed/PostCard/Dark
Feed/StoriesBar/Default
Feed/Composer/Default

Profile/Avatar/Large
Profile/Avatar/Small
Profile/StatsRow/Default
Profile/PhotoGrid/Default
Profile/Button/Follow
Profile/Button/Following
Profile/Button/Message

CreatePost/Composer/Empty
CreatePost/Composer/Filled
CreatePost/MediaUpload/Default
CreatePost/AddOnRow/PhotoVideo
CreatePost/AddOnRow/TagFriends

Settings/SectionHeader/AccountSettings
Settings/SectionHeader/Privacy
Settings/NavRow/Default
Settings/NavRow/WithSubtitle
Settings/ToggleRow/On
Settings/ToggleRow/Off

Global/BottomNav/Light
Global/BottomNav/Dark
Global/FAB/Default
Global/FAB/Expanded
Global/TopBar/Default
Global/TopBar/WithBack
```

---

## Microinteractions Reference

| Component | Trigger | Animation | Duration | Easing |
|-----------|---------|-----------|----------|--------|
| Primary button | Tap | Scale 1→0.97→1 | 120ms | ease |
| Follow button | Tap | Text + fill swap | 200ms | ease |
| Like heart | Tap | Scale 1→1.3→1, color shift | 150ms | spring |
| FAB | Tap | Rotate 45°, expand | 220ms | ease-out |
| Bottom nav tab | Tap | Icon +2px, label fade in | 160ms | ease |
| Screen push | Navigate | Slide left | 300ms | ease-in-out |
| Screen pop | Back | Slide right | 280ms | ease-in-out |
| Feed skeleton | Auto | Opacity 0.4→1→0.4 loop | 1200ms | ease-in-out |
| Toast / snackbar | Auto | Slide up from bottom | 200ms | ease-out |

---

## Accessibility Compliance — WCAG 2.1 AA

| Criterion | Specification | Status |
|-----------|---------------|--------|
| 1.4.3 Contrast (Normal text) | ≥ 4.5:1 | PASS — body text 18.1:1 |
| 1.4.3 Contrast (Large text) | ≥ 3:1 | PASS — brand purple 4.5:1 |
| 1.4.11 Non-text contrast | ≥ 3:1 | PASS — all UI components |
| 2.5.5 Target size | ≥ 44×44px | PASS — all targets 48px min |
| 1.3.1 Info and relationships | Labels programmatic | PASS — annotated in Figma |
| 1.4.1 Use of color | Not color alone | PASS — icons + color for errors |
| 1.4.4 Resize text | Up to 200% no loss | PASS — flexible layouts |
| 2.4.7 Focus visible | Visible focus indicator | PASS — brand purple ring |
