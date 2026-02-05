# Cursor Landing Page Clone

A modern, dark-themed SaaS landing page built to replicate the Cursor IDE website. This project features a clean, production-quality design built with pure HTML and CSS (no frameworks or JavaScript).

## Hosted on GitHub Pages: 
[https://mursaleennisar.github.io/cursor-clone/](https://mursaleennisar.github.io/cursor-clone/)

## 🎨 Design Overview

This is a **desktop-only** landing page with a focus on modern design principles, dark theme aesthetics, and smooth visual hierarchy.

## 🔤 Typography

### Fonts Used
- **All Text**: Inter

## 🎨 Color System

### Background Colors
- **Primary Background**: `#0D0D0D`
- **Secondary Background**: `#141414`
- **Card Background**: `#1C1914`
- **Secondary Card**: `#26251E`
- **Logo Strip Background**: `#1A1A1A`
- **Logo Card**: `#232323`

### Text Colors
- **Primary Text (White)**: `#FFFFFF`
- **Secondary Text (Off-white)**: `#B8B8B8`
- **Tertiary Text**: `#A1A1A1`
- **Muted Text**: `#8A8A8A`
- **Darker Muted**: `#6B6B6B`

### Accent Colors
- **Primary Accent (Orange)**: `#f54e00` / `#FF7849`

### Borders
- **Subtle Border**: `rgba(255, 255, 255, 0.03)`
- **Light Border**: `rgba(255, 255, 255, 0.08)`
- **Medium Border**: `#2A2A2A` / `#333333`

## 📐 Layout System

### Container
- **Max Width**: 1240px
- **Horizontal Padding**: 32px
- **Centered**: margin auto

### Spacing
- **Section Padding**: 80-120px vertical
- **Card Gap**: 16px
- **Column Gap**: 48-80px

### Border Radius
- **Small Elements**: 4px
- **Cards**: 4-12px
- **Images**: 16-20px
- **Buttons**: 999px (pill shape)
- **Badges**: 12px

## 📄 Page Sections

### 1. **Header / Navbar**
- Sticky positioning at top
- Backdrop blur effect
- Contains: Logo, Navigation links (Product, Business, Pricing, Resources), Sign in link, Download button
- Background: `rgba(13, 13, 13, 0.95)`
- Height: 72px

### 2. **Hero Section**
- Large headline with call-to-action
- Hero screenshot image
- Download button with icon
- Centered content with max-width constraint

### 3. **Logo Partners Strip**
- Title: "Trusted every day by teams that build world-class software"
- 8 company logos in 4-column grid
- Individual bordered cards for each logo
- Companies: Stripe, OpenAI, Linear, Datadog, NVIDIA, Figma, Ramp, Adobe

### 4. **Feature Split Sections (3 sections)**
- Alternating two-column layouts (50/50 split)
- Content includes heading, description, and CTA link
- Features:
  - "Agents turn ideas into code"
  - "Magically accurate autocomplete"
  - "In every tool, at every step"

### 5. **Testimonial Cards Section**
- 6 testimonial cards in 3-column grid
- Each card contains:
  - Review quote
  - Avatar image (48px circular)
  - Name and role
- Testimonials from: Diana Hu (Y Combinator), Patrick Collison (Stripe), Andrej Karpathy, Jensen Huang (NVIDIA), Greg Brockman (OpenAI), shadcn

### 6. **Advanced Tools Section - "Stay on the frontier"**
- Section heading with 3 tool cards
- Each card contains:
  - Title and description
  - CTA link
  - Screenshot image at bottom
- Cards: "Use the best model for every task", "Complete codebase understanding", "Develop enduring software"

### 7. **Changelog Section**
- Horizontal 4-column card grid
- Each card shows:
  - Version badge (optional)
  - Date
  - Title
- CTA: "See what's new in Cursor →"

### 8. **Media Showcase Section**
- Single horizontal card with 30/70 split
- Left (30%): Text content and CTA
- Right (70%): Team photo
- Heading: "Cursor is an applied research team focused on building the future of software development"

### 9. **Blog Updates Section - "Recent highlights"**
- Heading on left side
- 3 blog cards centered at 60% width
- Each card shows:
  - Title
  - Summary
  - Category and date
- CTA: "View more posts →"
- Background: `#1C1914`

### 10. **Final CTA Section**
- Centered layout
- Large heading: "Try Cursor now."
- Download button

### 11. **Footer**
- 5-column grid layout
- Columns: Product, Resources, Company, Legal, Connect
- Footer bottom with:
  - Copyright (left): "© 2026 Anysphere, Inc. ☑ SOC 2 Certified"
  - Controls (right): Theme toggle and language selector
- Background: `#1C1914`

## 🖼️ Images Used

### Feature Images
- `hero.png` - Main hero screenshot
- `feature-1.png` - GitHub/Slack integration
- `feature-2.png` - Tab autocomplete
- `feature-3.png` - AI agent development

### Logo Images (SVG)
- `stripe.svg`, `openai.svg`, `linear.svg`, `datadog.svg`
- `nvidia.svg`, `figma.svg`, `ramp.svg`, `adobe.svg`
- `logo.svg` - Cursor logo

### Avatar Images (WebP)
- `diana-hu-avatar.webp`
- `patrick-collison-avatar.webp`
- `andrej-karpathy-avatar.webp`
- `jensen-huang-avatar.webp`
- `greg-brockman-avatar.webp`
- `shadcn-avatar.webp`

### Tool Card Images (PNG)
- `best-modex.png` - Model selection interface
- `complete-codebase.png` - Codebase understanding
- `develop-enduring.png` - Enterprise development

### Team Photo
- `homepage-team-photo.webp` - Team showcase image

## 🎯 Key Features

### Design Principles
- **Desktop-Only**: No responsive design or media queries
- **No Animations**: Static design with minimal hover effects
- **Semantic HTML5**: Proper use of header, section, footer, nav, main tags
- **Clean CSS**: Organized into logical sections with consistent naming
- **No Frameworks**: Pure HTML and CSS only
- **Production Quality**: Clean, maintainable code structure

### Button Styles
- Primary button: White background, black text
- Pill shape with 999px border-radius
- Subtle hover effects (opacity and translateY)

### Card Styles
- Consistent 4px border-radius
- Subtle borders: `rgba(255, 255, 255, 0.03)`
- Dark backgrounds with proper contrast
- Minimal or no hover effects
