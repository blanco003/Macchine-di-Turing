- imposto # come separatore destro e ritorno sulla primo carattere del nastro
$\\$

- mi sposto a sinistra fino ad incontrare 0 e mi sposto a destra (ora sono sull'ultimo carattere del primo operando)
    - se è 1 lo segno con X e mi sposto a destra
    - se è X mi continuo a spostare a sinistra
        - se incontro $\square$ vuol dire che il primo operando è terminato (dunque il max è il secondo operando)
            - scorro tutto il nastro riscrivendo al posto di X del primo operando 1
            - copio il secondo operando dopo #
            - mi sposto sul primo carattere del risultato ed accetto
$\\$
- mi sposto a destra fino ad incontrare # e mi sposto a destra (ora sono sull'ultimo carattere del secondo operando)
    - se è 1 lo segno con X e mi sposto a sinistra, e scorro tutto il nastro per ricominciare l'algoritmo
    - se è X mi continuo a spostare a sinistra
        - se incontro 0 vuol dire che il secondo operando è terminato (dunque il max è il primo operando)
            - scorro tutto il nastro verso destra per riscrivere al posto di X del secondo operando 1
            - copio il primo operando dopo #
            - mi sposto sul primo carattere del risultato ed accetto
