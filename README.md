# Luke Wang — personal website

Personal academic and engineering website at **https://lukewangw.github.io/**.

## Edit

- `index.html`: biography, research, projects, experience, and education.
- `styles.css`: responsive layout and typography.
- `assets/`: lightweight SVG illustrations for research and featured projects. Signals and traces are schematic illustrations.
- `LukeWang.pdf`: the resume linked from the introduction. Replace this file to update the resume.
- `.nojekyll`: serves the plain static files directly on GitHub Pages.

No build step or package installation is required. The website works without JavaScript.

## Preview locally

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open http://127.0.0.1:8000.

## Publish

GitHub Pages publishes the `main` branch from `/ (root)` in the `Lukewangw/Lukewangw.github.io` repository. Commit and push changes to update the live website.

## Content

The initial version summarizes the owner's existing resumes and project descriptions. Research entries describe work in progress and make no publication or benchmark claims. Project links point to the owner's chosen demos and repositories; private repositories require GitHub access. Review role dates and wording when updating the page, and update the footer's revision month.
