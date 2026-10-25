ERROR POINT Technologies

Official website of ERROR POINT Technologies, offering courses, internships, final-year projects, business projects, paper publication and placement support for college students in Bangalore and Tamil Nadu.

Live site: https://error-point.pages.dev

Tagline: Pinpoint Problems. Deliver Solutions.

Pages
Page	File	Address
Home	index.html	/
About	about.html	/about
Services	services.html	/services
Courses	courses.html	/courses
Contact	contact.html	/contact
Tech
Plain HTML, CSS and JavaScript. No framework and no build step.
Each page is a standalone file with its content already written into the HTML, so search engines can read it without running JavaScript.
Hosted on Cloudflare Pages, deployed automatically from this repository.
Dark theme with orange accents, fully responsive (desktop, tablet, phone).
Repository structure
/
├── index.html                      Home page
├── about.html                      About page
├── services.html                   Services page
├── courses.html                    Courses page
├── contact.html                    Contact page with enquiry form
├── logo.png                        Logo used for search results (structured data)
├── og-image.png                    1200x630 preview image for link sharing
├── sitemap.xml                     List of pages for search engines
├── robots.txt                      Crawler rules and sitemap location
└── google4f031f9ac4effb0f.html     Google Search Console verification file
Features
Animated hero with a live "find the error" code window
Services, courses, FAQ and learning-approach sections
Contact form with validation
WhatsApp button with a ready-written message
Email and WhatsApp shortcuts under the "Get Started" button
Instagram, WhatsApp and email links in the footer
SEO
Unique title, description and canonical address on every page
Open Graph and Twitter Card tags for link previews
JSON-LD structured data describing the business and its services
sitemap.xml and robots.txt
Registered in Google Search Console

Important: do not delete google4f031f9ac4effb0f.html. Google needs it to keep the site verified.

Editing the site

Business details (email, WhatsApp number, location, WhatsApp message) are in the CONFIG object near the top of the <script> section in each page.

The same script is included in every page, so a change to contact details must be made in all five HTML files: index.html, about.html, services.html, courses.html and contact.html.

After editing:

Commit the changes to this repository.
Cloudflare Pages redeploys automatically within about a minute.
If you add a new page, add it to sitemap.xml too.
Run locally

Open index.html in a browser, or serve the folder with a simple server:

bash
python3 -m http.server 8000

Then visit http://localhost:8000.

Contact form

The contact form opens the visitor's own email app with a draft addressed to the business email. The enquiry is only sent once the visitor presses Send there, and nothing is stored on a server. To receive enquiries directly, connect a form service such as Formspree or Web3Forms, or save submissions to a Google Sheet.

Contact
Email: info.errorpoint.in@gmail.com
Instagram: @error_point.in

© ERROR POINT Technologies. All rights reserved.
