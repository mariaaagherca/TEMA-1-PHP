# TEMA-1-PHP
# 🏥 MediCareHub

**MediCareHub** este o aplicație web menită să simplifice gestionarea activităților unui spital modern – de la evidența pacienților și internărilor, până la facturare, servicii medicale și administrarea personalului medical.  
Proiectul face parte dintr-un studiu privind modelarea și implementarea bazelor de date relaționale pentru domeniul medical.

---

## 🌐 Descriere generală

Aplicația este structurată pe mai multe niveluri de acces, în funcție de rolul utilizatorului:

- 🧑‍💼 **Administratorul spitalului** – gestionează saloanele, personalul medical, tarifele și conturile utilizatorilor.
- 👨‍⚕️ **Doctorul** – actualizează fișele pacienților, stabilește diagnostice și prescrie tratamente.
- 👩‍⚕️ **Asistentul medical** – monitorizează pacienții internați și actualizează starea lor zilnică.
- 🧍‍♂️ **Pacientul** – poate vizualiza informațiile proprii, istoricul tratamentelor și factura finală.

Aplicația oferă o **interfață publică** (pentru pacienți) și una **administrativă**, disponibilă doar după autentificare.  
Drepturile de acces sunt gestionate automat în funcție de rol.

---

## 🧠 Scopul proiectului

Scopul principal al aplicației **MediCareHub** este **automatizarea proceselor medicale și administrative** din cadrul unui spital.  
Prin centralizarea datelor într-o bază de date MySQL și o interfață web intuitivă, sistemul:

- reduce erorile umane,
- accelerează procesele interne,
- facilitează colaborarea între personalul medical și administrativ,
- oferă pacienților acces la informațiile proprii într-un mod sigur și organizat.

---

## 🧩 Componente principale

| Componentă | Descriere |
|-------------|-----------|
| **`medhub.html`** | Pagina principală de prezentare a aplicației și a structurii generale. |
| **`main.html`** | Modelul conceptual al bazei de date și relațiile dintre entități. |
| **`style.css`** | Fișierul de stil comun pentru întreaga aplicație. |
| **`administrator.png`**, **`doctor.png`**, **`pacient.png`** | Diagrame UML de secvență pentru fiecare rol principal. |

---

## 🗂️ Model conceptual

Modelul bazei de date include următoarele entități principale:

- **Pacient**
- **Doctor**
- **Salon**
- **Internare**
- **Tratament**
- **Serviciu_Medical**
- **Factura**
- **Internare_Serviciu**

Fiecare entitate conține atribute relevante pentru activitatea medicală, iar relațiile (1:N, M:N, 1:1) sunt clar definite și vizualizate în diagrama ER.

---

## 📊 Diagrame UML de secvență

Diagramele UML evidențiază fluxul de interacțiuni dintre utilizatori și backend:

1. 🧍‍♂️ **Pacient** – logare, vizualizare fișă medicală, descărcare factură.  
2. 👨‍⚕️ **Doctor** – autentificare, gestionare pacienți, prescriere tratamente.  
3. 🧑‍💼 **Administrator** – administrarea saloanelor și a conturilor de utilizatori.

Aceste diagrame sunt disponibile în pagina `medhub.html`, în secțiunea „Diagrame UML de secvență”.

---

## ⚙️ Tehnologii utilizate

- **HTML5** – structurarea paginilor web  
- **CSS3 (custom styles)** – design și estetică modernă  
- **PHP & MySQL** – (menționate ca backend teoretic) pentru stocarea și gestionarea datelor  
- **PlantUML** – pentru generarea diagramelor UML de secvență



