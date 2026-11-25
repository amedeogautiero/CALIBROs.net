| # | Capitolo | Contenuto |
|---|---|---|
| 1 | Executive Summary | Presentazione di CALIBROs e della sua proposta di valore |
| 2 | Product Vision | Visione, obiettivi e filosofia del prodotto |
| 3 | Product Overview | Architettura e componenti della piattaforma |
| 4 | Free Product | Estensione VS Code gratuita |
| 5 | Commercial Products | On-Premise e Cloud |
| 6 | Professional Services | Servizi professionali offerti |
| 7 | Business Model | Modelli di ricavo e licensing |
| 8 | Competitive Analysis | Analisi dei competitor |
| 9 | Pricing Strategy & Commercial Offering  | Pacchetti commerciali, edizioni, licenze e prezzi |
| 10 | Target Market | Clienti potenziali e segmentazione |
| 11 | Go-to-Market Strategy | Strategia di ingresso sul mercato |
| 12 | Marketing Strategy | Comunicazione e promozione |
| 13 | Distribution Strategy | Marketplace, sito, distribuzione software |
| 14 | Roadmap | Evoluzione commerciale e tecnologica |--------------------------------------------------------------------------------


--------------------------------------------------------------------------------------------------------------------------------------------------------
# 1. Motivazione del progetto

CALIBROs nasce dalla volontà di colmare il vuoto lasciato dalla dismissione degli strumenti Microsoft Visual Studio Web Performance and Load Test, offrendo una valida alternativa agli sviluppatori e alle aziende che utilizzavano questa tecnologia.

L'obiettivo non è semplicemente replicare le funzionalità del prodotto Microsoft, ma realizzare una piattaforma moderna e professionale, capace di offrire un'esperienza di sviluppo completa per la progettazione e la realizzazione di test Web.

La filosofia alla base del progetto è quella di considerare il Web Testing una vera attività di sviluppo software, anziché una semplice attività di configurazione di strumenti per l'esecuzione di test.

I WebTest sono concepiti come componenti di normali progetti .NET, all'interno dei quali è possibile sviluppare test funzionali, test di regressione e logiche personalizzate. Gli stessi WebTest possono successivamente diventare la base per la realizzazione di campagne di Load Testing.

Un elemento fondamentale del progetto è la Developer Experience: la possibilità di utilizzare strumenti tipici degli ambienti di sviluppo, come breakpoint, variable watch e debugging, per progettare, verificare e analizzare il comportamento dei test.

CALIBROs vuole quindi recuperare e superare l'esperienza offerta dal precedente strumento Microsoft, introducendo un approccio moderno, flessibile e integrato nell'ecosistema degli strumenti utilizzati dagli sviluppatori.

--------------------------------------------------------------------------------------------------------------------------------------------------------

# 2. Product Vision 

CALIBROs nasce con l'obiettivo di colmare il vuoto lasciato dalla dismissione degli strumenti Microsoft per Web Performance e Load Testing, realizzando una piattaforma moderna e professionale, capace di offrire una vera esperienza di sviluppo dedicata al Web Testing.

CALIBROs non vuole essere semplicemente uno strumento per generare traffico e misurare le prestazioni delle applicazioni Web, ma un ambiente integrato per progettare, sviluppare, eseguire e analizzare test Web.

La piattaforma si rivolge principalmente a Web Developer e Performance Engineer, indipendentemente dalle tecnologie e dai linguaggi utilizzati per sviluppare le applicazioni sottoposte a test.

Il suo approccio integra Functional Testing, Regression Testing e Performance Testing, consentendo di sviluppare test funzionali e di riutilizzarli come base per successive campagne di Load Testing.

Uno degli elementi distintivi di CALIBROs è l'esperienza di sviluppo: funzionalità come breakpoint, variable watch e debugging permettono di progettare e verificare i test utilizzando strumenti e modalità familiari agli sviluppatori.

Attraverso Visual Studio Code, una configurazione dichiarativa basata su YAML e un'infrastruttura modulare per l'esecuzione distribuita, CALIBROs vuole integrare il Performance Testing nel naturale ciclo di sviluppo delle applicazioni Web.

**La visione di CALIBROs è trasformare il Web Testing in una vera attività di sviluppo software, unificando test funzionali, regressione e performance testing in un unico ambiente di lavoro.**
--------------------------------------------------------------------------------------------------------------------------------------------------------

# 3. Target Professionale

CALIBROs si rivolge principalmente a professionisti che operano nello sviluppo e nella verifica delle applicazioni Web, indipendentemente dalle tecnologie e dai linguaggi di programmazione utilizzati per realizzarle.

I principali destinatari della piattaforma sono:

## 3.1 Web Developer

Rappresentano uno dei principali utilizzatori di CALIBROs.

Possono utilizzare l'estensione Visual Studio Code per progettare, sviluppare ed eseguire WebTest funzionali, verificare il comportamento delle applicazioni e individuare eventuali regressioni.

La possibilità di utilizzare strumenti di debugging, breakpoint e variable watch consente di affrontare la realizzazione dei test con un'esperienza molto simile a quella dello sviluppo software tradizionale.

## 3.2 Performance Engineer

Rappresentano l'altro principale gruppo di utilizzatori della piattaforma.

Utilizzano CALIBROs per progettare scenari di carico, configurare utenti virtuali, eseguire LoadTest e StressTest e analizzare le prestazioni delle applicazioni Web.

Possono utilizzare i WebTest già realizzati durante la fase di sviluppo come base per le successive campagne di Performance Testing.

## 3.3 QA Engineer

Rappresentano un ulteriore gruppo di utilizzatori che può beneficiare delle funzionalità della piattaforma.

La possibilità di realizzare test funzionali e di regressione all'interno dello stesso ambiente utilizzato per la progettazione dei LoadTest consente di integrare le attività di Quality Assurance e Performance Testing.

Il loro coinvolgimento rappresenta una conseguenza naturale dell'approccio integrato adottato da CALIBROs.

--------------------------------------------------------------------------------------------------------------------------------------------------------

# 4. Target Commerciale

Il mercato di riferimento di CALIBROs è costituito principalmente da aziende che sviluppano applicazioni Web e che hanno già maturato la necessità di effettuare attività di Performance Testing.

Il target commerciale iniziale è rappresentato da piccole e medie software house, con particolare attenzione alle organizzazioni che utilizzano già strumenti di Load Testing o che in passato hanno utilizzato Microsoft Visual Studio Web Performance and Load Test.

## 4.1 Software House che utilizzano già strumenti di Load Testing

Rappresentano uno dei principali segmenti di mercato.

Queste aziende conoscono già l'importanza delle attività di Performance Testing e dispongono generalmente di processi e competenze per la realizzazione e l'esecuzione dei test.

CALIBROs può rappresentare un'alternativa interessante grazie a un ambiente di sviluppo integrato, alla possibilità di effettuare debugging dei WebTest e alla prospettiva di ridurre i tempi necessari per la realizzazione e la manutenzione degli scenari di test.

## 4.2 Ex utilizzatori di Microsoft Visual Studio Web Performance and Load Test

Rappresentano un segmento particolarmente interessante per il lancio iniziale del prodotto.

Si tratta di sviluppatori e aziende che conoscono già il modello di lavoro introdotto da Microsoft e che, a seguito della dismissione del prodotto, potrebbero essere interessati a una soluzione alternativa.

La familiarità con l'approccio di sviluppo dei WebTest e la possibilità di ritrovare un'esperienza di lavoro simile a quella del precedente strumento Microsoft costituiscono elementi potenzialmente favorevoli all'adozione di CALIBROs.

## 4.3 Grandi aziende

Rappresentano un possibile segmento di espansione commerciale.

Le organizzazioni più strutturate possono avere necessità di infrastrutture dedicate, esecuzioni distribuite, gestione centralizzata dei test e requisiti specifici di sicurezza e governance.

Il loro coinvolgimento dipenderà anche dal livello di maturità raggiunto dal prodotto e dalla notorietà acquisita sul mercato.

## 4.4 Società di consulenza e Performance Testing

Rappresentano un possibile segmento commerciale da approfondire.

Queste organizzazioni potrebbero utilizzare CALIBROs come piattaforma per offrire servizi di progettazione, realizzazione ed esecuzione di LoadTest ai propri clienti.

Potrebbero inoltre diventare partner commerciali o tecnologici del progetto.

## 4.5 Sviluppatori individuali e freelance

Non rappresentano il principale target commerciale.

Potranno utilizzare liberamente l'estensione Visual Studio Code gratuita e contribuire alla diffusione del prodotto attraverso il suo utilizzo, la partecipazione alle community tecniche e la condivisione delle proprie esperienze.

Il loro contributo sarà particolarmente importante per aumentare la notorietà di CALIBROs e favorire la sua adozione presso le aziende.

--------------------------------------------------------------------------------------------------------------------------------------------------------

# 5. Modello Commerciale

CALIBROs adotterà un modello commerciale basato sulla distribuzione gratuita degli strumenti di sviluppo e sulla commercializzazione delle infrastrutture e dei servizi necessari per l'esecuzione dei test di carico.

La strategia prevede tre principali offerte commerciali:

- DeoWebLoadTest Extension – Free
- DeoWebLoadTest On-Premise – Commercial
- DeoWebLoadTest Cloud – Commercial

A queste si aggiunge un'offerta di servizi professionali dedicati ai clienti.

## 5.1 DeoWebLoadTest Extension – Free

L'estensione per Visual Studio Code sarà distribuita gratuitamente attraverso il Visual Studio Code Marketplace.

Non sono previste limitazioni artificiali alle funzionalità offerte dall'estensione.

Gli utilizzatori potranno:

- Creare e modificare WebTest.
- Progettare scenari di test.
- Utilizzare l'editor YAML.
- Gestire DataSource, variabili e parametri.
- Configurare validazioni.
- Utilizzare gli strumenti di ispezione delle richieste.
- Eseguire singoli WebTest.
- Eseguire test multipli.
- Effettuare debugging dei test attraverso gli strumenti disponibili nell'ambiente di sviluppo.

L'estensione non permette invece di effettuare LoadTest o StressTest e non supporta la simulazione di utenti virtuali contemporanei.

La generazione del carico e l'esecuzione distribuita sono funzionalità riservate alle componenti commerciali della piattaforma.

La versione gratuita costituisce il principale strumento di diffusione e acquisizione di nuovi utilizzatori.

## 5.2 DeoWebLoadTest On-Premise – Commercial

La soluzione On-Premise è destinata alle aziende che desiderano eseguire i LoadTest utilizzando infrastrutture proprie.

Il cliente installa localmente le componenti necessarie all'esecuzione dei test:

- **CLI:** strumento per l'esecuzione dei test da linea di comando.
- **Controller:** componente responsabile del coordinamento e della gestione delle esecuzioni.
- **Agent:** componenti incaricati della generazione del carico e della simulazione degli utenti virtuali.

Il cliente può distribuire Controller e Agent sulla propria infrastruttura, realizzando un ambiente di esecuzione distribuito.

Il modello commerciale prevede l'acquisto di licenze per l'utilizzo della piattaforma, con una possibile tariffazione basata sul numero di utenti virtuali e/o sulle ore di utilizzo.

Le modalità definitive di licensing e pricing saranno definite successivamente.

## 5.3 DeoWebLoadTest Cloud – Commercial

La soluzione Cloud consente di utilizzare le funzionalità di Load Testing senza dover installare o gestire direttamente le componenti infrastrutturali necessarie all'esecuzione.

Il cliente continua a utilizzare l'estensione Visual Studio Code per progettare e configurare i propri test, mentre l'esecuzione viene demandata all'infrastruttura Cloud di CALIBROs.

Gli Agent vengono messi a disposizione attraverso l'infrastruttura Cloud e coordinati per eseguire le campagne di Load Testing.

Il cliente non deve installare CLI, Controller o Agent nella propria infrastruttura.

Il modello commerciale sarà basato sul consumo delle risorse di esecuzione, con una possibile tariffazione in funzione del numero di utenti virtuali e della durata delle esecuzioni.

Le modalità definitive di pricing, eventuali pacchetti prepagati e formule di abbonamento saranno definite successivamente.

## 5.4 Professional Services – Commercial

CALIBROs potrà offrire servizi professionali alle aziende che desiderano affidare a un soggetto specializzato la progettazione e l'esecuzione delle proprie campagne di Performance Testing.

Questi servizi saranno proposti come offerta aggiuntiva rispetto all'acquisto della soluzione On-Premise o Cloud.

Le attività potranno comprendere:

- Analisi delle applicazioni da sottoporre a test.
- Progettazione degli scenari di test.
- Realizzazione dei WebTest.
- Configurazione dei DataSource e dei parametri.
- Progettazione delle campagne di Load Testing.
- Esecuzione dei test.
- Analisi dei risultati.
- Individuazione di eventuali colli di bottiglia.
- Consulenza per l'ottimizzazione delle prestazioni.

Il modello economico potrà prevedere incarichi a progetto, pacchetti di attività o tariffe professionali.

## 5.5 Proprietà intellettuale e distribuzione

CALIBROs sarà distribuito come software proprietario.

Non è prevista la distribuzione pubblica e libera dei sorgenti del prodotto.

Anche le componenti gratuite saranno distribuite esclusivamente in forma binaria, attraverso i canali ufficiali previsti.

La gratuità dell'estensione Visual Studio Code non comporta quindi la concessione di una licenza Open Source.

Le condizioni di utilizzo, distribuzione e licensing saranno disciplinate da apposite licenze software.

-------------------------------------------------------------------------------------------------------------------


-------------------------------------------------------------------------------------------------------------------

# 6. Professional Services

## 6.1 Obiettivo

I Professional Services rappresentano una componente dell'offerta commerciale CALIBROs e hanno l'obiettivo di supportare le aziende nell'utilizzo della piattaforma per la progettazione, lo sviluppo, l'esecuzione e l'analisi dei test funzionali e di performance.

L'offerta di servizi professionali consente ai clienti di affidarsi a competenze specialistiche per realizzare attività di testing, affrontare problematiche prestazionali e migliorare la qualità e l'affidabilità delle proprie applicazioni Web.

I Professional Services possono essere acquistati indipendentemente dalle modalità di utilizzo della piattaforma, On-Premise o Cloud, secondo le condizioni commerciali previste.

## 6.2 Catalogo dei servizi

L'offerta di Professional Services comprende le seguenti aree.

### Test Design

Analisi dell'applicazione da sottoporre a test e progettazione degli scenari di verifica.

Le attività possono comprendere:
- Analisi dei flussi applicativi.
- Identificazione delle operazioni e dei percorsi utente più significativi.
- Definizione degli scenari funzionali e di carico.
- Identificazione dei parametri e delle condizioni di esecuzione.
- Definizione degli obiettivi e dei criteri di valutazione dei test.

### Test Development

Realizzazione dei WebTest e degli scenari di LoadTest utilizzando CALIBROs.

Le attività possono comprendere:
- Sviluppo dei WebTest funzionali.
- Configurazione di richieste, variabili, DataSource e validazioni.
- Realizzazione di scenari di carico e stress.
- Sviluppo di componenti ed estensioni personalizzate.
- Manutenzione ed evoluzione dei test esistenti.

### Test Execution

Configurazione e conduzione delle campagne di test attraverso l'infrastruttura CALIBROs.

Le attività possono comprendere:
- Configurazione dei parametri di esecuzione.
- Configurazione degli utenti virtuali.
- Esecuzione di LoadTest e StressTest

# 7. Business Model

## 7.1 Principi del modello di business

Il modello di business di CALIBROs si basa su una combinazione di prodotti software gratuiti, prodotti commerciali e servizi professionali.

L'obiettivo è favorire la diffusione della piattaforma tra gli sviluppatori Web, rendendo disponibili gratuitamente gli strumenti necessari per progettare, sviluppare, eseguire e verificare i WebTest, e monetizzare le funzionalità dedicate all'esecuzione dei test di carico e stress, oltre ai servizi professionali.

Il modello prevede quindi una distinzione tra:

- Ambiente di sviluppo e gestione dei WebTest.
- Infrastruttura e capacità di esecuzione dei LoadTest e StressTest.
- Servizi professionali di consulenza e supporto.

Questa separazione consente di favorire l'adozione della piattaforma senza richiedere un investimento iniziale per ogni sviluppatore che intenda utilizzarla.

## 7.2 Prodotti e fonti di ricavo

L'offerta commerciale CALIBROs si articola in tre componenti principali:

1. Free Extension.
2. Commercial Products.
3. Professional Services.

### 7.2.1 Free Extension

L'estensione per Visual Studio Code viene distribuita gratuitamente e rende disponibili tutte le funzionalità previste per la progettazione e la gestione dei WebTest.

Non sono previste limitazioni artificiali delle funzionalità disponibili all'interno dell'estensione.

La versione gratuita consente di:

- Creare e modificare WebTest.
- Configurare richieste HTTP.
- Gestire variabili e DataSource.
- Configurare parametri e validazioni.
- Ispezionare richieste e risposte.
- Utilizzare gli strumenti di debugging disponibili.
- Eseguire singoli WebTest o più test.

L'estensione gratuita non consente invece di eseguire LoadTest e StressTest e non include funzionalità di generazione del carico attraverso utenti virtuali concorrenti.

La Free Extension rappresenta il principale strumento di diffusione della piattaforma e costituisce il punto di ingresso per sviluppatori, Performance Engineer e aziende interessate a CALIBROs.

### 7.2.2 Commercial Products

I prodotti commerciali consentono di utilizzare le funzionalità di esecuzione dei LoadTest e StressTest.

Sono previste due modalità di utilizzo.

#### CALIBROs On-Premise

La soluzione On-Premise consente al cliente di installare ed eseguire localmente l'infrastruttura necessaria per la generazione del carico.

La componente commerciale comprende:

- Installazione della CLI per l'esecuzione dei LoadTest.
- Installazione del Controller.
- Installazione degli Agent.
- Possibilità di configurare infrastrutture distribuite per la generazione del carico.

L'esecuzione avviene nell'infrastruttura del cliente, che mantiene il controllo dell'ambiente e delle risorse utilizzate.

Il modello di licensing sarà basato sulla capacità di generazione del carico, espressa attraverso il numero di Virtual User e/o la durata del loro utilizzo.

#### CALIBROs Cloud

La soluzione Cloud consente di eseguire LoadTest e StressTest utilizzando Agent ospitati nell'infrastruttura CALIBROs.

Il cliente non deve installare localmente Controller e Agent per la generazione del carico.

L'utilizzo avviene attraverso la piattaforma, che gestisce l'infrastruttura necessaria all'esecuzione dei test.

Il modello commerciale sarà basato sulla capacità di generazione del carico utilizzata e/o sulla durata delle esecuzioni.

Questa modalità permette di accedere alle funzionalità di Load Testing senza dover predisporre e mantenere un'infrastruttura dedicata.

### 7.2.3 Professional Services

I Professional Services rappresentano una fonte di ricavo aggiuntiva rispetto alla vendita dei prodotti software.

Comprendono i servizi di:

- Test Design.
- Test Development.
- Test Execution.
- Performance Analysis.
- Performance Consulting.
- Continuous Testing.

I servizi potranno essere acquistati direttamente da CALIBROs oppure erogati attraverso partner qualificati, secondo il modello misto definito nel capitolo dedicato.

## 7.3 Modello di Licensing

Il modello di licensing di CALIBROs si basa principalmente sulla capacità di generazione del carico, espressa in **Virtual Users (VU)**, e sulla durata del diritto di utilizzo del prodotto.

Il cliente acquista una licenza che definisce il numero massimo di Virtual Users che possono essere utilizzati contemporaneamente, indipendentemente dal numero di LoadTest eseguiti.

### 7.3.1 Principi generali

Il modello prevede i seguenti principi:

- Il limite della licenza è espresso in Virtual Users contemporanei.
- Il numero di LoadTest eseguibili non è limitato.
- Il numero di esecuzioni e di iterazioni non è limitato.
- La capacità acquistata rappresenta il limite complessivo utilizzabile, indipendentemente dal numero di Agent installati.
- La capacità viene liberata quando un LoadTest termina e può essere utilizzata da altre esecuzioni.

Ad esempio, una licenza da 250 VU consente di eseguire contemporaneamente più LoadTest, purché la somma dei Virtual Users utilizzati non superi 250.

### 7.3.2 Licensing On-Premise

Il prodotto CALIBROs On-Premise prevede diverse formule di licenza, per adattarsi alle differenti esigenze dei clienti.

| Formula | Durata | Descrizione |
|---|---|---|
| Weekly Pass | 7 giorni | Licenza temporanea per esigenze occasionali, POC o campagne di test. |
| Monthly Subscription | 1 mese | Abbonamento mensile. |
| Quarterly Subscription | 3 mesi | Abbonamento trimestrale. |
| Annual Subscription | 12 mesi | Abbonamento annuale. |
| Perpetual License | Senza scadenza | Licenza permanente, senza limiti temporali di utilizzo. |

Ogni formula prevede uno specifico limite massimo di Virtual Users acquistati.

**Licenze a durata limitata**

Per le licenze Weekly, Monthly, Quarterly e Annual, il diritto di utilizzo è valido esclusivamente durante il periodo acquistato.

Alla scadenza:
- Non è possibile avviare nuovi LoadTest.
- Non è possibile incrementare il carico dei test in corso.
- Gli eventuali test ancora attivi vengono gestiti attraverso una procedura di arresto controllato.

**Licenza perpetua**

La Perpetual License garantisce il diritto di utilizzo del prodotto senza scadenza temporale.

Il limite massimo di Virtual Users rimane quello acquistato e non è soggetto a rinnovi periodici.

Il cliente può continuare a utilizzare il prodotto ed eseguire LoadTest senza limiti di numero o frequenza, nel rispetto della capacità acquistata.

La licenza perpetua garantisce il diritto di utilizzo della versione acquistata. Gli aggiornamenti alle versioni successive e il supporto tecnico possono essere regolati attraverso un contratto di manutenzione separato.

### 7.3.3 Licensing Cloud

Il prodotto CALIBROs Cloud prevede un modello commerciale basato su abbonamento.

Il cliente acquista una determinata capacità di generazione del carico, espressa in Virtual Users, e utilizza gli Agent ospitati nell'infrastruttura Cloud di CALIBROs.

Il modello consente di utilizzare le funzionalità di LoadTest senza dover installare e gestire direttamente l'infrastruttura necessaria alla generazione del carico.

La definizione delle formule commerciali, delle durate degli abbonamenti e delle eventuali modalità di consumo costituisce un punto ancora da approfondire.

### 7.3.4 Gestione tecnica delle licenze

La gestione delle licenze è affidata a un sistema centralizzato denominato **CALIBROs Licensing Server**.

L'architettura prevede tre componenti principali:

| Componente | Responsabilità |
|---|---|
| Licensing Server | Gestione delle licenze, attivazioni, scadenze e autorizzazioni. |
| Controller | Verifica della licenza e gestione della capacità complessiva di Virtual Users disponibile. |
| Agent | Esecuzione dei Virtual Users assegnati dal Controller. |

La licenza viene rilasciata attraverso un documento firmato digitalmente, contenente almeno:
- Identificativo della licenza.
- Tipologia di prodotto.
- Numero massimo di Virtual Users.
- Tipologia di licenza.
- Data di inizio validità.
- Data di scadenza, se prevista.

Il Controller verifica la validità della licenza prima di autorizzare l'esecuzione di un LoadTest.

Gestisce inoltre il budget complessivo dei Virtual Users, riservando la capacità necessaria per ogni esecuzione e distribuendola tra gli Agent disponibili.

Gli Agent possono utilizzare esclusivamente la quantità di Virtual Users assegnata dal Controller.

Per le licenze a scadenza è prevista una verifica periodica con il Licensing Server, attraverso autorizzazioni temporanee (lease), al fine di verificare la validità della licenza anche durante il periodo di utilizzo.

L'architettura On-Premise mantiene l'esecuzione dei test interamente nell'infrastruttura del cliente. La comunicazione con il Licensing Server riguarda esclusivamente le informazioni necessarie alla gestione e alla verifica delle licenze.

### 7.3.5 Manutenzione e aggiornamenti

Per le licenze perpetue, la manutenzione rappresenta un elemento commerciale distinto dal diritto di utilizzo del prodotto.

Potrà comprendere:
- Accesso alle nuove versioni del prodotto.
- Aggiornamenti e miglioramenti.
- Correzioni e aggiornamenti di sicurezza.
- Supporto tecnico.

La manutenzione potrà essere proposta attraverso un contratto annuale rinnovabile.

Per le licenze a sottoscrizione, gli aggiornamenti e il supporto saranno invece regolati dalla durata e dalle condizioni dell'abbonamento.

### Stato delle decisioni

**DECISIONI**
- Licensing basato sul numero massimo di Virtual Users contemporanei.
- Nessun limite al numero di LoadTest e di esecuzioni.
- Disponibilità di licenze a durata limitata e perpetue per il prodotto On-Premise.
- La licenza perpetua non ha scadenza temporale.
- Il Controller gestisce il budget complessivo dei VU e la loro distribuzione tra gli Agent.
- Il Licensing Server gestisce attivazione e verifica delle licenze.

**PROPOSTE**
- Utilizzo di licenze firmate digitalmente.
- Verifica periodica delle licenze attraverso autorizzazioni temporanee.
- Manutenzione annuale separata per le licenze perpetue.

**OPEN POINT**
- Definizione dei pacchetti commerciali e dei relativi prezzi.
- Definizione delle modalità di rinnovo e delle condizioni di manutenzione.
- Definizione delle formule commerciali Cloud.
- Definizione delle politiche di funzionamento in assenza temporanea di connessione al Licensing Server.

## 7.4 Strategia di acquisizione dei clienti

La Free Extension rappresenta il principale strumento di acquisizione e diffusione della piattaforma.

Gli sviluppatori possono iniziare a utilizzare CALIBROs senza sostenere costi e senza dover acquistare preventivamente una licenza commerciale.

L'utilizzo dell'estensione può favorire la diffusione del prodotto all'interno delle software house e delle organizzazioni, creando interesse verso le funzionalità commerciali di Load Testing.

Il passaggio ai prodotti commerciali avviene quando emerge la necessità di eseguire test di carico e stress, utilizzando l'infrastruttura On-Premise oppure quella Cloud.

Questo modello consente di separare l'adozione degli strumenti di sviluppo dalla decisione di investimento nelle funzionalità di generazione del carico.

## 7.5 Sostenibilità ed evoluzione del modello

Il modello di business è progettato per combinare ricavi derivanti dai prodotti software e ricavi derivanti dai servizi professionali.

Le principali fonti di ricavo sono:

- Licensing della soluzione On-Premise.
- Utilizzo della soluzione Cloud.
- Erogazione di Professional Services.

La distribuzione gratuita dell'estensione favorisce la diffusione della piattaforma e contribuisce alla creazione di una base di utilizzatori che può generare opportunità commerciali.

Nel tempo, il modello potrà evolvere attraverso l'introduzione di ulteriori formule commerciali, pacchetti di utilizzo e accordi con partner.

---

**Stato del capitolo:** DECISIONE sulle tre componenti dell'offerta commerciale e sul ruolo della Free Extension. PROPOSTA per la struttura complessiva del modello di business. OPEN POINT per il licensing, le formule di acquisto e la definizione dei prezzi.

# 8. Competitive Analysis

## 8.1 Obiettivo dell'analisi

L'analisi competitiva ha l'obiettivo di identificare il posizionamento di CALIBROs rispetto agli strumenti già presenti sul mercato del Web Performance Testing e del Load Testing.

Il confronto non deve limitarsi alle funzionalità di generazione del carico, ma deve considerare l'intera esperienza di lavoro degli utenti: dalla progettazione dei test alla loro realizzazione, dal debugging all'esecuzione, fino all'analisi dei risultati.

Particolare attenzione viene riservata agli strumenti utilizzati da sviluppatori e Performance Engineer, poiché CALIBROs intende differenziarsi anche attraverso un'esperienza di sviluppo più vicina a quella degli ambienti di programmazione tradizionali.

## 8.2 Concorrenti e soluzioni alternative

I principali prodotti e strumenti individuati per il confronto sono:

| Prodotto | Azienda / Organizzazione | Approccio |
|---|---|---|
| Apache JMeter | Apache Software Foundation | Open Source, GUI e Test Plan |
| Grafana k6 | Grafana Labs | Test as Code |
| Gatling | Gatling Corp. | Test as Code e ambiente visuale |
| OpenText LoadRunner | OpenText | Piattaforma enterprise di performance testing |
| Tricentis NeoLoad | Tricentis | Piattaforma visuale di performance testing |
| StresStimulus | Stimulus Technology | Web Performance e Functional Testing |

Viene inoltre considerato Microsoft Visual Studio Web Performance and Load Test, prodotto storico che rappresenta il riferimento originario e una delle motivazioni alla base della nascita di CALIBROs.

## 8.3 Developer Experience

### 8.3.1 Definizione

Per Developer Experience si intende l'esperienza complessiva di chi sviluppa e mantiene i test.

Non riguarda soltanto la facilità di configurazione di uno scenario, ma comprende gli strumenti messi a disposizione per comprendere il comportamento del test, individuare errori, ispezionare i dati e intervenire sul codice.

Per CALIBROs questa dimensione rappresenta uno degli elementi centrali del posizionamento competitivo.

### 8.3.2 Dimensioni di confronto

Il confronto viene articolato nelle seguenti dimensioni:

1. **Test Development** – strumenti e modalità per creare, modificare e organizzare i WebTest.
2. **Debugging** – possibilità di interrompere e controllare l'esecuzione dei test, anche attraverso breakpoint e avanzamento controllato.
3. **Variable Inspection** – possibilità di osservare e analizzare il valore delle variabili durante l'esecuzione.
4. **Request Inspection** – strumenti per analizzare richieste HTTP, risposte, header, payload e informazioni correlate.
5. **Test Organization** – modalità di organizzazione dei test, degli scenari e dei relativi componenti.
6. **Code Extensibility** – possibilità di estendere il comportamento dei test attraverso codice personalizzato.
7. **IDE Integration** – integrazione con gli ambienti di sviluppo e con i relativi strumenti di debugging.

### 8.3.3 Posizionamento di CALIBROs

CALIBROs offre un ambiente dedicato allo sviluppo dei WebTest integrato in Visual Studio Code.

Le funzionalità disponibili comprendono:

- Creazione e modifica dei WebTest.
- Configurazione delle richieste HTTP e dei relativi parametri.
- Gestione di variabili e DataSource.
- Configurazione di validazioni e controlli.
- Ispezione delle richieste e delle risposte HTTP.
- Esecuzione controllata dei WebTest.
- Debugging attraverso breakpoint.
- Ispezione delle variabili durante l'esecuzione.
- Estensione delle funzionalità attraverso codice personalizzato .NET.
- Utilizzo del debugging nativo .NET per il codice estendibile.

In particolare, il debugging rappresenta un elemento distintivo dell'esperienza di sviluppo proposta da CALIBROs.

L'obiettivo è consentire allo sviluppatore di analizzare il comportamento del WebTest direttamente nell'ambiente di lavoro, senza dover ricorrere esclusivamente a log, output di esecuzione o strumenti di analisi successiva.

L'estensibilità attraverso .NET consente inoltre di utilizzare le funzionalità dell'ecosistema Microsoft per sviluppare e diagnosticare componenti personalizzati.

### 8.3.4 Confronto con i concorrenti

Le soluzioni analizzate presentano approcci differenti alla Developer Experience.

| Prodotto | Approccio allo sviluppo e debugging |
|---|---|
| Apache JMeter | Ambiente visuale basato su Test Plan. Offre strumenti di ispezione delle richieste e delle risposte, oltre a funzionalità di logging e diagnostica. |
| Grafana k6 | Approccio Test as Code, affiancato da k6 Studio, che permette di eseguire una singola iterazione e ispezionare richieste, risposte, log e risultati. |
| Gatling | Approccio Test as Code basato su SDK e linguaggi di programmazione. Lo sviluppo e il debugging utilizzano prevalentemente gli strumenti dell'IDE. |
| OpenText LoadRunner | Ambiente di sviluppo e debugging maturo, con breakpoint, watch delle variabili e strumenti specifici per gli script. |
| Tricentis NeoLoad | Ambiente visuale con modalità di debugging step-by-step e breakpoint per determinate tipologie di azioni e componenti personalizzati. |
| StresStimulus | Ambiente visuale con editor C#, componenti .NET personalizzati e possibilità di utilizzare Visual Studio per lo sviluppo e il debugging delle estensioni esterne. |

Il confronto evidenzia che alcune funzionalità di debugging sono già presenti anche nei prodotti concorrenti.

In particolare, LoadRunner e NeoLoad dispongono di strumenti di debugging dedicati, mentre StresStimulus offre possibilità di estensione attraverso codice .NET e integrazione con Visual Studio.

Di conseguenza, la differenziazione di CALIBROs non deve essere basata sulla semplice presenza di breakpoint o sulla possibilità di utilizzare codice personalizzato.

Il valore potenziale risiede nella combinazione di queste funzionalità all'interno di un ambiente moderno, integrato in Visual Studio Code e specificamente orientato allo sviluppo dei WebTest.

### 8.3.5 Possibile vantaggio competitivo

La principale opportunità di differenziazione individuata è rappresentata dall'integrazione tra:

- Ambiente dedicato allo sviluppo dei WebTest.
- Debugging del flusso di esecuzione.
- Breakpoint e ispezione delle variabili.
- Ispezione dettagliata delle richieste HTTP.
- Estensibilità attraverso codice .NET.
- Debugging nativo .NET per il codice personalizzato.
- Possibilità di riutilizzare i WebTest come base per la realizzazione dei LoadTest.

CALIBROs intende quindi portare le pratiche tipiche dello sviluppo software all'interno del Web Performance Testing.

L'obiettivo è ridurre la distanza tra la realizzazione di un test funzionale e la sua successiva trasformazione in uno scenario di carico.

Questo approccio potrebbe consentire di semplificare lo sviluppo e la manutenzione dei test, riducendo la dipendenza da procedure di diagnosi basate esclusivamente sull'analisi dei log e dei risultati di esecuzione.

**Stato della valutazione:** il posizionamento è una proposta strategica da validare attraverso un confronto più approfondito con i concorrenti e, successivamente, attraverso prove pratiche.

### 8.3.6 Conclusioni

L'analisi preliminare della Developer Experience evidenzia uno spazio competitivo interessante per CALIBROs.

Gli strumenti esistenti adottano approcci differenti: alcuni privilegiano la configurazione visuale, altri lo sviluppo attraverso codice, altri ancora offrono ambienti di debugging particolarmente maturi.

CALIBROs intende combinare questi approcci, proponendo un ambiente di sviluppo dedicato ai WebTest, con strumenti di debugging integrati e possibilità di estensione attraverso .NET.

La Developer Experience rappresenta pertanto una delle principali aree sulle quali costruire il posizionamento competitivo e la comunicazione commerciale del prodotto.
**Stato:** PROPOSTA – Analisi competitiva preliminare, da approfondire e validare.
-------------------------------------------------------------------------------------------------------------------









-------------------------------------

Confronto Developer Experience
Legenda:
- Nativo: funzionalità integrate nello strumento.
- IDE: funzionalità disponibili attraverso un IDE esterno.
- Parziale: funzionalità presenti, ma con modalità o limiti differenti.
- Non documentato: non ho trovato evidenze sufficienti nella documentazione ufficiale consultata.
| Funzionalità        | CALIBROs | JMeter | k6           | Gatling      | LoadRunner | NeoLoad | StresStimulus |
|---------------------|----------|--------|--------------|--------------|------------|---------|---------------|
| Test Development    | Nativo   | Nativo | IDE / Codice | IDE / Codice | Nativo     | Nativo  | Nativo        |
| Breakpoint sui test | Nativo   | Non documentato | Parziale | IDE | Nativo | Nativo | Non documentato |
| Step-by-step debugging | Nativo | Parziale | Parziale | IDE | Nativo | Nativo | Non documentato |
| Ispezione variabili | Nativo | Parziale | Parziale | IDE | Nativo | Nativo | Nativo / IDE |
| Request/Response Inspector | Nativo | Nativo | Nativo | Parziale | Nativo | Nativo | Nativo |
| Debug codice personalizzato | .NET nativo | IDE / linguaggio | IDE / linguaggio | IDE / linguaggio | IDE / linguaggio | Nativo / estensioni | .NET / Visual Studio |
| Integrazione VS Code | Nativa | Estensioni | Nativa / Estensioni | IDE | Non documentato | Non documentato | Non documentato |
-------------------------------------------------------------------------------------------------------------------









































# 9. Pricing Strategy & Commercial Offering

## 9.1 Obiettivo

Questo capitolo definisce la struttura dell'offerta commerciale CALIBROs, identificando i prodotti acquistabili, le relative configurazioni, le modalità di licensing e i criteri per la determinazione dei prezzi.

L'obiettivo è costruire un'offerta commerciale chiara, modulare e scalabile, capace di adattarsi alle diverse esigenze delle aziende che sviluppano, testano e mantengono applicazioni Web.

La strategia di pricing dovrà tenere conto del valore offerto dalla piattaforma, della capacità di generare ed eseguire test di carico, delle dimensioni delle organizzazioni clienti e del confronto con le soluzioni concorrenti.

## 9.2 Principi di Pricing

La strategia commerciale CALIBROs si basa sui seguenti principi:

- **Modularità:** il cliente deve poter acquistare esclusivamente i prodotti e le capacità di cui ha bisogno.
- **Scalabilità:** l'offerta deve poter crescere insieme alle esigenze del cliente, aumentando progressivamente la capacità di esecuzione.
- **Trasparenza:** le condizioni commerciali, i limiti di utilizzo e le modalità di licensing devono essere facilmente comprensibili.
- **Accessibilità:** la piattaforma deve consentire anche alle piccole e medie software house di avvicinarsi al Load Testing professionale.
- **Valorizzazione del prodotto:** il prezzo deve riflettere il valore delle funzionalità offerte e non essere determinato esclusivamente dai costi infrastrutturali.

## 9.3 Struttura dell'Offerta Commerciale

L'offerta CALIBROs è articolata in tre principali categorie:

1. **Free Product:** estensione gratuita per Visual Studio Code.
2. **Commercial Products:** prodotti On-Premise e Cloud per l'esecuzione di LoadTest e StressTest.
3. **Professional Services:** servizi professionali di consulenza, progettazione e supporto.

L'estensione gratuita rappresenta il principale canale di accesso all'ecosistema CALIBROs, mentre i prodotti commerciali e i servizi professionali costituiscono le principali fonti di ricavo.

## 9.4 Commercial Packages

### 9.4.1 Free Product

L'estensione CALIBROs per Visual Studio Code è distribuita gratuitamente.

Non sono previste limitazioni artificiali sulle funzionalità di sviluppo e debugging dei WebTest.

L'utente può utilizzare gratuitamente le funzionalità necessarie per:

- Creare e modificare WebTest.
- Configurare richieste HTTP.
- Gestire variabili, DataSource e parametri.
- Configurare validazioni.
- Ispezionare richieste e risposte HTTP.
- Eseguire e debuggare WebTest funzionali.

L'esecuzione di LoadTest e StressTest, così come la generazione di carico concorrente attraverso Virtual User, richiede invece l'utilizzo dei prodotti commerciali.

**Decisione:** l'estensione rimane completamente gratuita, senza edizioni a pagamento o limitazioni sulle funzionalità di sviluppo dei WebTest.

### 9.4.2 On-Premise

La soluzione On-Premise è destinata alle organizzazioni che desiderano eseguire i test utilizzando la propria infrastruttura.

Comprende i componenti necessari per l'esecuzione dei LoadTest:

- CLI.
- Controller.
- Agent.
- Supporto all'esecuzione distribuita.

Il modello commerciale è basato su licenze che definiscono la capacità massima di Virtual User utilizzabile.

Il cliente sostiene i costi dell'infrastruttura necessaria per l'esecuzione dei test.

### 9.4.3 Cloud

La soluzione Cloud consente di utilizzare la capacità di esecuzione messa a disposizione direttamente da CALIBROs.

Gli Agent sono ospitati nell'infrastruttura Cloud di CALIBROs, evitando al cliente la necessità di installare e gestire una propria infrastruttura di generazione del carico.

Il modello commerciale è basato su abbonamento.

La capacità disponibile, le modalità di utilizzo e le eventuali fasce di consumo dovranno essere definite nell'offerta commerciale.

### 9.4.4 Professional Services

I Professional Services costituiscono un'offerta commerciale separata dai prodotti software.

Comprendono attività di consulenza e supporto relative alla progettazione, allo sviluppo, all'esecuzione e all'analisi dei test.

I servizi possono essere acquistati direttamente da CALIBROs oppure attraverso consulenti e società partner.

Le modalità di erogazione e i relativi prezzi saranno definiti in funzione della tipologia e della complessità dell'intervento.

## 9.5 Licensing e Formule Commerciali

Le formule di licensing definiscono la durata del diritto di utilizzo e la capacità di esecuzione acquistata dal cliente.

### 9.5.1 On-Premise Licensing

Per il prodotto On-Premise sono previste le seguenti formule:

| Formula | Durata |
|---|---|
| Weekly Pass | 7 giorni |
| Monthly Subscription | 1 mese |
| Quarterly Subscription | 3 mesi |
| Annual Subscription | 12 mesi |
| Perpetual License | Senza scadenza |

Le licenze a tempo consentono di utilizzare il prodotto per il periodo acquistato, entro i limiti di capacità previsti dalla licenza.

La Perpetual License consente invece l'utilizzo senza limiti temporali della versione acquistata, mantenendo il limite di Virtual User previsto dalla licenza.

Le condizioni relative agli aggiornamenti e al supporto sono disciplinate separatamente.

### 9.5.2 Cloud Licensing

Per il prodotto Cloud è previsto un modello basato su abbonamento.

Il cliente acquista il diritto di utilizzare la capacità di esecuzione Cloud per un determinato periodo.

Le formule commerciali, le modalità di fatturazione e le eventuali opzioni di consumo dovranno essere definite.

**Open Point:** definizione delle formule Cloud e del relativo modello di fatturazione.

## 9.6 Virtual User Capacity

La capacità di esecuzione rappresenta uno dei principali elementi di differenziazione commerciale.

Il numero massimo di Virtual User determina la quantità di utenti virtuali che possono essere eseguiti contemporaneamente nell'ambito della capacità concessa dalla licenza.

Per il prodotto On-Premise, il limite di Virtual User deve essere rispettato complessivamente tra tutti gli Agent utilizzati dal cliente.

L'architettura distribuita non deve consentire di superare la capacità acquistata semplicemente aumentando il numero di Agent.

La definizione delle fasce commerciali di Virtual User dovrà consentire di soddisfare esigenze differenti, dalle attività di test di piccola scala fino agli scenari di carico più impegnativi.

**Open Point:** definizione delle fasce di capacità e dei relativi quantitativi di Virtual User.

## 9.7 Pricing Model

La determinazione dei prezzi dovrà considerare principalmente:

- Numero massimo di Virtual User.
- Durata della licenza.
- Modalità di distribuzione (On-Premise o Cloud).
- Infrastruttura necessaria per l'esecuzione.
- Costi operativi e infrastrutturali sostenuti da CALIBROs.
- Valore commerciale delle funzionalità offerte.
- Posizionamento rispetto ai prodotti concorrenti.

Per il prodotto On-Premise, il prezzo sarà principalmente correlato alla capacità di Virtual User e alla durata della licenza.

Per il prodotto Cloud, il prezzo dovrà considerare anche i costi di infrastruttura e di erogazione del servizio.

I Professional Services seguiranno invece una politica di pricing indipendente, basata sulla tipologia e sull'impegno richiesto dalle attività.

**Open Point:** definizione dei prezzi effettivi e delle relative fasce commerciali.

## 9.8 Upgrade, Renewal e Maintenance

L'offerta commerciale dovrà prevedere modalità semplici per aumentare la capacità acquistata e rinnovare le licenze.

Le principali operazioni commerciali previste sono:

- **Capacity Upgrade:** aumento del numero massimo di Virtual User.
- **License Renewal:** rinnovo di una licenza in scadenza.
- **License Extension:** estensione della durata della licenza, ove prevista.
- **Product Updates:** accesso agli aggiornamenti del prodotto secondo le condizioni commerciali applicabili.

Per le licenze perpetue, il diritto di utilizzo della versione acquistata rimane valido senza scadenza.

L'accesso alle versioni successive, agli aggiornamenti e al supporto potrà essere regolato attraverso un servizio di Maintenance separato.

**Open Point:** definizione delle politiche di upgrade, rinnovo e manutenzione.

## 9.9 Commercial Offering Evolution

L'offerta commerciale CALIBROs dovrà evolvere progressivamente sulla base delle esigenze del mercato e dell'esperienza acquisita con i primi clienti.

La strategia iniziale dovrà privilegiare una struttura semplice, evitando un numero eccessivo di pacchetti e configurazioni commerciali.

Nel tempo potranno essere introdotte nuove fasce di capacità, formule di licensing e servizi aggiuntivi, mantenendo la modularità e la trasparenza come principi fondamentali.

L'obiettivo è costruire un'offerta in grado di accompagnare il cliente dalla prima esperienza con il prodotto fino all'utilizzo professionale e su larga scala della piattaforma.

---

### Stato delle decisioni

| Argomento                                       | Stato       |
|-------------------------------------------------|-------------|
| Estensione VS Code gratuita                     | DECISIONE   |
| Prodotti commerciali On-Premise e Cloud         | DECISIONE   |
| Licensing On-Premise a tempo                    | DECISIONE   |
| Perpetual License                               | DECISIONE   |
| Licensing Cloud in abbonamento                  | DECISIONE   |
| Capacità espressa in Virtual User               | DECISIONE   |
| Fasce commerciali di Virtual User               | DA DEFINIRE |
| Pacchetti commerciali e relative configurazioni | DA DEFINIRE |
| Prezzi                                          | DA DEFINIRE |
| Upgrade e rinnovi                               | DA DEFINIRE |
| Maintenance e Support                           | DA DEFINIRE |
| Modello di fatturazione Cloud                   | DA DEFINIRE |

# 10. Target Market

## 10.1 Obiettivo

Questo capitolo identifica il mercato potenziale di CALIBROs e definisce i principali segmenti di clientela ai quali rivolgere l'offerta commerciale.

L'analisi distingue tra:

- **Target professionale:** le figure tecniche che utilizzano direttamente la piattaforma.
- **Target commerciale:** le organizzazioni che possono acquistare i prodotti e i servizi CALIBROs.
- **Influencer e promotori:** professionisti che, pur non rappresentando necessariamente clienti paganti, possono favorire la diffusione e l'adozione del prodotto.

L'obiettivo è concentrare inizialmente gli sforzi commerciali sui segmenti con maggiore probabilità di adozione, evitando di disperdere risorse su mercati che richiederebbero un cambiamento significativo nelle abitudini e nei processi aziendali.

## 10.2 Mercato di Riferimento

CALIBROs si rivolge al mercato professionale dello sviluppo software e del testing di applicazioni Web, con particolare riferimento alle organizzazioni che effettuano attività di:

- Web Testing.
- Functional Testing.
- Regression Testing.
- Performance Testing.
- Load Testing.
- Stress Testing.

Il mercato di riferimento non è costituito genericamente da tutte le aziende che sviluppano applicazioni Web.

La priorità commerciale è rappresentata dalle organizzazioni che già effettuano attività di Load Testing e che utilizzano strumenti specifici per verificare le prestazioni e il comportamento delle proprie applicazioni sotto carico.

Queste organizzazioni hanno già maturato la necessità di effettuare test prestazionali e conoscono il valore di questo tipo di attività. CALIBROs può quindi proporsi come una soluzione alternativa, senza dover prima creare nel cliente la consapevolezza dell'importanza del Load Testing.

## 10.3 Target Professionale

Le principali figure professionali che possono utilizzare CALIBROs sono:

### 10.3.1 Web Developer

Sviluppatori che realizzano e mantengono applicazioni Web e che necessitano di strumenti per creare, eseguire e debuggare test funzionali e di regressione.

Rappresentano un segmento importante per l'adozione dell'estensione gratuita di Visual Studio Code.

### 10.3.2 Performance Engineer

Professionisti specializzati nell'analisi delle prestazioni delle applicazioni e nella progettazione, esecuzione e valutazione dei test di carico.

Costituiscono uno dei principali utilizzatori professionali dei prodotti commerciali CALIBROs.

### 10.3.3 QA Engineer e Software Tester

Professionisti che si occupano della qualità del software e delle attività di testing.

Possono utilizzare CALIBROs per sviluppare e mantenere WebTest funzionali e di regressione, oltre che per collaborare alle attività di Performance e Load Testing.

## 10.4 Segmentazione del Target Commerciale

Il mercato commerciale viene suddiviso in quattro segmenti principali, caratterizzati da differenti livelli di priorità.

### 10.4.1 Piccole e Medie Software House

**Priorità: ALTA**

Rappresentano il principale segmento commerciale di riferimento per CALIBROs.

Sono organizzazioni che sviluppano applicazioni Web per clienti propri o terzi e che dispongono di competenze tecniche interne dedicate allo sviluppo e al testing.

La priorità è rivolta in particolare alle software house che:

- Effettuano già attività di Load Testing.
- Utilizzano strumenti commerciali o open source per i test prestazionali.
- Necessitano di strumenti per sviluppare e mantenere test funzionali e di carico.
- Sono interessate a migliorare l'integrazione tra sviluppo software e testing.
- Cercano alternative agli strumenti attualmente utilizzati.

Questo segmento rappresenta il principale potenziale bacino di clienti per i prodotti On-Premise e Cloud.

### 10.4.2 Organizzazioni che utilizzano già strumenti di Load Testing

**Priorità: ALTA**

Questo segmento comprende aziende che hanno già adottato strumenti specifici per il Load Testing e che dispongono di processi consolidati per la verifica delle prestazioni delle applicazioni.

All'interno di questo segmento assumono particolare rilevanza gli ex utilizzatori di Microsoft Visual Studio Web Performance and Load Test, prodotto ormai dismesso.

Questi utenti rappresentano un'opportunità interessante perché conoscono già il modello di lavoro basato sulla creazione, gestione ed esecuzione di WebTest e LoadTest.

CALIBROs intende offrire a questo pubblico un ambiente di sviluppo moderno, basato su Visual Studio Code e tecnologie .NET, con particolare attenzione all'esperienza di sviluppo e debugging.

Il segmento comprende anche organizzazioni che utilizzano altre piattaforme di Load Testing e che potrebbero valutare CALIBROs come alternativa.

### 10.4.3 Grandi Aziende ed Enterprise

**Priorità: MEDIA – SVILUPPO FUTURO**

Le grandi organizzazioni rappresentano un potenziale mercato di espansione.

Possono avere esigenze significative in termini di:

- Test prestazionali su applicazioni critiche.
- Esecuzione distribuita dei test.
- Elevato numero di Virtual User.
- Integrazione con infrastrutture e processi aziendali.
- Gestione centralizzata delle attività di testing.

Tuttavia, l'accesso a questo segmento potrebbe richiedere un livello di notorietà, credibilità commerciale e maturità del prodotto superiore a quello necessario per acquisire piccole e medie software house.

Per questo motivo, le grandi aziende non rappresentano il principale obiettivo della fase iniziale, ma un segmento da sviluppare progressivamente.

### 10.4.4 Società di Consulenza e Performance Testing

**Priorità: DA VALUTARE**

Le società specializzate in consulenza, Quality Assurance e Performance Testing possono rappresentare un segmento interessante.

Queste organizzazioni potrebbero utilizzare CALIBROs per svolgere attività di testing presso i propri clienti oppure proporre la piattaforma come parte dei servizi professionali offerti.

Potrebbero inoltre diventare partner commerciali o tecnici per la diffusione del prodotto.

L'effettivo interesse di questo segmento e le relative modalità di collaborazione dovranno essere approfonditi.

## 10.5 Sviluppatori Individuali e Freelance

**Ruolo: ADOZIONE E DIFFUSIONE**

Gli sviluppatori individuali e i professionisti freelance non rappresentano il principale target di monetizzazione diretta.

Potranno utilizzare gratuitamente l'estensione CALIBROs per Visual Studio Code, sperimentandone le funzionalità e adottandola nelle proprie attività professionali.

Questo segmento riveste comunque un ruolo importante nella strategia di diffusione del prodotto.

Gli sviluppatori individuali possono:

- Conoscere e sperimentare CALIBROs.
- Contribuire alla diffusione della piattaforma.
- Promuoverne l'utilizzo presso le software house con cui collaborano.
- Favorirne l'adozione all'interno delle organizzazioni.

L'estensione gratuita rappresenta quindi uno strumento di acquisizione e diffusione, anche in assenza di una conversione commerciale diretta del singolo utilizzatore.

## 10.6 Priorità dei Segmenti di Mercato

La seguente tabella riassume la segmentazione e le relative priorità commerciali.

| Segmento | Priorità | Ruolo |
|---|---|---|
| Piccole e medie software house che effettuano Load Testing | Alta | Clienti commerciali principali |
| Organizzazioni che utilizzano già strumenti di Load Testing | Alta | Potenziali clienti e utilizzatori |
| Ex utenti Microsoft Visual Studio Web Load Test | Alta | Segmento prioritario per l'acquisizione |
| Grandi aziende ed Enterprise | Media | Espansione futura |
| Società di consulenza e Performance Testing | Da valutare | Clienti e potenziali partner |
| Sviluppatori individuali e Freelance | Diffusione | Utilizzatori dell'estensione gratuita e promotori |

## 10.7 Esclusioni e Non-Priorità

Nella fase iniziale, CALIBROs non intende rivolgersi prioritariamente alle organizzazioni che non effettuano attività di Load Testing e che non hanno una necessità concreta di questo tipo di soluzione.

L'acquisizione di questi clienti richiederebbe infatti un'attività preliminare di sensibilizzazione, formazione e introduzione di nuovi processi aziendali.

La strategia iniziale privilegia invece organizzazioni che conoscono già il Load Testing e che possono valutare CALIBROs sulla base delle funzionalità, dell'esperienza di utilizzo e del valore offerto.

## 10.8 Evoluzione del Target Market

Il mercato di riferimento potrà essere progressivamente ampliato sulla base dei risultati ottenuti nella fase iniziale di commercializzazione.

La strategia prevede di:

1. Concentrarsi sulle piccole e medie software house che effettuano già Load Testing.
2. Intercettare gli utilizzatori di strumenti concorrenti e gli ex utenti Microsoft Visual Studio Web Load Test.
3. Sviluppare la diffusione dell'estensione gratuita tra gli sviluppatori.
4. Valutare collaborazioni con società di consulenza e Performance Testing.
5. Estendere progressivamente la presenza commerciale verso le grandi organizzazioni.

Questa evoluzione consentirà di costruire una base iniziale di utilizzatori e clienti, consolidando la credibilità del prodotto prima di affrontare segmenti di mercato più complessi.

# 11. Go-to-Market Strategy

## 11.1 Obiettivo

Questo capitolo definisce la strategia attraverso la quale CALIBROs intende entrare nel mercato, acquisire i primi utilizzatori e sviluppare progressivamente la propria presenza commerciale.

L'obiettivo iniziale non è raggiungere immediatamente un mercato molto ampio, ma individuare segmenti di clientela con esigenze già consolidate di Web Testing, Performance Testing e Load Testing.

La strategia dovrà consentire di:

- Far conoscere CALIBROs alla comunità professionale di riferimento.
- Favorire l'adozione dell'estensione gratuita per Visual Studio Code.
- Individuare organizzazioni interessate ai prodotti commerciali.
- Acquisire i primi clienti paganti.
- Costruire credibilità e referenze commerciali.
- Sviluppare progressivamente un ecosistema di utilizzatori e partner.

## 11.2 Strategia di Ingresso nel Mercato

La strategia di ingresso si basa su un approccio progressivo, partendo dagli utilizzatori tecnicamente più vicini al prodotto.

CALIBROs non intende inizialmente rivolgersi indistintamente a tutte le organizzazioni che sviluppano applicazioni Web.

La priorità sarà raggiungere professionisti e aziende che:

- Effettuano già attività di Load Testing.
- Utilizzano strumenti specifici per il Performance Testing.
- Hanno utilizzato Microsoft Visual Studio Web Performance and Load Test.
- Sono interessati a modernizzare i propri strumenti di testing.
- Cercano un ambiente di sviluppo integrato con Visual Studio Code e tecnologie .NET.

Questo approccio consente di rivolgersi a un pubblico che conosce già il problema che CALIBROs intende risolvere.

## 11.3 Free Product as Acquisition Channel

L'estensione gratuita per Visual Studio Code rappresenta uno degli elementi centrali della strategia di ingresso nel mercato.

La possibilità di utilizzare gratuitamente le funzionalità di sviluppo, debugging ed esecuzione dei WebTest consente agli sviluppatori di conoscere CALIBROs senza dover affrontare inizialmente una decisione di acquisto.

La strategia prevede che l'estensione gratuita venga utilizzata come principale canale di acquisizione degli utilizzatori.

Il percorso di adozione previsto è il seguente:

1. Lo sviluppatore scopre CALIBROs.
2. Installa gratuitamente l'estensione per Visual Studio Code.
3. Inizia a creare, modificare ed eseguire WebTest funzionali.
4. Familiarizza con l'ambiente di sviluppo e le funzionalità di debugging.
5. Quando emerge la necessità di eseguire LoadTest o StressTest, può valutare i prodotti commerciali.
6. L'organizzazione presso cui lavora può diventare un potenziale cliente CALIBROs.

L'estensione gratuita costituisce quindi un punto di ingresso nell'ecosistema commerciale, senza imporre allo sviluppatore un acquisto iniziale.

## 11.4 Early Adopters

La prima fase di commercializzazione dovrà concentrarsi sull'individuazione di un gruppo ristretto di utilizzatori e organizzazioni potenzialmente interessati al prodotto.

Gli Early Adopters rappresentano un elemento fondamentale per verificare la validità della proposta commerciale e raccogliere indicazioni concrete sull'utilizzo della piattaforma.

I segmenti prioritari sono:

- Ex utilizzatori di Microsoft Visual Studio Web Performance and Load Test.
- Software house che effettuano già attività di Load Testing.
- Performance Engineer e QA Engineer.
- Società specializzate in Performance Testing.
- Sviluppatori interessati a strumenti evoluti per il Web Testing.

In questa fase sarà importante raccogliere feedback relativi a funzionalità, usabilità, prestazioni, installazione, configurazione e modalità di licensing.

L'obiettivo non è soltanto ottenere i primi utilizzatori, ma individuare organizzazioni disposte a sperimentare concretamente i prodotti commerciali.

## 11.5 Commercial Conversion Strategy

La conversione commerciale dovrà avvenire principalmente quando l'utilizzatore manifesta la necessità di funzionalità non disponibili nell'estensione gratuita.

In particolare, il passaggio all'offerta commerciale avviene quando emerge la necessità di:

- Eseguire LoadTest e StressTest.
- Generare carico attraverso Virtual User concorrenti.
- Distribuire l'esecuzione su più Agent.
- Utilizzare infrastrutture dedicate per l'esecuzione dei test.
- Accedere alla capacità di generazione del carico offerta dalla soluzione Cloud.

Il percorso commerciale dovrà essere il più possibile naturale.

L'utilizzatore conosce già CALIBROs, ha familiarità con l'ambiente di sviluppo e può quindi valutare i prodotti commerciali senza dover introdurre una piattaforma completamente nuova nei propri processi.

La conversione potrà avvenire attraverso l'acquisto diretto dei prodotti On-Premise o Cloud, oppure attraverso un primo intervento di Professional Services.

## 11.6 Initial Commercial Focus

Nella fase iniziale, gli sforzi commerciali dovranno concentrarsi su un numero limitato di segmenti.

La priorità sarà assegnata a:

1. Piccole e medie software house che effettuano già Load Testing.
2. Organizzazioni che utilizzano strumenti concorrenti.
3. Ex utilizzatori di Microsoft Visual Studio Web Load Test.
4. Società di consulenza specializzate in Performance Testing.

Le grandi organizzazioni potranno essere affrontate successivamente, quando CALIBROs avrà acquisito una maggiore presenza sul mercato, referenze commerciali e una consolidata esperienza di utilizzo.

## 11.7 Partnership Strategy

La crescita commerciale potrà essere supportata dalla collaborazione con consulenti indipendenti e società specializzate in testing e Performance Engineering.

I partner potranno contribuire alla diffusione di CALIBROs attraverso:

- Presentazione della piattaforma ai propri clienti.
- Utilizzo dei prodotti CALIBROs nei progetti di consulenza.
- Erogazione di Professional Services.
- Supporto all'adozione della piattaforma.
- Individuazione di nuove opportunità commerciali.

Il modello di collaborazione dovrà rimanere flessibile, consentendo sia l'acquisizione diretta dei clienti da parte di CALIBROs sia lo sviluppo di opportunità attraverso partner esterni.

## 11.8 Go-to-Market Phases

L'ingresso nel mercato viene articolato in quattro fasi evolutive.

### Phase 1 – Product Introduction

Obiettivo: rendere CALIBROs disponibile e far conoscere il prodotto al pubblico tecnico di riferimento.

Attività principali:

- Pubblicazione dell'estensione gratuita per Visual Studio Code.
- Presentazione delle principali funzionalità.
- Disponibilità della documentazione tecnica.
- Coinvolgimento dei primi sviluppatori.
- Raccolta dei primi feedback.

### Phase 2 – Early Adoption

Obiettivo: costruire una prima base di utilizzatori e individuare le prime organizzazioni interessate.

Attività principali:

- Coinvolgimento di software house e professionisti.
- Attività dimostrative sui principali scenari di utilizzo.
- Raccolta di feedback strutturati.
- Individuazione dei primi casi d'uso reali.
- Verifica dell'interesse verso i prodotti commerciali.

### Phase 3 – Commercial Launch

Obiettivo: avviare la commercializzazione dei prodotti On-Premise e Cloud.

Attività principali:

- Presentazione dell'offerta commerciale.
- Disponibilità delle formule di licensing.
- Acquisizione dei primi clienti paganti.
- Attivazione dei primi contratti di Professional Services.
- Raccolta delle prime referenze commerciali.

### Phase 4 – Market Expansion

Obiettivo: ampliare progressivamente la presenza commerciale.

Attività principali:

- Sviluppo di collaborazioni con partner.
- Ampliamento della base clienti.
- Consolidamento della presenza nei segmenti prioritari.
- Accesso progressivo al mercato Enterprise.
- Evoluzione dell'offerta commerciale sulla base delle esigenze rilevate.

## 11.9 Success Metrics

L'efficacia della strategia Go-to-Market dovrà essere valutata attraverso indicatori che misurino sia la diffusione del prodotto sia i risultati commerciali.

I principali indicatori da monitorare saranno:

| Indicatore | Obiettivo |
|---|---|
| Download dell'estensione | Misurare la diffusione iniziale |
| Installazioni attive | Misurare l'adozione effettiva |
| Utilizzatori ricorrenti | Valutare il coinvolgimento degli sviluppatori |
| Organizzazioni utilizzatrici | Misurare la diffusione aziendale |
| Richieste di informazioni commerciali | Misurare l'interesse verso i prodotti a pagamento |
| Conversioni commerciali | Misurare il passaggio da utilizzatore gratuito a cliente |
| Clienti paganti | Misurare l'acquisizione commerciale |
| Ricavi ricorrenti | Valutare la sostenibilità del modello commerciale |
| Partnership attive | Misurare lo sviluppo dell'ecosistema commerciale |

Gli indicatori dovranno essere monitorati nel tempo e utilizzati per correggere la strategia di acquisizione e commercial

# 12. Marketing Strategy

## 12.1 Obiettivo

Questo capitolo definisce la strategia di comunicazione e promozione di CALIBROs, con l'obiettivo di costruire visibilità, riconoscibilità e credibilità nel mercato professionale del Web Testing e del Performance Testing.

La strategia di marketing dovrà:

- Far conoscere CALIBROs al pubblico professionale di riferimento.
- Comunicare chiaramente la proposta di valore della piattaforma.
- Evidenziare gli elementi distintivi rispetto alle soluzioni concorrenti.
- Favorire la diffusione dell'estensione gratuita per Visual Studio Code.
- Generare interesse verso i prodotti commerciali.
- Costruire una reputazione tecnica e commerciale nel settore.

Il marketing dovrà supportare la strategia Go-to-Market, contribuendo alla generazione di opportunità commerciali e alla crescita dell'ecosistema di utilizzatori.

## 12.2 Brand Positioning

CALIBROs intende posizionarsi come una piattaforma professionale per lo sviluppo, il debugging e l'esecuzione di WebTest, LoadTest e StressTest.

Il posizionamento dovrà differenziarsi dagli strumenti tradizionali di Load Testing, valorizzando soprattutto l'esperienza di sviluppo offerta dalla piattaforma.

Gli elementi distintivi da comunicare sono:

- **Developer Experience:** un ambiente progettato per gli sviluppatori, non soltanto per configurare ed eseguire test.
- **Integrated Debugging:** funzionalità di debugging, breakpoint e ispezione delle variabili.
- **Request Inspection:** strumenti per analizzare richieste e risposte HTTP.
- **.NET Extensibility:** possibilità di estendere le funzionalità attraverso codice .NET.
- **VS Code Integration:** integrazione con un ambiente di sviluppo conosciuto e utilizzato dai professionisti.
- **Functional and Load Testing:** possibilità di sviluppare WebTest funzionali e utilizzarli come base per i LoadTest.

Il messaggio centrale dovrà evidenziare che CALIBROs non è soltanto un motore di generazione del carico, ma un ambiente di lavoro completo per chi sviluppa e gestisce test Web.

## 12.3 Value Proposition e Key Messages

La comunicazione commerciale dovrà essere costruita intorno a una proposta di valore semplice e riconoscibile.

La principale idea da trasmettere è:

**CALIBROs porta l'esperienza dello sviluppo software professionale nel mondo del Web Testing e del Load Testing.**

I messaggi principali da sviluppare sono:

### Developer-Centric Testing

Il testing viene trattato come un'attività di sviluppo software, con strumenti e funzionalità familiari agli sviluppatori.

### Debugging First

Breakpoint, ispezione delle variabili e debugging permettono di comprendere il comportamento dei test e individuare più facilmente eventuali problemi.

### One Workflow, Multiple Testing Scenarios

I WebTest possono essere sviluppati e utilizzati sia per verifiche funzionali e di regressione sia come base per scenari di Load Testing.

### Extensible with .NET

La possibilità di utilizzare codice .NET consente di estendere i test e implementare comportamenti personalizzati.

### Start Free, Scale Professionally

L'estensione gratuita permette di iniziare a utilizzare CALIBROs senza costi. Quando emergono esigenze di Load Testing e Stress Testing, è possibile passare ai prodotti commerciali.

## 12.4 Target Communication

La comunicazione dovrà essere adattata ai diversi destinatari identificati nel capitolo Target Market.

| Destinatario | Messaggio principale |
|---|---|
| Web Developer | Un ambiente professionale per sviluppare e debuggare WebTest |
| Performance Engineer | Uno strumento evoluto per progettare ed eseguire LoadTest |
| QA Engineer | Un unico ambiente per WebTest funzionali e di regressione |
| Software House | Una piattaforma integrabile nei processi di sviluppo e testing |
| Ex utenti Visual Studio Web Load Test | Un'alternativa moderna per il Web Testing e il Load Testing |
| Società di consulenza | Una piattaforma utilizzabile nei progetti di testing dei propri clienti |

La comunicazione dovrà mantenere un'identità coerente, adattando il livello di approfondimento tecnico e i benefici evidenziati in funzione del pubblico.

## 12.5 Content Marketing

Il Content Marketing rappresenterà uno dei principali strumenti per costruire autorevolezza e visibilità.

CALIBROs opera in un settore tecnico nel quale contenuti concreti, dimostrazioni e approfondimenti possono avere un valore superiore alla comunicazione puramente promozionale.

I contenuti potranno includere:

- Articoli tecnici sul Web Testing e sul Load Testing.
- Tutorial per utilizzare CALIBROs.
- Guide alla creazione e al debugging dei WebTest.
- Approfondimenti sulle funzionalità della piattaforma.
- Esempi di utilizzo del codice .NET nei test.
- Confronti tra differenti approcci al Performance Testing.
- Analisi di scenari reali di testing.
- Best practice per la progettazione e l'esecuzione dei test di carico.

L'obiettivo è produrre contenuti utili anche dal punto di vista tecnico, in grado di attirare professionisti interessati agli argomenti trattati e far conoscere progressivamente CALIBROs.

## 12.6 Website e Brand Communication

Il sito ufficiale CALIBROs dovrà rappresentare il principale punto di riferimento per la comunicazione istituzionale e commerciale.

Dovrà consentire ai visitatori di comprendere rapidamente:

- Che cos'è CALIBROs.
- Quali problemi intende risolvere.
- Quali sono le sue caratteristiche distintive.
- Quali prodotti sono disponibili.
- Quali sono le differenze tra Free Product, On-Premise e Cloud.
- Come iniziare a utilizzare la piattaforma.
- Come ottenere informazioni commerciali e supporto.

Il sito dovrà prevedere una presentazione chiara della piattaforma, pagine dedicate ai singoli prodotti, documentazione, tutorial e riferimenti per i contatti commerciali.

La comunicazione dovrà mantenere coerenza tra identità visiva, terminologia, messaggi e presentazione dei prodotti.

## 12.7 Social Media e Community

La presenza sui canali social dovrà essere orientata principalmente alla comunità tecnica e professionale.

I canali potranno essere utilizzati per:

- Presentare nuove funzionalità.
- Pubblicare articoli e tutorial.
- Condividere dimostrazioni del prodotto.
- Annunciare aggiornamenti e nuove versioni.
- Interagire con sviluppatori e professionisti del testing.
- Raccogliere feedback e suggerimenti.

Particolare attenzione potrà essere dedicata a LinkedIn, per raggiungere professionisti e organizzazioni, e a GitHub, per favorire il coinvolgimento della comunità tecnica.

La scelta definitiva dei canali e il livello di presenza da mantenere dovranno essere definiti in funzione delle risorse disponibili e dei risultati ottenuti.

## 12.8 Product Demonstrations e Video

La dimostrazione concreta delle funzionalità rappresenta uno strumento particolarmente importante per CALIBROs.

Le caratteristiche distintive della piattaforma, soprattutto quelle relative al debugging e all'esperienza di sviluppo, possono essere comunicate in modo più efficace attraverso dimostrazioni pratiche.

I contenuti video potranno mostrare:

- Creazione di un nuovo WebTest.
- Configurazione delle richieste HTTP.
- Utilizzo di variabili e DataSource.
- Esecuzione e debugging di un WebTest.
- Utilizzo dei breakpoint e ispezione delle variabili.
- Analisi delle richieste e delle risposte HTTP.
- Estensione dei test attraverso codice .NET.
- Creazione ed esecuzione di un LoadTest.

I video dovranno privilegiare scenari reali e dimostrazioni dirette, evitando presentazioni esclusivamente teoriche o promozionali.

## 12.9 Events, Webinars e Technical Outreach

La partecipazione a eventi e iniziative tecniche potrà contribuire alla diffusione di CALIBROs e alla costruzione di relazioni con potenziali clienti e partner.

Le attività potranno comprendere:

- Webinar tecnici.
- Presentazioni online del prodotto.
- Sessioni dimostrative.
- Partecipazione a conferenze sullo sviluppo software e sul testing.
- Incontri con community di sviluppatori.
- Collaborazioni con professionisti del Performance Engineering.

Queste iniziative potranno essere sviluppate progressivamente, privilegiando inizialmente modalità a basso costo e con un pubblico altamente specializzato.

## 12.10 Competitive Communication

La comunicazione di CALIBROs dovrà evidenziare i propri elementi distintivi rispetto alle altre piattaforme di Load Testing.

Il confronto competitivo dovrà essere basato su caratteristiche verificabili e dimostrabili, evitando affermazioni generiche o confronti non supportati da evidenze.

Particolare attenzione dovrà essere dedicata a:

- Esperienza di sviluppo e debugging.
- Gestione e ispezione dei WebTest.
- Integrazione con Visual Studio Code.
- Estensibilità attraverso codice .NET.
- Riutilizzo dei WebTest per differenti scenari di testing.
- Modalità di distribuzione e licensing.

La comunicazione competitiva dovrà valorizzare ciò che rende CALIBROs differente, senza basarsi esclusivamente sul confronto dei prezzi o sul numero di funzionalità.

## 12.11 Brand Identity e Visual Communication

CALIBROs dovrà sviluppare un'identità visiva riconoscibile e coerente con il proprio posizionamento tecnologico.

Gli elementi da definire comprendono:

- Logo e simbolo identificativo.
- Palette cromatica.
- Tipografia.
- Stile grafico del sito.
- Identità visiva dell'estensione e dei prodotti commerciali.
- Template per presentazioni e materiale promozionale.
- Stile grafico dei contenuti social e dei video.

L'identità dovrà trasmettere professionalità, affidabilità, precisione e attenzione all'esperienza degli sviluppatori.

## 12.12 Marketing Performance e KPI

Le attività di marketing dovranno essere monitorate attraverso indicatori che consentano di valutare la visibilità raggiunta, l'interesse generato e il contributo alle attività commerciali.

I principali indicatori da considerare sono:

| Indicatore | Obiettivo |
|---|---|
| Visite al sito | Misurare la visibilità del brand |
| Download dell'estensione | Misurare l'interesse verso il prodotto gratuito |
| Visualizzazioni dei video | Valutare l'efficacia delle dimostrazioni |
| Letture degli articoli | Misurare l'interesse verso i contenuti tecnici |
| Interazioni sui social | Valutare il coinvolgimento della comunità |
| Iscrizioni ai webinar | Misurare l'interesse verso le iniziative tecniche |
| Richieste di informazioni | Misurare l'interesse commerciale generato |
| Lead qualificati | Valutare le opportunità commerciali generate |

Gli indicatori dovranno essere analizzati periodicamente per individuare i canali e i contenuti maggiormente efficaci.

## 12.13 Marketing Strategy Evolution

La strategia di marketing dovrà evolvere insieme alla maturità del prodotto e alla sua presenza sul mercato.

Nella fase iniziale sarà opportuno privilegiare attività di comunicazione tecnica, contenuti dimostrativi e iniziative rivolte direttamente agli sviluppatori e ai professionisti del testing.

Con la crescita della base di utilizzatori e l'acquisizione dei primi clienti, potranno essere introdotte attività promozionali più strutturate, campagne commerciali, partecipazione a eventi e collaborazioni con partner.

L'obiettivo è costruire progressivamente un brand riconoscibile nel mercato del Web Testing e del Performance Testing, associato a un'esperienza di sviluppo professionale e a strumenti evoluti per il debugging e l'esecuzione dei test.

---

### Stato delle decisioni

| Argomento | Stato |
|---|---|
| Posizionamento Developer-Centric | PROPOSTA |
| Valorizzazione del debugging come elemento distintivo | PROPOSTA |
| Content Marketing tecnico | PROPOSTA |
| Sito ufficiale come punto di riferimento | PROPOSTA |
| Presenza su LinkedIn e GitHub | PROPOSTA |
| Produzione di video dimostrativi | PROPOSTA |
| Webinar ed eventi tecnici | PROPOSTA |
| Identità visiva coordinata | DA DEFINIRE |
| Piano editoriale e frequenza di pubblicazione | DA DEFINIRE |
| Budget marketing | DA DEFINIRE |
| KPI e strumenti di misurazione | DA DEFINIRE |
+# 13. Distribution Strategy

## 13.1 Obiettivo

Questo capitolo definisce la strategia di distribuzione dei prodotti CALIBROs, identificando i canali attraverso i quali gli utenti potranno ottenere, installare, aggiornare e utilizzare la piattaforma.

L'obiettivo è rendere i prodotti facilmente accessibili, garantendo al tempo stesso un processo di distribuzione professionale, sicuro e coerente con le diverse modalità di utilizzo.

La strategia dovrà considerare le specificità dei tre principali ambiti dell'offerta:

- Free Product: estensione per Visual Studio Code.
- Commercial Products: componenti software On-Premise e servizi Cloud.
- Professional Services: servizi professionali erogati direttamente o attraverso partner.

## 13.2 Distribution Channels

La distribuzione CALIBROs sarà articolata attraverso differenti canali, in funzione del prodotto e del pubblico di riferimento.

I principali canali previsti sono:

- **Visual Studio Code Marketplace:** distribuzione dell'estensione gratuita.
- **Official CALIBROs Website:** punto di accesso centrale per prodotti, download, documentazione e informazioni commerciali.
- **Software Distribution Platform:** distribuzione dei componenti commerciali e dei relativi aggiornamenti.
- **Cloud Platform:** accesso ai servizi Cloud CALIBROs.
- **Partner Channel:** distribuzione e promozione attraverso consulenti e organizzazioni partner.

## 13.3 Visual Studio Code Extension Distribution

L'estensione CALIBROs per Visual Studio Code sarà distribuita attraverso il Visual Studio Code Marketplace.

Questo canale rappresenta il principale punto di accesso per gli sviluppatori interessati a utilizzare gratuitamente la piattaforma.

La distribuzione attraverso il Marketplace consentirà di:

- Rendere l'estensione facilmente individuabile dagli utenti.
- Semplificare installazione e aggiornamento.
- Raggiungere direttamente la comunità degli sviluppatori.
- Pubblicare nuove versioni in modo centralizzato.
- Presentare descrizione, funzionalità e documentazione del prodotto.

La pagina dell'estensione dovrà contenere una presentazione chiara delle funzionalità, immagini dimostrative, istruzioni di installazione e riferimenti alla documentazione ufficiale.

L'estensione dovrà mantenere un processo di rilascio regolare e controllato, con versioni identificabili e informazioni sulle modifiche introdotte.

**Decisione:** il Visual Studio Code Marketplace sarà il canale ufficiale di distribuzione dell'estensione gratuita.

## 13.4 On-Premise Software Distribution

I prodotti CALIBROs On-Premise saranno distribuiti attraverso il sito ufficiale o una piattaforma dedicata alla distribuzione del software.

La distribuzione dovrà comprendere i componenti necessari per installare e utilizzare la soluzione:

- CLI.
- Controller.
- Agent.
- Dipendenze e componenti runtime necessari.
- Strumenti di configurazione e gestione.

I pacchetti dovranno essere organizzati in modo da semplificare l'installazione e la gestione delle diverse componenti.

La distribuzione dovrà prevedere:

- Download dei pacchetti software.
- Identificazione delle versioni disponibili.
- Documentazione di installazione e configurazione.
- Informazioni sulle dipendenze.
- Istruzioni per l'attivazione delle licenze.
- Procedure di aggiornamento.

I componenti dovranno poter essere installati nell'infrastruttura del cliente, senza richiedere che i dati dei test o delle applicazioni sottoposte a verifica vengano trasferiti all'infrastruttura CALIBROs.

## 13.5 Cloud Distribution

Il prodotto CALIBROs Cloud sarà erogato attraverso l'infrastruttura gestita direttamente da CALIBROs.

Il cliente non dovrà installare o amministrare gli Agent Cloud, che saranno gestiti centralmente dalla piattaforma.

La distribuzione del servizio dovrà prevedere:

- Accesso al servizio attraverso il sito o il portale CALIBROs.
- Gestione delle credenziali e delle autorizzazioni.
- Attivazione e gestione degli abbonamenti.
- Accesso alla capacità di esecuzione acquistata.
- Informazioni sullo stato del servizio e sulle risorse disponibili.

L'esperienza di utilizzo dovrà essere integrata con gli strumenti locali del cliente, in particolare con l'estensione Visual Studio Code e gli eventuali componenti client necessari.

**Open Point:** definizione delle modalità tecniche di connessione e utilizzo degli Agent Cloud.

## 13.6 Official Website

Il sito ufficiale CALIBROs rappresenterà il punto di riferimento centrale per la distribuzione e la presentazione dell'intero ecosistema.

Dovrà consentire agli utenti di:

- Conoscere la piattaforma e i suoi prodotti.
- Accedere alla documentazione.
- Scaricare i componenti software.
- Consultare le versioni disponibili.
- Accedere alle informazioni sulle licenze.
- Acquistare o richiedere informazioni sui prodotti commerciali.
- Accedere ai servizi Cloud.
- Richiedere supporto tecnico e commerciale.

Il sito dovrà distinguere chiaramente i prodotti gratuiti da quelli commerciali e guidare l'utente verso il canale di distribuzione appropriato.

Dovrà inoltre rappresentare il punto di accesso alla documentazione tecnica, alle guide, ai tutorial e alle informazioni relative alle nuove versioni.

## 13.7 Software Packaging

I componenti CALIBROs dovranno essere distribuiti attraverso pacchetti software strutturati, versionati e facilmente identificabili.

La strategia di packaging dovrà garantire:

- Identificazione univoca del prodotto.
- Versionamento coerente dei componenti.
- Inclusione delle dipendenze necessarie.
- Facilità di installazione e aggiornamento.
- Integrità dei pacchetti distribuiti.
- Compatibilità tra le diverse componenti della piattaforma.

Dovranno essere valutati i formati di distribuzione più appropriati per i diversi componenti, tenendo conto delle piattaforme operative supportate e delle modalità di installazione previste.

Particolare attenzione dovrà essere dedicata alla distribuzione degli Agent, che potranno essere installati su più macchine nell'ambito delle architetture di esecuzione distribuita.

**Open Point:** definizione dei formati ufficiali dei pacchetti e delle relative modalità di installazione.

## 13.8 Versioning e Software Updates

CALIBROs dovrà adottare una strategia di versionamento uniforme per i propri prodotti e componenti.

Ogni rilascio dovrà essere identificabile attraverso una versione e accompagnato dalle relative informazioni sulle modifiche introdotte.

Il processo di aggiornamento dovrà prevedere:

- Pubblicazione delle nuove versioni.
- Disponibilità delle Release Notes.
- Documentazione delle modifiche.
- Indicazione di eventuali incompatibilità.
- Procedure di aggiornamento.
- Gestione delle dipendenze tra componenti.

Per i componenti On-Premise, gli aggiornamenti saranno resi disponibili attraverso i canali ufficiali di distribuzione.

Per l'estensione VS Code, il processo di aggiornamento sarà gestito attraverso il Marketplace.

Per i servizi Cloud, gli aggiornamenti saranno gestiti direttamente da CALIBROs.

Le politiche di accesso agli aggiornamenti dovranno rispettare le condizioni di licensing e manutenzione definite nell'offerta commerciale.

## 13.9 Software Security and Integrity

La distribuzione dei prodotti CALIBROs dovrà garantire l'autenticità e l'integrità del software.

I principali requisiti da considerare sono:

- Distribuzione attraverso canali ufficiali.
- Protezione dei pacchetti durante il trasferimento.
- Verifica dell'integrità dei file distribuiti.
- Firma digitale degli eseguibili e dei pacchetti, ove applicabile.
- Controllo delle versioni pubblicate.
- Protezione delle informazioni relative alle licenze.

Particolare attenzione dovrà essere dedicata ai componenti commerciali, affinché il cliente possa verificare che il software installato provenga effettivamente da CALIBROs.

## 13.10 Partner Distribution

La strategia di distribuzione potrà prevedere il coinvolgimento di partner commerciali e tecnici.

I partner potranno contribuire alla diffusione dei prodotti attraverso:

- Presentazione di CALIBROs ai propri clienti.
- Supporto all'installazione e alla configurazione.
- Distribuzione dei riferimenti ai canali ufficiali.
- Erogazione di servizi professionali.
- Supporto alla fase di adozione.

La distribuzione del software dovrà comunque mantenere un riferimento centralizzato ai canali ufficiali CALIBROs, in modo da garantire uniformità delle versioni e controllo sull'origine dei pacchetti.

Le modalità di rivendita, distribuzione diretta e gestione delle licenze attraverso i partner saranno definite nell'ambito degli accordi commerciali.

## 13.11 Distribution Strategy Evolution

La strategia di distribuzione dovrà evolvere insieme alla maturità della piattaforma e alla crescita della base clienti.

Nella fase iniziale sarà opportuno privilegiare canali semplici e facilmente gestibili:

1. Visual Studio Code Marketplace per l'estensione gratuita.
2. Sito ufficiale per la presentazione e la distribuzione dei prodotti commerciali.
3. Download centralizzato dei componenti On-Premise.
4. Accesso diretto ai servizi Cloud.

Con la crescita della piattaforma potranno essere introdotti sistemi più evoluti per la gestione dei download, degli aggiornamenti, delle licenze e degli acquisti.

L'obiettivo è costruire un sistema di distribuzione affidabile e scalabile, in grado di supportare sia l'adozione individuale dell'estensione gratuita sia l'utilizzo professionale dei prodotti commerciali.

---

### Stato delle decisioni

| Argomento | Stato |
|---|---|
| Visual Studio Code Marketplace per l'estensione | DECISIONE |
| Sito ufficiale CALIBROs | DECISIONE STRATEGICA |
| Distribuzione On-Premise attraverso canali ufficiali | PROPOSTA |
| Erogazione Cloud gestita da CALIBROs | DECISIONE |
| Versionamento dei prodotti | PROPOSTA |
| Distribuzione centralizzata degli aggiornamenti | PROPOSTA |
| Firma digitale e verifica di integrità | PROPOSTA |
| Formati dei pacchetti software | DA DEFINIRE |
| Modalità di acquisto online | DA DEFINIRE |
| Portale clienti e gestione download | DA DEFINIRE |
| Distribuzione e rivendita attraverso partner | DA DEFINIRE |

# 13. Distribution Strategy

## 13.1 Obiettivo

Questo capitolo definisce la strategia di distribuzione dei prodotti CALIBROs, identificando i canali attraverso i quali gli utenti potranno ottenere, installare, aggiornare e utilizzare la piattaforma.

L'obiettivo è rendere i prodotti facilmente accessibili, garantendo al tempo stesso un processo di distribuzione professionale, sicuro e coerente con le diverse modalità di utilizzo.

La strategia dovrà considerare le specificità dei tre principali ambiti dell'offerta:

- Free Product: estensione per Visual Studio Code.
- Commercial Products: componenti software On-Premise e servizi Cloud.
- Professional Services: servizi professionali erogati direttamente o attraverso partner.

## 13.2 Distribution Channels

La distribuzione CALIBROs sarà articolata attraverso differenti canali, in funzione del prodotto e del pubblico di riferimento.

I principali canali previsti sono:

- **Visual Studio Code Marketplace:** distribuzione dell'estensione gratuita.
- **Official CALIBROs Website:** punto di accesso centrale per prodotti, download, documentazione e informazioni commerciali.
- **Software Distribution Platform:** distribuzione dei componenti commerciali e dei relativi aggiornamenti.
- **Cloud Platform:** accesso ai servizi Cloud CALIBROs.
- **Partner Channel:** distribuzione e promozione attraverso consulenti e organizzazioni partner.

## 13.3 Visual Studio Code Extension Distribution

L'estensione CALIBROs per Visual Studio Code sarà distribuita attraverso il Visual Studio Code Marketplace.

Questo canale rappresenta il principale punto di accesso per gli sviluppatori interessati a utilizzare gratuitamente la piattaforma.

La distribuzione attraverso il Marketplace consentirà di:

- Rendere l'estensione facilmente individuabile dagli utenti.
- Semplificare installazione e aggiornamento.
- Raggiungere direttamente la comunità degli sviluppatori.
- Pubblicare nuove versioni in modo centralizzato.
- Presentare descrizione, funzionalità e documentazione del prodotto.

La pagina dell'estensione dovrà contenere una presentazione chiara delle funzionalità, immagini dimostrative, istruzioni di installazione e riferimenti alla documentazione ufficiale.

L'estensione dovrà mantenere un processo di rilascio regolare e controllato, con versioni identificabili e informazioni sulle modifiche introdotte.

**Decisione:** il Visual Studio Code Marketplace sarà il canale ufficiale di distribuzione dell'estensione gratuita.

## 13.4 On-Premise Software Distribution

I prodotti CALIBROs On-Premise saranno distribuiti attraverso il sito ufficiale o una piattaforma dedicata alla distribuzione del software.

La distribuzione dovrà comprendere i componenti necessari per installare e utilizzare la soluzione:

- CLI.
- Controller.
- Agent.
- Dipendenze e componenti runtime necessari.
- Strumenti di configurazione e gestione.

I pacchetti dovranno essere organizzati in modo da semplificare l'installazione e la gestione delle diverse componenti.

La distribuzione dovrà prevedere:

- Download dei pacchetti software.
- Identificazione delle versioni disponibili.
- Documentazione di installazione e configurazione.
- Informazioni sulle dipendenze.
- Istruzioni per l'attivazione delle licenze.
- Procedure di aggiornamento.

I componenti dovranno poter essere installati nell'infrastruttura del cliente, senza richiedere che i dati dei test o delle applicazioni sottoposte a verifica vengano trasferiti all'infrastruttura CALIBROs.

## 13.5 Cloud Distribution

Il prodotto CALIBROs Cloud sarà erogato attraverso l'infrastruttura gestita direttamente da CALIBROs.

Il cliente non dovrà installare o amministrare gli Agent Cloud, che saranno gestiti centralmente dalla piattaforma.

La distribuzione del servizio dovrà prevedere:

- Accesso al servizio attraverso il sito o il portale CALIBROs.
- Gestione delle credenziali e delle autorizzazioni.
- Attivazione e gestione degli abbonamenti.
- Accesso alla capacità di esecuzione acquistata.
- Informazioni sullo stato del servizio e sulle risorse disponibili.

L'esperienza di utilizzo dovrà essere integrata con gli strumenti locali del cliente, in particolare con l'estensione Visual Studio Code e gli eventuali componenti client necessari.

**Open Point:** definizione delle modalità tecniche di connessione e utilizzo degli Agent Cloud.

## 13.6 Official Website

Il sito ufficiale CALIBROs rappresenterà il punto di riferimento centrale per la distribuzione e la presentazione dell'intero ecosistema.

Dovrà consentire agli utenti di:

- Conoscere la piattaforma e i suoi prodotti.
- Accedere alla documentazione.
- Scaricare i componenti software.
- Consultare le versioni disponibili.
- Accedere alle informazioni sulle licenze.
- Acquistare o richiedere informazioni sui prodotti commerciali.
- Accedere ai servizi Cloud.
- Richiedere supporto tecnico e commerciale.

Il sito dovrà distinguere chiaramente i prodotti gratuiti da quelli commerciali e guidare l'utente verso il canale di distribuzione appropriato.

Dovrà inoltre rappresentare il punto di accesso alla documentazione tecnica, alle guide, ai tutorial e alle informazioni relative alle nuove versioni.

## 13.7 Software Packaging

I componenti CALIBROs dovranno essere distribuiti attraverso pacchetti software strutturati, versionati e facilmente identificabili.

La strategia di packaging dovrà garantire:

- Identificazione univoca del prodotto.
- Versionamento coerente dei componenti.
- Inclusione delle dipendenze necessarie.
- Facilità di installazione e aggiornamento.
- Integrità dei pacchetti distribuiti.
- Compatibilità tra le diverse componenti della piattaforma.

Dovranno essere valutati i formati di distribuzione più appropriati per i diversi componenti, tenendo conto delle piattaforme operative supportate e delle modalità di installazione previste.

Particolare attenzione dovrà essere dedicata alla distribuzione degli Agent, che potranno essere installati su più macchine nell'ambito delle architetture di esecuzione distribuita.

**Open Point:** definizione dei formati ufficiali dei pacchetti e delle relative modalità di installazione.

## 13.8 Versioning e Software Updates

CALIBROs dovrà adottare una strategia di versionamento uniforme per i propri prodotti e componenti.

Ogni rilascio dovrà essere identificabile attraverso una versione e accompagnato dalle relative informazioni sulle modifiche introdotte.

Il processo di aggiornamento dovrà prevedere:

- Pubblicazione delle nuove versioni.
- Disponibilità delle Release Notes.
- Documentazione delle modifiche.
- Indicazione di eventuali incompatibilità.
- Procedure di aggiornamento.
- Gestione delle dipendenze tra componenti.

Per i componenti On-Premise, gli aggiornamenti saranno resi disponibili attraverso i canali ufficiali di distribuzione.

Per l'estensione VS Code, il processo di aggiornamento sarà gestito attraverso il Marketplace.

Per i servizi Cloud, gli aggiornamenti saranno gestiti direttamente da CALIBROs.

Le politiche di accesso agli aggiornamenti dovranno rispettare le condizioni di licensing e manutenzione definite nell'offerta commerciale.

## 13.9 Software Security and Integrity

La distribuzione dei prodotti CALIBROs dovrà garantire l'autenticità e l'integrità del software.

I principali requisiti da considerare sono:

- Distribuzione attraverso canali ufficiali.
- Protezione dei pacchetti durante il trasferimento.
- Verifica dell'integrità dei file distribuiti.
- Firma digitale degli eseguibili e dei pacchetti, ove applicabile.
- Controllo delle versioni pubblicate.
- Protezione delle informazioni relative alle licenze.

Particolare attenzione dovrà essere dedicata ai componenti commerciali, affinché il cliente possa verificare che il software installato provenga effettivamente da CALIBROs.

## 13.10 Partner Distribution

La strategia di distribuzione potrà prevedere il coinvolgimento di partner commerciali e tecnici.

I partner potranno contribuire alla diffusione dei prodotti attraverso:

- Presentazione di CALIBROs ai propri clienti.
- Supporto all'installazione e alla configurazione.
- Distribuzione dei riferimenti ai canali ufficiali.
- Erogazione di servizi professionali.
- Supporto alla fase di adozione.

La distribuzione del software dovrà comunque mantenere un riferimento centralizzato ai canali ufficiali CALIBROs, in modo da garantire uniformità delle versioni e controllo sull'origine dei pacchetti.

Le modalità di rivendita, distribuzione diretta e gestione delle licenze attraverso i partner saranno definite nell'ambito degli accordi commerciali.

## 13.11 Distribution Strategy Evolution

La strategia di distribuzione dovrà evolvere insieme alla maturità della piattaforma e alla crescita della base clienti.

Nella fase iniziale sarà opportuno privilegiare canali semplici e facilmente gestibili:

1. Visual Studio Code Marketplace per l'estensione gratuita.
2. Sito ufficiale per la presentazione e la distribuzione dei prodotti commerciali.
3. Download centralizzato dei componenti On-Premise.
4. Accesso diretto ai servizi Cloud.

Con la crescita della piattaforma potranno essere introdotti sistemi più evoluti per la gestione dei download, degli aggiornamenti, delle licenze e degli acquisti.

L'obiettivo è costruire un sistema di distribuzione affidabile e scalabile, in grado di supportare sia l'adozione individuale dell'estensione gratuita sia l'utilizzo professionale dei prodotti commerciali.

---

### Stato delle decisioni

| Argomento | Stato |
|---|---|
| Visual Studio Code Marketplace per l'estensione | DECISIONE |
| Sito ufficiale CALIBROs | DECISIONE STRATEGICA |
| Distribuzione On-Premise attraverso canali ufficiali | PROPOSTA |
| Erogazione Cloud gestita da CALIBROs | DECISIONE |
| Versionamento dei prodotti | PROPOSTA |
| Distribuzione centralizzata degli aggiornamenti | PROPOSTA |
| Firma digitale e verifica di integrità | PROPOSTA |
| Formati dei pacchetti software | DA DEFINIRE |
| Modalità di acquisto online | DA DEFINIRE |
| Portale clienti e gestione download | DA DEFINIRE |
| Distribuzione e rivendita attraverso partner | DA DEFINIRE |

# 14. Roadmap

## 14.1 Obiettivo

Questo capitolo definisce la roadmap evolutiva di CALIBROs, individuando le principali fasi di sviluppo tecnologico, consolidamento del prodotto e crescita commerciale.

La roadmap ha lo scopo di stabilire un percorso progressivo che consenta di trasformare CALIBROs da progetto software in una piattaforma professionale commercialmente sostenibile.

L'evoluzione dovrà tenere conto di due dimensioni strettamente correlate:

- **Evoluzione tecnologica:** sviluppo delle funzionalità, consolidamento dell'architettura, affidabilità e maturità della piattaforma.
- **Evoluzione commerciale:** introduzione dell'offerta, acquisizione dei primi clienti, sviluppo dei canali commerciali e crescita del mercato.

Le due dimensioni dovranno procedere in modo coordinato, evitando di anticipare iniziative commerciali rispetto alla maturità effettiva del prodotto.

## 14.2 Roadmap Principles

La roadmap CALIBROs si basa sui seguenti principi:

- **Progressive Development:** sviluppare la piattaforma per fasi successive, introducendo progressivamente funzionalità e capacità.
- **Product Quality First:** privilegiare affidabilità, stabilità e qualità del prodotto prima di ampliare eccessivamente l'offerta.
- **Commercial Readiness:** rendere disponibili i prodotti commerciali quando le funzionalità e i processi necessari sono sufficientemente maturi.
- **Customer Feedback:** utilizzare il feedback degli utilizzatori e dei primi clienti per orientare le priorità di sviluppo.
- **Scalability:** progettare l'architettura in modo da supportare la crescita della piattaforma e dei carichi di lavoro.
- **Sustainable Growth:** sviluppare il progetto in modo compatibile con le risorse economiche e organizzative disponibili.

## 14.3 Phase 1 – Product Foundation

**Obiettivo:** consolidare le fondamenta tecnologiche della piattaforma CALIBROs.

Questa fase è dedicata al completamento e alla stabilizzazione delle funzionalità fondamentali necessarie per sviluppare ed eseguire WebTest.

### Evoluzione tecnologica

Attività principali:

- Consolidamento dell'architettura software.
- Completamento delle funzionalità principali dell'estensione Visual Studio Code.
- Gestione e validazione della struttura YAML dei WebTest.
- Gestione delle richieste HTTP e delle relative configurazioni.
- Gestione di variabili, parametri e DataSource.
- Implementazione delle validazioni delle richieste e delle risposte.
- Sviluppo e consolidamento del motore di esecuzione dei WebTest.
- Implementazione delle funzionalità di debugging.
- Sviluppo degli strumenti di ispezione delle richieste e delle risposte.
- Implementazione dei meccanismi di estensibilità attraverso codice .NET.
- Introduzione di test automatici e procedure di verifica della qualità.

### Evoluzione commerciale

In questa fase non è prevista una commercializzazione strutturata.

Le attività saranno principalmente orientate alla preparazione del prodotto gratuito e alla definizione delle fondamenta dell'offerta commerciale.

### Risultato atteso

Una piattaforma tecnologicamente stabile, in grado di consentire lo sviluppo, l'esecuzione e il debugging dei WebTest attraverso un'esperienza di lavoro integrata con Visual Studio Code.

## 14.4 Phase 2 – Free Product Launch

**Obiettivo:** rendere disponibile pubblicamente l'estensione gratuita CALIBROs e iniziare a costruire una base di utilizzatori.

### Evoluzione tecnologica

Attività principali:

- Consolidamento della versione pubblica dell'estensione.
- Preparazione dei pacchetti di distribuzione.
- Pubblicazione sul Visual Studio Code Marketplace.
- Completamento della documentazione per gli utilizzatori.
- Preparazione di tutorial ed esempi.
- Definizione del processo di rilascio e aggiornamento.
- Raccolta e gestione delle segnalazioni degli utenti.

### Evoluzione commerciale e marketing

Attività principali:

- Lancio pubblico dell'estensione.
- Presentazione delle funzionalità principali.
- Avvio delle attività di comunicazione tecnica.
- Pubblicazione di articoli e dimostrazioni.
- Coinvolgimento degli sviluppatori e delle community tecniche.
- Individuazione dei primi utilizzatori professionali.

### Risultato atteso

Disponibilità pubblica del Free Product e acquisizione dei primi utilizzatori, con particolare attenzione agli sviluppatori e ai professionisti del Web Testing.

## 14.5 Phase 3 – On-Premise Commercial Launch

**Obiettivo:** completare e rendere commercialmente disponibile la soluzione CALIBROs On-Premise.

Questa fase rappresenta il primo passo significativo verso la monetizzazione della piattaforma.

### Evoluzione tecnologica

Attività principali:

- Consolidamento del motore di esecuzione dei LoadTest.
- Completamento dell'architettura Controller e Agent.
- Supporto all'esecuzione distribuita.
- Gestione dei Virtual User concorrenti.
- Implementazione della gestione centralizzata delle licenze.
- Sviluppo del Licensing Server.
- Implementazione dei meccanismi di attivazione e verifica delle licenze.
- Preparazione dei pacchetti di installazione.
- Gestione delle configurazioni e delle dipendenze.
- Implementazione delle funzionalità di monitoraggio e reporting.
- Verifica delle prestazioni e della stabilità attraverso test su scenari realistici.

### Evoluzione commerciale

Attività principali:

- Definizione definitiva dei pacchetti On-Premise.
- Definizione delle fasce di capacità Virtual User.
- Completamento delle formule di licensing.
- Definizione dei prezzi.
- Preparazione delle procedure di acquisto e attivazione.
- Pubblicazione della documentazione commerciale.
- Acquisizione dei primi clienti paganti.

### Risultato atteso

Disponibilità commerciale della soluzione On-Premise, con possibilità di eseguire LoadTest e StressTest utilizzando infrastrutture gestite direttamente dai clienti.

## 14.6 Phase 4 – Cloud Commercial Launch

**Obiettivo:** introdurre la soluzione CALIBROs Cloud, consentendo ai clienti di utilizzare capacità di generazione del carico gestite direttamente da CALIBROs.

### Evoluzione tecnologica

Attività principali:

- Progettazione dell'infrastruttura Cloud.
- Realizzazione degli Agent Cloud.
- Implementazione della gestione delle risorse di esecuzione.
- Gestione degli abbonamenti e delle autorizzazioni.
- Integrazione con il sistema di licensing.
- Implementazione dei meccanismi di comunicazione tra i componenti locali e Cloud.
- Gestione della sicurezza e dell'isolamento tra clienti.
- Monitoraggio dell'infrastruttura e dei consumi.
- Implementazione dei meccanismi di scalabilità.
- Definizione delle procedure operative e di continuità del servizio.

### Evoluzione commerciale

Attività principali:

- Definizione dei pacchetti Cloud.
- Definizione delle modalità di abbonamento.
- Definizione dei prezzi e delle capacità disponibili.
- Preparazione del portale di accesso.
- Introduzione delle procedure di attivazione e gestione dei clienti.
- Lancio commerciale del servizio.

### Risultato atteso

Disponibilità della soluzione Cloud, che consentirà ai clienti di eseguire test di carico senza dover installare e gestire direttamente l'infrastruttura di generazione del carico.

## 14.7 Phase 5 – Market Expansion

**Obiettivo:** ampliare la presenza commerciale e consolidare CALIBROs nel mercato professionale.

### Evoluzione tecnologica

Attività principali:

- Evoluzione delle funzionalità della piattaforma sulla base dei feedback ricevuti.
- Miglioramento delle prestazioni del motore di esecuzione.
- Ampliamento delle capacità di reporting e analisi.
- Miglioramento degli strumenti di monitoraggio.
- Introduzione di nuove funzionalità richieste dai clienti.
- Ampliamento delle possibilità di integrazione con strumenti e processi esterni.
- Miglioramento della scalabilità della soluzione Cloud.
- Evoluzione degli strumenti di amministrazione e gestione.

### Evoluzione commerciale

Attività principali:

- Ampliamento della base clienti.
- Sviluppo delle collaborazioni con società di consulenza e partner.
- Introduzione di nuove configurazioni commerciali.
- Ampliamento delle fasce di capacità Virtual User.
- Consolidamento delle attività di marketing.
- Sviluppo della presenza nel mercato Enterprise.
- Introduzione di ulteriori servizi professionali.
- Valutazione di nuovi mercati geografici.

### Risultato atteso

Una piattaforma consolidata, con una base clienti crescente, un'offerta commerciale strutturata e un ecosistema di utilizzatori e partner.

## 14.8 Roadmap Summary

La seguente tabella riassume le principali fasi evolutive.

| Fase | Denominazione | Priorità tecnologica | Obiettivo commerciale |
|---|---|---|---|
| 1 | Product Foundation | Consolidamento della piattaforma e dei WebTest | Preparazione del prodotto |
| 2 | Free Product Launch | Stabilizzazione e distribuzione dell'estensione | Acquisizione dei primi utilizzatori |
| 3 | On-Premise Commercial Launch | Controller, Agent, LoadTest e licensing | Acquisizione dei primi clienti paganti |
| 4 | Cloud Commercial Launch | Infrastruttura e Agent Cloud | Introduzione dell'offerta Cloud |
| 5 | Market Expansion | Evoluzione e scalabilità della piattaforma | Crescita commerciale e sviluppo del mercato |

## 14.9 Roadmap Governance

La roadmap dovrà essere considerata uno strumento dinamico, aggiornato periodicamente sulla base dello stato di avanzamento del progetto e delle esigenze del mercato.

Le priorità potranno essere modificate in funzione di:

- Risultati dei test e verifiche tecniche.
- Feedback degli utilizzatori.
- Richieste dei clienti.
- Opportunità commerciali.
- Risorse economiche e organizzative disponibili.
- Evoluzione del mercato e delle tecnologie.

Il passaggio da una fase alla successiva dovrà essere subordinato al raggiungimento di risultati verificabili.

In particolare, il lancio commerciale dei prodotti dovrà essere preceduto da verifiche di affidabilità, stabilità, sicurezza e completezza delle funzionalità necessarie.

## 14.10 Success Criteria

Per ciascuna fase dovranno essere definiti criteri oggettivi che consentano di valutarne il completamento.

I principali indicatori da considerare sono:

| Area | Indicatore |
|---|---|
| Prodotto | Funzionalità completate rispetto agli obiettivi della fase |
| Qualità | Test automatici superati e difetti critici risolti |
| Affidabilità | Stabilità delle esecuzioni e assenza di anomalie bloccanti |
| Distribuzione | Disponibilità dei pacchetti e procedure di installazione |
| Adozione | Numero di utilizzatori e organizzazioni coinvolte |
| Commerciale | Numero di clienti acquisiti |
| Economica | Ricavi e sostenibilità dei costi operativi |
| Customer Feedback | Soddisfazione e richieste di miglioramento |

La roadmap dovrà essere accompagnata da una pianificazione operativa più dettagliata, nella quale saranno definiti attività, responsabilità, priorità e tempistiche.

---

### Stato della roadmap

| Elemento | Stato |
|---|---|
| Evoluzione per fasi successive | PROPOSTA |
| Consolidamento del Free Product come prima priorità | PROPOSTA |
| Lancio commerciale On-Premise | PROPOSTA |
| Introduzione successiva del Cloud | PROPOSTA |
| Espansione commerciale progressiva | PROPOSTA |
| Durata delle singole fasi | DA DEFINIRE |
| Date dei rilasci | DA DEFINIRE |
| Milestone tecnologiche dettagliate | DA DEFINIRE |
| Budget e risorse necessarie | DA DEFINIRE |
| Criteri di passaggio tra le fasi | DA DEFINIRE |

# 20 Product Vision (2)

CALIBROs nasce con l'obiettivo di colmare il vuoto lasciato dalla dismissione degli strumenti Microsoft per Web Performance e Load Testing, realizzando una piattaforma moderna e professionale, capace di offrire una vera esperienza di sviluppo dedicata al Web Testing.

CALIBROs non vuole essere semplicemente uno strumento per generare traffico e misurare le prestazioni delle applicazioni Web, ma un ambiente integrato per progettare, sviluppare, eseguire e analizzare test Web.

La piattaforma si rivolge principalmente a Web Developer e Performance Engineer, indipendentemente dalle tecnologie e dai linguaggi utilizzati per sviluppare le applicazioni sottoposte a test.

Il suo approccio integra Functional Testing, Regression Testing e Performance Testing, consentendo di sviluppare test funzionali e di riutilizzarli come base per successive campagne di Load Testing.

Uno degli elementi distintivi di CALIBROs è l'esperienza di sviluppo: funzionalità come breakpoint, variable watch e debugging permettono di progettare e verificare i test utilizzando strumenti e modalità familiari agli sviluppatori.

Attraverso Visual Studio Code, una configurazione dichiarativa basata su YAML e un'infrastruttura modulare per l'esecuzione distribuita, CALIBROs vuole integrare il Performance Testing nel naturale ciclo di sviluppo delle applicazioni Web.

**La visione di CALIBROs è trasformare il Web Testing in una vera attività di sviluppo software, unificando test funzionali, regressione e performance testing in un unico ambiente di lavoro.**
--------------------------------------------------------------------------------------------------------------------------------------------------------
