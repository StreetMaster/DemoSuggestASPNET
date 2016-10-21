# DemoSuggestASPNET
Demo ASP.NET per l'utilizzo del servizio SUGGEST di autocompletamento degli indirizzi italiani  


Il progetto è sviluppato in C# - Framework 4.6.1


L'end point della libreria da includere nella sezione js di inizializzazione 
    http://ec2-46-137-97-173.eu-west-1.compute.amazonaws.com/suggest/js/1.0/suggest.js

Per l'utilizzo registrarsi sul sito http://streetmaster.it e richiedere la chiave per il servizio SUGGEST.
Il servizio permette di effettuare in maniera gratuita 1800 chiamate mensili. 
Per volumi di utilizzo maggiori consultare nel sito i piani di utilizzo.
Se non viene utilizzata una chiave valida il servizio restituisce nel menu a tendina un avviso.

Il servizio ha a livello di singola strada su tutto il territorio nazionale.
La base dati di riferimento è costantemente aggiornata con le variazioni amministrative e postali ufficiali.
La versione FILL rispetto alla versione VERIFY correda l'output con molti dati aggiuntivi.
  
Output di base:
  - comune\indirizzo verificato e corretto in tutti i suoi compomenti
  
Informazioni aggiuntive SUGGEST  
 - codice istat del comune
 - codice istat della regione
 - geocodifica xy
 - scomposizione dell'indirizzo in Denominazione urbanistica e Toponimo 
 
Per ogni domanda o chiarimento manda una mail a supporto@streetmaster.it
