# sAI Blog

Personal engineering blog. Hosted on GitHub Pages.

## Deploy in 5 minutes

### 1. Create a GitHub repo
- Go to [github.com/new](https://github.com/new)
- Name it: `sai-blog` (or anything you want)
- Make it **Public**
- Don't add a README (we already have one)
- Click **Create repository**

### 2. Push this code
Open your terminal and run:

```bash
cd sai-blog
git init
git add .
git commit -m "Initial commit - sAI blog"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sai-blog.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under "Source", select **Deploy from a branch**
- Branch: `main`, folder: `/ (root)`
- Click **Save**
- Wait ~1 minute

### 4. Your site is live!
Your blog will be at: `https://YOUR_USERNAME.github.io/sai-blog/`

## Custom domain (optional)
1. Buy a domain (e.g., Namecheap, Cloudflare)
2. In repo Settings → Pages → Custom domain, enter your domain
3. Add a CNAME record pointing to `YOUR_USERNAME.github.io`
4. Check "Enforce HTTPS"

## Adding new posts
1. Create a new `.html` file in `/posts/`
2. Add a card linking to it in `index.html`
3. Push to GitHub — auto-deploys

## Structure
```
sai-blog/
├── index.html                          # Homepage
├── posts/
│   └── mlops-sagemaker-ai-agents.html  # First post
├── .nojekyll                           # Tells GitHub to skip Jekyll
└── README.md                           # This file
```
