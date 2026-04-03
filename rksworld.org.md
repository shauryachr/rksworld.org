# Assets Folder

This folder contains all the images and media files for the portfolio website.

## Structure

### Profile Images
- `profile/` - Professional headshots and personal photos
- `profile/main-profile.jpg` - Main profile picture for hero section

### Background Images
- `backgrounds/` - Background images for different sections
- `backgrounds/hero-bg.jpg` - Hero section background
- `backgrounds/expertise-bg.jpg` - Expertise section background

### Gallery Images
- `gallery/` - Images for the carousel/gallery section
- `gallery/research-1.jpg` - Research related images
- `gallery/academic-1.jpg` - Academic event photos
- `gallery/awards-1.jpg` - Awards and recognition photos

### Icons and Logos
- `icons/` - Small icons and logos
- `logos/` - Organization and institution logos

## Adding New Images

1. Place images in the appropriate subfolder
2. Use descriptive names (e.g., `research-lab-2023.jpg`)
3. Optimize images for web (use .jpg for photos, .png for graphics)
4. Keep file sizes reasonable (under 500KB for most images)

## Usage in Components

Import images in your React components like this:
```typescript
import profileImage from "@/assets/profile/main-profile.jpg";
```
