# NFC Connector Releases

Canale pubblico ufficiale per gli aggiornamenti Windows di **NFC Connector**, distribuito da NetForges.

Questa repository contiene esclusivamente pacchetti compilati, note di rilascio e manifest SHA-256. Non contiene sorgenti, progetti cliente, database o credenziali.

## Installazione

Aprire la sezione **Releases**, scegliere la versione più recente e scaricare il pacchetto Windows x64. Dalla versione 0.3.0-preview.22 il connettore controlla questo canale e mostra in Home un avviso prima di qualsiasi download.

## Sicurezza

Ogni pacchetto è accompagnato da un file `*-release.json` con dimensione e SHA-256. Il connettore verifica l'hash prima di dichiarare completato il download.

Gli aggiornamenti non partono automaticamente: l'utente deve scegliere **Scarica e verifica**.