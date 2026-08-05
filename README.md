# monkeyradioplayer
A simple web player that connects to the services of monkey radio and enable Moneky Boto AI to report Artist and Title of the song recognized

feat: mega-update player BETA (cover live, buffering banane, smart pause)



- Integrazione JSONBin per lettura brano in tempo reale dal demone Boto.
- Ricerca automatica cover art ad alta risoluzione via iTunes API (con fallback al video logo originale in caso di mancato match).
- Nuova UI di buffering dinamico con animazione "banane" 🍌 (adattiva: max 6 su desktop, max 3 su mobile).
- Logica Smart Pause: svuota la cache e forza il ricaricamento del live se la pausa supera i 30 secondi (evita lag e salti temporali sul riavvio).
- Pieno supporto Media Session API per invio metadati e cover art ai dispositivi Bluetooth e alla schermata di blocco iOS/Android.
- Gestione avanzata Wake Lock per prevenire lo standby e auto-reconnect stabile in caso di micro-disconnessioni.

