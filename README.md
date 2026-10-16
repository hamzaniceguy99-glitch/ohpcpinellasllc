# OHPC Pinellas — ohpc pinellas llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `ohpcpinellasllc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/ohpcpinellasllc.mjs`).
> To change the content, edit that file and run `node build.mjs ohpcpinellasllc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@ohpcpinellasllc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($On application / $On application / $No) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
OHPC Pinellas LLC, a Florida limited liability company (document number L16000092753), owns and leases small commercial and retail units in Pinellas County: letting directly to local businesses without an agent in between, agreeing leases in plain terms with every recurring charge stated before signature, coordinating fit-out so a tenant can trade from the date agreed, and maintaining the buildings and common areas it owns. The company leases only property it owns and is not a real estate broker acting for others. Site: ohpcpinellasllc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
