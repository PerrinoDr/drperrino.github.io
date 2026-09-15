# Sito Web — Dr. Felice Perrino, Cardiologo

Sito statico (HTML + Tailwind CSS via CDN + JS vanilla), pronto per GitHub Pages senza bisogno di build.
Contenuti allineati al sito già pubblicato su https://perrinodr.github.io/.

## Struttura

```
index.html          Home
trattamenti.html     Trattamenti e Servizi (con filtri per categoria)
blog.html             Blog (con ricerca e filtri per categoria)
contatti.html         Contatti e Prenotazioni
css/style.css         Stili condivisi (colori, font, animazioni)
js/script.js          Menu mobile, animazioni, accordion, slider, form
```

## Come pubblicarlo su GitHub Pages

1. Nel repository `perrinodr.github.io` (o un nuovo repository), carica tutti i file di questa cartella nella **root**, mantenendo le sottocartelle `css/` e `js/`.
2. Vai su **Settings → Pages**.
3. In "Build and deployment", scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`.
4. Il sito sarà online dopo circa un minuto.

## Dati riportati dal sito esistente

- Indirizzo: Viale Vittoria, 3, 43125 Parma PR
- Email: dr.perrino@protonmail.com
- Telefono e orari: ancora "da confermare", come nel sito originale
- Il modulo di prenotazione verifica i dati ma non li invia realmente (nessun backend collegato) — per attivare l'invio effettivo serve un servizio come Formspree o Netlify Forms

## Personalizzazioni consigliate prima della pubblicazione

- Sostituire le immagini placeholder (da Unsplash) con foto reali dello studio e del dottore
- Aggiungere telefono e orari appena confermati
- Aggiornare i dati dell'Ordine dei Medici e la Partita IVA nel footer
- Collegare il form a un servizio di invio email reale
