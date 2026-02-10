# Image Assets Guide

## Required Images

### Root Level
| File | Dimensions | Purpose |
|------|------------|---------|
| `banner.jpg` | 1200x630px | OG image for social sharing |
| `hero-video.mp4` | 1920x1080px | Homepage hero background (optional, can use image) |
| `about-photo.jpg` | 800x1000px | About/Studio page main photo |
| `profile-1.jpg` | 400x400px | Team member photo 1 |
| `profile-2.jpg` | 400x400px | Team member photo 2 (optional) |

### /portfolio/ - Project Images
Each project needs:
- `project-X-cover.jpg` - 1200x800px - Main cover image
- `project-X-detail-1.jpg` - 1200x800px - Detail shots (as many as needed)

Example structure:
```
portfolio/
├── project-1-cover.jpg
├── project-1-detail-1.jpg
├── project-1-detail-2.jpg
├── project-2-cover.jpg
├── project-2-detail-1.jpg
└── ...
```

### /articles/ - Blog Post Images
Each article needs:
- `article-X-cover.jpg` - 1200x630px - Featured image

### /studio/ - Facility Images
- `studio-1.jpg` through `studio-5.jpg` - 1200x800px - Workspace/facility photos

### /logos/ - Brand Assets
- `logo.png` - Primary logo (transparent background)
- `logo-light.png` - Light version for dark backgrounds
- `logo-dark.png` - Dark version for light backgrounds
- Any partner/certification logos

## Image Guidelines

1. **Quality**: Use high-resolution images (minimum 72dpi, prefer 150dpi)
2. **Format**: JPG for photos, PNG for logos/graphics with transparency
3. **Compression**: Optimize for web (use tools like TinyPNG or Squoosh)
4. **Aspect Ratios**:
   - Portfolio: 3:2 landscape
   - Articles: 1.91:1 (social media optimal)
   - Profiles: 1:1 square
5. **File Size**: Keep under 500KB per image for performance

## Placeholder Images

While developing, you can use placeholder services:
- https://placeholder.com
- https://picsum.photos

Example: `<img src="https://picsum.photos/1200/800" />`
