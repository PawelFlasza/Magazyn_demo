📦 Warehouse Management SQL Project
🧭 Opis projektu
Projekt przedstawia uproszczony model systemu magazynowego (WMS) zbudowany w Oracle SQL. Zawiera strukturę tabel, relacje, dane przykładowe oraz podstawę do tworzenia raportów i logiki biznesowej.
Celem projektu jest pokazanie umiejętności w zakresie:
- projektowania relacyjnych baz danych,
- modelowania procesów magazynowych,
- pisania czytelnych i skalowalnych skryptów SQL,
- pracy z Git i dokumentacją techniczną.

🏗️ Zakres funkcjonalny
Model obejmuje kluczowe obszary magazynu:
* Obszar      -  Opis                                                     
* Products    - Lista produktów, ich kategorie, waga, status aktywności    
* Warehouses  - Dane magazynów i lokalizacji                               
* Stock       - Stany magazynowe per produkt i magazyn                     
* Movements   - Historia ruchów magazynowych (przyjęcia, wydania, korekty) 
* Operators   - Pracownicy realizujący zadania                            
* PickingTasks- Zadania kompletacyjne przypisane operatorom                



🗄️ Struktura repozytorium
PawelFlasza/
└─ Magazyn_demo/
   └─ model_magazynu/
      └─ 01_schema_and_seed_oracle.sql   # definicje tabel + dane testowe



▶️ Uruchamianie projektu
- Uruchom środowisko Oracle (SQL*Plus, SQL Developer, DBeaver itp.).
- Wykonaj skrypt:
PawelFlasza/Magazyn_demo/model_magazynu/01_schema_and_seed_oracle.sql


- Po wykonaniu skryptu baza będzie zawierała:
- pełną strukturę tabel,
- klucze główne i obce,
- dane przykładowe do testów i raportów.

📊 Przykładowe zapytania, które można zbudować
- aktualny stan magazynowy per magazyn,
- historia ruchów dla wybranego produktu,
- analiza wydajności operatorów,
- liczba zadań kompletacyjnych per dzień,
- produkty nieaktywne lub bez zapasu.


🎯 Cele projektu
- stworzenie kompletnego, czytelnego projektu SQL do portfolio,
- odwzorowanie realnych procesów magazynowych,
- przygotowanie bazy pod dalsze rozszerzenia (procedury, widoki, raporty),
- pokazanie umiejętności pracy z GitHubem.

📌 Autor
Paweł — operator logistyczny z 10+ lat doświadczenia, rozwijający się w kierunku SQL i projektowania baz danych.
