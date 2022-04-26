# prog_algo_2022

Diario degli esercizi:

01/03:
- Progettare un algoritmo che prende come parametro un intero $n$ e in tempo $O(\sqrt{n})$ verifica se il numero $n$ è semiprimo. Un numero si dice semiprimo se è il prodotto di due numeri primi (non necessariamente diversi).
Ad esempio $25$ e $15$ sono semiprimi, $17$ e $12$ no.
- Dimostrare che:
  * in un grafo connesso G ci sono sempre almeno due vertici che hanno lo stesso grado.
  * L’affermazione è ancora valida nel caso in cui il grafo non sia connesso?
  * Dimostrare che se tutti i vertici di un grafo G hanno grado almeno due allora nel grafo G c'è almeno un ciclo.
  * Se il grado di ogni vertice è esattamente due, si può affermare che G è un ciclo?

08/03
- Dimostrare che:
  * ogni grafo connesso contiene un vertice la cui rimozione non sconnette il grafo
  * ogni grafo connesso (con almeno due nodi) contiene due vertici la cui rimozione non sconnette il grafo.
- Sia G un grafo connesso. Per ogni nodo $x$, sia $D_x$ la distanza massima in G per $x$ (vale a dire: il numero massimo di archi che bisogna attraversare per raggiungere da $x$ qualunque altro nodo di G). Rispondere alle seguenti domande:
  * Possono esistere due nodi $u$ e $v$ in G tali che $D_u =4$ e $D_v = 8$?
  * Possono esistere due nodi $u$ e $v$ in G tali che $D_u =4$ e $D_v = 9$?
In caso affermativo esibite un esempio e altrimenti dimostrate l’impossibilità.

15/03
- Completamento del problema della volta precedente
- Notebook "01_intro_graphs"

22/03
- Esercizi su:
  * Calcola albero DFS
  * Elencare archi in avanti, all'indietro, e di attraversamento
  * Individua componenti fortemente connesse
  * Archi minimi da aggiungere per avere unica componente fortemente connessa
  * Archi da eliminare per DAG
  * Calcolare sort-topologico e DAG


29/03
- (Grafo delle antipatie) Bisogna formare dei gruppi di lavoro partizionando un insieme di n studenti i cui nomi vanno da 0 a n-1.
I gruppi li forma il docente che ad  ogni studente da la possibilità' di segnalare un eventuale studente con cui  non ha nessuna intenzione di formare gruppo. Queste informazioni vengono codificate in una 
lista L di n elementi dove L[i] e' lo studente segnalato da i (nel caso in cui lo studente  i non abbia segnalato nessuno e va d'accordo con tutti allora  L[i]=-1).

Progettare un algoritmo di complessità' O(n)  che prende come parametro  la lista L e restituisce il numero minimo di gruppi che il docente e' costretto a formare per accontentare le richieste di tutti gli studenti. 
Motivare la correttezza e la complessità' del vostro algoritmo e se possibile scrivetene il codice python.
- Ripasso algoritmo dei ponti
- Notebook "02_graphs_antipatie" e "03_ponti"

05/04
- Sia G = (V,E) un qualsiasi grafo orientato con pesi sugli archi, pesi che possono essere anche negativi ma in cui non sono presenti cicli di peso negativo.
  * Dimostrare che l’algoritmo di Dijkstra su grafi di questo tipo non calcola necessariamente i cammini di costo minimo tra la sorgente e gli altri nodi del grafo.
  * Per il calcolo dei cammini di costo minimo in G si suggerisce il seguente algoritmo: Sia M il costo minimo tra i costi degli archi di G. Modifichiamo i pesi degli archi di G sommando a ciascuno di questi l’intero |M| abbastanza grande da renderli tutti positivi. Al grafo che si ottiene G0 (che ha pesi positivi) applichiamo l’algoritmo di Dijkstra. I cammini minimi che vengono così calcolati sono anche cammini minimi per il grafo originale G? Motivare la risposta.
  * E l'MST?
 - Sia G un grafo non diretto, connesso e pesato. Dimostrare o confutare che un albero dei cammini minimi di G è anche un albero di copertura di peso minimo.
 - Provare che qualora i pesi di G siano tutti distinti, allora T è l’unico minimo albero di copertura. Mostrare che che la condizione sul fatto che i pesi siano tutti distinti non è necessaria per l’unicità del minimo albero di copertura.

12/04
- Dati due insiemi S_A e S_B di interi positivi, entrambi composti da N elementi, ordinarli in due array A (array ordinato degli elementi di S_A) e B (array ordinato degli elementi di S_B) tali per cui sia massimizzata la produttoria: C = a_1^{b_1} * a_2^{b_2} * ... * a_N^{b_N}. Fornire algoritmo, complessità, e dimostrare correttezza
- Dato un array di punti reali X = \[x_1, x_2, x_3, ...\] con x_1 <= x_2 <= x_3 <= ... <= x_n (ovvero, l'array è ordinato crescente), determinare il più piccolo insieme di segmenti chiusi (ovvero gli estremi sono compresi) di lunghezza unitaria che copre tutti i punti. Fornire algoritmo, complessità, e dimostrare correttezza
- Esempio di problema senza sottostruttura ottimale: il massimo percorso semplice in un grafo
- Problema di fornire un resto con un numero limitato di tagli di monete

19/04
No Lezione (Pasqua)

26/04
- Soluzione al problema del resto di monete
- Esercizi sul Master Theorem
- Problema dei chip

5/05
TBA

10/05
TBA

17/05
TBA
