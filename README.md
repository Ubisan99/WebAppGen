# WebAppGen
Generatore app tramite ollama local

# Ollama Frontend Connector

Questo progetto permette di interfacciare un'applicazione frontend con il motore di modelli AI **Ollama**. Per far funzionare correttamente l'integrazione, segui i passaggi riportati di seguito.

---

## 1. Installazione di Ollama

Se non hai ancora installato Ollama sul tuo sistema Linux, apri il terminale ed esegui il comando ufficiale di installazione:

```bash
curl -fsSL [https://ollama.com/install.sh](https://ollama.com/install.sh) | sh





sudo pkill -9 ollama; export OLLAMA_HOST=0.0.0.0 && export OLLAMA_ORIGINS="*" && ollama serve



ollama pull MODELLO


# Risoluzione Problemi di Connessione Ollama su Ubuntu

Questo file contiene le istruzioni per sbloccare la comunicazione tra Ollama e le applicazioni esterne (come interfacce web o desktop) configurando correttamente il firewall di sistema.

## 📝 Perché l'app non funziona?
Su Ubuntu, il firewall predefinito (**UFW**) spesso blocca le connessioni in entrata sulle porte non standard. Poiché Ollama utilizza la porta **11434**, l'app potrebbe non riuscire a contattare il server locale anche se quest'ultimo è attivo.

## 🛠 Soluzione: Sbloccare la porta 11434

Esegui i seguenti passaggi nel terminale per autorizzare il traffico:

1. **Aggiungi la regola al firewall:**
   ```bash
   sudo ufw allow 11434/tcp

sudo ufw reload


sudo ufw status | grep 11434





