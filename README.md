# 🧹 To-Do Pulizie Domestiche

Questa è una **web app semplice e intelligente** per gestire le pulizie di casa tramite una **to-do list automatica**, pensata per essere usata **da iPhone come un’app** (tramite GitHub Pages).

Le attività vengono mostrate automaticamente in base a:
- giorno della settimana
- giorno del mese
- mese dell’anno

Ogni task scompare quando viene completato e ricompare secondo regole precise.

---

## 📱 Come si usa
1. Apri il sito con **Safari**
2. Tocca **Condividi → Aggiungi alla schermata Home**
3. Usala come una normale app

✔ Funziona anche offline  
✔ Nessuna registrazione richiesta

---

## 🔁 Regole di funzionamento

### ✅ Attività giornaliere
- Sono **sempre visibili**
- Si **resettano ogni giorno**
- Anche se completate, ricompaiono il giorno successivo

**Attività incluse:**
- 🌬️ Arieggiare le stanze  
- 🛏️ Rifare i letti  
- 🍽️ Svuotare stoviglie  
- 🧹 Passare aspirapolvere  
- 🧺 Riordinare oggetti fuori posto  
- 🚿 Pulizia veloce bagni  
- 🍽️ Pulire tavolo  
- 🍳 Pulire piano cucina  
- 🗑️ Buttare immondizia  

---

### 🗓️ Attività settimanali
- Compaiono **solo nel giorno corretto**
- Si resettano il giorno successivo

**Programmazione:**
- 🛏️ Materassi e cambio lenzuola (**Lunedì**)
- 🪶 Spolverare (**Lunedì**)
- 🪶 Spolverare (**Martedì**)
- 🚿🧽 Pavimenti e bagni (**Mercoledì**)
- 👕 Bucato (**Giovedì**)
- ♻️🧺 Bidoni e tappeti (**Venerdì**)
- 🧹 Aspirapolvere (**Domenica**)

---

### 🗂️ Attività mensili
- Compaiono **all’inizio del mese**
- Restano visibili finché non vengono completate
- Hanno un **giorno del mese consigliato**
- Il **giorno della settimana viene calcolato automaticamente**
- Se oggi coincide con il giorno consigliato, compare ⭐ **“Consigliato oggi”**

**Programmazione (giorno del mese):**
- ❄️ Frigo → **5**
- 🔥 Forno e microonde → **7**
- 🍽️💨 Lavastoviglie e cappa → **10**
- 👕🔄 Lavatrice e asciugatrice → **12**
- 🧹✨ Pulizia profonda aspirapolvere → **15**
- 🪟 Vetri → **18**
- 📏 Battiscopa → **20**
- 🚪 Porte → **22**
- 🔘 Interruttori → **25**
- 🌿 Giardino → **28**

> 💡 Nota: se il mese ha meno giorni (es. febbraio), il task resta comunque visibile per tutto il mese.

---

### 🚨 Pulizie straordinarie
- Compaiono **solo nei mesi indicati**
- Restano visibili finché non vengono completate
- Hanno un **giorno del mese consigliato**
- Mostrano ⭐ **“Consigliato oggi”** se la data coincide

**Programmazione:**
- 🚰 Scarichi → gennaio, giugno, novembre (**giorno 10**)
- 🛋️ Mobili sotto e dietro → febbraio, giugno, ottobre (**giorno 15**)
- ☕🫖 Decalcificazione macchina caffè e bollitore → febbraio, luglio, dicembre (**giorno 5**)
- 🗄️ Interno dei cassetti → gennaio, maggio, settembre (**giorno 20**)
- ♨️❄️ Termosifoni e condizionatori → maggio, ottobre (**giorno 10**)
- 🏠 Soffitto e pareti → marzo, luglio, novembre (**giorno 18**)
- 📦 Spolverare in alto → aprile, agosto, dicembre (**giorno 8**)
- 🌱 Pavimento giardino → aprile, agosto (**giorno 22**)
- 🌳 Ordinare giardino → marzo, luglio, novembre (**giorno 15**)
- 👚 Cambio stagione → aprile, ottobre (**giorno 5**)
- 🧱 Marciapiede e muri esterni → gennaio, settembre (**giorno 12**)

---

## ⭐ “Consigliato oggi”
Il badge **⭐ Consigliato oggi** appare quando:
- il task è visibile
- oggi coincide con il **giorno del mese suggerito**

👉 Serve come **suggerimento**, non come scadenza rigida.

---

## 💾 Salvataggio dei dati
- Lo stato delle attività è salvato in **localStorage**
- I dati restano **solo sul dispositivo**
- Nessun dato viene inviato online

⚠️ Cambiando dominio (es. rinominando la repository), le checklist ripartono vuote.

---

## 🛠️ Tecnologie usate
- HTML
- CSS
- JavaScript
- GitHub Pages

---

## 🎯 Obiettivo
Ridurre il **carico mentale**, distribuire le pulizie nel tempo e avere sempre chiaro **cosa fare oggi**, senza dover ricordare tutto.

---

## ✨ Miglioramenti futuri possibili
- Barra di avanzamento giornaliera/mensile
- Nascondere automaticamente le sezioni vuote
- Evidenziazione delle priorità
- Storico delle attività completate
- Notifiche soft