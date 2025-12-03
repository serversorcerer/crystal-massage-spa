# Assets Directory

This directory contains all visual assets for the Crystal Spa website, organized by type.

## Directory Structure

```
assets/
├── images/              # Production-ready images
│   ├── hero-massage.jpg # Hero section massage image (4096x2734px, 8.1MB)
│   └── logo-figma.png   # Logo exported from Figma (1609x533px, 61KB)
├── Logo.png             # Original logo file (if different from Figma export)
└── reference/           # Reference screenshots from Figma
    ├── Hero Text.png
    ├── Menu and Contact.png
    ├── Navigation.png
    └── index.html.png
```

## Image Assets

### Production Images (`images/`)

- **hero-massage.jpg**: High-resolution hero image showing a relaxing massage scene. Used in the homepage hero section.
  - Dimensions: 4096 × 2734px
  - Format: JPEG
  - Size: ~8.1MB
  - Usage: `<img src="assets/images/hero-massage.jpg">`

- **logo-figma.png**: Logo exported directly from Figma design.
  - Dimensions: 1609 × 533px
  - Format: PNG (with transparency)
  - Size: ~61KB
  - Usage: `<img src="assets/Logo.png">` (or update to use logo-figma.png if preferred)

### Reference Images (`reference/`)

These are screenshots from Figma used for reference during development. They are not used in the production website.

## Notes

- All production images are optimized and ready for web use
- The hero image is high-resolution for retina displays
- Logo should ideally be exported as SVG for better scalability (if available in Figma)
- Reference screenshots can be removed after development is complete

## Asset Sources

All assets were exported from the Figma design file via MCP integration.

