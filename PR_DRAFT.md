# PR Draft: Bootstrap research-pages structure

## Suggested title
`Initialize research-pages scaffold and documentation`

## Suggested body
### What this PR does
- adds initial repository scaffold for standalone research HTML pages
- documents category conventions and naming workflow in `README.md`
- adds root `index.html`, `templates/research-page.html`, and placeholder folders

### Why
This establishes a consistent, low-overhead layout for creating and organizing research pages over time.

### Notes for reviewers
- the structure is intentionally simple and file-based
- future page additions should go under `pages/<category>/`

### Follow-ups
- add first real page under `pages/notes/`
- link category pages from `index.html`
