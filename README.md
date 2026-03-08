# WeatherApp 🌤️

Una semplice e intuitiva applicazione web per visualizzare le condizioni meteorologiche in tempo reale di qualsiasi città nel mondo.

Questo progetto unisce l'interfaccia utente alla programmazione asincrona in JavaScript, permettendo di interrogare un'API meteo esterna e aggiornare il DOM dinamicamente con i risultati ottenuti.

## Demo

Puoi visualizzare il progetto live qui: [[Link alla Demo]](https://aledev2026.github.io/WeatherApp/)

## Caratteristiche

- **Ricerca per Città:** Inserisci il nome di una città per ottenere i dati meteo aggiornati istantaneamente.
- **Dati in Tempo Reale:** Visualizzazione della temperatura, delle condizioni atmosferiche (es. soleggiato, pioggia, nuvoloso) e di altri dettagli utili.
- **Interfaccia Responsiva:** Design curato grazie all'utilizzo di CSS, per garantire un'ottima visualizzazione su ogni schermo.
- **Gestione Errori:** Se la città inserita non esiste o la connessione fallisce, l'app avvisa l'utente in modo chiaro.

## Tecnologie Utilizzate

- **HTML5** - Per la struttura semantica dell'interfaccia.
- **CSS3** - Per lo stile e il layout dell'applicazione (`styles.css`).
- **Vanilla JavaScript** - Per la logica dell'app e le chiamate di rete tramite `fetch` (`script.js`).
- **REST API** - Utilizzo di un'API meteo esterna (es. OpenWeatherMap) per recuperare i dati in formato JSON.

## Come avviare il progetto localmente

Il progetto è puramente Frontend e non richiede l'installazione di librerie esterne.

1. Clona questo repository sul tuo computer:
   ```bash
   git clone [https://github.com/aledev2026/WeatherApp.git](https://github.com/aledev2026/WeatherApp.git)
Entra nella cartella del progetto:

Bash
cd WeatherApp

Apri il file index.html direttamente nel tuo browser.

Cerca la tua città preferita e scopri che tempo fa!
