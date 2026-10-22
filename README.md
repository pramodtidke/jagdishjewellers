# Jagdish Jewellers — static website

Premium multi-page website concept by Markase, built with HTML, CSS and vanilla JavaScript for GitHub Pages. No build step or backend is required.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` from this folder and visit `http://localhost:8000`. Some browsers restrict features when opened as file URLs, so the local server is preferred.

## Deploy to GitHub Pages
1. Create a GitHub repository and upload all files and folders from this project.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**. Select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish. Test every page at `https://USERNAME.github.io/REPOSITORY/` including links, images, WhatsApp, map and mobile navigation.
5. The site uses relative asset paths and separate `.html` pages, so it supports repository subpaths.
6. For a custom domain, enter it in Settings → Pages, configure the DNS records recommended by GitHub for your domain provider, wait for DNS to propagate, then enable **Enforce HTTPS** when available. Confirm with Markase how the first-year domain arrangement in the agreement will be registered/managed; GitHub Pages hosting is static and a `github.io` URL is not a custom domain.

## Configure before launch
Edit `assets/js/site-config.js` to verify the phone number/address, change the WhatsApp number, add exact official social profile URLs, and optionally add a form endpoint. Do not place secrets in frontend code. Contact form currently opens WhatsApp with a prefilled message; the user must press Send. GitHub Pages does not process form submissions itself.

## Replace demo photos
Replace the remote demo image URLs in the HTML with approved, optimized client photographs. See `ASSET_REPLACEMENT_GUIDE.md`. Current images are illustrative and do not represent confirmed inventory or actual store photography.

## Test checklist
- [ ] All six pages and `404.html` load on the published subpath.
- [ ] Mobile navigation works with touch and keyboard.
- [ ] Call and WhatsApp links use the owner-verified number.
- [ ] Google Maps pin/address is correct.
- [ ] Gallery category filters and lightbox work.
- [ ] Enquiry validation works and WhatsApp opens with expected details.
- [ ] Replace sitemap/robots placeholder domain, add canonical URL if desired, and verify social URLs.
- [ ] Confirm hours, real categories, privacy wording, and contact details with owner.


## Reliability updates
- All decorative jewellery artwork is bundled locally under `assets/images/`, so the pages do not depend on third-party image hosts. Replace these illustrations with approved real store photography when available.
- The contact page has no enquiry form; customers can use the phone and WhatsApp links.
- Instagram and Facebook links are shown in the footer. Replace platform home URLs with the verified official store profile URLs in `assets/js/site-config.js` before launch.
- Confirm phone, address, map pin and store hours with the owner before publishing.
