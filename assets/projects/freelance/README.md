# Freelance Work collection

The portfolio's **Freelance Work** card opens a collection of client projects.
Client details are defined in `freelanceClients` in the site's `index.html`.

## Kings Elevator

- `kings-elevator/brochure/1.jpg` through `24.jpg`: company brochure.
- `kings-elevator/sales-sheet-compact/1.jpg`: 6.5 × 9 inch sales sheet.
- `kings-elevator/sales-sheet-letter/1.jpg`: letter-size sales sheet.

These are web previews rendered from the supplied PDFs. Original print PDFs remain
in the local `New Projects` folder. They are not needed to serve the website.

## Add another client

1. Create a folder under `assets/projects/freelance/` using a short lowercase client name.
2. Export each document's pages as JPGs, numbered `1.jpg`, `2.jpg`, and so on.
3. Add a client to the `freelanceClients` array with `id`, `name`, `category`,
   `description`, `cover`, and a `documents` array.
4. For each document, provide `title`, `path` (ending in `/`), `pages` (the exact count),
   and `ratio` (page width divided by page height). Use `spread: true` instead of
   `ratio` for a brochure with A4 portrait covers and A3 landscape interior spreads.
5. Preview the collection and verify every document before publishing.

Client cards and document buttons are generated automatically from this data.
Freelance documents are not subject to the existing project gallery's 20-page limit.
