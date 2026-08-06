# West Industrial Services Website Launch Guide

## What is ready

- Redesigned mobile-friendly website
- Dedicated apostille information page
- Apostille request and callback form
- Privacy notice and service disclaimer
- Search titles, descriptions, canonical links, structured data, robots.txt, and sitemap.xml
- Current GitHub Pages address preserved until a custom domain is purchased

## Important domain finding

`westindustrialservices.com` is already registered by another party. As of August 6, 2026, these alternatives returned no active `.com` registration in the Verisign registry lookup:

1. `westindustrialservicesllc.com` — recommended because it exactly matches the legal business name
2. `westindustrialva.com` — shorter and location focused
3. `westindustrialapostille.com` — useful only if apostille becomes a separate brand

Domain availability can change at any time. Complete the purchase before adding a CNAME file or changing search URLs.

## Activate the apostille form

The website uses FormSubmit to deliver form entries to `westindustrialservicesllc@gmail.com`.

1. After the updated site is live, open `apostille-request.html`.
2. Submit one test request using your own information.
3. Open the activation email sent by FormSubmit to the West Industrial Gmail account.
4. Click the activation/confirmation link.
5. Submit a second test request.
6. Confirm the second request arrives in the inbox and does not go to Spam.

Do not ask customers to upload identity documents through this form. It intentionally collects basic intake details only.

## Connect a purchased domain to GitHub Pages

After purchasing the final domain:

1. In the GitHub repository, open **Settings → Pages**.
2. Under **Custom domain**, enter the full domain without `https://`, then save.
3. Add a root-level file named `CNAME` containing only the chosen domain.
4. At the domain registrar, add these four `A` records for the root (`@`):
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
5. Add a `CNAME` record for `www` pointing to `spkhqxh6bs-dotcom.github.io`.
6. Remove conflicting `A`, `AAAA`, or forwarding records for `@` and `www`.
7. Wait for DNS verification, then select **Enforce HTTPS** in GitHub Pages.
8. Replace every current GitHub Pages URL in the site with the final `https://yourdomain.com` URL, including canonical links, structured data, the form `_next`, `robots.txt`, and `sitemap.xml`.

Always confirm GitHub's current Pages DNS instructions before changing live DNS records.

## Submit the site to Google

1. Open Google Search Console at `https://search.google.com/search-console`.
2. Add a **Domain property** using the purchased domain.
3. Copy Google's TXT verification record into the domain's DNS settings.
4. After verification, open **Sitemaps** and submit `https://yourdomain.com/sitemap.xml`.
5. Use **URL inspection** for the homepage and `apostille.html`, then request indexing.
6. Create or claim a Google Business Profile using the same business name, phone, service area, and website.
7. Do not create fake addresses, reviews, or service claims. Google discovery normally develops over time and is not guaranteed.

## Final checks before advertising

- Test the website on a phone and computer.
- Test every phone, email, menu, and form link.
- Activate FormSubmit and confirm a real request reaches the inbox.
- Purchase and connect the final domain before printing it on business materials.
- Keep apostille pricing as quote-based until the service-fee schedule and third-party costs are documented.
- Review the privacy notice and disclaimer with qualified counsel if the service expands into legal, immigration, translation, or document-storage work.
