# GitHub Pages HTML Test

This project is a simple static website used to test hosting an HTML page with GitHub Pages.

The goal is to verify that a browser can load a basic HTML page from a GitHub repository and that the site is publicly accessible through GitHub's built-in hosting service.

## Project purpose

This repository can be used as a minimal example for:

- hosting static HTML files on GitHub Pages
- testing page rendering in a browser
- validating deployment settings and URL output
- learning how GitHub Pages works with a simple project

## Typical structure

A basic GitHub Pages project usually contains files like:

- `index.html` — the main page
- `style.css` — optional styling
- `script.js` — optional JavaScript
- other static assets such as images or fonts

## Local preview

To preview the site locally, open the HTML file directly in a browser or run a small local web server from the project folder.

Example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Open the repository in GitHub.
3. Go to Settings.
4. Open the Pages section.
5. Under Source, choose the branch you want to publish, usually `main`.
6. Select the root folder or `/` for the site.
7. Save the settings.
8. GitHub will provide a live URL such as:

```text
https://<username>.github.io/<repository-name>/
```

## Example page

A minimal page can look like this:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GitHub Pages Test</title>
  </head>
  <body>
    <h1>Hello from GitHub Pages</h1>
    <p>This page is being hosted from a GitHub repository.</p>
  </body>
</html>
```

## Notes

- GitHub Pages serves static content only.
- It is best suited for HTML, CSS, and JavaScript files.
- Changes pushed to the configured branch will usually appear shortly after deployment.
- This repository is intended for testing and experimentation, not production-critical hosting.

## License

This project is provided for testing and learning purposes.
