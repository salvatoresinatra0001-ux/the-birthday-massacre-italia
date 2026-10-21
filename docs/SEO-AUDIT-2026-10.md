# SEO tecnico e audit homepage — ottobre 2026

**Progetto:** The Birthday Massacre Italia  
**URL canonico:** https://www.thebirthdaymassacre-italia.it/  
**Branch di lavoro:** `seo-logo-favicon-2026-10`  
**Ambito:** revisione statica del markup della homepage, metadati, immagini, dati strutturati e file di crawl. Non equivale a un crawl esterno completo né a un punteggio Lighthouse.

## Interventi applicati

- Titolo SEO aggiornato: **The Birthday Massacre Italia | Discografia e archivio**.
- Meta description specifica, in italiano, con contenuti reali della pagina e senza promesse di affiliazione ufficiale.
- Canonical assoluto coerente con il dominio principale.
- Meta robots esplicito con indicazioni per anteprime di immagini, snippet e video.
- Open Graph completo per sito, URL, titolo, descrizione, immagine e testo alternativo.
- Twitter Card `summary_large_image` con titolo, descrizione e alt immagine.
- JSON-LD `WebSite`, `WebPage` e `MusicGroup` collegati tramite `@id`; il sito resta dichiarato come archivio indipendente.
- H1 aggiornato per includere il nome della band senza perdere il tono editoriale.
- Collegamenti di preconnessione per il dominio dell'immagine della band e Wikimedia Commons.
- Favicon fotografico ricavato da una fotografia su Wikimedia Commons, con fallback SVG locale; touch icon configurata.
- Logo/wordmark ad alta risoluzione inserito in hero, con alt descrittivo e collegamento esplicito al sito ufficiale della band.
- Il logo è caricato dalla CDN del sito ufficiale, senza alterarne il file; la disponibilità e il rendering finale vanno verificati nel browser dopo la pubblicazione.
- Sitemap e robots.txt già presenti e coerenti con il dominio canonico; sitemap include homepage e pagina evento italiana.

## Controlli statici

- Un solo H1 previsto nella homepage.
- Canonical assoluto presente.
- Titolo, descrizione, Open Graph e Twitter Card presenti.
- JSON-LD presente con lingua italiana e relazioni esplicite tra sito, pagina e gruppo musicale.
- Immagine hero già descritta con alt e crediti/licenza; fotografia usata per favicon/social è collegata alla relativa pagina file di Wikimedia Commons.
- Navigazione, contenuti editoriali, CSS responsive e JavaScript esistenti mantenuti.

## Limiti e verifiche ancora necessarie

- Il crawl Site Audit di Semrush non è stato eseguibile: l'account richiede ulteriori API units. Non viene quindi dichiarato un punteggio Semrush o un audit crawler completato.
- Dopo il merge/deploy verificare nel browser favicon, caricamento del logo esterno, resa mobile e anteprime social.
- Eseguire una scansione live di link interni/esterni, status HTTP, redirect, Core Web Vitals e dati strutturati con strumenti crawler e Rich Results Test.
- Per la fotografia di Wikimedia Commons mantenere il credito e la licenza CC BY-SA 4.0 associati alla pagina del file.
- Il wordmark è proprietà dei rispettivi titolari; il sito italiano resta un archivio indipendente e non affiliato.

## Stato

Markup e asset reference aggiornati sul branch di lavoro. Questo documento registra controlli statici e limiti; non attesta un punteggio di performance, indicizzazione Google o una verifica visiva cross-device.
