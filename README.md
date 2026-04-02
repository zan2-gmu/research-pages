# Research Pages

This repository stores standalone HTML pages that I create for my research.

The logic is simple:

- each page is one HTML file
- pages are grouped by category
- each page can be linked directly from other documents

## Categories

Use these folders inside `pages/`:

- `pages/notes/` for short research notes, observations, or working thoughts
- `pages/reviews/` for literature reviews, comparisons, or summaries
- `pages/references/` for curated reference pages or source collections
- `pages/experiments/` for test pages, prototypes, demos, or result pages

If a page could fit in more than one category, choose the folder that matches
its main purpose.

## Structure

```text
/
|-- LICENSE
|-- README.md
|-- index.html
|-- pages/
|   |-- notes/
|   |-- reviews/
|   |-- references/
|   |-- experiments/
|   `-- shared/
|-- drafts/
`-- templates/
```

## Naming

Use short descriptive filenames:

```text
topic-slug.html
```

Examples:

```text
pages/notes/attention-mechanism-notes.html
pages/reviews/alignment-literature-review.html
pages/references/benchmark-datasets.html
pages/experiments/tokenization-visualizer.html
```

## Workflow

1. Create a page in the category that fits best.
2. Keep the filename stable once you start citing it from another document.
3. Use `drafts/` for unfinished pages.
4. Use `pages/shared/` for CSS, JS, or images reused by multiple pages.

## Why This Structure

This is meant to stay easy:

- categories are based on page type
- links remain predictable
- the repo stays easy to browse
- you do not need a complex system to keep growing it
