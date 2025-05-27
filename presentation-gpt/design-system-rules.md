# Design System Rules

## Introduction

This design system provides a comprehensive set of rules and guidelines for maintaining visual consistency across our applications. It encompasses typography, spacing, colors, borders, and component styles, all designed to work together harmoniously while ensuring accessibility and responsiveness.

The system is built on a foundation of reusable tokens that can be applied across different platforms and contexts. These tokens are organized into logical categories and follow a consistent naming convention, making them easy to implement and maintain.

## Brand Identity

### Logo Usage

#### Placement
- **Center Aligned**
  - Use for brand-focused communications without headlines or other content
  - Always center align to the wordmark, not the entire logo mark

- **Corner Aligned**
  - Use for all other brand communications with headlines and content
  - When left-aligning the logo mark:
    - Use at least the width of two "d" characters as margin
    - Align the "d" in the wordmark with the star icon extending beyond the margin

#### Usage
- **Minimum Sizes**
  - Digital with clear space: 32x64px
  - Digital without clear space: 16x48px

- **Clear Space**
  - Always maintain minimum clear space around the logo

- **Approved Versions**
  - Only use official versions of the logo with approved background colors

#### Primary Logo
- The primary logo (icon + wordmark) should be used in almost all cases
- Never use the icon by itself—always pair it with the Dialpad wordmark

### Sub-Branding

#### Non-Product Sub-Brands
- Use the Dialpad wordmark paired with the sub-brand name
- Set the sub-brand name in Season Mix at the same size as the wordmark

#### Product Sub-Brands
- Use the Dialpad Platform sub-brand wordmarks or approved plain-text typesets
- Example: DialpadAi
  - Follow the same usage rules as other product platforms

### Typography

#### Type Family
- Season Sans and Season Mix are built with shared character and proportions
- Designed to work together across brand applications

#### Type Sizing
- Season Sans and Mix should always be used at the same size

#### Type Usage
- Designed for a consistent and unified tone across brand touchpoints

### Mixed Headlines
- Used for attract-level headlines to emphasize impact and outcomes
- Combine:
  - Season Sans 650 weight (lead)
  - Season Mix 550 weight (follow)
- Maximum: 48 characters
- Use color to emphasize the latter portion (positive outcomes)
- Use only for headlines written specifically for this mixed format

### Gradient
- Represents optimism, innovation, and the power of the Dialpad platform
- Always use approved gradient assets for brand consistency

#### Placement
- Anchor the gradient to the bottom of the composition
- Align the center of the gradient to:
  - Bottom-center
  - Bottom-left
  - Bottom-right

## Table of Contents

1. [Brand Identity](#brand-identity)
   - [Logo Usage](#logo-usage)
   - [Sub-Branding](#sub-branding)
   - [Typography](#typography-1)
   - [Mixed Headlines](#mixed-headlines)
   - [Gradient](#gradient)

2. [Typography](#typography)
   - [Font Families](#font-families)
   - [Font Sizes](#font-sizes)
   - [Line Heights](#line-heights)
   - [Font Weights](#font-weights)
   - [Text Cases](#text-cases)
   - [Typography Styles](#typography-styles)

3. [Spacing System](#spacing-system)
   - [Base Unit](#base-unit)
   - [Size Scale](#size-scale)
   - [Percentage Scale](#percentage-scale)
   - [Negative Values](#negative-values)

4. [Colors](#colors)
   - [Neutral Colors](#neutral-colors)
   - [Foreground Colors](#foreground-colors)
   - [Status Colors](#status-colors)
   - [Link Colors](#link-colors)
   - [Surface Colors](#surface-colors)
   - [Status Surface Colors](#status-surface-colors)
   - [Border Colors](#border-colors)
   - [Special Colors](#special-colors)

5. [Border System](#border-system)
   - [Border Sizes](#border-sizes)
   - [Border Radius](#border-radius)

6. [Design Principles](#design-principles)

---

## Typography

### Font Families
- **Body**: System fonts with fallbacks
  - Primary: -apple-system, BlinkMacSystemFont, "SF Pro"
  - Fallbacks: "Segoe UI", SFMono, "Helvetica Neue", Cantarell, Ubuntu, Roboto, Arial, "Noto Sans"
  - Emoji support: "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji"

- **Expressive**: "Season Mix" with system font fallbacks
- **Monospace**: SFMono-Regular, "SF Mono", Consolas, "Liberation Mono", Menlo, Courier

### Font Sizes
- **Root**: 10px
- **Scale**:
  - 100: 12px
  - 200: 15px
  - 300: 19px
  - 400: 27px
  - 500: 38px

### Line Heights
- 100: 1
- 200: 1.2
- 300: 1.4
- 400: 1.6
- 500: 1.8
- 600: 2

### Font Weights
- Normal: 400
- Medium: 500
- SemiBold: 600
- Bold: 700

### Text Cases
- Uppercase
- Lowercase
- Capitalize
- None

### Typography Styles

#### Body Styles
- **Medium**
  - Size: 15px
  - Line Height: 1.6
  - Weight: 400
  - Compact variant available

- **Small**
  - Size: 12px
  - Line Height: 1.4
  - Weight: 400
  - Compact variant available

#### Headline Styles
- **Eyebrow**
  - Size: 12px
  - Line Height: 1.4
  - Weight: 400
  - Text Case: Uppercase

- **Small**
  - Size: 12px
  - Line Height: 1.4
  - Weight: 700
  - Variants: Regular, Compact, Soft, Soft Compact

- **Medium**
  - Size: 15px
  - Line Height: 1.6
  - Weight: 700
  - Variants: Regular, Compact

- **Large**
  - Size: 19px
  - Line Height: 1.6
  - Weight: 700
  - Variants: Regular, Soft, Compact, Soft Compact

- **Extra Large**
  - Size: 27px
  - Line Height: 1.2
  - Weight: 500
  - Variants: Regular, Compact

- **2X Large**
  - Size: 38px
  - Line Height: 1.2
  - Weight: 500
  - Variants: Regular, Compact

## Spacing System

### Base Unit
- Base: 8px

### Size Scale
- 0: 0rem
- 50: 0.03125rem
- 100: 0.0625rem
- 200: 0.125rem
- 300: 0.25rem
- 350: 0.375rem
- 400: 0.5rem
- 450: 0.75rem
- 500: 1rem
- And so on up to 1200

### Percentage Scale
- 0% to 100% in standard increments
- Special values: 33.333%, 66.7%

### Negative Values
- Available for all size values
- Used for positioning and offsets

## Colors

### Neutral Colors
- White: #ffffff
- Black: #000000
- Transparent

### Foreground Colors
- Primary: #1C1C1C
- Secondary: #3A3A3A
- Tertiary: #535353
- Muted: #000000
- Placeholder: #808080
- Disabled: #808080

### Status Colors
- Critical: #D90A45
- Critical Strong: #AF0032
- Success: #008E52
- Success Strong: #004F2E
- Warning: #815008

### Link Colors
- Primary: #7C52FF
- Primary Hover: #5023DD
- Critical: #D90A45
- Critical Hover: #AF0032
- Success: #008E52
- Success Hover: #004F2E
- Warning: #815008
- Warning Hover: #533204
- Muted: #3A3A3A
- Muted Hover: #1C1C1C
- Disabled: #808080

### Surface Colors
- Primary: #ffffff
- Secondary: #F9F9F9
- Moderate: #E9E9E9
- Bold: #D2D2D2
- Strong: #535353
- Contrast: #252525

### Status Surface Colors
- Critical: #FFE5E6
- Warning: #FFF4CC
- Success: #EDF9EB
- Info: #EAF2FA
- Brand: #F5F0FF

### Border Colors
- Subtle: #1C1C1C
- Default: #1C1C1C
- Moderate: #1C1C1C
- Bold: #1C1C1C
- Focus: #4AA9EA
- Accent: #FF1BA4

### Special Colors
- AI Gradient: Complex gradient from purple to orange
- Backdrop: #000000

## Border System

### Border Sizes
- 0: 0rem
- 50: 0.03125rem
- 100: 0.0625rem
- 150: 0.09375rem
- 200: 0.125rem
- 300: 0.25rem
- 400: 0.5rem

### Border Radius
- 0: 0rem
- 100: 0.0625rem
- 200: 0.125rem
- 300: 0.25rem
- 400: 0.5rem
- 450: 0.75rem
- 500: 1rem
- 600: 2rem
- Pill: 6.375rem
- Circle: 50%

## Design Principles

1. **Consistency**
   - Use predefined tokens for all measurements
   - Maintain consistent spacing and sizing
   - Follow typography hierarchy

2. **Accessibility**
   - High contrast ratios
   - Clear visual hierarchy
   - Proper text sizing and spacing

3. **Responsiveness**
   - Flexible units (rem)
   - Percentage-based layouts
   - Responsive typography

4. **Theme Support**
   - Light and dark mode variants
   - Inverted color schemes
   - Opaque variants for overlays

5. **Component Design**
   - Consistent border radiuses
   - Standardized spacing
   - Unified color palette 