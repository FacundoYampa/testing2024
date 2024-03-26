Este es un repositorio de ejemplo para explicar el flujo de trabajo de git. Por ahora se hicieron las sguientes operaciones

git config --global user.name "jjcblanco" git config --global user.email "jjcblanco@gmail.com"

Se creó una carpeta llamada testing_git

Abrimos el cmd y nos movemos a la carpeta con cd (para entrar en una carpeta de pone cd nombre y para subir cd ..)

Entramos en ella con cd testing_git y realizamos las modificaciones o agregados

con git init (inicializamos el proyecto o repositorio)
usando git status para ver los cambios que voy haciendo
agregamos el nuevo archivo creado con git add . (agrega todos los archivos de la carpeta)
git commit -m "Mi primer commit" con esto establecemos el mensaje del primer commit
me respondio
[master 7936b8f] modificacion 1 file changed, 3 insertions(+), 2 deletions(-)
Ahora linkeo mi repositorio local con el repositorio remoto de github
para eso voy a github y cree un repo llamado testing_git copie el link https://github.com/jjcblanco/testing_git
y lo pegue como: git remote add origin https://github.com/jjcblanco/testing_git.git
luego puedo hacer un push al repositorio remoto con : git push -u origin master
que me respondio
Enumerating objects: 6, done. Counting objects: 100% (6/6), done. Delta compression using up to 24 threads Compressing objects: 100% (4/4), done. Writing objects: 100% (6/6), 579 bytes | 579.00 KiB/s, done. Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 remote: Resolving deltas: 100% (1/1), done. To https://github.com/jjcblanco/testing2024.git
[new branch] main -> main branch 'main' set up to track 'origin/main'.
