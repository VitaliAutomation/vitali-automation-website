# Vitali Automation website preview v2 — asset path repair

This release keeps all website files at the repository ROOT so GitHub's browser uploader cannot separate CSS, JavaScript or logo paths.

## What changed

Every HTML page now loads `site.css`, `site.js` and `brand.svg` from the same folder as `index.html`. The broken v1 pages incorrectly requested `css/site.css`, `js/site.js` and `assets/brand.svg` although the GitHub upload flattened those assets.

## Upload to GitHub

1. Extract ZIP. Select **all files inside** the extracted folder (not the enclosing folder).
2. In `VitaliAutomation/vitali-automation-website`, choose **Add file → Upload files** and drag the files.    The HTML files should be updated in place.
3. Commit as `Fix website styles and asset paths`.
4. Visit `https://vitaliautomation.github.io/vitali-automation-website/` and press Ctrl+F5.

This preview contains `noindex,nofollow` and draft legal pages; do not link the production app until the legal terms and real store configuration are verified.
