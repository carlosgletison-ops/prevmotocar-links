# Design System: Prev MotoCar Brand Links

**Project ID:** carlosgletison-ops/prevmotocar-links

## 1. Visual Theme & Atmosphere
The design system of Prev MotoCar is built around a **Vibrant Solid Red & High-Contrast White** atmosphere. It captures energy, strong brand authority, protection, and corporate reliability. The visual language uses a solid red backdrop with a subtle white technical grid, populated by opaque, creamy white cards. This creates an extremely clean, readable, and bold visual appearance.

## 2. Color Palette & Roles
* **Vibrant Brand Red** (`#e31c23`): Used as the primary background color of the body to convey security, brand identity, and presence.
* **Pure Creamy White** (`rgba(255, 255, 255, 0.94)` / `#ffffff`): Used for glassmorphic cards and headers, acting as high-contrast content containers.
* **Solid White** (`#ffffff`): Used for section titles, vertical bar indicators, and footer texts directly on the red background, ensuring readability.
* **Dark Charcoal** (`#1f2937`): Used for card titles and main headings to establish legibility on the white cards.
* **Slate Gray** (`#4b5563`): Used for descriptions and card details to create typographic contrast.
* **Dimmed White** (`rgba(255, 255, 255, 0.7)`): Used for secondary footer text to maintain visual hierarchy.

## 3. Typography Rules
* **Font Family**: Public Sans, a clean, modern, and highly legible sans-serif font.
* **Titles**: 800 (Extra Bold) or 900 (Black) weight, with a slightly condensed letter-spacing (`-0.02em`) for maximum brand presence.
* **Body / Subheadings**: 500 (Medium) to 700 (Bold) weight, ensuring strong legibility for emergency card content.
* **Descriptions / Details**: 400 (Regular) weight, using slate gray color inside cards.

## 4. Component Stylings
* **Buttons / Direct Link Cards**:
  * Shape: Pill-shaped icons (`rounded-full`) inside rounded rectangular cards (`rounded-lg` with `16px` border-radius).
  * Color & Borders: Clean white background, thin white borders (`rgba(255, 255, 255, 0.6)`), lighting up to solid white on hover.
  * Interaction: Glossy white spotlight reflection tracking the mouse pointer, with a translation up (`translateY(-3px)`) and clean drop shadow on hover.
* **Cards / Containers**:
  * Corner Roundness: Generously rounded corners (`24px` border-radius or `var(--radius-lg)`).
  * Background Color: High-opacity white glass (`rgba(255, 255, 255, 0.94)`) with background blur filter (`backdrop-filter: blur(12px)`).
  * Shadow Depth: Soft dark drop shadow (`rgba(0, 0, 0, 0.15)`) combined with a white outline glow on hover.
* **Inputs / Forms**:
  * (N/A for links page).

## 5. Layout Principles
* **Whitespace & Margins**: Spacing is configured in a clear vertical hierarchy with `2.25rem` margins between sections and `0.85rem` between individual cards.
* **Grid & Responsiveness**:
  * Desktop/Tablet: Benefits are organized in a clean 2-column grid (`grid-template-columns: repeat(2, 1fr)`).
  * Mobile: Grid falls back to a vertical list of horizontal cards to optimize readability and thumb-reach.
* **Overlay Grid**: A white grid pattern (`background-size: 40px 40px`) overlays the red background at 4% opacity to create a technical layout foundation.
