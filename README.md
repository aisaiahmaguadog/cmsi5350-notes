# CMSI 5350 — Machine Learning

LMU, Fall 2026. Personal notes, in-class notebooks, and project work for the course.
Homework submissions are handled separately (see below) and aren't part of this repo.

## Course topics

Covers the fundamentals of machine learning: exploratory data analysis, baseline and
linear classifiers, regression, model evaluation/training error, and building up to more
advanced supervised learning methods over the semester.

## Organization

- `Lectures/` — lecture slides and notes
- `Notebooks/` — in-class Colab `.ipynb` notebooks (from the professor's live coding)
- `Projects/` — course projects
- `cmsi5350_env/` — local Python virtual environment for running notebooks/assignments (not tracked in git)

## Homework

Homework isn't stored in this repo. Each assignment is auto-generated as its own GitHub
repo under the `cmsi-5350-fall-2026` org via lmu.postcommit.ai, and graded by pushing to
that repo directly. Clone each one into its own folder under `Homework/` (gitignored here):

```
cd Homework
git clone https://github.com/cmsi-5350-fall-2026/<repo-name>.git
```

Note: org-created repos don't show up under "your repositories" on GitHub unless you
star/watch them — that's expected, not a misconfiguration.

## Saving notebooks from Colab

For files in `Notebooks/`, use Colab's **File → Save a copy in GitHub** to commit directly
to this repo instead of downloading and re-uploading manually.
