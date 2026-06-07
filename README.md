# Bulk Task Creator
Built by Shine Bright Virtual — shinebrightvirtual.com
Live at bulktaskcreator.com

Create tasks in bulk on a schedule you define. Works with ClickUp and more platforms coming soon.

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to vercel.com → Add New Project → Import your repo
3. Leave all settings as default → Deploy
4. In Vercel's domain settings, add bulktaskcreator.com and follow the DNS instructions
5. In Squarespace Domains, add the DNS records Vercel provides

## How it works

- Pure HTML/CSS/JS — no build step, no dependencies, no server needed
- Calls the ClickUp API directly from the browser
- API token is never stored or sent anywhere except ClickUp
- Saved presets stored in browser localStorage
