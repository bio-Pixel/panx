# Showcase Section Documentation

## Overview
The showcase section presents your research trajectory in three key areas:
1. **Tumor Vascular Atlas** - Single-cell dissection of tumor vascular heterogeneity
2. **PDAC Ecosystem Heterogeneity** - Large-scale analysis of pancreatic cancer microenvironment
3. **Mechanism and Translational Insights** - From spatial biology to clinical applications

## Files Created

### HTML Structure
- `_includes/widgets/showcase_section.html` - Main showcase section with placeholders

### CSS
- `assets/css/showcase.css` - Custom styling for the showcase section

### Assets
- `assets/images/placeholder/` - Directory with SVG placeholder images

### Documentation
- `showcase_asset_checklist.md` - Detailed requirements for final images
- `showcase.json` - Original specifications for the showcase

## Integration Steps

The showcase is already integrated into your homepage. To enable/disable it:
1. Edit `_data/display.yml`
2. Set `show_showcase: true` or `false`

## Next Steps

### 1. Replace Placeholders
You need to replace the placeholder SVG images with your actual publication figures:

1. **vascular_single_cell_atlas.png**
   - Replace with your vascular atlas figure
   - Format: PNG or SVG
   - Dimensions: 1200x800px minimum

2. **angiogenesis_schematic.png**
   - Replace with angiogenesis schematic or model
   - Format: PNG or SVG
   - Dimensions: 1200x800px

3. **pdac_ecosystem_main_figure.png**
   - Replace with your PDAC ecosystem figure
   - Format: PNG
   - Dimensions: 1200x800px

4. **pancosmos_logo.png**
   - Replace with PANCOSMOS logo
   - Format: PNG with transparency or SVG
   - Dimensions: 300x100px

5. **mechanism_or_translation_figure.png**
   - Replace with ADA2-TLS mechanism figure
   - Format: PNG
   - Dimensions: 1400x600px

### 2. Enable Links
Uncomment and add your publication links in the showcase HTML:
```html
<!-- <a href="#" class="btn btn-outline-primary btn-sm me-2">Paper</a> -->
```

### 3. Update Content
Edit the text in `showcase_section.html` to match your specific work.

## Design Notes

- The section is responsive and uses Bootstrap grid system
- Each block has a clear visual hierarchy
- Placeholder images are SVG for crisp scaling
- The time stamp shows when the section was last updated

## Preview
You can view the showcase section by accessing your homepage directly. The section will appear after your bio section and before the news section.