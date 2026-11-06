*This project has been created as part of the 42 curriculum by margagab.*

<h1 align = "center" style = "font-size: 5em;"> Libft </h1>
<br>

## Description
Libft est une bibliothèque que j'ai créée dans le cadre du cursus de 42.

Le but de ce projet est de recréer plusieurs fonctions de la bibliothèque standard du C, mais aussi d'en créer de nouvelles qui pourront être utiles dans les prochains projets.

<br>

Le projet est composé de trois parties :

* **Fonctions de la libc** : réimplémentation de fonctions de la libc.

* **Fonctions supplémentaires** : fonctions permettant notamment de manipuler des chaînes de caractères, de faire des conversions ou d'écrire sur un descripteur de fichier.

* **Listes chaînées** : création et manipulation de listes chaînées avec une structure.

<br>

## Instructions
Pour compiler la bibliothèque, il suffit de lancer :
```bash
make
```

Cela crée la bibliothèque `libft.a`.

<br>

Le Makefile contient également les commandes suivantes :
```bash
make clean
make fclean
make re
```

`clean` supprime les fichiers objets.

`fclean` supprime également la bibliothèque.

`re` permet de tout recompiler.

<br>

Pour utiliser la bibliothèque dans un autre projet, il suffit d'inclure `libft.h` et de compiler le programme avec `libft.a`, accessible depuis le dossier courant.

Par exemple :
```bash
cc main.c libft.a
```
<br>

## Fonctions
### Fonctions de la libc
La première partie consiste à recréer des fonctions de la bibliothèque standard du C :

`ft_isalpha` - `ft_isdigit` - `ft_isalnum` - `ft_isascii` - `ft_isprint` - `ft_strlen` - `ft_memset` - `ft_bzero` - `ft_memcpy` - `ft_memmove` - `ft_strlcpy` - `ft_strlcat` - `ft_toupper` - `ft_tolower` - `ft_strchr` - `ft_strrchr` - `ft_strncmp` - `ft_memchr` - `ft_memcmp` - `ft_strnstr` - `ft_atoi` - `ft_calloc` - `ft_strdup`

### Fonctions supplémentaires
La deuxième partie ajoute des fonctions pour la manipulation de chaînes :

`ft_substr` - `ft_strjoin` - `ft_strtrim` - `ft_split` - `ft_itoa` - `ft_strmapi` - `ft_striteri` - `ft_putchar_fd` - `ft_putstr_fd` - `ft_putendl_fd` - `ft_putnbr_fd`

### Listes chaînées
La dernière partie permet de travailler avec des listes chaînées grâce à la structure `t_list` :

`ft_lstnew` - `ft_lstadd_front` - `ft_lstsize` - `ft_lstlast` - `ft_lstadd_back` - `ft_lstdelone` - `ft_lstclear` - `ft_lstiter` - `ft_lstmap`

<br>

## Ressources
Pour ce projet, j'ai principalement utilisé le **man** et le **web** pour comprendre le fonctionnement des fonctions.

J'ai également consulté des dépôts **GitHub** et j'ai demandé de l'aide à d'autres **étudiants** ainsi qu'à des **proches** lorsque j'avais besoin de plus d'explications.

Pour tester mes fonctions, j'ai fait des **main**, j'ai utilisé une **Moulinette** trouvée sur Internet et l'**IA** en cas de doute.

<br>

## Utilisation de l'IA
J'ai principalement utilisé l'IA pour ce **README** et pour m'aider lors des **corrections** des fonctions.

Son utilisation est restée **modérée** et aucune ligne de code de ce projet n'a été générée par IA.

L'objectif était de comprendre les problèmes rencontrés et de progresser, plutôt que de faire réaliser le projet directement par l'IA.
