---
title: Assistenza – NetScanner
---

# Assistenza – NetScanner

NetScanner per iPhone, iPad e Mac. In caso di domande, errori o suggerimenti, scriva a
**app.sascha@icloud.com**. Indichi per cortesia il dispositivo, la versione di iOS o macOS e la
versione dell’app (visibile nella schermata Info dell’app).

Qui trova l’[informativa sulla privacy](datenschutz-it) e le [note legali](impressum-it). (Versione tedesca: [Support](support).)

## Domande frequenti

### La scansione non trova alcun dispositivo.
L’app necessita dell’autorizzazione **“Rete locale”**. Senza di essa, il sistema scarta le
richieste verso i dispositivi della Sua rete domestica. Verifichi in *Impostazioni → Privacy e
sicurezza → Rete locale* che NetScanner sia attivato. Il dispositivo deve inoltre trovarsi nella
stessa rete Wi-Fi dei dispositivi che cerca.

### Perché mancano alcuni dispositivi?
- I dispositivi in sospensione profonda (ad esempio le serrature a batteria) non rispondono e non
  possono comparire.
- Le reti Wi-Fi per ospiti o IoT si trovano spesso in una rete diversa o separata dalla rete
  principale. I loro dispositivi non sono quindi raggiungibili dalla rete sottoposta a scansione.
- Una scansione può richiedere più tempo, perché l’app cerca anche i dispositivi che non
  rispondono al ping. Attenda il termine della scansione.
- Con l’accesso al router (solo FRITZ!Box), l’app mostra anche i dispositivi presenti nell’elenco
  dei dispositivi del box.

### Perché per alcuni dispositivi manca il produttore?
iPhone, iPad e molti altri dispositivi utilizzano un indirizzo Wi-Fi casuale (“privato”), per il
quale non esistono informazioni sul produttore. Se un dispositivo comunica altrimenti un nome o un
modello (ad esempio tramite Bonjour), l’app se ne serve per formulare un’ipotesi. iOS non mette a
disposizione delle app gli indirizzi MAC di altri dispositivi; l’app li ricava da Bonjour, UPnP,
NetBIOS o dall’elenco dei dispositivi del router.

### Perché l’app necessita della posizione?
Solo affinché il sistema fornisca il **nome e la qualità del segnale del Wi-Fi**. L’app non legge
alcuna coordinata di posizione e non memorizza né trasmette alcuna posizione.

### Che cosa accade ai miei dati nel test di velocità?
Il test di velocità utilizza il servizio di misurazione aperto di Measurement Lab (M-Lab). A
seconda della connessione, l’app trasferisce diverse centinaia di megabyte; con i dati mobili ciò
può esaurire il Suo volume di dati. M-Lab pubblica i risultati delle misurazioni, compreso
l’indirizzo IP, come dati aperti. Il test si avvia solo quando tocca “Avvia”.

### Che cosa accade ai miei dati in Stato dei servizi?
Stato dei servizi legge le pagine di stato pubbliche dei fornitori presenti nell’elenco direttamente dal Suo
dispositivo e verifica se i loro servizi rispondono. I fornitori vedono il Suo indirizzo IP; allo sviluppatore non
viene inviato nulla. Le richieste vengono inviate quando apre lo strumento per la prima volta, tocca “Verifica ora”
oppure aggiunge un fornitore o un indirizzo. L’app interroga altri fornitori e i Suoi indirizzi solo dopo che li
ha attivati o inseriti. Rimuove i Suoi indirizzi scorrendo verso sinistra.

### Stato dei servizi mostra “Raggiungibile”, ma il fornitore ha dei problemi.
Per un indirizzo aggiunto da Lei, l’app può inizialmente solo verificare se la pagina risponde. Riconosce
automaticamente molte pagine di stato e ne mostra i messaggi. Per le altre inserisca in più l’indirizzo di un feed
RSS o Atom della pagina di stato (solo `https`). L’app stima dal testo se un messaggio indica un disservizio;
un avviso può quindi essere a volte troppo cauto o mancare. Per i fornitori dell’elenco, l’icona accanto al
servizio apre la pagina di stato del fornitore.

### Come funziona l’accesso al router?
È facoltativo ed è pensato per i router FRITZ!Box. Inserisce indirizzo, nome utente e password.
L’app li utilizza per leggere l’elenco dei dispositivi direttamente dal Suo box. La password viene
memorizzata nel portachiavi del Suo dispositivo e inviata solo al Suo router. L’accesso per le
applicazioni (TR-064) deve essere consentito sul box.

### L’app si arresta in modo anomalo o mostra qualcosa di errato.
Ci indichi che cosa ha fatto subito prima dell’arresto. Il rapporto sull’arresto anomalo è utile:
*Impostazioni → Privacy e sicurezza → Analisi e miglioramenti → Dati di analisi*, voce
“NetScanner”.
