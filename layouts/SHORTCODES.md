# Custom Layouts and Shortcodes

This directory contains custom layouts, partials, and shortcodes for this website.

## Custom Shortcodes

### Experience Item

Used for displaying work or educational experience in a consistent format.

```
\{\{< experience-item 
  title="Job Title"
  company="Company Name"
  link="https://company-website.com"
  location="City, Country"
  startDate="Jan 2020"
  endDate="Present"
>\}\}
* Responsibility or achievement 1
* Responsibility or achievement 2
* Responsibility or achievement 3
\{\{< /experience-item >\}\}
```

### Featured Image

Used for displaying images with captions and credits consistently.

```
\{\{< featured-image 
  src="image.jpg" 
  caption="Image caption" 
  credit="Source Name" 
  link="https://link-to-source.com" 
  width="80%" 
  class="additional-class"
>\}\}
```

### Publication Links

Used for displaying consistent publication links and resources.

```
\{\{< publication-links 
  pdf="https://example.com/paper.pdf" 
  code="https://github.com/example/code" 
  dataset="https://example.com/dataset"
  poster="https://example.com/poster" 
  project="https://example.com/project" 
  slides="https://example.com/slides" 
  source="https://example.com/source" 
  video="https://example.com/video" 
>\}\}
```

## Custom Partials

### Citation View

Located at `partials/views/4.html`, this partial fixes the missing citation view for publications.

### Custom Experience Block

Located at `partials/blox/experience-custom.html`, this is a custom implementation of the experience block with improved DRY principles.

## Custom Styles

Custom styles for all shortcodes and components are located in `partials/hooks/head-end/custom-styles.html`.

## Example Usage

See `/content/post/example-with-shortcodes/index.md` for a complete example of how to use these shortcodes.