# The Birthday Massacre Italia

Sito web italiano **non ufficiale** dedicato ai [The Birthday Massacre](https://www.thebirthdaymassacre.com), band di Toronto formatasi a London (Ontario) nel 1999.

Il sito non è affiliato, approvato o gestito dalla band, dalla sua etichetta (Metropolis Records) o dai suoi management. Tutti i marchi, i nomi, le immagini e le copertine appartengono ai rispettivi titolari.

## Contenuti

Sezioni della pagina (ancore tra parentesi):

- Home (`#home`): presentazione della band
- Novità (`#novita`): ultime uscite
- Musica (`#musica`): album e tracklist
- Ascolta (`#ascolta`): link alle piattaforme di streaming e acquisto (Spotify, Apple Music, Qobuz, Bandcamp, Metropolis, Patreon)
- Foto (`#foto`) e Video (`#video`)
- Testi (`#testi`)
- Tour (`#tour`): date dei concerti
- Band (`#band`): membri e ruoli
- Store (`#store`): merchandising e collegamenti ai negozi

## Struttura del repository

| File | Descrizione |
| --- | --- |
| `index.html` | Pagina principale del sito (versione 20.0) |
| `support.js` | Runtime necessario per il rendering della pagina |
| `thumbnail.webp` | Anteprima del sito |
| `.nojekyll` | Disabilita Jekyll su GitHub Pages |
| `.github/workflows/pages.yml` | Workflow di deploy automatico su GitHub Pages |

## Tecnologie

- HTML5 e CSS inline
- React 18.3.1 e Babel standalone, caricati da [unpkg](https://unpkg.com)
- Font da [Google Fonts](https://fonts.google.com) (Cormorant Garamond, Barlow, Barlow Condensed)

Non è richiesto alcun processo di build: il sito è statico.

## Pubblicazione su GitHub Pages

1. Carica il contenuto del repository sul branch `main`.
2. Vai su **Settings → Pages**.
3. In **Build and deployment → Source**, seleziona **GitHub Actions**.
4. Ad ogni push su `main` il workflow pubblica automaticamente il sito. Puoi seguirne l'esecuzione nella scheda **Actions**.

Il sito sarà disponibile all'indirizzo:

```
https://<tuo-utente>.github.io/<nome-repository>/
```

Il percorso relativo di `support.js` funziona sia alla radice di un dominio sia in un sotto-percorso, quindi non serve modificare nulla per il deploy in un repository di progetto.

## Dipendenze esterne

Alcune risorse sono caricate da servizi di terze parti (immagini da Bandcamp, Discogs e Zoogle Tools, runtime da unpkg, font da Google Fonts). Se uno di questi servizi cambia URL o rimuove un'immagine, la relativa sezione potrebbe apparire vuota: in quel caso va aggiornato il contenuto corrispondente in `index.html`.

## Sviluppo

Il file `index.html` contiene il markup e i dati (array JavaScript in fondo alla pagina, nel blocco `<script type="text/x-dc">`). Per aggiornare date di tour, tracce, merchandising o link, modifica direttamente quegli array.

## Licenza e crediti

Il codice di questo repository (struttura e configurazione) è rilasciato senza vincoli particolari. I contenuti relativi alla band (nomi, testi, immagini, copertine, loghi) restano di proprietà dei rispettivi titolari e vengono qui riportati a scopo informativo.
