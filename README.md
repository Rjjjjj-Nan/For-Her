# A little letter for you

A romantic, static love-letter website with an anniversary date unlock. It
does not use a database, backend, cookies, or analytics.

## Personalize it

Open `script.js` and edit the `surprise` object near the top:

- `anniversary`: the unlock date in `YYYY-MM-DD` format.
- `dateLabel`: the date shown on the letter.
- `greeting`, `paragraphs`, `signOff`, and `signature`: your letter.
- `photoLabels`: captions for the eight clickable memory cards.

The landing page decorations use `couple-heart.png`, which is already included
in the project folder. Keep that image beside `index.html` when deploying.

The album includes eight sample photos inside the `photos/` folder. The
`photoLabels` and `photoPaths` arrays in `script.js` control the caption and
image used by each card.

When you have different pictures, replace the filenames in `photoPaths` with
your own image paths and keep the files inside the project folder.

## Deploy

This is a static site. Upload `index.html`, `styles.css`, and `script.js` to
any static hosting provider. No installation or build command is needed.

- **GitHub Pages:** put the files in a repository, enable Pages, and choose the
  branch containing these files.
- **Netlify / Vercel:** import the folder or repository, leave the build command
  blank, and use the project root as the publish directory.
- **Any web host:** upload the three files to the public web directory.
