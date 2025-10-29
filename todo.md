# First step: Set up a minimal Hugo site with GitHub Pages

## Tasks
- [x] Initialize Hugo site structure (`content/`, `layouts/`, `assets/`)
- [x] Add a minimal theme scaffold (customize to “green terminal” later)
- [x] Configure GitHub Pages workflow to build and deploy on push to `main`
- [x] Add basic config in `hugo.toml` (site metadata, `baseURL`, section for chapters)

## Files to create
- [x] `hugo.toml`
- [x] `content/_index.md`
- [x] `content/chapters/` (with a sample chapter)
- [x] `layouts/_default/baseof.html`
- [x] `layouts/_default/single.html`
- [x] `layouts/_default/list.html`
- [x] `.github/workflows/pages.yml` (Hugo build + Pages deploy)

## Next steps
- [ ] Set `baseURL` in `hugo.toml` (GitHub Pages URL or custom domain)
- [ ] Add `static/CNAME` if using a custom domain and enable Pages
- [ ] Ensure chapter header/footer show home, prev, and next links
- [ ] Improve responsive styles (mobile spacing, font sizes, typography)
- [x] Generate TOC on home from chapter files, sorted by `weight`
- [x] Show per-chapter word counts in TOC and total word count on home
- [x] Display progress toward 50,000 words on home page
- [ ] Implement Obsidian-style wiki-links `[[Chapter Title]]` → chapter URLs
- [ ] Add `404.html`, `sitemap.xml`, and `robots.txt`
- [ ] Document authoring workflow in `README.md` (add chapters, set `weight`, links)
- [ ] Verify GitHub Actions deploy and Pages visibility on `main`
- [ ] Optional: Preview deploys on pull requests
- [ ] Stretch: Obsidian vault integration via Git plugin
- [ ] Stretch: Command-line footer UI for navigating chapters
