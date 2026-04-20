
Este archivo contiene los comandos esenciales para gestionar el repositorio.

## 1. Flujo Diario (Guardar cambios)
Para subir tus avances al repositorio de GitHub:

* git status -> Revisa qué archivos has modificado.
* git add . -> Prepara todos los archivos para el guardado.
* git commit -m "Descripción de lo que hiciste"` -> Crea una "foto" de tus cambios.
* git push origin principal -> Sube tus cambios a la nube.

## 2. Actualizar el código local
Si trabajas con alguien más (como Cesar Mosquera) o desde otra PC:

git pull origin principal -> Trae los cambios más recientes de GitHub.

## 3. Ramas (Branches)
Para trabajar en funciones nuevas sin dañar el código principal:

* git branch -> Lista las ramas actuales.
* git checkout -b nombre-rama -> Crea y se cambia a una rama nueva.
* git checkout principal -> Vuelve a la rama principal.

4. Otros útiles
* git log --oneline -> Ver el historial de cambios resumido.##
##CONSULTAR LOGS

## 4. Git log
git log --onñine
gitl log --online -graph --all
git log --stat 
git log -p
git log -s
git log --oneline -10
git log --author= "coraquillafreddy@gmail.com"

# 5. Por fecha 

git log --afther="2026-01-01"
git log --before="2026-01-01"
git log --afther"2026-01-01" 

# 6. Consutar commit especifico 

git show 3950b43540b5460a1cb8169c357bc909f6a62a6b
git show 3950b43540b5460a1cb8169c357bc909f6a62a6b --name-only
git show 3950b43540b5460a1cb8169c357bc909f6a62a6b --stat

git show ccc76e1a762350fedbd2e3122400409d7bfc10bd
git show ccc76e1a762350fedbd2e3122400409d7bfc10bd --name-only
git show ccc76e1a762350fedbd2e3122400409d7bfc10bd --stat

# 7. Modificar el ultimo commit 

git commit --amend -m "feat 
