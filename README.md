# Indirect Effects Website

This is a Quarto website for the Indirect Effects project.

## Building the website

To render the website locally:
```bash
quarto render
```

To preview the website:
```bash
quarto preview
```

## Publishing to GitHub Pages

1. Make sure the repository is initialized and connected to GitHub
2. Render the website: `quarto render`
3. Commit and push all files including the `docs/` folder
4. On GitHub, go to Settings > Pages
5. Set Source to "Deploy from a branch"
6. Select the `main` branch and `/docs` folder
7. Click Save

The website will be published at: `https://<username>.github.io/<repository-name>/`
