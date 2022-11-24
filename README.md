#### A propos

Ce dépôt contient un workspace préconfiguré pour développer des programmes C++ sur une machine linux.



#### Prérequis

Les éléments suivants doivent être installés sur la machine linux :

- le compilateur *g++*,
- le débogueur *gdb*,

```bash
sudo apt install g++ gdb
```

#### Remarques

Le workspace peut être testé en compilant et en exécutant le fichier *main.cpp* situé dans le dossier *hello-world*

Pour ajouter un nouveau programme au workspace :

- créer un nouveau dossier dans le workspace ;

- écrire le code du nouveau programme dans ce nouveau dossier. 

**Important** : Pour que la compilation ne pose pas de problème, il est impératif qu'il n'y ait pas plusieurs programmes *main()* dans un même dossier &rarr; il faut donc un seul programme main() par dossier.
