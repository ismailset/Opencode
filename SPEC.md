# Portfolio Specification: Junior Web Designer

## 1. Project Overview
- **Project name**: Designer Portfolio
- **Type**: Single-page portfolio website
- **Core functionality**: Showcase a junior web designer's work, skills, and contact information with an elegant, editorial aesthetic
- **Target users**: Potential employers, clients, collaborators

## 2. UI/UX Specification

### Layout Structure
- **Header**: Fixed minimal nav with name/logo and nav links
- **Hero**: Full-height intro with animated text reveal
- **About**: Brief bio with skill highlights
- **Projects**: Grid showcase of 3-4 portfolio pieces
- **Contact**: Simple contact section with email
- **Footer**: Minimal credits

### Responsive Breakpoints
- Mobile: < 768px (single column)
- Tablet: 768px - 1024px (2 columns for projects)
- Desktop: > 1024px (3-4 columns for projects)

### Visual Design

**Color Palette**
- Background: `#F7F5F0` (warm cream)
- Primary text: `#1A1A1A` (near black)
- Accent: `#E85D04` (burnt orange)
- Secondary: `#8B8680` (warm gray)
- Card background: `#FFFFFF`

**Typography**
- Headings: "Playfair Display" (serif, elegant)
- Body: "DM Sans" (clean, modern)
- Hero title: 72px desktop / 42px mobile
- Section headings: 48px desktop / 32px mobile
- Body text: 18px
- Small text: 14px

**Spacing System**
- Section padding: 100px vertical desktop / 60px mobile
- Container max-width: 1200px
- Grid gap: 32px
- Card padding: 24px

**Visual Effects**
- Subtle grain texture overlay on background
- Cards with soft shadow: `0 4px 24px rgba(0,0,0,0.08)`
- Hover lift on project cards: translateY(-8px)
- Smooth scroll behavior
- Staggered fade-in animations on scroll

### Components

**Navigation**
- Logo/name on left
- Links: Work, About, Contact
- Underline animation on hover

**Hero Section**
- Large headline with staggered word reveal
- Subtitle with role description
- Scroll indicator

**Project Cards**
- Image thumbnail (placeholder gradient/pattern)
- Project title
- Short description
- Tags for technologies used
- Hover: lift + shadow increase

**Skill Tags**
- Pill-shaped badges
- Subtle background color

**Contact Button**
- Solid accent color
- Hover: darken + slight scale

## 3. Functionality Specification

### Core Features
- Smooth scroll navigation
- Scroll-triggered animations (fade in sections)
- Project cards link to individual case studies (placeholder links)
- Mailto contact link
- Responsive layout

### User Interactions
- Click nav links → smooth scroll to section
- Hover project cards → lift animation
- Hover nav links → underline animation
- Scroll → elements fade in

### Edge Cases
- Images use CSS gradients as placeholders (no external image dependencies)
- Fallback fonts if Google Fonts fail

## 4. Acceptance Criteria
- [ ] Page loads without errors
- [ ] All sections visible and properly styled
- [ ] Navigation links scroll to correct sections
- [ ] Animations trigger on scroll
- [ ] Responsive on mobile/tablet/desktop
- [ ] All text is readable and properly sized
- [ ] Color scheme matches spec exactly
