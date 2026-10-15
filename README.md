# PageFlow Agent — Meta App Website

Six-page responsive informational website for a Facebook Page video publishing app.

## Pages
- `index.html` — Home
- `services.html` — Services
- `about.html` — About
- `privacy-policy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `data-deletion.html` — Data Deletion Instructions

## Deploy
1. Upload all HTML files and the `assets` folder to any static HTTPS host, such as Netlify, Cloudflare Pages, GitHub Pages, or your own web hosting.
2. Ensure all pages are publicly reachable via HTTPS and not blocked by robots.txt or authentication.
3. Set your Meta App Dashboard URLs to the publicly hosted full URLs for `privacy-policy.html`, `terms.html`, and `data-deletion.html` (deletion *instructions* option, not callback).
4. Replace the app name and contact address with your real registered app information. Current contact address is `inamullahbaryar@gmail.com` — confirm it is the appropriate support and privacy contact.
5. Carefully update the legal pages so data collection, processing, providers, retention, and deletion statements exactly match the real app.
6. Ensure your actual automation backend securely supports the processes described before seeking Meta review.

## Customize
Edit `make.py` for shared brand/contact values or legal text, then execute `python make.py` to regenerate the six pages. You can also edit the generated HTML directly. Edit `assets/style.css` to change design colors.

## IMPORTANT
This package is a **public-facing informational/policy site**, not a Facebook login, OAuth backend, scheduler, token store, or video upload service. App Live status and Page publishing depend on Meta review, eligible permissions, secure OAuth/API implementation, and your actual app's compliance. Meta approval is not guaranteed.

Do not add Facebook App Secrets or access tokens to this static site.
