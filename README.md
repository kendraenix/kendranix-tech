# $0 Link Page Blueprint
### by Kendra Nix — kendranix.tech

A complete free resource funnel built with pure HTML/CSS/JS. No frameworks, no build step, no dependencies. Deploy to Vercel in 60 seconds.

---

## 📁 File Structure

```
/
├── index.html                  → Your branded link hub (home page)
├── vercel.json                 → Vercel routing config (clean URLs)
├── .gitignore
├── pages/
│   ├── blueprint.html          → Lead magnet landing page
│   ├── master-prompt.html      → The master Claude prompt guide
│   ├── domain-walkthrough.html → Buy domain + go live walkthrough
│   └── thank-you.html          → Post-opt-in thank you page
└── docs/
    ├── email-sequence.md       → 4-email Kit nurture sequence (copy/paste ready)
    └── social-content.md       → LinkedIn, Facebook, Threads, YouTube outline
```

---

## 🚀 Deploy to Vercel (3 steps)

### Option A — Vercel Dashboard (easiest)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo → click **Deploy**

Done. Vercel auto-detects static HTML and the `vercel.json` handles all routing.

### Option B — Vercel CLI
```bash
npm i -g vercel
cd link-page-blueprint
vercel
```

---

## 🔗 Live URLs (after deploy)

| Page | URL |
|------|-----|
| Link hub | `yourdomain.com/` |
| Blueprint landing page | `yourdomain.com/blueprint` |
| Master Claude prompt | `yourdomain.com/master-prompt` |
| Domain walkthrough | `yourdomain.com/domain-walkthrough` |
| Thank you page | `yourdomain.com/thank-you` |

---

## 🔧 Things to update before going live

- [ ] `index.html` — swap in your real photo URL, live offer links, Kit form ID
- [ ] `pages/blueprint.html` — confirm Kit form ID matches
- [ ] `pages/master-prompt.html` — verify Paperbell link
- [ ] `pages/domain-walkthrough.html` — confirm Hosting.com affiliate link
- [ ] `pages/thank-you.html` — update next-step page URLs to your live Vercel domain
- [ ] `docs/email-sequence.md` — paste emails into Kit, activate sequence
- [ ] Connect custom domain in Vercel → Settings → Domains

---

## 🛠 Tech stack

- Pure HTML/CSS/JS — zero build step, zero dependencies
- Google Fonts (Playfair Display + DM Sans) via CDN
- Giphy embed (thank you page gif)
- Kit (ConvertKit) for email opt-ins
- Paperbell for Operations Audit checkout
- Hosting.com affiliate link for domain walkthrough

---

© 2026 Kendra Nix | [kendranix.com](https://kendranix.com) | [kendranix.tech](https://kendranix.tech)
