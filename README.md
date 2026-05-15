# Faith Ego Laundry Micro-Site

A lightweight, mobile-first landing page for Faith Ego Laundry & Dry Cleaning. The site is designed to convert visitors into WhatsApp leads using a simple basket estimator and WhatsApp order link.

## Features

- Hero section with clear call-to-action
- Services grid for the core laundry offerings
- Interactive booking estimator with plus/minus controls
- Live total price calculation
- One-click WhatsApp order message generation
- Mobile-first, fast, no-build setup

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Font Awesome via CDN

## Getting Started

1. Open [index.html](index.html) in a browser.
2. No installation or build step is required.
3. Edit the content directly in the HTML file if needed.

## How the Booking Estimator Works

- Add items using the plus and minus buttons.
- The basket summary updates automatically.
- The total estimated price updates in real time.
- Clicking **Send Order via WhatsApp** opens a pre-filled WhatsApp message using the required format:
  - `https://wa.me/2349030071786?text=[URL_ENCODED_MESSAGE]`

## Customization

You can update the following inside [index.html](index.html):

- Item names and prices in the JavaScript `items` array
- Service cards and icons
- Contact numbers in the footer and booking panel
- Brand colors in the Tailwind config
- The flyer image reference `faith.jpg`

## Brand Guidelines Used

- Primary colors: navy blue and lime green
- Backgrounds: white and light gray
- Typography: Inter, with a clean sans-serif fallback
- Motto: We wash more than just clothes, WE WASH WORRIES AWAY!

## Assets

The workspace includes [faith.jpg](faith.jpg), which can be used as the main flyer image or visual reference.

## Deployment

This is a static site, so it can be deployed to any static hosting platform, such as:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any basic web server

Upload [index.html](index.html) and [faith.jpg](faith.jpg) together so the hero image loads correctly.

## Notes

- The current WhatsApp destination uses the number from the PRD: 2349030071786.
- Total price formatting uses Nigerian Naira formatting.
- The page is responsive and touch-friendly for mobile users.
