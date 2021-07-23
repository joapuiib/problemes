name: InsertVehicleDB
authors: 
  - joan.puigcerver
keywords:
  - DB
tests:
  - name: public_test
    input: |
      0232VOQ
      Ford
      Focus
      2003
      Diesel
    output: "Vehicle 0232VOQ - Ford Focus (2003, Diesel) insertat."
---
# InsertVehicleDB
Demana a l'usuari el diferents atributs d'un vehicle i l'inserta a la base de dades.
Nota: Si intentes introduir un cotxe amb una matricula existent et fallarà per PK
