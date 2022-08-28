# SIMULARE SQLite - PROIECT POO

Temă: **Baza mea de date SQLite** <br />
Motivație: Experiență practică care ajută să vezi cum se combină diferite clase pentru a dezvolta un produs software „real” (SQLite este real și folosit foarte mult) <br />
Scop final: Implementarea unei versiuni limitate a unui sistem de gestionare a bazelor de date, cum ar fi SQLite https://www.sqlite.org/index.html <br />

*TEHNOLOGIILE UTILIZATE:* <br />
֍ Limbajul de programare – **C++** <br />
֍ Mediul de dezvoltare – **Visual Studio** <br />


În cadrul disciplinei **Programare Orientată Obiect** în limbajul C++ am realizat, în echipă formată din patru persoane, un proiect ce constă într-o bază de date asemănătoare MySQL sau SQLite, respectând anumite cerințe obligatorii. Aplicația este una de tip consolă, realizată în Visual Studio 2019. Primește input de la tastatură, din fișiere text, binare sau csv, putând fi lansată din IDE-ul Visual Studio sau din linia de comandă. Funcția main poate primi argumente în linia de comandă: maxim 5 fișiere text sau sintagma "import into nume_tabela nume_fisier.csv", ce populează o tabelă cu date din respectivul fișier. Se pot crea și șterge tabele (CREATE/DROP TABLE), se pot popula rând cu rând (INSERT INTO...) sau mai multe rânduri deodată (cu fișier .csv), de asemenea, se pot realiza select-uri, update-uri, delete-uri, simulând limbajul SQL. Parsarea comenzilor este realizată cu ajutorul regex. Aplicația poate fi rulată direct cu ajutorul fișierului .exe, permițând și argumente în linia de comandă. Aceste argumente pot fi fișiere .txt ce conțin comenzi, câte una pe fiecare rând, sau se pot importa date într-o tabelă anterior creată din fișiere csv. Pentru a adăuga argumente, se poate lansa executabilul din PowerShell.

Specificațiile proiectului:  <br />
https://docs.google.com/document/u/1/d/e/2PACX1vSquShMz8Eetfu39RuHzA3s9EXLtIQSO71H8AIJJfWrsDePpR_Rg1S92B95dkUknFTzxy8_Mw82Eaaz/pub
