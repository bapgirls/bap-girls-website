# BAP Girls Website

A custom, mobile-friendly BAP Girls information, booking, and membership-application website.

## Files
- `index.html` — main one-page website
- `application.html` — membership application
- `thank-you.html` — submission confirmation page
- `styles.css` — all visual styling
- `assets/bap-girls-logo.jpg` — uploaded BAP Girls logo

## Deploying to Render
1. Create a free GitHub account and a new repository.
2. Upload all files/folders in this package to the repository.
3. In Render, create a **Static Site** and connect that GitHub repository.
4. Use the repository's root directory as the publish directory.
5. No build command is needed.
6. Deploy.

## Application email
The application uses FormSubmit to send submissions to `forpicedits1@gmail.com`.
On the first real submission, FormSubmit may require the recipient email to be confirmed. The email will then receive the submitted fields in a readable table.

IMPORTANT: In `application.html`, the `_next` hidden field currently points to `https://bapgirls.onrender.com/thank-you.html` as a placeholder. After Render gives you your actual free site address, change that one value to:
`https://YOUR-RENDER-SUBDOMAIN.onrender.com/thank-you.html`

The Instagram buttons point to:
https://www.instagram.com/bap.girls/

No custom domain or payment processor is required for the setup.
