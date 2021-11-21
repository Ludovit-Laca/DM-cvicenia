# Dátový súbor

Z predpripraveného logovacieho súboru z minulého semestra vytvorte dátový súbor, ktorý bude obsahovať:
* informáciu o kategórií webovej stránky portálu (uvod, studium, oznamy, ...);
* či sa jedná o prístup zvnútra siete alebo zvonka siete na základe IP (0/1);
* či sa jedná o prístup študenta alebo zamestnanca (0/1);
* informáciu o hodine prístupe (0-23);
* informáciu o dni prístupu (1-7);

IP adresy pre klasifikáciu prístupov a študentov/zamestnancov:
* 10.160.0.xxx -> IN/STUDENT
* 10.160.1.xxx -> IN/STUDENT
* 10.160.2.0xx -> IN/STUDENT
* 10.160.2.1xx -> IN/STUDENT
* 10.160.2.2xx -> IN/ZAMEST
* 10.160.3.xxx -> IN/STUDENT
* 10.160.xxx.xxx -> IN/ZAMEST
* ostatne -> OUT

Príkazy v Pythone vhodné pre riešenie tohto zadania:
```
import pandas as pd
pd.read_csv() - načítanie log súboru
```
