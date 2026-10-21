# kimsum.studio

The static site for Kim Sum Studio (金心工作室). Plain HTML, CSS and a few lines of JavaScript. No build step needed.

## Put it live on GitHub Pages

1. **Back up the old site.** In your existing kimsum.studio repo, create a branch called `old-portfolio` (Branch dropdown, type the name, Create branch). Your current site is now saved there.
2. **Switch back to the main branch** (usually `main`).
3. **Delete the old files.** Delete the old site's files from `main`, but keep the `CNAME` file if there is one.
4. **Upload these files.** Click **Add file → Upload files**, drag in *everything inside this folder* (not the folder itself), then click **Commit changes**.
   - The `.nojekyll` file is hidden on a Mac. In Finder press **Cmd + Shift + .** to show it, and include it in the upload.
5. **Check the Pages settings.** Go to **Settings → Pages**. Source should be "Deploy from a branch", branch `main`, folder `/ (root)`. The custom domain should still read `kimsum.studio`, with "Enforce HTTPS" ticked.
6. **Wait and check.** Wait a minute or two, then visit https://kimsum.studio. Hard-refresh with **Cmd + Shift + R** if you still see the old site.

Your domain's DNS settings don't need to change, because the site stays in the same repo.

## What's where

| Page | File |
|---|---|
| Home | `index.html` |
| Projects | `projects/index.html` |
| About | `about/index.html` |
| 01 Fuel Card Launch | `projects/fuel-card-launch/index.html` (**not indexed by search engines**) |
| 02 Exhibitor Recommendations | `projects/exhibitor-recommendations/index.html` |
| 03 mirrOR | `projects/mirror-surgical-interface/index.html` |
| 04 FIBO | `projects/fibo-ar-treasure-hunt/index.html` |

- Images, video and fonts are in `assets/`.
- `robots.txt` and `sitemap.xml` keep the Fuel Card page out of search results.
- The page itself also carries a `noindex` tag.

## Small text edits

Open the page's `index.html` on GitHub, click the pencil icon, change the words, and commit. The site updates within a minute or two.
