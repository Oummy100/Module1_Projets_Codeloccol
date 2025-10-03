# Correction de l'exercice N°5

## les Commandes Utilisées

``` mkdir -p``` : Pour créer une arborescence de dossiers,je l'ai utilisé pour créer l'arborescence des dossiers **projet_scolaire/maths projet_scolaire/sciences**
Syntaxe: ```mkdir nom_du_dossier```

``` cd ``` : Pour Aller d'un repertoire à un autre
Syntaxe: ```cd nom_du_repertoir```

NB: ```cd ..```permet de retourner dans le dossier precedant

```touch``` : Pour créer un ficher, je l'ai utilisé pour créer le fichier texte **equations.txt** et **experiences.txt**.
Syntaxe: ```touch nom_du_fichier```

```echo``` : Pour ajouter du texte dans un fichier, je l'ai utilisé pour ajouter du texte les deux dossiers **equations.txt** et **experiences**

syntaxe:

```echo "texte_à_ajouter" >> nom_du_fihier_destinataire```

```mv``` : Pour deplacer/renommer un fichier/dossier, je l'ai utilisé pour renommer le fichier **equation.txt** en **geometrie.txt** et deplacer le fichier **experiences.txt** vers **Users/oummy/projet_scolaire/maths**

Syntaxe: 

|  | Fichier          | Dossier |
| :--------------- |:---------------:| -----:|
| Déplacer  |   ```mv nom_du_fichier  chemin/vers/l'/emplacement```      |  ```mv nom_du_dossier chemin/vers/l'/emplacement```
| Renommer  | ```mv nom_actuel_du_fichier nouveau_nom_du_fichier```             |  ```mv nom_actuel_du_dossier nouveau_nom_du_dossier```  |

```rm``` : Pour supprimer un fichier/dossier,je l'ai utilisé dans l'exercice pour supprimer le dossier **sciences**

Pour supprimer un dossier il faut ajouter l'option ```-r```(récursif) afin d'indiquer à la commande rm de supprimer le dossier ainsi que tout son contenu.

syntaxe:

Supprimer un simple fichier: ```rm nom_du_fichier.txt```

Supprimer un dossier: ```rm -r nom_du_dossier```

## Capture d'écran de l'exercice

![la capture de l'esxercice](Capture_exercice5.png)