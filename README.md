# Progetto SAD — Servizi assistenziali

Questo repository contiene il progetto del gruppo per il corso di **Software Architecture Design**. Tutti i gruppi partono dalla stessa traccia; ogni gruppo definisce e motiva la propria soluzione applicativa e architetturale.

## Il problema

Un ente benefico riceve da **Operatori Autorizzati (OPT)** richieste di servizi assistenziali, come supporto psicologico, educativo e sociale. L'ente collabora con professionisti di diverse qualifiche, disponibili a erogare le prestazioni richieste.

Il sistema deve permettere di:

- raccogliere e seguire le richieste presentate dagli OPT;
- registrare i professionisti, le loro qualifiche e disponibilità;
- supportare l'assegnazione dei professionisti alle richieste;
- registrare le prestazioni effettivamente erogate;
- produrre, ogni tre mesi, rendiconti delle prestazioni associate alle richieste di ciascun OPT e delle prestazioni erogate da ciascun professionista;
- generare statistiche sui servizi erogati, sulle categorie di persone assistite e sulla percentuale di richieste soddisfatte;
- esportare le statistiche in un **formato aperto**, utilizzabile da un ente esterno autorizzato.

I tipi di prestazione erogabili devono essere configurabili. Il sistema deve essere normalmente disponibile e proteggere la confidenzialità dei dati, consentendo l'accesso in base ai ruoli degli utenti.

La traccia lascia aperte le regole operative e le scelte di progettazione. Il gruppo deve chiarire e documentare le proprie ipotesi: per esempio, quando una richiesta si considera soddisfatta, come si gestiscono le disponibilità e chi autorizza un'assegnazione.

## Il gruppo

| Responsabilità | Studente | Periodo |
| --- | --- | --- |
| Product Owner | Da compilare | Intero progetto |
| Scrum Master | Da compilare | Sprint corrente |
| Developers | Da compilare | Intero progetto |

Il **Product Owner** mantiene l'obiettivo del prodotto e ordina il Product Backlog. Rimane nel ruolo per assicurare continuità nelle priorità. Lo **Scrum Master** facilita il lavoro del gruppo e cambia a ogni Sprint. Tutti i membri, inclusi Product Owner e Scrum Master, contribuiscono al prodotto e alle attività tecniche. I compiti di progettazione, implementazione, verifica e documentazione vengono distribuiti e alternati.

Ogni studente usa il proprio account GitHub. Il repository è condiviso con i membri del gruppo e con la docente secondo le indicazioni del corso; non si condividono credenziali di accesso.

## Product Backlog e Sprint

Il **Product Backlog** è mantenuto nelle [Issues](../../issues) e organizzato nel GitHub Project del gruppo:

> **Link al GitHub Project:** da inserire

Per ogni issue indichiamo:

1. il risultato atteso e il motivo per cui è utile;
2. i criteri con cui ne verificheremo il completamento;
3. gli eventuali collegamenti a requisiti, scenari di qualità e decisioni architetturali.

Il Project contiene gli stati `Backlog`, `Ready`, `In progress`, `In review` e `Done`, oltre ai campi *Priority* e *Iteration*. Le issue dello Sprint corrente formano lo **Sprint Backlog**. Una issue completata rimanda alle relative pull request, ai test o agli altri artefatti verificabili.

### A ogni Sprint

1. **Sprint Planning:** definiamo uno Sprint Goal, selezioniamo il lavoro e concordiamo come verificarlo.
2. **Lavoro e coordinamento:** aggiorniamo issue e repository, rendiamo visibili gli impedimenti e riesaminiamo il piano quando serve.
3. **Sprint Review:** mostriamo un incremento eseguibile o, per un'attività esplorativa, un prototipo o una verifica riproducibile. Discutiamo i risultati con la docente e aggiorniamo il backlog.
4. **Sprint Retrospective:** scegliamo un miglioramento concreto del modo di lavorare da applicare nello Sprint successivo.

### Definition of Done iniziale

Un elemento può essere dichiarato `Done` quando i suoi criteri di completamento sono verificati, gli artefatti sono nel repository, le verifiche pertinenti sono documentate e le decisioni che incidono sull'architettura sono state motivate. Il gruppo può precisare questa definizione durante il progetto.

## Architettura e qualità

Il gruppo sceglie liberamente l'architettura e le tecnologie, rispettando la traccia. Le decisioni devono essere collegate a **scenari di qualità misurabili**, in particolare per disponibilità, modificabilità e confidenzialità. Per ciascuna decisione significativa documentiamo il problema, le alternative considerate, la scelta e le conseguenze attese.

> **Link alla descrizione dell'architettura:** da inserire  
> **Link alle decisioni architetturali:** da inserire  
> **Link agli scenari e alle verifiche:** da inserire

La valutazione degli scenari richiede evidenze: test, esperimenti, analisi o dimostrazioni riproducibili. I dati personali usati nelle dimostrazioni e nei test devono essere fittizi.

## Contributi e review

Prima di ogni Sprint Review, il gruppo rende disponibili l'incremento, il backlog aggiornato, le decisioni e le verifiche dello Sprint. Ogni componente indica brevemente **che cosa ha fatto, quale risultato ha ottenuto e dove si trova l'evidenza**. Un contributo può essere codice, test, analisi, modelli, una decisione architetturale, una revisione motivata o lavoro sul Product Backlog. Nei lavori svolti insieme sono indicati i contributi delle persone coinvolte.

Durante la review tutti devono poter spiegare il proprio lavoro e le scelte del gruppo. Il numero di commit o di righe di codice, da solo, non misura il contributo individuale.

> **Link alle schede dei contributi per Sprint:** da inserire

## Avvio ed esecuzione

Questa sezione va completata dal gruppo non appena esiste un primo incremento eseguibile:

- prerequisiti;
- istruzioni per avviare il sistema;
- configurazione necessaria, senza credenziali nel repository;
- istruzioni per eseguire i test;
- accesso alla dimostrazione con dati fittizi.
