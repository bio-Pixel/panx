# Xu Pan Academic Homepage - Setup Instructions

## What's been done:
- Profile information updated with Xu Pan's details
- Education background added
- Awards added
- Key publications created as markdown files
- News item for job market announcement added
- Social icons copied from panx-main directory

## What you need to add:

### 1. University Logos
Add the following logo files to `assets/images/badges/`:
- `tsinghua.png` - Tsinghua University logo
- `hmu.png` - Harbin Medical University logo

### 2. CV File
Upload your CV file and update the `cv_link` in `_data/profile.yml`:
```yaml
cv_link: https://your-username.github.io/cv.pdf
```

### 3. Additional Publications
Add more publications to `_publications/` directories by year. Each publication should be a markdown file with format:
```yaml
---
title:          "Paper Title"
date:           YYYY-MM-DD 00:01:00 +0800
selected:       true
pub:            "Journal Name"
pub_date:       "YYYY"
abstract: >-
  Brief summary of your paper.
authors:
  - Author 1
  - Author 2
  - Author 3
links:
  Paper: https://doi.org/...
  Code: https://github.com/...
---
```

### 4. Cover Images
Add publication cover images to `assets/images/covers/` if you want publication thumbnails.

### 5. Portrait Photo
Replace `assets/images/photos/portrait.jpg` with your actual photo.

## Running Locally:

1. Install Jekyll:
```bash
gem install bundler jekyll
bundle install
```

2. Run local server:
```bash
bundle exec jekyll serve
```

3. Open http://localhost:4000 in your browser

## Deploying to GitHub Pages:

1. Create a new repository named `panx9623.github.io`
2. Push this directory to that repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at https://panx9623.github.io
