# Showcase Section Documentation

## Overview
The showcase section presents your research trajectory in three key areas based on your Nature paper (2024):

1. **Tumor Vascular Atlas** - Single-cell dissection of tumor vascular heterogeneity
2. **PDAC Ecosystem Heterogeneity** - Large-scale analysis of pancreatic cancer microenvironment
3. **Mechanism and Translational Insights** - From spatial biology to clinical applications

## Files Created

### HTML Structure
- `_includes/widgets/showcase_section.html` - Main showcase section with your images

### CSS
- `assets/css/showcase.css` - Custom styling for the showcase section

### Images
- `assets/images/showcase/` - Directory containing:
  - `TVMmap.png` - Tumor vascular microenvironment map
  - `Angiogenesis.png` - Angiogenesis mechanism figure
  - `sprouting.gif` - Angiogenesis animation

## Integration

The showcase is already integrated into your homepage:
1. Added `show_showcase: true` to `_data/display.yml`
2. Added CSS to `_layouts/default.html`
3. Added section to `index.html`

## Features

- Responsive design using Bootstrap grid system
- Professional academic styling
- Images from your Nature paper publication
- Clean typography with Lato font
- Hover effects on cards
- DOI citation for your Nature paper

## Next Steps

1. **Add links** to your publication:
   - Uncomment the link placeholders in HTML
   - Add URLs to your paper, journal, and preprint

2. **Add more details**:
   - Update descriptions as needed
   - Add citations for related work
   - Include acknowledgments if desired

3. **Optimize images** (if needed):
   - Ensure images are optimized for web
   - Consider adding alt text for accessibility

## Citation
Your Nature paper should be cited as:
Pan et al. (2024). A single-cell atlas of tumour vasculature. Nature. DOI: 10.1038/s41586-024-07698-1