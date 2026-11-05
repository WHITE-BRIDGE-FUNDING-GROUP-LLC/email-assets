# White Bridge Funding — Email Asset Manifest

This repository holds White Bridge Funding marketing image assets and email HTML sources.

## V6.3 campaign

- Original portrait: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/v6.3/hero-portrait.jpg
- Editable email HTML source: [templates/whitebridge-v6.3-email.html](templates/whitebridge-v6.3-email.html)

## Shared image assets

- WhatsApp: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/whatsapp-icon.png
- Calendar: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/calendar-icon.png
- Website: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/website-icon.png
- Instagram: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/instagram-icon.png
- LinkedIn: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/linkedin-icon.png
- Brand logo: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/shared/logo-original.png

## Historical V6.2 sources

- Desktop: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/v6.2/hero-desktop.jpg
- Mobile: https://raw.githubusercontent.com/WHITE-BRIDGE-FUNDING-GROUP-LLC/email-assets/main/images/white-bridge/v6.2/hero-mobile.jpg

## Usage notes

- All email image references should be public HTTPS `<img src="...">` URLs. Never embed images as `data:image` or depend solely on CSS background images.
- Do not use private GitHub repositories for publicly visible email assets.
- Version assets under their own folders to avoid old email designs unexpectedly changing.
- Public GitHub raw-file links are suitable for internal testing; for high-volume production campaigns, move hosted assets to a proper CDN, branded static-asset domain, or Brevo media library and update the email HTML.
- Public repository: do not commit recipient/customer data, API keys, or other secrets.
