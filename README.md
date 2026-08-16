# DT4MOB Thesis

## Structure

- `template/` — official university LaTeX template goes here (unmodified, as downloaded).
- `main.tex` — top-level document; `\input`s each chapter. Created once the template is in place.
- `chapters/` — one `.tex` file per chapter, kept separate so long-document edits stay scoped.
- `figures/` — images/diagrams referenced from chapters.
- `references.bib` — BibTeX sources.

## Workflow

Chapter-by-chapter: outline a chapter's argument first, draft it grounded in the
dt4mob-twin-viewer repo (commits, code, benchmark data), then review/edit before
moving to the next chapter. Avoid drafting the whole document in one pass.

## Next steps

1. Drop the university LaTeX template into `template/`.
2. Wire `main.tex` to the template's class/style and `\input` the chapter files.
3. Push to Overleaf via git integration when ready.
