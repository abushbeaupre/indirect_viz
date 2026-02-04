# Visualizing Indirect Effects

This is a Quarto website for visualizing indirect effects in causal inference and network analyses. The website showcases a new visualization method for interpreting direct and indirect effects across various ecological case studies.

## About

This website presents a visualization method for indirect effects developed by Allen Bush-Beaupré, Simon Coroller-Chouraki, and Marc Bélisle from the Université de Sherbrooke. The method leverages commonly used software such as [`marginaleffects`](https://marginaleffects.com/) and [`ggplot2`](https://ggplot2-book.org/) to make indirect effects easier to interpret and can be seamlessly integrated into most analysis workflows.

## Website Content

The website includes:

- **Home**: Introduction to the visualization method with abstract and overview
- **Simulations**: Demonstrations of the method using simulated data for simple use cases
- **Case Study - Blowfly larvae**: Real-world application using Tree Swallows (*Tachycineta bicolor*) and their ectoparasites (*Protocalliphora* spp.)
- **Case Study - Bighorn Sheep**: Complex multi-mediator example examining carry-over effects of snow cover on bighorn sheep (*Ovis canadensis*) body mass

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

The website is published at: https://abushbeaupre.github.io/indirect_viz/

## Citation

If you use this visualization method, please cite the preprint available on bioRxiv (link to be added).

Data for the Tree Swallow case study is available at: https://doi.org/10.5281/zenodo.17980480
