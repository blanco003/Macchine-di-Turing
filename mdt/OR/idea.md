- imposto # come separatore destro e ritorno sul primo carattere di input
- scorro tutto il primo operando (fino ad incontrare /) e torno indietro sul primo carattere del primo operando
    - finchè leggo X ed Y (1 e 0 già segnati) mi sposto verso sinistra
        - se incontro $\square$ vuol dire che ho terminato l'input dunque mi sposto verso destra cambiando ogni X in 1 e Y in 0, quando arrivo a leggere #, mi sposto a destra sul primo carattere del risultato ed accetto 
    - se 1 lo segno con X, se 0 lo segno con Y
    - scorro tutto il nastro fino ad incontrare # e torno indietro sul primo carattere del secondo operando
        - se 1 lo segno con X, se 0 lo segno con Y
        - mi sposto fino alla fine del nastro ed a seconda dei simboli che ho segnato scrivo 1 o 0 (OR(1,1)=1, OR(1,0)=OR(0,1)=1, OR(0,0)=0)
        - torno indietro scorrendo tutto il nastro, quando incontro $\square$ mi sposto a destra e ricomincio il procedimento

