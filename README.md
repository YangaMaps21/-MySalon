# @MySalon

Beauty & wellness marketplace platform prototype — connects customers to salons, barbers, specialists, beauty spas and makeup artists, with booking, an AI look generator, a marketplace store, and a "Rent a Chair" feature for independent specialists.

This is a static HTML/CSS/JS prototype (no build step) that plugs into a real [Supabase](https://supabase.com) backend for auth and the chair-slot data.

## Pages

- `index.html` — homepage with interactive map, category browse, AI look tools
- `salons.html` / `salon-profile.html` — salon directory & profile (booking, staff, chair rental)
- `specialists.html` / `specialist-profile.html`
- `beauty-spa.html` / `beauty-spa-profile.html` / `beauty-spa-studio-profile.html`
- `makeup-artists.html` / `makeup-artist-profile.html`
- `market.html` / `market-shop.html` — marketplace store
- `rent-a-chair.html` — chair rental listings
- `list-your-business.html` — business onboarding flow
- `profile.html` — customer/business account (Supabase Auth) + dashboard
- `billing.html` — subscription plans & checkout
- `about.html`

## Deploying

Static site — no build step required. Deploys as-is on Vercel, Netlify, GitHub Pages, or any static host.
