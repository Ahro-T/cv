# Academic CV Website

A one-file static CV template inspired by a clean academic CV page.

## Edit

Open `cv.html` and replace placeholders:

- `Your Name`, department, university, email
- Homepage / LinkedIn / GitHub links
- Education, publications, research, projects, teaching, awards

Keep each entry in this pattern:

```html
<div class="cv-entry">
  <div class="entry-line-1">
    <span class="entry-title">Title</span>
    <span class="entry-date">Date</span>
  </div>
  <div class="entry-line-2">Institution or subtitle</div>
  <div class="entry-details">
    <ul>
      <li>Bullet point.</li>
    </ul>
  </div>
</div>
```

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/cv.html>.

## Publish with GitHub Pages

1. Create a GitHub repo named either:
   - `your-id.github.io` for `https://your-id.github.io/cv.html`, or
   - any repo name, e.g. `cv`, for `https://your-id.github.io/cv/cv.html`.
2. Push these files:

```bash
git init
git add index.html cv.html README.md
git commit -m "Create academic CV page"
git branch -M main
git remote add origin https://github.com/your-id/your-repo.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main / root**.
4. Use the `PDF` button on the page to print or save the CV as a PDF.
