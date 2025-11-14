=== WooCommerce Campi Fiscali Italiani ===
Contributors: Carlo Fischetti
Author website: https://carlofischetti.it
Tags: woocommerce, fatturazione, partita iva, codice fiscale, italia, checkout, fattura elettronica, pec, sdi
Requires at least: 5.8
Tested up to: 6.7
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Aggiunge campi fiscali italiani al checkout di WooCommerce: Codice Fiscale, Partita IVA, PEC e Codice SDI per la fatturazione elettronica.

== Description ==

WooCommerce Campi Fiscali Italiani è il plugin essenziale per tutti i negozi WooCommerce italiani che necessitano di raccogliere i dati fiscali dei clienti durante il checkout.

Il plugin aggiunge automaticamente i campi necessari per la fatturazione elettronica italiana, distinguendo tra clienti privati e aziende.

= Caratteristiche Principali =

 Select Tipo di Cliente: Permette al cliente di scegliere se è un privato o un'azienda
 Per Clienti Privati: Campo Codice Fiscale con validazione del formato italiano
 Per Aziende: 
   Partita IVA (con validazione 11 cifre)
   PEC (Posta Elettronica Certificata)
   Codice SDI/Codice Destinatario (7 caratteri alfanumerici)
 Validazione Automatica: Tutti i campi vengono validati in tempo reale
 Visualizzazione Completa: I dati fiscali appaiono in:
   Pagina "Grazie per il tuo ordine"
   Backend ordini (area amministratore)
   Email di notifica ordine
 Zero Configurazione: Funziona immediatamente dopo l'attivazione, senza bisogno di impostazioni
 Rimozione Campo Azienda: Disabilita automaticamente il campo "Azienda" predefinito di WooCommerce
 HPOS Ready: Compatibile con il nuovo sistema di archiviazione ordini ad alte prestazioni di WooCommerce

= Ideale Per =

 E-commerce italiani
 Negozi che necessitano di emettere fatture elettroniche
 Rivenditori B2B e B2C
 Tutti i siti che devono rispettare la normativa italiana sulla fatturazione

= Requisiti =

 WooCommerce 6.0 o superiore
 WordPress 5.8 o superiore
 PHP 7.4 o superiore

= Lingue Disponibili =

 Italiano (predefinito)
 Pronto per traduzioni in altre lingue

= Privacy e GDPR =

Il plugin salva i dati fiscali forniti dal cliente nell'ordine. È responsabilità del gestore del sito informare gli utenti sul trattamento di questi dati secondo il GDPR.

== Installation ==

= Installazione Automatica =

1. Vai su Plugin > Aggiungi Nuovo nella dashboard di WordPress
2. Cerca "WooCommerce Campi Fiscali Italiani"
3. Clicca su "Installa Ora" e poi su "Attiva"
4. Il plugin funzionerà immediatamente senza bisogno di configurazione

= Installazione Manuale =

1. Scarica il file .zip del plugin
2. Vai su Plugin > Aggiungi Nuovo > Carica Plugin
3. Seleziona il file .zip e clicca su "Installa Ora"
4. Attiva il plugin
5. Il plugin funzionerà immediatamente senza bisogno di configurazione

= Dopo l'Installazione =

Non è necessaria alcuna configurazione. I campi fiscali appariranno automaticamente nella pagina di checkout.

== Frequently Asked Questions ==

= Il plugin richiede configurazione? =

No, il plugin funziona immediatamente dopo l'attivazione. Non ci sono pagine di impostazioni perché tutti i campi vengono aggiunti automaticamente.

= Posso personalizzare i campi? =

Sì, essendo un plugin open source puoi modificare il codice secondo le tue necessità. Il codice è ben documentato e segue le best practice di WordPress.

= I campi sono obbligatori? =

Il campo "Tipo di Cliente" è sempre obbligatorio. Gli altri campi sono obbligatori solo in base alla selezione:
- Privato: Codice Fiscale obbligatorio
- Azienda: Partita IVA obbligatoria, PEC e SDI opzionali

= Cosa succede al campo "Azienda" predefinito di WooCommerce? =

Viene automaticamente nascosto e disabilitato per evitare confusione con i nuovi campi dedicati alle aziende.

= È compatibile con la fatturazione elettronica? =

Sì, raccoglie tutti i dati necessari per la fatturazione elettronica italiana (P.IVA, PEC, SDI).

= È compatibile con HPOS? =

Sì, il plugin è completamente compatibile con il nuovo sistema High-Performance Order Storage di WooCommerce.

= Funziona con i temi personalizzati? =

Sì, il plugin utilizza gli hook standard di WooCommerce ed è compatibile con tutti i temi che seguono gli standard WooCommerce.

= È traducibile? =

Sì, il plugin è predisposto per le traduzioni. Puoi usare Loco Translate o WPML per tradurlo.

== Screenshots ==

1. Campo "Tipo di Cliente" nella pagina di checkout
2. Campi per clienti privati (Codice Fiscale)
3. Campi per aziende (P.IVA, PEC, SDI)
4. Visualizzazione dati fiscali nel backend ordini
5. Dati fiscali nella pagina "Grazie per il tuo ordine"
6. Dati fiscali nelle email di notifica

== Changelog ==

= 1.0.0 - 2024-11-14 =
 Prima release pubblica
 Aggiunto campo select "Tipo di Cliente"
 Aggiunto campo Codice Fiscale per privati
 Aggiunti campi P.IVA, PEC e SDI per aziende
 Validazione automatica di tutti i campi
 Visualizzazione dati in backend, frontend e email
 Rimozione automatica campo "Azienda" predefinito
 Compatibilità con HPOS
 Compatibilità con WooCommerce 9.3

== Upgrade Notice ==

= 1.0.0 =
Prima release del plugin. Installalo per aggiungere i campi fiscali italiani al tuo checkout WooCommerce.

== Supporto ==

Per supporto, segnalazione bug o richieste di nuove funzionalità:

 Apri una issue su GitHub (https://github.com/carlofischetti/wc-campi-fiscali-italiani)
 Visita il forum di supporto WordPress (https://wordpress.org/support/plugin/wc-campi-fiscali-italiani)
 Contattaci su carlofischetti.it (https://carlofischetti.it/contatti)

== Contribuire ==

Il plugin è open source! Contributi e pull request sono benvenuti su GitHub (https://github.com/carlofischetti/wc-campi-fiscali-italiani).

== Crediti ==

Sviluppato con ❤️ per la community italiana di WooCommerce.
