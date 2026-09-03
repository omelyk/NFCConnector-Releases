# NFC Connector Releases

Canale pubblico ufficiale per gli aggiornamenti Windows di **NFC Connector**, distribuito da NetForges.

Questa repository contiene esclusivamente pacchetti compilati, note di rilascio e manifest SHA-256. Non contiene sorgenti del connettore, progetti cliente, database o credenziali.

## Installazione

Aprire la sezione **Releases**, scegliere la versione consigliata più recente e scaricare il pacchetto Windows x64. Il connettore controlla questo canale e mostra in Home un avviso prima di qualsiasi download. Il badge arancione **VERSIONE** consente anche di ripetere manualmente il controllo.

La versione installata è visibile già nella schermata di accesso dalla preview.25.

La preview.29 corregge il wizard iniziale: categorie e prodotti vengono sbloccati dal test di schema e permessi, senza richiedere la sincronizzazione completa del catalogo. Il mapping Published salvato nel workspace è riconosciuto direttamente.

## Sicurezza

Ogni pacchetto è accompagnato da un file `*-release.json` con dimensione e SHA-256. Il connettore verifica l'hash prima di dichiarare completato il download.

Gli aggiornamenti non partono automaticamente: l'utente deve scegliere **Scarica e verifica**. Il connettore scarica e verifica il pacchetto; l'installazione atomica automatica sarà introdotta in una fase successiva.