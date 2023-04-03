# Que es git?

Git es un sisteme de control de versiones. ¿Que es el "control de versiones"?
Es un sistema que registra los cambios en un archivo o conjunto de archivos a 
lo largo del tiempo para que se puedan recuperar versiones especificas mas adelante.
## Comandos Basicos

### Quick Resume

1. `git pull` 
2. `git status`
3. `git add .`
4. `git commit -m "file message" -m "description message"`
5. `git push -u origin master`  

### Extra

1. `git config --global user.email "email@com"`
2. `git config --global user.name "name"`

# git branching 
MB = Mastes Branch
FB = Feature Branch
HFB  = Hot Fix Branch

                        HFB
MB => c#1 => MB => c#2 MB c#3 MB c#4             Merge
                    FB c#1 FB c#2 

- git branch
- git checkout
- git checkout brand.name
- git checkout -b new-branch

## Github Workflow

write code
commit changes
make a pull request

## Local Git Workflow

write code 
stage canges
git add
commit changes
git commit
push changes
git push
make a pull request


