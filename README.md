# Exploding Kittens collection

A static card catalogue and illustrated guide, with Full and Compact decks.

- Full: 179 copies, including two Armageddon side cards.
- Compact: 90 copies, including the same two side cards.
- Both guides use five players. The deck switch updates quantities, artwork and rules together.
- All card images, fonts, scripts and data are local. No account, database, environment variables or build dependencies are required.

Open `index.html` locally, or serve this directory with any static web server.

## GitHub and Vercel

Use the contents of **this directory** as the repository root. Do not upload the parent EK directory, its archives, originals or working folders. The included ignore files keep local audit reports and notes out of a normal Git commit.

Import that GitHub repository into Vercel. The included `vercel.json` selects a static project with no build command and the repository root as the output directory. Navigation uses URL fragments, so no catch-all rewrite is needed. GitHub Pages can also serve these relative asset paths.

The package is about 522 MB because it retains the full-resolution cleaned PNG images. Its largest individual file is under 4 MB. Use a Git client to push the repository and import it through Vercel's Git integration. Vercel's Hobby CLI source-upload limit is 100 MB; this uncompressed package exceeds that particular upload path. See [Vercel limits](https://vercel.com/docs/limits) and [GitHub file guidance](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github).

## Content and validation scope

The Compact deck is a physical subset of the Full selection. Five Cat families retain three matching copies each; both Barking Kittens and the selected official singleton mechanics remain present. Custom interactions are labelled as house rules. Consistency and setup arithmetic have been checked; strategic balance has not been playtested.

The broader Cards catalogue retains its historical source descriptions. The detailed selected-face review covers the 81 Full-deck types, including all 61 Compact types; it is not a new independent verification of every historical fan card.

Card artwork, the reference-site logo and pack emblems remain third-party assets. Collecting them and running the site locally does not itself establish redistribution permission. No blanket open-source artwork license is asserted here. Font licenses are included under `Assets/Licenses/`.
