# My Academic Portfolio

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
   cd portfolio
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
├── _config.yml                         # Main site configuration: title, URL/baseurl, menus, theme settings, plugins
├── _config_dev.yml                     # Local development configuration override
├── home.md                             # Home page content
├── research.md                         # Research page entry point
├── projects.md                         # Projects page entry point
├── posts.md                            # News listing page entry point
├── index.html                          # Root landing/index file used by the site
│
├── _data/
│   ├── authors.yml                     # Author profile data, including sidebar/about text
│   ├── strings.yml                     # Custom labels, icons, and date formats
│   ├── social.yml                      # Social links and related metadata
│   └── variables.yml                   # Theme/site variables used by Hydejack
│
├── _includes/
│   ├── my-head.html                    # Custom additions/overrides in the HTML head
│   ├── my-body.html                    # Custom additions/overrides near the body area
│   ├── features.md                     # Custom reusable markdown include
│   ├── table.md                        # Custom reusable table include
│   ├── body/                           # Overridden body-related include fragments
│   └── components/                     # Overridden Hydejack components used in layouts/meta rendering
│
├── _layouts/
│   ├── research.html                   # Custom layout for the research listing page
│   ├── publication.html                # Custom layout for individual publication pages
│   └── project.html                    # Custom layout for individual project pages
│
├── _publications/
│   └── semantic-grading.md             # Publication/research entry content
│
├── _projects/                          # Individual project entries shown on the Projects page
│   ├── careerbuddy-web-app.md
│   ├── csedu-campus-kin.md
│   ├── csedu-website.md
│   ├── gitgrub.md
│   ├── museum.md
│   ├── price-retail.md
│   └── saving-the-wild.md
│
├── news/
│   └── _posts/                         # News posts/blog-style updates
│
├── _sass/
│   ├── my-inline.scss                  # Custom inline style overrides
│   └── my-style.scss                   # Main custom style overrides for the website
│
├── assets/
│   ├── img/                            # Images used across pages, posts, projects, and publications
│   ├── icons/                          # Custom icons/favicon-related assets
│   └── papers/                         # PDFs or linked paper files
│
├── .github/
│   └── workflows/                      # GitHub Actions workflow(s), usually for deployment/build
│
├── bin/
│   └── dev                             # Local development helper script
│
├── vendor/
│   └── bundle/
│       └── ruby/
│           └── 3.0.0/
│               └── gems/
│                   └── jekyll-theme-hydejack-9.2.1/
│                                          # Installed Hydejack theme source; useful for tracing default theme files
│
├── Gemfile                             # Ruby gem dependencies
├── Gemfile.lock                        # Locked gem versions
├── README.md                           # Project description and setup instructions
├── 404.md                              # Custom 404 page
│
├── _site/                              # Generated static site output; build artifact, not hand-edited
├── .jekyll-cache/                      # Jekyll cache; build artifact
│
├── docs/                               # Hydejack/theme documentation bundled with the starter repo
├── example/                            # Example content from the starter theme
├── licenses/                           # Theme and dependency license files
├── CHANGELOG.md                        # Hydejack/theme changelog
├── LICENSE.md                          # Repository/theme license file
└── NOTICE.md                           # Notices from the theme/package

### Notes

This website is customized from the Hydejack theme to better fit an academic and research-oriented portfolio.