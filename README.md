# Youth Press Project Website

A one-page website for the Youth Press Project.

## Replacing Images

The website currently uses SVG placeholder images that match the design. To replace them with your own images, simply add your images to the `assets/images/` folder with the following filenames (you can use .jpg, .png, or .svg formats):

### Favicon
- **File:** `assets/images/favicon.png` (or .ico)
- **Description:** The small icon that appears in browser tabs
- **Recommended size:** 32x32px or 64x64px PNG file

### Hero Background
- **File:** `assets/images/hero-background.jpg` (or .png, .svg)
- **Description:** The blurred background image for the hero section (a blur filter is applied automatically)
- **Current placeholder:** `hero-background.svg`
- **Recommended size:** 1920x500px or larger

### Feature Card Images
- **File 1:** `assets/images/feature-1.jpg` (or .png, .svg) - Free Journalism Workshops card
- **File 2:** `assets/images/feature-2.jpg` (or .png, .svg) - Student Press Rights card
- **File 3:** `assets/images/feature-3.jpg` (or .png, .svg) - Mentorship & Resources card
- **Current placeholders:** `feature-1.svg`, `feature-2.svg`, `feature-3.svg`
- **Recommended size:** Square images, 600x600px or larger

### Sponsor Logos
- **File 1:** `assets/images/sponsor-1.png` (or .svg) - YAB logo
- **File 2:** `assets/images/sponsor-2.png` (or .svg) - SJA logo
- **Current placeholders:** `sponsor-1.svg`, `sponsor-2.svg`
- **Recommended size:** Height of 60px, transparent background preferred

**Note:** When you add your images with the same filenames (but different extensions like .jpg or .png), you'll need to update the file extensions in `index.html` to match your image files.

## Running the Website

Simply open `index.html` in your web browser. No build process or server required.

## Customization

- Edit `styles.css` to modify colors, fonts, spacing, and layout
- Edit `index.html` to modify content and structure
- The website is fully responsive and will adapt to different screen sizes
