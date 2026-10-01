# Luke Wang — personal website

Personal academic and engineering website at **https://lukewangw.github.io/**.

## Edit

- `index.html`: biography, research, projects, experience, and education.
- `styles.css`: responsive layout and typography.
- `assets/`: a measured TorchScope benchmark plot and a screenshot of the PillarFortune application.
- `LukeWang.pdf`: the resume linked from the introduction. Replace this file to update the resume.
- `.nojekyll`: serves the plain static files directly on GitHub Pages.

No build step or package installation is required. The website works without JavaScript.

## Project images

- `torchscope-throughput.svg` plots median output throughput from the three repeats of `eager-bs1`, `eager-bs4`, and `eager-bs16` in [TorchScope session 20260930-021147](https://github.com/Lukewangw/gpu/tree/main/results/cpu-reference/20260930-021147). The measurements are 42.8, 104.4, and 181.7 tokens/s on a 4-vCPU Xeon, using PyTorch eager and a 134M-parameter random model in fp32. These are CPU reference results.
- `pillarfortune-app.jpg` is a screenshot captured from the [live application](https://lukewangw.github.io/PillarFortune/) in offline mode on September 30, 2026, using a built-in example question. The card artwork is Pamela Colman Smith's Rider–Waite–Smith tarot (1909), in the public domain.

## Preview locally

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open http://127.0.0.1:8000.

## Publish

GitHub Pages publishes the `main` branch from `/ (root)` in the `Lukewangw/Lukewangw.github.io` repository. Commit and push changes to update the live website.

## Content

The initial version summarizes the owner's existing resumes and project descriptions. Research entries describe work in progress and make no publication or benchmark claims. Project links point to the owner's chosen demos and repositories; private repositories require GitHub access. Review role dates and wording when updating the page, and update the footer's revision month.
