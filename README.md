# SugarPhilippines.com Website

Static, mobile-first website for a B2B wholesale sugar supplier in the Philippines.

## Quick Start
Open `index.html` in a browser. For local server (recommended):

```bash
# any simple server works
python -m http.server 8080
# then visit http://localhost:8080
```

## Structure
```
/ (root)
  index.html
  about.html
  locations.html
  contact.html
  /products
    index.html
    busco-standard.html
    busco-white.html
    busco-raw.html
    mitrphol.html
    passi.html
  /assets
    /css/styles.css
    /js/main.js
  sitemap.xml
  robots.txt
```

## Update Contact Details
Search & replace the following values with real business details:
- Phone: `+63 917 123 4567`
- WhatsApp: `https://wa.me/639171234567`
- Email: `sales@sugarphilippines.com`

## Form Handling
The quote form uses Formspree placeholder:
```
action="https://formspree.io/f/your-form-id"
```
Replace with your form endpoint or a backend handler.

## Performance Budget
- Target: **<2s load time**
- Keep images optimized and below 150KB each
- Avoid heavy JS libraries (current JS is minimal)

## Deployment
Upload the folder to your web host or deploy on Vercel/Netlify as a static site.
