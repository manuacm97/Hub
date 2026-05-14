# 🎯 BetHub

Hub di gestione scommesse personale. Funziona offline come PWA.

## Funzionalità

- **💰 Budget Hub** — budget totale con log trasferimenti, Rage Bet Fund (sbloccato sotto €10)
- **1️⃣2️⃣ Masaniello x2** — formula corretta (triangolo di Tartaglia), stake aggiornato per quota reale, New Start
- **📈 Scalata** — proiezione live, checkpoint con prelievo, modifica esiti, New dopo fallimento
- **🎲 Free Bet** — split 90/10 budget/rage automatico

## Deploy su GitHub Pages

1. Crea un repository pubblico su GitHub (es. `bethub`)
2. Carica questi file nella root del repository:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Vai su **Settings → Pages → Source** → seleziona `main` branch, cartella `/ (root)`
4. Clicca **Save** — dopo qualche minuto l'app è online su `https://tuousername.github.io/bethub`

## Installa come app (PWA)

- **iPhone/iPad**: Safari → pulsante Condividi → "Aggiungi a schermata Home"
- **Android**: Chrome → menu ⋮ → "Aggiungi a schermata Home"
- **Desktop**: barra indirizzo Chrome/Edge → icona installa (⊕)

## Dati

I dati sono salvati in `localStorage` del browser. Usa **Esporta JSON** per backup e per trasferire tra dispositivi.
