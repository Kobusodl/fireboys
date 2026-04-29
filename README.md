# Fireboys Integrated Solutions Website

A clean one-page static website for Fireboys Integrated Solutions. This version is suitable for GitHub Pages hosting.

## Files

- `index.html` — website structure and content
- `styles.css` — responsive styling
- `script.js` — mobile menu, scroll effects, footer year, and sector flip cards
- `assets/fireboys-logo.jpeg` — logo image
- `assets/sectors/README-images.txt` — list of sector image names to use
- `robots.txt` and `sitemap.xml` — basic SEO files

## Sector images

To show photos on the Industries / Sectors flip cards, save images in `assets/sectors/` using these exact file names:

- `commercial-retail.jpg`
- `mining-resources.jpg`
- `industrial-petrochemical.jpg`
- `government-public.jpg`
- `residential-developments.jpg`
- `nationwide-projects.jpg`

Recommended image size: 1200 x 800 px or larger, landscape JPG, compressed for web.

If an image is missing, the website will still work and show a dark gradient background instead of the photo.

## GitHub Pages setup

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

## Notes

The quote buttons use email links and the WhatsApp buttons use the Fireboys phone number. A proper form can be added later using Formspree, Tally, Basin, Google Forms, or a custom backend.
