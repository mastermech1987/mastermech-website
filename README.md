# MasterMech Auto Care Ltd.
Static HTML/CSS/JavaScript website for Cloudflare Pages.

## Cloudflare Pages settings
- Repository: mastermech1987/mastermech-website
- Production branch: main
- Framework preset: None
- Build command: leave empty
- Build output directory: /
- Root directory: repository root

The current canonical domain is https://mastermech-website.pages.dev. When the custom domain is purchased and connected, replace this origin in canonical tags, structured data, Open Graph, sitemap.xml, robots.txt and the form redirect fields. Pages serves service HTML files on extensionless URLs; internal links and sitemap use those routes. A top-level 404.html prevents unmatched URLs from returning the homepage.

## Verification completed
All internal links, fragment targets, image assets, sitemap destinations, page H1 counts and JSON-LD parse correctly. Six source images were optimized to WebP. Placeholder five-star testimonials and unconfirmed business-hours schema were removed. Navigation remains available on small screens, with fixed call/directions buttons and reduced-motion support.

## Launch work still required
- Confirm business hours and current $70 oil-change offer details with the shop.
- Deploy through Cloudflare Pages and verify HTTPS, service routes and 404 responses.
- Connect the owned domain and check DNS, www behavior and canonical URLs.
- Perform browser/mobile visual checks on the live deployment.
- Verify domain ownership in Google Search Console and submit /sitemap.xml.
- Add the final HTTPS URL to the matching Google Business Profile.

Business: MasterMech Auto Care Ltd., 25 Derby St, Winnipeg, MB R2W 5K9; 204-415-7009.

## Vehicle inquiry form
The homepage posts name, email, optional phone/year, make, model, service and message through FormSubmit to mastermechauto10@gmail.com. Default CAPTCHA protection remains enabled, with an additional honeypot.

The inbox owner must activate the form using the FormSubmit email triggered by an initial submission. Then confirm a real test inquiry arrives and reply-to uses the submitter email. Email delivery has not yet been tested. Do not treat deployment alone as proof of email delivery.

When connecting the custom domain, update the form's _next and _url fields to the final HTTPS domain. The thank-you page is noindex and excluded from the sitemap.
