# Claude instructions for this repository

This repository contains an Overleaf LaTeX project.

## Editing scope

You may edit:
- `.tex` files
- `.bib` files
- `.sty` and `.cls` files
- Markdown documentation files

Do not edit generated/build files, including:
- `.aux`
- `.log`
- `.out`
- `.toc`
- `.bbl`
- `.blg`
- `.bcf`
- `.run.xml`
- `.synctex.gz`
- generated PDFs unless explicitly requested

## LaTeX rules

- Preserve citation keys unless explicitly asked to change them.
- Preserve labels, refs, equations, tables, figures, and cross-references.
- Do not delete comments unless they are clearly obsolete.
- Do not rewrite large sections without explicit instruction.
- Keep terminology consistent across the document.
- Keep Czech and English text in the language already used in the edited section.
- Prefer minimal, reviewable changes over broad rewrites.

## Workflow

- Create a new branch for each task.
- Do not push directly to `main`.
- Open a pull request for all changes.
- In the pull request description, summarize:
  - what was changed
  - why it was changed
  - which files were touched
  - any risks or things the author should review

## Compilation

After edits, check whether the LaTeX project is likely to compile.
If compilation cannot be run, state that explicitly in the pull request description.
