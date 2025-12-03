# Website DRY Improvements

This document outlines the DRY (Don't Repeat Yourself) improvements made to the website.

## Implemented Improvements

### 1. Custom Shortcodes

Several shortcodes were created to reduce duplication in content files:

- **experience-item**: A shortcode for displaying work or educational experience consistently
- **featured-image**: A shortcode for displaying images with captions and credits
- **publication-links**: A shortcode for displaying publication resources like PDF, code, etc.

### 2. Missing Templates

Fixed missing template issues:

- Added `partials/views/4.html` for the citation view in publications
- Added supporting partials `page_metadata_authors.html` and `page_links.html`
- Added view fragments `views/4.start.html` and `views/4.end.html`

### 3. Standardized Archetypes

Created standardized archetypes to ensure consistency:

- **publication/index.md**: A template for creating new publications
- **experience.md**: A template for creating new experience pages
- **post/index.md**: A template for creating new blog posts

### 4. Documentation

Added documentation for all new components:

- **SHORTCODES.md**: Documentation of all shortcodes and how to use them
- **Example post**: Added an example post that demonstrates shortcode usage

### 5. Custom Styles

Added custom styles for all new components:

- Created a central stylesheet in `partials/hooks/head-end/custom-styles.html`

## Benefits

These improvements provide the following benefits:

1. **Consistency**: All similar content is now formatted consistently
2. **Maintainability**: Changes to layouts only need to be made in one place
3. **Reduced Duplication**: Common patterns have been extracted into reusable components
4. **Better Developer Experience**: Clear documentation and examples make it easier to add new content

## Example Usage

See `/content/post/example-with-shortcodes/index.md` for examples of how to use the new shortcodes.

## Next Steps

Consider implementing the following additional improvements:

1. Migrate existing content to use the new shortcodes
2. Extract more common patterns into shortcodes
3. Create additional archetypes for other content types