# IAU

Inteligentná analýza údajov - 5.semester

## Semestrálna práca (Projekt - 3. časti)

#### Autori
 - **Jan Lenhart**
 - **Marek Čederle**

#### Cvičenie
 - **Pondelok 15:00 - Lytvyn**

## Zadanie

**Celé zadanie**

[Zadanie PDF](./assignment_info/2024-IAU-zadanie.pdf)

[Data Description PDF](./assignment_info/IAU-2024-DataDescription.pdf)

**Sumár zadania s hodnotením**

Každá podúloha má ešte svoje časi A, B, C, ...

- [x] Fáza 1 - Prieskumná analýza (15b)
    - [x] 1.1 Základný opis dát spolu s ich charakteristikami (5b)
    - [x] 1.2 Identifikácia problémov, integrácia a čistenie dát (5b)
    - [x] 1.3 Formulácia a štatistické overenie hypotéz o dátach (5b)

___Fáza 1 body: 13,5/15
Feedback:
Formulacia hypotez by mohla byt viac jednoznacna. Co je "normalny stav"? co znamena "inu vahu" ? Chyba overenie statistickej sily (check Effect Size and Power anlysis).___

- [x] Fáza 2 - Predspracovanie údajov (15b)
    - [x] 2.1 Realizácia predspracovania dát (5b)
    - [x] 2.2 Výber atribútov pre strojové učenie (5b)
    - [x] 2.3 Replikovateľnosť predspracovania (5b)

___Fáza 2 body: 13,75/15
Feedback:
2.1-A - chyba overenie podobnosti train/test distribucie (-0.25). 2.3-B - na test set bola pouzita fit_transform(), kedze ma byt transform() (-1b)___

- [x] Fáza 3 - Strojové učenie (20b)
    - [x] 3.1  Jednoduchý klasifikátor na základe závislosti v dátach (5b)
    - [x] 3.2  Trénovanie a vyhodnotenie klasiﬁkátorov strojového učenia (5b)
    - [x] 3.3  Optimalizácia alias hyperparameter tuning (5b)
    - [x] 3.4  Vyhodnotenie vplyvu zvolenej stratégie riešenia na klasiﬁkáciu (5b)

___Fáza 3 body: 20/20
Feedback:
Well Done!___

**Aktivita na cvičení**
The QUEST (stačí jeden z dvoch, buď Q1 alebo Q2)
- Q1 (Image classification): klasifikačná úloha podľa počtu tried
- <font color='lime'> Q2 (Time-series forecasting): predpovedajte čo najpresnejšie nastávajúcu situáciu podľa historických dát.</font>

Vybrali sme si Q2. Dataset pre Q2 bol stiahnutí z [kaggle](https://www.kaggle.com/datasets/aayushmishra1512/netflix-stock-data).


- [x] Aktivity na cvičení (10b)
    - [x] 4.1 EDA and data preprocessing (5b)
    - [x] 4.2. Modeling and evaluation (5b)

___Aktivita body: x/10
Feedback:
TBD___

## Spustenie projektu

### Prerekvizity

*Ideálne je použiť virtual enviroment pre python*

- Python
- Knižnice

```bash
pip install -r requirements.txt
```

- Jupyter Notebook
