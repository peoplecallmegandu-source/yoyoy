# Ram Bhakti — Devotional Website for Lord Rama

This repository contains a modern, responsive multi-page devotional website dedicated to Lord Rama. The site is built using plain HTML, JavaScript and Tailwind CSS classes used directly in the markup.

Key features
- Multi-page site: index.html, about.html and contact.html, linked by relative paths (./about.html, ./contact.html).
- Full-width, fluid layout: all main wrappers use `w-full` and `max-w-none` to ensure the content fills the viewport width on all devices.
- Tailwind CSS via CDN for utility-first styling.
- Google Fonts used (Playfair Display for headings, Inter for body). Font names are included as comments at the top of each HTML file per project instructions.
- Interactive elements: mobile navigation toggle, gallery with filters and lightbox modal, contact form validation and simulated donation flow.
- Images use platform-resolvable placeholders in the format `https://images.unsplash.com/photo-1715929602107-8d3d4d410ec2?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw5fHxkZXRhaWxlZCUyMGRlc2NyaXB0aW9ufGVufDB8MHx8fDE3NTUyNjE0NDh8MA&ixlib=rb-4.1.0&q=80&w=1080`. The platform will fetch high-quality visuals for those descriptions.

Files
- index.html — Home page with hero image, quick links, gallery (filterable) and lightbox.
- about.html — Biography, key episodes, teachings and festivals related to Lord Rama.
- contact.html — Contact form for satsang/volunteer/donation enquiries, donation simulation and location image.
- README.md — This file.

How to use
1. Download all files into a single folder.
2. Open `index.html` in a modern browser (Chrome, Firefox, Safari). No server is required for basic usage.

Customizing
- Fonts: update the Google Fonts link in each HTML file and update the comment lines at the top if needed.
- Images: replace any `https://images.unsplash.com/photo-1618102230742-c0c41176e8df?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw1fHwuLi58ZW58MHwwfHx8MTc1NTI0MjE2NXww&ixlib=rb-4.1.0&q=80&w=1080` placeholders with your own image URIs or base64 data URIs if you have specific images.
- Content: edit the HTML files directly to change text, add more gallery items, or add more pages.

Accessibility & Notes
- Interactive controls have simple keyboard support (lightbox: arrow keys / Esc) and reasonable ARIA-friendly structure.
- The design uses fluid containers to respect the guideline that the website content fills the full width of the viewport.

License
This example site is provided for demonstration and devotional informational purposes. Customize and reuse as needed.
