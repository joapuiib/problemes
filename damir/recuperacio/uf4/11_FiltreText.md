name: FiltreText
authors: 
  - joan.puigcerver
keywords:
  - OOP
  - Interfaces
tests:
  - name: public_test
    input: "There is only one problem with common sense; it’s not very common."
    output: |
      THERE IS ONLY ONE PROBLEM WITH COMMON SENSE; IT’S NOT VERY COMMON.
      tHeRe iS OnLy oNe pRoBlEm wItH CoMmOn sEnSe; It’s nOt vErY CoMmOn.
      .nommoc yrev ton s’ti ;esnes nommoc htiw melborp eno ylno si erehT
---
# Exercici 11: FiltreText

Es demana realitzar una aplicació que permeti aplicar "filtres" a un text. Tots els filtres creats han de contindre el mètode __String filterText(String text)__.
Es demana crear les estructures necessàries per garantitzar que tots els filtres tinguen aquest mètode.

Els filtres que es volen crear son:
- UpperCaseFilter: Passa tot el text a majúscula.
- SwitchCaseFilter: EL text anirà alternant entre majúscules i minúscules. Comença en minúscula.
- ReverseFilter: Li dona la volta al tot el text.

El programa rebrà un text i aplicarà els tres filtres anteriors.
