![Multiverse by HTML5UP](https://repository-images.githubusercontent.com/192228387/23ca0280-91f4-11e9-86e0-afcf90e961ad)

# Vinicius Libero - Web Developer Portfolio

[![Build Status](https://travis-ci.com/liberom/portfolio.svg?branch=master)](https://travis-ci.com/liberom/portfolio)

Portfolio website showcasing full-stack Rails applications, AI projects, and web development expertise. Built with Jekyll and the [Multiverse](https://html5up.net/multiverse) template by [HTML5 UP](https://html5up.net).

**Live Site:** https://liberom.github.io/portfolio (coming soon)

## About This Portfolio

This portfolio showcases a range of projects including:

- **Brasiguay** - Social network for Brazilians relocating to Paraguay (Rails 7.1.3)
- **Invoo** - Financial analysis platform analyzing company statements (Rails 5.2.2)
- **ByMyHonor** - Full-stack web application (Rails 6.1.4)
- **Call Invest** - Investment tracking and analysis system (Rails 6.0.1)
- **Dev Blog** - Personal knowledge base and technical blog (Jekyll)

## How to Update the Portfolio

### Adding/Updating Project Entries

Each portfolio item is its own markdown *post*:

1. **Metadata** goes in the [`_images`](_images) folder (e.g., `01.md`, `02.md`)
2. **Project images** go in [`assets/images`](assets/images) folder (thumbnails and full-size versions)

### Edit a Project Entry

Edit files in the `_images` folder. Each file has this structure:

```markdown
---
title: Project Name
caption: Project description, tech stack, and key features
link: https://github.com/username/project
---
```

### Add a New Project Entry

1. Create a new file in `_images/` (e.g., `06.md`)
2. Add the front matter with title, caption, and GitHub link
3. Add corresponding images to `assets/images/` (thumbnail and full-size)

### Update Site Configuration

Edit `_config.yml` to update:
- Site title and description
- Author name and email
- Social media links (GitHub, LinkedIn, Twitter)
- Language settings (currently supports Portuguese and English)

## Development

### Local Setup

```bash
bundle install
bundle exec jekyll serve
```

Site will be available at `http://localhost:4000`

### Build for Production

```bash
bundle exec jekyll build
```

Output goes to `_site/` directory.

### Testing

```bash
# Build and validate HTML links
bundle exec jekyll build
bundle exec htmlproofer ./_site/
```

## Deployment

This site is configured for GitHub Pages deployment. To deploy:

1. Push to the repository
2. Travis CI will automatically build and deploy on `master` branch

## Template Information

- **Template:** Multiverse by HTML5 UP
- **Static Site Generator:** Jekyll 4.1
- **Plugins:** jekyll-feed, jekyll-seo-tag, jekyll-multiple-languages-plugin
- **Languages:** Portuguese & English

## License

See LICENSE file for details.
