# Design System: Prev MotoCar Brand Links

**Project ID:** carlosgletison-ops/prevmotocar-links

## 1. Visual Theme & Atmosphere
The design system of Prev MotoCar utilizes a **Corporate Split Dashboard** visual theme. The top header of the page features a bold, curved red banner that serves as a high-contrast backing for the white checkmark shield logo. The main content cards are placed in a container that overlaps the red banner, floating above a clean, luxury light gray background (`#f8fafc`). The overall atmosphere is highly professional, corporate, and clean—modeled after premium web application dashboards.

## 2. Color Palette & Roles
* **Vibrant Brand Red** (`#e31c23` to `#c81016`): Used as the solid gradient backdrop for the top header banner and the footer logo badge to ensure 100% contrast for the white logo.
* **Luxurious Page Background** (`#f8fafc`): Clean, light gray base of the body to convey trust, clarity, and professionalism.
* **Pure Card White** (`#ffffff`): The solid fill color of the main content cards and headers to ensure maximum contrast for text.
* **Dark Charcoal** (`#1f2937`): Used for section headers, card titles, and primary texts inside cards to maximize legibility.
* **Slate Gray** (`#4b5563`): Used for card details and text descriptions.
* **Light Red Accent** (`rgba(227, 28, 35, 0.04)`): Used for icon container backgrounds.

## 3. Typography Rules
* **Font Family**: Public Sans, a clean and reliable corporate sans-serif font.
* **Titles**: 800 (Extra Bold) or 900 (Black) weight, with a slightly condensed letter-spacing (`-0.02em`) for headlines.
* **Body / Subheadings**: 500 (Medium) to 700 (Bold) weight inside white cards.
* **Descriptions**: 400 (Regular) weight, using slate gray color inside cards.

## 4. Component Stylings
* **Buttons / Direct Link Cards**:
  * Shape: Pill-shaped icons (`rounded-full`) inside rounded rectangular cards (`rounded-lg` with `16px` border-radius).
  * Color & Borders: Opaque white card background, thin gray borders (`rgba(226, 232, 240, 0.9)`), highlighting to red on hover.
  * Interaction: Crimson spotlight overlay that tracks the mouse pointer, with a translation up (`translateY(-3px)`) and clean shadow on hover.
* **Cards / Containers**:
  * Corner Roundness: Generously rounded corners (`24px` border-radius or `var(--radius-lg)`).
  * Background Color: Solid white background (`#ffffff`).
  * Shadow Depth: Soft light drop shadow (`rgba(0, 0, 0, 0.04)`) combined with a soft crimson glow outline on hover.
* **Brand Logo Badges (Footer)**:
  * Shape & Background: Solid red rectangular container (`#e31c23`) with `0.5rem 1rem` padding and rounded corners.
  * Purpose: Restores high contrast for the white logo at the bottom of the light gray page.

## 5. Layout Principles
* **Whitespace & Margins**: Spacing is configured in a clear vertical hierarchy with `2.25rem` margins between sections and `0.85rem` between individual cards.
* **Overlapping Grid**: The main content container is positioned with a negative margin (`margin-top: -3.5rem`) so it overlaps the curved red header banner, creating a high-fidelity dashboard layer depth.
* **Grid & Responsiveness**:
  * Desktop/Tablet: Benefits are organized in a clean 2-column grid (`grid-template-columns: repeat(2, 1fr)`).
  * Mobile: Grid falls back to a vertical list of horizontal cards to optimize readability.
* **Overlay Grid**: A white grid pattern (`background-size: 40px 40px`) overlays the red header banner at 3% opacity.
