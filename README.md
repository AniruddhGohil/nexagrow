# NexaGrow — Digital Marketing Agency Website

A fast, SEO-optimized, fully static website for NexaGrow Digital Marketing Agency.

## 📁 Project Structure

```
nexagrow/
├── index.html          # Main homepage (SEO-optimized)
├── robots.txt          # Search engine crawl rules
├── sitemap.xml         # XML sitemap (update when adding pages)
├── css/
│   └── style.css       # All styles (CSS variables, responsive, animations)
├── js/
│   └── main.js         # All interactivity (nav, FAQ, counters, form, cursor)
└── images/
    ├── logo-icon.svg       # Logo lightning bolt icon
    ├── icon-seo.svg        # SEO service icon
    ├── icon-social.svg     # Social Media icon
    ├── icon-performance.svg # Performance Marketing icon
    ├── icon-search.svg     # Search Marketing icon
    ├── icon-meta.svg       # Meta/Facebook Ads icon
    ├── icon-google-ads.svg # Google Ads icon
    ├── icon-display.svg    # Display Ads icon
    ├── icon-target.svg     # Target icon (Why Us)
    ├── icon-data.svg       # Data icon (Why Us)
    ├── icon-speed.svg      # Speed/clock icon (Why Us)
    └── icon-shield.svg     # Shield icon (Why Us)
```

## 🚀 Hosting on GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site is live at `https://yourusername.github.io/nexagrow/`

## 🌐 Custom Domain

Update the `canonical` URL and `sitemap.xml` with your real domain before going live.

## 📍 Future Geo-Location Pages

To add city/location pages for SMBs:
1. Create a `/pages/` or `/locations/` folder
2. Duplicate `index.html` as template
3. Update page title, H1, meta description, and content for each city
4. Add each URL to `sitemap.xml`

Example: `/digital-marketing-new-york.html` or `/locations/london/`

## ✏️ Customization Checklist

- [ ] Replace `hello@nexagrow.com` with your real email
- [ ] Replace phone number with your real contact
- [ ] Update pricing if needed
- [ ] Add real client logos in `/images/`
- [ ] Add real case study data/images
- [ ] Create a real `og-image.png` (1200×630px) in `/images/`
- [ ] Update `sitemap.xml` domain from `nexagrow.com` to your domain
- [ ] Update `robots.txt` sitemap URL
- [ ] Update Schema.org structured data in `<head>`

## 🎨 Color Palette

| Color   | Hex       | Usage             |
|---------|-----------|-------------------|
| Blue    | `#0057FF` | Primary brand     |
| Amber   | `#FF8C00` | Accent / CTA      |
| Emerald | `#00C48C` | Success / tags    |
| Ink     | `#09090b` | Dark backgrounds  |
| Surface | `#f8f8fb` | Section alternate |

## 📦 No Build Step Required

Pure HTML + CSS + Vanilla JS — no npm, no webpack, no dependencies.
Just open `index.html` in a browser or push to GitHub Pages.
