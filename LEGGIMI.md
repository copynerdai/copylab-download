# CopyLab

Un laboratorio locale per leggere e annotare il copy, ricostruire le convinzioni e collegare le prove. Versione 1.0.4.

Scarica sempre l'ultima versione dalla [pagina ufficiale CopyLab](https://github.com/copynerdai/copylab-download). È un regalo sperimentale di Simone Coria per esercitarsi nell'analisi attiva.

## Aprire il programma

- **Mac Apple Silicon:** apri il pacchetto `macOS-Apple-Silicon` e sposta `CopyLab.app` in Applicazioni oppure nella cartella che preferisci. Si avvia con un doppio clic.
- **Mac Intel:** usa il pacchetto `macOS-Intel`.
- **Windows 64 bit:** estrai completamente lo ZIP e apri `CopyLab.exe`. Mantieni insieme l'eseguibile e le altre cartelle del pacchetto.

Non servono Node, Python, account o chiavi API. Puoi lavorare senza connessione: i modelli OCR per italiano e inglese sono già inclusi. Internet serve per scaricare l'app e verificare gli aggiornamenti.

Su Mac è richiesto macOS 13 o successivo. Per scegliere il pacchetto, apri menu Apple → Informazioni su questo Mac: se compare “Chip Apple”, usa Apple Silicon; se compare un processore Intel, usa Intel. La versione Windows è per sistemi x64.

### Se compare un avviso alla prima apertura

I pacchetti non hanno una firma commerciale; la versione Mac non è notarizzata. Se hai scaricato CopyLab dalla pagina ufficiale sopra e l'avviso riguarda lo sviluppatore non verificato:

- **Mac:** prova ad aprire l'app, poi vai in Impostazioni di Sistema → Privacy e sicurezza → Apri comunque, se disponibile. [Istruzioni Apple](https://support.apple.com/it-it/102445).
- **Windows:** nell'avviso SmartScreen “PC protetto da Windows”, usa Ulteriori informazioni → Esegui comunque, se disponibile. Smart App Control e le impostazioni dei computer gestiti possono impedire l'avvio. [Indicazioni Microsoft](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

Queste istruzioni riguardano gli avvisi su app non riconosciute; non ignorare segnalazioni di malware o file danneggiati e non disattivare globalmente le protezioni del sistema.

## Aggiornare CopyLab

All'apertura, CopyLab controlla su GitHub se c'è una nuova versione. In alto a destra trovi **Aggiornamenti**: puoi controllare anche manualmente e vedere la versione installata. Quando c'è una release più recente con il pacchetto per il tuo computer, compare **Nuova versione**.

1. Premi **Scarica aggiornamento**: il browser scarica lo ZIP adatto al tuo computer.
2. Attendi “Salvato in locale” e chiudi CopyLab.
3. Su Mac, estrai lo ZIP e sostituisci l'app nella cartella in cui l'avevi collocata. Su Windows, estrai tutto lo ZIP in una nuova cartella e apri il nuovo `CopyLab.exe`; aggiorna l'eventuale collegamento sul desktop.
4. Riapri l'app. Le analisi sono in una cartella separata dal programma e restano disponibili sullo stesso computer e account utente.

L'installazione è manuale. Il controllo invia a GitHub soltanto una richiesta delle informazioni sulla release, senza documenti o note; GitHub riceve i normali dati di connessione, come l'indirizzo IP. Se sei offline o GitHub non risponde, puoi continuare a lavorare. L'app ricontrolla a ogni avvio e il pulsante **Controlla aggiornamenti** permette di riprovare senza riavviare.

È sempre utile conservare una copia dei lavori importanti con **Esporta → Progetto modificabile**. Le versioni 1.0.0–1.0.3 non hanno l'avviso: il primo aggiornamento va scaricato dalla pagina ufficiale.

## Il primo pezzo

1. Scegli **Carica un pezzo di copy**, **Parti da un testo**, oppure apri l'esempio incluso. L'esempio è inventato e modificabile.
2. Puoi caricare Markdown, PDF, Word `.docx`, HTML, testo semplice e progetti `.copylab`. Una cartella HTML o uno ZIP può includere le immagini locali.
3. Controlla il testo importato. Correggi titoli, ordine e paragrafi; poi scegli **Inizia l'analisi**. L'originale resta conservato e raggiungibile da **Originale**.
4. Seleziona un passaggio e clicca una categoria a sinistra. La selezione resta valida mentre scegli. La scheda dell'annotazione compare a destra; il commento è facoltativo.
5. Applica altre categorie allo stesso intervallo oppure seleziona passaggi al suo interno. Le attribuzioni possono essere annidate o sovrapporsi parzialmente. Ogni scheda è indipendente ed espandibile.

**Nota libera**, in cima al pannello sinistro, crea un commento sul passaggio selezionato senza assegnargli una funzione del copy. Ha un colore neutro e una scheda espandibile a destra; può sovrapporsi alle altre annotazioni, si salva ed entra nelle esportazioni. Puoi ritrovarla anche nel filtro delle note.

Un clic su una nota richiama il passaggio. Un clic su un tratto con più evidenziazioni apre le note associate. I colori identificano le categorie; le sottolineature mostrano le altre funzioni nello stesso tratto. Il filtro a destra può isolare una categoria, i dubbi o le note da ricollegare.

## Gli 11 tipi di nota

Il pannello sinistro contiene soltanto: **Nota libera**, **Promessa**, **Anello catena delle convinzioni**, **Elemento di prova**, **Meccanismo del problema**, **Meccanismo della soluzione**, **Leva emotiva**, **Gestione obiezione**, **Reason why**, **Caratteristica prodotto**, **Funzionalità prodotto**.

Caratteristica prodotto descrive com'è fatto o cosa include; Funzionalità prodotto descrive cosa fa o permette di fare. Per le altre osservazioni usa Nota libera.

I progetti precedenti conservano le annotazioni già create, inclusi commenti, colori e collegamenti. Le categorie ritirate restano visibili nelle relative note ed esportazioni; nel filtro compaiono sotto “Annotazioni precedenti” solo quando sono presenti nel documento. Il menu per creare nuove note rimane di 11 voci.

## Scrivere e modificare

Il documento è modificabile: clicca nel punto desiderato e scrivi. **Appunto nel testo** inserisce uno spazio distinto per osservazioni libere, senza richiedere una selezione. Se un testo è selezionato, l'appunto viene inserito dopo quel passaggio e non lo cancella.

La barra permette di applicare grassetto, corsivo, headline, subheadline ed elenchi. **Annulla** e **Ripeti** riguardano le modifiche di questa sessione. Anche le annotazioni e le loro note possono essere annullate. Nelle caselle delle note, le scorciatoie di modifica del sistema riguardano il campo su cui stai scrivendo; i pulsanti nella barra del documento agiscono sulla cronologia del progetto.

Quando inserisci testo, le annotazioni seguono il passaggio. Quando lo modifichi, la scheda conserva anche la citazione iniziale. Se cancelli interamente un passaggio, la relativa nota resta visibile come **da ricollegare**. Seleziona il nuovo testo, apri la scheda, espandi **Collegamenti e approfondimenti** e usa **Collega alla selezione corrente**.

## Dal testo alla mappa

**Quadro generale** raccoglie ipotesi su pubblico, desiderio, consapevolezza e sofisticazione. Puoi lasciarle aperte e rivederle dopo la lettura.

Quando selezioni un passaggio e scegli **Anello catena delle convinzioni**, la mappa aggiunge automaticamente un anello con la citazione collegata. La formulazione della convinzione la scrivi tu nel campo **Convinzione da far accettare**, nella scheda a destra, oppure direttamente nella mappa. Per esempio: “Posso riuscirci anche con poco tempo”. L’app non interpreta il testo al tuo posto.

Passaggi successivi possono essere associati a un anello esistente. Ogni **Elemento di prova** compare subito nella mappa, nella sezione omonima, con citazione e commento. Se non ha associazioni mostra **Da collegare**. Dal menu **Quale anello o claim sostiene?** puoi collegarlo a uno o più elementi; puoi anche rimuovere i collegamenti senza perdere la prova. I collegamenti sono gli stessi disponibili nella nota, sotto **Collegamenti e approfondimenti**. Una prova non collegata resta visibile e non viene attribuita automaticamente a una convinzione.

**Mappa** permette di ordinare gli anelli, esplicitare convinzione iniziale e finale, consultare i passaggi collegati e scrivere una sintesi. “Nessuna prova collegata” descrive la compilazione dell'analisi; non dichiara che il copy sia privo di prove.

## Salvare e trasferire

Il lavoro si salva automaticamente nell'archivio locale. Lo stato compare nella barra superiore. Se il salvataggio fallisce, l'app lo segnala e propone di riprovare: puoi anche esportare un progetto.

- **Progetto modificabile:** file `.copylab` con documento, originali, immagini importate, annotazioni, convinzioni e collegamenti. Si riapre in CopyLab su un altro computer. L'importazione crea una nuova analisi e non sovrascrive quella esistente.
- **HTML:** resoconto completo da leggere o stampare, con immagini incorporate.
- **Markdown:** resoconto testuale; i riferimenti alle immagini rimandano al progetto o all'HTML.
- **PDF:** resoconto impaginato e stampabile dell'analisi.

Conserva copie dei progetti esportati. Il salvataggio automatico comprende una copia precedente per il recupero, ma si trova sullo stesso computer e non è un backup esterno. **Archivia questa analisi** la sposta nell'elenco delle archiviate; resta riapribile e ripristinabile.

Archivio dell'app desktop: `~/Library/Application Support/CopyLab/analisi` su Mac e `%APPDATA%\CopyLab\analisi` su Windows. La cartella contiene i progetti correnti e le copie precedenti `.bak`. Non modificarla mentre l'app è aperta.

## Limiti della prima versione

- Il supporto Word riguarda `.docx`. I vecchi `.doc`, i file `.pages` e `.odt` vanno esportati in un formato supportato.
- HTML significa file salvati, non acquisizione da un indirizzo web. Script, form e risorse remote non vengono eseguiti o scaricati. Le immagini devono essere incorporate oppure incluse nella cartella o nello ZIP.
- PDF: massimo 100 pagine; file o insieme di risorse massimo 80 MB. La struttura e le colonne possono richiedere correzioni. I PDF protetti da password vanno prima forniti in una versione leggibile autorizzata.
- L'OCR italiano/inglese è locale e può sbagliare, soprattutto su scansioni degradate. Controlla sempre il risultato sull'originale. È pensato per testo stampato, non come riconoscitore di manoscritti.
- Si annota il testo importato e si possono selezionare immagini intere. Non si disegnano ancora rettangoli sulla pagina PDF.
- Non sono incluse analisi AI, collaborazione online o sincronizzazione cloud.

La cartella del programma può essere spostata senza spostare l'archivio delle analisi. Per trasferire il lavoro su un altro computer, usa i file `.copylab`.
