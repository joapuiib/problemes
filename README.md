# Repositori de problemes M03
Col·lecció dels diferents problemes de M03

## Format
Definició del format.
* __exemple_problema.yaml__:
```yaml
- name: "ExempleProblema"
- authors: # Optional
  - pep.pi
```

### Carpetes
- Hi ha una carpeta per a cada grup-professor. 
- A dins una carpeta per cada UF.
- Cada UF té una carpeta per cada col·lecció de problemes. El nom ha de tenir el format 00_nom_colecció, per indicar l'ordre.
- S'ha de crear un fitxer per a cada problema. El nom del fitxer ha de ser 00_NomDelProblema.yaml
    - Hi ha un exemple de format d'exercici a la carpeta exemple_problema

### Exercicis
L'exercici ha de definir l'enunciat i diferents propietats de l'exercici. Veure l'exemple.

#### Tests
Es poden definir dins del yaml del exercici o en carpetes separades.
Si s'opta per tenir-los en la carpeta separada, aquesta ha de tenir el mateix nom que l'exercici.
Dins de la carpeta hi haurà un fitxer *.in per l'entrada de cada test i un fitxer *.out per la sortida. 
El nom del fitxer serà el nom del test. Si el test és privat el nom començara per guió baix.
Exemple de test privat:
    - \_my\_sample\_test.in
    - \_my\_sample\_test.out

### Introducció
En alguns casos una col·lecció d'exercicis necessita d'una introducció. Pots crear un document intro.md amb la introducció de la col·lecció de problemes.

