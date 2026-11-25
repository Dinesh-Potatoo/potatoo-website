# Potatoo website

Landing page for Potatoo – home-cooked dog food in Chennai.

## Edit
- WhatsApp number, greeting and menu dishes: the `<script>` block near the bottom of `index.html`.
- Logo: `assets/potatoo-logo.png`.

## Hosting
- Live at https://potatooo.com (GitHub Pages, repo `Dinesh-Potatoo/potatoo-website`, branch `main`).
- To update the site: edit, then `git add -A && git commit -m "..." && git push`. It goes live in about a minute.
- Domain is registered at GoDaddy. DNS: four `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and `CNAME` `www` → `dinesh-potatoo.github.io`.
- The `CNAME` file in this folder tells GitHub which domain to serve. Don't delete it.
