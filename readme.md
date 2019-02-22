Incapsulamento: Nasconde dati tramite codice
Astrazione: Come rappresentare gli oggeti in codice
Ereditarietà: dove si crea una classe nuova a partire da una già esistente
Polimorfismo: una singola proprietà che è possibile inviare a oggetti distinti

Analizzare:
Problema
Osservazione
Comprensione
Lettura

Plasmare:
Analisi del problema
Diagramma

Programmare
Diagramma
Linguaggio di programmazione


# Cosa risolve la programmazione orientata ad oggetti?
La programmazione orientata ad oggetti risolve i problemi che la programmazione strutturata ha generato
I principali problemi della programmazione strutturata sono:
-Il codice generato è troppo lungo, quindi, difficile da leggere e da mantenere
-Se qualcosa non funziona, si rompe tutto
-Difficile da mantenere, in quanto codice spaghetti

# Logica
La logica della programmazione orientata ad oggetti è analizzare il problema in forma di oggetti
Le classi hanno:
-attributi: le proprietà che hanno
-metodi: le cose che sanno fare
Tutto l'insieme si chiama oggetto
Questa logica viene chiamata paradigma di programmazione

# Linguaggi orientati ad oggetti
I principali di linguaggi orientati ad oggetti sono:
-Java
-Php
-Python
-Javascript
-C#
-Ruby
-Kotlin

# UML : Unified Modeling Language
E' un insieme di elementi grafici che si uniscono per creare diagrammi, UML è un linguaggio e quindi ha regole per combinare gli elementi

# Oggetti
Un oggetto può essere concreto o astratto e possiede proprietà e comportamenti

Esempio:
Un utente è un oggetto concreto
Una sessione è un oggetto astratto o concettuale

Le proprietà si possono chiamare anche attributi, esempio:
nome, dimensione, forma ecc..

Comportamento: sono tutte le operazioni dell'oggetto, esempio
login(), logout() ecc..

Esempio completo:
Un cane può avere diverse proprietà:
-nome
-colore
-razza
-altezza
Può avere anche dei comportamenti:
-abbaiare
-mangiare
-dormire
-correre

Immaginiamo di avere un sistema di addozioni, quindi dovremmo aggiungere nuove proprietà
-id : ho bisogno di un identificatore così da poterlo distinguere dagli altri cani
E anche nuovi comportamenti
essereAdottato()

# Astrazione e Classi
Una classe è il modello sulla quale si contruirà il nostro oggetto, quindi bisogna analizzare gli oggetti per creare classi, questa azione viene chiamata ASTRAZIONE, quanto noi estraiamo i dati da un oggetto per generare una classe.

# Modularità
E' un concetto della programmazione orientata ad oggetti e consiste nel dividere il sistema e creare moduli indipendenti, questo garantisce:
-Poter riutilizzare codice 
-Evitare collassi
-Maggior mantinibilità 
-Maggior leggibilità
-Una risoluzione più rapida dei problemi
Si ispira molto dal concetto di disegno modulare.
Per rendere la modularità effettiva ogni classe dovrà essere divisa in differenti file

# DRY: Don't Repeat Yoursel
E' una filosofia della programmazione che consiste nell'eliminare il codice duplicato, tutto questo è permesso grazie all'ereditarietà.
Quest'ultima ci permette creare nuove classi partendo da altre
"Quando mi rendo conto che abbiamo caratteristiche e comportamenti uguali devo realizzare un astrazione"