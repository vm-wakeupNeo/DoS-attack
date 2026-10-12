# Denial of Service (DoS) Lab — Metasploitable 2

## Descrizione

Questo progetto documenta un laboratorio pratico di cybersecurity dedicato allo studio di un attacco Denial of Service (DoS) in un ambiente virtualizzato e controllato.

Il test è stato eseguito su **Metasploitable 2**, una macchina virtuale intenzionalmente vulnerabile, utilizzata per attività didattiche e sperimentazioni di sicurezza informatica.

L'obiettivo è comprendere gli effetti di un attacco DoS sulla disponibilità di un servizio e osservare il comportamento del sistema durante il test.

## Obiettivi del laboratorio

- Comprendere il concetto di Denial of Service (DoS).
- Osservare gli effetti di un traffico anomalo sulla disponibilità di un servizio.
- Familiarizzare con l'utilizzo di Kali Linux in un laboratorio di cybersecurity.
- Analizzare il comportamento della macchina bersaglio durante il test.
- Comprendere l'importanza della disponibilità dei servizi nella sicurezza informatica.

## Ambiente di laboratorio

- **Attacker machine:** Kali Linux
- **Target machine:** Metasploitable 2
- **Environment:** Virtual machines
- **Network:** Isolated virtual network
- **Lab type:** Denial of Service (DoS)

## Metodologia

Il laboratorio è stato organizzato nelle seguenti fasi:

1. **Lab Setup** — Preparazione delle macchine virtuali e della rete di laboratorio.
2. **Connectivity Check** — Verifica della connettività tra Kali Linux e Metasploitable 2.
3. **DoS Test** — Esecuzione controllata del test sulla macchina vulnerabile.
4. **Observation** — Osservazione del comportamento del target durante il test.
5. **Documentation** — Registrazione dei comandi utilizzati e dei risultati osservati.

## Strumenti utilizzati

- Kali Linux
- Metasploitable 2
- Virtual machine software
- Linux command-line tools

## Contenuti
- Report completo del laboratorio in formato PDF
- Script contenente i comandi utilizzati e i rispettivi output lato attaccante
- Script contenente i comandi utilizzati e i rispettivi output lato vittima

**NB:** lo script lato vittima è stato registrato in un secondo momento. Di conseguenza, alcuni dati possono differire leggermente da quelli riportati nel report. Ad esempio, l'indirizzo IP della vittima indicato nella documentazione è `192.168.1.19`, mentre nello script è `192.168.1.23`.

Fatta eccezione per piccole incongruenze come quella descritta, la documentazione dell'attacco è corretta.

## Risultati e osservazioni

Il laboratorio ha permesso di approfondire il funzionamento di un test DoS in un ambiente controllato e di osservare il rapporto tra traffico generato, disponibilità del servizio e comportamento del sistema bersaglio.

I risultati dettagliati, i comandi utilizzati e le eventuali evidenze raccolte sono documentati nei file presenti nella repository.

## Competenze sviluppate

- Denial of Service fundamentals
- Virtualized security labs
- Linux command-line usage
- Network connectivity testing
- Basic security testing and documentation

## Note sulla sicurezza

Questo laboratorio è stato progettato esclusivamente per finalità didattiche e di apprendimento, utilizzando una macchina virtuale intenzionalmente vulnerabile in un ambiente di test autorizzato.

I test DoS possono compromettere la disponibilità dei servizi. Non eseguire prove di questo tipo su sistemi, reti o servizi di terzi senza un'autorizzazione esplicita.

---

*Hands-on cybersecurity learning through controlled and documented lab environments.*
