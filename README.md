# 🎓 Geeks Landing Page

Landing page responsive sviluppata con Bootstrap 5.3.8, ispirata a un template moderno per piattaforme di corsi online.  
Il progetto riproduce una struttura reale con navbar avanzata, hero section, griglie di card corsi responsive con rating dinamico a stelle e footer minimal.

---

## 🚀 Tecnologie utilizzate

- HTML5  
- CSS3  
- Bootstrap 5.3.8  
- Bootstrap Icons  
- Variabili CSS (:root)  

---

## 📂 Struttura del progetto

/assets  
  /imgs  
index.html  
style.css  
README.md  

---

## 🧱 Sezioni implementate

### Navbar
- Logo
- Menu dropdown (Browse, Landings, Pages, Accounts)
- Campanella notifiche
- Avatar con dropdown profilo
- Struttura semantica migliorata con uso corretto di button
- Layout completamente responsive

### Hero Section
- Titolo principale
- Descrizione
- Call-to-action
- Layout con Grid Bootstrap
- Personalizzazione tramite variabili CSS

### Sezione Informazioni
- 3 colonne con icone
- Allineamento con Flex utilities
- Layout responsive

### Sezioni Corsi
Tre sezioni:
- Recommended
- Most Popular
- Trending

Ogni sezione include:
- Card responsive con griglia: row-cols-2 row-cols-md-3 row-cols-lg-4
- Hover effect
- Rating dinamico con stelle:
  - bi-star-fill
  - bi-star-half
  - bi-star
- Prezzo attuale + prezzo barrato
- Footer card con autore e bookmark
- Frecce di navigazione UI posizionate esternamente

Responsive:
- 2 colonne su mobile
- 3 su tablet
- 4 su desktop

Card nascoste ai breakpoint inferiori tramite:
- d-none d-md-block
- d-none d-lg-block

### Footer
- Border-top separatore
- Copyright
- Link Privacy / Terms / Feedback / Support
- Centrato su mobile, distribuito su desktop

---

## 🎨 Organizzazione CSS

Il file style.css è strutturato in sezioni:

1. Variabili globali (:root)
2. Base
3. Navbar
4. Hero
5. Card
6. Rating
7. Frecce esterne
8. Footer

Le variabili permettono gestione centralizzata di:
- Colori
- Ombre
- Dimensioni
- Spaziature

---

## 📱 Responsive Design

Il progetto segue un approccio mobile-first utilizzando:
- Sistema Grid Bootstrap
- Utility classes (d-flex, gap, justify-content-*)
- Breakpoints (md, lg, xl)

---

## 🧠 Obiettivi del progetto

- Comprendere il sistema Grid di Bootstrap 5
- Utilizzare correttamente le utility classes
- Creare layout responsive professionali
- Organizzare CSS in modo scalabile
- Replicare un template reale in modo fedele

---

## 📌 Possibili miglioramenti futuri

- Implementare vero carousel funzionante
- Filtri dinamici per le card
- Dark mode
- Animazioni avanzate
- Versione con backend dinamico

---

👨‍💻 Progetto realizzato a scopo didattico per approfondire Bootstrap 5 e sviluppo frontend responsive.
