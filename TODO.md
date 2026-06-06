# TODO - VKL Lab live deployment

## Goal
Get a working live link for the VKL Lab static multi-page site.

## Steps
1. Create a repo-root deploy folder so Cloudflare static Pages can find `index.html` and `css/`, `js/`, `img/`, `lib/` at the same level.
2. Update any HTML asset paths only if needed (keep relative paths).
3. Commit changes to GitHub.
4. Tell Cloudflare Pages to deploy the correct root (repo root / deploy folder).
5. Redeploy and provide the generated live `pages.dev` / custom-domain link.

## Status
- Repo push already done to `master`.
- Cloudflare Pages deployment attempts currently return 404 due to wrong root/static detection.
- Next: restructure files for Cloudflare static hosting.
