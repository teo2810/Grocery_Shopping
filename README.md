# La mia spesa – PWA offline

App lista spesa installabile, 100% free, zero servizi terzi.  
Dati solo in localStorage del browser.

## File
- `index.html` – app completa
- `manifest.json` – PWA config
- `sw.js` – service worker offline
- `icon-192.png` / `icon-512.png` – icone

## Deploy gratis su GitHub Pages

1. Crea repo su github.com (es. `spesa-pwa`)
2. Carica questi file nella root del repo
3. Settings → Pages → Source: Deploy from branch → main → / (root)
4. Aspetta 1-2 min → vai su `https://TUO-USER.github.io/spesa-pwa/`

## Uso locale
Apri `index.html` in browser (o `npx serve .` se hai Node).

## Note memoria
- localStorage: max ~5-10 MB, persiste finché non cancelli dati browser.
- Per più stabilità: backup manuale via “Condividi lista”.
- Offline completo dopo prima visita (service worker).

Nessun account, nessun backend, nessun costo.
