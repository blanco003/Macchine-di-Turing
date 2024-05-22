- imposto come separatore a sinsitra dell'input $ e a destra #
- copio l'input a sinistra ed imposto come separatore a sinistra dell'input copiato #

- mi posiziono sull'ultimo simbolo del primo operando
- decremento di 1 il primo operando
    - se non ha più cifre da decrementare mi sposto nello stato per la copiatura del risultato

- mi posizioni sull'ultimo simbolo del secondo operando
- decremento di 1 il secondo operando
    - se non ha più cifra da decrementare, avevo già decrementato il primo operando quindi devo tornare ad incrementarlo e spostarmi nello stato per la copiatura del risultato

- mi posiziono sull'ultimo simbolo dell'input copiato e mi sposto verso sinistra
    - se il secondo operando è terminato (soli 0 trasformati in 1) lo trasformo in $\sqaure$ e mi sposto nello stato per la copiatura del risultato
    - se il secondo opernado ha almeno una cifra uguale ad 1 ricomincio il procedimento

- copiatura del risultato 
    - partendo dal separatore sinistro dell'input copiato # segno con X il simbolo incontrato
    - salto tutto l'input fino ad arrivare al secondo separatore a destra dell'input #, salto tutti i simboli già copiati e trasformo $\square$ con il simbolo da copiare
    - ritorno a sinistra fino ad incontare il simbolo segnato (X)

- quando non rimangono più simboli da segnare pulisco il nastro dal separatore sinistro #, tutte le X, e dal separatore $
- mi sposto sul primo simbolo del risultato ed accetto