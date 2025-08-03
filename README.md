# BiasedBit

Source for [biasedbit.com](https://biasedbit.com).

Built with [Hugo](https://gohugo.io/) and hosted on [GitHub Pages](https://pages.github.com/).

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/biasedbit/biasedbit.github.io.git
   cd biasedbit.github.io
   ```

2. Install tools (if not already installed):

   ```bash
   mise install
   ```

3. Start the development server:

   ```bash
   mise run dev
   ```

4. Build for production:

   ```bash
   mise run build
   ```

The site will be available at `http://localhost:1313` during development.

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions when changes are pushed to the `main` branch.

## Project Structure

```
.
├── .github/workflows/    # GitHub Actions deployment
├── layouts/             # HTML templates
├── static/              # Static files (CSS, images, etc.)
├── hugo.toml           # Hugo configuration
└── .mise.toml          # Tool management configuration
```

## Useful Commands

- `mise dev` - Start development server
- `mise build` - Build for production
- `mise clean` - Complete cleanup

## License

This project is licensed under the MIT License.
