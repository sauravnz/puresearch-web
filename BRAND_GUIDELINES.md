# PureSearch Brand Guidelines

## Brand Overview

PureSearch is the only managed OpenSearch service built specifically for New Zealand organizations. Our brand embodies trust, innovation, local expertise, and data sovereignty while maintaining a modern, professional aesthetic.

### Brand Personality
- **Trustworthy**: Reliable, secure, professional
- **Innovative**: Modern, forward-thinking, tech-savvy
- **Local**: Proudly New Zealand, understanding local needs
- **Accessible**: Approachable, supportive, human
- **Sovereign**: Independent, secure, compliant

## Logo System

### Primary Logo Concept
The PureSearch logo combines a stylized 'P' with a magnifying glass, featuring:
- **Core Element**: Letter 'P' that doubles as a magnifying glass handle
- **Search Lens**: Circular lens with flowing data visualization patterns
- **Koru Influence**: Subtle curves inspired by New Zealand's koru symbol
- **Data Animation**: Flowing streams representing real-time analytics

### Logo Variations

#### 1. Full Logo (`images/logo.svg`)
- **Usage**: Marketing materials, presentations, formal documents
- **Dimensions**: 200×60px
- **Contains**: Icon + "PureSearch" wordmark + tagline

#### 2. Horizontal Logo (`images/logo-horizontal.svg`)
- **Usage**: Website headers, business cards, letterheads
- **Dimensions**: 160×40px
- **Contains**: Icon + horizontal "PureSearch" text + subtle tagline

#### 3. Icon Only (`images/logo-icon.svg`)
- **Usage**: App icons, favicons, social media profiles, small spaces
- **Dimensions**: 48×48px (scalable)
- **Contains**: Icon only with data visualization

#### 4. Favicon (`favicon.ico`)
- **Usage**: Browser tabs, bookmarks
- **Dimensions**: 32×32px, 16×16px
- **Contains**: Simplified icon optimized for small sizes

## Color Palette

### Primary Colors
```css
--primary-color: #1E3A5F;    /* Deep Blue - Trust, professionalism */
--secondary-color: #E85D25;   /* Catalyst Orange - Energy, partnership */
--accent-color: #00703C;      /* NZ Green - Local identity, growth */
```

### Supporting Colors
```css
--bright-blue: #0EA5E9;      /* Data visualization, tech elements */
--text-dark: #333333;        /* Primary text */
--text-light: #666666;       /* Secondary text */
--text-muted: #64748B;       /* Tertiary text */
--background-light: #F8FAFC; /* Light backgrounds */
--white: #FFFFFF;            /* Pure white */
```

### Usage Guidelines
- **Primary Blue**: Main brand elements, navigation, headers
- **Secondary Orange**: CTAs, highlights, energy elements
- **Accent Green**: Success states, checkmarks, New Zealand elements
- **Bright Blue**: Data visualization, technical illustrations
- **Text Colors**: Maintain accessibility contrast ratios

## Typography

### Primary Font Family
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
```

### Wordmark Typography
- **"Pure"**: Inter Medium (500 weight)
- **"Search"**: Inter Bold (700 weight)
- **Tagline**: Inter Medium (500 weight), smaller size, letter-spaced

### Hierarchy
- **H1**: 3rem, Bold (700)
- **H2**: 2.5rem, SemiBold (600)
- **H3**: 1.5rem, SemiBold (600)
- **Body**: 1.125rem, Regular (400)
- **Small**: 0.875rem, Medium (500)

## Logo Usage Guidelines

### Minimum Sizes
- **Full Logo**: 120px width minimum
- **Horizontal Logo**: 80px width minimum
- **Icon Only**: 16px minimum (for favicons)

### Clear Space
- Maintain clear space equal to 1x the height of the icon around all logos
- Never place text or other elements within this clear space

### Do's and Don'ts

#### ✅ DO:
- Use provided logo files without modification
- Maintain original proportions
- Use on appropriate backgrounds with sufficient contrast
- Use monochrome versions for single-color applications
- Ensure logos are crisp and clear at all sizes

#### ❌ DON'T:
- Stretch, distort, or skew the logo
- Change colors (except for approved monochrome versions)
- Add effects, shadows, or outlines
- Use on busy backgrounds without sufficient contrast
- Recreate or redraw the logo
- Use outdated versions

### Background Usage
- **Light Backgrounds**: Use standard color versions
- **Dark Backgrounds**: Use white/light versions with sufficient contrast
- **Complex Backgrounds**: Add subtle background treatment or use in a container

## Brand Applications

### Website Implementation
```html
<!-- Primary Navigation -->
<img src="images/logo-horizontal.svg" alt="PureSearch Logo" width="160" height="40">

<!-- Hero Section -->
<img src="images/logo-icon.svg" alt="PureSearch Icon" width="200" height="200">

<!-- Footer -->
<img src="images/logo-horizontal.svg" alt="PureSearch Logo" class="footer-logo">
```

### Favicon Implementation
```html
<link rel="icon" type="image/svg+xml" href="images/logo-icon.svg">
<link rel="icon" type="image/png" sizes="32x32" href="images/logo-icon.svg">
<link rel="apple-touch-icon" sizes="180x180" href="images/logo-icon.svg">
```

## Visual Elements

### Data Visualization Patterns
- **Flowing Streams**: Animated curves representing real-time data
- **Network Nodes**: Connected points showing distributed systems
- **Wave Patterns**: Representing continuous data flow
- **Hexagonal Grids**: Search indices and structured data

### Animation Guidelines
- **Duration**: 2-3 seconds for logo animations
- **Easing**: Ease-in-out for natural movement
- **Respect Motion Preferences**: Disable for users who prefer reduced motion
- **Purpose**: Enhance brand experience, not distract

## Brand Voice & Messaging

### Primary Taglines
- **Main**: "Built for New Zealand"
- **Extended**: "The Only Managed OpenSearch Service Built for New Zealand"
- **Positioning**: "Your Data. Your Cloud. Your Country."

### Key Messages
1. **Data Sovereignty**: "Your data never leaves New Zealand"
2. **Local Expertise**: "New Zealand-based team in your timezone"
3. **Catalyst Integration**: "Native integration with Catalyst Cloud"
4. **Enterprise Grade**: "Enterprise features without enterprise complexity"
5. **Open Source**: "No vendor lock-in, full OpenSearch power"

## File Formats & Export

### SVG (Primary)
- **Advantages**: Scalable, small file size, web-optimized
- **Usage**: Web, digital applications, vector graphics

### PNG (Backup)
- **Sizes**: 16px, 32px, 64px, 128px, 256px, 512px
- **Usage**: When SVG not supported, raster applications

### Print Applications
- **Vector**: SVG or PDF for print reproduction
- **Raster**: High-resolution PNG (300 DPI minimum)

## Brand Compliance

### Quality Control
- Always use official logo files from the brand package
- Ensure proper contrast ratios for accessibility (4.5:1 minimum)
- Test logos at various sizes before implementation
- Maintain consistent spacing and proportions

### Updates & Versions
- This brand system is version 1.0 (2025)
- All materials should use current brand assets
- Contact brand team for new applications or modifications

## Contact & Support

For questions about brand usage, additional assets, or implementation support:
- **Brand Guidelines**: This document
- **Asset Location**: `/images/` directory
- **Implementation**: See CSS variables in `styles.css`

---

**Brand System Created**: June 2025  
**Last Updated**: June 2025  
**Version**: 1.0

*This brand system embodies PureSearch's commitment to New Zealand's digital sovereignty while providing world-class search and analytics capabilities.* 