# apunte sobre git

## comandos basicos

```bash
git init							#1, crea el repositorio
git add								#2, agrega el archivo al próximo commit
git commit -m "mensaje del commit"	#3, es para agregar un commit
git commit --amend					#3b, modifica el commit anterior
git status							#-, te dice cómo está el próximo repositorio
git log								#-, ver todos los commits
git clone                           #-, clonar lo que haya en el github a la compu
git pull                            #-, actualiza el repositorio remoto con el local
cd + dirección de carpeta           #-, posicionarse en una carpeta desde el git
git checkout master                 #-, es la rama master    

## rama nueva 
git checkout -b (rama) "crea la rama"
git checkout (rama) "cambia de rama"
git merge (rama) "para fusionar ramas"
git difftool (rama) "marca las diferencias entre ramas"
git stash "limpia el commit, para descartas cambios"
git push --upstream origin (rama) "crea la rama en el github"


```