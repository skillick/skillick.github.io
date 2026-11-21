# skillick.github.io

Personal website of Samuel Killick, live at <https://skillick.github.io>.

Built with Jekyll on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and hosted on GitHub Pages.

## Where things live

| What | Where |
| --- | --- |
| Homepage / about text | `_pages/about.md` |
| Sidebar (name, bio, links) and site settings | `_config.yml` |
| Header menu links | `_data/navigation.yml` |
| Publications | `_publications/` (one file each, named `YYYY-MM-DD-short-title.md`) |
| Talks | `_talks/` |
| Teaching | `_teaching/` |
| Portfolio items | `_portfolio/` |
| Blog posts | `_posts/` |
| PDFs and other downloads | `files/` |
| Images | `images/` |

Every file in `_publications/`, `_talks/` and `_teaching/` needs a full `date: YYYY-MM-DD` in its front matter, or the site won't build.

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Or with Docker: `docker compose up`.
