# Freelance Work collection

The portfolio's **Freelance Work** card opens a collection of client projects.
Client details are defined in `freelanceClients` in the site's `index.html`.

## Kings Elevator

- `kings-elevator/brochure/1.jpg` through `24.jpg`: company brochure.
- `kings-elevator/sales-sheet-compact/1.jpg`: 6.5 × 9 inch sales sheet.
- `kings-elevator/sales-sheet-letter/1.jpg`: letter-size sales sheet.

## PetBrick

- `petbrick/campaign/1.jpg` and `2.jpg`: the two complete campaign presentation pages.
- `petbrick/cover.webp`: a small preview of the campaign's opening section.
- Source: `New Projects/Cat Brick/CatBrick Draft Vol 23.pdf`.

## MaisonEnamel

- `maison-enamel/brand/`: logo, clock and peacock profile images, and three shop banner variations.
- `maison-enamel/clock-catalog/1.jpg` through `14.jpg`: bilingual clock catalog.
- `maison-enamel/cover.webp`: a small shop banner preview.
- Sources: `New Projects/Esty Brand/01-Brand/` and its `Final` folder, plus `EtsyClock-Catalog-English-Chinese.pdf`.

## Walker

- `walker/phone/`: onboarding and app/training boards.
- `walker/tablet/`: onboarding and app/training boards.
- `walker/cover.webp`: a small phone onboarding preview.
- Source: the four PNG boards in `New Projects/Walker/`.

PDF pages are served as JPG previews; standalone artwork is served as WebP while
preserving its original dimensions. Each preview has a full-size image link.
Original files remain in the local `New Projects` folder. Source notes, generation
prompts and duplicate ZIP contents are not published as portfolio assets.

## Add another client

1. Create a folder under `assets/projects/freelance/` using a short lowercase client name.
2. Export each document's pages as JPGs, numbered `1.jpg`, `2.jpg`, and so on.
3. Add a client to the `freelanceClients` array with `id`, `name`, `category`,
   `description`, `cover`, and a `documents` array.
4. For a numbered PDF preview, provide `title`, `path` (ending in `/`), `pages`
   (the exact count), and `ratio` (page width divided by page height). Use
   `spread: true` instead of `ratio` for A4 portrait covers with A3 landscape interiors.
   For individual artwork or screen boards, provide `title` and an `images` array;
   each image needs `src`, `width`, `height`, and a descriptive `label`.
5. Preview the collection and verify every document before publishing.

Client cards and document buttons are generated automatically from this data.
Freelance documents are not subject to the existing project gallery's 20-page limit.
