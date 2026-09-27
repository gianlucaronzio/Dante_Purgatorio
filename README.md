# Il Purgatorio di Dante — sei canti fondamentali

App didattica interattiva a file singolo (`index.html`, nessuna dipendenza esterna oltre Google Fonts) per lo studio dei sei canti più studiati del Purgatorio dantesco: **I, III, V, VI, XI, XXX**.

Pensata per la classe IV Scienze Umane. Contiene:
- presentazione della cantica (struttura, contrappasso, durata delle pene) con fonti istituzionali;
- vademecum per la ricerca sul Dartmouth Dante Project;
- schema completo del Purgatorio;
- per ogni canto: link alle fonti, scheda del protagonista, scheda guida alla comprensione, 20 quiz a risposta multipla con soluzione.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `purgatorio-dante`).
2. Carica in esso il file `index.html` (mantenendo esattamente questo nome) e questo `README.md`.
3. Vai su **Settings → Pages** del repository.
4. In **Source**, seleziona il branch `main` (o `master`) e la cartella `/ (root)`.
5. Salva: dopo qualche minuto l'app sarà online all'indirizzo
   `https://<tuo-username>.github.io/<nome-repository>/`

Nessuna build, nessun server: è un sito statico a pagina singola.

## Modifiche future

Tutti i contenuti (fonti, canti, schede, quiz) sono raccolti in oggetti JavaScript all'inizio dello `<script>` del file `index.html` (`FONTI`, `CANTI`, `SCHEMA`): per aggiungere un canto, un quiz o una fonte è sufficiente intervenire lì, senza toccare il resto del codice.
