# OAPPC Trapani — 3 proposte HTML

**Data:** 24 ottobre 2026  
**Formato:** prototipi navigabili in HTML, CSS e JavaScript puro; nessuna installazione richiesta.

## Da dove partire

Apri `index.html` nel browser per confrontare le tre direzioni grafiche. I tre siti demo sono:

- `proposta-01-civica.html`: portale pubblico, chiaro, servizio-first;
- `proposta-02-archivio.html`: direzione editoriale, patrimonio, studi e fotografia;
- `proposta-03-orizzonte.html`: direzione immersiva, dark, home con viewer 3D.

## Funzioni testabili in tutti e tre

Menu responsive; pagine Home, Albo, Vetrina professionisti, Profilo di studio, Atlante progetti, Scheda progetto, Formazione, Dettaglio evento, Servizi, L'Ordine; ricerca istantanea degli studi con filtro per competenza; filtri progetti; espansione FAQ; prototipo Canvas 3D con trascinamento touch/mouse, zoom, reset e visibilità della copertura. Ogni proposta usa hash navigation (`#formazione`, `#progetto`, ecc.), quindi funziona anche aprendo il file in locale.

## Limiti intenzionali e percorso tecnico

- Il visualizzatore usa un modello 3D **procedurale dimostrativo**, non importa né legge file SKP/DWG/IFC. L'integrazione reale richiederà una pipeline di import/conversione e una scelta di viewer specifico per i formati.
- Le scene grafiche sono **illustrazioni originali interpretative**, non foto documentarie.
- I nominativi degli studi, i progetti concettuali e gli eventi sono di fantasia e sono marcati come esempi. Palazzo Senatorio e le saline sono riferimenti geografico-culturali, non progetti attribuiti a iscritti.
- Albo, pagamenti, autenticazione, integrazione con i portali professionali e form di iscrizione non sono attivi.
- Le proposte sono **wireframe evoluti / prototipi di design**, **non** dichiarazioni di conformità AGID/WCAG: accessibilità, sicurezza, usabilità e trattamento dati richiedono audit e collaudo sul prodotto finale.
- In fase di sviluppo, implementare le Linee guida PA, la verifica degli obblighi di trasparenza applicabili all'Ordine, responsive, tastiera, alternative ai viewer e pubblicazione secondo policy degli iscritti.

## Sorgenti di riferimento

- https://www.architettitrapani.it/ordine/ — dati istituzionali e contatti.
- https://www.architettitrapani.it/professione/formazione-e-crediti/ — formazione.
- https://docs.italia.it/italia/design/lg-design-servizi-web/it/versione-corrente/index.html — Linee guida.

## Assets

`assets/palazzo.svg`, `corte.svg`, `saline.svg`, `studio.svg` sono illustrazioni vettoriali create per questa demo; `assets/preview-*.png` sono anteprime compositive, non screenshot del sito eseguito.

## Per pubblicare su hosting di test

Caricare l'intera cartella mantenendo i percorsi relativi; aprire `index.html`. Non richiede API key, CDN o librerie esterne. Non usare questo prototipo come portale istituzionale senza validazione tecnica ed editoriale.
