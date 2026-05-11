# News Portal — Hugo + Tailwind + Netlify CMS (Free starter)

Ei project ta ekta starter news portal — static site built with Hugo, styled with Tailwind (CDN), and editable via Netlify CMS.

Features
- Homepage with latest posts and featured posts
- Article pages (title, author, date, categories, tags, featured image)
- Category/tag pages
- RSS (built-in Hugo) and sitemap
- Netlify CMS admin at /admin for non-technical editing
- Mobile responsive

Quick steps to deploy (short)
1. Create a new GitHub repository and push these files.
2. Create a site on Netlify -> "New site from Git" -> connect your GitHub repo.
   - Build command: `hugo`
   - Publish directory: `public`
3. In Netlify dashboard: Site settings -> Identity -> Enable Identity.
   - Under Identity Settings -> Services -> Enable Git Gateway.
   - Invite yourself (or create users) — you will receive invite email.
4. Open https://<yoursite>.netlify.app/admin — login and start adding posts.

Config to check before deploy
- Edit `config.toml` -> `baseURL` to your site URL (or leave placeholder while developing).
- Branch name in `static/admin/config.yml` is `main` by default — change if your repo uses another branch.

How to use CMS
- After enabling Identity & Git Gateway, visit `/admin`.
- Login / accept invite, then you can Create/Edit posts; changes will be committed to the repo (Git-based workflow).

If you want, ami nicher steps follow kore apnar behalf e deploy korte pari — kintu ami apnar GitHub repo name o owner dorkar hobe for automated push. Jodi apni chaen ami push kore diye dibo, GitHub repo name o permission bolun.

Enjoy — ami ekhane achi jodi kono step e help dorkar hoy.
