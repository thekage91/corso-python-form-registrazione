## Esercizio Pratico: Creazione di una Form di Registrazione

**Obiettivo**: Implementare una form di registrazione che raccoglie username, email e password, con validazione dei dati e protezione CSRF.

**Passaggi**:
1. Definire una classe `RegistrationForm` con campi per username, email e password. Utilizzare i validatori per assicurare che tutti i campi siano compilati e che l'email sia nel formato corretto.
2. Creare un template HTML per la form che visualizza i campi e eventuali messaggi di errore di validazione.
3. Implementare una route in Flask che gestisce la visualizzazione della form e il processo di submission.
4. Aggiungere la protezione CSRF alla form utilizzando Flask-WTF.
