# CCIS WEEK 2026 – Email (HTML/CSS)

HTML + CSS only email with a **terminal theme** for CCIS WEEK 2026.

## Colors (terminal palette)

| Hex       | Usage        |
|----------|--------------|
| `#232518` | Background   |
| `#ABFFC1` | Mint accent (title) |
| `#6BF279` | Green (borders)    |
| `#74EDCA` | Teal (theme line, QR border) |

## Contents

- **Logo** – Left side (expects `assets/css_logo_transparent_1-15e349a7-9bcb-40b8-b592-af83cb23e81f.png`).
- **CCIS WEEK 2026** and theme: *When Minds Meet, Wherever We Are*.
- **QR code** – Right side; sample from [QR Server API](https://goqr.me/api/). Replace the `img` `src` with your own QR image or link when sending.

## Setup

1. Create an `assets` folder and add the logo with the filename above, or change the logo `src` in `index.html` to your file path.
2. For real campaigns, use **absolute URLs** for all images (logo and QR) so they load in email clients.

## Usage

Open `index.html` in a browser to preview. Use as the body of your email or paste into your email tool (e.g. Mailchimp, SendGrid) and ensure images are hosted and linked with full URLs.
