
# Cyber Fortress – Resources Site (Jekyll)

This is a lightweight Jekyll site designed for GitHub Pages. It provides
simple, fast navigation to tools used during the **Cyber Fortress** exercise.

## Quick start (GitHub Pages)
1. Create a new public repo on GitHub, e.g., `cyber-fortress`.
2. Upload this folder's contents to the repo root.
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), folder: `/ (root)`
4. Wait a minute for Pages to build, then visit the published URL.
5. (Optional) Set a custom domain and update `_config.yml` `url`/`baseurl`.

## Pulling forked requests
1. Beware! Because it is hosted by some GitHub owner you must modify '_config.yml' with the appropriate url and baseurl. Not resolving this creates many display errors during testing.

## Local preview (optional)
You can preview locally with Ruby/Jekyll (not required for GitHub Pages builds):

```bash
gem install bundler jekyll
bundle init
bundle add jekyll
bundle exec jekyll serve
```
