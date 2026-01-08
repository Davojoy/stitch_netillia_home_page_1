# Netillia Website - Deployment Structure

## Entry Point
**`index.html`** - This is the main entry point for the website (Home page)

## File Structure (Flattened for Web Hosting)

```
stitch_netillia_home_page_1/
├── index.html              # Home page (entry point)
├── about.html              # About Us page
├── services.html           # Services page
├── case-studies.html       # Case Studies page
├── contact.html            # Contact page
├── testimonials.html       # Testimonials page
└── README-DEPLOYMENT.md    # This file
```

## Navigation Links

All navigation links have been updated to use the flat structure:

- **Home**: `index.html`
- **About Us**: `about.html`
- **Services**: `services.html`
- **Case Studies**: `case-studies.html`
- **Contact**: `contact.html`
- **Testimonials**: `testimonials.html`
- **Blog**: `#` (placeholder - page not yet created)

## Deployment Instructions

### Option 1: Static Web Hosting (Recommended)
Upload all `.html` files to your web hosting root directory. The server will automatically serve `index.html` as the default page.

**Supported Platforms:**
- Netlify
- Vercel
- GitHub Pages
- AWS S3 + CloudFront
- Any traditional web host (cPanel, etc.)

### Option 2: Local Testing
Use a local web server to test:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## Original Structure (Archived)

The original nested directory structure has been preserved in:
- `netillia_home_page/`
- `netillia_about_us_page/`
- `netillia_services_page/`
- `netillia_case_studies_&_projects/`
- `netillia_contact_page/`
- `netillia_testimonials_page/`

These can be deleted after confirming the flattened structure works correctly.

## SEO Considerations

All pages include:
- ✅ Proper `<title>` tags
- ✅ Semantic HTML5 structure
- ✅ Responsive meta viewport
- ✅ Clean, descriptive URLs
- ✅ Consistent navigation structure

## Next Steps

1. Test all navigation links locally
2. Deploy to your hosting platform
3. Set up custom domain (if applicable)
4. Configure SSL certificate
5. Submit sitemap to search engines
6. Set up analytics (Google Analytics, etc.)

---

**Last Updated**: January 8, 2026
**Structure**: Flattened for web hosting best practices
