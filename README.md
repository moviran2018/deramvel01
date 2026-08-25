# Dreamwell - Static Real Estate Site

## Deploy to GitHub + Cloudflare (2 steps)

### 1. GitHub
1. Create empty repo on GitHub (e.g. dreamwell)
2. In this folder run:
   git init
   git add .
   git commit -m "initial"
   git branch -M main
   git remote add origin https://github.com/YOURNAME/dreamwell.git
   git push -u origin main
3. In GitHub repo Settings -> Pages -> Source: main / root

### 2. Cloudflare
1. Cloudflare Dashboard -> Add Site -> your domain
2. Or use Cloudflare Pages -> Connect to Git -> select dreamwell repo -> Deploy
3. Cloudflare will auto-cache and give high speed globally.

All data is in localStorage (assets/app.js). For real backend later connect to Cloudflare Workers or Supabase via API.

Files: index.html, properties.html, property.html, admin/index.html
