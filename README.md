**TechCon 2024 Conference Website**

This project is a basic multi-page website for the fictional TechCon 2024 Conference. It was built using only HTML5, with semantic structure and accessibility in mind.

The website includes:

A homepage with an introduction and embedded promotional video.

An about page with the history, mission, and past speakers.

A schedule page with a detailed timetable of events presented in a structured HTML table.

A registration page with a form for attendees to sign up.

A contact page with contact details, social links, an embedded map, and a contact form.

📂 Project Structure
TechCon_HTML/
└── techcon_website/
    ├── index.html       # Homepage
    ├── about.html       # About TechCon 2024
    ├── schedule.html    # Conference Schedule
    ├── register.html    # Registration Form
    └── contact.html     # Contact Page

**Page Details**

1. Homepage (index.html)

Uses <header>, <main>, <section>, and <footer>.

Contains the conference title in an <h1>.

Includes a navigation menu linking to all other pages.

Provides a short introduction paragraph.

Embeds a promotional video using the <video> tag with controls and accessible description.

2. About Page (about.html)

Title: “About TechCon 2024” inside <h1>.

Structured with multiple <article> sections:

History with descriptive text and images.

Mission with conference goals and images/icons.

Past Speakers with short bios and photos of notable speakers.

3. Schedule Page (schedule.html)

Title: “Schedule for TechCon 2024” inside <h1>.

Built with an accessible <table> inside <main>.

Table includes:

<caption>: “Detailed Schedule of Events for TechCon 2024”.

<th> headers for Time, Session, and Speaker.

<td> rows for each scheduled event.

4. Register Page (register.html)

Title: “Register for TechCon 2024”.

Contains a registration form with fields for:

Full name (<input type="text">)

Email (<input type="email">)

Password and password confirmation (<input type="password">)

Terms and conditions agreement (<input type="checkbox">)

Ends with a submit button labeled “Register Now”.

5. Contact Page (contact.html)

Title: “Contact Us”.

Contains:

Conference email (mailto: link).

Social media links opening in new tabs.

Google Maps embed (<iframe>) showing the venue.

Contact form with fields for name, email, and message.

**Key Features**

Consistent navigation menu across all pages.

Semantic HTML: <header>, <nav>, <main>, <section>, <article>, <footer>.

Accessibility features: descriptive alt text for images, <caption> for table, labels for all form fields.

Footer on every page includes:

© 2024 TechCon Conference. All rights reserved. copyright

**How to View**

Clone the repo:

git clone https://github.com/<your-username>/TechCon_HTML.git


Open the techcon_website/ folder.

Double-click index.html to open the homepage in your browser.

Navigate through the pages using the menu.

**Notes**

This project focuses on HTML only (no CSS/JavaScript).

The goal was to demonstrate correct use of HTML structure, media embedding, and accessibility.