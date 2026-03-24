# Meherun Farzana — Academic Portfolio

This repository contains my personal academic portfolio website, built with Jekyll and the Hydejack theme. It presents my academic background, research interests, publications, projects, news, and selected activities.

## Website

Live site: [reckless-meherun.github.io](https://reckless-meherun.github.io/)

## Overview

This portfolio includes:

- a home page with a short academic profile
- a research section for publications and ongoing work
- a projects section for selected technical and research projects
- a news section for recent updates and milestones
- custom styling and layout modifications built on top of Hydejack

## Tech Stack

- Jekyll
- Hydejack
- Markdown
- HTML/CSS
- GitHub Pages

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/reckless-meherun/meherunfarzana.portfolio.git
2. Go to the project directory:
   ``` bash
   cd reckless_meherun
3. Install dependencies:
    ```bash
    bundle install
4. Run the local server:
   ```bash
   bundle exec jekyll serve --port 4002
5. Open in browser:
    ```bash
    http://127.0.0.1:4002/
## Repository Structure
```bash
.
├── _config.yml              # Main site configuration
├── _data/
│   ├── authors.yml          # Author profile and about section data
│   └── strings.yml          # Theme strings, icons, and date formats
├── _includes/               # Reusable overridden layout components
├── _layouts/
│   ├── project.html         # Custom project page layout
│   ├── publication.html     # Custom publication page layout
│   └── research.html        # Custom research listing layout
├── _posts/                  # News posts
├── _publications/           # Research and publication entries
├── _projects/               # Project entries
├── assets/                  # Images, CSS, and other static files
└── vendor/bundle/ruby/3.0.0/gems/jekyll-theme-hydejack-9.2.1/
                           # Hydejack theme source used by the site

### Notes

This website is customized from the Hydejack theme to better fit an academic and research-oriented portfolio.