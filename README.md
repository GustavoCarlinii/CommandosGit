# CommandosGit
comandos basicos de git

#iniciar proyecto
git init

#Agregar nombre de usuario:
en la terminal local 
git config user.name "nombre de usuario de github"

#Agregar email:
git config user.email "email"

#Para hacerlo global(Todos mis repositorios locales sabran quien soy)
agregar:
--global 
git config --global user.name "nombre de usuario"
git config --global user.email "email"

#Añadir un repositorio remoto a uno local 
git remote add origin colocar la url de tu repositorio remoto 

#Verificar con que repositorio esta syncronizado
git remote -v

#Agregar mis archivos al repositorio:
git status (vere el estado de mis archivos respecto al repositorio)
git add . (agrega el archivo al repositorio, en este caso agrega todos los archivos presentes en el repositorio, para archivos puntaules hago git add nombreArchivo.js)

#Control de versiones:
para agregar los cambios de los archivos, realizo nuevamente
git add .

-Agregar commits
git commit -m "nombre del commit" (esto nos permitira ir agregando las versiones y que fuimos haciendo)

-Agregar cambios al repositorio remoto
git push origin master

git push (una vez ya enlazado los repositorios)

#Bajar archivos del Repositorio:
git clone url del repositorio (con esto creo una copia completa de los archivos del repositorio, esto se realiza una vez cuando los archivos no estan en la computadora)

git pull origin master (traer todos los cambios del repositorio en la nube al local)





