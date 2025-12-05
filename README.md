# TDAbench 2026 Website

A modern, elegant Jekyll website for the TDAbench 2026 workshop on benchmark data sets for machine learning classification of astronomical transients.

**Workshop Dates:** March 9-12, 2026  
**Location:** SkAI Institute, Chicago, IL  
**Website:** https://tdabench.github.io/TDABench2026

## Features

- Modern, responsive design with sleek blue color scheme
- Mobile-friendly with hamburger menu
- Easy-to-update YAML data files for program, participants, and dates
- Animated hover effects and link interactions
- SEO optimized with Jekyll SEO tag
- GitHub Pages compatible

## Local Development

### Prerequisites

- Ruby (2.7 or higher recommended)
- Bundler (`gem install bundler`)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/TDABench/TDABench2026.git
   cd TDABench2026
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000/TDABench2026/`

## Project Structure

```
.
├── _config.yml          # Site configuration
├── _data/
│   ├── dates.yml        # Important dates
│   ├── participants.yml # Participant list
│   └── program.yml      # Workshop schedule
├── _includes/
│   ├── header.html      # Site header/navigation
│   └── footer.html      # Site footer
├── _layouts/
│   └── default.html     # Main layout template
├── _sass/
│   └── main.scss        # Styles (SCSS)
├── assets/
│   ├── css/
│   │   └── main.scss    # CSS entry point
│   └── images/          # Image assets
├── index.html           # Home page
├── program.html         # Program page
├── participants.html    # Participants & Registration
└── travel.html          # Travel & Lodging
```

## Updating Content

### Adding Participants

Edit `_data/participants.yml`:

```yaml
- name: "Dr. Jane Smith"
  affiliation: "University of Chicago"

- name: "Prof. John Doe"
  affiliation: "Caltech"
```

### Updating the Program

Edit `_data/program.yml` to add or modify schedule items:

```yaml
day1:
  date: "Monday, March 9, 2026"
  events:
    - time: "9:00 - 10:00"
      title: "Session Title"
      speaker: "Speaker Name"
      type: "session"
```

### Updating Important Dates

Edit `_data/dates.yml`:

```yaml
- date: "January 15, 2026"
  title: "Registration Opens"
  description: "Early bird registration begins"
```

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Color Scheme

The website uses a blue color palette inspired by the SkAI Institute:

- Primary: `#0a1628` (Deep navy)
- Secondary: `#1a2d4a` (Dark blue)
- Accent: `#2d5a8a` (Medium blue)
- Highlight: `#4a90d9` (Bright blue)
- Light Accent: `#6bb3f0` (Light blue)

## License

© 2026 TDAbench. All rights reserved.
