# Variables Declarations - Exercise 1

In questo esercizio si sta cercando di far stampare la frase "Paul plays football", ma se si esegue il codice si noterà l'errore "**personName is not defined**".

Cosa occorre fare per fixare l'errore?

Risposta:
Il problema risiede nello scope della variabile personName, pertanto:
1. Eliminare il blocco condizionale in quanto sempre vero;
2. Cambiare la parola chiave let con var;
3. Spostare l'assegnazione della stringa ' plays footbal' all'interno del blocco condizionale.