# SKATERS Website (GitHub Pages + Jekyll)

This repository hosts the public website for **SKATERS** (**S**cientists for **K**nowledge of **AT**mospheric inv**ERS**ions).  
It uses the built-in **minima** Jekyll theme for a clean, simple look.

## Quick start

1. Create a new GitHub repository (public is recommended) and push these files.
2. In the repo, go to **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default), folder `/ (root)`
3. Your site will appear at:
   - **User/org site:** `https://<your-username>.github.io/`
   - **Project site:** `https://<your-username>.github.io/<repo-name>/`

## Customize
- Update `_config.yml` (title, description, email).
- Edit `index.md`, `about.md`, `contact.md`.
- Add pages (Markdown files) as needed; include them in `header_pages` to show in the top nav.

## Local preview (optional)
If you want to run locally, install Ruby & Bundler, then:
```bash
bundle init
echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile
bundle install
bundle exec jekyll serve
```
Open http://localhost:4000.

## License
You can choose and add a LICENSE file (e.g., CC-BY for content).