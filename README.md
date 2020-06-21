# git-cheat-sheet
Very useful git commands / Comandos utiles de git

###### Clone a repo at the current path / Clonar un repositorio en el path actual
```shell
git clone git@github:me/name.git .
```

###### Add a remote to a folder / Agregar un remoto a una carpeta
```shell
git remote add origin https://github.com/jlsubia404/hyperblog.git</b>
```
###### Show origins / Muestra los origines 
```shell
git remote -v
```

###### Create a new local branch / Crear una rama local
```shell
git checkout -b myNewBranch
```

###### Restore all working tree files with top pathspec magic / Devolver todos los cambios en unstage
```shell
git restore :/
```

###### Show all branches with the las commit of each one. Addiontaly, mark with '*' the current branch / muestra todas las ramas con el ultimo commit de cada uno. Adicionalmarca con *  la rama actual
```shell
git branch -v
```

###### Show the history commit of an specific file / Muestra la historia de un archivo en especifico
```shell
git log --full-history [path_of_my_file]
```


###### Force to merge a commit with remote / forzar a fusionar commit de un remoto
```shell
git pull origin master --allow-unrelated-histories
```


###### Show the git command help / Para ver la ayuda de cualquier comando
```shell
git [comando] --help
```
