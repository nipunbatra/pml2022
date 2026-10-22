# CS 691 · Probabilistic Machine Learning (2022)

Course website for Probabilistic Machine Learning at IIT Gandhinagar, Semester I 2022–23 (August–November 2022):
<https://nipunbatra.github.io/pml2022/>

The site is a [Quarto](https://quarto.org) website in the same design as
[ES 667 Deep Learning](https://nipunbatra.github.io/dl-2026/). GitHub Pages serves the `main` branch as it is, so
the site renders in place: every page's `.html` is committed next to its `.qmd`, and `.nojekyll` turns Jekyll off.
After editing a page, run `rm -f robots.txt && quarto render` (Quarto will not copy the generated `robots.txt` onto itself) and commit the result.

| File | Contents |
|---|---|
| `index.qmd` | Home: course facts, course record, module overview, questions, references, teaching assistant |
| `schedule.qmd` | Lectures: every class with its slides, notes and notebooks |
| `assessment.qmd`, `_dates.qmd` | Grading, dates and assignments |
| `assignments/` | The assignment list (`index.qmd`) and Assignments 1–4 |
| `projects/index.qmd` | Project ideas |
| `slides/`, `notebooks/` | Slides, notes and notebooks |
| `calendar/`, `schedule/`, `staff/`, `announcements/` | Redirects from the old site's addresses |
| `styles.scss`, `course.scss`, `rail.html`, `course-theme.html`, `course-tools.html` | Shared theme |
