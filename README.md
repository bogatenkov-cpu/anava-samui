# ANAVA Samui — Landing Page

First Freehold Oceanview Condominium in Koh Samui.

## Deploy

This is a static HTML landing page, ready for Vercel or Netlify.

### Vercel (recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import repo
3. Click Deploy — no configuration needed

### Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag `index.html` onto the page

## Structure

```
/
├── index.html      # Main landing page (self-contained, all CSS/JS inline)
└── README.md
```

## Lead form

The contact form is ready for webhook integration. To connect to CRM:
1. Add a Vercel Serverless Function at `/api/lead.js`
2. Point the form `action` to `/api/lead`
