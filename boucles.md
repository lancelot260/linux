## Les Boucles en SHELL

Les boucles en bash comportent deux types les boucles **for** et les boucles **while**.

# Les boucles **for**

la boucle **for** permet de parcourir une liste d'une taille connue. La boucle for comprend trois composant l'initialisation, la condition et l'opperation.
- L'initialisation comme le nom l'indique vous devez indiquer une varible qui vous servira d'index dans la boucle.
- la condition vous permet de regler juqu'à ou votre boucle bouclera.
- l'opperation precise quel calcule la boucle doit effectuer un addition, une soustraction, une multiplication ou biens une division.

voici un petit example
![for example](./picture/Screenshot_2020-12-10_08-57-50.png)

Ici la boucle **for** va créer une variable **i** qui sera intialisé à 0. La boucle effectura sont operation tant que 10 - la valeur de **i** n'est pas égale à 0 et l'opperation est tout simplement **i** + 1. Mais bon on dit "qu'un act vaut mille discours" donc voilà le resultat de notre petite boucle

![for result](./picture/Screenshot_2020-12-10_08-58-14.png)

Et voilà! notre boulce a effectuer dix fois son opperation. Mais passons a l'interieur de notre boucle.
Comme vous avez pu le constater il y a unbout de code dans notre boucle, on peut le remarquer par son decalement par rapport au reste du code. Ce code est ce que on appele le corp de la boucle. Soit l'utiliter de votre boucle. Le corp de votre boucle sont toutes les choses que votre boucle va effectuer le nombre de fois demander. Dans notre example il affiche simplement le nombre de tours que la boucle effectue.

# Les boucles **while**

la boucle **while** effectura ses instructions tant que la condition que vous poser sera respecter. Cette boucle permet donc d'affectuer une tache sans avoir forcément besoins de connaitre la fin de la liste que nous traitons.
La boucle while ne prend que une condition comme parametre. Voici un petit example :

![while exemle](./picture/Screenshot_2020-12-10_11-19-30.png)

Dans ce cas la boucle vous demande de taper yes et ne s'erettera pas tant que la condition n'es pas remplise.

![while result](./picture/Screenshot_2020-12-10_11-20-36.png)

Voila ce que cela donne une fois executer.

## Atention 

Vous pouvez créer ce que on appele des boucle infini soit des boucles qui ne se stoperon jamais. la plus connue est tout simplement :

`while true; do`
 
 ` echo hello`

`done`

Si jamais vous faites une boucle infinie non voulu fermais votre terminal ou faite la commande **CRT + C**
