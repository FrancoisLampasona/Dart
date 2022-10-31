# Introduzione a Dart 

<center>
<img src="https://swansoftwaresolutions.com/wp-content/uploads/2020/02/08.20.20-What-is-Dart-and-how-is-it-used-1024x576.jpg" width="600" height="290">

</center>

> ##  Dart :

- Linguaggio di programmazione orientanto agli oggetti
- Linguaggio tipizzato
- Linguaggio C-Like (Imperativo come Java e C)
- Gestione della memoria mediante garbage collection

---
> ## Come funziona Dart ?

<center> 

|Standalone :             |       Compilato :                 |     Web :         |
|    :---                 |             :---                  |     :--           |
|- Just In Time (JIT)     |       - Ahead of Time (AOT)       |     - Traspilato  |
|- Interpretato           |       - Compilato                 |     - No DVM      |
|- Dart Virtual Machine   |       - No DVM                    |     - Browser     |
|- Basse prestazioni      |       - Alte prestazioni          |                   |
|- Multiplatform          |       - MultiPlatform             |                   |

</center>


> ## Indice dei contenuti :

---
*Il linguaggio :*

1. [Variabili e Tipi](#variabili-e-tipi)
2. I Modificatori
3. Null-safety
4. Operatori
5. Costrutti di selezione
6. Costrutti di iterazione
7. Le asserzioni
8. Funzioni

*Paradigma Object Oriented :*

9. Classi
10. Costruttori
11. Getters e Setters
12. Ereditarietà
13. Classi Astratte
14. Interfacce
15. Extensions
16. Mixins
17. Generics
18. Attributi e metodi statistici
19. Classi invocabili
20. Enum

*Dart Avanzata :*

21. Eccezioni
22. Librerie
23. Commenti

*Programmazione Asincrona :*

24. Future
25. Stream
26. Isolate
---
> ## Variabili e Tipi :
<br>

Variabile = rappresentazione in memoria di un determinato dato

 Dichiarazione della variabile può essere esplicita o implicita : <br>
>- Esplicita => String , Int , Boolean (nome-della-varibile) <br>
>- Implicita => var (nome-della-variabile) è il compiltare a stabilirne il tipo

I tipi possono : Numeri , Stringe , Boolean , Liste , Set , Dizionari 

Numeri  = Interi / Floating Point <br>
Stringe = Carattarei Alpha Numerici <br>
Boolean = True o False

>Liste = Elementi seguono un certo ordine sono numerati <br>
>Set   = Gli elementi non hanno vincoli sugli ordine <br>
>Dizionari = Ogni elemento è associato ad una chiave <br>

Tipo speciale : `dynamic`

`Dynamic` : Quando il tempo della variabile non è noto durante la compilazione





