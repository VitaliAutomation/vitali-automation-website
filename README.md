# Vitali Automation Website — V3 with original logo and actual app screenshots

This is a complete replacement for the separate new GitHub Pages website repository `VitaliAutomation/vitali-automation-website` (not the old `vitaliautomation.github.io` repository).

All files are FLAT and go directly into the repository root. Upload files directly, not an outer folder. GitHub may ask to overwrite existing website files; confirm the change only in the NEW repository.

Main changes:
- Official user-supplied Vitali Automation blue/grey industrial-control logo replaces the illustrated V across header/footer.
- Actual Android Recipe Assistant development screenshots; no mockups or AI recreations.
- Recipe Assistant hero showcases the real cookbook homepage and full recipe page.
- Swipeable/scrollable gallery of 8 selected actual screenshots.
- Homepage features a real screenshot thumbnail.
- Existing pages, original navigation, prices and legal DRAFT notices retained.

Screenshots selected: cookbook home, AI-generated lasagne, creamy-chicken recipe detail, My Recipes collection, Kitchen AI, Weekly Meal Planner, Shopping List, Photo Recipe Import.

Please review legal drafts and pricing before publishing to vitaliautomation.com. The root-level `robots.txt` and `noindex` meta tags remain for preview. No domain DNS settings changed.

All image source files are user-supplied. Logo has only been trimmed of external white margins. App screenshots have only been resized and WebP-compressed; actual screen content is preserved.


## V4 screenshot layout hotfix — 8 November 2026

V3's new screenshot classes could render with an older cached `site.css` file in Edge/GitHub Pages, causing images to display at natural height. **All HTML pages now load the new `site-v4.css` filename**. The Recipe Assistant page also includes tiny critical image-size rules as a safeguard.

Upload **every extracted file at the repository root**, including the NEW `site-v4.css` and the eight `app-*.webp` files. Do not place the site into a subfolder. The old `site.css` can remain; V4 pages use `site-v4.css`.

Verify desktop and mobile layout, scroll through the image carousel, and do not connect the custom domain until legal pages are final.
