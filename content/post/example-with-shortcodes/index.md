---
title: "Example Post Using Shortcodes"
subtitle: "A demonstration of DRY content with shortcodes"
summary: "This post demonstrates how to use the custom shortcodes to maintain DRY content across the website."
authors:
  - admin
tags:
  - Example
  - Hugo
  - Shortcodes
categories:
  - Documentation
date: 2025-04-25T00:00:00Z
featured: false
draft: true

# Featured image
image:
  caption: "Example featured image"
  focal_point: "Center"
  placement: 2
  preview_only: false

# Projects (optional).
projects: []
---

## Introduction

This is an example post that demonstrates how to use the custom shortcodes created to maintain DRY (Don't Repeat Yourself) principles across the website.

## Featured Image Example

{{< featured-image src="featured.jpg" caption="This is a featured image with a caption" credit="Unsplash" >}}

## Experience Item Example

Here's how to use the experience item shortcode:

{{< experience-item 
  title="Senior Machine Learning Scientist"
  company="Example Company"
  link="https://example.com"
  location="Remote"
  startDate="Jan 2022"
  endDate="Present"
>}}
* Responsibility 1
* Responsibility 2
* Responsibility 3
{{< /experience-item >}}

## Publication Links Example

Here's how to use the publication links shortcode:

{{< publication-links 
  pdf="https://example.com/paper.pdf" 
  code="https://github.com/example/code" 
  dataset="https://example.com/dataset"
  slides="https://example.com/slides" 
>}}

## Benefits of Using Shortcodes

Using shortcodes provides several benefits:

1. **Consistency**: All similar content is formatted the same way
2. **Maintainability**: Changes to layout only need to be made in one place
3. **Simplicity**: Content creators don't need to remember complex HTML
4. **Extensibility**: New features can be added to shortcodes without changing content

## Conclusion

By implementing these shortcodes, we've significantly improved the DRY principles in this website, making it easier to maintain and extend in the future.