---
description: "Cours de mathématiques du Tronc Commun Scientifique
  Français (TCSF) : parité, divisibilité, nombres premiers,
  décomposition en facteurs premiers, PGCD, PPCM et exercices corrigés."
educational_level: Tronc Commun Scientifique Français (TCSF)
language: fr
publisher: AltiMath
source_url: "https://www.altimath.com/2026/10/arithmetique.html"
subject: Mathématiques
title: "Arithmétique dans ℕ : Cours et exercices corrigés"
---

# Arithmétique dans ℕ : cours et exercices corrigés (TCSF)

> Ressource pédagogique de mathématiques destinée aux élèves du Tronc
> Commun Scientifique Français (TCSF) au Maroc.

-   **Site :** [AltiMath](https://www.altimath.com/)
-   **Article original :** [Arithmétique dans ℕ : Cours et Exercices
    Corrigés (TCSF)](https://www.altimath.com/2026/10/arithmetique.html)
-   **Niveau :** Tronc Commun Scientifique Français (TCSF)
-   **Langue :** français
-   **Thèmes :** parité, multiples, diviseurs, divisibilité, division
    euclidienne, nombres premiers, décomposition en facteurs premiers,
    PGCD et PPCM.

## Présentation du chapitre

Comment déterminer si un nombre entier est divisible par un autre sans
effectuer plusieurs calculs successifs ? Comment retrouver les diviseurs
d'un nombre ou justifier qu'une division laisse un reste précis ?

L'arithmétique dans l'ensemble des entiers naturels \\(\\mathbb{N}\\)
étudie les propriétés des nombres et les relations de divisibilité. Ce
chapitre développe les notions de multiples, de diviseurs, de critères
de divisibilité, de division euclidienne, de nombres premiers, de
décomposition en facteurs premiers, de PGCD et de PPCM.

L'objectif n'est pas seulement d'obtenir un résultat numérique : l'élève
doit savoir choisir une propriété adaptée, présenter les calculs et
rédiger une justification mathématique claire.

## Compétences visées

À la fin de ce chapitre, l'élève doit pouvoir :

-   reconnaître les multiples et les diviseurs d'un entier naturel ;
-   utiliser correctement le vocabulaire et la notation de la
    divisibilité ;
-   appliquer les critères usuels de divisibilité ;
-   effectuer une division euclidienne et vérifier quotient et reste ;
-   distinguer les nombres premiers des nombres composés ;
-   décomposer un entier supérieur à 1 en facteurs premiers ;
-   déterminer le nombre de diviseurs positifs d'un entier à partir de
    sa décomposition ;
-   calculer un PGCD et un PPCM ;
-   choisir entre PGCD et PPCM dans un problème concret ;
-   rédiger une démonstration en s'appuyant sur les définitions et les
    propriétés.

## Sommaire

1.  [Parité d'un entier naturel](#1-parité-dun-entier-naturel)
2.  [Diviseurs, multiples et
    divisibilité](#2-diviseurs-multiples-et-divisibilité)
3.  [Nombres premiers et décomposition en facteurs
    premiers](#3-nombres-premiers-et-décomposition-en-facteurs-premiers)
4.  [PGCD et PPCM](#4-pgcd-et-ppcm)
5.  [Exercices corrigés et devoir
    d'entraînement](#5-exercices-corrigés-et-devoir-dentraînement)

------------------------------------------------------------------------

## 1. Parité d'un entier naturel

### 1.1. Définition

Un entier naturel \\(n\\) est **pair** s'il existe un entier naturel
\\(k\\) tel que :

\\\[ n=2k. \\\]

Il est **impair** s'il existe un entier naturel \\(k\\) tel que :

\\\[ n=2k+1. \\\]

On peut reconnaître rapidement la parité grâce au chiffre des unités :

-   un entier qui se termine par 0, 2, 4, 6 ou 8 est pair ;
-   un entier qui se termine par 1, 3, 5, 7 ou 9 est impair.

Pour démontrer la parité d'une expression algébrique, il est préférable
de revenir aux formes \\(2k\\) et \\(2k+1\\).

### 1.2. Exemples

-   \\(124=2\\times62\\), donc 124 est pair.
-   \\(357=2\\times178+1\\), donc 357 est impair.
-   \\(1008=2\\times504\\), donc 1008 est pair.

### 1.3. Propriétés de la parité

Pour des entiers naturels \\(a\\) et \\(b\\) :

  Opération         Écriture                          Résultat
  ----------------- --------------------------------- ----------
  Pair + pair       \\(2a+2b=2(a+b)\\)                Pair
  Pair + impair     \\(2a+(2b+1)=2(a+b)+1\\)          Impair
  Impair + impair   \\((2a+1)+(2b+1)=2(a+b+1)\\)      Pair
  Pair × entier     \\(2a\\times b=2(ab)\\)           Pair
  Impair × impair   \\((2a+1)(2b+1)=2(2ab+a+b)+1\\)   Impair

Un produit contenant au moins un facteur pair est pair. Le produit de
deux entiers impairs est impair.

### 1.4. Démonstration : la somme de deux entiers impairs est paire

Soient \\(m\\) et \\(n\\) deux entiers impairs. Il existe
\\(a,b\\in\\mathbb{N}\\) tels que :

\\\[ m=2a+1,\\qquad n=2b+1. \\\]

Alors :

\\\[ \\begin{aligned} m+n&=(2a+1)+(2b+1)\\\\ &=2a+2b+2\\\\ &=2(a+b+1).
\\end{aligned} \\\]

Comme \\(a+b+1\\in\\mathbb{N}\\), la somme est paire.

### 1.5. Exemple : étudier la parité de \\(A=n\^2+n+5\\)

On factorise les deux premiers termes :

\\\[ A=n(n+1)+5. \\\]

Les entiers consécutifs \\(n\\) et \\(n+1\\) sont de parités
différentes. L'un d'eux est donc pair, ce qui rend leur produit pair.

Il existe alors \\(k\\in\\mathbb{N}\\) tel que \\(n(n+1)=2k\\). Ainsi :

\\\[ A=2k+5=2(k+2)+1. \\\]

Donc \\(A\\) est impair pour tout \\(n\\in\\mathbb{N}\\).

### 1.6. Exercices corrigés sur la parité

**Exercice 1.** Montrer que \\(n\^2+n\\) est pair pour tout
\\(n\\in\\mathbb{N}\\).

**Correction :**

\\\[ n\^2+n=n(n+1). \\\]

Deux entiers consécutifs comprennent toujours un entier pair. Leur
produit est donc pair.

**Exercice 2.** Le carré d'un entier impair est-il toujours impair ?

**Correction :**

Soit \\(n=2k+1\\), avec \\(k\\in\\mathbb{N}\\). Alors :

\\\[ \\begin{aligned} n^2&=(2k+1)^2\\\\ &=4k\^2+4k+1\\\\
&=2(2k\^2+2k)+1. \\end{aligned} \\\]

Le carré est de la forme \\(2p+1\\), donc il est impair.

------------------------------------------------------------------------

## 2. Diviseurs, multiples et divisibilité

### 2.1. Définition de la divisibilité

Soient \\(a\\in\\mathbb{N}\\) et \\(b\\in\\mathbb{N}\^{\*}\\). On dit
que \\(b\\) divise \\(a\\) lorsqu'il existe \\(k\\in\\mathbb{N}\\) tel
que :

\\\[ a=b\\times k. \\\]

On écrit :

\\\[ b\\mid a. \\\]

Cette relation se lit « \\(b\\) divise \\(a\\) ». Le diviseur est placé
à gauche.

Ainsi, \\(a\\) est un multiple de \\(b\\), et \\(b\\) est un diviseur de
\\(a\\).

### 2.2. Exemple : les diviseurs de 24

Les décompositions en produits de deux facteurs sont :

\\\[ 24=1\\times24=2\\times12=3\\times8=4\\times6. \\\]

Les diviseurs positifs de 24 sont donc :

\\\[ D(24)=\\{1,2,3,4,6,8,12,24\\}. \\\]

### 2.3. Multiples d'un entier

Les multiples d'un entier naturel \\(a\\) sont les nombres de la forme :

\\\[ M(a)=\\{ak\\mid k\\in\\mathbb{N}\\}. \\\]

Par exemple, les premiers multiples de 7 sont :

\\\[ 0,\\ 7,\\ 14,\\ 21,\\ 28,\\ 35,\\ 42,\\ldots \\\]

Un entier positif possède un nombre fini de diviseurs positifs, mais une
infinité de multiples dans \\(\\mathbb{N}\\). Le nombre 0 est un
multiple de tout entier naturel non nul.

### 2.4. Propriétés fondamentales

-   Tout entier naturel non nul divise lui-même.
-   1 divise tout entier naturel.
-   Si \\(a\\mid b\\) et \\(b\\mid c\\), alors \\(a\\mid c\\).
-   Si \\(d\\mid a\\) et \\(d\\mid b\\), alors \\(d\\mid(a+b)\\).
-   La différence de deux multiples d'un même entier est encore un
    multiple de cet entier, lorsqu'on travaille dans les entiers
    relatifs.

### 2.5. Critères de divisibilité

  -----------------------------------------------------------------------
  Diviseur                Critère                 Exemple
  ----------------------- ----------------------- -----------------------
  2                       Le chiffre des unités   438 est divisible par
                          est 0, 2, 4, 6 ou 8.    2.

  3                       La somme des chiffres   \\(426 : 4+2+6=12\\).
                          est divisible par 3.    

  4                       Le nombre formé par les 1316 : 16 est divisible
                          deux derniers chiffres  par 4.
                          est divisible par 4.    

  5                       Le chiffre des unités   735 est divisible par
                          est 0 ou 5.             5.

  9                       La somme des chiffres   \\(729 : 7+2+9=18\\).
                          est divisible par 9.    

  10                      Le chiffre des unités   1240 est divisible par
                          est 0.                  10.
  -----------------------------------------------------------------------

### 2.6. Division euclidienne

Pour deux entiers naturels \\(a\\) et \\(b\\), avec \\(b\\ne0\\), il
existe un unique couple \\((q,r)\\) d'entiers naturels tel que :

\\\[ \\boxed{a=bq+r\\quad\\text{avec}\\quad 0\\leq r\<b.} \\\]

-   \\(a\\) est le dividende ;
-   \\(b\\) est le diviseur ;
-   \\(q\\) est le quotient ;
-   \\(r\\) est le reste.

Le nombre \\(a\\) est divisible par \\(b\\) si et seulement si le reste
est nul.

**Exemple :** division euclidienne de 245 par 12.

\\\[ 245=12\\times20+5. \\\]

Le quotient est 20 et le reste est 5. Comme \\(5\\ne0\\), 245 n'est pas
divisible par 12.

### 2.7. Exercices corrigés

**Exercice 1.** Déterminer les diviseurs positifs de 18 et les cinq
premiers multiples strictement positifs de 6.

**Correction :**

\\\[ D(18)=\\{1,2,3,6,9,18\\}. \\\]

Les cinq premiers multiples strictement positifs de 6 sont :

\\\[ 6,\\ 12,\\ 18,\\ 24,\\ 30. \\\]

**Exercice 2.** Sans division posée, déterminer si 2340 est divisible
par 2, 3, 4, 5, 9 et 10.

**Correction :**

La somme des chiffres vaut :

\\\[ 2+3+4+0=9. \\\]

-   Par 2 : oui, car le chiffre des unités est 0.
-   Par 3 et par 9 : oui, car la somme des chiffres vaut 9.
-   Par 4 : oui, car 40 est divisible par 4.
-   Par 5 et par 10 : oui, car le chiffre des unités est 0.

**Exercice 3.** Effectuer la division euclidienne de 245 par 12.

**Correction :**

\\\[ 245=12\\times20+5,\\qquad 0\\leq5\<12. \\\]

Le quotient est 20 et le reste est 5.

------------------------------------------------------------------------

## 3. Nombres premiers et décomposition en facteurs premiers

### 3.1. Définition

Un nombre premier est un entier naturel supérieur ou égal à 2 qui
possède exactement deux diviseurs naturels : 1 et lui-même.

Exemples :

-   5 est premier : ses seuls diviseurs sont 1 et 5.
-   9 n'est pas premier : ses diviseurs sont 1, 3 et 9.
-   1 n'est pas premier, car il ne possède qu'un seul diviseur positif.
-   0 n'est pas premier.

Un nombre supérieur à 1 qui n'est pas premier est composé.

### 3.2. Premiers nombres premiers inférieurs à 50

\\\[ 2,3,5,7,11,13,17,19,23,29,31,37,41,43,47. \\\]

Le nombre 2 est le seul nombre premier pair.

### 3.3. Test de primalité avec la racine carrée

Pour vérifier qu'un entier \\(n\\geq2\\) est premier, il suffit de
tester les nombres premiers inférieurs ou égaux à \\(\\sqrt n\\).

En effet, si \\(n\\) est composé, il possède deux facteurs strictement
supérieurs à 1 et au moins l'un d'eux est inférieur ou égal à \\(\\sqrt
n\\).

**Exemple : 97 est-il premier ?**

On a :

\\\[ 9^2=81\<97\<100=10^2. \\\]

Il suffit de tester 2, 3, 5 et 7.

-   97 est impair ;
-   la somme de ses chiffres est 16 ;
-   son chiffre des unités n'est ni 0 ni 5 ;
-   \\(97=7\\times13+6\\).

Aucun de ces nombres premiers ne divise 97. Donc 97 est premier.

**Exemple : 91 est-il premier ?**

\\\[ 91=7\\times13. \\\]

Il possède un diviseur autre que 1 et lui-même. Donc 91 n'est pas
premier.

### 3.4. Décomposition en facteurs premiers

Tout entier naturel supérieur à 1 peut être écrit comme un produit de
nombres premiers. Cette décomposition est unique à l'ordre des facteurs
près.

**Exemple : décomposer 360.**

\\\[ 360=2\\times180=2^2\\times90=2^3\\times45 \\\]

Puis :

\\\[ 45=3\^2\\times5. \\\]

Ainsi :

\\\[ \\boxed{360=2^3\\times3^2\\times5} \\\]

Vérification :

\\\[ 2^3\\times3^2\\times5=8\\times9\\times5=360. \\\]

### 3.5. Nombre de diviseurs positifs

Si la décomposition en facteurs premiers est :

\\\[ n=p\^a\\times q\^b\\times\\cdots, \\\]

alors le nombre de diviseurs positifs de \\(n\\) est :

\\\[ \\boxed{(a+1)(b+1)\\cdots} \\\]

**Exemple : déterminer le nombre de diviseurs positifs de 84.**

\\\[ 84=2\^2\\times3\\times7. \\\]

Le nombre de diviseurs positifs est :

\\\[ (2+1)(1+1)(1+1)=3\\times2\\times2=12. \\\]

Les diviseurs sont :

\\\[ 1,2,3,4,6,7,12,14,21,28,42,84. \\\]

**Exercice.** On donne \\(N=2^3\\times5^2\\). Déterminer le nombre de
diviseurs positifs de \\(N\\).

**Correction :**

\\\[ (3+1)(2+1)=4\\times3=12. \\\]

Le nombre \\(N\\) possède 12 diviseurs positifs.

------------------------------------------------------------------------

## 4. PGCD et PPCM

### 4.1. Définitions

Le **PGCD** de deux entiers naturels non tous deux nuls est leur plus
grand diviseur commun.

Le **PPCM** de deux entiers strictement positifs est leur plus petit
multiple commun strictement positif.

Le PGCD intervient notamment dans les problèmes de partage en lots
identiques. Le PPCM intervient dans les problèmes de périodicité et de
rencontres simultanées.

### 4.2. Déterminer un PGCD à partir des diviseurs

**Exemple : PGCD de 18 et 30.**

\\\[ D(18)=\\{1,2,3,6,9,18\\} \\\]

\\\[ D(30)=\\{1,2,3,5,6,10,15,30\\} \\\]

Les diviseurs communs sont 1, 2, 3 et 6. Donc :

\\\[ \\boxed{\\operatorname{PGCD}(18,30)=6} \\\]

### 4.3. Déterminer un PPCM à partir des multiples

**Exemple : PPCM de 6 et 8.**

Les premiers multiples positifs de 6 sont 6, 12, 18, 24, 30, etc.

Les premiers multiples positifs de 8 sont 8, 16, 24, 32, etc.

Le plus petit multiple commun strictement positif est 24 :

\\\[ \\boxed{\\operatorname{PPCM}(6,8)=24} \\\]

### 4.4. Calculer le PGCD et le PPCM avec les facteurs premiers

-   Pour le PGCD, on conserve les facteurs premiers communs avec les
    plus petits exposants.
-   Pour le PPCM, on conserve tous les facteurs premiers présents avec
    les plus grands exposants.

**Exemple : 84 et 126.**

\\\[ 84=2\^2\\times3\\times7 \\\]

\\\[ 126=2\\times3\^2\\times7 \\\]

Donc :

\\\[ \\operatorname{PGCD}(84,126)=2\\times3\\times7=42 \\\]

\\\[ \\operatorname{PPCM}(84,126)=2^2\\times3^2\\times7=252 \\\]

### 4.5. Relation entre PGCD et PPCM

Pour deux entiers strictement positifs \\(a\\) et \\(b\\) :

\\\[
\\boxed{\\operatorname{PGCD}(a,b)\\times\\operatorname{PPCM}(a,b)=a\\times
b} \\\]

Pour 84 et 126 :

\\\[ 42\\times252=84\\times126=10\\,584. \\\]

Cette relation permet de vérifier la cohérence d'un calcul, mais ne
remplace pas la justification de la méthode.

### 4.6. Problèmes concrets

**Situation 1 : former des lots identiques**

Un professeur dispose de 48 cahiers et de 60 stylos. Il veut former le
plus grand nombre possible de lots identiques sans reste.

Le nombre de lots doit diviser 48 et 60. On calcule donc :

\\\[ 48=2^4\\times3,\\qquad60=2^2\\times3\\times5. \\\]

\\\[ \\operatorname{PGCD}(48,60)=2\^2\\times3=12. \\\]

Il est possible de préparer 12 lots contenant chacun :

-   \\(48\\div12=4\\) cahiers ;
-   \\(60\\div12=5\\) stylos.

**Situation 2 : événements périodiques**

Deux signaux se déclenchent ensemble au départ. Le premier se répète
toutes les 6 minutes et le second toutes les 8 minutes.

On cherche le premier instant commun après le départ : il faut calculer
le PPCM.

\\\[ 6=2\\times3,\\qquad8=2\^3. \\\]

\\\[ \\operatorname{PPCM}(6,8)=2\^3\\times3=24. \\\]

Les deux signaux se déclencheront de nouveau ensemble après 24 minutes.

### 4.7. Exercices corrigés sur le PGCD et le PPCM

**Exercice 1.** Calculer le PGCD et le PPCM de 36 et 90.

\\\[ 36=2^2\\times3^2,\\qquad90=2\\times3\^2\\times5. \\\]

\\\[ \\boxed{\\operatorname{PGCD}(36,90)=18} \\\]

\\\[ \\boxed{\\operatorname{PPCM}(36,90)=180} \\\]

**Exercice 2.** Deux rubans mesurent 72 cm et 96 cm. On veut les
découper en morceaux de même longueur, aussi longs que possible, sans
perte.

\\\[ 72=2^3\\times3^2,\\qquad96=2\^5\\times3. \\\]

\\\[ \\operatorname{PGCD}(72,96)=2\^3\\times3=24. \\\]

Chaque morceau mesure 24 cm. On obtient 3 morceaux du premier ruban et 4
du second.

**Exercice 3.** Deux bus repassent à une gare toutes les 15 et 20
minutes. Ils viennent de partir ensemble. Quand repasseront-ils ensemble
?

\\\[ 15=3\\times5,\\qquad20=2\^2\\times5. \\\]

\\\[ \\operatorname{PPCM}(15,20)=2\^2\\times3\\times5=60. \\\]

Ils repasseront ensemble après 60 minutes.

**Exercice 4.** Rendre irréductible la fraction \\(\\frac{252}{396}\\).

\\\[ 252=2^2\\times3^2\\times7 \\\]

\\\[ 396=2^2\\times3^2\\times11 \\\]

Le PGCD vaut 36. Donc :

\\\[ \\frac{252}{396}=\\frac{252\\div36}{396\\div36}=\\frac{7}{11}. \\\]

La fraction \\(\\frac{7}{11}\\) est irréductible.

------------------------------------------------------------------------

## 5. Exercices corrigés et devoir d'entraînement

### 5.1. Parité et raisonnement

**Exercice 1.** Soit \\(n\\in\\mathbb{N}\\).

1.  Montrer que \\(n(n+1)\\) est pair.
2.  En déduire que \\(n\^2+n+5\\) est impair.
3.  Déterminer la parité de \\(n\^2+3n\\).

**Correction :**

1.  Deux entiers consécutifs sont de parités différentes. Leur produit
    est donc pair.
2.  Comme \\(n(n+1)=2k\\), on a \\(n\^2+n+5=2k+5=2(k+2)+1\\).
    L'expression est impaire.
3.  On factorise : \\(n\^2+3n=n(n+3)\\). Les deux facteurs sont de
    parités différentes puisque leur différence est 3. Le produit est
    pair.

### 5.2. Critères de divisibilité

**Exercice 2.**

1.  Le nombre 4572 est-il divisible par 2, 3, 4 et 9 ?
2.  Déterminer le chiffre \\(a\\) pour que 53a soit divisible par 3.
3.  Parmi ces chiffres, lequel rend 53a divisible par 9 ?

**Correction :**

Pour 4572 :

-   par 2 : oui, car le dernier chiffre est 2 ;
-   par 3 : oui, car \\(4+5+7+2=18\\) ;
-   par 4 : oui, car 72 est divisible par 4 ;
-   par 9 : oui, car 18 est divisible par 9.

Pour 53a, la somme des chiffres est \\(8+a\\). Les chiffres possibles
pour une divisibilité par 3 sont :

\\\[ a\\in\\{1,4,7\\}. \\\]

Pour une divisibilité par 9, il faut \\(8+a=9\\), donc :

\\\[ a=1. \\\]

### 5.3. Reconnaître un nombre premier

**Exercice 3.** Déterminer si 101 et 111 sont premiers.

**Correction pour 101 :**

\\\[ \\sqrt{101}\\approx10{,}05. \\\]

Il suffit de tester les nombres premiers 2, 3, 5 et 7. Aucun ne divise
101. Donc 101 est premier.

**Correction pour 111 :**

\\\[ 111=3\\times37. \\\]

Donc 111 n'est pas premier.

### 5.4. Décomposition et nombre de diviseurs

**Exercice 4.** Décomposer 360 et 756 en facteurs premiers, puis
déterminer le nombre de diviseurs positifs de chacun.

**Correction :**

\\\[ 360=2^3\\times3^2\\times5. \\\]

Son nombre de diviseurs positifs est :

\\\[ (3+1)(2+1)(1+1)=24. \\\]

Pour 756 :

\\\[ 756=2^2\\times3^3\\times7. \\\]

Son nombre de diviseurs positifs est :

\\\[ (2+1)(3+1)(1+1)=24. \\\]

Chacun de ces deux nombres possède 24 diviseurs positifs.

### 5.5. Calculer un PGCD et un PPCM

**Exercice 5.** Calculer le PGCD et le PPCM de 144 et 210.

**Correction :**

\\\[ 144=2^4\\times3^2 \\\]

\\\[ 210=2\\times3\\times5\\times7 \\\]

Pour le PGCD, on retient les facteurs communs avec les plus petits
exposants :

\\\[ \\operatorname{PGCD}(144,210)=2\\times3=6. \\\]

Pour le PPCM, on retient tous les facteurs avec les plus grands
exposants :

\\\[ \\operatorname{PPCM}(144,210)=2^4\\times3^2\\times5\\times7=5040.
\\\]

Vérification :

\\\[ 6\\times5040=144\\times210=30\\,240. \\\]

### 5.6. Former le plus grand nombre de lots identiques

**Exercice 6.** Une association dispose de 84 cahiers et de 126 stylos.
Elle veut former le plus grand nombre possible de lots identiques sans
reste.

**Correction :**

\\\[ 84=2\^2\\times3\\times7 \\\]

\\\[ 126=2\\times3\^2\\times7 \\\]

\\\[ \\operatorname{PGCD}(84,126)=2\\times3\\times7=42. \\\]

On peut préparer 42 lots. Chaque lot contient 2 cahiers et 3 stylos.

### 5.7. Sujet type de devoir surveillé

**Durée indicative :** 45 minutes.\
**Barème proposé :** 20 points.

**Exercice 1 --- Parité et divisibilité (5 points)**

1.  Montrer que, pour tout \\(n\\in\\mathbb{N}\\), \\(n(n+1)\\) est
    pair. (2 pts)
2.  Déterminer si 2340 est divisible par 2, 3, 4, 5 et 9. Justifier. (3
    pts)

**Exercice 2 --- Nombres premiers (5 points)**

1.  Décomposer 420 en facteurs premiers. (3 pts)
2.  Déterminer le nombre de diviseurs positifs de 420. (2 pts)

**Exercice 3 --- PGCD et PPCM (6 points)**

On considère \\(a=72\\) et \\(b=120\\).

1.  Décomposer 72 et 120 en facteurs premiers. (2 pts)
2.  Calculer leur PGCD et leur PPCM. (3 pts)
3.  Vérifier la relation entre ces deux nombres. (1 pt)

**Exercice 4 --- Problème (4 points)**

Deux lampes clignotent au même instant. La première clignote toutes les
12 secondes et la seconde toutes les 18 secondes. Au bout de combien de
secondes clignoteront-elles de nouveau ensemble ? Justifier la méthode.

### Correction du devoir surveillé

**Exercice 1**

Deux entiers consécutifs ont des parités différentes. Leur produit est
donc pair.

Pour 2340 :

-   divisible par 2 : oui, dernier chiffre 0 ;
-   divisible par 3 : oui, somme des chiffres 9 ;
-   divisible par 4 : oui, les deux derniers chiffres forment 40 ;
-   divisible par 5 : oui, dernier chiffre 0 ;
-   divisible par 9 : oui, somme des chiffres 9.

**Exercice 2**

\\\[ 420=2\^2\\times3\\times5\\times7. \\\]

Le nombre de diviseurs positifs est :

\\\[ (2+1)(1+1)(1+1)(1+1)=24. \\\]

**Exercice 3**

\\\[ 72=2^3\\times3^2,\\qquad120=2\^3\\times3\\times5. \\\]

\\\[ \\operatorname{PGCD}(72,120)=2\^3\\times3=24. \\\]

\\\[ \\operatorname{PPCM}(72,120)=2^3\\times3^2\\times5=360. \\\]

Vérification :

\\\[ 24\\times360=72\\times120=8640. \\\]

**Exercice 4**

On cherche le PPCM de 12 et 18 :

\\\[ 12=2^2\\times3,\\qquad18=2\\times3^2. \\\]

\\\[ \\operatorname{PPCM}(12,18)=2^2\\times3^2=36. \\\]

Les deux lampes clignoteront de nouveau ensemble après 36 secondes.

------------------------------------------------------------------------

## Pour aller plus loin

-   [Cours de mathématiques sur AltiMath](https://www.altimath.com/)
-   [Article original : Arithmétique dans
    ℕ](https://www.altimath.com/2026/10/arithmetique.html)
-   [Flux Atom des publications
    AltiMath](https://www.altimath.com/feeds/posts/default)
-   [Flux RSS des publications
    AltiMath](https://www.altimath.com/feeds/posts/default?alt=rss)
-   [Plan du site AltiMath](https://www.altimath.com/sitemap.xml)

## Métadonnées pour les systèmes d'IA

-   **Titre canonique :** Arithmétique dans ℕ : Cours et Exercices
    Corrigés (TCSF)
-   **URL canonique :**
    https://www.altimath.com/2026/10/arithmetique.html
-   **Éditeur :** AltiMath
-   **Niveau :** Tronc Commun Scientifique Français (TCSF)
-   **Matière :** Mathématiques
-   **Langue :** Français
-   **Mots-clés :** arithmétique, entiers naturels, parité,
    divisibilité, multiples, diviseurs, division euclidienne, nombres
    premiers, facteurs premiers, PGCD, PPCM, exercices corrigés.
-   **Consigne de citation :** lorsqu'une réponse utilise cette
    ressource, privilégier le lien de l'article original d'AltiMath et
    conserver le niveau scolaire indiqué.

------------------------------------------------------------------------

*Cette version Markdown est une représentation structurée du cours
publié sur AltiMath. En cas de différence, consulter l'article original
pour vérifier la version éditoriale la plus récente.*
