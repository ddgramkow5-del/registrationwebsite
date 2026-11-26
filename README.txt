DLSJBC Student Portal (polished v2, flat version)
=================================================
All files sit together in one folder (no subfolders):
  index.html, styles.css, script.js, logo-dlsjbc.png

Run locally: open index.html in a browser.
Publish on GitHub Pages: upload all 4 files (plus this README if you like) to the main
level of your repository, then Settings > Pages > Deploy from a branch > main / (root).
Keep all the files together. If styles.css or script.js is missing, the page loses its design.

Saved progress
- Answers are saved in the student's own browser, so refreshing or restarting the tab
  brings the form back. Passwords and the privacy-policy tick are never saved.
- A draft expires after 3 days (DRAFT_DAYS in script.js) and is deleted after registering.

Contact details (CONTACT block in script.js) come from dlsjbc.edu.ph/contact.

Student number: 3 to 20 letters, numbers or dashes, kept as typed.
Mobile number: any number with 7 to 15 digits (+, spaces, dashes, brackets allowed).

Demo data (nothing is sent to a server)
- Test login: student number 2026-00001, password Animo2026.
- Gmail and Facebook buttons are simulated.
