# Ice Mold Viewer

Interactive 3D viewer for a 12-cube clear ice mold prototype.

## Features

- **3D Visualization**: Rotate, zoom, and explore the mold design with Three.js
- **Multiple Views**: Perspective, top, front, and side views
- **Exploded View**: See how components separate
- **Technical Specs**: Complete dimensions and material specifications
- **2D Schematics**: Top-down and cross-section diagrams

## Deployment

This is a single-page static site that can be deployed to:
- Cloudflare Pages
- Netlify
- GitHub Pages
- Any static hosting service

### Deploy to Cloudflare Pages

1. Go to https://dash.cloudflare.com/
2. Navigate to **Workers & Pages** → **Create application** → **Pages**
3. Connect to GitHub and select the `iceproject` repository
4. Click **Save and Deploy**

Your site will be live at: `https://iceproject.pages.dev`

## Local Development

Simply open `index.html` in a web browser. No build process required.

## Technology

- Three.js for 3D rendering
- Pure HTML/CSS/JavaScript (no frameworks)
- Self-contained single file
