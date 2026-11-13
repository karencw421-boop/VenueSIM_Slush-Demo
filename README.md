# Vinyl Records

An interactive record player for iPad (12.9″, landscape or portrait) and desktop browsers.
Pick a record, take it out of its sleeve, and turn the dial to blend the unprocessed
recording into the version processed for the venue.

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The whole site in one file. Images and audio are built into it, so this is the only file the site needs. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. |
| `assets/` | The original images and audio, kept for reference and future edits. The site doesn't load them. |

## Put it online with GitHub Pages

1. On github.com, create a new repository (for example `vinyl-records`). It can be public or private, but free accounts need it public for Pages.
2. Click **Add file → Upload files**, drag in everything from this folder (including `.nojekyll` and `assets`), and click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the page shows your link, like `https://your-name.github.io/vinyl-records/`. Open it on the iPad.

Tip: on the iPad, open the link in Safari, tap **Share → Add to Home Screen** to open it full screen like an app.

## Using it

- **Switch records:** swipe left or right, tap the arrows, or use the ← → keys.
- **Listen:** tap the record to take it out of its sleeve. Tap it again to put it back.
- **Process the sound:** turn the dial. Every record starts at 10% processed.

## Good to know

- The page needs an internet connection: the 3D library (three.js) and the typeface load from the web.
- Sound only starts after a tap, as browsers require. On iPad, turn off silent mode if there's no sound.
- The file is about 9 MB, so the first load can take a few seconds.
- The typeface is a stand-in (Hanken Grotesk) until an Apfel Grotezk font file is added.
- Records 3 and 4 are placeholders that repeat records 1 and 2.
