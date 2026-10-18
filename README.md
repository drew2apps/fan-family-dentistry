# Fan Family Dentistry website

The site for Fan Family Dentistry (Dr. Yunfei Fan, D.D.S., Santa Rosa): fanfamilydentistry.com.
A single static page. No build step.

## Files
- `public/` is the website: `index.html`, `images/`, `robots.txt`, `sitemap.xml`
- `public/_redirects` sends the old Homestead page addresses (services.html, contact.html and so on) to the matching section
- `wrangler.jsonc` tells Cloudflare to serve `public/`

## Hosting
GitHub repo `strobidev/fan-family-dentistry`, deployed by the Cloudflare Worker `fan-family-dentistry`
(Workers Builds: every push to `main` runs `npx wrangler deploy`).
Preview address: https://fan-family-dentistry.drew2apps.workers.dev

The domain is registered at Cloudflare. Email is Google Workspace: keep the 5 MX records and the
google-site-verification TXT record in Cloudflare DNS.

## Still to add
- 3 real patient reviews (with permission); the styles for them are already in `index.html` (`.reviews`)
- A photo of Dr. Fan (and the team)
- Confirm Sunday hours, the financing partner, Dr. Fan's Chinese name, and the Spanish and Chinese wording
- An appointment form that sends somewhere (for now the page offers call or email)
