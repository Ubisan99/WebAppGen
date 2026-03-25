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




