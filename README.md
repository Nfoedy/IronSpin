# IronSpin

## 🎮 Overview

**IronSpin** è un gioco pinball arcade sviluppato in **Unreal Engine 5**, basato principalmente sulla fisica e sul controllo reattivo delle palette.

Il progetto propone un gameplay semplice e immediato: il giocatore deve mantenere la pallina in gioco, colpire bumper e altri elementi del tavolo per accumulare punti e cercare di sopravvivere il più a lungo possibile prima di esaurire tutte le vite.

Dal punto di vista visivo, **IronSpin** adotta uno stile sci-fi essenziale, arricchito da effetti neon e da una presentazione ispirata ai classici arcade.

---

## 🎯 Project Goals

L'obiettivo principale di **IronSpin** era sviluppare un piccolo progetto arcade incentrato su **fisica, game feel e chiarezza del gameplay**.

Lo sviluppo si è concentrato soprattutto su:

- gestione della pallina tramite fisica;
- comportamento reattivo delle flipper;
- interazione con bumper ed elementi rimbalzanti;
- sistema di punteggio;
- gestione delle vite e del game over;
- HUD integrato direttamente nel playfield;
- feedback visivi e sonori in stile arcade.

Il progetto non nasce con l'obiettivo di costruire un pinball complesso o ricco di sistemi avanzati, ma di realizzare un gameplay loop semplice, leggibile e soddisfacente, curando soprattutto la risposta dei controlli e il comportamento degli elementi principali del tavolo.

---

## 🎮 Controls

| Input | Azioni |
|---|---|
| `A` | Left Flipper |
| `D` | Right Flipper |
| `Space` | Launcher |
| `Mouse` | Menu navigation |
| `Esc` | Pause Menu |

---

## 🕹️ Gameplay

In **IronSpin** il giocatore controlla le due flipper del tavolo da gioco per mantenere la pallina in movimento e impedire che cada nello scarico finale.

Durante la partita, la pallina può colpire bumper e altri elementi interattivi del tavolo, generando rimbalzi e aumentando il punteggio.

Ogni volta che la pallina cade fuori dal campo di gioco, il giocatore perde una vita.

### Score System

Il punteggio aumenta in base agli urti contro bumper e altri elementi del playfield.

L'obiettivo è ottenere il punteggio più alto possibile, mantenendo la pallina in gioco il più a lungo possibile.

### Lives System

Il giocatore dispone di un numero limitato di vite.

Ogni perdita della pallina comporta la riduzione di una vita e una nuova rimessa in gioco della sfera, finché il numero di vite non raggiunge lo zero.

### Game Over

Quando tutte le vite vengono esaurite, la partita termina e il giocatore deve ricominciare.

---

## 🧠 Development Focus

Una parte importante dello sviluppo di **IronSpin** è stata dedicata alla costruzione di un gameplay arcade chiaro e reattivo attraverso **Blueprint Visual Scripting**.

Il progetto ha richiesto in particolare di lavorare su:

- gestione della fisica della pallina;
- controllo delle flipper;
- logica di lancio iniziale;
- rilevamento delle collisioni;
- aggiornamento del punteggio;
- gestione delle vite;
- visualizzazione delle informazioni di gioco nel playfield;
- integrazione di effetti visivi e sonori.

L'obiettivo era creare un piccolo progetto completo, nel quale gli elementi principali del pinball risultassero leggibili, funzionali e ben integrati tra loro.

---

## Blueprint Gameplay Architecture

Il progetto è stato sviluppato utilizzando **Blueprint Visual Scripting**, organizzando la logica di gioco attorno ai principali elementi del tavolo.

La pallina rappresenta il cuore del sistema fisico, mentre le flipper e i bumper costituiscono gli elementi principali dell'interazione di gameplay.

Accanto a questi sistemi, il progetto comprende anche:

- la gestione del punteggio;
- il conteggio delle vite;
- la logica di game over;
- l'HUD posizionato direttamente nel tavolo da gioco;
- gli effetti visivi, come la scia neon della pallina.

Questo approccio ha permesso di costruire un progetto semplice ma completo, adatto a sperimentare il comportamento fisico degli oggetti e la costruzione di un gameplay arcade immediato.

---

## 📌 Final Considerations

Lo sviluppo di **IronSpin** mi ha permesso di lavorare su un progetto compatto ma utile per approfondire la realizzazione di meccaniche arcade in Unreal Engine.

La parte più importante del lavoro è stata trovare un buon equilibrio tra **fisica, controlli e feedback di gioco**, così da rendere il comportamento delle flipper e della pallina il più possibile chiaro e soddisfacente.

Anche in un progetto relativamente semplice, è stato importante collegare correttamente più sistemi tra loro: input, collisioni, punteggio, vite, HUD ed effetti audiovisivi.

**IronSpin** rappresenta quindi un piccolo esercizio di gameplay design e implementazione tecnica, utile per consolidare le basi di un gioco arcade costruito attorno a una meccanica immediata e riconoscibile.

---


## 📸 Video & Media

- link Youtube: https://www.youtube.com/watch?v=xUOsMmtIoJg
