## TP Structure alternative Partie 2

### Exercice 1

Formulez un algorithme équivalent à l’algorithme suivant :
```
Si Tutu > Toto + 4 OU Tata = "OK" Alors
  Tutu ← Tutu + 1
Sinon
  Tutu ← Tutu – 1
Finsi
``` 

### Exercice 2

Cet algorithme est destiné à prédire l'avenir, et il doit être infaillible !
Il lira au clavier l’heure et les minutes, et il affichera l’heure qu’il sera une minute plus tard. 
Par exemple, si l'utilisateur tape 21 puis 32, l'algorithme doit répondre :
"Dans une minute, il sera 21 heure(s) 33".
NB : on suppose que l'utilisateur entre une heure valide. Pas besoin donc de la vérifier.

### Exercice 3

De même que le précédent, cet algorithme doit demander une heure et en afficher une autre. 
Mais cette fois, il doit gérer également les secondes, et afficher l'heure qu'il sera une seconde plus tard.
Par exemple, si l'utilisateur tape 21, puis 32, puis 8, l'algorithme doit répondre : 
"Dans une seconde, il sera 21 heure(s), 32 minute(s) et 9 seconde(s)".
NB : là encore, on suppose que l'utilisateur entre une date valide.

### Exercice 4

Un magasin de reprographie facture 0,10 E les dix premières photocopies, 0,09 E les vingt suivantes et 0,08 E au-delà. 
Ecrivez un algorithme qui demande à l’utilisateur le nombre de photocopies effectuées et qui affiche la facture correspondante.

### Exercice 5

Les habitants de Zorglub paient l’impôt selon les règles suivantes :
les hommes de plus de 20 ans paient l’impôt
les femmes paient l’impôt si elles ont entre 18 et 35 ans
les autres ne paient pas d’impôt
Le programme demandera donc l’âge et le sexe du Zorglubien, et se prononcera donc ensuite sur le fait que l’habitant est imposable.

### Exercice 6

Les élections législatives, en Guignolerie Septentrionale, obéissent à la règle suivante :
lorsque l'un des candidats obtient plus de 50% des suffrages, il est élu dès le premier tour.
en cas de deuxième tour, peuvent participer uniquement les candidats ayant obtenu au moins 12,5% des voix au premier tour.
Vous devez écrire un algorithme qui permette la saisie des scores de quatre candidats au premier tour. 
Cet algorithme traitera ensuite le candidat numéro 1 (et uniquement lui) : 
il dira s'il est élu, battu, s'il se trouve en ballottage favorable (il participe au second tour en étant arrivé en tête à l'issue du premier tour) 
ou défavorable (il participe au second tour sans avoir été en tête au premier tour).
