# Naseeb Transportation Website

## Files
- `index.html` — Home page (Hero, Services, Why Us, Quote Form, Instagram, Footer)
- `contact.html` — Contact Us page (Info, Form, Map, Footer)
- `style.css` — Shared stylesheet for both pages
- `logo.png` — **Place your logo file here** (rename it to logo.png)

## Deployment to GitHub Pages

1. Create a new GitHub repository (e.g. `naseeb-transportation`)
2. Upload all 4 files to the root of the repository
3. Go to **Settings → Pages → Source → Deploy from branch (main)**
4. Site will be live at: `https://yourusername.github.io/naseeb-transportation/`
5. Add a `.nojekyll` file (empty file) to the root to avoid build issues

## Contact Form Setup (Formspree)

The forms use Formspree to handle submissions without a backend:
1. Go to https://formspree.io and create a free account
2. Create a new form and copy your form ID
3. Replace `YOUR_FORM_ID` in both `index.html` and `contact.html` with your actual Formspree ID
   - Search for: `formspree.io/f/YOUR_FORM_ID`
   - Replace with: `formspree.io/f/xabcdefg` (your actual ID)

## Instagram Feed (Live Posts)

To show a live Instagram feed on the Home page:
1. Go to https://behold.so (free plan available)
2. Connect your @naseeb_transportation Instagram account
3. Copy the embed code they provide
4. In `index.html`, find the `<div class="insta-embed-note">` section
5. Replace that div with your Behold embed code

## Logo
- Place your `logo.png` file in the same folder as the HTML files
- The site will automatically display it in the header
- If the image doesn't load, it falls back to a styled text logo

## Color Reference
- Red/Orange: #CC3300
- Black: #1a1a1a
- Off-white: #f5f5f5
