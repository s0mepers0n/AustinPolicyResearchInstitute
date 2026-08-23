# Austin Policy Research Institute — website

Plain HTML/CSS/JS site, ready for GitHub Pages. No build step, no frameworks.

## Files

- `index.html` — homepage
- `about-us.html`, `leadership.html`, `projects.html`, `essay-competition.html`, `high-school-fellowship.html` — the other pages, linked from the nav bar on every page
- `styles.css` — all styling
- `script.js` — mobile nav menu toggle
- `images/` — put your photos here (see `images/README.md` for exact filenames)

## How to put this on GitHub Pages

1. Create a new repository on GitHub (e.g. `austinpolicyresearchinstitute.github.io`, or any name you like).
2. Upload all of these files to the repository, keeping the folder structure (the `images` folder should stay a folder, not be flattened).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch".
5. Set **Branch** to `main` (or whichever branch you uploaded to) and folder to `/ (root)`, then **Save**.
6. Wait a minute or two, then GitHub will give you a URL like `https://yourusername.github.io/your-repo-name/` — that's your live site.

## Where to add real content

- **Photos**: every dashed box that says "PUT PHOTO HERE" is a placeholder. Follow `images/README.md` to know exactly which filename fills which spot, then replace the `<div class="image-placeholder">...</div>` with `<img src="images/filename.jpg" alt="describe the photo">`.
- **Text**: anything that says "Text goes here or something, Idk" is a placeholder for you to write real copy. Just edit it directly in the `.html` files — search for that phrase in your code editor to find every spot.
- **Nav links / page structure**: already wired up and working — all five pages link to each other correctly, so you shouldn't need to touch those unless you rename a page.
- **Email / social links**: in the footer of every page, swap `mailto:info@example.com` and the Instagram link for your real contact info.
