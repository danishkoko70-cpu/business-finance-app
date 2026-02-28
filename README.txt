# Phase 5 Business Finance Web App (Static)

## Login
- Admin: **admin** / **admin123**
- Manager: **manager** / **manager123**

After login, go to **Settings** (Admin) and change passwords.

## Hosting (Netlify / any static hosting)
Upload the whole folder contents (including assets/) to your hosting root.

Recommended: set **login.html** as the start page.
If your host forces index.html, you have two options:
1) Rename login.html to index.html and rename current index.html to dashboard.html and update links.
2) Use host settings (redirect/rewrite) to point / to /login.html.

## Data Storage
This is a **no-backend** app using **localStorage**.
Data is saved per-browser (each device has its own data).

Use **Backup** to download JSON and store it safely.
You can restore it from Settings (Admin).

## Modules included
- Dashboard + charts
- Income
- Expense
- Sales
- Purchases
- Bank
- Approvals (optional approval workflow)
- Reports (CSV export + P/L)
- Settings (Admin)
- Profile
- Help

## Test folder
`/test` folder is included for your hosting tests.
