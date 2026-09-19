# Engineering Notes

Personal learnings in **System Design**, **DSA**, **AI**, and **Projects** — written as Markdown, published via GitHub Pages.

**Site:** https://sreeramkarumury.github.io/engineering/

## Structure

```
system-design/   # architecture & trade-offs
dsa/             # patterns & problem write-ups
ai/              # ML / LLM / tooling notes
projects/        # build logs & retrospectives
```

Each folder has a `_template.md` — copy it, rename, fill front matter, write.

## Add a note

1. Copy the topic `_template.md` → e.g. `system-design/rate-limiting.md`
2. Set `title`, `parent`, `nav_order`
3. Optional: `# published: false` in front matter to keep it off the site until ready
4. Push to `main` → Pages deploys automatically

## Local preview

```bash
bundle install
bundle exec jekyll serve
# → http://localhost:4000/engineering/
```

## GitHub Pages setup (one-time)

1. Repo **Settings → Pages**
2. Source: **GitHub Actions**
3. After the first push of this workflow, the site goes live at the URL above

## LinkedIn

Share individual note URLs (stable permalinks), not just the homepage — e.g.  
`https://sreeramkarumury.github.io/engineering/system-design/your-note/`
