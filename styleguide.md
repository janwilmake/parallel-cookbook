# Parallel.ai Style Guide

## Overview

Parallel.ai uses a dual-theme design system with distinct visual approaches for public landing pages (light theme) and the authenticated application interface (dark theme). The platform also features a unique HUMAN/MACHINE toggle that switches between user-friendly layouts and machine-readable text formats.

---

## Theme System

### Light Theme (Landing Pages)

- **Background**: Clean white (#FFFFFF)
- **Primary Text**: Dark gray/black for high contrast
- **Typography**: Clean, modern sans-serif
- **Layout**: Spacious, marketing-focused with generous whitespace
- **Usage**: Public pages, about sections, marketing content

### Dark Theme (Application Interface)

- **Background**: Deep charcoal/black (#1a1a1a or similar)
- **Primary Text**: Light gray/white (#ffffff, #e5e5e5)
- **Secondary Text**: Medium gray (#888888, #aaaaaa)
- **Layout**: Dense, productivity-focused interface
- **Usage**: Authenticated areas, API interfaces, working environments

---

## Typography

### Headings

- **Style**: Bold, sans-serif
- **Light Theme**: Dark text on light background
- **Dark Theme**: White/light gray text
- **Hierarchy**: Clear size differentiation between H1, H2, H3

### Body Text

- **Light Theme**: Medium gray for readability
- **Dark Theme**: Light gray (#cccccc or similar)
- **Line Height**: Generous spacing for readability

### Code/Technical Text

- **Font**: Monospace
- **Style**: Used in machine-readable format
- **Color**: Consistent with theme (light on dark, dark on light)

---

## Navigation & Header

### Logo/Brand

- **Text**: "parallel" in lowercase
- **Style**: Bold, modern sans-serif
- **Color**: Adapts to theme (dark on light, light on dark)

### Navigation Links

- **Style**: Clean, minimal
- **Spacing**: Generous horizontal spacing
- **Links**: About, Blog, Docs, START BUILDING
- **Hover States**: Subtle color changes

### Call-to-Action Button

- **Primary CTA**: "START BUILDING"
- **Style**: Rectangular button with "P" icon
- **Color**: Accent color that stands out from background

---

## HUMAN/MACHINE Toggle

### Purpose

Switches between two distinct display modes:

#### HUMAN Mode

- **Layout**: Traditional web interface
- **Design**: User-friendly, visually appealing
- **Typography**: Mixed sizes, styled headings
- **Spacing**: Generous whitespace and padding
- **Target**: End users, casual browsing

#### MACHINE Mode

- **Layout**: Text-heavy, structured format
- **Design**: Minimalist, functional
- **Typography**: Monospace or simple fonts
- **Content**: Raw text, URLs, structured data
- **Spacing**: Compact, information-dense
- **Target**: APIs, scraping, data extraction

### Toggle Implementation

- **Location**: Bottom of pages
- **Style**: Radio button style toggle
- **Labels**: "HUMAN" and "MACHINE"
- **Visual**: Clear active state indication

---

## Interface Components

### Form Elements

- **Input Fields**:
  - Dark theme: Dark background with light borders
  - Light theme: Light background with subtle borders
- **Buttons**: Consistent with theme colors
- **Dropdowns**: Match overall dark/light aesthetic

### Code Examples

- **Background**: Darker shade within dark theme
- **Text**: Syntax highlighting appropriate to theme
- **Format**: Tabbed interface (Python, cURL examples shown)

### Cards/Sections

- **Dark Theme**: Subtle borders or background variations
- **Light Theme**: Clean white cards with soft shadows
- **Padding**: Generous internal spacing
- **Corners**: Slightly rounded for modern feel

---

## Color Palette

### Dark Theme

- **Primary Background**: #1a1a1a (or similar deep charcoal)
- **Secondary Background**: Slightly lighter variations
- **Primary Text**: #ffffff
- **Secondary Text**: #cccccc, #888888
- **Accent**: Orange/amber for interactive elements
- **Borders**: Subtle gray (#333333)

### Light Theme

- **Primary Background**: #ffffff
- **Secondary Background**: Very light gray (#f8f8f8)
- **Primary Text**: #333333
- **Secondary Text**: #666666, #888888
- **Accent**: Consistent with dark theme accents
- **Borders**: Light gray (#e5e5e5)

---

## Layout Principles

### Grid System

- **Responsive**: Adapts to different screen sizes
- **Content Width**: Centered with maximum width constraints
- **Margins**: Generous side margins on larger screens

### Spacing

- **Vertical Rhythm**: Consistent spacing between sections
- **Horizontal**: Balanced spacing for readability
- **Density**: Light theme more spacious, dark theme more compact

### Content Organization

- **Hierarchy**: Clear information architecture
- **Sections**: Well-defined content blocks
- **Flow**: Logical progression from top to bottom

---

## Interactive Elements

### Buttons

- **Primary**: Prominent call-to-action styling
- **Secondary**: Subtle, complementary to theme
- **Hover States**: Subtle color/opacity changes
- **Icons**: Simple, consistent icon usage

### Links

- **Styling**: Underlined or color-differentiated
- **Hover**: Color changes or underline appearance
- **Visited**: Appropriate visited state styling

### Form Interactions

- **Focus States**: Clear indication of active fields
- **Validation**: Error states with appropriate colors
- **Feedback**: Success and error messaging

---

## Accessibility

### Contrast

- **Text**: High contrast ratios for readability
- **Interactive Elements**: Clear visual distinction
- **Focus States**: Visible focus indicators

### Typography

- **Size**: Adequate base font sizes
- **Line Height**: Sufficient spacing for readability
- **Weight**: Appropriate font weights for hierarchy

---

## Technical Implementation Notes

### Theme Switching

- CSS custom properties for easy theme switching
- Consistent component behavior across themes
- Smooth transitions when changing themes

### HUMAN/MACHINE Toggle

- JavaScript-driven content switching
- Maintain semantic HTML structure
- Preserve accessibility across modes

### Responsive Design

- Mobile-first approach
- Breakpoint considerations for both themes
- Consistent experience across devices
