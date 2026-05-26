# 🛠️ Quick Repair Tool v18.4 - Ultimate MSP Edition

**Quick Repair Tool** è un ecosistema avanzato di diagnostica, manutenzione e risoluzione dei problemi per ambienti **Windows 10 e Windows 11**. Progettato specificamente per Sistemisti, provider MSP e tecnici Helpdesk, lo strumento centralizza e automatizza le operazioni più critiche in un'unica interfaccia grafica (GUI) responsiva, riducendo drasticamente i tempi di intervento.

---

## 🚀 Installazione e Avvio

L'installazione è centralizzata tramite pacchetto eseguibile:

1. Scarica ed esegui il file `Setup_QuickRepairTool.exe` dalla sezione [Releases].
2. Segui la rapida procedura guidata a schermo.
3. Al termine dell'installazione, il software si avvierà automaticamente.
4. Per gli avvii successivi, utilizza il comodo collegamento creato sul Desktop o nel menu Start.

⚠️ **Requisito fondamentale:** Il software opera a livello di Kernel, Registro e Servizi. Richiede **sempre** i privilegi di Amministratore (verifica che l'interfaccia mostri la dicitura verde `[OK] Licenza Amministratore` in alto a destra).

---

## 🌟 Funzionalità Principali

### 🤖 Auto-Pilot Workflow
Una sequenza logica e automatizzata (SFC, DISM, AdwCleaner, Pulizia Temp, Network Reset) per risolvere gran parte dei ticket standard con un solo clic. Il motore è asincrono: l'interfaccia non si congela mai durante le operazioni lunghe e può essere ridotta a icona.

### ☢️ Protocollo Nucleare Stampanti
Una procedura di eradicazione profonda dei driver di stampa bloccati. Bypassa i blocchi di sicurezza dello Spooler, elimina i pacchetti nativi e OEM forzatamente tramite API `printui.exe` e pulisce fisicamente i rami critici del Registro di Sistema.

### 🛡️ Backup, Ripristino e Sicurezza
* **Punti di Ripristino (VSS):** Creazione istantanea di snapshot di sistema aggirando preventivamente il blocco nativo delle 24h imposto da Windows.
* **Robocopy Mirror:** Modulo di backup ultra-veloce multithread per la salvaguardia dei profili utente.
* **Kill OneDrive:** Chiusura forzata del demone cloud per sbloccare i file di sistema bloccati.
* **Sblocco MTP Smartphone:** Reset del servizio WpdFsSvc per dispositivi mobili non riconosciuti via USB.

### 📦 Winget Integration & Toolbox "Usa e Getta"
* Installazione silenziosa e invisibile di 14 app essenziali (Chrome, 7-Zip, Adobe Reader, ecc.).
* Toolbox di diagnostica *Portable* (Revo Uninstaller, Malwarebytes, WizTree, BlueScreenView) che si scaricano, si avviano e **si auto-disinstallano** alla chiusura, per non lasciare eseguibili superflui sul PC del cliente.

### 🎨 Performance e UI Modding Sicuro (Windhawk)
Integrazione nativa con il motore *Windhawk* per iniettare modifiche all'interfaccia (es. Menu Contestuale Classico di Win10 su Win11, Separazione Etichette Taskbar, Disattivazione Galleria) direttamente in memoria RAM, garantendo massima stabilità senza corrompere il registro.

### 👻 Disinstallazione "Scorched Earth"
Il pulsante rosso **DISINSTALLA** non si limita a rimuovere l'app:
1. Pulisce la cache dei file Recenti di Windows.
2. Distrugge le tracce e il file fisico `Setup_QuickRepairTool.exe` dalle cartelle Download e Desktop (impedendo al cliente di riscaricarlo e fare danni).
3. Offre la possibilità di creare un Punto di Ripristino "Ottimale" in uscita, "fotografando" il PC perfettamente riparato.

---

## 📁 Log e Reportistica
Ogni singola operazione, sia essa un successo o un errore, viene tracciata in tempo reale nel terminale integrato e salvata permanentemente in un file `.log` univoco. I log sono consultabili nella sottocartella `Logs` all'interno della directory di installazione.

---

## ⚠️ Disclaimer
Questo strumento esegue operazioni amministrative avanzate (manipolazione del registro di sistema, arresto di servizi critici, sradicamento driver). **L'utilizzo è destinato esclusivamente a personale IT qualificato.** Si raccomanda di sfruttare la funzione "Crea Punto di Ripristino" integrata nel tool prima di lanciare operazioni distruttive su macchine di produzione o in possesso di dati sensibili.

---
*Progettato da e per sistemisti.*
