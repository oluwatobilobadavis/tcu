# The Church Unwrinkled

Responsive React + Vite multi-page church website.

## Run locally

1. Install Node.js (LTS).
2. Open this folder in VS Code.
3. Open the terminal in the project folder.
4. Run:

```bash
npm install
npm run dev
```

5. Open the local URL printed by Vite, usually `http://localhost:5173`.

## Production build

```bash
npm run build
npm run preview
```

The production-ready website is generated in `dist/`.

## Important content to replace before launch

- Replace the temporary church photographs in `src/App.jsx` with approved church photographs.
- Replace the CU text mark with the official church logo if available.
- Add the pastor's real name, photograph and biography.
- Confirm and add official service days and times.
- Add official phone, email and social media links.
- Confirm the church's exact meeting point. The map currently uses Cedar Care Hospital, Ogombo Road, Abraham Adesanya, Ajah as the supplied landmark, not as a claim that the church is inside the hospital.

## Forms

Both forms submit by POST to:

`https://formspree.io/f/mvkkydrr`

Make sure this endpoint is active and verified in the church's Formspree account. Test both forms after deployment.

## Fonts and imagery

Anton and Manrope are loaded from Google Fonts. Temporary photographs are loaded from Unsplash and require an internet connection.
