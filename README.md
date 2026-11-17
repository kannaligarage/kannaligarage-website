# KANNALI Garage — GitHub-ready public website

A lightweight static website for KANNALI Garage, SpareX and GarageOS. No npm install, build command, backend or database is needed.

## Files

- `index.html` — home
- `platforms.html`, `sparex.html`, `garage.html`, `garageos.html` — product and service pages
- `about.html`, `development.html`, `contact.html` — company pages
- `privacy.html`, `terms.html` — draft public legal pages
- `style.css`, `app.js`, `assets/` — styling, navigation and supplied official logo
- `sitemap.xml`, `robots.txt`, `CNAME` — search engine and GitHub Pages configuration

## Test locally

Open `index.html` in a browser. For a more realistic test, run `python -m http.server 8080` in this folder and open `http://localhost:8080`.

## Deploy to GitHub Pages (only if your current site uses GitHub Pages)

1. **Back up your existing repository first** (download ZIP or create a branch). Do not overwrite it without checking the existing host.
2. Create a new repository for testing, or use a new branch of the existing website repository.
3. Upload the **contents of this folder** to the repository root (not the ZIP file itself).
4. In GitHub → Settings → Pages, set source to **Deploy from a branch**, select the publishing branch and `/ (root)`.
5. Test the GitHub Pages preview URL and check all pages and mobile layout.
6. Only when ready, configure the custom domain `www.kannaligarage.com` in Pages. `CNAME` is included for this purpose.
7. At your domain registrar, configure DNS to match the actual GitHub Pages instructions. **Do not change DNS if your existing site uses another host until you have identified the existing configuration.**
8. Enable **Enforce HTTPS** when GitHub makes it available. Test both `https://www.kannaligarage.com` and `https://kannaligarage.com`; set the apex redirect at the DNS/hosting level as appropriate.

If your existing website uses Vercel, Netlify, AWS or another provider, upload this static website to that provider instead and **do not use the GitHub Pages DNS steps**.

## Required checks before publishing

- Confirm the legal business name and founding date on the site and AWS application match the registration documents. These have intentionally **not been invented** in the website.
- Verify `support@kannaligarage.com` is active and monitored; replace if necessary.
- Verify workshop address and phone number, including any postal code.
- Review the privacy and terms drafts for your actual hosting, analytics and data practices; seek legal review.
- Confirm all product status labels are truthful.
- If you add a contact form, payment, analytics, cookies or tracking later, update privacy notices and implement appropriate consent and security.
- Confirm ownership and right to publish the supplied KANNALI logo.

## AWS Activate

This website is designed to provide clear company identity, accurate product status and publicly accessible pages. **AWS Activate approval is not guaranteed**. AWS independently evaluates eligibility. Ask AWS support about the previous rejection and ensure the application details are consistent with your website.

## CEO message

The homepage and About page include a CEO message and the supplied portrait (`assets/ceo-portrait.jpg`). Before publishing, obtain the CEO’s approval of the draft statement and replace “Office of the CEO” with the confirmed name and designation if desired. The portrait should only be used with the pictured person’s permission.
