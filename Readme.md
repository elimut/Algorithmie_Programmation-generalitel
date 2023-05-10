# Algorithmie Programmation

## Algorhitmie

>Processus de résolution de problème
Série d'instruction, suivies étapes par étapes pour faire quelques chose d'utile, ou résoudre un problème.
Différentes manières de résoudre un problème, puis faire en sorteque l'ordinateur le fasse pour moi.
Langage naturel qui sera traduit en langage de programmation (traduction d'algorithmes en suite d'instructions compréhensibles par l'ordinateur. Machine ne sachant gérer que des 0 et des 1 = **système binaire**, avant cartes perforées. Ordinateur ne comprend pas la,ngage naturel, et difficulté de coder en 0 et 1 -> langage de programmation).

## Programmation, programme

Constitués de plusieurs algorithmes et interface utilisateur.

>Ensemble d' instructions exécutables par un oridnateur, et qui permet à ce dernier de répondre à un problème que nous nous posons.

Prend un ensemble de données d'entrée, exécute des instructions, puis retourne des données en sortie.
Doit fonctionner dans tous les cas possibles.

Action effectuée par un programme -> **instruction**
Il en existe trois grandes catégories : 
- opérations de base
- exécution conditionnelle
- itération

Ensemble des lignes d'un programme = **code ou code source/source** (sorte d'encodage).
Coder, ou encoder (= programmer) = traduire les acttions à exécuter dans un langage de programmation.
Actions définies par des algorithmes préalablemment rédigées dans un langage intermèdiaire entre description en langage naturel, et le langage de programmation = **pseudo-code ou LDA**(Langage de Description d'Algorithme).

Instruction de haut en bas.

Code contient des lignes d'instructions exécutant une action élémentaire.

>Informatique:
>- Acquisition de l'information (ou **données**= contenu brut, aucun traitement intellectuel)
>- Traitement de l' information
>- Restitution de l'information


>**Arithmétique binaire**(base 2) ->
gestion 0 et 1 (tous les jours base 10: dix chiffres de 0 à 9, chiffre à gauche on plus de poids ex: 587 = 500+80+7 -> (5.10²)+(8.10¹)+(7.10^0)).
Valable pour toutes les bases:
2^4 = 2.2.2.2
x^0 = 1
ex: 1111 base 2 ->
    (1.2³)+(1*2²)+(1.2^1)+(1.2^0)
    ->
    (2.2.2)+(2.2)+(2.1)+(2*0)=
    8+4+2+2+1= 15 base 10
|B10|0|1|2|3|4|5|
|:--|:--|:--|:--|:--|:--|:--|
|B2|0|1|10|11|100|101|
>Valeurs des puissances de 2 :
|Puissance de 2|0|1|2|3|4|5|6|7|8|9|10|
|:-------------|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|
|Valeurs|1|2|4|8|16|64|128|256|512|1024|

## Variables

"Tiroir" ou "étiquettes".
**Existent quand nom et type attribués = initialisation**.

>Emplacement pour stocker des données temporairement, contenu pouvant varier au cours du programme.
Peut être définie par utilisateur ou programme lui-mêle.
On peut accèder à son contenu en faisant référence à son nom.

Ne permettent que deux types d' opérations : 
- lecture données
- stockage données

Un programme, peut ne pas contenir de variable, mais les variables améliore la lisibilté du code.

**Déclarer = créer**
En pratique une variable par info à traiter.

**Nommer**: important surtout si beaucoup de variables.
- explicite
- long et descriptif
- aucunes abréviations
- aucun espace(utiliser _)
- minuscule (sauf sigle) 

Une variable a une durée de vie qui n' excède pas la durée d'exécution du programme.Créee par programme et cesse d' exister à la fin de celui-ci.
Les données stockées dans les varibles sont hebergées dans la mémoire vive ( =**RAM** ) de l'ordinateur. Mémoire volatile, qui s'efface lorsque l'on éteint l'ordinateur.

### Types de données:

Nombre, texte, date...
One ne peut pas mélanger nombre et texte.
En attribuant; des types de données à une varibale, le programme est capavble de détecter certaines erreurs.

>**Déclarer (existe)-> Nom Initialiser : Type, valeur**.

### Opérations courantes 

#### Variables type nombre :

**Incrémentation**= valeur variable est incrémentée signifie valeur variable augmente. Par défaut, est égal à 1.

**x=x+1 -> signifie affecter 1 différent = mathématiques ( égal à).**

#### Variables type texte:

**String**= Chaîne de caractère, données textuelles.

**Concaténation**= Opération qui consiste à mettre bout à bout des chaînes de caractères.

#### Boucles:

Répèter les instructions.
Instructions se lisent d ehaut en bas, mais modification possible et mise à jour ordre exécution instruction.

- Répète toutes les instructions de la boucle
- Dans ordre d' écriture
- Parcours des instructions dans la boucle= **itération** (iter latin= chemin)
- Une fois le nombre d' iétration accomplies, le programme sort de la boucle, et exécute l' instruction qui suit immédiatemment
- Il peut y avoir une  boucle dans la boucle

-> Tant que: **While**
Répète un certains nombres de fois en fonction d'une **condition**(expression logique à laquelle on peut attribuer la valeur vrai/faux.En général, deux valeurs qui sont reliées par un opérateur).

Répète instructions dans boucle tant que la condition est vraie.

->Boucle infinie:
Si instructions dans la boucle ne font jamais évoluer la condition.


->Jusqu'à:
Répète jusqu'à ce que condition soit vraie.
Boucle éxécutée tant que la condition est fausse.

->Imbriquées:
Boucle dans boucle (ex: boucle imbriquée de Pythagore).


#### Test conditionnel

Instruction qui pose une question au programme et qui exécute une action en fonction de la réponse donnée.

>**Attention aux informations binaires: il est impératif qu'on ne puisse répondre que par oui ou par non**

Dans un test conditionnel, le programme va évaluer une condition logique (=détermine si énoncé de la condition est vrai ou faux).

->Si Sinon:

Quand deux choix s' excluent mutuellement plutôt que "si/si".

->Si Sinon Si:

Dans le cas de plusieurs options.

Les conditions sont évaluées dans l'ordre d'écriture, dès qu'une condition est vraie sort du bloc si.

>Placement en tête des conditions les plus souvent vraies.Cela permet de réduire le temps d' exécution.


->Conditions complexes:

Formées à l'aide d'opérateurs logiques.










