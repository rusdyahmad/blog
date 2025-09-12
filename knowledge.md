# Rusdy Blog Project

This is a Hugo static site generator blog project using the PaperMod theme.

## Project Structure

- `content/posts/` - Blog post markdown files
- `themes/PaperMod/` - Hugo theme (git submodule)
- `public/` - Generated static site files
- `hugo.toml` - Hugo configuration
- `static/` - Static assets
- `layouts/partials/` - Custom layout partials

## Development Workflow

- Use `hugo server` for local development with live reload
- Posts are written in markdown in `content/posts/`
- The site is built to `public/` directory
- Uses Google Analytics (GA4) with ID: G-JP295JCT48

## Theme Customization

- Custom CSS in `assets/css/extended/custom.css`
- Custom head extensions in `layouts/partials/extend_head.html`
- Active menu state styling for Posts navigation

## Content Guidelines

- Posts should have proper frontmatter with title, date, categories, and tags
- Images should be optimized and placed in appropriate directories
- Use descriptive filenames for SEO

## Deployment

- Static files are generated in `public/` directory
- CNAME file indicates custom domain deployment
- Build process: `hugo` command generates the site