## Testo Originale della Minuta di Meeting

Sono previsti servizi per studenti, docenti e tutor. Docenti e tutor definiscono la sezione dedicata alle informazioni generali del corso ( descrizione, programma, testi consigliati, info e altro ..); la sezione dedicata ai materiali didattici ( slides e dispense); la sezione dedicata alle esercitazioni, agli elaborati, alla costituzione elenco gruppi di lavoro e assegnazione tutor ed elaborati, altro...; la sezione dedicata a testi, standard, lectures suggeriti; la sezione dedicata a iniziative culturali e scientifiche. Gli studenti potranno visitare le diverse sezioni del sito, scaricare materiali didattici e nell'apposita area depositare gli elaborati di gruppo.

## Concetti utili per strutturare il testo

È richiesto di implementare un sito web per la gestione del corso di ingegneria informatica. Il sito web deve gestire l'accesso a tre tipologie di utenti; gli studenti, i docenti e i tutor. Gli account dei docenti possono essere creati solo dal gestore del sito. Un docente può creare un account tutor. I docenti e i tutor possono abilitare gli account studenti. Gli studenti possono registrarsi alla piattaforma compilando un form con i propri dati; l'account prima di essere funzionante deve essere abilitato da un docente o da un tutor.

Il sito è diviso in quattro sezioni:

1.   Una dedicata alle informazioni generali sul corso(descrizione, programma, testi consigliati, modalità d'esame, e altre info utili)
2.   Una dedicata alla condivisione di materiali didattici(slides e dispense)
3.   Una dedicata alle esercitazioni, agli elaborati, e alla gestione dei gruppi
4.   Una dedicata alle iniziative culturali e agli eventi.

Gli studenti possono navigare, previa autenticazione, tutte e quattro le sezioni, mentre solo i docenti e i tutor potranno apportare modifiche. Nella sezione 3 gli studenti potranno creare dei gruppi. Uno qualsiasi degli studenti può creare un nuovo gruppo invitando gli altri studenti a prendere parte al gruppo. Una volta che gli altri membri hanno confermato la loro partecipazione il gruppo viene attivato. Se il gruppo non è composto da esattamente tre membri deve essere attivato da un docente o da un tutor. Gli studenti devono scegliere un nome per il gruppo durante la fase di creazione.

Le sezioni 1 e 4 sono navigabili anche da utenti non loggati.

## Glossario

| Termini                   | Eventuali sinonimi | Definizione                              |
| ------------------------- | ------------------ | ---------------------------------------- |
| **Tipologie di utenti**   | Tipi di account    | Gli utenti che interagiscono con il sistema sono divisi in varie tipologie in base alla quali vengono abilitati diversi componenti.<br />Le tipologie sono:<br />	- Studente<br />	- Docente<br />	- Tutor |
| **Sezioni**               | Aree               | Le vari componenti di cui si compone il sito.<br />Il sito è diviso nelle seguenti aree tematiche:<br />	- Informazioni sul corso<br />	- Materiali didattici<br />	- Esercitazioni<br />	- News ed eventi |
| **Gruppo**                |                    | Insieme di studenti. I gruppi standard sono costituiti da tre membri. Ve ne possono prendere parte anche di più(o di meno), ma devono essere approvati. |
| **Elaborato**             |                    | Lavoro prodotto da un gruppo.            |
| **Navigare**              | Accesso            | Consultare le aree tematiche del sito.   |
| **Apportare modifiche**   |                    | Aggiungere, modificare e rimuovere contenuti dal sito web. |
| **Utenti non loggati**    |                    | Visitatori della pagina web che non hanno effettuato nessun tipo di autenticazione. |
| **Piattaforma**           | Sito web, sistema  | Il sistema preso in esame(?).            |
| **Account non abilitato** |                    | Un account a cui è concesso accedere al sistema, ma non alle aree riservate. |

## Requisiti

1.   Creazione di un account tutor

     1.  Il docente accede alla piattaforma

     2.  Il docente compila un form con i dati del tutor

     3.  Il docente conferma l'operazione

2.   Registrazione di uno studente

     1.  Lo studente si collega alla pagina per il log up

     2.  Lo studente inserisce i propri dati nel sistema

     3.  Lo studente conferma l'operazione

     4.  Il docente o il tutor approva o meno l'account dello studente

3.   Modifica degli elementi di una sezione

     1.  Il docente o il tutor accede al sito

     2.  Il docente o il tutor naviga fino alla sezione da modificare

     3.  Il docente o il tutor seleziona la modalità di modifica della sezione

     4.  Il docente o il tutor può scegliere di correggere il testo presente all'interno della pagina, di aggiungere di nuovo o di scegliere un file locale da caricare sulla piattaforma

     5.  Il docente o il tutor salva le modifiche apportate

4.   Creazione di un gruppo di studenti

     1.  Lo studente accede alla piattaforma

     2.  Lo studente naviga fino alla sezione dedicata agli elaborati e alla gestione dei gruppi

     3.  Lo studente sceglie la modalità di creazione di un gruppo

     4.  Lo studente inserisce il nome del gruppo

     5.  Lo studente inserisce gli indirizzi email degli studenti da invitare. A questi studenti verranno inviati automaticamente degli inviti a prendere parte al gruppo

     6.  Gli studenti invitati confermano di voler prendere parte al gruppo

     7.  Se il numero totale di studenti per il gruppo è 3, il gruppo è attivato

     8.  In caso contrario, il gruppo deve essere attivato da un docente o da un tutor. Viene inviato automaticamente un messaggio ai docenti e ai tutor.

5.   Modifica di un elaborato

     1.  Lo studente, che fa parte di un gruppo già attivato, accede alla piattaforma

     2.  Lo studente naviga fino alla sezione dedicata agli elaborati e alla gestione dei gruppi

     3.  Lo studente sceglie la modalità di modifica dell'elaborato

     4.  Lo studente può aggiungere e/o modificare i documenti. La piattaforma accetta l'upload diretto dei file oppure un link esterno che rimanda ad un documento di Google Drive o ad un altro servizio di cloud storage. Il docente e i tutor possono inserire dei commenti relativi agli elaborati caricati da ogni gruppo

     5.  Gli studenti che fanno parte di un gruppo attivato ricevono un messaggio automatico ogni volte che il docente o il tutor inseriscono un commento al loro elaborato

## Attori ed obiettivi primari (macro funzionalità)

### Docente

| Codice | Obiettivo primario                 | Riferimento                             |
| ------ | ---------------------------------- | --------------------------------------- |
| MF.1   | Aggiunta di un nuovo account tutor | 1.1<br />1.2<br />1.3                   |
| MF.2   | Approvazione di uno studente       | 2.4                                     |
| MF.3   | Modifica di una sezione            | 3.1<br />3.2<br />3.3<br />3.4<br />3.5 |
| MF.4   | Approvazione di un gruppo          | 4.8                                     |
| MF.5   | Commentare il lavoro di un gruppo  | 5.5                                     |

### Tutor

| Codice | Obiettivo primario                | Riferimento                             |
| ------ | --------------------------------- | --------------------------------------- |
| MF.2   | Approvazione di uno studente      | 2.4                                     |
| MF.3   | Modifica di una sezione           | 3.1<br />3.2<br />3.3<br />3.4<br />3.5 |
| MF.4   | Approvazione di un gruppo         | 4.8                                     |
| MF.5   | Commentare il lavoro di un gruppo | 5.5                                     |

### Studente

| Codice | Obiettivo primario                   | Riferimento                             |
| ------ | ------------------------------------ | --------------------------------------- |
| MF.6   | Registrazione di uno studente        | 2.1<br />2.2<br />2.3                   |
| MF.7   | Creazione di un gruppo               | 4.1<br />4.2<br />4.3<br />4.4<br />4.5 |
| MF.8   | Conferma partecipazione ad un gruppo | 4.6                                     |
| MF.9   | Creazione di un nuovo elaborato      | 5.1<br />5.2<br />5.3<br />5.4<br />    |
| MF.10  | Modifica di un elaborato             | 5.1<br />5.2<br />5.3<br />5.4<br />    |

## Scenari

### Scenari MF.1 - Aggiunta di un nuovo account tutor 

| Scenario                                 | SC.1.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo account tutor       |
| **Utenti coinvolti**                     | Docente 1                                |
| **Assunzioni**                           | Il docente 1 è in possesso di un account abilitato |
| **Descrizione colloquio dello scenario** | - La piattaforma chiede le credenziali di accesso.<br />- Il docente comunica al sistema il suo username e la password.<br />- Il sistema autorizza il docente<br />- Il docente chiede al sistema di aggiungere un nuovo account tutor.<br />- Il sistema chiede al docente i dati del tutor.<br />- Il docente comunica i dati del tutor<br />- Il docente conferma l'operazione. <br/>- Il sistema comunica il buon esito del sistema |
___

| Scenario                                 | SC.1.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo account tutor - dati di login non corretti |
| **Utenti coinvolti**                     | Docente 2                                |
| **Assunzioni**                           | Il docente 2 è in possesso di un account abilitato |
| **Descrizione colloquio dello scenario** | - La piattaforma chiede le credenziali di accesso.<br />- Il docente comunica al sistema il suo username e la password.<br />- Il sistema avvisa il docente che i dati forniti non sono validi. |

___

| Scenario                                 | SC.1.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Aggiunta di un nuovo account tutor - il tutor già esiste |
| **Utenti coinvolti**                     | Docente 3                                |
| **Assunzioni**                           | Il docente 3 è in possesso di un account abilitato |
| **Descrizione colloquio dello scenario** | - La piattaforma chiede le credenziali di accesso.<br />- Il docente comunica al sistema il suo username e la password.<br />-Il sistema autorizza il docente<br />- Il docente chiede al sistema di aggiungere un nuovo account tutor.<br />- Il sistema chiede al docente i dati del tutor.<br />- Il docente conferma l'operazione. <br/>- Il sistema comunica al docente che il tutor già esiste. |

### Scenari MF.2 - Approvazione di uno studente 

| Scenario                                 | SC.2.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di uno studente             |
| **Utenti coinvolti**                     | Docente 1 o Tutor 1                      |
| **Assunzioni**                           | Il docente 1 o il tutor 1 ha già effettuato l'accesso |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor chiede la lista delle approvazioni pendenti.<br />- Il sistema risponde con la lista di tutti gli account studenti in attesa di approvazione.<br />- Il docente o il tutor comunica l'approvazione a cui è interessato <br/>- Il sistema chiede se si vuole approvare o meno l'account.<br />- Il docente o il tutor decide di approvare la richiesta.<br />- Il sistema comunica il buon esito dell'operazione. |

---

| Scenario                                 | SC.2.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di uno studente - la richiesta viene rifiutata |
| **Utenti coinvolti**                     | Docente 2 o Tutor 2                      |
| **Assunzioni**                           | Il docente 2 o il tutor 2 ha già effettuato l'accesso |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor chiede la lista delle approvazioni pendenti.<br />- Il sistema risponde con la lista di tutti gli account studenti in attesa di approvazione.<br />- Il docente o il tutor comunica l'approvazione a cui è interessato <br/>- Il sistema chiede se si vuole approvare o meno l'account.<br />- Il docente o il tutor decide di rifiutare la richiesta.<br />- Il sistema chiede se si vuole inserire una nota con le motivazioni.<br />- Il docente o il tutor comunica al sistema di voler inserire la nota e immette nel sistema le motivazioni.<br />- Il sistema comunica il buon esito dell'operazione. |

---

| Scenario                                 | SC.2.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di uno studente - non ci sono richieste pendenti |
| **Utenti coinvolti**                     | Docente 3 o Tutor 3                      |
| **Assunzioni**                           | Il docente 3 o il tutor 3 ha già effettuato l'accesso |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor chiede la lista delle approvazioni pendenti.<br />- Il sistema risponde che non c'è alcuna richiesta pendente. |

### Scenari MF.3 - Modifica di una sezione  

| Scenario                                 | SC.3.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di una sezione                  |
| **Utenti coinvolti**                     | Docente 1 o Tutor 1                      |
| **Assunzioni**                           | Il docente 1 o il tutor 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor sceglie la sezione da modificare.<br />- Il sistema mostra la sezione scelta.<br />- Il docente o il tutor chiede al sistema di modificare la sezione.<br />-Il sistema entra nella modalità di modifica.<br />- Il docente o il tutor modifica il testo.<br />- Il sistema salva le modifiche e comunica il buon esito dell'operazione. |
___

| Scenario                                 | SC.3.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di una sezione - Impossibilità ad effettuare la modifica |
| **Utenti coinvolti**                     | Docente 2 o Tutor 2                      |
| **Assunzioni**                           | Il docente 2 o il tutor 2ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor sceglie la sezione da modificare.<br />- Il sistema mostra la sezione scelta.<br />- Il docente o il tutor chiede di modificare la sezione.<br />- Il sistema comunica l'impossibilità di entrare nella modalità di modifica, poichè un altro docente o un tutor stanno apportando delle modifiche. |
### Scenari MF.4 - Approvazione di un gruppo 

| Scenario                                 | SC.4.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di un gruppo                |
| **Utenti coinvolti**                     | Docente 1 o Tutor 1                      |
| **Assunzioni**                           | Il docente 1 o o il tutor 1 ha già effettuato il login; il docente o il tutor ha alcune richieste di approvazione pendenti |
| **Descrizione colloquio dello scenario** | -Il docente o il tutor chiede al sistema di mostrare le richieste di approvazione dei gruppi pendenti.<br />- Il sistema mostra tutte le richieste pendenti.<br />- Il docente o il tutor seleziona la richiesta a cui è interessato.<br />- Il sistema mostra il nome del gruppo, il numero di membri e le loro credenziali.<br />- Il docente o il tutor sceglie di approvare il gruppo.<br />- Il sistema comunica il buon esito dell'operazione e comunica la decisione del docente o del tutor agli studenti interessati. |
___

| Scenario                                 | SC.4.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di un gruppo - Il gruppo non viene approvato |
| **Utenti coinvolti**                     | Docente 2 o Tutor 2                      |
| **Assunzioni**                           | Il docente 2 o il tutor 2 ha già effettuato il login; il docente o il tutor ha alcune richieste di approvazioni pendenti |
| **Descrizione colloquio dello scenario** | -Il docente o il tutor chiede al sistema di mostrare le richieste di approvazione dei gruppi pendenti.<br />- Il sistema mostra tutte le richieste pendenti.<br />- Il docente o il tutor seleziona la richiesta a cui è interessato.<br />- Il sistema mostra il nome del gruppo, il numero di membri e le loro credenziali.<br />- Il docente o il tutor sceglie di non approvare il gruppo e aggiunge le eventuali motivazioni.<br />- Il sistema comunica il buon esito dell'operazione e comunica la decisione del docente o del tutor agli studenti interessati. |
___

| Scenario                                 | SC.4.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Approvazione di un gruppo - Non ci sono approvazioni pendenti |
| **Utenti coinvolti**                     | Docente 3 o Tutor 3                      |
| **Assunzioni**                           | Il docente 3 o il tutor 3 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | -Il docente o il tutor chiede al sistema di mostrare le richieste di approvazione dei gruppi pendenti.<br />- Il sistema comunica che non ci sono approvazioni di gruppi pendendi |
___

### Scenari MF.5 - Commentare il lavoro di un gruppo

| Scenario                                 | SC.5.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Commentare il lavoro di un gruppo        |
| **Utenti coinvolti**                     | Docente 1 o Tutor 1                      |
| **Assunzioni**                           | Il docente 1 o il tutor 1 ha già effettuato il login; il docente o il tutor ha alcune richieste di revisione degli elaborati pendenti |
| **Descrizione colloquio dello scenario** | - Il docente o il tutor chiede al sistema di mostrare le richieste di revisioni pendenti.<br />- Il sistema mostra le richieste pendenti.<br />- Il docente o il tutor seleziona la richiesta che gli interessa.<br />- Il sistema mostra il nome del gruppo e le credenziali dei membri ed entra nella modalità di modifica dell'elaborato.<br />- Il docente o il tutor modifica il testo ed aggiunge eventuali commenti.<br />- Il sistema salva le modifiche e comunica agli studenti interessati che il docente o il tutor ha revisionato il loro elaborato. |
___

### Scenari MF.6 - Registrazione di un account studente

| Scenario                                 | SC.6.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Registrazione di un account studente     |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           |                                          |
| **Descrizione colloquio dello scenario** | - Lo studente chiede di potersi registrare.<br />- Il sistema chiede le informazioni necessarie alla autenticazione.<br />- Lo studente inserisce i proprio dati.<br />- Il sistema invia una richiesta di approvazione a tutti i docenti o tutor e comunica il buon esito dell'operazione. |
___

| Scenario                                 | SC.6.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Registrazione di un account studente - lo studente già esiste nel sistema |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           |                                          |
| **Descrizione colloquio dello scenario** | - Lo studente chiede di potersi registrare.<br />- Il sistema chiede le informazioni necessarie alla autenticazione.<br />- Lo studente inserisce i proprio dati.<br />- Il sistema comunica che quella email è già associata ad un accont. |

### Scenari MF.7 - Creazione di un nuovo gruppo

| Scenario                                 | SC.7.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo             |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema chiede allo studente di inserire il nome del gruppo e il numero di membri.<br />- Lo studente inserisce i dati, con tre come numero di membri.<br />- Il sistema verifica la disponibilità del nome e chiede le credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi degli studenti da invitare.<br />- Il sistema verifica che tutti gli studenti inseriti siano già iscritti alla piattaforma e non facciano parte di un altro gruppo e chiede conferma.<br />- Lo studente conferma i nomi degli altri membri.<br />- Il sistema invia una comunicazione a tutti gli studenti indicati e comunica il buon esito dell'operazione. |
___

| Scenario                                 | SC.7.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - numero di membri diversi da tre |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema chiede allo studente di inserire il nome del gruppo e il numero di membri.<br />- Lo studente inserisce i dati, con un numero di membri diverso da tre.<br />- Il sistema comunica che i gruppi con numero di membri diverso da tre non sono di approvazione automatica, ma dovranno essere revisionati da un docente o un tutor.<br />- Lo studente conferma il numero di membri.<br />- Il sistema verifica la disponibilità del nome e chiede le credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi degli studenti da invitare.<br />- Il sistema verifica che tutti gli studenti inseriti siano già iscritti alla piattaforma e non facciano parte di un altro gruppo e chiede conferma.<br />- Lo studente conferma i nomi degli altri membri.<br />- Il sistema invia una comunicazione a tutti gli studenti indicati e a tutti i docenti ed i tutor; comunica il buon esito dell'operazione. |
___

| Scenario                                 | SC.7.3                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - uno o più studenti invitati non sono iscritti alla piattaforma |
| **Utenti coinvolti**                     | Studente 3                               |
| **Assunzioni**                           | Lo studente 3 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema chiede allo studente di inserire il nome del gruppo e il numero di membri.<br />- Lo studente inserisce i dati.<br />- Il sistema verifica la disponibilità del nome e chiede le credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi degli studenti da invitare.<br />- Il sistema verifica che tutti gli studenti inseriti siano già iscritti alla piattaforma e comunica che uno o più studenti non sono iscritti.<br /> |

| Scenario                                 | SC.7.4                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - nome non disponibile |
| **Utenti coinvolti**                     | Studente 4                               |
| **Assunzioni**                           | Lo studente 4 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema chiede allo studente di inserire il nome del gruppo e il numero di membri.<br />- Lo studente inserisce i dati.<br />- Il sistema verifica la disponibilità del nome e comunica che il nome non è disponibile. |
___

| Scenario                                 | SC.7.5                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - uno o più studenti invitati fanno già parte di un altro gruppo |
| **Utenti coinvolti**                     | Studente 5                               |
| **Assunzioni**                           | Lo studente 5 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema chiede allo studente di inserire il nome del gruppo e il numero di membri.<br />- Lo studente inserisce i dati.<br />- Il sistema verifica la disponibilità del nome e chiede le credenziali degli studenti da invitare.<br />- Lo studente inserisce i nomi degli studenti da invitare.<br />- Il sistema verifica che tutti gli studenti inseriti siano già iscritti alla piattaforma e non facciano parte di un altro gruppo e comunica che uno o più studenti fanno già parte di un gruppo. |
___

| Scenario                                 | SC.7.6                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo gruppo - lo studente fa già parte di un gruppo |
| **Utenti coinvolti**                     | Studente 6                               |
| **Assunzioni**                           | Lo studente 6 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di poter creare un nuovo gruppo.<br />- Il sistema informa che già fa parte di un gruppo e che non può essere membro di due gruppi. |

### Scenari MF.8 -  Conferma partecipazione ad un gruppo 

| Scenario                                 | SC.8.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Conferma partecipazione ad un gruppo     |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login, lo studente ha almeno un invito a prendere parte in un gruppo |
| **Descrizione colloquio dello scenario** | - Lo studente chiede di visualizzare la lista degli inviti a prendere parte in un gruppo.<br />- Il sistema mostra tutti gli inviti.<br />- Lo studente seleziona l'invito che gli interessa.<br />- Il sistema mostra il nome del gruppo selezionato e le credenziali dei suoi membri.<br />- Lo studente accetta l'invito.<br />- Il sistema comunica il buon esito dell'operazione. |
___

| Scenario                                 | SC.8.2                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Conferma partecipazione ad un gruppo - rifiuto dello studente |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login, lo studente ha almeno un invito a prendere parte in un gruppo |
| **Descrizione colloquio dello scenario** | - Lo studente chiede di visualizzare la lista degli inviti a prendere parte in un gruppo.<br />- Il sistema mostra tutti gli inviti.<br />- Lo studente seleziona l'invito che gli interessa.<br />- Il sistema mostra il nome del gruppo selezionato e le credenziali dei suoi membri.<br />- Lo studente rifiuta l'invito, allegando eventuali motivazioni.<br />- Il sistema comunica il buon esito dell'operazione. |

### Scenari MF.9 - Creazione di un nuovo elaborato

| Scenario                                 | SC.9.1                                   |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Creazione di un nuovo elaborato          |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di creare un nuovo elaborato.<br />- Il sistema mostra la lista delle tracce disponibili.<br />- Lo studente sceglie la traccia a cui è interessato.<br />- Il sistema conferma il buon esito dell'operazione. |

___
### Scenari MF.10 - Modifica di un elaborato

| Scenario                                 | SC.10.1                                  |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di un elaborato - upload diretto |
| **Utenti coinvolti**                     | Studente 1                               |
| **Assunzioni**                           | Lo studente 1 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di mostrare la lista degli elaborati del gruppo di cui fa parte.<br />- Il sistema mostra la lista degli elaborati.<br />- Lo studente chiede al sistema di inserire un nuovo documento.<br />- Il sistema chiede la modalità di caricamento del documento.<br />- Lo studente sceglie l'upload diretto e seleziona il file .pdf da caricare.<br />- Il sistema conferma il buon esito dell'operazione. |

___

| Scenario                                 | SC.10.2                                  |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di un elaborato - inserimento link esterno |
| **Utenti coinvolti**                     | Studente 2                               |
| **Assunzioni**                           | Lo studente 2 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di mostrare la lista degli elaborati del gruppo di cui fa parte.<br />- Il sistema mostra la lista degli elaborati.<br />- Lo studente chiede al sistema di inserire un nuovo documento.<br />- Il sistema chiede la modalità di caricamento del documento.<br />- Lo studente sceglie di caricare un link ad un documento di Google Drive ed inserisce il link.<br />- Il sistema conferma il buon esito dell'operazione. |
___

| Scenario                                 | SC.10.3                                  |
| ---------------------------------------- | ---------------------------------------- |
| **Scopo**                                | Modifica di un elaborato - nessun elaborato prodotto |
| **Utenti coinvolti**                     | Studente 3                               |
| **Assunzioni**                           | Lo studente 3 ha già effettuato il login |
| **Descrizione colloquio dello scenario** | - Lo studente chiede al sistema di mostrare la lista degli elaborati del gruppo di cui fa parte.<br />- Il sistema avvisa che il gruppo di cui fa parte ancora non ha prodotto alcun elaborato. |

## Use cases

### UC.1 - Aggiunta di un nuovo account tutor 

| Nome del caso d'uso  | Aggiunta di un nuovo account tutor       |
| -------------------- | ---------------------------------------- |
| **Descrizione**      | Descrive il processo che il docente deve compiere per poter aggiungere un tutor |
| **Precondizione**    | Il docente è in possesso di un account abilitatalo |
| **Postcondizione**   | Viene creato l'account tutor             |
| **Scenari astratti** | SC.1.1 - SC.1.2 - SC.1.3                 |

#### Scenario principale 

| Docente                                  | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| 1.1 Il docente chiede di accedere al sistema |                                          |
|                                          | 2.1 Il sistema chiede le credenziali di accesso |
|                                          |                                          |
| 3.1 Il docente comunica il suo user name e la password |                                          |
|                                          | 4.1 Il sistema autentica il docente      |
| 5.1 Il docente chiede al sistema di aggiungere un nuovo account tutor |                                          |
|                                          | 6.1 Il sistema chiede i dati del tutor   |
| 7.1 Il docente comunica i dati del tutor<br />7.2 Il docente conferma l'operazione |                                          |
|                                          | 8.1 Il sistema comunica il buon esito dell'operazione |

#### Scenario alternativo A1 - Dati di accesso non corretti

| Docente | Sistema                                  |
| ------- | ---------------------------------------- |
|         | A1.4.1 Il sistema avvisa il docente che i dati inserito non sono validi<br />Ritorno allo scenario principale al passo 2.1 |

#### Scenario alternativo A2 - Il tutor già esiste

| Docente | Sistema                                  |
| ------- | ---------------------------------------- |
|         | A2.8.1 Il sistema avvisa il docente che i dati inseriti corrispondono ad un tutor già presente nel sistema.<br />Ritorno allo scenario principale al passo 6.1 |

### UC.2 - Approvazione di uno studente 

| Nome del caso d'uso  | Approvazione di uno studente             |
| -------------------- | ---------------------------------------- |
| **Descrizione**      | Descrive il processo che un docente o un tutor deve eseguire per poter approvare uno studente |
| **Precondizione**    | Il docente o il tutor ha già eseguito l'autenticazione |
| **Postcondizione**   |                                          |
| **Scenari astratti** | SC.2.1 - SC.2.2 - SC.2.3                 |

#### Scenario principale 

| Docente o tutor                          | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| 1.1 Il docente o il tutor chiede la lista delle approvazioni pendenti |                                          |
|                                          | 2.1 Il sistema comunica la lista delle approvazioni pendenti |
| 3.1 Il docente o il tutor comunica l'approvazione a cui è interessato |                                          |
|                                          | 4.1 Il sistema chiede se si vuole approvare o meno la richiesta |
| 5.1 Il docente o il tutor comunica di approvare la richiesta |                                          |
|                                          | 6.1 Il sistema comunica il buon esito dell'operazione |

#### Scenario alternativo A1 - La richiesta viene rifiutata

| Docente o tutor                          | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| A1.5.1 Il docente o il tutor comunica di rifiutare la richiesta |                                          |
|                                          | A1.6.1 Il sistema chiede se si vuole inserire una nota con le motivazioni |
| A1.7.1 Il docente o il tutor comunica al sistema di voler inserire la nota<br />A1.7.2 Il docente o il tutor comunica al sistema le motivazioni |                                          |
|                                          | A1.8.1 - Il sistema comunica il buon esito dell'operazione |

#### Scenario alternativo A2 - Non ci sono richieste pendenti

| Docente o tutor | Sistema                                  |
| --------------- | ---------------------------------------- |
|                 | A2.2.1 Il sistema comunica che non ci sono richieste pendenti |

### UC.3 - Modifica di una sezione

| Nome del caso d'uso  | Modifica di una sezione                  |
| -------------------- | ---------------------------------------- |
| **Descrizione**      | Descrive il processo che un docente o un tutor deve eseguire per poter apportare delle modifiche ad una sezione del sito |
| **Precondizione**    | Il docente o il tutor ha già eseguito l'autenticazione |
| **Postcondizione**   |                                          |
| **Scenari astratti** | SC.3.1 - SC.3.2                          |

#### Scenario principale

| Docente o tutor                          | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| 1.1 Il docente o il tutor sceglie la sezione da modificare |                                          |
|                                          | 2.1 Il sistema mostra la sezione scelta  |
| 3.1 Il docente o il tutor chiede di modificare la sezione |                                          |
|                                          | 4.1 Il sistema entra nella modalità modifica |
| 5.1 Il docente o il tutor esegue le modifiche |                                          |
|                                          | 6.1 Il sistema salva le modifiche<br />6.2 Il sistema comunica il buon esito dell'operazione |

#### Scenario alternativo A1 - Impossibilità ad effettuare la modifica

| Docente o tutor | Sistema                                  |
| --------------- | ---------------------------------------- |
|                 | A1.4.1 Il sistema comunica l'impossibilità di entrane nella modalità modifica<br />A1.4.2 Il sistema mostra eventuali motivazioni |

### UC.4 - Approvazione di un gruppo 

| Nome del caso d'uso  | Approvazione di un gruppo                |
| -------------------- | ---------------------------------------- |
| **Descrizione**      | Descrive il processo che un docente o un tutor deve eseguire per poter approvare un gruppo |
| **Precondizione**    | Il docente o il tutor ha già eseguito l'autenticazione |
| **Postcondizione**   |                                          |
| **Scenari astratti** | SC.4.1 - SC.4.2 - SC4.3                  |

#### Scenario principale

| Docente o tutor                          | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| 1.1 Il docente o il tutor chiede la lista di approvazione dei gruppi |                                          |
|                                          | 2.1 Il sistema mostra tutte le richieste pendenti |
| 3.1 Il docente o il tutor comunica la richiesta a cui è interessato |                                          |
|                                          | 4.1 Il sistema mosta il nome del gruppo e il numero di membri |
| 5.1 Il docente o il tutor sceglie di approvare il gruppo |                                          |
|                                          | 6.1 Il sistema comunica il buon esito dell'operazione<br />6.2 Il sistema comunica la decisione agli studenti interessati |

#### Scenario alternativo A1 - Il gruppo non viene approvato

| Docente o tutor                          | Sistema                                  |
| ---------------------------------------- | ---------------------------------------- |
| A1.5.1 Il docente o il tutor sceglie di non approvare il gruppo<br />A1.5.2 Il docente o il tutor inserisce le eventuali motivazioni |                                          |
|                                          | Ritorno allo scenario principale al punto 6.1 |

#### Scenario alternativo A2 - La lista delle approvazioni è vuota

| Docente o tutor | Sistema                                  |
| --------------- | ---------------------------------------- |
|                 | A2.2.1 Il sistema comunica che la lista delle approvazioni è vuota |
|                 |                                          |

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.