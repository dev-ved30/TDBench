# TDAbench 2026 Website

A modern Jekyll website for the TDAbench 2026 workshop.

## Project Structure

- `_config.yml` - Jekyll configuration
- `_data/` - YAML data files (dates, participants, program)
- `_includes/` - Reusable HTML components (header, footer)
- `_layouts/` - Page layout templates
- `_sass/` - SCSS stylesheets
- `assets/` - CSS and images
- `index.html` - Home page
- `program.html` - Program page
- `participants.html` - Participants & Registration page
- `travel.html` - Travel & Lodging page

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

Push to the `main` branch of the TDABench2026 repository for automatic GitHub Pages deployment.

## Updating Content

- **Participants:** Edit `_data/participants.yml`
- **Program:** Edit `_data/program.yml`
- **Important Dates:** Edit `_data/dates.yml`
