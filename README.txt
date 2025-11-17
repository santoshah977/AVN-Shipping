How to use this static AVN Shipping site on GitHub Pages

1) Files included:
   - index.html
   - style.css
   - script.js
   - README.txt

2) Save these files into the root of your GitHub repo (e.g. AVN-Shipping).

3) Commit & push:
   git add index.html style.css script.js README.txt
   git commit -m "Add static AVN Shipping homepage"
   git push origin main

4) Enable GitHub Pages:
   - Go to your repo on GitHub -> Settings -> Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Save, then wait a minute for the site to be published.

5) Your site will be available at:
   https://santoshah977.github.io/AVN-Shipping/

6) To replace placeholders:
   - Replace logo & images by uploading assets to repo (create /assets/) and update src paths.
   - Hook the contact form to an actual endpoint (Formspree, Netlify forms, or your server).
   - Replace any placeholder text with real content.

7) Support:
   - If you want me to modify text, swap images, or tune styles for mobile, tell me which parts to update.
