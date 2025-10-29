# 🧠 Lezione sul Modello ISO/OSI

## 🎯 Obiettivo
Capire come funziona la comunicazione tra due computer in rete, grazie ai **7 livelli del modello ISO/OSI**.

---

## 🔹 Cos’è il modello ISO/OSI

Il **modello ISO/OSI** (*Open Systems Interconnection*) è uno **schema teorico** che spiega come i dati vengono trasmessi da un computer all’altro attraverso **7 livelli**, ognuno con un compito preciso.

Ogni livello:
- comunica solo con quello **superiore** e **inferiore**,
- ha funzioni specifiche per gestire i dati durante la trasmissione.

---

## 🧩 I 7 LIVELLI (dall’alto verso il basso)

| Livello | Nome | Funzione principale | Esempi |
|----------|------|---------------------|---------|
| **7** | **Applicazione** | Interfaccia tra utente e rete. Fornisce i servizi per le applicazioni. | HTTP, HTTPS, FTP, SMTP, DNS |
| **6** | **Presentazione** | Traduce, cripta e comprime i dati. | SSL/TLS, JPEG, MP3 |
| **5** | **Sessione** | Gestisce la connessione (apertura, mantenimento, chiusura). | Sessioni remote, login |
| **4** | **Trasporto** | Controlla che i dati arrivino corretti, li divide in pacchetti. | TCP, UDP |
| **3** | **Rete** | Gestisce gli indirizzi IP e il percorso dei pacchetti. | IP, router |
| **2** | **Collegamento dati** | Controlla la trasmissione locale tra due dispositivi. | Ethernet, Wi-Fi, MAC address |
| **1** | **Fisico** | Trasmette i bit (0 e 1) su cavi o onde radio. | Cavi, antenne, fibra ottica |

---

## ⚙️ Esempio pratico

📱 **Invio di un messaggio WhatsApp**

1. **Applicazione** – scrivi “Ciao!” nell’app.  
2. **Presentazione** – il testo viene codificato (es. UTF-8).  
3. **Sessione** – si stabilisce la connessione con il server.  
4. **Trasporto** – i dati vengono divisi in pacchetti (TCP).  
5. **Rete** – i pacchetti ricevono un indirizzo IP.  
6. **Collegamento dati** – preparazione per la trasmissione Wi-Fi.  
7. **Fisico** – il segnale viaggia come onde radio fino al router.  

👉 Quando arriva al destinatario, il processo si svolge **al contrario** (dal livello 1 al 7).

---

## 🔄 Confronto OSI e TCP/IP

| Caratteristica | OSI | TCP/IP |
|----------------|-----|--------|
| Numero di livelli | 7 | 4 |
| Origine | ISO (modello teorico) | DARPA (modello pratico) |
| Scopo | Studiare la comunicazione | Far funzionare Internet |
| Livelli principali | Applicazione, Presentazione, Sessione, Trasporto, Rete, Collegamento, Fisico | Applicazione, Trasporto, Internet, Accesso rete |

---

## 🧠 Mnemoniche per ricordarli

**In inglese:**  
➡️ *All People Seem To Need Data Processing*

**In italiano:**  
➡️ *Anna Prega Sempre Tutti Nel Cuore Forte*

---

## 📊 Schema visuale dei livelli
