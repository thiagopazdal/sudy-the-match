# NEXORA Studio

A brand-new bilingual (English/Spanish) website concept with a premium grayscale visual identity. It is independent of your existing `nexora` website.

## Files
- `index.html` — structure and content
- `styles.css` — responsive visual system
- `script.js` — language toggle, mobile navigation, contact form
- `favicon.svg` — browser icon
- `og-cover.svg` — social sharing cover

## Publish safely without changing the current site
1. Download and extract `nexora-studio.zip`.
2. In GitHub, create a **new public repository** named `nexora-studio`.
3. Upload the five files above directly to the repository root (do not upload the ZIP itself).
4. Open **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
6. After GitHub Pages finishes, visit `https://YOUR-USERNAME.github.io/nexora-studio/` and replace `YOUR-USERNAME` in the social metadata in `index.html` with your GitHub username.

## Important: configure contact
Open `script.js` and replace:
```js
const config = { contactEmail: "" };
```
with your real business contact email, for example:
```js
const config = { contactEmail: "hello@example.com" };
```
The form validates the fields and opens the visitor's configured email application. It does **not** send or store information by itself. Test it on a phone and a computer.

## Before sharing publicly
- Check both languages using the EN / ES control.
- Test the mobile navigation and every section link.
- Submit the contact form after adding your real email.
- Confirm the concept projects are clearly presented as concepts; do not imply they are commissioned client work.
- Add real project links only after the demo pages are published and tested.

## Customize
Edit the text in `index.html` and the `translations` object in `script.js` together so English and Spanish stay consistent. Colors are set near the top of `styles.css` using CSS variables.


## Imágenes incluidas

Las fotos que compartiste están dentro de la carpeta `images/`. La portada y tres tarjetas del portfolio ya usan algunas de ellas. Subí la carpeta `images` completa al repositorio, junto con `index.html`, `styles.css` y `script.js`; no cambies los nombres de archivo porque el HTML los referencia directamente.
