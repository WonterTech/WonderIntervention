# Fiche d'intervention – Wonder Tech

Digital version of the Wonder Tech intervention form. Fill it in on a phone, sign with a finger, and save it as a PDF with the same layout as the paper form.

## Use

1. Open the page (see "Publish" below).
2. Fill in the fields, tick the boxes, sign in the two boxes.
3. Tap **Enregistrer en PDF** and choose "Save as PDF" in the print dialog.
4. Tap **Nouvelle fiche** to start the next one.

Add the page to your home screen to open it like an app; it also works offline after the first visit.

## Publish (GitHub Pages)

Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. The form is then available at `https://<your-username>.github.io/<repo-name>/`.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The form (HTML, CSS and JavaScript in one file) |
| `logo.png` | Logo without shadow, used in the form header |
| `logo-ombre.png` | Logo with shadow |
| `icon-192.png`, `icon-512.png` | App icons |
| `manifest.webmanifest`, `sw.js` | Home-screen install and offline use |

Entries are kept only in the browser of the device being used; nothing is sent to a server.
