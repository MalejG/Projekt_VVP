Zde bude projekt

Napady:

Vypocet Biosavartova zakonu na matici a vypocet jednotlivych matic


## 1 Textový popis
Tento projekt se zabývá výpočtem magnetického pole, které vytváří proud tekoucí v definované cívce. Základem bude využití Biot-Savartova zákona k sestavení matice, která reprezentuje cívku k výslednému magnetickému poli v prostoru (nebo v průřezu). Následně bude možné z této matice extrahovat a dále zpracovat hodnoty magnetického pole v různých bodech či průřezech.
Na počátku bude nutné nadefinovat popis cívky – tvaru donut :) a veličinu elektrického proudu. Na základě toho se aplikuje funkce pro výpočet magnetického pole v zadané oblasti. Dále vizualizujeme výsledné hodnoty (například 2D či 3D).
Výstupem budou vizualizace matic a jeji prúrezy.

## 2 Funcionality
1. Načtení a definice geometrie cívky
    - [ ] třída pro načtení parametrů závitu cívky.
    - [ ] definice cívky v kódu (donut) 
2. Výpočet magnetického pole
    - [ ] Implementace výpočtu podle Biot-Savartova zákona.
    - [ ] Sestavení výsledné matice.
3. Uložení a extrakce výsledků
    - [ ] Ukládání výsledné matice magnetického pole do formátu (HDF5).
    - [ ] Třída pro řezání 
4. Vizualizace
    - [ ] Vytvoření třídy pro vizualizaci 2D a  3D (matplotlib)
    - [ ] Generování obrázků 