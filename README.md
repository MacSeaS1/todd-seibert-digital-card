# Todd Seibert Digital Business Card

Cloudflare Workers package for Todd Seibert's Macomb County Planning and Economic Development digital business card.

## Deploy through the Cloudflare dashboard

1. Sign in to the Macomb County Cloudflare account.
2. Open **Workers and Pages** and select **Create**.
3. Create a new Worker named `todd-seibert-digital-card`.
4. Open the Worker's code editor.
5. Replace the starter code with everything in `src/index.js`.
6. Select **Deploy**.

The QR code and downloadable contact file automatically use the Worker's final URL. No URL needs to be manually changed after deployment.

## Deploy with Wrangler

Install Node.js, open this folder in Terminal and run:

```bash
npm install
npm run deploy
```

Wrangler will ask you to sign in to Cloudflare if needed. The project name and entry point are already configured in `wrangler.toml`.

## Included features

- Macomb County and Planning and Economic Development branding
- Official Macomb County logo
- Todd's office and cell phone links
- Email and LinkedIn links
- Macombgov.org/ped link
- Office address and map link
- Downloadable vCard contact file
- QR code that automatically follows the deployed Worker URL
- Responsive layout for iPhone, Android and desktop
