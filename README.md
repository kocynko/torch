# Klasifikácia Vekom Podmienenej Degenerácie Makuly s YOLOv8

Tento repozitár obsahuje implementácie modelov neurónových sietí, ktoré sa zaoberajú detekciou vekom podmienej degenrácie makuly z obrazov očného pozadia. Zameriava sa predovšetkým na modely YOLOv8.

1. **Modely pre detekciu vekom podmienenej degenerácie makuly**

## Inštalácia

1. Najprv si nainštalujte Python verzia 3.8. Môžete ho stiahnuť a nainštalovať z [Python.org](https://www.python.org/downloads/) alebo použiť nástroj na správu balíčkov ako `brew` pre macOS alebo `apt` pre Linux.

2. Potom vytvorte a aktivujte virtuálne prostredie pre váš projekt. 
    ```bash
    python3 -m venv myenv
    source myenv/bin/activate
    ```

3. Aktualizujte nástroj `pip`, aby ste mali najnovšiu verziu.
    ```bash
    python -m pip install --upgrade pip

4. Na stránke [Pytorch.org](https://pytorch.org/) nainštalujte verziu Pytorch podľa vašich požiadaviek


6. Teraz nainštalujte potrebné knižnice. Použite nasledujúci príkaz na inštaláciu všetkých potrebných knižníc naraz.
    ```bash
    pip install ultralytics
    ```
## Použitie

V tomto repozitári je obsiahnutý Jupyter Notebook (súbor s príponou .ipynb), ktorý obsahuje implementáciu modelu YOLOv8. 

Pre použitie konkrétneho modelu jednoducho otvorte príslušný Jupyter Notebook a postupujte podľa pokynov v ňom. Pred začatím odporúčam skontrolovať, či je cesta k datasetom správna.
