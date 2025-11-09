THE PAVILION GARDENS — Ready for hosting

What I changed
- Externalized styles into `styles.css` and enhanced them (variables, responsive rules, focus states).
- Added meta description and Open Graph tags to `index.html`.
- Added favicon link (place a `favicon.ico` next to `index.html` if you have one).
- Replaced placeholder text with emoji icons and fixed contact links (tel: and mailto:).
- Improved accessibility (aria-hidden for decorative emoji, focus outlines for keyboard users).

How to preview locally
1. Open the folder `TPG Authentic` in a terminal.
2. Run a local static server (python is easiest):

```powershell
# from the folder that contains index.html
python -m http.server 8000; start http://localhost:8000/
```

3. Visit `http://localhost:8000/` in your browser to preview.

Hosting on GitHub Pages
1. Create a new Git repository in this folder and push to GitHub.
2. In the repository settings, enable GitHub Pages and select the `main` branch (or `gh-pages`) as the source. The site will be published at `https://<username>.github.io/<repo>/`.

Notes & next steps (optional)
- Replace the temporary gallery images with real images and add optimized copies (webp or compressed JPG) in an `assets/` folder.
- Add a real `favicon.ico` and `site logo` images.
- Add structured data (JSON-LD) for local businesses/events if needed for SEO.
- If you want, I can also produce a minified CSS file and a deploy script for GitHub Actions.

If you'd like me to continue, tell me which of the optional steps you want next.