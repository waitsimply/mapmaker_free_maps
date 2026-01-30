# Maps Directory

This directory contains all map image files organized for easy discovery and SEO optimization.

## File Naming Convention

Use descriptive, SEO-friendly filenames with hyphens separating words:

**Good examples:**
- `world-political-map-2026.png`
- `north-america-physical-map.svg`
- `europe-population-density-map.png`
- `africa-climate-zones-map.jpg`

**Avoid:**
- `map1.png`
- `IMG_001.png`
- `untitled.png`

## Required Metadata

For each map added, create an entry in `maps-metadata.json` with the following structure:

```json
{
  "filename": "usa_states_blank_2000w.png",
  "title": "USA States Blank Map for Web & Slides",
  "description": "Blank USA states map with state boundaries only. Includes all 50 states with Alaska and Hawaii insets. Ideal for web, slides, and classrooms.",
  "category": "usa",
  "tags": ["usa", "map", "states", "blank"],
  "altText": "Blank outline map of the United States showing all 50 states with state boundaries only.",
  "resolution": "2000x1250",
  "format": "PNG",
  "dateAdded": "2026-01-29",
  "keywords": ["usa map", "free usa map", "usa states", "usa blank map"]
}
```

## Categories

Use one of these standardized categories:
- `world` - World maps
- `continent` - Continental maps (Africa, Asia, Europe, etc.)
- `country` - Country-specific maps
- `region` - Regional maps (Middle East, Caribbean, etc.)
- `thematic` - Thematic maps (population, climate, resources, etc.)
- `historical` - Historical maps

## Image Specifications

- **Minimum resolution:** 2000px on the longest side
- **Recommended formats:** PNG for raster, SVG for vector
- **File size:** Optimize images to be under 2MB when possible
- **Color mode:** RGB for digital use

## Creating Thumbnails

For each map in `/maps/`, create a corresponding thumbnail in `/thumbnails/`:
- Same filename as the original
- Maximum dimensions: 400x400px
- Format: JPG or PNG
- Optimized for web (under 100KB)
