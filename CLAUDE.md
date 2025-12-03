# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Build Commands
- Start local server: `cd my-website && hugo server`
- Build site: `cd my-website && hugo --gc --minify`
- Build with specific URL: `cd my-website && hugo --gc --minify -b $URL`
- Test single page: `cd my-website && hugo server --buildDrafts --disableFastRender -p 1313`

## Content Guidelines
- Markdown files (.md) in content/ define site pages
- Front matter uses YAML syntax between --- delimiters
- Use Hugo shortcodes for advanced formatting: {{< shortcode >}}
- Place images in assets/ or static/ depending on processing needs

## Code Style
- Follow existing file structure and naming conventions
- Use kebab-case for filenames and directories
- YAML formatting: 2-space indentation
- Markdown: Use ATX-style headings (# H1, ## H2)
- Maintain clear content organization with frontmatter for metadata

## Best Practices
- Test changes locally before deployment
- Optimize images before adding to repository
- Use Hugo partial templates for reusable components
- Maintain backward compatibility with existing content