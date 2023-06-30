# Generatore siti web su Azure
Realizzazione, tramite l'approccio DevSecOps, di un software in grado di generare servizi web realistici.<br>
Il software deve essere in grado di:
1. Generare siti mockup di diverso tipo (e-commerce, news, blog, siti aziendali)
2. In base al tipo di sito scelto, l'utente deve avere la possibilità di selezionare diversi parametri per la generazione:
<br>2.1. tema, numero progetti (sito Portfolio)
<br>2.2. argomenti, quantità e lunghezza dei post (blog)
<br>2.3. il numero di prodotti, categorie, ecc. (e-commerce)
<br>2.4. sezioni, numero di articoli, lunghezza della pagina, ecc. (sito Web di notizie)
3. Generare tutti i file statici
4. Automatizzare la distribuzione sul Cloud tramite contenitori
5. Gestire in modo sicuro il flusso dei dati

Infine, abbiamo implementato un'API in grado di generare e gestire (avviare, spegnere, modificare) l'ambiente composto dagli “n” siti web di un determinato utente.
