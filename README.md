# VouchAI — AI Financial Automation (static site)

This repo contains a single-page marketing site for **VouchAI** built with Tailwind CDN. It's ready to publish on **GitHub Pages**.

## Files
- `index.html` — complete landing page (hero, features, how-it-works, pricing, contact).

## How to publish on GitHub Pages
1. Create a new repository (e.g., `vouchai-site`) on GitHub.
2. Add `index.html` and `README.md` to the repo and push.
3. In repo Settings → Pages, choose branch `main` and folder `/ (root)`. Save.
4. Your site will be available at `https://<username>.github.io/<repo>/` within a minute.

## Customization
- Replace the Lottie URL in `<lottie-player src="...">` with your animation JSON.
- Swap placeholder images/mockups with real screenshots in the `features` section.
- Replace alert-based demo forms with your scheduling / signup integration (Calendly, HubSpot, Zapier webhook).
- Add analytics (GTAG) and meta tags for SEO as needed.

## Notes
- This is a static marketing page — for real demos or signups, connect forms to your backend or a form service.
- Tailwind is loaded via CDN for simplicity. If you prefer a production setup, use Tailwind CLI or Next.js with a build pipeline.

Enjoy — push to GitHub and make it live!
