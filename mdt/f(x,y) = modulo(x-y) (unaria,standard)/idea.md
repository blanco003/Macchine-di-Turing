- imposto $\$$ come separatore sinistro e # come separatore destro
- copio l'input a sinistra ed imposto come separatore a sinistra @
$\\$

- scorro il primo operando e quando incontro 0 mi sposto a sinistra (ora sono sull'ultimo simbolo del primo opernado)
    - se incontro 1 lo segno con X e mi sposto a destra sul secondo operando
    - finchè incontro X mi sposto a sinistra
        - se incontro @ vuol dire che ho esaurito il primo operando
            - trasformo @ , tutte le X del primo operando e lo 0 separatore in $\square$ e  mi sposto sul secondo operando
                - se incontro X vuol dire che erano simboli già sottratti dunque li trasformo in $\square$
                - se incontro 1 lo segno con Y, scorro tutto il nastro e lo scrivo alla fine
                - se incontro $\$$ lo trasformo in $\square$, mi sposto sul primo simbolo del risultato ed accetto

$\\$
- scorro tutto il secondo operando e quando incontro $\$$ mi sposto a sinistra(ora sono sull'ultimo simbolo del secondo operando)
    - se incontro 1 lo segno con X e mi sposto tutto a sinistra per ricominciare l'algoritmo
    - finchè incontro X mi sposto a sinistra
        - se incontro 0 vuol dire che ho esaurito il secondo operando (!! mi devo ricordare che avevo già sottratto 1 dal primo operando)
            - trasformo tutte lo 0 separatore e tutte le X del secondo operando in $\square$ e mi sposto tutto a sinistra
                - trasformo tutte le X del primo operando in $\square$
                - trasformo @ in 1 (poichè avevo già sottratto 1 dal primo opernado)
                - se incontro 1 lo segno con Y, scorro tutto il nastro e lo scrivo alla fine
                - scorro tutti i simboli $\square$
                - se incontro $\$$ lo trasformo in $\square$, mi sposto sul primo simbolo del risultato ed accetto
 