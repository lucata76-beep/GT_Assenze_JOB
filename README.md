# GT_Assenze_JOB
Web app per segnare le assenze dal lavoro

App a file unico (`index.html`, HTML + CSS + JavaScript senza framework) per registrare le ore di assenza di un singolo dipendente: FERIE (FER), PAR e LEGGE 104 (104). Pensata per Safari su iPhone e per la schermata Home.

## Dati e privacy
- I dati (assenze, impostazioni) restano nel browser del dispositivo (localStorage). L'app non invia nulla a server o a terzi.
- Backup e ripristino tramite file JSON dalla schermata Impostazioni.
- L'unica risorsa esterna è la libreria jsPDF 3.0.3 caricata da cdnjs.cloudflare.com, usata solo per generare il PDF.

## Valori contrattuali
L'app non contiene monte ore, maturazioni o tetti di permesso: vanno inseriti dall'utente nelle Impostazioni. Finché mancano, l'app mostra "DA IMPOSTARE" e non calcola.
