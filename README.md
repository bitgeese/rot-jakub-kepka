# Simple Landing Page

A minimalist landing page with TailwindCSS JIT CDN and Stripe buy buttons.

## Features

- TailwindCSS JIT CDN for on-the-fly CSS generation
- No build step required
- Responsive design
- Impact font
- Black background with red accent color
- Integrated Stripe buy buttons

## Usage

Simply open the `dist/index.html` file in your browser. Since we're using Tailwind JIT CDN, there's no need to build any CSS files. The Tailwind styles are generated on-the-fly by the CDN.

## Customization

- Update the content in `dist/index.html`
- Modify Tailwind configuration in the `<script type="tailwind-config">` section of the HTML
- Add custom CSS styles by adding a `<style>` tag in the HTML

## Deployment

For production, you can simply upload the `dist/index.html` file to any web server. No build step is required. 