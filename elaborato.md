## Testo Originale della Minuta di Meeting

Sono previsti servizi per studenti, docenti e tutor. Docenti e tutor definiscono la sezione dedicata alle informazioni generali del corso ( descrizione, programma, testi consigliati, info e altro ..); la sezione dedicata ai materiali didattici ( slides e dispense); la sezione dedicata alle esercitazioni, agli elaborati, alla costituzione elenco gruppi di lavoro e assegnazione tutor ed elaborati, altro...; la sezione dedicata a testi, standard, lectures suggeriti; la sezione dedicata a iniziative culturali e scientifiche. Gli studenti potranno visitare le diverse sezioni del sito, scaricare materiali didattici e nell'apposita area depositare gli elaborati di gruppo.

## Concetti utili per strutturare il testo

È richiesto di implementare un sito web per la gestione del corso di ingegneria informatica. Il sito web deve gestire l'accesso a tre tipologie di utenti; gli studenti, i docenti e i tutor. Gli account dei docenti possono essere creati solo dal gestore del sito. Un docente può creare un account tutor. I docenti e i tutor possono invitare gli studenti a partecipare tramite una mail. Gli studenti possono richiedere l'accesso al sistema dando la loro mail al docente o al tutor a lezione, o compilando un form sul sito.

Il sito è diviso in quattro sezioni:

1.   Una dedicata alle informazioni generali sul corso(descrizione, programma, testi consigliati, modalità d'esame, e altre info utili)
2.   Una dedicata alla condivisione di materiali didattici(slides e dispense)
3.   Una dedicata alle esercitazioni, agli elaborati, e alla gestione dei gruppi
4.   Una dedicata alle iniziative culturali e agli eventi.

Gli studenti possono navigare, previa autenticazione, tutte e quattro le sezioni, mentre solo i docenti e i tutor potranno apportare modifiche. Nella sezione 3 gli studenti potranno creare dei gruppi. Uno qualsiasi degli studenti può creare un nuovo gruppo invitando gli altri studenti a prendere parte al gruppo. Una volta che gli altri membri hanno confermato la loro partecipazione il gruppo viene attivato. Se il gruppo non è composto da esattamente tre membri deve essere attivato da un docente o da un tutor. Gli studenti devono scegliere un nome per il gruppo durante la fase di creazione.

Le sezioni 1 e 4 sono navigabili anche da utenti non loggati.

## Glossario

| Termini                    | Eventuali sinonimi | Definizione                              |
| -------------------------- | ------------------ | ---------------------------------------- |
| **Tipologie di utenti**    | Tipi di account    | Gli utenti che interagiscono con il sistema sono divisi in varie tipologie in base alla quali vengono abilitati diversi componenti.<br />Le tipologie sono:<br />	- Studente<br />	- Docente<br />	- Tutor |
| **Form**                   |                    | Campo per la sottomissione di dati       |
| **Sezioni**                | Aree               | Le vari componenti di cui si compone il sito.<br />Il sito è diviso nelle seguenti aree tematiche:<br />	- Informazioni sul corso<br />	- Materiali didattici<br />	- Esercitazioni<br />	- News ed eventi |
| **Gruppo**                 |                    | Insieme di studenti. I gruppi standard sono costituiti da tre membri. Vene possono prendere parte anche di più(o di meno), ma devono essere approvati. |
| **Elaborato**              |                    | Lavoro prodotto da un gruppo.            |
| **Navigare**               | Accesso            | Consultare le aree tematiche del sito.   |
| **Apportare modifiche**    |                    | Aggiungere, modificare ed rimuovere contenuti dal sito web. |
| **Utenti non loggati**     |                    | Visitatori della pagina web che non hanno effettuato nessun tipo di autenticazione. |
| **Piattaforma**            | Sito web, sistema  | Il sistema preso in esame(?).            |

## Requisiti

1.   Creazione di un account tutor

     1.  Il docente accede alla piattaforma

     2.  Il docente compila un form con i dati del tutor

     3.  Il docente conferma l'operazione

     4.  Il tutor riceve l'invito via email

     5.  Il tutor effettua il login utilizzando i dati temporanei ricevuti per email

     6.  Il tutor cambia la password

2.   Creazione di un account studente

     1.  Lo studente comunica la propria mail ad un docente o ad un tutor

     2.  Il docente o il tutor compila un form con la mail dello studente

     3.  Il docente o il tutor conferma l'operazione

     4.  Lo studente riceve un invito tramite mail

     5.  Lo studente compila il form con i suoi dati

     6.  Lo studente conferma l'operazione

3.   Modifica degli elementi di una sezione

     1.  Il docente o il tutor accede al sito

     2.  Il docente o il tutor naviga fino alla sezione da modificare

     3.  Il docente o il tutor seleziona la modalità di modifica della sezione

     4.  Il docente o il tutor può scegliere di correggere il testo presente all'interno della pagina, di aggiungerne di nuovo o di scegliere un file locale da caricare sulla piattaforma

     5.  Il docente o il tutor salva le modifiche apportate

4.   Creazione di un gruppo di studenti

     1.  Lo studente accede alla piattaforma

     2.  Lo studente naviga fino alla sezione dedicata agli elaborati e alla gestione dei gruppi

     3.  Lo studente sceglie la modalità di creazione di un gruppo

     4.  Lo studente inserisce il nome del gruppo

     5.  Lo studente inserisce gli indirizzi email degli studenti da invitare. A questi studenti verranno inviati automaticamente degli inviti a prendere parte al gruppo

     6.  Gli studenti invitati confermano di voler prendere parte al gruppo

     7.  Se il numero totale di studenti per il gruppo è 3, il gruppo è arrivato

     8.  In caso contrario, il gruppo deve essere attivato da un docente o da un tutor. Viene inviato automaticamente un messaggio ai docenti e ai tutor.

5.   Modifica di un elaborato

     1.  Lo studente, che fa parte di un gruppo già attivato, accede alla piattaforma

     2.  Lo studente naviga fino alla sezione dedicata agli elaborati e alla gestione dei gruppi

     3.  Lo studente sceglie la modalità di modifica dell'elaborato

     4.  Lo studente carica il documento dell'elaborato sul sito. La piattaforma accetta file con estensione .pdf oppure un link che rimanda ad un documento di Google Drive Il docente o il tutor possono inserire dei commenti relativi agli elaborati caricati da ogni gruppo

     5.  Gli studenti che fanno parte di un gruppo attivato ricevono un messaggio automatico ogni volte che il docente o il tutor inseriscono un commento al loro elaborato

## Attori ed obiettivi primari (macro funzionalità)

### Docente

| Codice | Obiettivo primario                 | Riferimento           |
| ------ | ---------------------------------- | --------------------- |
| MF.1   | Aggiunta di un nuovo account tutor | 1.1<br />1.2<br />1.3 |

### Tutor

| Codice | Obiettivo primario                       | Riferimento                             |
| ------ | ---------------------------------------- | --------------------------------------- |
| MF.2   | Aggiunta di un nuovo studente alla piattaforma | 2.2<br />2.3                            |
| MF.3   | Modifica di una sezione                  | 3.1<br />3.2<br />3.3<br />3.4<br />3.5 |
| MF.4   | Approvazione di un gruppo                | 4.8                                     |
| MF.5   | Commentare il lavoro di un gruppo        | 5.5                                     |

### Docente

| Codice | Obiettivo primario                       | Riferimento                             |
| ------ | ---------------------------------------- | --------------------------------------- |
| MF.2   | Aggiunta di un nuovo studente alla piattaforma | 2.2<br />2.3                            |
| MF.3   | Modifica di una sezione                  | 3.1<br />3.2<br />3.3<br />3.4<br />3.5 |
| MF.4   | Approvazione di un gruppo                | 4.8                                     |
| MF.5   | Commentare il lavoro di un gruppo        | 5.5                                     |

### Studente

| Codice | Obiettivo primario                   | Riferimento                                      |
| ------ | ------------------------------------ | ----------------------------------------         |
| MF.6   | Creazione di un account studente     | 2.1<br />2.4<br />2.5<br />2.6                   |
| MF.7   | Creazione di un gruppo               | 4.1<br />4.2<br />4.3<br />4.4<br />4.5<br />4.7 |
| MF.8   | Conferma partecipazione ad un gruppo | 4.6                                              |
| MF.9   | Modifica di un elaborato             | 5.1<br />5.2<br />5.3<br />5.4<br />             |

## Scenari

### Scenari MF.1 - Aggiunta di un nuovo account tutor 

| Scenario                                 | SC.1.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo account tutor       |
| **Utenti coinvolti**                     | Docente 1                                |
| **Assunzioni**                           | Il docente 1 è in possesso di un account abilitato |
| **Descrizione colloquio dello scenario** | - Il docente, usando il suo web browser si collega alla piattaforma.<br />- La piattaforma chiede, tramite un form, le credenziali di accesso.<br />- Il docente effettua il login.<br />- Il docente preme sul pulsante per l'aggiunta di un nuovo account tutor.<br />- Il sistema chiede al docente di compilare un form con i dati del tutor.<br />- Il docente conferma l'operazione. |
___

| Scenario                                 | SC.1.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo account tutor - dati di login non corretti |
| **Utenti coinvolti**                     | Docente 2                                |
| **Assunzioni**                           | Il docente 2 è in possesso di un account abilitato |
| **Descrizione colloquio dello scenario** | - Il docente, usando il suo web browser si collega alla piattaforma.<br />- La piattaforma chiede, tramite un form, le credenziali di accesso.<br />- Il docente effettua il login.<br />- Il sistema avvisa il docente che i dati forniti per il log in non sono validi.<br />- Il sistema reindirizza il web browser alla schermata di login. |

___

### Scenari MF.3 - Aggiunta di un nuovo studente alla piattaforma 

| Scenario                                 | SC.3.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo studente alla piattaforma - invito di un nuovo studente |
| **Utenti coinvolti**                     | Amministratore 1                         |
| **Assunzioni**                           | L'amministratore 1 è in possesso dei dati dello studente |
| **Descrizione colloquio dello scenario** | - L'amministratore, usando il suo web browser si collega alla piattaforma.<br />- La piattaforma chiede, tramite un form, le credenziali di accesso.<br />- L'amministratore effettua il login.<br />- L'amministratore preme sul pulsante per l'aggiunta di un nuovo studente.<br />- Il sistema chiede, tramite un form, di inserire i dati dello studente.<br />- L'amministratore compila il form e completa l'operazione.<br />- Il sistema informa l'amministratore del buon esito dell'operazione. |
___

| Scenario                                 | SC.3.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo studente alla piattaforma - invito di un nuovo studente, lo studente già esiste |
| **Utenti coinvolti**                     | Amministratore 2                         |
| **Assunzioni**                           | L'amministratore 2 è in possesso dei dati dello studente |
| **Descrizione colloquio dello scenario** | - L'amministratore, usando il suo web browser si collega alla piattaforma.<br />- La piattaforma chiede, tramite un form, le credenziali di accesso.<br />- L'amministratore effettua il login.<br />- L'amministratore preme sul pulsante per l'aggiunta di un nuovo studente.<br />- Il sistema chiede, tramite un form, di inserire i dati dello studente.<br />- L'amministratore compila il form e completa l'operazione.<br />- Il sistema informa l'amministratore che i dati inseriti corrispondono ad un utente già presente nel sistema |

| Scenario                                 | SC.3.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo studente alla piattaforma - Lo studente non viene accettato**Utenti coinvolti** |
|                                          | Amministratore 3                         |
| **Assunzioni**                           |                                          |
| **Descrizione colloquio dello scenario** | - Il sistema notivica all'amministratore che un nuovo utente ha richiesto di accedere alla piattaforma in qualità di studente.<br />- L'amministratore analizza la richiesta.<br />- L'amministratore rifiuta la richiesta e compila una nota spiegando le motivazioni della sua scelta.<br />- L'amministratore clicca sul pulsante di conferma.<br />- Il sistema comunica il buon esito dell'operazione.<br />- Il sistema inoltra la nota all'email dell'utente richiedente. |
### Scenari MF.4 - Modifica di una sezione  

| Scenario                                 | SC.4.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di una sezione                  |
| **Utenti coinvolti**                     | Amministratore 1                         |
| **Assunzioni**                           | L'amministratore 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - L'amministratore sceglie la sezione da modificare.<br />- L'amministratore preme sul pulsante per la modifica.<br />- il sistema reinderizza l'amministratore in un editor per la modifica.<br />- L'amministratore apporta le modifiche.<br />- L'amministratore salva le modifiche.<br />- Il sistema comunica il successo dell'operazione. |
___


| Scenario                                 | SC.4.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di una sezione - Impossibilità ad effettuare la modifica |
| **Utenti coinvolti**                     | Amministratore 3                         |
| **Assunzioni**                           | L'amministratore 3 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - L'amministratore sceglie la sezione da modificare.<br />- L'amministratore preme sul pulsante per la modifica.<br />- Il sistema avvisa l'amministratore che un altro amministratore già sta apportando modifiche alla sezione.<br />- il sistema chiede all'amministratore di riprovare più tardi. |
### Scenari MF.5 - Approvazione di un gruppo 

| Scenario                                 | SC.5.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di un gruppo                |
| **Utenti coinvolti**                     | Amministratore 1                         |
| **Assunzioni**                           | L'amministratore 1 ha già effettuato il login, all'amministratore è stata notificata la richiesta di approvazione |
| **Descrizione colloquio dello scenario** | - L'amministratore clicca sulla notifica.<br />- Il sistema apre una finestra che contiene l'elenco dei menbri ed eventuali note degli studenti.<br />- L'amministratore clicca sul pulsante per l'approvazione.<br />- Il sistema gli comunica il buon esito dell'operazione.<br />- Il sistema notifica agli studenti che il gruppo è stato approvato. |
___



| Scenario                                 | SC.5.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di un gruppo - Il gruppo non viene approvato |
| **Utenti coinvolti**                     | Amministratore 2                         |
| **Assunzioni**                           | L'amministratore 2 ha già effettuato il login, all'amministratore è stata notificata la richiesta di approvazione |
| **Descrizione colloquio dello scenario** | - L'amministratore clicca sulla notifica.<br />- Il sistema apre una finestra che contiene l'elenco dei menbri ed eventuali note degli studenti.<br />- L'amministratore clicca sul pulsante per non approvare il gruppo.<br />- Il sistema mostra un'area di testo.<br />- L'amministratore scrive nell'area di testo le motivazioni della sua decisione e conferma l'operazione.<br />- Il sistema gli comunica il buon esito dell'operazione.<br />- Il sistema notifica agli studenti che il gruppo non è stato approvato. |
___

### Scenari MF.6 - Commentare il lavoro di un gruppo

| Scenario                                 | SC.6.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Commentare il lavoro di un gruppo        |
| **Utenti coinvolti**                     | Amministratore 1                         |
| **Assunzioni**                           | L'amministratore 1 ha già effettuato il login, all'amministratore è stata notificata la richiesta di revisione di un elaborato o parte di esso |
| **Descrizione colloquio dello scenario** | - L'amministratore clicca sulla notifica.<br />- Il sistema apre un editor per la visualizzazione e la modifica di un elaborato ed eventuali note degli studenti membri del gruppo.<br />- L'amministratore effettua le eventuali modifiche.<br />- L'amministratore inserisci gli eventuali commenti all'elaborato.<br />- L'amministratore clicca sul pulsante per salvare le modifiche.<br />- Il sistema gli comunica il buon esito dell'operazione.<br />- Il sistema notifica agli studenti che l'amministratore ha revisionato il loro elaborato. |
___

### Scanari MF.7 - Creazione di un account studente

| Scenario                                 | SC.7.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un account studente         |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           |                                          |
| **Descrizione colloquio dello scenario** | - Lo studente tramite il suo web browser si collega alla pagina per richiedere l'acesso.<br />- Lo studente compila il form inserendo la sua email e preme il pulsante per la conferma.<br />- Il sistema comunica il buon esito dell'operazione.<br />- Lo studente riceve l'invito via email.<br />- Lo studente tramite il link ricevuto via email si collega alla pagina di registrazione.<br />- Lo studente compila un form con tutti i suoi dati e preme il pulsante di conferma.<br />- Il sistema gli comunica il buon esito dell'operazione e lo reindirizza alla home page del sito. |
___

| Scenario                                 | SC.7.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un account studente - la richiesta è stata rifutata |
| **Utenti coinvolti**                     | Studente 3                               |
| **Assunzioni**                           | Lo studente 3 ha già comunicato la sua email ad un amministratore |
| **Descrizione colloquio dello scenario** | - Lo studente riceve via email le ragioni del rifiuto<br />- Lo studente invia una mail di risposta all'amministratore. |
___

### Scenari MF.8 - Creazione di un nuovo gruppo

| Scenario                                 | SC.8.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo             |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente clicca sul pulsante per la creazione di un nuovo gruppo .<br />- Il sistema apre una finestra per l'inserimento del nome del gruppo e la selezione del numero di membri da invitare.<br />- Lo studente inserisce il nome del gruppo e seleziona tre come numero di membri da invitare.<br />- Il sistema verifica la disponibilità del nome del gruppo.<br />- Il sistema notifica la disponibilità del nome.<br />- Il sistema apre una finestra per l'inserimento delle credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi dei membri e clicca sul pulsante di conferma.<br />- Il sistema conferma il buon esito dell'operazione e invia una notifica agli studenti invitati.<br />- Il sistema notifica che il gruppo è attivo |

___

| Scenario                                 | SC.8.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - numero di membri diversi da tre |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente clicca sul pulsante per la creazione di un nuovo gruppo .<br />- Il sistema apre una finestra per l'inserimento del nome del gruppo e la selezione del numero di membri da invitare.<br />- Lo studente inserisce il nome del gruppo e seleziona il numero di membri da invitare.<br />- Il sistema verifica la disponibilità del nome del gruppo.<br />- Il sistema notifica la disponibilità del nome.<br />- Il sistema apre una finestra per l'inserimento delle credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi dei membri e clicca sul pulsante di conferma.<br />- Il sistema conferma il buon esito dell'operazione e invia una notifica agli studenti invitati.<br />- Il sistema invia una notifica all'amministratore per l'approvazione del gruppo<br />- Il sistema notifica che il gruppo non è statro approvato e mostra le motivazioni della scelta. |
___

| Scenario                                 | SC.8.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - numero di membri diversi da tre |
| **Utenti coinvolti**                     | Studente 3                               |
| **Assunzioni**                           | Lo studente 3 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente clicca sul pulsante per la creazione di un nuovo gruppo .<br />- Il sistema apre una finestra per l'inserimento del nome del gruppo e la selezione del numero di membri da invitare.<br />- Lo studente inserisce il nome del gruppo e seleziona il numero di membri da invitare.<br />- Il sistema verifica la disponibilità del nome del gruppo.<br />- Il sistema notifica la disponibilità del nome.<br />- Il sistema apre una finestra per l'inserimento delle credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi dei membri e clicca sul pulsante di conferma.<br />- Il sistema notifica che uno studente non è inscritto alla piattaforma.<br />- Lo studente annulla l'operazione. |

### Scenari MF.9 -  Conferma partecipazione ad un gruppo 

| Scenario                                 | SC.9.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Conferma partecipazione ad un gruppo     |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente riceve la notifica di partecipazione ad un gruppo.<br />- Lo studente clicca sulla notifica.<br />- Il sistema apre una pagina con il nome del gruppo e la lista dei partecipati.<br />- Lo studente clicca sul pulsante di conferma per la partecipazione.<br />- Il sistema conferma il buon esito dell'operazione. |
___

| Scenario                                 | SC.9.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Conferma partecipazione ad un gruppo - rifiuto dello studente |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente riceve la notifica di partecipazione ad un gruppo.<br />- Lo studente clicca sulla notifica.<br />- Il sistema apre una pagina con il nome del gruppo e la lista dei partecipati.<br />- Lo studente clicca sul pulsante per rifiutare la partecipazione.<br />- Il sistema conferma il buon esito dell'operazione. |
___

### Scenari MF.10 - Modifica di un elaborato

| Scenario                                 | SC.10.1                                  |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di un elaborato                 |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente si reca nella sezione dedicata agli elaborati.<br />- Lo studente clicca sul pulsante per aggiungere un nuovo documento.<br />- Il sistema chiede con quale sistema aggiungere il documento.<br />- Lo studente sceglie l'upload diretto e seleziona il file da caricare.<br />- Il sistema conferma il buon esito dell'operazione. |

___

| Scenario                                 | SC.10.2                                  |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di un elaborato                 |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente si reca nella sezione dedicata agli elaborati.<br />- Lo studente clicca sul pulsante per aggiungere un nuovo documento.<br />- Il sistema chiede con quale sistema aggiungere il documento.<br />- Lo studente sceglie di inserire un link ad un documento su Google Drive.<br />- Il sistema conferma il buon esito dell'operazione. |

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
