# Editing Guide for This Site

This site uses Hugo with Hugo Blox (Academic CV). Most content is Markdown in `content/` and site-wide settings live in `config/_default/`.

## Where to edit

- Homepage sections: `content/_index.md`
- About page: `content/about.md`
- Experience & Credentials page (canonical resume): `content/experience.md`
- Publications landing page: `content/publication/_index.md`
- Individual publications: `content/publication/<slug>/index.md`
- Author profile and resume data (single source of truth for work/education/patents): `content/authors/admin/_index.md`
- Navigation menu: `config/_default/menus.yaml`
- Site metadata (title/base URL): `config/_default/hugo.yaml`
- SEO, analytics, header/footer, appearance (dark/light default, color theme): `config/_default/params.yaml`
- Custom styles (palette, cards, buttons): `layouts/partials/hooks/head-end/custom-styles.html`
- Custom shortcodes reference: `layouts/SHORTCODES.md`

## Current site structure (consulting-focused)

- Homepage: `content/_index.md`
- Services (lead-gen): `content/services.md`
- About (narrative intro): `content/about.md`
  - Bio card + condensed highlights (current role + 2-3 standout achievements)
  - Links out to `/experience/` (full history) and `/publication/` (full research record) — does **not** repeat them
- Experience & Credentials (canonical resume): `content/experience.md`
  - Bio card, full work + education timeline (`resume-experience` block), patents + conference papers (`resume-awards` block), external links
  - `/work/` and `/credentials/` alias to this page (see `aliases:` in its front matter) — those separate pages were retired because they duplicated this content
- Blog (Substack landing): `content/blog.md`
- Publications (canonical full list): `content/publication/_index.md` and `content/publication/<slug>/index.md`
  - Patents/conference papers render from the same `resume-awards` data as the Experience page (not retyped)
  - Journal publications are a short curated list linking to each publication's own detail page

## DRY principle: one source of truth per fact

This site previously had the same job history, patents, and bio repeated (with drifting wording) across About, Experience, Work, and Credentials pages. That's fixed structurally, not just cosmetically — keep it that way:

- **Work history, education, patents, and conference papers** live *only* in `content/authors/admin/_index.md` (`work`, `education`, `awards` params). Render them with the `resume-experience` and `resume-awards` blocks wherever they're needed — never hand-type a job or patent entry into a page's Markdown.
- **Journal publications** live *only* in `content/publication/<slug>/index.md` (title, authors, abstract, doi, etc.). The `/publication/` list page shows a short blurb + link to each page — don't copy the abstract into the list page.
- Other pages (About, homepage) should **link to** `/experience/` or `/publication/` for the full record, not restate it. A one-line highlight referencing a role is fine; a re-typed job card is not.
- If you need the same data in a new place, prefer adding a `resume-experience` / `resume-awards` block over copy-pasting Markdown.

## Session learnings / gotchas

- **`collection` block formatting**: embedding a `collection` block inside a combined page (e.g. About) previously rendered as unformatted concatenated text. Untested since then — if you want to auto-list publications instead of the curated list, test it in isolation first.
- **Substack posts**: for visible post previews, use Stackblocks embed (`<div class="stackblocks-embed" ...></div>` + `https://frame.stackblocks.app/frame.js`) rather than the Substack `/embed` iframe (signup only).
- **Hero logo asset**: the homepage hero uses `static/images/logos/neuralthmics_logo2.png` (note the filename typo — intentional to match the existing file, don't silently "fix" it without updating both the file and the reference). It's dark-colored artwork, so `.hero-logo-wrap` in `custom-styles.html` gives it a white backdrop card in dark mode — don't remove that or the logo becomes unreadable.
- **Site width**: global width changes live in `layouts/partials/hooks/head-end/custom-styles.html`.
- **Menu philosophy**: keep the main menu compressed for conversion (currently Services / About / Experience / Blog / Contact in `config/_default/menus.yaml`).
- **Publication type codes**: `publication_types` must use CSL-style strings (`paper-conference`, `article-journal`, `article`, `report`, `book`, `chapter`, `thesis`, `patent`) — the theme's i18n only translates those. Numeric codes (legacy Academic CV convention) render as raw numbers to visitors.

## How to edit pages

### Landing pages (`content/_index.md`, `content/about.md`, `content/experience.md`, `content/publication/_index.md`)
- Each page defines `sections:` with `block:` types like `markdown`, `resume-biography-3`, `resume-experience`, or `resume-awards`.
- Update text inside `content.text` using Markdown (HTML is used in a few places for layout and buttons).
- Keep existing `design:` keys unless you need layout changes.

### Publications
- Each publication lives at `content/publication/<slug>/index.md`.
- Update the frontmatter fields like `title`, `date`, `publication`, `doi`, and `abstract`.
- Add a `featured.jpg/png` in the same folder to show a thumbnail.
- After adding one, add a short blurb + `[Read full abstract →](/publication/<slug>/)` link to `content/publication/_index.md`'s Journal Publications section.

### Experience data (profile-driven — the single source of truth)
- The resume-style data is in `content/authors/admin/_index.md` under `work`, `education`, and `awards`.
- Add/edit a job here once; it appears everywhere `resume-experience` is used (currently just `/experience/`).
- Add/edit a patent or conference paper in `awards` once; it appears everywhere `resume-awards` is used (`/experience/` and `/publication/`).
- Date fields use `YYYY-MM-DD`.

### Custom shortcodes
- Reusable shortcodes are documented in `layouts/SHORTCODES.md`.
- The experience shortcode is defined at `layouts/shortcodes/experience-item.html`.

## Style conventions

- Use sentence case for headings.
- Keep lists short and scannable.
- No decorative emoji in headings or bullets (dropped sitewide for a more precise, credible tone) — the functional "→" arrow on CTA links is the one exception.
- Preserve existing HTML blocks for buttons and special layout.

## Common tasks

### Update the homepage CTA email
- Edit the `mailto:` link in `content/_index.md` under the first and last sections.

### Add a new job or degree
1. Add an entry to `work` or `education` in `content/authors/admin/_index.md`.
2. It renders automatically on `/experience/` via the `resume-experience` block — no other file needs editing.

### Add a new patent or conference paper
1. Add an entry to `awards` in `content/authors/admin/_index.md`. Link `url` to the matching `/publication/<slug>/` page if one exists.
2. It renders automatically on `/experience/` and `/publication/` via the `resume-awards` block.

### Add a new publication
1. Create a new folder in `content/publication/` with `index.md`.
2. Copy frontmatter from an existing publication and update fields (use CSL-style `publication_types`, see gotchas above).
3. Add `featured.jpg/png` if you want a thumbnail.
4. Add a short blurb + link in `content/publication/_index.md`.

### Change menu labels or order
- Update `config/_default/menus.yaml` and adjust `weight`.
