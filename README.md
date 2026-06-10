# Pihai Sun — Academic Homepage

Source code of my personal academic homepage:
👉 **<https://sunpihai-up.github.io>**

I am an M.S. student at Harbin Institute of Technology, working on monocular depth
estimation, event-based vision, and image–event multimodal fusion.

The site is a [Jekyll](https://jekyllrb.com/) website built on the
[minimal-light](https://github.com/yaoyao-liu/minimal-light) theme and is
automatically built and deployed by GitHub Pages.

## Repository layout

| Path | What it controls |
| --- | --- |
| `_config.yml` | Name, position, affiliation, email, links, avatar, favicon |
| `index.md` | About Me · Research Interests · News |
| `_data/publications.yml` | Publication list (edit this to add papers) |
| `_includes/services.md` | Academic services (optional) |
| `assets/img/avatar.jpg` | Profile photo |
| `assets/files/Pihai_Sun_CV.pdf` | CV (PDF) |

## How to update

- **Add a publication:** add an entry to `_data/publications.yml`.
- **Edit text / news:** edit `index.md`.
- **Change basic info or links:** edit `_config.yml`.

Commit and push to the `main` branch — GitHub Pages rebuilds and redeploys the
site automatically (usually within a minute or two).

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
# then open http://localhost:4000
```

## Credits

Built with the [minimal-light](https://github.com/yaoyao-liu/minimal-light) theme
by [Yaoyao Liu](https://github.com/yaoyao-liu), which is in turn based on
[minimal](https://github.com/orderedlist/minimal). Theme released under CC0 1.0.
