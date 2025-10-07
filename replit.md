# Vũ Thị Kim Ngân - Personal Album Website

## Overview

This is a personal portfolio/album website showcasing Vũ Thị Kim Ngân. The project is a static front-end website built with vanilla HTML and CSS, featuring a hero section, biography, and photo gallery. The design emphasizes a spring-themed aesthetic with soft pink gradients and animated backgrounds to reflect the subject's personality and birth season (spring, Aries zodiac).

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture

**Technology Stack:**
- Pure HTML5 and CSS3 (no frameworks or libraries)
- Vanilla JavaScript (minimal, if any)
- Static site architecture

**Design Pattern:**
- Single-page application (SPA) structure with multiple sections
- Section-based layout: Hero, Biography, Gallery
- Mobile-first responsive design approach using viewport meta tag

**Styling Approach:**
- CSS3 custom animations and keyframes for visual effects
- Gradient-based color scheme (pink, peach, cream tones)
- CSS Grid/Flexbox for layout management
- Animated backgrounds using pseudo-elements and CSS transforms

**Key Components:**
1. **Hero Section** - Full viewport height landing area with animated background pattern and centered content
2. **Biography Section** - Card-based information display with decorative headers and poetic descriptions
3. **Gallery Section** - Photo album with 6 image slots using proper img tags, placeholder overlays for empty images, and hover animations

**Animation Strategy:**
- Keyframe animations for background movement (`moveBackground`)
- Fade-in effects for content reveal (`fadeInUp`)
- Radial gradient patterns for decorative backgrounds

### Content Structure

**Information Architecture:**
- Personal details: Name, age, birthdate, zodiac sign
- Biographical narrative in Vietnamese language
- Visual content through photo gallery
- Thematic consistency: Spring/Aries personality traits

**Accessibility Considerations:**
- Semantic HTML5 structure
- Vietnamese language declaration (`lang="vi"`)
- Proper meta viewport configuration for responsive display

## External Dependencies

**Current State:**
- No external dependencies
- No third-party libraries or frameworks
- No backend services or APIs
- No database integration
- Self-contained static assets (CSS inline)

**Potential Future Dependencies:**
- Image hosting service for gallery photos
- Font service (Google Fonts or similar) for enhanced typography
- JavaScript libraries for enhanced gallery functionality (lightbox, carousel)
- Static site hosting platform (Netlify, Vercel, GitHub Pages)