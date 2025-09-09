# Illustrated History of Google — Single-Page Site

This folder contains a fully functional, responsive, interactive single-page website that illustrates key milestones in Google's history.

## What's inside
- `index.html` — One file, all features. Uses CDN links for Tailwind CSS and Alpine.js.
- External images are hotlinked from Wikimedia/Google sources so there are **no placeholders**.

## Features
- Interactive timeline: slider + search + category filter
- Light/dark mode
- Tap-to-view sources (citations)
- Expandable gallery
- 4-question instant-feedback quiz
- "I'm Feeling Lucky" randomizer

## How to deploy (Netlify drag & drop)
1. Go to https://app.netlify.com/drop
2. Drag **index.html** into the dropzone. Netlify will deploy and give you a live URL.

### Alternative: GitHub + Netlify
1. Create a GitHub repo and commit `index.html`.
2. In Netlify, "New site from Git", connect the repo, deploy main branch.

### Alternative: Google Drive share
Upload the file to Drive and share the folder link (ensure permissions allow viewing).

## Sources used

- History overview: Wikipedia — https://en.wikipedia.org/wiki/History_of_Google
- Maps launch & retrospective: The Keyword — https://blog.google/products/maps/look-back-15-years-mapping-world/
- Maps page: Wikipedia — https://en.wikipedia.org/wiki/Google_Maps
- YouTube acquisition (Oct 9, 2006): SEC press — https://www.sec.gov/Archives/edgar/data/1288776/000119312506206884/dex991.htm
- YouTube acquisition closed (Nov 13, 2006): SEC press — https://www.sec.gov/Archives/edgar/data/1288776/000119312506238320/dex991.htm
- Chrome launch: Official Google Blog — https://googleblog.blogspot.com/2008/09/fresh-take-on-browser.html
- Alphabet announcement: The Keyword — https://blog.google/alphabet/google-alphabet/
- Alphabet operating structure release: Alphabet IR — https://abc.xyz/investor/news/2015/0810
- Bard becomes Gemini (Feb 2024): The Keyword — https://blog.google/products/gemini/bard-gemini-advanced-app/
- Gemini era update (Feb 2024): The Keyword — https://blog.google/technology/ai/google-gemini-update-sundar-pichai-2024/
- Dutch auction IPO analysis: Berkeley Tech. L.J. PDF — https://www.btlj.org/data/articles2015/vol20/20_1_AR/20-berkeley-tech-l-j-0405-0442.pdf
- IPO context: Wired — https://www.wired.com/2004/11/google-blazes-lonely-ipo-trail

## Notes
- This is an educational project; logos and screenshots are used under fair use. You can swap images by editing the `gallery` array and the `events[*].image/thumb` fields in the script near the end of the file.
- Last built: 2025-09-09 (UTC)
