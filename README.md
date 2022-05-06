# A checklist for all sites that are going live
The checklist that is used when a site is going live

## Frontend
- [ ] Minified assets
- [ ] Layout is preserved after PurgeCSS 
- [ ] Remove all `console.log` lines in scripts
- [ ] 404 template
- [ ] Use `font-dispay: swap` when possible

## Images
- [ ] Images are optimized
- [ ] Use `webp` whenever possible
- [ ] Provide `width` and `heigth` for `img` elements whenever possible
- [ ] Provide `srcset` whenever necessary

## Meta
- [ ] Title & meta description
- [ ] Open graph w/ image
- [ ] Favicon
- [ ] Provide `rel="alternate"` and `hreflang` attributes for multilingual sites

## a11y
- [ ] Run Firefox diagnostic and solve all detected issues
- [ ] SVGs have title or role presentation
- [ ] Buttons have and accessible name
- [ ] Image elements have `alt` attributes
- [ ] Links have a discernible name
- [ ] Sufficient contrast ratio is desirable
- [ ] Test keyboard navigation and fix all detected issues

## Server
- [ ] SSL certificate installed
- [ ] Check `http` redirects to `https`
- [ ] Check `www` redirects `non-www` domain
- [ ] Setup browser cache nginx/apache
- [ ] Redirect old urls if necessary
- [ ] Ensure no mixed content

## SEO and analytics
- [ ] Analytics is running in production
- [ ] GDPR & cookies
- [ ] Setup Google Search Console
- [ ] Provide a `sitemap.xml`
