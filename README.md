# Portfolio Website

This is a single-page personal portfolio designed for GitHub Pages. It is intentionally lightweight and easy to customize for a polished professional profile.

## Files

- `index.html` — main page content
- `styles.css` — visual design and layout
- `script.js` — small script for dynamic date rendering
- `assets/profile-placeholder.svg` — placeholder image to replace with your professional photo

## Customize the content

Open `index.html` and replace the placeholder content:

- `[Your Name]`
- `[job title / discipline]`
- `[brief industry focus]`
- company names and roles in the Experience section
- project descriptions
- email and links in the footer
- photo source if you want to swap in a real image

## Add your professional photo

1. Put your image in the `assets` folder.
2. Rename it to something like `profile.jpg`.
3. Update the image path in `index.html` from `assets/profile-placeholder.svg` to your new file.

Example:

```html
<img src="assets/profile.jpg" alt="Professional headshot of [Your Name]" />
```

## Run locally

From the project folder, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Publish on GitHub Pages

1. Push this repo to GitHub.
2. In GitHub, open the repository.
3. Go to Settings -> Pages.
4. Set the source to "Deploy from a branch".
5. Choose the `main` branch and the root folder (`/`).
6. Save the settings.

Your site will be available at:

```text
https://<your-username>.github.io/<repository-name>/
```

## Notes

This project intentionally uses a simple static site so it is easy to host and maintain. If you want, you can later expand it with a contact form, downloadable resume, or more advanced animations.
