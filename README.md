# Mateo Sonaglia — Portfolio

A responsive personal portfolio built with Next.js for deployment on Vercel.

## Local development

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Deploy to Vercel

1. Create a new GitHub repository and upload this project.
2. In Vercel, select **Add New → Project** and import the repository.
3. Keep the detected **Next.js** settings and deploy.
4. Review the generated `vercel.app` preview.
5. In **Project → Settings → Domains**, add `mateosonaglia.com` and `www.mateosonaglia.com`.
6. At Namecheap, add the exact DNS records shown by Vercel. Preserve any MX/TXT records used for email.
7. Set one domain as primary and redirect the other to it.

Do not change DNS until the Vercel preview has been approved.

## Content notes

- Contact details are defined in `app/contact/page.tsx` and `app/layout.tsx`.
- The LinkedIn footer currently uses a generic LinkedIn URL and should be replaced with Mateo's exact profile URL.
- The contact form opens the visitor's email application. It can later be replaced with a server-side email service such as Resend.
- SEO metadata is configured for `https://mateosonaglia.com`.
