# Kata Romain

> **À propos**
>
> ⓘ Ceci est la donnée d'un [kata], un _exercice de programmation_ qui se
> déroule généralement dans le cadre d'un [coding dojo]. Il est proposé aux
> membres du dojo de l'[EPFL] et fait partie d'une collection de différents
> katas identifiés par le tag **[epfl-dojo-kata]** sur GitHub.  
> Vous êtes plus que bienvenu d'essayer de le réaliser dans le langage de
> programmation de votre choix. Lorsque c'est terminé, ajoutez-vous à la liste
> de ceux qui l'ont fait dans ce document en proposant une [Pull Request]. Vous
> pouvez également **[epfl-dojo-kata]** partager votre intérêt pour ce dépôt en
> le «[stargazant]».  
> Bonne lecture et bon code !

[kata]: https://fr.wikipedia.org/wiki/Coding_dojo#Kata
[coding dojo]: https://fr.wikipedia.org/wiki/Coding_dojo
[EPFL]: https://www.epfl.ch
[epfl-dojo-kata]: https://github.com/topics/epfl-dojo-kata
[Pull Request]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
[stargazant]: https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars

## Introduction

Les Romains étaient des gens intelligents. 

Ils ont conquis la majeure partie de l'Europe et l'ont gouvernée pendant des
centaines d'années. Ils ont inventé le béton, les routes droites et même les
bikinis. 

Une chose qu'ils n'ont jamais découverte, c'est le chiffre zéro. Cela a rendu
un peu plus difficile l'écriture et la datation de l'histoire de leurs exploits,
mais le système de chiffres qu'ils ont inventé est toujours utilisé aujourd'hui.

Les Romains écrivaient les nombres à l'aide de lettres :

    I = 1
    V = 5
    X = 10
    L = 50
    C = 100
    D = 500
    M = 1000

On peut combiner les lettres pour ajouter des valeurs, en les énumérant du plus
grand au plus petit, de gauche à droite :

    II = 2
    VIII = 8
    XXXI = 31

Toutefois, vous ne pouvez énumérer que trois lettres identiques consécutives.
Une seule valeur inférieure peut précéder une valeur supérieure, pour indiquer
une soustraction. 

Cette règle n'est utilisée que pour construire des valeurs non atteignables par
les règles précédentes :

    IV = 4
    CM = 900

Mais 15 est `XV`, pas `XVX`.


## Autres conseils

Les chiffres romains modernes s'écrivent en exprimant chaque chiffre séparément
en commençant par le chiffre le plus à gauche et en sautant tout chiffre ayant
une valeur de zéro. 


## Exemples

**1990**: 1000=M, 900=CM, 90=XC; MCMXC. 

**2008**: 2000=MM, 8=VIII; MMVIII.


## Tâche

Écrire un programme qui convertit des nombres en chiffres romains.


## Pour aller plus loin

Voici quelques idées pour aller plus loin avec ce Kata :
* Se documenter sur les chiffres romain (https://fr.wikipedia.org/wiki/Num%C3%A9ration_romaine) ;
* Proposer un convertisseur, fonctionnant de décimal à chiffres romains et invérsément ;
* Proposer une solution intégrants les [Macrons](https://fr.wikipedia.org/wiki/Macron_(diacritique)) ;
* etc...

Le **[kata-braille](https://github.com/ponsfrilus/kata-braille)** et le 
le **[kata-morse](https://github.com/ponsfrilus/kata-morse)** sont dans le
même genre, n'hésitez pas à les faire aussi !


## Je l'ai fait 💪

* La version de [@octocat](https://github.com/octocat) a été faite en `langage`
  et est disponible [ici](https://#).


# Remerciement

Merci à @davidwhitney pour l'original (https://github.com/davidwhitney/CodeDojos/tree/master/RomanNumerals) duquel ce kata est traduit.
