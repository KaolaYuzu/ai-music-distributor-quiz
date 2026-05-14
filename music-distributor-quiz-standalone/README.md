Files included:
- quiz.html: standalone lead magnet quiz page
- subscribe.js: Vercel API function forwarding lead data to Google Apps Script

Upload targets in GitHub:
- Replace root /quiz.html with quiz.html, OR use it as a new standalone project index.html
- Replace /api/subscribe.js with subscribe.js

Important:
The automatic email delivery depends on your Google Apps Script or Brevo automation. This version sends lead_magnet and send_guide=true so the backend can trigger the guide email/download-link flow.
