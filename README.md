# Ali's Bolton Plastering Services — editable Netlify website

This version keeps the single-page website design but adds an editor at `/admin/` using Decap CMS.

## What you can edit without coding

- Business name, phone number, email, WhatsApp message, Facebook links
- Hero text and hero photo
- Services
- About section and bullet points
- Gallery photos and captions
- Areas covered
- Reviews
- Contact text and service-area note
- SEO title and description

## Files

- `index.html` — the live website
- `content/site.json` — all editable website content
- `admin/index.html` — the admin editor page
- `admin/config.yml` — Decap CMS editor setup
- `images/uploads/` — photos uploaded through the admin panel
- `netlify.toml` — Netlify settings

## How to put it on Netlify

1. Put these files in a GitHub repository.
2. In Netlify, create a new site from that GitHub repository.
3. Build settings:
   - Build command: leave blank
   - Publish directory: `.`
4. After the site is live, go to Netlify → your site → Identity.
5. Enable Identity.
6. Under Identity settings, enable Git Gateway.
7. Invite yourself as a user under Identity.
8. Open `https://YOUR-SITE.netlify.app/admin/` and log in.
9. Edit the content and upload photos. Saving in the admin panel commits changes to GitHub and Netlify redeploys the site.

## Important

The admin page will not save properly until Netlify Identity and Git Gateway are enabled for the deployed Netlify site.

If your real domain is `alisboltonplastering.co.uk`, set it in Netlify and keep the Website URL field as `https://alisboltonplastering.co.uk/`.
