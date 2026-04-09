# sAI

Personal engineering blog by Sai Rohit Thota. Writing about MLOps, AI agents, crypto infrastructure, and the systems behind production software.

**Live:** https://roeittt.github.io/sai-blog/

## Stack

Plain HTML + CSS. No build step, no framework, no dependencies. Hosted on GitHub Pages.

## Structure

```
.
├── index.html        # Homepage with post list
├── posts/            # One HTML file per post
└── README.md
```

## Writing a new post

1. Create `posts/your-slug.html`
2. Add a `<a class="post-card">` block to `index.html` linking to it
3. Commit and push:
   ```
   git add . && git commit -m "Add post: your title" && git push
   ```

GitHub Pages rebuilds automatically in under a minute.
