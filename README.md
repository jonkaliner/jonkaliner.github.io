# Jon Kaliner – Personal Website

Live at **https://jonkaliner.github.io/** – built automatically by GitHub Pages (Jekyll) on every push to `main`.
Design: the [AcademicPages](https://github.com/academicpages/academicpages.github.io) theme (MIT, see `LICENSE`).

## Writing a blog post

1. Create a new file in `_posts/` named `YYYY-MM-DD-short-title.md`, e.g. `_posts/2026-11-02-why-batteries-matter.md`.
   You can do this directly on github.com: open the `_posts` folder → **Add file → Create new file**.
2. Start the file with this header, then write the post in Markdown below it:

   ```markdown
   ---
   title: "Why batteries matter"
   date: 2026-11-02
   tags:
     - engineering
     - energy
   ---

   Your text here. **Bold**, *italic*, [links](https://example.com), lists, quotes …
   ```

3. Commit / push. The post shows up under **Blog Posts** after a minute or two.

The first paragraph is used as the preview on the blog page. To add images, put them in `images/` and use `![description](/images/file.jpg)`.

## Where things live

- `_pages/about.md` – home page (About)
- `_pages/cv.md` – CV page
- `_pages/year-archive.html` – "Blog Posts" page (all posts by year)
- `_posts/` – blog posts (Markdown)
- `_data/navigation.yml` – top menu links
- `_config.yml` – name, sidebar info (bio, location, links), site settings
- `images/profile.jpg`, `files/CV.pdf` – profile picture and downloadable CV
- `_layouts/`, `_includes/`, `_sass/`, `assets/` – theme files
