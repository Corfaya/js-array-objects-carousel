Creare un carosello. Se non avete fantasia potete copiare l'immagine allegata (è comprensiva di bonus).
Numero di push minimi: 10
Raccomandazione: seguite le milestone una per una. Ricordarsi/rivedere il live coding della mattina
può essere d'aiuto
*Milestone 0:*
Come visto a lezione, focalizziamoci prima sulla creazione del markup statico: costruiamo il container e inseriamo l'immagine grande in modo da poter stilare lo slider.
*Milestone 1:*
Ora rimuoviamo i contenuti statici e usiamo l’array di oggetti letterali per popolare dinamicamente il carosello.
****
Al click dell'utente sulle frecce verso sinistra o destra, l'immagine attiva diventerà visibile e dovremo aggiungervi titolo e testo.
**Milestone 2:
Aggiungere il *ciclo infinito* del carosello.** Ovvero se la miniatura attiva è la prima e l'utente clicca la freccia verso destra, la miniatura che deve attivarsi sarà l'ultima e viceversa per l'ultima miniatura se l'utente clicca la freccia verso sinistra.
*BONUS 1:*
Aggiungere le thumbnails (sottoforma di miniatura) ed al click attivare l’immagine corrispondente.
*BONUS 2:*
Aggiungere funzionalità di autoplay: dopo un certo periodo di tempo (3 secondi) l’immagine attiva dovrà cambiare alla successiva.
*BONUS 3:*
Aggiungere bottoni di start/stop e di inversione del meccanismo di autoplay.

# FLOW
- Creare container su HTML e stilizzare
- Rimuovo da HTML i contenuti statici e li reinserisco tramite array di oggetti
- Creo un ciclo in base all'evento click