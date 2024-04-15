Vogliamo sviluppare una dashboard di gestione dei dati del personale dei corsi di una Academy tech.
Ipotizzando una metodologia di sviluppo Agile, in questo sprint vogliamo:
Scrivere 3 casi d’uso che rappresentino dei requisiti funzionali di questa applicazione
Disegnare il Domani Model (diagramma delle classi) dell’applicazione (almeno per quanto riguarda i casi d’uso definiti)
===
## UC1: Gestione del corso

- Attori: Amministratore
- Descrizione: l'amministratore può creare, modificare e/o eliminare uno o più corsi.
- Scenario di utilizzo:
    1. L'amministratore accede all'area di gestione dei corsi.
    2. L'amministratore crea un nuovo corso, specificando nome del corso, materie di studio, docenti, durata del corso.
    3. L'amministratore modifica le informazioni di un corso esistente.
    4. L'amministratore elimina un corso.


## UC2: Gestione delle lezioni

- Attori: Docenti
- Descrizione: Il docente può aggiungere, modificare e/o eliminare una o più lezioni.
- Scenario di utilizzo:
    1. Il docente accede all'area di gestione delle lezioni.
    2. Il docente visualizza l'elenco delle lezioni pianificate per la sua materia.
    3. Il docente aggiunge una nuova lezione, specificando argomento, data e ora della lezione, aula dove verrà svolta la lezione.
    4. Il docente modifica i dettagli di una lezione esistente.
    5. Il docente elimina una lezione del corso.


## UC3: Gestione esami
- Attori: Docenti
- Descrizione: Il docente può aggiungere/modificare uno o più esami.
- Condizione: Il docente deve essere associato al corso dove vuole aggiungere/modificare un esame.
- Scenario di utilizzo:
    1. Il docente accede all'area di gestione degli esami.
    2. Il docente visualizza gli esami disponibili per ogni corso.
    3. Il docente accede al corso dove vuole aggiungere/modificare un esame.
    4. Il docente aggiunge un esame al corso, associando la materia, specificando modalità, data e ora dell'esame, aula dove verrà svolto l'esame.
    5. Il docente modifica i dettagli di un esame esistente.