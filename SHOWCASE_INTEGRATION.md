# Showcase Integration Guide

## Overview
This guide explains how to integrate the showcase section into your academic homepage.

## Files Created

### 1. HTML Structure
- **File**: `_includes/widgets/showcase_section.html`
- **Purpose**: Contains the complete showcase section with placeholder images
- **Usage**: Include this in your main homepage file

### 2. Custom CSS
- **File**: `assets/css/showcase.css`
- **Purpose**: Provides styling for the showcase section
- **Usage**: Add to the default layout header

### 3. Asset Checklist
- **File**: `showcase_asset_checklist.md`
- **Purpose**: Lists all required images and specifications
- **Usage**: Reference when preparing your visual assets

## Integration Steps

### Step 1: Add CSS to Layout
In `_layouts/default.html`, add the showcase CSS link after the existing CSS:

```html
<head>
    <!-- ... existing CSS ... -->
    <link rel="stylesheet" href="{{ '/assets/css/showcase.css' | relative_url }}">
</head>
```

### Step 2: Add Showcase to Homepage
In `index.html`, add the showcase section where you want it to appear:

```html
{% if site.data.display.homepage.show_showcase %}
    {% include widgets/showcase_section.html %}
{% endif %}
```

### Step 3: Enable in Configuration
In `_data/display.yml`, add the showcase toggle:

```yaml
homepage:
  # ... existing settings ...
  show_showcase: true
```

### Step 4: Prepare Assets
1. Create the placeholder directory: `assets/images/placeholder/`
2. Add placeholder images with the names listed in `showcase_asset_checklist.md`
3. Prepare your final images according to the specifications
4. Replace placeholder images with final assets

## Asset Directory Structure
```
assets/
└── images/
    └── placeholder/
        ├── vascular_single_cell_atlas.png
        ├── angiogenesis_schematic.png
        ├── pdac_ecosystem_main_figure.png
        ├── pancosmos_logo.png
        └── mechanism_or_translation_figure.png
```

## Customization Notes

### Text Content
- All text is easily editable in `showcase_section.html`
- Modify titles, subtitles, and descriptions as needed
- Update the PANCOSMOS description if needed

### Layout Adjustments
- The section is responsive and uses Bootstrap grid system
- Adjust column classes (e.g., `col-lg-6`) for different layouts
- Modify spacing by changing the `py-5` and `mb-5` classes

### Color Scheme
- The section uses white background (default Bootstrap)
- Custom colors can be added to `showcase.css`
- Currently follows the site's Lato font scheme

### Links
- Commented out link placeholders are ready for activation
- Add your paper links, resource links, etc. as needed

## Next Steps
1. Integrate the CSS into your layout
2. Add the HTML to your homepage
3. Create the placeholder directory and images
4. Enable the showcase in your configuration
5. Prepare final assets according to the checklist