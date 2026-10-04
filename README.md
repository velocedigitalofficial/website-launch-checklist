
# Website Launch Checklist

A practical checklist we run through before a business website goes live. Copy it into your own project notes and tick items off.

Maintained by [Veloce Digital](https://velocedigital.co), a web design and development agency.

## 1. Content and design
- [ ] Every page has a clear purpose and one main call to action
- [ ] No placeholder text, lorem ipsum or stock-photo watermarks left
- [ ] Contact details (email, phone, WhatsApp) are correct and clickable
- [ ] Legal pages exist: privacy policy, terms, and cookie notice if you use tracking
- [ ] Forms send to the right inbox and a test submission arrives
- [ ] 404 page exists and links back to the homepage

## 2. Mobile and accessibility
- [ ] Checked on a real mid-range phone, not only browser dev tools
- [ ] Tap targets are large enough and text is readable without zooming
- [ ] Images have meaningful `alt` text
- [ ] Text/background colour contrast is sufficient
- [ ] The whole site can be used with a keyboard only

## 3. Performance
- [ ] Images are compressed and served in modern formats (WebP/AVIF)
- [ ] Images have width/height set to avoid layout shift
- [ ] Fonts are limited, with a fallback stack
- [ ] No unused scripts; third-party widgets (chat, analytics) loaded last
- [ ] Run PageSpeed Insights on the homepage and one inner page, on mobile
- [ ] Check Core Web Vitals: LCP, INP and CLS

## 4. Technical SEO
- [ ] Every page has a unique `<title>` and meta description
- [ ] One `<h1>` per page, with a sensible heading order
- [ ] Canonical URL set on every page
- [ ] `robots.txt` allows crawling and is not blocking the whole site
- [ ] No leftover `noindex` tags from staging
- [ ] XML sitemap exists, lists only indexable URLs, and uses accurate `lastmod` dates
- [ ] Old URLs 301-redirect to new ones (single hop, no chains)
- [ ] Internal links point to final URLs, not redirects
- [ ] Open Graph and social share image set

## 5. Search Console and analytics
- [ ] Domain verified in Google Search Console
- [ ] Sitemap submitted
- [ ] Key pages inspected with URL Inspection and indexing requested
- [ ] Analytics installed and conversions (form, WhatsApp click, purchase) tracked
- [ ] Bing Webmaster Tools set up

## 6. Security
- [ ] HTTPS everywhere; HTTP redirects to HTTPS
- [ ] Security headers set (HSTS, X-Content-Type-Options, Referrer-Policy)
- [ ] Admin logins use strong, unique passwords and two-factor authentication
- [ ] CMS, plugins and dependencies are up to date
- [ ] Backups run automatically and a restore has been tested
- [ ] No API keys or secrets in the public code

## 7. Business basics
- [ ] Google Business Profile claimed and linked to the site
- [ ] Same business name, address and phone everywhere (NAP consistency)
- [ ] Email on your own domain, with SPF, DKIM and DMARC records
- [ ] Uptime monitoring switched on

## After launch (first 30 days)
- [ ] Check Search Console for crawl errors and indexing problems weekly
- [ ] Fix any 404s that appear
- [ ] Review which pages get impressions and improve their titles and descriptions
- [ ] Ask early customers for reviews

## License
Free to use and share. Attribution appreciated.
