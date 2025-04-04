# Tracce proposte

## Progetto da 6.5 punti: analisi e visualizzazione dati

### Descrizione generale
Utilizzare le librerie Pandas e Seaborn per caricare, analizzare ed esplorare un dataset. Il progetto consiste nell’individuare alcune domande interessanti da porsi sui dati, esplorare le risposte attraverso analisi statistiche e visualizzazioni significative, e presentare i risultati in modo chiaro e ordinato.
### Richieste
Il progetto deve includere:
- Caricamento del dataset (preferibilmente in formato CSV).
- Pulizia e preparazione dei dati, se necessario (es. gestione dei valori nulli, ridenominazione colonne, trasformazioni).
- Almeno 3 analisi statistiche (es. medie, frequenze, correlazioni, ecc.) sfruttando i dataframe di Pandas.
- Almeno 3 visualizzazioni realizzate con Seaborn (es. scatter plot, boxplot, heatmap, barplot...).
- Una breve spiegazione in linguaggio naturale dei risultati ottenuti.
### Esempii di analisi
- Quali sono le categorie più frequenti?
- Com’è distribuita una variabile numerica? (media, deviazione standard, moda, mediana, ...)
- Esistono correlazioni tra due variabili? (scatterplot, heatmap, ...)
- Come cambiano i valori nel tempo? (lineplot, groupby per data)
### Dataset
- Harry Potter: https://www.kaggle.com/datasets/gulsahdemiryurek/harry-potter-dataset?select=Spells.csv
- Film e serie Netflix: https://www.kaggle.com/datasets/shivamb/netflix-shows
- Performance studenti: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data
- Libri: https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019
- Canzoni: https://www.kaggle.com/datasets/arnavvvvv/spotify-music

## Progetto da 8.25 punti: piattaforma quiz

### Descrizione generale
Progettare e realizzare un programma interattivo in Python che permetta all’utente di svolgere un quiz a scelta multipla, con valutazione finale delle risposte.
### Richieste
Il progetto deve includere:
- Leggere da un file csv  le domande, le quattro risposte e quella corretta. Devono essere almeno 25. [Libreria Pandas]
- Proporre 10 domande, una alla volta, in ordine randomico, con anche le opzioni proposte in ordine randomico. [Libreria Random]
- Consentire di selezionare un'opzione entro massimo 30 secondi. [Libreria Time]
- Arrivati al termine delle domande, stampare il punteggio ottenuto e un riassunto delle risposte date, con relativa risposta corretta.
- A ogni stampa, si presti particolare attenzione a una grafica testuale gradevole. [Librerie Rich, Prettytable, Pyfiglet e Colorama]
 
## Progetto da 8.25 punti: fanta-torneo

### Descrizione generale
Creare un'applicazione Python che simuli un gioco fanta-torneo (es. FantaCalcio, FantaSanremo, FantaSerieTv, FantaProf, ...). Il programma deve permettere di comporre la propria squadra con un certo numero di monete a disposizione e un prezzo per ogni giocatore acquistabile, l'attribuzione di punteggi sulla base di eventi, e il calcolo della classifica, salvando i risultati intermedi in dei file csv.

### Richieste
Il progetto deve includere:
- Elenco dei personaggi acquistabili: leggere da un csv l'elenco dei personaggi acquistabili nella propria formazione, insieme al loro prezzo. [Libreria pandas]
- Gestione degli acquisti: permettere l'acquisto di vari personaggi, restando in un budget prestabilito, e salvare gli acquisti in un file. [Libreria pandas]
- Registrare eventi: permettere di scegliere tra una lista di eventi positivi e negativi, con i relativi punteggi di bonus e malus, attribuendolo al personaggio di riferimento.
- Classifica: generare una classifica finale, ordinata per punteggio, anche attraverso un grafico. [Libreria Seaborn]
- A ogni stampa, si presti particolare attenzione a una grafica testuale gradevole. [Librerie Rich, Prettytable, Pyfiglet e Colorama]

## Progetto da 10 punti: Prezzi Amazon

### Descrizione generale
Creare un programma in Python che accede al prezzo di un prodotto su Amazon, lo confronta con una soglia impostata dall’utente e invia un'email o una notifica Telegram di avviso se il prezzo è sceso sotto quella soglia.

### Richieste
Il progetto deve includere:
- Indicazione dell'url, del prezzo soglia e della mail dell'utente.
- Accedere al contenuto della pagina Amazon, individuare e leggere il prezzo attuale. [Librerie Requests e Beautifulsoup4]
- Se il prezzo è inferiore alla soglia, inviare una email all’utente, altrimenti stampare un messaggio che il prezzo è ancora troppo alto. [Libreria Smtplib]
- In alternativa, si può mandare una notifica su Telegram tramite un bot. [Libreria Requests, ma richiede di avere anche un bot Telegram]
- Controllare automaticamente il prezzo ogni ora. [Libreria Time]

### Avvertenze:
Amazon può bloccare o limitare l’accesso automatico, quindi è consigliato non fare troppe richieste in poco tempo ed eseguire il programma con prudenza (es. ogni ora o più).
  
## Progetto da 10 punti: Giochino con grafica
### Descrizione generale
Realizzare un piccolo gioco a due giocatori (umano vs umano o umano vs computer) o in solitario con una interfaccia grafica semplice. 
Giochi consigliati a due giocatori: tris, forza 4, battaglia navale.
Giochi consigliati a un giocatore: memory, campo minato.

### Richieste
Il progetto deve includere:
- Interfaccia grafica, semplice ma chiara e funzionante. [Libreria Tkinter]
- Logica del gioco completa: gestione dei turni, delle regole e delle condizioni di vittoria.
- Messaggi chiari e visivi all’utente: vittoria, errore, pareggio, ecc.
- Eventuali mosse randomiche o pensate da parte del computer. [Libreria Random]
