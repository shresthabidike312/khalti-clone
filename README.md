# Khalti Login Page Clone (Frontend Only)

A Next.js (App Router) + Tailwind CSS recreation of the Khalti login screen layout.
No real backend/auth — submitting the form always shows an error message.

## Run it

```bash
npm install
npm run dev
```

Then open http://localhost:3000

## Notes
- Bank/institution logos are shown as generic numbered circular placeholders
  (real trademarked bank logos were intentionally not reproduced).
- The "khalti" wordmark is a simple CSS/SVG recreation, not the original logo asset.
- All links (Forgot Password, Signup, Login as SubUser) are inert placeholders.
- Submitting the login form always sets an error state — no real authentication occurs.

## Structure
- `app/page.js` — the login page component (client component, holds form state + error)
- `app/layout.js` — root layout
- `app/globals.css` — Tailwind directives
- `tailwind.config.js` / `postcss.config.js` — Tailwind setup
