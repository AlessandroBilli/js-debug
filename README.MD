#   js-debug
## Bundel 1



1- Il ciclo non partirà mai perchè poichè questo ciclo ha la condizione di  **i > 5** per funzionare ma i non è maggiore di 5 perchè è stato determinato come valore 0 e quindi questa condizone non è vera e il ciclo non si attiva mai e darà errore.



2- Questa function non avrà l'effetto desiderato, infatti con **(num % 2 = 0)**, perchè **=** viene utilizzato per dare una assegnazione, mentre per verificare ad esempio che la divisione dia il resto di 0, deve essere utilizato **===** perchè appunto serve per verificare che due valori sono perfettamente identici e quindi attiverà **if** solo e unicamente se il resto sarà 0.


3- Questo ciclo non funziona poichè le istruzioni del ciclo sono divise con **,** che serve semplicente a separare elementi e non a terminare un istrzuione, funzionalità che fa il **;**.


4- Questa function ha molteplici errori, il primo è **numbers.length - 1**, difatti in questo modo trascura l'ultimo elemento dell'array. Successivamente il **;** su **i++** è erratto perchè causa un interruzione della funzione senzà il completamento di essa e quindi darà errore. Andando avanti **(numbers % 2 = 0);**, è sbagliato per i due motivi precedentemente scritti. Proseguendo la posizione sbagliata del **return** all'interno del ciclo **for** fa sì che la funzione restituisca l'**array** evenNumbers dopo aver trovato il primo numero pari, interrompendo il ciclo e restituendo solo quel singolo numero anziché tutti i numeri pari.












