name: GestioUsuaris
authors: 
  - joan.puigcerver
keywords:
  - OOP
  - Inheritance
tests:
  - name: public_test
    input: 
    output: |
      Nom: Dani
      Cognoms: Carrasco Morera
      Data de naixement: 04/09/1986
      Correu electrònic: dani.carrasco@itb.cat

      Nom: Laura
      Cognoms: Ivars Perelló
      Data de naixement: 17/05/1996
      Correu electrònic: laura.ivars@itb.cat

      Nom: Aitana
      Cognoms: Sanchis Marí
      Data de naixement: 20/11/2001
      Correu electrònic: aitana.sanchis.7e4@itb.cat
---
# Exercici 10: GestioUsuaris
* Relitza aquest exercici en el subpackage extraordinaria.uf4.gestiousuaris

Es vol realitzar un programa per gestionar els usuaris de l'ITB

Cada usuari té les següents característiques:
* Nom
* Primer cognom
* Segon cognom
* Data de naixement

A més, volem identificar també els diferents estudiants, que tindran la següent informació:
* Nom
* Primer cognom
* Segon cognom
* Data de naixement
* Data de matriculació

El programa ha de generar el correu electrònic de cada usuari amb el següent format:
* __nom.primer@itb.cat__

En el cas dels estudiants, també inclourà l'any de matriculació en hexadecimal:
* __nom.primer.hex@itb.cat__. Podeu obtindre el codi hexadecimal amb Integer.toHexString(int)

Es demana fer un programa que cree per defecte els següents estudiants i els mostre en el següent format:
- Usuari{nom: "Dani", primerCognom: "Carrasco", segonCognom: "Morera", dataNaixement:"04/09/1986"}
- Usuari{nom: "Laura", primerCognom: "Ivars", segonCognom: "Perelló", dataNaixement:"17/05/1996"}
- Estudiant{nom: "Aitana", primerCognom: "Sanchis", segonCognom: "Marí", dataNaixement: "20/11/2001", dataMatriculacio: 2020}
