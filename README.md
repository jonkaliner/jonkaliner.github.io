# Jon Kaliner – Personal Website

Live at **https://jonkaliner.github.io/** – built automatically by GitHub Pages (Jekyll) on every push to `main`.

## Writing a blog post

1. Create a new file in `_posts/` named `YYYY-MM-DD-short-title.md`, e.g. `_posts/2026-11-02-why-batteries-matter.md`.
   You can do this directly on github.com: open the `_posts` folder → **Add file → Create new file**.
2. Start the file with this header, then write the post in Markdown below it:

   ```markdown
   ---
   title: "Why batteries matter"
   tags: [engineering, energy]
   ---

   Your text here. **Bold**, *italic*, [links](https://example.com), lists, quotes …
   ```

3. Commit / push. The post shows up at `/blog/` after a minute or two.

The first paragraph is used as the preview on the blog page. To add images, put them in `images/` and use `![description](/images/file.jpg)`.

## Structure

- `index.html` – About page
- `cv.html` – CV page
- `blog/index.html` – list of all posts
- `_posts/` – blog posts (Markdown)
- `_layouts/`, `_includes/` – shared page layout and sidebar
- `assets/css/style.css` – styles
- `images/profile.jpg`, `files/CV.pdf` – profile picture and downloadable CV
