# david-bridges-summer-school — GitHub Pages site

This repository now contains a simple static website in the `docs/` folder. To publish it with GitHub Pages:

1. Commit the new files (if they are not already in the repo):
   ```bash
   git add docs/*
   git commit -m "Add GitHub Pages site in docs/"
   git push
   ```

2. Enable GitHub Pages:
   - Go to the repository on GitHub -> Settings -> Pages.
   - Under "Source", select the `main` branch and the `/docs` folder (or whichever branch you used).
   - Save. The site will publish at `https://<your-username>.github.io/<repo-name>/` (for this repo: `https://jdavid675.github.io/david-bridges-summer-school/`).

3. (Optional) Customize:
   - Replace the sample schedule and resources in `docs/index.html`.
   - Add images into `docs/assets/` and reference them from the page.
   - If you prefer Jekyll or a theme, switch to using `_config.yml` and Jekyll-friendly files and remove `.nojekyll`.

If you'd like, I can:
- open a branch with these files and create a pull request,
- or directly push them to the `main` branch for you (I will need permission / instruction to do so).

- TEAM-NAME: GITTY_UP(1)
