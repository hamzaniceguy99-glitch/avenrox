# Avenrox — indoor rowing coaching

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `avenrox.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/avenrox.mjs`).
> To change the content, edit that file and run `node build.mjs avenrox` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@avenrox.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($25 / $69 / $145) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Coaching in indoor rowing, delivered online: one-on-one video sessions and small group sessions covering rowing machine stroke technique, structured training plans, pacing and time trial testing, and complementary strength and mobility work. Clients follow a 6 to 12 week program with video review of their stroke and review of their training data. Avenrox provides no medical, physical therapy or rehabilitation advice and asks clients with pain, injury or a medical condition to consult a qualified healthcare professional before training. Services are sold as month-to-month subscriptions from $25 to $145 per month, cancellable at any time. No equipment is sold or shipped. Site: avenrox.shop
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
