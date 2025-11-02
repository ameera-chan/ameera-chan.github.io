# Ameera Chan - Personal Website

A clean, minimalist personal website for showcasing cybersecurity work, CTF experiences, and projects.

## Design

This website features a simple, GitHub-inspired dark theme with:
- Clean typography using Inter font
- Minimal color scheme (dark gray background with blue accents)
- Responsive design for all devices
- Easy navigation with sticky header
- Professional layout similar to modern developer portfolios

## Structure

- **Home (`index.md`)**: Main landing page with profile, CTF experience, projects, skills, and certifications
- **About (`about.md`)**: Detailed about page with all information
- **Blog (`blog.md`)**: Blog listing page for CTF writeups and articles
- **Layout (`_layouts/default.html`)**: Main template with navigation and footer
- **Styles (`assets/css/style.scss`)**: All CSS styling

## Local Development

To run this site locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## Deployment

This site is designed for GitHub Pages. Simply push to the `main` branch and GitHub will automatically build and deploy the site.

## Customization

### Update Profile Information
Edit `_config.yml` to update:
- Site title
- Description
- GitHub username
- LinkedIn URL

### Add CTF Writeups
Create new markdown files in a `_posts` or `writeups` directory and link to them from the blog page.

### Modify Colors
Edit the color values in `assets/css/style.scss`:
- `#1a1a1a` - Background color
- `#e0e0e0` - Text color
- `#58a6ff` - Link color
- `#30363d` - Border color

## Credits

Design inspired by clean, minimal developer portfolios with a focus on content and readability.
