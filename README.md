# Portfolio Website

A premium dark mode portfolio website with deep navy & gold color scheme, built with HTML, CSS, and vanilla JavaScript.

## Design Features

- **Deep Navy & Gold Dark Mode** - Professional color scheme with vibrant gold accents
- **Two-column layouts** - Image-heavy sections inspired by premium fintech design
- **Dark/Light section balance** - Alternating backgrounds for visual rhythm
- **Responsive design** - Works beautifully on mobile, tablet, and desktop
- **Smooth animations** - Hover effects, transitions, and modal interactions
- **No frameworks** - Pure HTML/CSS/JS for fast loading

## Color Palette

- **Deep Navy:** `#0a1628` (primary dark)
- **Navy Blue:** `#1e3a5f` (mid-tone backgrounds)
- **Vibrant Gold:** `#fbbf24` (accent, buttons, highlights)
- **Light Gold:** `#fcd34d` (hover states)
- **Slate:** `#0f172a` (dark section backgrounds)

## Files

- `index.html` - Main HTML structure with featured projects and about section
- `styles.css` - All styling with dark mode color scheme
- `script.js` - Interactive functionality (modals, smooth scrolling, animations)

## Customization Guide

### 1. Update Your Information

**In `index.html`:**

**Hero Section (lines 17-48):**
- Line 20: Change badge text from "✨ Open to New Projects"
- Line 21: Update your name and tagline
- Line 22: Modify subtitle
- Lines 25-35: Update stats (Years Experience, Engagement %, Campaigns)

**Featured Projects (lines 52-115):**
Each featured project has:
- Project image placeholder with upload instructions
- Project label, title, and description
- Highlight metrics (customize the numbers)
- Modal ID for detailed case study

**About Section (lines 170-220):**
- Line 173: Update intro paragraph
- Lines 180-182: Modify experience paragraphs
- Lines 192-217: Customize skills cards with your expertise

**Contact (lines 226-234):**
- Line 229: Update intro text
- Line 231: Change email address
- Line 232: Add your LinkedIn URL

### 2. Add Your Project Images

**Image Locations & Sizes:**

**Hero Image** (line 45)
```html
<!-- Replace placeholder with: -->
<img src="your-photo.jpg" alt="Your Name">
<!-- Recommended: 600x700px, professional headshot or workspace photo -->
```

**Featured Project 1 - Movember** (line 57)
```html
<img src="movember-campaign.jpg" alt="Movember Campaign">
<!-- Recommended: 800x600px, campaign visuals or presentation slides -->
```

**Featured Project 2 - Diversity Conference** (line 80)
```html
<img src="diversity-conference.jpg" alt="Diversity Conference">
<!-- Recommended: 800x600px, event materials or branding -->
```

**Additional Projects** (lines 128, 145)
```html
<img src="project3.jpg" alt="Project Name">
<!-- Recommended: 600x400px for each -->
```

### 3. Customize Modal Content

Each project has a detailed modal popup. Update in `index.html` starting at line 242:

**Modal Structure:**
- **The Brief** - Project context and objectives
- **My Role** - Your specific contribution
- **The Approach** - Strategy and execution
- **Results** - Measurable outcomes

### 4. Adjust Colors

**In `styles.css` (lines 10-24):**

To change the color scheme, update these CSS variables:
```css
--primary-color: #0a1628;     /* Main dark navy */
--accent-color: #fbbf24;      /* Gold accent */
--accent-light: #fcd34d;      /* Light gold */
--bg-dark: #0f172a;           /* Dark section backgrounds */
```

**Popular alternatives:**
- **Charcoal & Teal:** `--accent-color: #14b8a6;`
- **Navy & Purple:** `--accent-color: #8b5cf6;`
- **Forest & Sage:** `--primary-color: #1e3a28; --accent-color: #10b981;`

### 5. Customize Section Backgrounds

Current layout (dark/light balance):
- Hero: Dark navy
- Featured Project 1: White
- Featured Project 2: Dark navy (with padding)
- Additional Projects: Light grey (with dark cards)
- About Header: Dark navy
- About Content: Light grey
- About Skills: Dark navy
- Contact: Dark navy
- Footer: Darkest navy

To change a section background, update the CSS class background color.

## Deployment to GitHub Pages

### Initial Setup

1. **Create GitHub Repository**
   - Go to github.com and sign in
   - Click "New repository"
   - Name it: `yourusername.github.io` (use your actual GitHub username)
   - Make it Public
   - Don't add README/gitignore/license
   - Click "Create repository"

2. **Upload Files**
   - Click "uploading an existing file"
   - Drag and drop: `index.html`, `styles.css`, `script.js`
   - Add commit message: "Initial portfolio"
   - Click "Commit changes"

3. **Wait & Visit**
   - Wait 2-5 minutes for deployment
   - Visit: `https://yourusername.github.io`
   - Hard refresh if needed (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)

### Making Updates

**Method 1: Edit on GitHub**
1. Click on the file you want to update
2. Click pencil icon (Edit)
3. Make changes
4. Scroll down, add commit message
5. Click "Commit changes"
6. Wait 1 minute, hard refresh your site

**Method 2: Delete & Re-upload**
1. Click on file → trash icon
2. Commit deletion
3. Click "Add file" → "Upload files"
4. Upload new version
5. Commit changes

### Custom Domain (Optional)

To use `yourname.com` instead of `yourusername.github.io`:

1. Buy domain from Namecheap, Google Domains, etc. (£10-15/year)
2. In domain DNS settings, add A records:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. In GitHub: Settings → Pages → Custom domain
4. Enter your domain and enable "Enforce HTTPS"

## Page Structure

The portfolio follows this layout for optimal dark/light balance:

1. **Navigation** - Fixed header with smooth scrolling
2. **Hero** - Two-column intro with stats
3. **Featured Projects** - Large image + detailed content layouts
4. **Additional Projects** - Card grid for more work
5. **About** - Three-part section (dark-light-dark)
6. **Contact** - Simple CTA with email/LinkedIn
7. **Footer** - Minimal with copyright

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies
- Optimized CSS (under 100KB)
- Fast page load (<1 second)
- Smooth 60fps animations

## Tips

- **Images:** Use optimized JPG/PNG files (compress before uploading)
- **Copy:** Keep text concise - people skim portfolios
- **Projects:** Show 4-6 best projects, not everything
- **Updates:** Refresh content every 3-6 months
- **Testing:** Always check on mobile before sharing

## Troubleshooting

**Site not loading?**
- Wait 5 minutes after first deployment
- Check repository name matches: `yourusername.github.io`
- Verify files are in root directory (not in a folder)

**Old version showing?**
- Hard refresh: Cmd+Shift+R (Mac) or Ctrl+Shift+R (Windows)
- Clear browser cache
- Try incognito/private window

**Styling looks broken?**
- Check file names exactly match: `styles.css`, `script.js`
- Ensure files uploaded to root (not in subfolders)
- Check console for errors (F12 → Console tab)

**Modal not opening?**
- Verify `script.js` file is present
- Check modal IDs match between button and modal div
- Open console (F12) to check for JavaScript errors

## Design Credits

Inspired by premium fintech design patterns from Chip.uk and modern portfolio best practices.

## Questions?

This is a static site - no backend, no database, just clean HTML/CSS/JS. Perfect for showcasing your work without complexity.

Good luck with your portfolio!

