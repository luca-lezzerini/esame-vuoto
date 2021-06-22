# esame-vuoto

Client Angular + server SpringBoot vuoti da usare come base per esami ed esercitazioni.

Contengono codice di test.

Una volta fatto pull, andare nella cartella di progetto del client Angular e digitare

# npm update

per allineare le librerie node.js

Poi lanciare il client come al solito (ng s --o) e, dopo la compilazione, partirà la demo ufficiale di Angular.

Poi lanciare il database assicurandosi di avere un'utenza come indicato nell'application.properties del server.

Poi lanciare il server. Una volta che il server è partito, fare una richiesta GET da browser su http://localhost:8080/test-esame 

Dopo alcuni istanti si ottiene la risposta seguente:

TestEntity{id=8, num1=2, num2=3, result=5}

Se tutto funziona come descritto sopra, il client e il server sono pronti per l'esame. Il codice di test presente in entrambi può essere tranquillamente cancellato o ignorato nel corso dell'esame.

