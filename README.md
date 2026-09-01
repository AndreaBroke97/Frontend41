# Esercizi Frontend — HTML, CSS e JavaScript

Esercizi e progetti di sviluppo frontend svolti durante i miei studi alla Steve Jobs Academy, sede di Catania: dalle basi del CSS (selettori, media query, grid) alla manipolazione del DOM con JavaScript, fino ai quattro progetti realizzati come esame finale del modulo.

---

## Sul contenuto di questa repository

Questa repository raccoglie l'intero percorso di apprendimento del frontend, non solo i risultati finiti. Per questo motivo convivono cartelle con esercizi completi, prove ed esperimenti lasciati a metà: fanno parte del processo di apprendimento tanto quanto i progetti riusciti, e ho preferito lasciarli visibili piuttosto che ripulire la repository facendo sembrare il percorso più lineare di quanto sia stato.

In particolare, la cartella `01_sito_iphone` è una delle meno curate del gruppo: è rimasta incompleta e con alcune imprecisioni. La lascio così com'è, a documentazione del percorso.

Un progetto (`27_ESAME-FE-utente-API`) è stato realizzato con il supporto di di IA solo per la parte di JavaScript a causa di poca esperienza, purtroppo per colpa di cause esterne all'interno dell'istituto, come indicato direttamente nel codice.

---

## Esercizi (CSS e layout)

| Cartella | Contenuto |
|---|---|
| `00_sito_google` | Riproduzione della homepage di Google |
| `01_sito_iphone` | Riproduzione del sito iPhone — incompleta |
| `02_media_queries` | Esercizio sulle media query per il responsive design |
| `03_doppia_class` | Esercizio sull'uso di più classi CSS sullo stesso elemento |
| `04_sito_bike.it` | Riproduzione di un sito di e-commerce di biciclette |
| `05_specificità_dei_selettori` | Esercizio sulla specificità dei selettori CSS |
| `06_grid` | Esercizio base su CSS Grid |
| `07_grid_foto` | Galleria fotografica con CSS Grid |
| `08_prova_grid` | Prova/esperimento su CSS Grid |
| `09_prova_media_quieres` | Prova/esperimento su media query |
| `21_position_sticky` | Esercizio sulla proprietà `position: sticky` |

## Esercizi (JavaScript e DOM)

| Cartella | Contenuto |
|---|---|
| `10_javascript` | Esercizi introduttivi di JavaScript incompleti |
| `11_javascript_array_for` | Esercizi su array e cicli `for` in JavaScript |
| `12_somma_e_media_java_array` | Calcolo di somma e media su un array in JavaScript |
| `13_html_java` | Esercizio di integrazione tra HTML e JavaScript |
| `14_dom` | Introduzione alla manipolazione del DOM |
| `15_esercitazione_dom` | Esercitazione sul DOM |
| `16_button_dom` | Interazione con un bottone tramite il DOM |
| `17_YUEI_HTML` | Esercizio HTML |
| `18_button_dom2` | Seconda esercitazione su bottoni e DOM |

## Altri esercizi

| Cartella | Contenuto |
|---|---|
| `20_esercitazione` | Esercitazione generale |
| `23_provaEsame` | Simulazione d'esame |

---

## I quattro progetti d'esame

### 24_ESAME-FINALE-FE — Card prodotto e-commerce

Card prodotto in stile e-commerce per una sneaker Calvin Klein, con immagine, prezzo scontato, prezzo originale barrato e un badge promozionale. Esercizio mirato sulla struttura di una card prodotto e sulla gestione visiva dello sconto.

### 25_Esame-FE-Team-Rxjs — Pagina team

Pagina che presenta il team di RxJS con una card per ciascun membro, contenente nome e avatar. Esercizio sul layout a griglia di card ripetute.

### 26_Esame-FE-sito-airbnb — Layout in stile Airbnb

Riproduzione parziale del layout di Airbnb: barra di navigazione con ricerca e due sezioni di alloggi in evidenza, ciascuna con una fila di card a scorrimento orizzontale.

### 27_ESAME-FE-utente-API — Utenti da API

Pagina che recupera una lista di utenti da un'API pubblica (JSONPlaceholder) e genera dinamicamente una card per ciascuno, con nome ed email. Include anche un pulsante che alterna uno stile di colore sulle card già generate.

---

## Come eseguire i progetti

La maggior parte delle cartelle contiene pagine statiche HTML/CSS: basta aprire il file `.html` direttamente nel browser.

Per i progetti con JavaScript (dalla cartella `10_javascript` in poi, e i quattro esami), è consigliabile aprire la pagina tramite un piccolo server locale (ad esempio l'estensione "Live Server" di VS Code) invece che con il doppio click, per evitare eventuali limitazioni del browser sui file caricati localmente.

Il progetto `27_ESAME-FE-utente-API` richiede una connessione a internet attiva, perché recupera i dati da un'API esterna.
