# Hugo Tufte Theme Site

Site built with the [hugo-tufte](https://github.com/loikein/hugo-tufte) theme.

## Quick Start

### Running the Local Server

```bash
hugo server --buildDrafts --disableFastRender
```

After starting, open your browser at `http://localhost:1313/`

### Creating a New Post

```bash
hugo new posts/post-name.md
```

### Building for Production

```bash
hugo
```

Generated files will be in the `public/` folder.

## Project Structure

- `config.yaml` - site configuration
- `content/` - site content (posts, pages)
- `themes/hugo-tufte/` - Hugo Tufte theme
- `static/` - static files (CSS, JS, images)
- `layouts/` - custom templates (optional)

## Configuration

Main parameters are configured in the `config.yaml` file:

- `title` - site title
- `params.subtitle` - subtitle
- `params.math` - enable/disable LaTeX support
- `params.codeblocksdark` - dark theme for code blocks
- `menu.nav` - navigation menu

## Theme Documentation

Full documentation and examples are available in the `themes/hugo-tufte/exampleSite/` folder.

