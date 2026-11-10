---
title: Informativa sulla privacy – NetScanner
---

# Informativa sulla privacy – NetScanner (iPhone, iPad e Mac)

*Questa è una traduzione dell’originale tedesco, [Datenschutzerklärung](datenschutz). In caso di dubbio prevale la versione tedesca.*

Ultimo aggiornamento: 10 novembre 2026

## 1. Titolare del trattamento

Sascha Z.
Wilhelmhofallee 68, 47799 Krefeld, Germania
E-mail: app.sascha@icloud.com

## 2. Principio

NetScanner non raccoglie, non memorizza e non trasmette alcun dato personale allo sviluppatore.
Non esistono account utente, pubblicità, tracciamento né servizi di analisi o di segnalazione
degli arresti anomali di terze parti. Tutti i risultati di una scansione di rete rimangono sul
Suo dispositivo.

## 3. Che cosa elabora l’app sul Suo dispositivo

- **Scansione di rete:** indirizzi IP, nomi host, tempi di risposta, porte aperte, indirizzi MAC
  e dati dei produttori dei dispositivi presenti nella Sua rete locale. I dati vengono tenuti
  in memoria per la visualizzazione. Inoltre, dopo una scansione l’app aggiunge una voce alla
  cronologia delle scansioni (v. sotto). Se esporta i risultati (CSV, PDF o JSON), è Lei a
  decidere dove viene salvato il file.
- **Cronologia delle scansioni e “I miei dispositivi”:** dopo ogni scansione l’app memorizza sul
  Suo dispositivo quali dispositivi (indirizzo IP, indirizzo MAC, nome, produttore) sono stati
  trovati in quale rete e in quale momento, per poter riconoscere dispositivi nuovi e mancanti.
  Memorizza inoltre titoli, note e contrassegni (“fissato”, “dispositivo noto”) nonché nomi e
  note personalizzati dei dispositivi che Lei stesso inserisce. Vengono conservate le ultime 50
  scansioni per rete, al massimo 200 in totale; le scansioni fissate vengono sempre conservate.
  I dati risiedono esclusivamente nella cartella protetta dell’app sul Suo dispositivo (nessuna
  sincronizzazione con iCloud, nessuna trasmissione). Nell’app può eliminare singole scansioni,
  la cronologia di una rete e le voci dei dispositivi; eliminando l’app vengono rimossi tutti i
  dati.
- **Rete locale:** per trovare i dispositivi nella Sua rete domestica l’app necessita
  dell’autorizzazione “Rete locale” (iOS o macOS). La scansione invia richieste ping, TCP e UDP
  (ad esempio mDNS, NetBIOS, SSDP) a indirizzi della Sua rete per individuare dispositivi attivi,
  nomi e produttori. Queste richieste non lasciano la Sua rete.
- **Strumenti di rete:** ping, ricerca DNS, traceroute (anche su IPv6), verifica delle porte,
  verifica web, verifica e-mail, browser Bonjour, Wake-on-LAN, calcolatore di sottoreti, test di
  velocità e “IP pubblico” vengono eseguiti solo quando li avvia Lei. I relativi risultati (ad
  esempio tempi di risposta, percorso, certificato, porte) vengono tenuti in memoria solo per la
  visualizzazione. Fa eccezione il test di velocità: l’app memorizza i relativi risultati (ora,
  download, upload, latenza, tipo di connessione, ubicazione del server di misurazione) come
  cronologia dei test di velocità sul Suo dispositivo (fino a 200 voci, eliminabili singolarmente
  o tutte insieme), così come lo stile di visualizzazione da Lei scelto (indicatore o barre).
- **Widget e controlli (iPhone e iPad):** il widget di rete e il widget del test di velocità
  mostrano l’ultimo indirizzo IP pubblico noto, l’ora e il numero di dispositivi dell’ultima
  scansione e l’ultima misurazione del test di velocità. A tale scopo l’app memorizza questi
  valori in un file nella cartella condivisa (App Group) dell’app e del widget sul Suo
  dispositivo. Altre app non possono accedervi. I controlli del Centro di Controllo si limitano
  ad aprire l’app. La sezione 4 descrive come i widget inviano richieste a Internet.
- **Siri e Comandi rapidi:** le azioni dell’app (ad esempio scansione, ping, test di velocità,
  traceroute, IP pubblico) vengono eseguite sul Suo dispositivo. L’app restituisce il risultato a
  Siri o all’app Comandi rapidi; l’uso che ne fa spetta a Lei.
- **Informazioni sul Wi-Fi e posizione (iPhone, iPad e Mac):** per mostrare il nome del Wi-Fi e
  la qualità della connessione, il sistema (iOS o macOS) richiede l’autorizzazione “Posizione”
  (Durante l’uso dell’app). L’app non legge coordinate di posizione e non memorizza né trasmette
  alcuna posizione.
- **Accesso al router (facoltativo, iPhone, iPad e Mac):** se inserisce indirizzo, nome utente e
  password del Suo router, l’app legge l’elenco dei dispositivi direttamente dal router. Le
  credenziali vengono memorizzate solo sul Suo dispositivo (le password nel portachiavi di iOS o
  macOS) e inviate esclusivamente al Suo router.
- **Versione per Mac:** l’app per Mac offre le stesse funzioni dell’app per iPhone e iPad
  (scansione di rete, strumenti di rete, visualizzazione del Wi-Fi, accesso al router) senza
  widget, ma con un elemento nella barra dei menu che mostra l’indirizzo IP pubblico, l’ultima
  scansione e azioni rapide. Quando lo apre, l’app richiede l’indirizzo IP pubblico (v. sezione
  4). Su richiesta, l’app si avvia all’accesso (interruttore nell’elemento della barra dei menu;
  macOS la elenca sotto “Elementi di login”, dove può disattivarla in qualsiasi momento) e resta
  in esecuzione in background affinché l’elemento della barra dei menu rimanga visibile. L’app
  viene eseguita nella sandbox di app di macOS. Determina gli indirizzi MAC tramite Bonjour,
  UPnP, NetBIOS o l’elenco dei dispositivi del router; non legge la tabella ARP del Mac.

## 4. Richieste a servizi esterni

Per le funzioni “IP pubblico” (inclusa la visualizzazione del provider) e “Test di velocità” e
per i widget, l’app invia richieste a servizi su Internet. Per ragioni tecniche, questi servizi
vedono il Suo indirizzo IP pubblico:

| Servizio | Finalità |
|---|---|
| ipify.org (api.ipify.org, api6.ipify.org) | Determinazione del Suo indirizzo IP pubblico IPv4/IPv6 |
| ipwho.is, con ipinfo.io come alternativa | Associazione dell’IP pubblico a un provider (ISP), a un numero AS e a una posizione approssimativa |
| Measurement Lab (M-Lab): locate.measurementlab.net e il server di misurazione da lì assegnato | Test di velocità: individuazione del server più vicino e misurazione di download, upload e latenza con il test aperto NDT7 |

Queste richieste vengono attivate quando apre o aggiorna lo strumento “IP pubblico” (anche
tramite il pulsante di aggiornamento nel widget di rete o aprendo l’elemento della barra dei
menu su Mac) oppure tocca “Avvia” nel test di velocità o “Avvia test” nel widget del test di
velocità. **Eccezione, widget di rete:** finché ha configurato il widget di rete nella schermata
Home, nella schermata di blocco o nella vista Oggi, esso richiede il Suo indirizzo IPv4 pubblico
a ipify.org circa ogni 30 minuti (l’ora esatta è decisa da iOS), anche senza che l’app sia
aperta, per mantenerlo aggiornato. Questa richiesta in background è diretta solo a ipify.org,
non a ipwho.is, ipinfo.io né a Measurement Lab. Termina quando rimuove il widget. Non vengono
trasmessi altri dati (nome, ID del dispositivo, dati di rete). I servizi sono gestiti da terzi.
Per il loro trattamento dei dati valgono le rispettive informative sulla privacy.

**Test di velocità e Measurement Lab:** un test di velocità trasferisce dati di prova per circa
10 secondi ciascuno in download e in upload. A seconda della connessione, si tratta di diverse
centinaia di megabyte; con una rete mobile può esaurire il Suo volume di dati. Secondo la propria
informativa sulla privacy, Measurement Lab conserva a tempo indeterminato i risultati delle sue
misurazioni e li rende pubblicamente disponibili come dati di ricerca aperti. Ciò include il Suo
indirizzo IP nonché la data e l’ora della misurazione. Il test di velocità si avvia solo quando
tocca o fa clic su “Avvia” oppure tocca “Avvia test” nel widget del test di velocità, e l’app
segnala tale pubblicazione nella finestra del test di velocità. Il widget del test di velocità
esegue la stessa misurazione; non la avvia mai da solo. Se non lo desidera, non avvii il test di
velocità. Dettagli e informazioni sull’esercizio dei Suoi diritti sono disponibili all’indirizzo
<https://www.measurementlab.net/privacy/>.

**Ping, ricerca DNS, traceroute, verifica delle porte, verifica web e verifica e-mail:** con
questi strumenti l’app invia richieste alla destinazione da Lei indicata (la verifica web apre
una connessione e legge il certificato TLS e le intestazioni HTTP) e, per il traceroute, ai
router lungo il percorso. La risoluzione dei nomi è affidata al server DNS della Sua rete.
Queste richieste vanno direttamente dal Suo dispositivo alla rispettiva destinazione e non allo
sviluppatore.

**Verifica e-mail:** l’app interroga i record DNS del dominio da Lei inserito (MX, SPF, DKIM,
DMARC, MTA-STS, TLS-RPT e BIMI). Queste interrogazioni passano attraverso il server DNS della Sua
rete, che può vederle, mentre lo sviluppatore non può vederle. Se il dominio dispone di una policy
MTA-STS, l’app la scarica tramite HTTPS dall’indirizzo `mta-sts.<dominio>` del dominio da Lei
inserito. Non vengono trasmessi altri dati e i risultati vengono tenuti in memoria solo per la
visualizzazione.

La base giuridica è l’art. 6, par. 1, lett. b) GDPR (erogazione della funzione da Lei richiamata
o configurata, ad esempio il widget).

## 5. Nessuna comunicazione a terzi, nessun tracciamento

Lo sviluppatore non riceve alcun dato dall’app. Non vi è alcun tracciamento ai sensi dell’App
Tracking Transparency di Apple.

## 6. I Suoi diritti

Poiché lo sviluppatore non tratta alcun dato personale, non può fornirLe informazioni al
riguardo. Può revocare in qualsiasi momento le autorizzazioni concesse nelle impostazioni di iOS
o macOS ed eliminare l’app, il che rimuove tutti i dati memorizzati localmente. Le spettano i
diritti previsti dal GDPR (accesso, rettifica, cancellazione, limitazione, opposizione, reclamo a
un’autorità di controllo).

## 7. Modifiche

Se l’app viene ampliata con funzioni che trasmettono dati, la presente informativa sarà
adeguata in via preventiva.

## 8. Note legali

Identificazione del fornitore: [Note legali](impressum-it).
