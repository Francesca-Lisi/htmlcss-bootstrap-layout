Bootstrap Grid Layout
===
Esercizio 6/11/2024
## Consegna
Riprodurre un layout con griglia responsive utilizzando Bootstrap 5! 

Aiutatevi con gli screenshot in allegato e le classi di Bootstrap per riprodurre il giusto layout a seconda dello spazio a disposizione sui diversi dispositivi

**Bonus**

- E’ possibile centralizzare in qualche punto il fatto che il testo sia bianco?
- E’ possibile centralizzare il layout delle colonne di qualche riga utilizzando la classe row-cols?

## Sviluppo
1. Dopo aver creato la struttura base del progetto inserendo i file necessari (readme, html, css) ho cambiato il *Title* del file e inserito nella *Head* i link per collegare Bootstrap e il file style.css.
2. Suddivido il body in *Header* e *Main* ed inserisco all'interno del primo il Titolo e sottotitolo che centreremo e allontaneremo attraverso le classi bootstrap.
3. Il main è composto da un container che contiene 3 row, ognuna delle quali presenta un numero di colonne e un comportamento responsive diverso. Attraverso le classi applicate alle row e alle colonne riproduciamo gli stili degli screen.

**Bonus**

- E’ possibile centralizzare il testo bianco applicandolo direttamente al **.container** per poi applicare il testo nero ai blocchi chiari attraverso la classe **.text-bg-light**.
- E’ possibile centralizzare il layout delle colonne della terza row (l'unica che presenta le colonne di uguale dimensione in tutti i breakpoint) applicando le classi (**.row-cols-n**) per i vari breakpoint direttamente alla row anzichè per ogni colonna.


