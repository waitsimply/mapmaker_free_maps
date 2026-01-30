# Contributing to Free Maps Repository

Thank you for your interest in contributing to this collection of free educational and journalistic maps!

## How to Contribute

### Suggesting Maps

If you'd like to suggest a map to be added to the collection:

1. Open an issue with the title "Map Request: [Map Description]"
2. Include details about:
   - Type of map (political, physical, thematic, etc.)
   - Geographic area covered
   - Intended use case
   - Any specific features needed

### Contributing Maps

To contribute a map directly:

1. **Create the map** using [mapmaker.io](https://mapmaker.io)

2. **Prepare your files:**
   - High-resolution map image (minimum 2000px on longest side)
   - Thumbnail version (400x400px max, under 100KB)
   - Use descriptive, SEO-friendly filenames with hyphens

3. **Follow naming conventions:**
   - Good: `southeast-asia-political-map.png`
   - Bad: `map1.png` or `IMG_001.png`

4. **Add metadata** to `maps-metadata.json`:
   ```json
   {
     "filename": "your-map-name.png",
     "title": "Descriptive Title",
     "description": "Detailed description of the map",
     "category": "world|continent|country|region|thematic|historical",
     "tags": ["tag1", "tag2", "tag3"],
     "altText": "Comprehensive alt text for accessibility",
     "resolution": "4000x2000",
     "format": "PNG",
     "dateAdded": "YYYY-MM-DD",
     "keywords": ["keyword1", "keyword2"]
   }
   ```

5. **Update sitemap.xml** if adding individual map pages

6. **Submit a pull request** with:
   - Map file in `/maps/` directory
   - Thumbnail in `/thumbnails/` directory
   - Updated `maps-metadata.json`
   - Clear PR description explaining the map and its use cases

## Quality Guidelines

### Image Requirements
- Minimum resolution: 2000px on longest side
- Maximum file size: 2MB (optimize when possible)
- Formats: PNG (preferred), SVG, or high-quality JPG
- Color mode: RGB

### Content Requirements
- Maps must be created using mapmaker.io
- Accurate geographical information
- Clear, readable labels and legends
- Appropriate for educational or journalistic use
- Free of copyrighted elements from other sources

### SEO Requirements
- Descriptive filenames with hyphens separating words
- Comprehensive alt text for accessibility
- Relevant keywords and tags
- Detailed descriptions

## Code of Conduct

- Be respectful and constructive in all interactions
- Focus on educational and journalistic value
- Ensure accuracy of geographical and political information
- Respect the Creative Commons BY 4.0 license terms

## Questions?

If you have questions about contributing, please open an issue or contact the repository maintainer.

---

All contributions will be licensed under CC BY 4.0, requiring attribution to mapmaker.io.
