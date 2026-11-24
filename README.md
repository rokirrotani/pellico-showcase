# Caffè Pellico — Web App (Case Study)

> Il codice sorgente è privato (progetto commissionato). Questo repository descrive in forma pubblica il lavoro svolto.

Sito web full-stack per un bar/caffetteria: vetrina pubblica con menu dinamico e area di amministrazione per aggiornare prezzi e descrizioni senza intervenire sul codice.

## Il mio ruolo
Progettazione e sviluppo end-to-end: architettura, frontend, backend, database e deploy.

## Stack
- **Frontend:** React, Vite
- **Backend:** Node.js, Express
- **Database:** MySQL

## Architettura
- Architettura separata **client / server**.
- Backend a livelli con pattern **DAO + DTO**, controller e middleware dedicati.
- Bootstrap automatico dello schema del database e dati iniziali all'avvio.
- Autenticazione dell'area admin con password con hash e token firmati.
- Menu non statici: caricati via API dal database.

## Funzionalità
- Menu dinamici (caffetteria, bevande, pranzi) aggiornabili dall'area admin
- Dashboard admin per modificare nome, prezzo e descrizione dei piatti
- Analytics: visualizzazioni del sito e classifica dei contenuti più visti
- Cookie banner e design responsive
- Materiali stampabili (menu e tovagliette) generati da pagine HTML

## Sviluppi futuri
- Gestione multilingua del menu
- Prenotazioni ed eventi online
- Galleria e gestione contenuti da admin
- Test automatici e pipeline CI/CD
