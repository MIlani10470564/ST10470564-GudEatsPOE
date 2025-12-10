# GudEats Website Project

Developer: Milani Mviko  
Date Completed: November 2025   
Project: Web Development POE

---

## Overview

GudEats is a multi-page restaurant website showcasing recipes, meal ideas, and an enquiries form.  
The project demonstrates knowledge of HTML, CSS, and JavaScript, as well as implementation of SEO, page speed, and basic web security practices.

---

## Folder Structure

GudEats/
│
├── index.html
├── about-us.html
├── contact-us.html
├── gallery.html
├── recipe.html
├── enquiries.html
│
├── css/
│ └── style.css
│
├── js/
│ └── enquiry-submit.js
│
├── Assets/
│ ├── images/
│ └── audio/
│
├── robots.txt
├── sitemap.xml
└── README.md


---

## Design and Colour Scheme

| Element | Colour | Hex Code |
|----------|---------|----------|
| Background | #000042 |
| Text | #f3f6f4 |
| Recipe Cards and Buttons | #72a5d3 |

---

## Image Licensing

All images used in this project are licensed for free commercial use from [Pexels](https://www.pexels.com/).  
Each image (for example, burger, pizza, and sushi) was sourced from Pexels to comply with image licensing requirements.

---

## Enquiries Form

The enquiries form on `enquiries.html` uses [Formspree](https://formspree.io/) to send messages directly to the developer’s email address.

Example form:

```html
<form action="https://formspree.io/f/yourformid" method="POST">
  <input type="text" name="name" required placeholder="Your Name">
  <input type="email" name="email" required placeholder="Your Email">
  <textarea name="message" required placeholder="Your Enquiry"></textarea>
  <button type="submit">Send Enquiry</button>
</form>
SEO Files
robots.txt
txt
Copy code
User-agent: *
Allow: /

Sitemap: https://www.example.com/sitemap.xml
Host: https://www.example.com
sitemap.xml
The sitemap lists all major pages to help search engines index the website efficiently.

Page Speed Optimization
Images were compressed using TinyPNG.


CSS and JS files were minified.

JavaScript is loaded using the defer attribute.

Preconnect tags were added to speed up font and asset loading.

Tested with Google Lighthouse for performance improvements.

Security Measures
Each HTML page includes a Content Security Policy (CSP) meta tag:

html
Copy code
<meta http-equiv="Content-Security-Policy"
  content="
    default-src 'self';
    connect-src 'self' https://formspree.io;
    form-action 'self' https://formspree.io;
    img-src 'self' data: https:;
    script-src 'self';
    style-src 'self' 'unsafe-inline';
    font-src 'self' https://fonts.gstatic.com;
    upgrade-insecure-requests;">
Other security headers:

X-Frame-Options: DENY

X-Content-Type-Options: nosniff

Referrer-Policy: no-referrer-when-downgrade

Permissions-Policy: geolocation=(), microphone=()

HTTPS is enforced when hosted online.

Deployment
The site is suitable for hosting on:

GitHub Pages

Netlify

Vercel

Place robots.txt and sitemap.xml in the site root.
Ensure all image and page paths are relative (e.g., gallery.html).

https://github.com/MIlani10470564/ST10470564-GudEatsPOE.git
References

Formspree. (n.d.) Formspree – Contact form for static sites. Available at: https://formspree.io/
 (Accessed: 3 November 2025)

Google. (n.d.) Google Lighthouse – Web performance and SEO tool. Available at: https://developer.chrome.com/docs/lighthouse
 (Accessed: 3 November 2025)

Max Themes. (n.d.) B-Chef – Restaurant HTML Template. Available at: https://www.max-themes.com/
 (Accessed: 3 November 2025)

Pexels. (n.d.) Free stock photos & videos you can use everywhere. Available at: https://www.pexels.com/
 (Accessed: 3 November 2025)

TinyPNG. (n.d.) Compress PNG and WebP images intelligently. Available at: https://tinypng.com/
 (Accessed: 3 November 2025)

W3C. (n.d.) Robots Exclusion Standard (robots.txt). Available at: https://www.w3.org/TR/robots/
 (Accessed: 3 November 2025)

W3C. (n.d.) Extensible Markup Language (XML) Sitemap Protocol. Available at: https://www.sitemaps.org/protocol.html
 (Accessed: 3 November 2025)

