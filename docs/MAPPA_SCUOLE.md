# Mappa delle scuole ANSIA

Pagina: https://marcoguerzoni.github.io/mypages/mappa_scuole.html

La pagina è utilizzabile anche aprendo direttamente il file HTML, con una connessione Internet. La cartografia vettoriale è fornita da OpenFreeMap; non usa il servizio raster `tile.openstreetmap.org`. Non richiede chiavi API. Le attribuzioni OpenFreeMap, OpenMapTiles e OpenStreetMap vengono visualizzate dal componente cartografico.

- Guida del fornitore: https://openfreemap.org/quick_start/
- Leaflet 1.9.4, MapLibre GL JS 5.6.1, adattatore MapLibre GL Leaflet 0.1.3.
- La cartografia richiede WebGL. In caso di errore del servizio o di WebGL, i punti e le schede restano disponibili; se Leaflet non carica, resta consultabile l'elenco.
- Dati: le 11 schede del precedente HTML, con coordinate, valori e punteggi originali. Alcuni nomi sono ripetuti e non sono stati deduplicati. Il filtro non ricalcola i punteggi.
- I punteggi riguardano il contenuto dei PTOF; non sono una misurazione diretta del benessere degli studenti.

La copia nella radice e quella in `docs/` sono identiche. GitHub Pages pubblica `docs/`.

## Verifica effettuata

Apertura `file://` e HTTPS, cartografia vettoriale caricata, nessuna richiesta al precedente servizio raster, 11 punti, ricerca, cambio indicatore, popup, stato senza risultati, visualizzazione mobile e indisponibilità simulata del fornitore. Coordinate e indicatori confrontati con l'HTML originale.

Un'eventuale nuova esportazione Folium dal notebook può reintrodurre la vecchia sorgente raster: conservare questo adattamento quando si aggiornano i dati.
