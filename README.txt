
Byte Fort — Multi‑page Website
==============================

Structure
---------
- index.html               (Home)
- courses.html             (Courses overview + download PDF)
- about.html               (About page)
- founder.html             (Founder & CEO page — replace the image src)
- contact.html             (Contact page — updates mailto:)
- gmail-hacking.html       (Course 1 — 1–2 page explanation)
- botnet.html              (Course 2 — 1–2 page explanation)
- mobile-malware.html      (Course 3 — 1–2 page explanation)
- bug-hunters-diary.html   (Course 4 — 1–2 page explanation)
- assets/css/style.css
- assets/js/main.js
- assets/img/founder-placeholder.jpg  (replace with your image)
- assets/pdfs/courses.pdf             (replace with your PDF)

What to customize
-----------------
1) Footer social links in every page (WhatsApp, LinkedIn, Gmail).
   - WhatsApp: https://wa.me/your-number-here
   - LinkedIn: https://linkedin.com/in/your-handle
   - Gmail: mailto:yourmail@gmail.com

2) Founder image:
   - Option A: Upload your image to assets/img/founder.jpg and change the path.
   - Option B: Use an online URL and replace the <img src="..."> in founder.html.

3) Courses PDF:
   - Replace assets/pdfs/courses.pdf with your file (same name) to keep links working.

How to run
----------
Just open index.html in your browser. All pages are linked through the top navigation.

Deploy tips
-----------
- GitHub Pages: push this folder to a repo and set Pages source to the root (or /docs).
- Netlify/Vercel: drag & drop this folder on the dashboard.
