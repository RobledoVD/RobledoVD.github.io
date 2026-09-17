# Vanessa Robledo Delgado — Academic Website

Static academic website prepared for GitHub Pages at `https://robledovd.github.io`.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **public** repository named exactly `RobledoVD.github.io`.
2. Upload all files and folders from this project to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. GitHub will publish the site at `https://robledovd.github.io` after a few minutes.

## Replace the photograph placeholder

1. Add a portrait image to `assets/`, preferably as `portrait.jpg`.
2. In `index.html`, replace the complete `portrait-placeholder` block with:

```html
<img class="portrait-image" src="assets/portrait.jpg" alt="Portrait of Vanessa Robledo Delgado">
```

3. Add this rule to `styles.css`:

```css
.portrait-image {
  width: min(310px, 33vw);
  aspect-ratio: 4 / 5;
  object-fit: cover;
  object-position: center;
  border-radius: 170px 170px 22px 22px;
}
```

## Update the site

- Main content: `index.html`
- Colors and layout: `styles.css`
- Navigation and scroll effects: `script.js`
- Downloadable CV: `assets/vanessa-robledo-cv.pdf`

## Content to verify before publication

- Confirm the year and location of the AMS presentation currently listed as 2025.
- Expand the Caribbean workshop locations if desired.
- Add any publications not included in the three source CVs.
- Add a LinkedIn URL if it should appear in the profile links.
- Replace the photograph placeholder.
