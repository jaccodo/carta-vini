# Carta dei Vini

App per il telefono con la carta dei vini del locale: ricerca, filtri per tipologia, scheda di ogni bottiglia con costo, prezzo al calice, asporto e tavolo, margini e fasce di prezzo consigliate. Si possono aggiungere, modificare, duplicare ed eliminare i vini.

Accesso con Google, dati condivisi in Firestore (collezione `vini`, parametri in `vini_impostazioni/parametri`), stesso progetto Firebase del Catalogo Prodotti.

Provarla sul PC: `node server.js` e apri
- http://localhost:5175/?prova  → modalità prova, senza login, dati solo nel browser
- http://localhost:5175         → app vera (login Google)

Primo avvio: con la carta vuota compare "Importa i vini iniziali", che carica `vini-iniziali.json` (ricavato dal vecchio Excel; non va su GitHub).
