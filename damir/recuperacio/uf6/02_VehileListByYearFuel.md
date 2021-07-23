name: VehicleListByYearFuel
authors: 
  - joan.puigcerver
keywords:
  - DB
tests:
  - name: public_test
    input: |
      2015
      Diesel
    output: |
      # Vehicles de l'any 2015 amb combustible Diesel:
      0429 DMV - Tesla Model X (2015, Diesel)
      1105 TYS - VAZ Веста (2015, Diesel)
      1156 VHS - Kia Sorento Prime (2015, Diesel)
      1255 VSH - Fiat Tipo (2015, Diesel)
      1465 SWH - BMW M2 (2015, Diesel)
      1897 GMV - Ravon Gentra (2015, Diesel)
      1999 JJW - Rolls-Royce Dawn (2015, Diesel)
      2167 SCW - VAZ Largus Cross (2015, Diesel)
      2237 DCT - McLaren 540C (2015, Diesel)
      4610 ZLT - Mercedes S-class Cabrio (2015, Diesel)
      6157 VFP - McLaren 570S (2015, Diesel)
      7165 RWK - Fiat 124 Spider (2015, Diesel)
      7690 CZF - Renault Talisman (2015, Diesel)
      8123 NLZ - Ferrari 488 (2015, Diesel)
      9771 TRB - Daihatsu Cast (2015, Diesel)
      9833 DJJ - Mercedes GLE-class Coupe (2015, Diesel)
      9858 GJB - Jaguar XE (2015, Diesel)
      9904 CCX - Opel Karl (2015, Diesel)
---
# VehicleListByYearFuel
Mostra la llista de vehicles amb un any de matriculació i un combustible concret, ordenats per matrícula.
