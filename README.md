# GitHub Pages site

This ZIP is a dependency-free static website. It requires no package manager, runtime, or build command.

## Publish

1. Extract the ZIP at the root of a new or existing GitHub repository.
2. Commit and push the files to the repository's default branch.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and **/(root)**, then save.
6. Use **Visit site** after GitHub reports a successful Pages deployment.

Edit the HTML, CSS, and assets directly in GitHub or locally, then push again. Preview locally with `python3 -m http.server 8080` and open `http://localhost:8080/`.

The package uses relative page, asset, and navigation URLs so it works as either an account site or a project site. The included `.nojekyll` file tells GitHub Pages to serve the static files without Jekyll processing.
