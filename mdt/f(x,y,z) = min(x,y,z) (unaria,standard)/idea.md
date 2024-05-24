- imposto # come separatore destro e ritorno all'inzio dell'input


- scorro tutti gli 1 e le X (1 del primo operando già segnati) fino ad incontrare 0 e mi sposto a sinistra (sono sull'ultimo ultimo carattere del primo operando)
    - se incontro X continuo a spostarmi a sinistra
    - se incontro 1 lo sostituisco con X e mi sposto a destra 
    - se incontro $\square$ vuol dire che ho finito i simboli del primo operando
        - scorro tutto il nastro fino alla fine risistemando l'input (trasformando le Y e Z in 1)
        - ritorno sul primo carattere del primo operando
            - se incontro 1 lo segno con Y, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare Y, lo sostituisco con 1 e mi sposto a destra
            - se incontro X lo segno con Y, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare Y, lo sostituisco con 1 e mi sposto a destra
            - se incontro 0 (ho finito di copiare il risultato), scorro il nastro fino ad incontrare #, mi sposto a destra ed accetto (sono sul primo simbolo di output) 


- ora sono posizionato sul primo simbolo del secondo operando, scorro tutti gli 1 e le Y (1 del secondo operando già segnati) fino ad incontrare 0 mi sposto a sinistra (sono sull'ultimoultimo carattere del secondo operando)
    - se incontro Y continuo a spostarmi a sinistra
    - se incontro 1 lo sostituisco con Y e mi sposto a destra 
    - se incontro 0 vuol dire che ho finito i simboli del secondo operando
        - mi sposto all'inzio del nastro
        - scorro tutto il nastro sostituendo ogni X e Z con 1 
        - torno indietro fino a posizionarmi sul primo simbolo del secondo operando
            - se incontro 1 lo segno con X, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare X, lo sostituisco con 1 e mi sposto a destra
            - se incontro Y lo segno con X, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare X, lo sostituisco con 1 e mi sposto a destra
            - se incontro 0 (ho finito di copiare il risultato), scorro il nastro fino ad incontrare #, mi sposto a destra ed accetto (sono sul primo simbolo di output) 
            

- ora sono posizionato sul primo simbolo del terzo operando, scorro tutti gli 1 e le Z (1 del terzo operando già segnati) fino ad incontrare 0 mi sposto a sinistra (sono sull'ultimo carattere del secondo operando)
    - se incontro Z continuo a spostarmi a sinistra
    - se incontro 1 lo sostituisco con Z e mi sposto a destra 
    - se incontro 0 vuol dire che ho finito i simboli del terzo operando
        - scorro tutto il nastro verso sinistra trasformando ogni X e Y in 1
        - ritorno sul primo carattere del terzo operando
            - se incontro 1 lo segno con X, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare X, lo sostituisco con 1 e mi sposto a destra
            - se incontro Z lo segno con X, scorro tutto il nastro, sostituisco $\square$ con 1, ritorno indietro fino ad incontrare X, lo sostituisco con 1 e mi sposto a destra
            - se incontro # (ho finito di copiare il risultato), mi sposto a destra ed accetto (sono sul primo simbolo di output) 

