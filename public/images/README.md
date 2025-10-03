# Images Directory

This directory contains all static images for the TBMC website.

## Structure

```
static/
├── images/
│   ├── posts/           # Post cover images
│   ├── pages/           # Page images
│   └── general/         # General site images
```

## Adding Cover Images to Posts

To add a cover image to a post, add the `cover` parameter to the front matter:

```yaml
---
title: "Your Post Title"
description: "Post description"
author: "Author Name"
date: "2025-10-03T21:10:06+04:00"
cover: "/images/posts/your-image.jpg"
---
```

## Image Guidelines

- **Format**: Use JPG or PNG
- **Size**: Recommended 1200x630px for post covers
- **File naming**: Use descriptive names with hyphens (e.g., `bitcoin-lecture-cover.jpg`)
- **Optimization**: Compress images before uploading for better performance

## Example

For a post about Bitcoin lectures, you might use:
- File: `static/images/posts/bitcoin-lecture-cover.jpg`
- Front matter: `cover: "/images/posts/bitcoin-lecture-cover.jpg"`
