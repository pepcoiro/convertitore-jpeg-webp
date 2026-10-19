# Convertitore JPEG → WebP

Utility web minimale per convertire immagini JPG/JPEG in WebP direttamente nel browser, con tema chiaro/scuro manuale.

## Utilizzo

1. Apri `index.html` in un browser moderno oppure visita la versione pubblicata con GitHub Pages.
2. Seleziona o trascina uno o più file JPG/JPEG.
3. Imposta la dimensione massima per immagine (predefinita: 5 MB), la qualità iniziale e un suffisso facoltativo.
4. Premi **Converti**. Scarica ogni file singolarmente oppure tutti insieme in un archivio ZIP.

## Pubblicare con GitHub Pages

Nel repository, apri **Settings → Pages**. In **Build and deployment**, scegli **Deploy from a branch**, seleziona il branch `main` e la cartella `/(root)`, poi salva. Al termine della pubblicazione GitHub mostrerà l'indirizzo del sito nella stessa sezione.

## Privacy e limiti

- La conversione avviene sul dispositivo: le immagini non vengono caricate su un server.
- Per creare lo ZIP viene caricata su richiesta la libreria JSZip da cdnjs. Se non hai una connessione, puoi comunque scaricare i file uno alla volta.
- Il browser deve supportare l'esportazione WebP.
- Il limite di dimensione è un obiettivo: se non è raggiungibile nemmeno alla qualità minima, il risultato viene segnalato.
- Gli originali non vengono modificati.

## File

- `index.html` — applicazione completa (HTML, CSS e JavaScript).
- `README.md` — istruzioni per l'uso e la pubblicazione.
