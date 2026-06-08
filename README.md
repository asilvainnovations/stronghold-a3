# Stronghold A3 Security Agency — PWA

**Eastern Visayas' Premier "Zero-Liability" Security Partner**

## 🚀 Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages → Source**: Select `GitHub Actions`
3. The included workflow (`.github/workflows/deploy.yml`) auto-deploys on push to `main`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

## 🔐 Operations Portal Password

Default password: `stronghold2026`

> ⚠️ **Change before production deployment** — update `APP.password` in `js/app.js`

## 📁 File Structure

```
stronghold-a3/
├── index.html              # PWA entry point + SEO meta
├── manifest.json           # PWA manifest
├── sw.js                   # Service Worker (offline support)
├── css/
│   └── main.css            # Full design system
├── js/
│   └── app.js              # SPA router, all pages, BSC data
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions auto-deploy
```

## 📄 Pages

### Public (No Authentication)
- **Home** — Hero, Zero-Liability Moat, Core Competencies, Capability Statement, Phase Preview
- **Services** — Full service catalog, 3-Bridge Tech Stack, Cloud SMS CTA
- **About Us** — Vision/Mission/Values images, Guiding Principles, Capability Statement
- **Contact** — Form with service inquiry, contact info, service area

### Internal (Password Protected: `stronghold2026`)
- **BSC Dashboard** — Interactive Balanced Scorecard with all 4 perspectives, collapsible rows, KPI gauges, tooltips, Strategy Map image
- **Strategy Map** — Full 4-Phase Stronghold Sequence with phase cards + strategy map image
- **Cloud SMS** — Embedded iframe to `https://resilient-secure-mobile.deploypad.app/`

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary | `#0A1628` Deep Navy |
| Accent | `#3B82F6` Bright Blue |
| Text | `#FFFFFF` White |
| Body | `#CBD5E1` Gray-300 |
| Display Font | Oswald (Google Fonts) |
| Body Font | Roboto Condensed (Google Fonts) |

## ✅ SEO Features

- Structured data (JSON-LD LocalBusiness schema)
- Open Graph meta tags
- Twitter Card meta tags
- Semantic HTML5 headings
- Alt text on all images
- `rel="manifest"` for PWA
- `theme-color` meta tag

## 🛡️ PWA Features

- Service Worker with cache-first strategy
- Offline fallback to `index.html`
- Installable on mobile and desktop
- App icons linked from Supabase storage

## 📊 BSC Data Source

Balanced Scorecard data is embedded in `js/app.js` from the Google Sheets:
`https://docs.google.com/spreadsheets/d/1YHN02Kwzy0FFMVV7ctl0NK_q-jWlUs7wqFHQvDyszvs`

All 19 objectives across 4 perspectives (Financial, Customer, Internal Processes, Learning & Growth) are included with phase, timeline, owner, KPI, baseline, and target.

## 🔗 External Assets

| Asset | URL |
|-------|-----|
| Logo | Supabase Storage (Stronghold Logo.png) |
| Zero-Liability Moat | Supabase Storage (Zero-Liablity Moat.png) |
| Vision-Mission-Values | Supabase Storage (VMV.png) |
| Guiding Principles | Supabase Storage (Guiding Principles.png) |
| Strategy Map | Supabase Storage (The Stronghiold Sequence-2.png) |
| Cloud SMS | https://resilient-secure-mobile.deploypad.app/ |
