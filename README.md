# PayCo mobile preview

This is a static, mobile-friendly front-end preview. It does not connect to school accounts, a backend, or real payments. The student, cashier, and admin screens are interactive previews only. Do not use it for real financial activity.

## Publish with GitHub and Vercel

1. Create a **private** repository on GitHub, for example `payco-mobile-preview`.
2. Upload `index.html`, `vercel.json`, and this `README.md` to the repository root.
3. In Vercel, choose **Add New → Project**, import that GitHub repository, keep the framework as **Other**, leave the build command empty, and deploy the static files from the repository root.
4. Vercel will provide an HTTPS URL that can be opened on a phone. Add it to the phone home screen from the browser menu if you want an app-like shortcut.

The login is intentionally a preview flow. Real school authentication and payment processing need a secure server before this can be used with real student accounts or money.
