# Faith Ego Laundry Micro-Site

A lightweight, mobile-first landing page for Faith Ego Laundry & Dry Cleaning. The site is designed to convert visitors into WhatsApp leads using a simple basket estimator and a fast contact flow.

## Features

- Hero section with primary booking CTA
- WhatsApp contact button in the hero and a floating WhatsApp button
- Services grid for laundry, dry cleaning, home service, industrial services, and collect & deliver
- Interactive booking estimator with plus/minus controls
- Live total price calculation
- Pre-filled WhatsApp order message
- Favicon support and Google Analytics tag
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

## How the Booking Flow Works

- Add items using the plus and minus buttons.
- The basket summary updates automatically.
- The total estimated price updates in real time.
- Clicking any WhatsApp button opens a pre-filled WhatsApp message using the required format:
  - `https://wa.me/2349030071786?text=[URL_ENCODED_MESSAGE]`

## Customization

You can update the following inside [index.html](index.html):

- Item names and prices in the JavaScript `items` array
- Service cards and icons
- Contact numbers in the footer and booking panel
- Brand colors in the Tailwind config
- The favicon reference `favicon.png`
- The flyer image reference `faith.jpg`

## Brand Guidelines Used

- Primary colors: navy blue and lime green
- Backgrounds: white and light gray
- Typography: Inter, with a clean sans-serif fallback
- Motto: We wash more than just clothes, WE WASH WORRIES AWAY!

## Assets

The workspace includes [faith.jpg](faith.jpg), which is used as the main flyer image.
The workspace also includes [favicon.png](favicon.png), which is used as the browser favicon.


## Deployment

This is a static site, so it can be deployed to any static hosting platform, such as:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any basic web server

Upload [index.html](index.html), [faith.jpg](faith.jpg), and [favicon.png](favicon.png) together so the page loads correctly.

## Notes

- The current WhatsApp destination uses the number from the PRD: 2349030071786.
- Total price formatting uses Nigerian Naira formatting.
- The page is responsive and touch-friendly for mobile users.
