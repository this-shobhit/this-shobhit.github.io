# this-shobhit.github.io

Personal site and GitHub Pages for Shobhit (Jekyll).

## Structure

- **`_config.yml`** — Jekyll config (collections, plugins, permalinks).
- **`_layouts/`** — Layouts: `default`, `work`, `article-writing`, `about`, etc.
- **`_includes/`** — Header, footer, YouTube player, comments.
- **`_notes/`** — Markdown files for the Notes blog (each becomes a post).
- **`_thoughts/`** — Markdown files for Thoughts and Reviews (each becomes a post).
- **`css/`** — Styles (`style.css`).
- **`images/`** — Site images and `images/icons/` for icons.
- **Main nav** — work, notes, thoughts and reviews, about (defined in root pages with `nav_order`).
- **Work subnav** — Presentations, Teaching, CV (when on any work page).

## Run locally

```bash
# With Bundler (if you use a Gemfile)
bundle install
bundle exec jekyll serve

# Or with system Jekyll
jekyll serve
```

Then open <http://localhost:4000>.

## Deploy

Pushing to the default branch on GitHub builds and serves the site via GitHub Pages.
