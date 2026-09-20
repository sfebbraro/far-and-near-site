FAR & NEAR — Website (deploy folder)
==========================================

This folder is the complete, self-contained website, ready to publish.
To view it locally, open index.html in a browser. To publish it (GitHub Pages),
upload the ENTIRE CONTENTS of this folder to your repo root so index.html sits
at the top level. Full steps are in ../SETUP-GUIDE.md.

Contents
--------
index.html            Homepage (cover, three stories, offerings, about, follow)
sardinia-sicily.html  Feature: Three Weeks in Sardinia and Sicily
alaska.html           Feature: Nine Days in Alaska
minam.html            Feature: Where Time Stands Still (Minam, Oregon)
assets/img/<story>/   Responsive photos (WebP + JPG, 5 widths each) + manifest.json
logo/                 Wordmark, muted wordmark, and favicon files
.nojekyll             Tells GitHub Pages to serve all files as-is

Connected services
------------------
- Contact form: the on-site pop-up posts into your Google Form; responses land
  in your linked Google Sheet. Offering choice is tagged on each submission.
- Google Analytics (GA4) is installed on every page (ID G-4F1HR6CWZ9).
- Follow along links to instagram.com/farandnear.travel.

Still to do at launch
---------------------
- Add your site link to the Instagram bio once the domain is live.
- Optional: point a custom domain at the site (SETUP-GUIDE.md, section 5).
