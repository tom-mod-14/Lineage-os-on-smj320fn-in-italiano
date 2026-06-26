# Lineage-os-on-smj320fn-in-italiano

## Guida all'installazione di LineageOS 14.1 per Samsung Galaxy J3 2016 (SM-J320FN)

Questa guida spiega come installare la ROM non ufficiale LineageOS 14.1 (Android 7.1.2) sul Samsung Galaxy J3 2016 (SM-J320FN).

> ⚠️ **ATTENZIONE:** Questo processo cancellerà tutti i dati presenti sul telefono. Effettua un backup prima di procedere. Procedi a tuo rischio e pericolo.

---

### 💾 Download dei File Richiesti

Tutti i file necessari (Odin, TWRP, la ROM LineageOS e le Google Apps corrette per questo modello) sono ospitati e pronti al download in questo archivio:
👉 [Link alla cartella Google Drive](INSERISCI_IL_TUO_LINK_QUI)

---

### 🛠️ Istruzioni Passo-Passo

#### Passo 1: Preparazione e Modalità Download (Download Mode)
1. Sul telefono, rimuovi il tuo **Account Google** per evitare il blocco FRP.
2. Abilita le **Opzioni Sviluppatore** (Vai su *Impostazioni > Info sul telefono > Premi 7 volte su "Versione build"*).
3. Apri le *Opzioni Sviluppatore* e attiva le voci **Debug USB** e **Sblocco OEM** (se presente).
4. Spegni completamente il telefono.
5. Avvia il telefono in **Modalità Download** premendo e tenendo premuti contemporaneamente i tasti: `Volume Giù + Home + Accensione`.
6. Premi il tasto `Volume Su` nella schermata di avviso per confermare.
7. Connetti il telefono al PC tramite il cavo USB.
8. Apri **Odin** come amministratore sul tuo PC. Assicurati che la casella in alto a sinistra `ID:COM` diventi blu (telefono rilevato).

#### Passo 2: Installazione della Recovery TWRP
1. In Odin, clicca sul pulsante **AP** e seleziona il file della recovery scaricato (es. `twrp-3.0.2-0-j3xnlte.tar`).
2. Vai nella scheda **Options** di Odin e togli la spunta da **"Auto Reboot"**.
3. Clicca su **Start** e attendi che la barra di avanzamento sul telefono finisca e che Odin mostri il messaggio verde **"PASS"**.
4. Scollega il telefono, **rimuovi la batteria** per spegnerlo e poi reinseriscila.

#### Passo 3: Formattazione e Trasferimento dei File
1. Avvia il telefono in **TWRP Recovery** tenendo premuti contemporaneamente i tasti: `Volume Su + Home + Accensione`.
2. Non appena appare il logo Samsung, **rilascia il tasto di Accensione** ma continua a tenere premuti gli altri due.
3. Una volta entrato in TWRP, scorri la barra in basso per consentire le modifiche (*Swipe to allow modifications*).
4. Vai su **Wipe > Format Data**, digita `yes` e conferma.
5. Connetti il telefono al PC. La memoria interna del telefono verrà riconosciuta dal computer e apparirà vuota.
6. Copia il file `.zip` della LineageOS e il file delle GApps dal PC all'interno della memoria del telefono.

#### Passo 4: Installazione della ROM e delle GApps
1. In TWRP, vai su **Install**, seleziona il file `.zip` di LineageOS e scorri la barra in basso per avviare il flash.
2. Una volta terminato, torna indietro su **Install**, seleziona il file delle GApps e avvia il flash.
3. Dopo aver installato entrambi i pacchetti, premi su **Wipe Cache/Dalvik**.
4. Infine, premi su **Reboot System** e attendi l'avvio di LineageOS.

---

Goditi il tuo smartphone veloce, pulito e privo di app inutili! 🚀
