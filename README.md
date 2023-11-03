# Generatore siti web su Azure
Realizzazione, tramite l'approccio DevSecOps, di un software in grado di generare servizi web realistici.

Il software deve essere in grado di:</br>
&nbsp;&nbsp;&nbsp;&nbsp;**1 -** Generare siti mockup di diverso tipo (e-commerce, news, blog, siti aziendali).</br>
&nbsp;&nbsp;&nbsp;&nbsp;**2 -** Generare tutti i file statici.</br>
&nbsp;&nbsp;&nbsp;&nbsp;**3 -** Automatizzare la distribuzione sul Cloud tramite contenitori.</br>
&nbsp;&nbsp;&nbsp;&nbsp;**4 -** Gestire in modo sicuro il flusso dei dati.</br>
&nbsp;&nbsp;&nbsp;&nbsp;**5 -** In base al tipo di sito scelto, l'utente deve avere la possibilità di selezionare diversi parametri per la generazione:</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Portfolio:** tema e numero progetti.</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Blog:** argomenti, quantità e lunghezza dei post.</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**E-commerce:** informazioni sui prodotti venduti.</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Notizie:** sezioni, numero di articoli, lunghezza della pagina.</br>

Infine, abbiamo implementato un'API in grado di generare e gestire (avviare, spegnere, modificare) l'ambiente composto dagli “n” siti web di un determinato utente.
