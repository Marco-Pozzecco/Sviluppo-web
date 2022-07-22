# Variables Declarations - Exercise 3

In questo esercizio occorre implementare la funzione `addStudent`, la quale si occupa di aggiungere un elemento all'array `students` dichiarato tramite `const`.

Qual è il metodo che possiamo utilizzare per aggiungere un elemento all'array?

Sai individuare il motivo per cui abbiamo la possibilità di aggiungere un elemento all'array nonostante abbiamo dichiarato la variabile come `readonly`?

Risposta:

I dati primitivi e strutturati sono trattati diversamente, in questo caso possiamo modificare l'array ma non ci sarebbe permesso assegnare un nuovo valore alla variabile, qualunque valore esso sia, anche un altro array.