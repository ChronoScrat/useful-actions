# R Actions

Here is a list of GitHub actions involving R:

- [`R-CMD-check`](R-CMD-check.yaml): Runs a complete version of the R-CMD-CHECK in the latest versions of Windows, Ubuntu and MacOS. Necessary for creating packages, but time-consuming.

- [`Render README`](render-readme.yaml): Renders a README.Rmd file into a GitHub-friendly README.md, and commits it to main without retriggering all the other actions.

- [`pkgdown`](pkgdown.yaml): Runs pkgdown to render a library's site and push it to `gh-pages`.