# Zero Inspection website

A responsive static website with no build step or dependencies. Contact links go directly to WhatsApp, phone and email. No prices or daily job capacity are included.

## Files

- `index.html`: content and search metadata
- `styles.css`: responsive design
- `script.js`: mobile menu and footer year
- `assets/logo.jpeg`: supplied company logo

Open `index.html` locally to review. Upload these files to the repository root, keeping the assets folder structure intact.

## Hosting

Use GitHub to store the source. GitHub Pages has restrictions on running an online business: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

Cloudflare Pages supports GitHub-connected static sites:
https://developers.cloudflare.com/pages/get-started/git-integration/

Select this repository, choose no framework, use `exit 0` as the build command and `.` as the output directory. Confirm the preview before configuring a domain.

## Domain

The intended domain is `www.zero-inspection.com`. Its registration/expiry has not been verified. Check the WordPress.com account that purchased it before changing DNS or renewing. Never share your account password.

To connect a Cloudflare Pages custom domain, follow:
https://developers.cloudflare.com/pages/configuration/custom-domains/

Add the custom domain in the hosting dashboard before creating its DNS record. Using the root domain with Cloudflare Pages requires Cloudflare nameservers. Preserve any existing mail records when changing DNS.

## Content maintenance

WhatsApp/phone: +601155823072
Email: zeroinspection55@gmail.com

The property graphic and report overview are illustrations, not customer photographs or actual inspection results. Visitors can switch the full page between English, Simplified Chinese and Bahasa Melayu. The selected language is remembered in this browser when local storage is available. WhatsApp enquiry messages change with the selected language. The approved inspection overview is included, with website text labels that translate with the page. Facebook, Instagram and TikTok profile links are supplied by the business. Nationwide home and business internet application assistance is listed separately from inspection services.


## Search setup

English, Chinese and Malay have static pages at /, /zh/ and /ms/. Canonical URLs, language alternatives, robots.txt and sitemap.xml currently target https://www.zero-inspection.com/. Confirm that this is the final live hostname before deployment. Submit the sitemap in Google Search Console after the domain is connected. No search ranking or indexing is guaranteed.
