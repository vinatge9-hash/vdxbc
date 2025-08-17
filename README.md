# Paws & Care — Dog Care Website

This repository contains a simple, responsive multi-page dog care website prototype built with HTML, Tailwind CSS, and vanilla JavaScript. It includes pages for Home, About, and Contact and demonstrates common features for a small service business.

Files

- index.html — Home page with hero, service cards, tips, and newsletter subscription.
- about.html — Company story, mission, and team profiles.
- contact.html — Contact form, location image, and opening hours.

Features

- Responsive layout built with Tailwind CSS (CDN) and Google Fonts.
- Mobile-friendly header and menu.
- Newsletter subscription (simulated, stores subscriber in localStorage).
- Contact form with client-side validation and simulated send.

Images

- All images in the HTML files use a placeholder pattern expected by the environment: the src attribute uses the special format {{unsplash: a detailed description of the image}}. Replace these placeholders with real Unsplash URLs or your own assets when you deploy the site.

How to use

1. Open ./index.html in a browser to view the site.
2. Navigate between pages using the header links.
3. Use the contact form on contact.html to simulate sending a message.

Customization

- Tailwind classes are used throughout. Edit classes directly in the HTML to adjust layout and styling.
- To change fonts, update the Google Fonts link in the <head> of each HTML file.
- To wire forms to a backend, replace the simulated send behaviors in the JavaScript with fetch/XHR calls to your API.

Notes

- This is a starter prototype intended for demos and internal use. For production, consider optimizing assets, adding accessibility improvements, and integrating server-side form handling and security measures.

Enjoy building a happier world for dogs and their people with Paws & Care!
