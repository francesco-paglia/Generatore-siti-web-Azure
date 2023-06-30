# Generatore siti web su Azure
Realizzazione, tramite l'approccio DevSecOps, di un software in grado di generare servizi web realistici.<br>
Il software deve essere in grado di:
* Generare siti mockup di diverso tipo (e-commerce, news, blog, siti aziendali)
* In base al tipo di sito scelto, l'utente deve avere la possibilità di selezionare diversi parametri per la generazione:
** tema, numero progetti (sito Portfolio)
** argomenti, quantità e lunghezza dei post (blog)
** il numero di prodotti, categorie, ecc. (e-commerce)
** sezioni, numero di articoli, lunghezza della pagina, ecc. (sito Web di notizie)
* Generare tutti i file statici
* Automatizzare la distribuzione sul Cloud tramite contenitori
* Gestire in modo sicuro il flusso dei dati
<br>
Infine, abbiamo implementato un'API in grado di generare e gestire (avviare, spegnere, modificare) l'ambiente composto dagli “n” siti web di un determinato utente.
