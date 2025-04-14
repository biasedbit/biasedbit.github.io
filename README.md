# Personal page

Personal page built with Jekyll and hosted on GitHub Pages.

## Prerequisites

- Ruby 3.4.2 or higher
- Bundler
- Git

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/biasedbit/biasedbit.github.io.git
   cd biasedbit.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

## Development

To run the site locally:

```bash
bundle exec jekyll serve
```

This will start a local server at `http://localhost:4000`. The site will automatically rebuild when you make changes to the source files.

## Building for Production

To build the site for production:

```bash
bundle exec jekyll build
```

The built site will be available in the `_site` directory.

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No manual deployment is needed.

## Project Structure

- `_includes/` - Reusable components
- `_layouts/` - Page templates
- `_sass/` - SCSS files
- `css/` - Compiled CSS files
- `images/` - Image assets
- `_config.yml` - Site configuration
- `index.html` - Homepage
