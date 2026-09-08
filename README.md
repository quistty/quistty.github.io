# David Quist

Personal academic portfolio website built with Jekyll and adapted from the academic theme by LeNPaul.

This repository is a customized version of the original template and no longer matches the default academic structure. The site has been simplified to a personal portfolio layout with separate pages for home, about, projects, and contact.

## Current site structure

- Home page: `index.md` and `_layouts/home.html`
- About page: `about.md` and `_layouts/about.html`
- Projects page: `projects.md` and `_layouts/projects.html`
- Contact page: `contact.md` and `_layouts/contact.html`
- Shared navigation and profile data: `_data/settings.yml` and `_includes/header.html`
- About section: `_includes/about.html` and the social links defined in `_data/settings.yml`

## Files removed or renamed from the original template

The default academic theme files that were removed include:

- `courses.md`
- `cv.md`
- `people.md`
- `publications.md`
- `_layouts/courses.html`
- `_layouts/cv.html`
- `_layouts/people.html`
- `_layouts/about.html`

The site was reworked to use custom pages instead:

- `about.md` replaces the original template content with a personal profile/about section
- `projects.md` replaces project and group-related content
- `_layouts/about.html` and `_layouts/projects.html` define the current custom pages

## Local development

To run this site locally:

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000
```

## Notes

This project keeps the core Jekyll structure from the original academic theme while using a different content model tailored to this site.
