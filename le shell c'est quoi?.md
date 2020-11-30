# Pour biens commencer
# Votre machine
Avant de voir ce qu'est le shell penchons nous un peu sur la machine soit votre ordinateur. Chaque machine a son propre système d'exploitatation.
Qui depent de votre machine. le système d'exploitation permet de faire la liaison entre le HardWare et le SoftWare. Le HardWare sont les ressources materielles de votre pc.
Comme âr exemple votre pocesseur, votre disque dur ou biens votre ram et tous autres composant de votre pc. 
Le SoftWare sont les applications de votre ordinateur par exemple votre explorateur de fichier, votre moteur de recherche ou biens votre terminal.
L'OS (accronyme pour système d'exploitatoin) permet de faire transiter les demande de l'utilisateur depuis les aplication au ressource matereil de votre machine grace a des pilotes. Ces  pilotes sont lancer des le demarage de votre machine.

# Les composants d'un OS
penchons un peu sur les composants d'un OS pour mieux comprendre ce que nous allons manipuler :
* Le KERNEL
  * Noyau de l'OS
  * Gère les fonctions clés de l'OS
  * Permet la communication directe avec les ressources matérielles
  * Interface entre le logiciel et le matériel de l'ordinateur
* Les DRIVERS 
  * Correspondance au pilotes
  * Gere le bon foctionnement des peripheriques
* LE SHELL
  * Interpréteur de commandes
  * Permet de communiquer avec l'OS par l'intermédiaire d'un langage de commandes
![Schéma du système d'exploitation](./img/architecture.png)

# Defenition shell:
Un shell Unix est un interpréteur de commandes destiné aux systèmes d'exploitation Unix et de type Unix qui permet d'accéder aux fonctionnalités internes du système d'exploitation.
Il se présente sous la forme d'une interface de ligne de commande accessible depuis un terminal. Le shell existe en plusieur version : 
- powershell pour windows
- zsh! pour mac
- bash
- ssh
- ksh
Pour n'en citer que quelqu'un.
# 
Ces versions de shell different tous des particuliarité propre certaint langage sont quasiment indentique de l'un à l'autre, mais ils ont tous la même utilité.
Tout les versions de shell sont utiliser pour pouvoir optimiser des taches basique qui prendrait plusiuer ligne de commande. Le shell permet de créer des scripts.
Les scripts sont des fichiers qui vont effectuer certaine ligne de commande pour vous faire taper moins de ligne de commande et vous rendre la cie plus simple.
Donc pourquoi utiliser le shell? Le shell permet de lancer des scripts qui effecturons de multitude de ligne de commande anfin d'optimiser votre temps pour vous donner un exemple:
un script pourait suprimer tous les fichiers temporaires dans votre dossier, compiler vos frichier et lancer l'excutable et finir par le suprimé.
A la ffin le script vous enverez un message pour vous prevenir comment c'est passer le deroullement de l'operration avec des message d'erreur qui sont modifier au cours du script.
Ce qui vous permetera de garder un oeil sur le deroulement de l'action facilement.
