# SMS-Based Fraud Detection Practical Training Report Template

This project is a compilable university technical-report template. It intentionally contains no invented organizational facts, datasets, technologies, measurements, or model results.

## Project structure

```text
.
├── main.tex
├── references.bib
├── chapters/
│   ├── chapter01-introduction.tex
│   ├── chapter02-context.tex
│   ├── chapter03-requirements.tex
│   ├── chapter04-design-methodology.tex
│   ├── chapter05-implementation.tex
│   ├── chapter06-testing-results.tex
│   ├── chapter07-discussion.tex
│   └── chapter08-conclusion.tex
├── appendices/
│   ├── appendix-a-supporting-evidence.tex
│   └── appendix-b-code-and-configuration.tex
├── figures/
└── code/
```

## Compile

With MacTeX or TeX Live:

```bash
latexmk -pdf main.tex
```

The template uses `biblatex` with `biber`. Add verified sources to `references.bib`, cite them with `\parencite{key}` or `\textcite{key}`, and run `latexmk` again.

## Replacing placeholders

- Replace metadata commands near the top of `main.tex`.
- Replace `\placeholder{...}`, `\insertplaceholder{...}`, and `[INSERT ...]` text with verified project information.
- Add figures under `figures/` and update the corresponding `\insertfigure` path.
- Add short, sanitized code excerpts under `code/` if required.
- Do not include credentials, private identifiers, unredacted SMS content, or entire source files.
- Remove optional sections that do not apply, but preserve the technical narrative and cross-references.
