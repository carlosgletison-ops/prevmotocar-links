# Design System: Prev MotoCar Brand Links

**Project ID:** carlosgletison-ops/prevmotocar-links

## 1. Visual Theme & Atmosphere
The design system of Prev MotoCar is built around a **Sleek Premium Dark Red** atmosphere. It captures a sense of emergency, high-end protection, security, and modernity. The aesthetic philosophy combines a pitch-dark base layer with fluid, slow-floating red ambient glow highlights, overlayed with a micro-thin technical grid for a structured layout. The overall vibe is protective, state-of-the-art, and highly interactive.

## 2. Color Palette & Roles
* **Deep Space Charcoal** (`#0a090c`): Used as the primary background color of the body to convey security, high contrast, and premium appeal.
* **Pure Solid White** (`#ffffff`): Used for brand titles and primary text, ensuring outstanding legibility against the dark background.
* **Sleek Accent Red** (`#e31c23`): Used for primary action borders, icon highlighting, and brand accents.
* **Glow Crimson** (`#ff2a34`): A brighter, high-vibrancy red used for hover status highlights and interactive glow effects.
* **Dimmed Slate Gray** (`#9ca3af`): Used for subheadings, descriptions, and secondary metadata to enforce typographic hierarchy.
* **Muted Onyx** (`#121116`): The solid fill color for glassmorphic cards, mixed with 70% opacity to allow background blur absorption.

## 3. Typography Rules
* **Font Family**: Public Sans, a clean and neutral sans-serif font that conveys high-tech reliability.
* **Titles**: 800 (Extra Bold) or 900 (Black) weight, with a slightly condensed letter-spacing (`-0.02em`) for a strong, impactful brand header.
* **Body / Subheadings**: 500 (Medium) to 700 (Bold) weight, ensuring strong legibility for quick phone and contact readings.
* **Descriptions / Details**: 400 (Regular) weight, using slate gray color to establish a clear visual hierarchy.

## 4. Component Stylings
* **Buttons / Direct Link Cards**:
  * Shape: Pill-shaped icons (`rounded-full`) inside rounded rectangular cards (`rounded-lg` with `16px` border-radius).
  * Color & Borders: Translucent dark background, thin red borders (`rgba(227, 28, 35, 0.12)`), lighting up to high-contrast red on hover.
  * Interaction: Rich interactive spotlight effect (glow matching the mouse pointer via custom CSS variables) and translation up (`translateY(-2px)`) on hover.
* **Cards / Containers**:
  * Corner Roundness: Generously rounded corners (`24px` border-radius or `var(--radius-lg)`).
  * Background Color: Glassmorphic dark overlay (`rgba(18, 17, 22, 0.7)`) with high-depth background blur filter (`backdrop-filter: blur(20px)`).
  * Shadow Depth: Deep, soft black drop shadow (`rgba(0, 0, 0, 0.7)`) combined with a soft red outline glow (`rgba(227, 28, 35, 0.15)`) on hover.
* **Inputs / Forms**:
  * (N/A for links page, but follows card styling: dark translucent backgrounds with thin bordered strokes).

## 5. Layout Principles
* **Whitespace & Margins**: Structured vertical rhythm using margins of `2.25rem` (spacing between main sections) and `0.85rem` (spacing between action cards).
* **Grid & Responsiveness**:
  * Desktop/Tablet: Benefits are organized in a clean 2-column grid (`grid-template-columns: repeat(2, 1fr)`).
  * Mobile: Grid transforms into a vertical list of horizontal rows where the icon and text are aligned side-by-side to optimize space and vertical scroll.
* **Overlay Grid**: A faint technical pixel grid (`background-size: 40px 40px`) overlays the viewport to anchor items with technical precision.
