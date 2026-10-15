# Fan Family Dentistry website

The new site for Fan Family Dentistry (Dr. Yunfei Fan, D.D.S., Santa Rosa).
A single static page: `index.html`. No build step.

## Status
Preview only. `index.html` carries `noindex` and `robots.txt` blocks search engines
until the real photos and reviews are in and the domain points here.

## Hosting
GitHub repo `drew2apps/fan-family-dentistry` connected to a Cloudflare Pages project.
Cloudflare settings: framework preset None, build command empty, output directory `/`.
Every push to `main` deploys to https://fan-family-dentistry.pages.dev.

## Before launch
- Real photos of Dr. Fan, the team and the office; 3 real patient reviews (with permission)
- Confirm Sunday hours, the financing partner, Dr. Fan's Chinese name, and the Spanish and Chinese wording
- Make the appointment form send somewhere (it only shows a "please call" note today)
- Remove the preview banner, the `noindex` tag and `robots.txt`
- Point fanfamilydentistry.com at the Cloudflare Pages project
