# Editing Guide for This Site

This site uses Hugo with Hugo Blox (Academic CV). Most content is Markdown in `content/` and site-wide settings live in `config/_default/`.

## Where to edit

- Homepage sections: `content/_index.md`
- About page: `content/about.md`
- Experience page: `content/experience.md`
- Publications landing page: `content/publication/_index.md`
- Individual publications: `content/publication/<slug>/index.md`
- Author profile and resume data: `content/authors/admin/_index.md`
- Navigation menu: `config/_default/menus.yaml`
- Site metadata (title/base URL): `config/_default/hugo.yaml`
- SEO, analytics, header/footer: `config/_default/params.yaml`
- Custom styles: `layouts/partials/hooks/head-end/custom-styles.html`
- Custom shortcodes reference: `layouts/SHORTCODES.md`

## How to edit pages

### Landing pages (`content/_index.md`, `content/about.md`, `content/experience.md`, `content/publication/_index.md`)
- Each page defines `sections:` with `block:` types like `markdown` or `resume-biography-3`.
- Update text inside `content.text` using Markdown (HTML is used in a few places for layout and buttons).
- Keep existing `design:` keys unless you need layout changes.

### Publications
- Each publication lives at `content/publication/<slug>/index.md`.
- Update the frontmatter fields like `title`, `date`, `publication`, `doi`, and `abstract`.
- Add a `featured.jpg/png` in the same folder to show a thumbnail.

### Experience data (profile-driven)
- The resume-style data is in `content/authors/admin/_index.md` under `work`, `education`, and `awards`.
- If you use the built-in Hugo Blox resume blocks, keep the date format as `YYYY-MM-DD`.

### Custom shortcodes
- Reusable shortcodes are documented in `layouts/SHORTCODES.md`.
- The experience shortcode is defined at `layouts/shortcodes/experience-item.html`.

## Style conventions

- Use sentence case for headings.
- Keep lists short and scannable.
- Prefer consistent emoji usage per section (the current pages use emoji icons in headings).
- Preserve existing HTML blocks for buttons and special layout.

## Common tasks

### Update the homepage CTA email
- Edit the `mailto:` link in `content/_index.md` under the first and last sections.

### Add a new publication
1. Create a new folder in `content/publication/` with `index.md`.
2. Copy frontmatter from an existing publication and update fields.
3. Add `featured.jpg/png` if you want a thumbnail.

### Change menu labels or order
- Update `config/_default/menus.yaml` and adjust `weight`.
