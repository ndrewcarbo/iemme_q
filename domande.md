## Che cos'è una classe astratta?
Una classe si può definire come una aggregazione di metodi e attributi. Una classe astratta è una classe che non può essere istanziata. È un'astrazione, una sorta di stampo che contiene attributi e metodi che verranno poi ereditati dalle sue sottoclassi. Una classe astratta viene ESTESA da una sottoclasse.
Un metodo astratto è un metodo SENZA CORPO che deve essere necessariamente essere ereditato da una sottoclasse tramite la parola chiave OVERRIDE che ci permette di riscrivere il metodo nella sottoclasse.

## Che cos'è la classe Object?
Object è la superclasse dalla quale derivano tutte le entità.

## Che cos'è la firma?
È il modo con cui un metodo può essere richiamat. Due metodi non possono avere la stessa firma sebbene possano chiamarsi allo stesso modo. Le firme devono essere necessariamente diverse (cioè avere parametri diversi). Quando esistono dei metodi che hanno lo stesso nome ma firme diverse si dice che si sta facendo un OVERLOAD di parametri.

## Che cos'è una lista?
Una lista risolve il problema degli array statici: è una raccolta di dati ch possono anche non essere delo stesso tipo e la lunghezza della lista è variabile.

## Che cos'è un array?
Un array è una raccolta di dati omogenea e statica. Cioè un array ha una lunghezza fissa e al suo interno i dati sono tutti dello stesso tipo.

## Se scrivo IEsempio<T>?
IEsempio è un'interfaccia. <T> rappresenta un tipo di dato generico.
L'elemento interfaccia è un costrutto che contiene esclusivamente dei metodi senza corpo. È in realtà un elenco di metodi senza corpo quindi tecnicamente non è una classe, ma ci dice esclusivamente cosa si è costretti ad implementare a livello di metodi Al suo interno quindi NON ci sono attributi.
Un'interfaccia viene IMPLEMENTATA.

## Che cos'è un metodo statico?
È un metodo che non ha bisogno dell'istanza di una classe per essere richiamato I metodi static vengono allocati immediatamente all'inizio del programma. Un esempio di metodo static è il MAIN che rappresenta l'unizio del mio programma.

## Concetto di information hiding e incapsulamento
Con il concetto di incapsulamento intendiamo dire che tutto ciò che appartiene ad una classe viene descritto al suo interno. È buona norma non far acceder direttamente gli utenti agli attributi di una classe, quindi utiliziamo i modificatori di accesso (public, private) consentendo il loro accesso solo tramite i metodi get e set, che permettono di filtrare il dato in entrata e il dato in uscita. Con private posso quindi nascondere i dettagli costruttivi (attributi, metodi, filtri) della mia classe (e quindi delle sue istanze), questo è il concetto di information hiding.

## STORED PROCEDURE 
sono un innesto di linguaggio programmazione in una base dati. 
la store procedure è una vista con cui posso interagire

 ## LINQ
è UN COMPONENTE CHE AGGIUNGE AI LINGUAGGI .NET LA POSSIBILITà DI EFFETTUARE INTERROGAZIONI SU OGGETTI UTILIZZANDO
UNA SINTASSI SIMILE A SQL

## diamond <  >
il tipo di dato che si aspetta la lista

## SOLID 
SONO DELLE REGOLE CHE DEVONO ESSERE SEGUITE QUANDO SI SVILUPPA UN SOFTWARE
DEI PRINCIPI DI WELL CODING
5:
-SINGLE RESPONSIBILITY(ogni classe ha una sola responsabilità)
-OPEN/CLOSED (ereditarietà quindi aperta alle estensioni ma chiusa alle modifiche)
-LISKOV (polimorfismo sostituiammo con propri sottotipi)
-INTERFACE SEGREGATION (interfacce specifiche che suddividono repsponsbilita piuttosto che una sola)
-DEPENDENCY INVERSION

## VIEW
la VIEW o vista non permette inserimento , eliminazione
effettivmente la view non esistono 




## stringa di comando per fare push
git remote add origin https://github.com/acelilli/iemme_q.git



git branch -M main

git push -u origin main
