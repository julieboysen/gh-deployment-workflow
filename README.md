
# GitHub Pages Deployment

This project demonstrates how to use **GitHub Actions** to automatically deploy a static website to **GitHub Pages** whenever changes are made to the `index.html` file in the `main` branch.

## Workflow Details

The deployment process is handled by a GitHub Actions workflow (`deploy.yml`) which performs the following steps:
1. **Trigger on push**: The workflow is triggered on any push to the `main` branch, but only when `index.html` is changed.
2. **Checkout code**: The workflow checks out the repository code.
3. **Deploy to GitHub Pages**: The website is automatically deployed to the `gh-pages` branch, making it accessible at `https://julieboysen.github.io/gh-deployment-workflow/`.

## Project Link
For more details about this project, visit the [GitHub Pages Deployment Project](https://roadmap.sh/projects/github-actions-deployment-workflow).
    
