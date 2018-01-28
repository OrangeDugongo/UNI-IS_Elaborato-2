## Testo originale

Sono previsti servizi per studenti, docenti e tutor. Docenti e tutor definiscono la sezione dedicata alle informazioni generali del corso ( descrizione, programma, testi consigliati, info e altro ..); la sezione dedicata ai materiali didattici ( slides e dispense); la sezione dedicata alle esercitazioni, agli elaborati, alla costituzione elenco gruppi di lavoro e assegnazione tutor ed elaborati, altro...; la sezione dedicata a testi, standard, lectures suggeriti; la sezione dedicata a iniziative culturali e scientifiche. Gli studenti potranno visitare le diverse sezioni del sito, scaricare materiali didattici e nell'apposita area depositare gli elaborati di gruppo.

## Testo strutturato

È richiesto di implementare un sito web per la gestione del corso di ingegneria informatica. Il sito web deve gestire l'accesso a tre tipologie di utenti; gli studenti, i docenti e i tutor. Gli account dei docenti possono essere creati solo dal gestore del sito. Un docente può creare un account tutor. I docenti e i tutor possono invitare gli studenti a partecipare tramite una mail. Gli studenti possono richiedere l'accesso al sistema dando la loro mail al docente o al tutor a lezione, o compilando un form sul sito.

Il sito è diviso in quattro sezioni:

1.   Una dedicata alle informazioni generali sul corso(descrizione, programma, testi consigliati, modalità d'esame, e altre info utili)
2.   Una dedicata alla condivisione di materiali didattici(slides e dispense)
3.   Una dedicata alle esercitazioni, agli elaborati, e alla gestione dei gruppi
4.   Una dedicata alle iniziative culturali e agli eventi.

Gli studenti possono navigare, previa autenticazione, tutte e quattro le sezioni, mentre solo i docenti e i tutor potranno apportare modifiche. Nella sezione 3 gli studenti potranno creare dei gruppi. Uno qualsiasi degli studenti può creare un nuovo gruppo invitando gli altri studenti a prendere parte al gruppo. Una volta che gli altri membri hanno confermato la loro partecipazione il gruppo viene attivato. Se il gruppo non è composto da esattamente tre membri deve essere attivato da un docente o da un tutor. Gli studenti devono scegliere un nome per il gruppo durante la fase di creazione.

Le sezioni 1 e 4 sono navigabili anche da utenti non loggati.

## Glossario

| Termini                 | Eventuali sinonimi | Definizione                              |
| ----------------------- | ------------------ | ---------------------------------------- |
| **Tipologie di utenti** | Tipi di account    | Gli utenti che interagiscono con il sistema sono divisi in varie tipologie in base alla quali vengono abilitati diversi componenti.<br />Le tipologie sono:<br />	- Studente<br />	- Docente<br />	- Tutor |
| **Form**                |                    | Campo per la sottomissione di dati       |
| **Sezioni**             | Aree               | Le vari componenti di cui si compone il sito.<br />Il sito è diviso nelle seguenti aree tematiche:<br />	- Informazioni sul corso<br />	- Materiali didattici<br />	- Esercitazioni<br />	- News ed eventi |
| **Gruppo**              |                    | Insieme di studenti. I gruppi standard sono costituiti da tre membri. Vene possono prendere parte anche di più(o di meno), ma devono essere approvati. |
| **Elaborato**           |                    | Lavoro prodotto da un gruppo.            |
| **Navigare**            | Accesso            | Consultare le aree tematiche del sito.   |
| **Apportare modifiche** |                    | Aggiungere, modificare ed rimuovere contenuti dal sito web. |
| **Utenti non loggati**  |                    | Visitatori della pagina web che non hanno effettuato nessun tipo di autenticazione |
| **Piattaforma**         | Sito web           | Il sistema preso in esame(?)             |

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

## Attori ed obiettivi primari (macro funzionalità) e scenari

### Docente

| Codice | Obiettivo primario         | Riferimento           |
| ------ | -------------------------- | --------------------- |
| MF.1   | Aggiunto di un nuovo tutor | 1.1<br />1.2<br />1.3 |

### Tutor

| Codice | Obiettivo primario        | Riferimento           |
| ------ | ------------------------- | --------------------- |
| MF.2   | Primo accesso di un tutor | 1.4<br />1.5<br />1.6 |

### Docente e tutor

| Codice | Obiettivo primario                       | Riferimento                            |
| ------ | ---------------------------------------- | -------------------------------------- |
| MF.3   | Aggiunta di un nuovo studente alla piattaforma | 2.2<br />2.3                           |
| MF.4   | Modifica di una sezione                  | 3.1<br />3.2<br />3.3<br />3.<br />3.5 |
| MF.5   | Approvazione di un gruppo                | 4.8                                    |
| MF.6   | Commentare il lavoro di un gruppo        | 5.5                                    |

### Studente

| Codice | Obiettivo primario               | Riferimento                              |
| ------ | -------------------------------- | ---------------------------------------- |
| MF.7   | Creazione di un account studente | 2.1<br />2.4<br />2.5<br />2.6           |
| MF.8   | Creazione di un gruppo           | 4.1<br />4.2<br />4.3<br />4.4<br />4.5<br />4.6<br />4.7 |
| MF.9   | Modifica di un elaborato         | 5.1<br />5.2<br />5.3<br />5.6           |

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.