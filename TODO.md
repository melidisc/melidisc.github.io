# Website Improvement Ideas

## Content and messaging
- Tighten the homepage hero copy to highlight a single, strongest value proposition.
- Add a short "Engagement models" section with typical scopes and timelines.
- Add 1–2 concrete case studies or outcomes (anonymized if needed).
- Add a short "Services overview" paragraph to the About page to reduce repetition.
- Add a concise "Featured Publications" list on the homepage linked to `/publication/`.

## UX and navigation
- Add an anchor-based quick nav on the homepage for the main sections.
- Add a CTA button in the top navigation (e.g., "Book a call").
- Create a "News" page that embeds a viewport of recent posts from X.
- Ensure publication page links (PDF, code, slides) are consistently populated.
- Add a "Back to top" link on long pages like experience and publications.

## Visual design
- Convert large Markdown sections into cards or columns for better scanning.
- Add small icons for the Services section to reduce text density.
- Standardize heading sizes across landing pages for consistent hierarchy.
- Add a subtle divider or background alternation between major sections.

## Performance and SEO
- Ensure every page has a unique meta description in frontmatter.
- Add `featured.jpg/png` for all publications to improve preview cards.
- Check that `static/images/site-thumbnail.png` matches current branding.
- Add Open Graph images for key landing pages.

## Accessibility and maintainability
- Replace inline styles in `content/_index.md` with reusable CSS classes.
- Add alt text for all images and verify contrast in dark mode.
- Move repeated CTA HTML blocks into a shortcode to keep pages DRY.
