# Nisab — prototype

**You started. Let's finish.**

Nisab helps Muslim women in the US who started investing and stopped get to their next step. It shows them where they stand, translates their halal (Shariah-compliant) investing options into plain language, and walks them through getting started, with women-only Circles at mosques and campus MSAs as the community layer.

This is a clickable prototype built for ENTP 315 (Lehigh University). It is a single self-contained HTML page: no build step, no backend, no real accounts or payments.

## What's in it

- **Landing page**: "Where did you leave off?" entry points
- **Check-in**: four quick questions, about 45 seconds
- **Home**: your stage, one clear next step, options that fit
- **My Path**: step-by-step checklist with plain-language glossary
- **Options**: halal investing options (stocks, ETFs, robo-advisors, retirement, sukuk, savings) with filters and compare
- **Community**: Circles, anonymous questions, membership (free / $5 a month)
- **For partners**: mosques, MSAs and financial providers
- **Insights** (`#insights`): founder view; charts use placeholder demo data

## Run it

Open `index.html` in any browser. That's it.

To publish it free with GitHub Pages: repo **Settings → Pages → Deploy from a branch → `main` / root**.

## Notes

- Provider names (Wahed, Manzil, Musaffa, Amana, SP Funds, Zoya, ShariaPortfolio, Stearns, UIF) are **examples, not recommendations**. Confirm current terms with each provider.
- Nisab is an educational prototype and does not provide financial, legal or religious advice.
- Answers, checklist progress and form entries are stored only in the visitor's own browser (localStorage).
