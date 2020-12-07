# Les variables en bash
Les variables en bash ne sont pas typer contrairment au autre langage de programation. Mais il exite des varible particuliere. Les varibles d'environnements.
Les variables d'environnements sont des donné du systeme recurable à tous moments.

# Les varibles d'environnements
- USER : Nom de l'utilisateur
- PATH : chemin d'accès au fichier bin qui contient le Shell
- LOGNAME : Nom de l'utilisateur connecté
- HOME : Répertoire home
- SHELL : Type de Shell utilisé
- PWD : Répertoire et chemin d'accès dans lequel on se trouve
- TERM_PROGRAM : Programme utilisé pour gérer le terminal
- TERM_PROGRAM_VERSION : La version du programme en question
- LANG : Langue utilisée avec son encodage
- _ : chemin d'accès à la commande printenv

# Afficher les varibles
- printenv : Affiche les variables d'environnement actives
- echo $VAR : Affiche le contenu de la variable d'environnement 
- set (liste des variables paramétrées)
- env : variables exportées d'office 

On utilise le symbole **$** pour preciser que ce sont des variables.

# Exemple
- echo : permet d'imprimer l'élement donner en parametre
![example](./picture/example_echo.png)
Echo nous print le parametre donné que se soit un varaible environnementale ou bien une variable créé de tout pièce.
Prenez du temps pour vous familiariser avec les variables d'environnemants et penser a utiliser la commande man si vous avez des doutes ou que vous voulez plus d'information.

*[Retour au sommaire](./README.md)* | *[chapitre précédent](https://github.com/lancelot260/linux/blob/main/commande.md)* | *[chapitre suivant](https://github.com/lancelot260/linux/blob/main/script%3F.md)*
