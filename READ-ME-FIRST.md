# Paw & Pocket — your site is ready to deploy

Everything in this folder is one self-contained website. No build step, no
framework, no dependencies. You can put it live in about five minutes.

## What's in the box
- `index.html` — the homepage (the Dog Cost Calculator)
- `about.html`, `privacy.html`, `disclosure.html`, `contact.html` — supporting pages
- `404.html` — the "page not found" page (Penny peeking)

## Deploy it (the friction-free way)

**Option A — Netlify Drop (fastest, free)**
1. Go to **app.netlify.com/drop**
2. Drag this whole `pawandpocket` folder onto the page.
3. You get a live URL instantly (something like `random-name.netlify.app`).

**Option B — Cloudflare Pages (free, great if you buy your domain at Cloudflare)**
1. Create a Cloudflare account → Workers & Pages → Create → Pages → Direct Upload.
2. Upload this folder. Live in a minute.

> I can't push it live for you — that needs your own hosting account and your
> sign-in — but either option above is genuinely a drag-and-drop.

## Point your domain at it
1. Buy the domain (~$10/yr) at **Cloudflare** or **Namecheap**. Check
   availability first — and do a quick trademark sanity-check on the name.
2. In Netlify/Cloudflare → Domain settings → add your custom domain, then
   follow the prompt to update DNS/nameservers at your registrar.
3. HTTPS is automatic and free on both hosts.

## Before you flip it to "live for real"
- [ ] Remove the **"prototype"** tag in `index.html` (search for `demo-tag`).
- [ ] Wire the real **affiliate links**: in `index.html`, the "Compare quotes"
      and "See food picks" buttons are placeholders (search `data-demo`).
      Once you're approved by your affiliate programs, swap them for real links
      to your tracking URLs.
- [ ] Replace the placeholder email `hello@paw-and-pocket.com` (in
      `contact.html`) with a real inbox on your domain.
- [ ] Review `privacy.html` against the analytics tool you actually use.
- [ ] (Optional) The currency rates in the calculator are today's snapshot.
      For a real launch, refresh them or wire up a live rate.

## Affiliate setup, in order
1. Get the site live (programs want a real, working site to approve).
2. Apply: **Impact** (Chewy + insurers), **Amazon Associates**, and one pet
   **insurance** program or comparison platform (the highest-paying path).
3. Paste your tracking links into the calculator CTAs.
4. Drive traffic: faceless Reels + SEO first; paid only to build an email list.

That's it. Welcome to the web, Penny.
