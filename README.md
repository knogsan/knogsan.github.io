# Portfolio Website

A personal portfolio website built with Jekyll and hosted on GitHub Pages.

🌐 **Live Site**: [https://knogsan.github.io/](https://knogsan.github.io/)

## About

This is a portfolio website showcasing my work, skills, and experience. The site is built using Jekyll with the Minima theme and is automatically deployed to GitHub Pages.

## Features

- **Works Section**: Showcase of projects and portfolio items
- **Skills Section**: Display of technical skills and expertise
- **About Section**: Personal information and background
- **Responsive Design**: Mobile-friendly layout
- **Jekyll-powered**: Static site generation for fast loading

## Project Structure

```
knogsan.github.io/
├── docs/                    # Jekyll site source files
│   ├── _config.yml         # Jekyll configuration
│   ├── _data/              # Data files for projects
│   ├── _includes/          # Reusable template components
│   ├── _layouts/           # Page layouts
│   ├── _posts/             # Blog posts (if any)
│   ├── _sass/              # Sass stylesheets
│   ├── assets/             # Images, CSS, and JS files
│   ├── index.html          # Homepage
│   ├── about.markdown      # About page
│   └── Gemfile             # Ruby dependencies
└── README.md               # This file
```

## Local Development

To run this site locally for development:

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/knogsan/knogsan.github.io.git
   cd knogsan.github.io
   ```

2. Navigate to the docs directory:
   ```bash
   cd docs
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

5. Open your browser and visit `http://localhost:4000`

### Making Changes

- Edit content in the [`docs/`](docs/) directory
- Modify site configuration in [`docs/_config.yml`](docs/_config.yml)
- Add new projects by updating data files in [`docs/_data/`](docs/_data/)
- Customize styling in [`docs/_sass/`](docs/_sass/)

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. The site is served from the [`docs/`](docs/) directory.

## Technologies Used

- **Jekyll**: Static site generator
- **Minima**: Jekyll theme
- **GitHub Pages**: Hosting platform
- **HTML5/CSS3**: Frontend markup and styling
- **JavaScript**: Interactive functionality

## Contact

- GitHub: [@knogsan](https://github.com/knogsan)
- Twitter: [@knogsan](https://twitter.com/knogsan)
- Email: knogsan@example.com

## License

This project is open source and available under the [MIT License](LICENSE).
