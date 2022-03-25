# A checklist for all sites that are going live
The checklist that is used when a site is going live

## Frontend
- [ ] Minified assets
- [ ] Layout is preserved after PurgeCSS 
- [ ] Remove all `console.log` lines in scripts
- [ ] 404 template

## Images
- [ ] Images are optimized
- [ ] Use webp whenever possible
- [ ] Provide width and heigth for `img` elements whenever possible
- [ ] ...

## Meta
- [ ] Title & meta description
- [ ] Open graph w/ image
- [ ] Favicon
- [ ] ...

## a11y
- [ ] Run Firefox diagnostic
- [ ] SVGs have title or role presentation
- [ ] ...

## Server
- [ ] SSL certificate installed
- [ ] Check `http` redirects to `https`
- [ ] Check `www` redirects `non-www` domain
- [ ] Setup browser cache nginx/apache
- [ ] Redirect old urls if necessary
- [ ] Ensure no mixed content
- [ ] ...

## Services
- [ ] Analytics is running in production
- [ ] GDPR & cookies
- [ ] Setup google search console
- [ ] ...
