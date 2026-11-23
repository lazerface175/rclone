# rclone on NAS

Static site (GitHub Pages) with a quick-reference guide for running
[rclone](https://rclone.org/) on a headless NAS.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `rclone`) and push this folder:

   ```sh
   git remote add origin https://github.com/<you>/rclone.git
   git push -u origin main
   ```

2. In the repo: **Settings → Pages → Source → Deploy from a branch**,
   pick `main` / `(root)` (or `/docs` if you move the site there), save.

3. The site is live at `https://<you>.github.io/rclone/` after a minute or two.

## Local preview

Any static file server works:

```sh
npx serve .
# or
python -m http.server 8000
```
