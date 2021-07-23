name: IsValidPlateNumber
authors: 
  - joan.puigcerver
keywords:
  - Collections
  - Queue
tests:
  - name: public_test
    input: |
      10
      9274   RMH
      8694 PNC
      3086XkH
      6c75FNC
      8198 YIY
      3296  VGB
      6213GFX
      2233   EBG
      0232 VOQ
      5932RLM
    output: |
      La matrícula 3086XkH és falsa.
      La matrícula 6c75FNC és falsa.
      La matrícula 8198YIY és falsa.
      La matrícula 2233EBG és falsa.
      La matrícula 0232VOQ és falsa.
---
# Exercici 14: IsValidPlateNumber
El Servei Català de Trànsit vol trobar les matrícules falses entre els cotxes que passen per una carretera en concret. 
S'ha instal·lat una càmera a la carretera, que ens proporciona les diferents matricules. Degut a la baixa resolució, de vegades la camara detecta espais entre els números i les lletres.

Es demana fer un programa que comprove que les matricules son correctes i avise de les matrícules falses. S'han d'eliminar els espais de la sortida.

Una matrícula consta de:
* 4 dígits del 0 al 9.
* 3 lletres majúscula dins del seguent conjunt: B, C, D, F, G, H, J, K, L, M, N, P, R, S, T, V, W, X, Y y Z.
