---
title: Leland E. Doss Resume Design System
description: Professional dark-mode technical resume with dynamic animations, electric VFX, and responsive layout
tokens:
  # Color Palette - Dark Mode Base
  colors:
    - name: Background Primary
      value: "#0e1a2b"
      description: Deep navy base background
    - name: Background Soft
      value: "#142640"
      description: Slightly lighter navy for panels and containers
    - name: Background Panel
      value: "#1a2f4d"
      description: Tertiary panel background with increased contrast
    - name: Background Panel Dark
      value: "#11233c"
      description: Darkest panel background for bottom gradients
    
    # Text Colors
    - name: Text Primary
      value: "#eef3fa"
      description: Primary text color - high contrast light blue-white
    - name: Text Secondary
      value: "#c2cfe0"
      description: Secondary text color - softer contrast for descriptions
    - name: Text Muted
      value: "#8a98ad"
      description: Tertiary text for labels and subtle content
    - name: Text Dim
      value: "#5a6577"
      description: Darkest text for minimal contrast areas
    
    # Accent Colors - Primary
    - name: Accent Primary
      value: "#5aa8ff"
      description: Main blue accent for interactive elements and accents
    - name: Accent Secondary
      value: "#82c0ff"
      description: Lighter blue for highlighted states and prominent text
    - name: Accent Warm
      value: "#d4a574"
      description: Warm golden-brown for dates, tags, and warm accents
    
    # Electric VFX Colors
    - name: Electric Cyan
      value: "#7ee2ff"
      description: Primary electric bolt color with glow
    - name: Electric Blue
      value: "#6bc7ff"
      description: Secondary electric branch color
    
    # Highlight & Glow Colors
    - name: Highlight Yellow
      value: "#ffdd59"
      description: Primary highlight for hover states
    - name: Highlight Orange
      value: "#ffaa2b"
      description: Secondary orange for smooth transitions
    - name: Highlight Status Green
      value: "#4ade80"
      description: Success/active status indicator
    
    # Border & Line Colors
    - name: Line
      value: "rgba(170, 200, 235, 0.14)"
      description: Subtle border for low-contrast divisions
    - name: Line Strong
      value: "rgba(170, 200, 235, 0.28)"
      description: Stronger border for primary divisions
    
    # Print Mode
    - name: Print Background
      value: "#ffffff"
      description: White background for print optimization

  # Typography
  typography:
    - name: Font Family
      value: "Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif"
      description: Modern sans-serif system font stack
    - name: Base Font Size
      value: "15px"
      description: Body text baseline
    - name: Line Height
      value: "1.55"
      description: Comfortable reading height for body text
    - name: Heading Scale
      value: "1.35em (section), 1.08em (item titles), 1.85em (name)"
      description: Typographic hierarchy scale
    - name: Letter Spacing
      value: "Standard -0.3px to -0.5px for headings, 0.5px-2.5px for labels"
      description: Fine-tuned letter spacing for clarity and elegance

  # Spacing & Sizing
  spacing:
    - name: Base Unit
      value: "8px"
      description: Fundamental spacing unit
    - name: Padding Standard
      value: "24px to 56px (context-dependent)"
      description: Content padding varies by container
    - name: Gap
      value: "6px to 20px"
      description: Spacing between sibling elements
    - name: Margin Bottom
      value: "20px (items), 44px (sections)"
      description: Vertical spacing between major containers

  # Border & Corner Radius
  radii:
    - name: Default
      value: "6px"
      description: Small buttons and tags
    - name: Container
      value: "8px"
      description: Cards and experience/project items
    - name: Rounded
      value: "14px"
      description: Main resume container
    - name: Circle
      value: "50%"
      description: Avatar and circular elements

  # Shadows & Elevation
  shadows:
    - name: Small
      value: "0 8px 24px rgba(0, 0, 0, 0.35)"
      description: Avatar glow effect
    - name: Medium
      value: "0 10px 24px rgba(0, 0, 0, 0.18)"
      description: Experience item base shadow
    - name: Large
      value: "0 20px 60px rgba(0, 0, 0, 0.4), 0 0 0 1px rgba(90, 168, 255, 0.05)"
      description: Main resume container shadow with blue highlight
    - name: Glow Base
      value: "0 16px 34px rgba(0, 0, 0, 0.24), 0 0 0 1px rgba(255, 196, 0, 0.10)"
      description: Experience item hover glow

  # Motion & Animation
  motion:
    - name: Slide-in Duration
      value: "0.7s - 0.8s"
      description: Page load entrance animations
    - name: Hover Transition
      value: "0.6s"
      description: Smooth hover state transitions
    - name: Pulse Duration
      value: "2s - 2.2s"
      description: Continuous pulse animations
    - name: Electric Animation
      value: "0.44s - 0.52s"
      description: Electric bolt pulse frequency
    - name: Timing Function
      value: "ease-out (entrance), ease-in-out (continuous)"
      description: Standard easing for natural motion

  # Filter Effects
  filters:
    - name: Electric Glow
      value: "Gaussian blur 4px with color matrix"
      description: SVG filter for electric bolt glow
    - name: Drop Shadow Smoke
      value: "Multiple layered drop-shadows (12px-24px offset)"
      description: Smokey hover effect with up to 4 layers
    - name: Brightness
      value: "1.05"
      description: Subtle brightness boost on interaction

  # Breakpoints
  breakpoints:
    - name: Tablet
      value: "900px"
      description: Switch to single-column layout
    - name: Mobile
      value: "540px"
      description: Compact mobile styling

---

## Design Overview

This resume presents a **high-tech, dark-mode professional identity** that merges contemporary UI aesthetics with cinematic visual effects. The design communicates technical expertise, precision, and creative ambition through a carefully orchestrated system of animations, glows, and electric VFX.

### Core Design Philosophy

**1. Dark Mode Sophistication**
The deep navy (`#0e1a2b`) foundation creates a premium, tech-forward atmosphere. Layered with subtle gradients and radial backgrounds, the dark mode reduces cognitive load while allowing accent colors to command attention. The overall aesthetic evokes the aesthetic of professional design tools and game engine interfaces.

**2. Electric Dynamism**
Electric cyan and blue bolts (`#7ee2ff`, `#6bc7ff`) animate across the viewport as elements slide in on page load. These jagged, branching lightning paths create a sense of energy and innovation—suggesting the builder's technical prowess and dynamic problem-solving approach. The electricity is not gratuitous; it connects elements to their final positions, creating visual continuity.

**3. Layered Interactivity**
Hover states are deeply considered:
- Experience items expand slightly and glow with warm yellow-to-orange transitions
- Smokey drop-shadow effects wave organically around the cards
- The portfolio link pulses with a golden glow
- Every interaction feels intentional and responsive to user intent

**4. Hierarchy Through Accent**
A dual-accent system guides visual hierarchy:
- **Cool accents** (`#5aa8ff`, `#82c0ff`) for structural elements, contact info, and skill tags
- **Warm accents** (`#d4a574`) for dates, badges, and secondary information
- This contrast ensures all information types are easily distinguishable

### Visual Identity

**Color Story:**
The palette tells a story of precision and warmth. The cool blues establish technical credibility (Unreal Engine, software, data). The warm golds humanize the interface and draw attention to key employment periods and achievements. Together, they create a balanced, sophisticated appearance.

**Typography:**
Inter provides a contemporary, highly legible foundation. Fine adjustments to letter-spacing (especially -0.5px for headings) create visual polish. Font weights are strategic: 700 for prominent titles, 600 for section headers, 300-500 for body text, creating clear visual hierarchy without heaviness.

**Motion Language:**
- **Page Load:** Smooth slide-ins from left (sidebar) and right (content) with staggered delays create a choreographed entrance
- **Hover:** 0.6s transitions feel responsive without jarring—allowing users to admire the glow effects
- **Continuous:** Portfolio link and electric bolts pulse gently, suggesting ongoing readiness and energy

### Specific Component Design

**Avatar:**
The 140px circular avatar is the visual anchor of the sidebar. It features:
- Rotating dashed border animation (24s cycle)—suggesting constant motion and availability
- Deep shadows that suggest depth
- Optional image support with object-fit for profile photos

**Experience Cards:**
These are the resume's most interactive components:
- Base state: subtle elevation, clear borders, 25% blue background tint
- Hover state: 3% scale increase, left border brightens, background opacity increases
- Smokey effect: layered drop-shadows with 4-directional wave pattern (12-24px offsets)
- Yellow-to-orange glow animation syncs with shadow waves

**Section Animations:**
Sections slide in alternating from left and right with staggered delays, creating a sophisticated cascade effect that prevents information overload.

**Electric VFX:**
Jagged SVG paths render smooth strokes that animate from start to final position. Dual-layer bolts (main + branches) with opacity variation create depth. SVG filters provide authentic electric glow without performance overhead.

### Accessibility & Responsiveness

**Motion Respects Preferences:**
All animations are disabled when `prefers-reduced-motion` is active, ensuring the resume remains accessible to users with vestibular disorders.

**Print Optimization:**
Print media queries remove animations, adjust colors for ink efficiency, and reflow the layout to single-column for optimal printed readability.

**Responsive Breakpoints:**
- **Desktop (900px+):** Two-column layout with full sidebar and main content
- **Tablet (≤900px):** Single-column layout, sidebar moves above content
- **Mobile (≤540px):** Compact typography, reduced padding, touch-friendly spacing

### Color Psychology & Intent

**Deep Navy Foundation:**
Creates trust, professionalism, and a calm, focused environment—appropriate for serious career documentation.

**Electric Blues & Cyans:**
Signal innovation, technology, and precision. These colors evoke Unreal Engine's UI and modern software aesthetics, aligning with the builder's identity.

**Golden Warm Tones:**
Introduce humanity and creativity. They break up the cool palette, suggesting approachability and diverse skill (both technical and artistic).

**Green Status Indicators:**
Follow web conventions for "live" and "active" states, making project status instantly legible.

### Animation Strategy

Animations serve three purposes:
1. **Delight:** Page load entrance sequence is memorable and polished
2. **Affordance:** Hover effects clearly communicate interactivity
3. **Information:** Experience item hover reveals additional visual context (glows and shadows)

All timing is calibrated for smoothness without feeling slow. The 0.6-0.8s range for major animations is proven to feel responsive while still allowing visibility of the motion.

---

## Usage & Customization

This design system is self-contained in the HTML file's `<style>` block. All token values are defined as CSS custom properties (variables) in the `:root` selector for easy theme adjustments.

### Extending the Color Palette

To add or modify colors, update the `:root` variables:
```css
:root {
  --bg: #0e1a2b;
  --accent: #5aa8ff;
  /* ... additional tokens ... */
}
```

### Modifying Animation Timing

All animation durations and delays are centralized in their respective keyframe definitions and element selectors. To speed up all animations globally, reduce the `animation-duration` and `animation-delay` values proportionally.

### Print Media Considerations

The design includes comprehensive print media queries that:
- Remove animations
- Convert dark mode to light mode
- Adjust shadows and glows for ink efficiency
- Ensure text remains high-contrast on paper

---

## Design Principles Applied

1. **Constraint Creates Beauty:** Strict color palette and spacing system create cohesion
2. **Motion Conveys Polish:** Smooth animations separate professional from amateur
3. **Hierarchy Guides Scanning:** Color, size, and weight guide the eye through content
4. **Dark Elevates Accents:** Dark backgrounds allow cool and warm accents to pop
5. **Asymmetry Engages:** Alternating slide-in directions and staggered items prevent monotony
6. **Technology Reflected:** Electric VFX and Unreal-inspired colors signal technical expertise

---

## Closing

This design balances technical sophistication with human warmth. Every element—from the rotating avatar border to the smokey hover effects—reinforces the builder's identity as a seasoned Unreal Engine developer with an eye for polished, immersive experiences.

The resume itself is an interactive portfolio, a testament to design and implementation prowess.
