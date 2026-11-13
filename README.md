# Gaurav Sharma — Portfolio

A single-file static site. `index.html` contains everything (styles, scripts, photo).
Double-click `index.html` to preview it offline.

## Host it free on Vercel (stays online; no time limit on the free Hobby plan)

### Option A — GitHub + Vercel (recommended)
1. Create a new repository on GitHub, e.g. `portfolio`, and upload every file in this folder.
2. Go to vercel.com, sign in with GitHub, choose "Add New… → Project" and import the repository.
3. Framework preset: "Other". Leave build command and output directory empty. Click Deploy.
4. You get a link like `https://portfolio-yourname.vercel.app`. Every push to GitHub redeploys it.

### Option B — Vercel CLI (no GitHub needed)
```
npm i -g vercel
cd gaurav-portfolio
vercel --prod
```

## Other free hosts that work with this same folder
- Netlify: drag this folder onto app.netlify.com/drop
- GitHub Pages: repo Settings → Pages → deploy from the main branch
- Cloudflare Pages: create a project and upload this folder

## Custom domain
In Vercel: Project → Settings → Domains → add your domain (e.g. gauravsharma.dev) and follow the DNS steps.

The PDF is served at `/Gaurav_Sharma_Portfolio.pdf` once deployed.
