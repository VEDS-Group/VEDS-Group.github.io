# VEDS-Group Documentation

This repository contains the official documentation website for VEDS-Group, hosted on GitHub Pages.

## Structure

```
├── cubecharging/          # CubeCharging project documentation
│   ├── index.md          # Changelog and overview
│   ├── laadpas/          # Laadpas Management docs
│   └── laadpaal/         # Laadpaal Management docs
├── assets/               # CSS, JS, and other assets
├── _layouts/             # Jekyll layouts
├── _includes/            # Jekyll includes
├── _config.yml           # Jekyll configuration
└── index.md              # Main homepage
```

## Local Development

### Prerequisites
- Ruby 3.4+ with RubyInstaller
- Git

### Setup
1. Clone the repository
2. Install dependencies: `bundle install`
3. Start local server: `bundle exec jekyll serve`
4. Open http://localhost:4000

### Features
- **Dark Mode**: Toggle button in top-right corner
- **Sidebar Navigation**: Per-page navigation for easy browsing
- **Responsive Design**: Works on all screen sizes
- **Professional Styling**: Clean, modern design

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### What gets deployed:
- All `.md` files
- `_config.yml`
- `_layouts/` directory
- `_includes/` directory
- `assets/` directory
- `CNAME` file

### What's ignored:
- `_site/` (generated files)
- `Gemfile.lock`
- `node_modules/`
- IDE files
- OS files
- Logs and temporary files

## Adding New Projects

To add documentation for new clients/projects:

1. Create a new folder (e.g., `clientname/`)
2. Add project-specific documentation
3. Update `_config.yml` header_pages
4. Update `_includes/header.html` navigation
5. Update main `index.md` with project links

## Contributing

1. Make changes locally
2. Test with `bundle exec jekyll serve`
3. Commit and push to `main` branch
4. GitHub Pages will automatically rebuild

## Support

For issues or questions, contact the VEDS-Group development team.
