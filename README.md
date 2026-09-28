# Plaza del Pescador – Invest Here

Static landing page. No build step.

## Put it on GitHub Pages
1. Create a new repository on GitHub and upload everything in this folder
   (index.html, the `assets` folder, and `.nojekyll`) to the root of the repo.
2. Go to **Settings → Pages**. Under "Build and deployment", pick
   **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.

## Use your own domain
1. In **Settings → Pages → Custom domain**, type your domain
   (for example `invest.yourdomain.com` or `yourdomain.com`) and save.
   GitHub adds a `CNAME` file to the repo for you.
2. At your domain registrar, add the DNS records:
   - Subdomain (e.g. `invest.yourdomain.com`): a **CNAME** record pointing to
     `YOUR-GITHUB-USERNAME.github.io`
   - Root domain (`yourdomain.com`): four **A** records pointing to
     185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
3. Once DNS is live (minutes to a few hours), tick **Enforce HTTPS**.

## Updating files
- Replace a PDF by uploading a new file with the same name into `assets/`.
- The YouTube video ID is set in `index.html` (search for `4zl1yNpvyq8`).
