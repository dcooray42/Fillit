# Fillit

Deuxième projet de l'école 42. Créer un programme qui prend en paramètre un fichier contenant des formes de tetriminos 
valables et qui retourne le carré le plus petit possible avec les tetriminos agencés à l'intérieur de ce dernier.

## Pour commencer

Ces instructions vous aideront à avoir une copie du projet et de pouvoir le faire marcher sur votre ordinateur.

### Prérequis

**Attention: A partir de maintenant, toutes les étapes (téléchargement, installation/compilation, exécution) seront à effectuer sur un terminal.**

#### Système d'exploitation

```
GNU/Linux, Mac OS X ou macOS Sierra
```

#### Téléchargement
Ce que vous devez faire pour télécharger les fichiers sources afin de pouvoir les compiler par la suite

```
git clone https://github.com/konamifox/Fillit.git [nom du PATH/dossier]
```

### Installation

Se placer dans le dossier dans lequel vous avez fait la copie des fichiers sources du projet puis rentrer la commande suivante

```
make
```
Plusieurs fichiers .o auront fait leur apparitions dans le dossier que vous avez cloné ainsi que le binaire

```
fillit
```
### Suppression

Pour supprimer les fichiers objets .o généré lors de la création du programme

```
make clean
```

Pour supprimer les fichiers objets .o et le programme

```
make fclean
```

Pour tout supprimer puis recompiler le programme

```
make re
```

## Faire des tests

Une fois que le programme a été créé, vous n'avez plus qu'à rentrer en ligne de commande le nom du programme + un fichier 
contenant des tetriminos valides.

### Utilisation du programme

Ligne de commande

```
./fillit [PATH/nom du fichier avec les tetriminos valides]
```

#### Exemple
![alt text](https://raw.githubusercontent.com/konamifox/Fillit/master/photo/photo_test.jpeg)
![alt text](https://raw.githubusercontent.com/konamifox/Fillit/master/photo/photo_fillit.jpeg)

## Note
100/100

## Auteur

* **Dimitri Cooray** - [Lien vers github](https://github.com/konamifox)
