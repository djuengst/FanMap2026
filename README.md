# Club Natties 2026 Pool Play FanMap++

Interactive field map and team tracker for the **2026 USA Ultimate Club National Championships** at Surf Cup Sports Park (San Diego, CA).

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `club-natties-2026-fanmap`).
2. Upload the contents of this zip file to the root of your repository:
   - `index.html` (Self-contained version with all 48 official logos embedded + `/logos/` folder support)
   - `index-external-logos.html` (Optional lightweight version that loads images exclusively from the `./logos/` folder)
   - `logos/` (Folder containing all 48 original team logo files)
3. In your GitHub repository, go to **Settings -> Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, select your `main` branch and `/ (root)` folder, and click **Save**.
5. Your interactive FanMap++ will be live at `https://<your-username>.github.io/<repo-name>/` within 60 seconds!
