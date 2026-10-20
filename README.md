# Asta Scout per Android

Distribuzione degli APK Android di Asta Scout e dei metadati per gli aggiornamenti. Il codice sorgente e gli archivi personali sono mantenuti separatamente e non sono pubblicati qui.

## Scarica e installa

Apri la pagina [Releases](https://github.com/danielperrella/asta-scout-android/releases), espandi **Assets** e scarica l’APK **arm64-release** per il telefono Android 14. Aprilo sul telefono e consenti l’installazione dalla fonte scelta quando Android lo richiede.

L’archivio parte vuoto. OCR e analisi di base funzionano sul dispositivo senza account o backend. Serve Internet per importare annunci/documenti e controllare nuove versioni.

## Aggiornamenti

Dalla versione 0.1.1 l’app controlla all’avvio il manifest pubblico `update.json` e propone **Aggiorna** oppure **Più tardi**. Il download parte solo dopo il consenso. L’APK viene verificato per dimensione, SHA-256, identità, versione e firma prima di aprire la conferma di installazione Android.

Se hai la versione 0.1.0 (5), installa manualmente la prima versione con updater dalla pagina Releases. Per gli aggiornamenti installa sopra l’app esistente senza disinstallare. Esporta prima un backup da **Impostazioni → Backup e ripristino**.

## Dati e verifiche

I documenti, le note e i backup personali restano sul dispositivo; questo repository contiene solo materiale di distribuzione. La disponibilità di una nuova versione non blocca l’uso offline dell’archivio. Risultati dei test e limiti sono indicati nelle singole release.
