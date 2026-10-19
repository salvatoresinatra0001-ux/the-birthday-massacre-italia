# The Birthday Massacre Italia — Netlify Edition

**Autore, ideazione e direzione editoriale:** Salvatore Sinatra.

## Fotografia principale
- Fonte / scheda di provenienza: https://commons.wikimedia.org/wiki/File:2015-07-25_The_Birthday_Massacre_(Amphi_festival_2015)_012.jpg
- Autore fotografico: Atamari
- Risoluzione dell'originale: 4176×2772 px
- Licenza: CC BY-SA 4.0
- Originale disponibile presso Wikimedia Commons; collegamento esterno nel markup HTML.
- Non attribuire la fotografia a Salvatore Sinatra. Non rimuovere l'attribuzione, il link di licenza o l'indicazione dell'autore. La presentazione via CSS adatta soltanto la finestra visiva e non genera file derivati.

## Fonti primarie
- https://thebirthdaymassacre.com/
- https://thebirthdaymassacre.bandcamp.com/music

## Architettura
- Branch Netlify: `netlify-light`
- Pubblicazione: `netlify/`
- `netlify/index.html`: documento, fotografia, icone SVG inline per link esterni, metadati e sezioni legali
- `netlify/assets/style.css`: layout e mobile
- `netlify/assets/app.js`: filtri di catalogo
- `netlify.toml`: directory di output statica

## Informativa editoriale
Questo è un archivio non ufficiale e indipendente. I marchi, le immagini, le opere e le pubblicazioni discografiche appartengono ai rispettivi titolari. Le fonti esterne restano sotto il controllo dei rispettivi gestori. Non dichiarare approvazioni o affiliazioni non esistenti.

## Pubblicazione
Per avviare il primo deploy Netlify con continuous deployment, associare il repository a Netlify scegliendo il branch di produzione `netlify-light`, directory `netlify`, senza comando di build. I file inseriti nel repository non equivalgono alla conferma di deploy; verificare l'identificativo e lo stato `ready` del deploy effettivo.
