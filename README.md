# Ali's Bolton Plastering Services - GitHub Pages Version

This version is designed to be hosted on GitHub Pages, not Netlify.

## What changed

- Removed Netlify Identity / Decap dependency.
- Kept Pages CMS editing through `.pages.yml`.
- Main hero image is now sized for a 946 x 400 px sign image.
- Logo can be uploaded as a square transparent PNG.
- The separate gallery section was removed.
- Each What We Do service card now has its own vertical 3:4 slideshow for 480 x 640 px photos.
- Reviews now use one Facebook review collage image sized for 1272 x 1024 px.
- Service area now supports a 718 x 561 px map image and editable city list.
- Contact buttons are now consistent: red phone, green WhatsApp, blue Facebook.
- Email button was removed.
- The final service area note was removed from the contact section.

## How to update the live website

1. Replace the existing files in your GitHub repository with the files in this package.
2. Make sure `index.html`, `.pages.yml`, `.nojekyll`, `content/site.json`, and the `images` folder are at the top level of the repo.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch: `main`.
6. Choose folder: `/ (root)`.
7. Save.

## How to edit content/photos

Use Pages CMS:

1. Go to https://app.pagescms.org
2. Sign in with GitHub.
3. Open your website repository.
4. Edit **Website content**.
5. Save/commit changes.
6. GitHub Pages will update the website after it publishes.

## Image sizes to upload

- Logo: square PNG, 1:1 aspect ratio, transparent background preferred.
- Main hero/sign image: 946 x 400 px.
- Service slideshow photos: 480 x 640 px vertical, 3:4 aspect ratio.
- Reviews collage: 1272 x 1024 px.
- Map image: 718 x 561 px.
- About/job image: 1385 x 1847 px.

## Important

The old `/admin/` page is no longer needed. Use Pages CMS instead.
