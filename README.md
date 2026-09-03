# NFC Connector Releases

Canale pubblico ufficiale per gli aggiornamenti Windows di **NFC Connector**, distribuito da NetForges.

Questa repository contiene esclusivamente pacchetti compilati, note di rilascio e manifest SHA-256. Non contiene sorgenti del connettore, progetti cliente, database o credenziali.

## Installazione

Aprire la sezione **Releases**, scegliere la versione consigliata più recente e scaricare il pacchetto Windows x64. Dalla versione 0.3.0-preview.23 il connettore controlla questo canale e mostra in Home un avviso prima di qualsiasi download.

## Sicurezza

Ogni pacchetto è accompagnato da un file `*-release.json` con dimensione e SHA-256. Il connettore verifica l'hash prima di dichiarare completato il download.

Gli aggiornamenti non partono automaticamente: l'utente deve scegliere **Scarica e verifica**. La preview 23 scarica e verifica il pacchetto; l'installazione atomica automatica sarà introdotta in una fase successiva.