# tristan-shah.github.io

A single-page personal site. No build step, no Jekyll: open `index.html` in a browser to preview it offline.

## Editing content

| What | Where |
|------|-------|
| News / updates | `content/news.js` — copy a block, paste it at the top of the list |
| Publications | `content/publications.js` — same idea |
| Research overview, contact | `index.html` — plain HTML, each section is marked with a `<!-- ==== NAME ==== -->` comment |
| Resume PDF | replace `papers/Resume.pdf` |
| Animations | `media/*.mp4` (compressed from the originals with ffmpeg) |

## Deploying to GitHub Pages

The site is static, so GitHub Pages serves it as-is from the root of `master`. The empty `.nojekyll` file tells Pages to skip the Jekyll build. Push to `master` and the site updates at https://tristan-shah.github.io within a minute or two.
