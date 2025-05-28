# 📱 Come funziona la tua app web

## 1. 🗓️ Visualizzazione Mesi e Giorni

📅 Quando apri la pagina, vedi una griglia con i 12 mesi dell'anno corrente.

🔘 Ogni mese è rappresentato da un pulsante cliccabile.

## 2. 🕹️ Selezione del Mese

👉 Cliccando su un mese, la vista cambia mostrando tutti i giorni di quel mese in una griglia 7xN (7 colonne per i giorni della settimana).

🟦 Ogni giorno è un "blocco" cliccabile.

## 3. ✍️ Visualizzazione e inserimento dati giornalieri

📊 Se per un giorno ci sono già registrazioni (entrate o uscite), sotto al numero del giorno vedi il totale delle entrate (in verde) e delle uscite (in rosso).

🖱️ Cliccando su un giorno si apre un modale (finestra popup) dove puoi:

- 👁️ Visualizzare e modificare le entrate e le uscite di quel giorno.  
- ➕ Aggiungere nuove entrate o uscite (cliccando su "Aggiungi Entrata" o "Aggiungi Uscita").  
- ❌ Eliminare voci esistenti.

🔢 I dati inseriti sono numeri decimali (es. 12.50 €).

## 4. 💾 Salvataggio dei dati

🗄️ Tutte le informazioni vengono salvate localmente nel browser usando localStorage.

🔒 Questo significa che i dati restano salvati anche chiudendo e riaprendo la pagina, ma solo sullo stesso browser e dispositivo.

🗂️ I dati sono organizzati per data, nel formato YYYY-MM-DD come chiave (es. "2025-05-28") e contengono due liste separate: income (entrate) e expense (uscite).

## 5. 🔄 Navigazione

🔙 Puoi tornare alla visualizzazione dei mesi cliccando il pulsante "Torna alla selezione mesi".

❎ Nel modale puoi chiudere con il pulsante "X".

## 6. 🎨 UI e UX

✨ Il design è semplice, pulito e responsive (funzionerà anche su schermi piccoli).

🟢 I colori aiutano a distinguere entrate (verde) e uscite (rosso).

🗂️ La selezione tra "Entrate" e "Uscite" nel modale avviene con due tab (bottoni) per facilitare l’inserimento.

---

# 🚀 Come potresti usarla

- 📈 Per tenere traccia delle tue entrate e uscite giornaliere.  
- 👀 Visualizzare facilmente i totali per ogni giorno.  
- 📝 Consultare e modificare i dati in modo semplice e rapido.  
- 🚫 Senza dover usare app complesse o database esterni.

---

# 🌟 Possibili miglioramenti futuri

- 📅 Totali mensili e annuali con riepiloghi.  
- 📂 Esportazione/importazione dati (es. CSV o JSON).  
- ☁️ Backup e sincronizzazione su cloud per accesso multi-dispositivo.  
- 🗃️ Aggiungere categorie per entrate e uscite.  
- 📊 Calendario con evidenza visiva dei giorni con saldo positivo o negativo.  
- 📆 Gestione di più anni.
