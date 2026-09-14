# Van Berkel Lab website

Source for the Van Berkel Lab website at **https://DerekVanBerkel.github.io/**.

The site is built with Quarto. Routine content is stored as simple `.qmd` Markdown files.

## Updating news
Create a folder under `news/posts/` with an `index.qmd` containing a title, date, description, categories, and the short update. The News page discovers posts automatically.

## Main content
- `index.qmd` — homepage
- `research.qmd` — research themes
- `projects.qmd` — major projects
- `people.qmd` — lab members and alumni
- `publications.qmd` — selected publications
- `teaching.qmd` — teaching
- `join.qmd` — prospective students and collaborators
- `news/` — news posts
- `styles/site.css` — site design

Every push to `main` triggers the Quarto publishing workflow.
