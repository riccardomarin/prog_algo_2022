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
TBD
