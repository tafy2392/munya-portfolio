# Munya Portfolio

This repository contains a minimalist Hugo portfolio starter for a personal career site.

## Features

- Simple, strong portfolio layout
- Home, About, Projects, and Contact pages
- Responsive styling for desktop and mobile
- Ready to customize with your own content and links

## Local setup

1. Install Hugo:
   ```bash
   brew install hugo
   ```
   Or follow the official instructions for your OS: https://gohugo.io/getting-started/installing/

2. Run the site locally:
   ```bash
   hugo server -D
   ```

3. Open the local preview in your browser, typically at:
   ```bash
   http://localhost:1313/
   ```

## Customize your portfolio

- Update your profile details in `hugo.toml`
- Change content in `content/_index.md`, `content/about.md`, and `content/contact.md`
- Add or edit project pages in `content/projects/`
- Adjust theme colors and layout in `static/css/styles.css`

## Deploy to GitHub Pages

Use either GitHub Pages with a Hugo build action or generate the static output locally:

```bash
hugo --minify
```

Then publish the generated `public/` directory through GitHub Pages or a deployment workflow.

## Suggested next steps

- Replace placeholder email, phone, LinkedIn, and GitHub information
- Add your real project case studies and resume
- Upload a profile image to a `static/` asset and link it in your content
