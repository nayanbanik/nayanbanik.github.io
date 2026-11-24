# nayanbanik.github.io

Source for the academic website of Nayan Banik, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT License, see [LICENSE](LICENSE)).

## Where things live

| To change…                 | Edit                                                        |
| -------------------------- | ----------------------------------------------------------- |
| Name, site URL, features   | `_config.yml`                                               |
| Home page bio and photo    | `_pages/about.md`, photo in `assets/img/`                   |
| Publications               | `_bibliography/papers.bib` (one BibTeX entry per paper)     |
| CV                         | `_data/cv.yml`                                              |
| Social and contact links   | `_data/socials.yml`                                         |
| Blog, news, projects, etc. | Switched off in the `exclude` list of `_config.yml` for now |

## Preview locally

With Docker Desktop running:

```bash
docker compose pull
docker compose up
```

Then open <http://localhost:8080>. Edits to pages and data files reload automatically.

The theme's full guides are in [`docs/`](docs/), starting with [`docs/CUSTOMIZE.md`](docs/CUSTOMIZE.md).
