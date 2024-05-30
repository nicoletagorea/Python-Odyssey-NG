# Tema Finală
---
## Mesaj de la Edy
Hey Hey mici ***pythoniști***! 🐍

Sper că ați avut parte de câteva săptămâni extrem de productive și utile de-a lungul acestui curs. Aceasta va fi ultima temă pentru acasă pe care o veți primi de la mine. 🥳 (în sfârșit scăpați de mine și eu de voi cum s-ar zice :) )

Până a trece la subiectul propriu-zis, aș vrea să vă mulțumesc pentru răbdarea și atenția acordată în timpul acestui curs. Sper că ați reușit să învățați câte ceva și că ați reușit să vă dezvoltați abilitățile de programare în Python. Iar dacă cel puțin unul dintre voi a reușit să-și descopere pasiunea pentru programare, atunci misiunea mea a fost îndeplinită. 🥰

Țineți minte că în IT, învățarea niciodată nu se termină, așa că nu vă opriți aici și nu vă lăsați limitați de cunoștințele pe care le aveți. Vorba aia "Google it!" sau versiunea mai nouă "Chat GPT it!". 🚀

În fine, să trecem la subiectul propriu-zis, ultima bătaie de cap. 🤓

---
## SARCINA

Tema aceasta va fi puțin mai deosebită decât celelalte. Ea are ca scop să vă ghideze în lucrul cu un proiect, dar în același timp să verifice cât de bine ați înțeles materialele lecțiilor 17-21 și nu numai.

Din fericire pentru voi, alături de această temă veți avea și un ghid după care puteți realiza tema. Ghidul îl găsiți mai jos. 📝

Scopul final al acestei teme este să aveți un proiect funcțional, care ar reprezenta un exemplu despre cum ar fi bine să arate un proiect în Python. La finalul temei veți avea un nou repositoriu pe GitHub, asigurați-vă că acesta va fi public astfel încât să-l putem găsi când vom verifica temele.

📌 ***Asigurați-vă că respectați ghidul(dar în același timp sunteți liberi să fiți ingenioși)***

---
## GHID

> ℹ️ În majoritatea cazurilor, un programist petrece mai mult timp citind cod decât scriind cod. De aceea, e important să puteți înțelege codul scris de alții și înțelegând să puteți modifica și să adăugați funcționalități noi.

### 1. Fork la proiect

> 📘 Ați fost acceptați ca Python Developer într-un proiect nou. Proiectul este unul open-source și este scris în Python. Pentru a începe să lucrați la proiect, trebuie să faceți un fork la acesta. Fork-ul reprezintă o copie a proiectului original, dar care se află sub controlul vostru. Puteți realiza un fork la orice proiect de pe GitHub, fără a cere permisiunea autorului proiectului.

În cazul dat, eu deja am început lucrul la proiect, dar din cauza că am prea multe proiecte pe cap, am decis să apelez la voi pentru ca să-l terminați. Proiectul se numește `odyssey_project` și îl găsiți în acest [link.](https://github.com/SigmoidAI/odyssey_project)

- Cum fac un fork la proiect?
    - Pentru a face un fork la proiect, accesați link-ul de mai sus și apăsați butonul `Fork` din dreapta sus a paginii.
    - După ce ați făcut fork la proiect, veți fi redirecționați pe o pagină nouă care va extrage proiectul în contul vostru de GitHub, apăsați pe butonul `Create Fork`.
    - Felicitări! Ați făcut fork la proiect cu succes.

### 2. Structura proiectului

Proiectul `odyssey_project` este un proiect open-source care are ca scop să ajute oamenii să-și găsească locuința perfectă. Proiectul este împărțit în mai multe module, fiecare modul având o funcționalitate specifică. Mai jos găsiți structura și descrierea proiectului.

> 📘 The Odyssey Project is a movie recommendation system built with Python. It involves web scraping using BeautifulSoup to collect popular movie data, processing the data for consistency, and storing it in a JSON file. The project includes an API for interacting with the data, allowing users to retrieve, add, update, and delete movie records. Comprehensive testing ensures data integrity and code quality, with all dependencies managed in a virtual environment. The project emphasizes clean code principles and includes documentation for installation, usage, and testing. Additionally, the scraping process will be optimized with parallelization for efficiency.

### 3. Setup

- Creați un mediu virtual nou pentru proiectul vostru folosind Python versiunea 3.12. (dacă nu vă reușește apelați la lecția despre virtual environments)
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

### 4. Web Scraping

- Folosiți BeautifulSoup pentru a extrage informații de la Google Search despre filmele populare într-un anumit an.
- Extrageți și stocați următoarele informații pentru fiecare film:
    - Numele filmului
    - Durata filmului
    - Tipul
    - Genul

### 5. Data Processing

- Curățați și procesați datele despre filme pentru a asigura consistența și acuratețea.
- Convertiți durata într-un format standard (ex. minute).
- Normalizați categoriile de vârstă la un set standard de valori.
- Standardizați numele genurilor pentru consistență.

### 6. Data Storage

- Salvați informațiile procesate despre filme într-un fișier JSON, care va acționa ca o bază de date improvizată.

### 7. API Creation

- Dezvoltați un API pentru a interacționa cu fișierul JSON.
- API-ul ar trebui să suporte următoarele operații:
    - Obține toate filmele
    - Obține un film specific
    - Actualizează un film
    - Șterge un film
    - Adaugă un film nou

### 8. Testing

- Creați un fișier de test pentru a testa funcțiile de procesare a datelor folosite pentru datele extrase.

### 9. Dependencies

- Listați toate dependențele în fișierul `requirements.txt`.
    ```bash
    pip freeze > requirements.txt
    ```

### 10. Documentation

- Furnizați un fișier `README.md` care să includă:
    - Instrucțiuni pentru instalarea proiectului.
    - Instrucțiuni pentru rularea proiectului.
    - Instrucțiuni pentru testarea proiectului.

Mult succes și spor la programare, dacă îți apar careva întrebări, nu ezita să-mi scrii pe discord la @pyramix ! 🚀