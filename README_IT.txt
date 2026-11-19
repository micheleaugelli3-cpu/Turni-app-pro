TURNIAPP PRO - WEB APP INSTALLABILE (PWA)

CONTENUTO
- index.html: applicazione TurniApp Pro 6.2.3 originale, calendario e funzioni mantenuti.
- manifest.json: impostazioni per installazione su Android/iPhone.
- sw.js: cache locale della struttura dell'app.
- icons/: icone installabili.

PUBBLICAZIONE
La PWA deve essere pubblicata su un indirizzo HTTPS (per esempio GitHub Pages).
Non aprire index.html direttamente dal file manager: manifest e service worker richiedono HTTPS o localhost.

INSTALLAZIONE ANDROID
1. Aprire l'indirizzo HTTPS con Chrome.
2. Menu ⋮ > Installa app (oppure Aggiungi a schermata Home).

INSTALLAZIONE IPHONE
1. Aprire l'indirizzo HTTPS con Safari.
2. Toccare Condividi > Aggiungi alla schermata Home.

DATI E PRIVACY
I turni e le buste paga continuano a essere salvati localmente nel browser/dispositivo tramite localStorage.
Non è prevista sincronizzazione cloud tra dispositivi. Usare la funzione di backup per trasferire i dati.

LIMITI OFFLINE
La struttura principale dell'app viene messa in cache dopo la prima visita. Tailwind CSS, PDF.js e Tesseract.js sono caricati da CDN: alcune funzioni di stile e soprattutto lettura PDF/OCR richiedono connessione Internet.

NOTA
Questa è una web app installabile (PWA), non un APK Android né un pacchetto App Store iOS.
