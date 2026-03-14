# SIM Landing + Privacy (for Vercel)

## Deploy to Vercel

1. **Sign up / log in** at [vercel.com](https://vercel.com).

2. **Import or upload this folder:**
   - **Option A:** Push this `landing` folder to a new GitHub repo, then in Vercel click "Add New Project" → "Import Git Repository" → select the repo. Root directory: set to `landing` (or the repo root if the repo only contains these files).
   - **Option B:** Install [Vercel CLI](https://vercel.com/docs/cli): `npm i -g vercel`. Then run `vercel` inside the `landing` folder and follow the prompts.

3. **Custom domain (optional):** In Vercel → Project → Settings → Domains, add `marine-sim.com` and `www.marine-sim.com`. Vercel will show the DNS records to add in Hostinger (A or CNAME).

## URLs after deploy

- **Landing:** `https://your-project.vercel.app/` (or `https://marine-sim.com` after domain is set)
- **Support (for App Store Connect):** `https://your-project.vercel.app/support` (or `https://marine-sim.com/support`)
- **Privacy (for App Store):** `https://your-project.vercel.app/privacy` (or `https://marine-sim.com/privacy`)

Use the **Support URL** in App Store Connect → App Information / Version → Support URL.  
Use the **Privacy URL** in App Store Connect → App Privacy → Privacy Policy URL.
