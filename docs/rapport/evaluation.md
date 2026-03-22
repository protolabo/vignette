# Évaluation & Tests

## Tests

Afin de s'assurer du bon fonctionnement du backend du projet, un certain nombre de tests on été mis en place.
Cela a été réalisé avec la dépendance JUnit ainsi que la librairie Mockito.

Mockito nous permet de simuler des objets, des services ou stockage et de les tester.


Ne sont testés que les Services du projet, qui sont directements dépendants de mon développement (contrairement à, par exemple, les repositories qui se reposent sur un framework puissant).
Les tests nous permettent de s'assurer que le code fonctionne correctement, en signalant des erreurs lors du build si notre code ne suit pas le comportement souhaité.