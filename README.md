# Sistem de Management al Bibliotecii (Python)

Acest proiect reprezintă o soluție completă pentru gestionarea unei biblioteci, construită pe baza principiilor de Programare Orientată pe Obiect (OOP) și Programare Funcțională. Aplicația permite administrarea cărților, autorilor, utilizatorilor și proceselor de împrumut printr-un meniu interactiv.

## Concepte Tehnice Implementate

Aplicația a fost dezvoltată respectând următoarele cerințe tehnice:

* **Programare Orientată pe Obiect (OOP):** Implementarea de clase precum `Biblioteca`, `Carte`, `Autor`, `Persoana` și `Utilizator`.
* **Programare Funcțională:** Utilizarea funcțiilor `lambda`, `filter` și `map` pentru căutarea și filtrarea eficientă a proiectelor sau resurselor.
* **Decoratori:** Implementarea de decoratori pentru logarea apelurilor funcțiilor (inclusiv timpul de execuție) și verificarea permisiunilor.
* **Tratarea Excepțiilor:** Gestiunea erorilor prin excepții personalizate pentru cazuri precum `CarteNegasitaException` sau `UtilizatorInexistentException`.

## Funcționalități Principale

* **Administrare Resurse:** Adăugarea, ștergerea și actualizarea cărților, autorilor și utilizatorilor.
* **Alocare și Urmărire:** Gestionarea procesului de împrumut și urmărirea disponibilității resurselor.
* **Rapoarte:** Generarea de rapoarte de stare pentru stocul de carte și activitatea utilizatorilor.
* **Meniu Interactiv:** O interfață de consolă prietenoasă pentru navigarea prin sistem.
