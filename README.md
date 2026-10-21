# HandPod, prototipo navigabile

Prototipo della tesi magistrale "HandPod and the Future of the Kitchen" (Politecnico di Milano, Integrated Product Design).

Pagina statica: `index.html` più quattro immagini. Nessun dato viene salvato sul server.

## Traduzione delle frasi (modello)

Fuori da Claude la pagina usa OpenRouter (modelli gratuiti) oppure l'API Anthropic. Nel pannello di destra,
sezione "Modello (versione sito)", il ricercatore sceglie il servizio e incolla la propria chiave: resta solo nel browser di quel computer (localStorage),
non entra nel log e non è mai nei file di questo repository. Senza chiave il prototipo funziona come
con la rete spenta: si compone toccando lo schermo.

## Log

"Esporta log (JSON)" scarica il file della sessione. "Importa sessione" lo ricarica e riprende
partecipante, profili e conversazione.
