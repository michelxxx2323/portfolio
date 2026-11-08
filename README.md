# Michel Soares — Portfolio

Source for my personal portfolio: strategy, data and product work, from Sales Ops and New Business at TOTVS to founding my own ventures (Hypernova and St. Clair), and now AI agents and automations built with Claude Code.

**Live site:** https://michelsoares.vercel.app/?lang=en

The site is bilingual (Portuguese and English): append `?lang=en` to any page, or use the language toggle.

## Pages

| Page | What's on it |
|---|---|
| [`index.html`](index.html) | Career timeline, the St. Clair case (D2C cookware brand: Instagram, UGC, ads, email and Shopify store), BI dashboards, AI projects, tools and contact |
| [`creators.html`](creators.html) | **Creator Supply Engine**: a case study for Passionfroot's Creator Acquisition Analyst role — sourcing, double AI vetting and pricing of B2B creators in Brazil and the US, with n8n, Clay, Apollo and Attio ([live](https://michelsoares.vercel.app/creators.html?lang=en)) |

## AI projects featured

| Project | Repository |
|---|---|
| Creator Supply Engine | [creator-supply-engine](https://github.com/michelxxx2323/creator-supply-engine) |
| "P.H.", an AI SDR agent for email and WhatsApp | [brax-sdr-agent](https://github.com/michelxxx2323/brax-sdr-agent) |
| Job Fit Screener (job radar) | [Radar-de-Vagas](https://github.com/michelxxx2323/Radar-de-Vagas) |
| AI inventory agent | [inventory-ai-agent](https://github.com/michelxxx2323/inventory-ai-agent) |

## Layout

| Path | What's in it |
|---|---|
| `index.html`, `creators.html` | The two pages: plain HTML, CSS and JavaScript in a single file each, no build step |
| `img/` | Portfolio images: St. Clair ads, Instagram, UGC, email campaigns, landing page and store, BI dashboards |
| `creators-img/` | Screenshots for the creators case: n8n workflows, Attio pipeline, Clay workflow, Apollo sequences |
| `creators-n8n/` | The three n8n workflows from the creators case, as importable JSON |

## How it's built

- Static HTML with no framework and no dependencies besides Google Fonts.
- Each piece of text is written in Portuguese with its English version in a `data-en` attribute; a small script swaps them based on `?lang=` and remembers the choice in `localStorage`.
- Designed and built with AI (Claude).
- Deployed on Vercel: every push to `main` goes live in about 30 seconds.

## Running locally

No build needed. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# http://localhost:8000/?lang=en
```

## Contact

[LinkedIn](https://www.linkedin.com/in/michelsoaresafonso)
