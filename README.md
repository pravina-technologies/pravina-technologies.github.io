# Pravina Technologies Website

This is the official website for Pravina Technologies, showcasing our AI products and services.

## Deployment

This website is deployed on GitHub Pages. The deployment is automated using GitHub Actions workflow.

### How to Deploy

1. Push changes to the `main` branch
2. GitHub Actions will automatically build and deploy the site to GitHub Pages
3. View the deployed site at https://pravinatechnologies.github.io

### Manual Deployment

If you need to trigger a deployment manually:

1. Go to the Actions tab in the GitHub repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow" and select the main branch
4. Click the green "Run workflow" button

## Local Development

To run the website locally:

1. Clone the repository
2. Open `index.html` in your browser

## Project Structure

- `index.html` - Main landing page
- `blog.html` - Blog listing page
- `blog-post.html` - Sample blog post template
- `styles.css` - Global styles
- `script.js` - JavaScript functionality
- `.github/workflows/deploy.yml` - GitHub Actions workflow for deployment