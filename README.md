# Allenatore: corsa e nutrizione (PWA)

Piano di corsa, coach IA, nutrizione e import dei CSV Garmin. Funziona su iPhone come un'app, con icona sulla Home e uso offline.

## Pubblicarla su GitHub Pages

1. Crea un account su github.com (se non lo hai) e un nuovo repository **pubblico**, per esempio `allenatore`.
2. Nel repository: **Add file > Upload files** e carica **tutti i file di questa cartella** (non lo zip): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png` e `.nojekyll`. Poi premi **Commit changes**.
3. Vai in **Settings > Pages**. Sotto "Build and deployment" scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, e salva.
4. Dopo 1–2 minuti l'app è online su `https://TUO-UTENTE.github.io/allenatore/`.

## Installarla sull'iPhone

1. Apri l'indirizzo in **Safari**.
2. Tocca **Condividi** (il quadrato con la freccia) e scegli **Aggiungi alla schermata Home**.
3. Apri l'app dall'icona sulla Home.

## Funzioni IA (coach, calorie, piano alimentare)

Fuori da claude.ai servono le tue credenziali:

1. Crea una chiave API su console.anthropic.com e imposta un limite di spesa.
2. Nell'app, **Impostazioni > Chiave API**, incolla la chiave.

La chiave resta solo nel browser del tuo telefono. Senza chiave tutto il resto funziona lo stesso: piano, calendario, import CSV, registro pasti, gel, ritmi.

## Cose da sapere

- I dati (piano, pasti, feedback, corse importate) sono salvati solo sul telefono. Quelli dell'app installata sono separati da quelli di Safari.
- Per aggiornare l'app basta sostituire `index.html` nel repository. Al lancio successivo con connessione si aggiorna da sola.
- Se vuoi tenere il repository privato servono GitHub Pro o un servizio come Netlify o Cloudflare Pages.
