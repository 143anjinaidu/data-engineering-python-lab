# Data Engineering Python Lab

Free static website with 30 exercises and 5 practical projects.

## Publish online with GitHub Pages (no laptop server needed after deployment)

1. Sign in at https://github.com/ and create a new **public** repository, e.g. `data-engineering-python-lab`.
2. Upload all files and folders in this project to the repository root: `index.html`, `content.json`, `samples/`, `projects/`, and `LICENSE`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment to finish. Your site URL will look like `https://YOUR-USERNAME.github.io/data-engineering-python-lab/`.

## Limitations
- This is a static site; no backend, learner accounts, or cloud-saved progress.
- The browser Python runtime loads Pyodide from a CDN and requires internet.
- No live PostgreSQL server or unrestricted API networking is provided by the browser editor.
- Full Parquet/PyArrow and PostgreSQL work should be run in a local or separately hosted Python environment.
- Do not put secrets or database credentials into the browser editor.
