# Rimrock Mobile Dentistry website

Static site: index.html, postop.html, refer.html, style.css, postop-pain-schedule.png.

## Publish with GitHub Pages
1. GitHub > New repository > name it `rimrock-site` (public).
2. Upload these files to the repo root (Add file > Upload files).
3. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at https://YOUR-USERNAME.github.io/rimrock-site/
5. Custom domain: Settings > Pages > Custom domain, then add the DNS records GitHub shows at your registrar. Turn on "Enforce HTTPS".

## Before going live
- Replace every yellow [PLACEHOLDER] (phone, email, bio, service area).
- Create a free form at formspree.io and replace YOUR_FORM_ID in index.html and refer.html.
- Dr. Hong reviews the post-op text and the pain medicine schedule picture (postop-pain-schedule.png).
- Confirm the services list (extractions, Botox) matches your license and insurance.
- Make a QR code of the postop.html address for the handout.
- Keep the financial dashboard OFF this public repo.

## Adding the post-op videos
1. Upload each video to YouTube and set visibility to Unlisted.
2. Copy the 11-character ID from the video address (the part after `v=`).
3. In postop.html, paste it into the matching `data-yt=""`, for example `data-yt="AbC123xyz_0"`.
4. Empty IDs show "Video coming soon." Do not show patients or faces without written consent.
