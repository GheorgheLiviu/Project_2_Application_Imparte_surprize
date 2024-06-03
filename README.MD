# Java Class Hierarchy - Aplicație 'Împarte surprize'

## Descriere
Aplicația 'Împarte surprize' este un proiect ce vizează aprofundarea conceptelor de design a ierarhiei de clase în Java. Scopul principal al proiectului este să implementeze diverse concepte de programare orientată pe obiect, precum moștenirea, compunerea și agregarea, încapsularea, utilizarea interfețelor și genericitatea, într-un mod practic și eficient.

## Scopuri
- Reutilizarea funcționalității prin diverse procedee, inclusiv moștenire, compunere și agregare.
- Implementarea unei arhitecturi de clase de nivel mediu de complexitate, cu o organizare corespunzătoare a codului.
- Lucrul cu obiecte de tipuri diferite dintr-o perspectivă comună, folosind upcasting.
- Proiectarea și utilizarea interfețelor în comunicarea dintre componente.
- Implementarea conceptului de genericitate în dezvoltarea software.

## Implementare
Proiectul este structurat în mai multe secțiuni, voi detalia fiecare secțiune în parte:

### 1. Tipuri de surprize
Fiecare surpriză este reprezentată printr-o clasă ce implementează interfația `ISurprise`. Există trei tipuri de surprize:
- FortuneCookie
- Candies
- MinionToy

### 2. Depozitarea surprizelor
Surprizele sunt depozitate în diverse tipuri de containere, care dictează modul de stocare și ordinea în care sunt împărțite. Pentru acest lucru, se utilizează interfața `IBag`, iar fiecare container implementează această interfață.

### 3. Crearea surprizelor
Clasa `GatherSurprises` este responsabilă pentru generarea aleatoare a surprizelor, fie într-un număr specificat, fie doar a unei surprize.

### 4. Crearea containerelor
Pentru crearea de containere, se utilizează un mecanism de tip Factory Pattern, implementat prin interfața `IBagFactory`.

### 5. Împărțirea surprizelor
Se implementează clasa abstractă `AbstractGiveSurprises`, care definește mecanismul de împărțire a surprizelor. Aceasta este extinsă de trei clase concrete: `GiveSurpriseAndApplause`, `GiveSurpriseAndSing`, `GiveSurpriseAndHug`, fiecare oferind surprize în moduri diferite.


--- 

Aceasta este o descriere generală a proiectului. Pentru detalii specifice și codul sursă, vă recomand să accesați fișierele relevante.