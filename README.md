# 🎨 STEP NITK Website Redesign

> A modern, responsive, and accessible redesign of the STEP NITK Home and About pages.

---

## 🔗 Project Links

- **Figma Design File & Interactive Prototype:** [View on Figma](https://www.figma.com/design/6h40F1x8lo2o5g9qVri7KZ/HOME-PAGE---ABOUT-PAGE-design?m=auto&t=Vkj1zHdQo6oBvZqJ-6)

---

## 📸 Before vs. After (Key UX Fixes)

### 1. Hero Section Layout Overflow
| Original (Layout Outflow & White Gap) | Redesign (1440px Container & Full Bleed) |
| :---: | :---: |
| <img src="./screenshots/starting_section-before.png" width="400"/> | <img src="./screenshots/starting_section-after.png" width="400"/> |

### 2. FAQ Component Mechanics & Hitbox
| Original (Unenclosed Box & Truncated Border) | Redesign (Closed Card & Full Surface Clickability) |
| :---: | :---: |
| <img src="./screenshots/FAQ-before.png" width="400"/> | <img src="./screenshots/FAQ-after.png" width="400"/> |

---

## 💡 Design Rationale & Decisions

### 1. Architectural & Layout Fixes
- **Hero Section Alignment:** Eliminated edge clipping and unwanted white margins by constraining the hero background and navigation bar within a unified 1440px container layout.
- **Text Collision Fix:** Solved overlapping text on statistical cards ("With Great Outcomes." overlapping "Active Innovators") using Auto Layout with fixed vertical spacing.

### 2. Usability & Accessibility Enhancements
- **Closed FAQ Cards:** Enclosed every FAQ item in a bounded card container (8px corner radius, subtle stroke).
- **Expanded Hitbox:** Wrapped question labels and icons inside Auto Layout so the entire rectangular card surface acts as a clickable trigger.
