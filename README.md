# Portfolio

Personal portfolio site for GitHub Pages.

## Structure

```
Portfolio/
├── index.md              # Homepage
├── about.md              # Background (minimal, discreet)
├── projects/             # Public project write-ups (add as cleared)
├── docs/                 # Public technical writing
├── assets/               # Images, diagrams
├── _drafts/              # Private drafts (excluded from build)
├── _config.yml           # Jekyll configuration
└── README.md             # This file (excluded from build)
```

## Privacy Notes

- `_drafts/` folder is excluded from the Jekyll build
- No personal identifiers beyond first name
- No email or social links in public config
- Projects only added when explicitly cleared for public sharing

## Local Development

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`

## Deployment

1. Create GitHub repo (can be private with Pages enabled)
2. Push this folder
3. Enable GitHub Pages in Settings → Pages
4. Site will be at `https://username.github.io/repo-name/`

## Adding Public Content

When ready to publish a project:
1. Move from `_drafts/` to `projects/`
2. Review for any personal details
3. Commit and push

---

*Created January 2026*
