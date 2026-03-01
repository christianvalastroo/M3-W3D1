🎓 Geeks Landing Page
Landing page responsive sviluppata con Bootstrap 5.3.8, ispirata a un template moderno per piattaforme di corsi online. Il progetto riproduce fedelmente una struttura reale con navbar avanzata, hero section, griglie di card corsi responsive con rating dinamico a stelle e footer minimal.
🚀 Tecnologie utilizzate
HTML5
CSS3
Bootstrap 5.3.8
Bootstrap Icons
Variabili CSS (:root)
📂 Struttura del progetto
/assets
  /imgs
index.html
style.css
README.md
🧱 Sezioni implementate
Navbar
Navbar completa con logo, menu dropdown (Browse, Landings, Pages, Accounts), campanella notifiche e avatar con dropdown profilo. Struttura semantica migliorata con utilizzo corretto degli elementi button e layout completamente responsive.
Hero Section
Sezione introduttiva con titolo principale, descrizione e call-to-action. Layout costruito con sistema Grid Bootstrap e personalizzazione tramite variabili CSS.
Sezione Informazioni
Blocco a tre colonne con icone e testo descrittivo. Utilizzo di Flex utilities per l’allineamento verticale e comportamento responsive.
Sezioni Corsi
Tre sezioni distinte:
Recommended
Most Popular
Trending
Ogni sezione include:
Card responsive con griglia row-cols-2 row-cols-md-3 row-cols-lg-4
Hover effect sulle card
Rating dinamico con stelle (bi-star-fill, bi-star-half, bi-star)
Prezzo attuale + prezzo barrato
Footer card con autore e icona bookmark
Frecce di navigazione UI posizionate esternamente tramite position: absolute
Layout responsive:
2 colonne su mobile
3 colonne su tablet
4 colonne su desktop
Alcune card vengono nascoste sui breakpoint inferiori usando:
d-none d-md-block
d-none d-lg-block
Footer
Footer minimal con separatore superiore, copyright e link di navigazione (Privacy, Terms, Feedback, Support). Layout centrato su mobile e distribuito su desktop.
🎨 Organizzazione CSS
Il file style.css è organizzato in sezioni logiche:
Variabili globali (:root)
Base
Navbar
Hero
Card
Rating
Frecce esterne
Footer
Le variabili CSS permettono gestione centralizzata di colori, ombre, dimensioni e spaziature, migliorando la manutenzione del codice.
📱 Responsive Design
Il progetto segue un approccio mobile-first utilizzando:
Sistema Grid Bootstrap
Utility classes (d-flex, gap, justify-content-*)
Breakpoints (md, lg, xl)
🧠 Obiettivi del progetto
Comprendere a fondo il sistema Grid di Bootstrap 5
Utilizzare correttamente le utility classes
Strutturare layout responsive professionali
Organizzare CSS in modo scalabile
Replicare un template reale in modo fedele
📌 Possibili miglioramenti futuri
Implementazione di un vero carousel funzionante
Filtri dinamici per le card
Dark mode
Animazioni avanzate
Versione con backend dinamico
