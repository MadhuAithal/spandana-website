# Spandana NGO Trust — Website

Static six-page website for Spandana NGO Trust, built to host free on GitHub Pages.

## Pages
- `index.html` — Home
- `about.html` — Our Story
- `programs.html` — Programs
- `impact.html` — Impact
- `support.html` — Support Us (donate / volunteer)
- `contact.html` — Contact

## Before going live — replace these placeholders
1. **Photos** — add real images into `/images` and reference them (hero, stories). Source from the old site files or facebook.com/NGOSpandana.
2. **Impact stories** (`impact.html`) — swap the three placeholder stories for real scholarship-recipient stories.
3. **UPI QR + bank details** (`support.html`) — add the Federal Bank UPI QR image and fill account/UPI/IFSC.
4. **Email** (`contact.html`, `support.html`) — add the real email; connect the contact form (e.g. Formspree) or switch to a mailto link.
5. **Cloudflare Web Analytics** — paste your token snippet in the marked spot inside each page's `<head>` (or add via Cloudflare dashboard once the domain is proxied).

## Hosting (GitHub Pages)
1. Create a repository, upload these files.
2. Settings → Pages → deploy from `main` branch, root.
3. Site goes live at `https://<user>.github.io/<repo>/` — share this URL with trustees for review.
4. Once approved, set the custom domain `spandana.ngo` (add a `CNAME` file + DNS records).
5. Optional: put Cloudflare in front for SSL, speed, and built-in analytics.

## Notes
- No build step, no frameworks — plain HTML/CSS/JS. Fully crawlable and AI/agent friendly.
- Each page has its own title, meta description, canonical URL, and Open Graph tags.
- NGO schema (JSON-LD) is embedded on every page.
- `sitemap.xml` and `robots.txt` included.
