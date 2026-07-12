# Academic Website

This is a Jekyll-based personal academic website structured after the Academic Pages template:

- `_config.yml` stores site identity, author profile, and collections.
- `_data/navigation.yml` controls the top navigation.
- `index.md` is the About page.
- `_pages/` contains Publications, Presentations, Awards, Teaching, and Service pages.
- `_publications/`, `_presentations/`, `_awards/`, `_teaching/`, and `_service/` contain individual Markdown entries.
- `assets/css/main.css` contains the visual styling.

## First Edits

1. Update any remaining profile details in `_config.yml`.
2. Replace `assets/images/jessica-sishi-fei.jpg` if you want to update the headshot.
3. Edit `index.md` for the About page.
4. Add or edit publication entries in `_publications/`.
5. Add or edit presentations in `_presentations/`.
6. Add or edit awards in `_awards/`.
7. Add or edit teaching entries in `_teaching/`.
8. Add or edit service entries in `_service/`.

## Local Preview

If Ruby and Bundler are available:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.
