# Apunte sobre git

## Comandos basicos



### Innit
crea el repositorio de git
### Add 
añade un archivo al proximo commit
### commit -m
crea una version del proyecto en el repositotio
### commit --amend
modifica el commit anterior
### status
te muestra el estado devtu proximo commit
### log
muestra la lista devtodos los commits creado

```bash
git init
git add *nombre del archivo*
git commit -m "mensaje del commit"
git commit --amend
git status
git log 
git checkout  -b *nombre rama nueva*
```

## Descargar repositorio de la nube


### clone
copia el repositorio del link que se le es dado en el link
### pull
actualiza el repositorio a la ultima version en la nube

```bash
git clone  
git pull
```

## .gitignore

git ignora lo que este dentro de este archivo a la hora de usar el git add

```
passwords.txt
build/
*.jpg
```

## Ramas
```bash
git checkout  -b *nombre para la rama nueva*
git checkout *nombre de rama a la que queres cambiar*
git merge *nombre de la rama con la que se quiere fusionar*
```
### chekout -b

crea una rama nueva

### chekout

pasa a la rama que se desee

### merge

fusiona los archivos de dos ramas (en la que se usa y la que se especifica)

