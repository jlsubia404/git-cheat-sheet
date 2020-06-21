# git-cheat-sheet
Very useful git commands / Comandos útiles de git

###### Clone a repo at the current path / Clonar un repositorio en el path actual
```shell
git clone git@github.com:jlsubia404/git-cheat-sheet.git .
```

###### Add a remote to a folder / Agregar un remoto a una carpeta
```shell
git remote add origin git@github.com:jlsubia404/git-cheat-sheet.git
```
###### Setting an url with 'origin' name / Establecer una url a un remoto con nombre 'origin'
```shell
git remote set-url origin git@github.com:jlsubia404/git-cheat-sheet.git
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
###### Add changes to the las commit with edit the message / Agrega los  cambios que hice al commit anterior. Ej: Cuando nos olvidamos de hacer commit de un archivo, entonces solo lanzamos ammend en lugar de crear otro commit

```shell
git commit --amend --no-edit
```
