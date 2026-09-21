# Linlin Feng's website

This is the source for [yanlinfeng123.github.io](https://yanlinfeng123.github.io), built with [Quarto](https://quarto.org/). Edit `index.qmd` and `Portfolio.qmd` to update the pages. Edit `styles.css` to change the appearance.

## Preview and publish

1. Open this folder in RStudio or a terminal and run `quarto preview` to check your changes.
2. Run `quarto render`. This updates the `docs/` folder, which contains the files GitHub Pages serves.
3. Commit and push the source files **and** the updated `docs/` folder to the `main` branch.
4. In the GitHub repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/docs** and save.

The repository name must be `YanlinFeng123.github.io` for the personal site address above. Keep `docs/.nojekyll` in place so GitHub serves Quarto's generated files correctly.

To add a project, replace the work-in-progress text in `Portfolio.qmd` with a heading, a short description, and a link. Render again before pushing.
