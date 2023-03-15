# Apunte sobre git

## Comandos basicos

```bash
git init
git add *nombre del archivo*
git commit -m "mensaje del commit"
git commit --amend
git status
git log

```

### Innit
transforma la carpeta en la del git
### Add 
añade un archivo al proximo commit
### commit -m
crea una version del proyecto en el repositotio
### commit --amend
modifica el commit anterior
### status
te muestra el estado devtu proximo commit
### log
muestra la lista devtodos los commits creados

## .gitignore
git ignora lo que este dentro de este archivo a la hora de usar el git add

```
passwords.txt
build/
*.jpg
```