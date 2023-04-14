# 2023-Actividad-1
Sistemas de Versionado sobre Git y Github

Fabricio Quevedo 
fabque@gmail.com


Configuration on pc Git Configuration As you read briefly in Getting Started, you can specify Git configuration settings with the git config command. One of the first things you did was set up your name and email address:

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
Create a new repository on the command line

```
git init
git add README.md
git commit -m "first commit"
git remote add origin *url-del-repo*
git push -u origin master
```
…or push an existing repository from the command line

```
git remote add origin *url-del-repo*
git push -u origin master
```
Git Basic Commands Página de soporte de Git con ayuda https://git-scm.com/docs/ https://git-scm.com/docs/gittutorial Más info sobre commandos básicos en Attlasian https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html

Acerca de fork y pull request ver enlace http://aprendegit.com/que-es-un-pull-request/

## Actividad 1 Comandos Básicos 
- a) Configurar usuario de git local (ver git config)  
- b) Una vez configurado el usuario. Crear un nuevo repositorio local con git realizar un commit (comandos a usar init, status, add (stage area nos permite incluir solo los archivos que queremos subir al commit dejando para otro commit los archivos que realizan otra funcion por ejemplo que forman parte de otra funcionalidad), commit).  
- c) Vincular el repositorio local con un repositorio remoto en github (comando remote). Para ello primero debemos crear el repositorio en por ejemplo una cuenta de github propia.   
- d) Clonar el repositorio de github remoto a un nuevo directorio en la maquina local (git clone)  
- e) Realizar un cambio en el repositorio anteriormente clonado y realizar un commit y subir el cambio al repositorio remoto (comandos commit y push, siempre es recomendable cuando se trabaja en equipo realiza un fetch para verificar si se produjeron cambios en el repositorio remoto, luego dichos cambios se traen al repo local con el comando pull) 
## Actividad 2 Branching, pull request y fork 
- a) Crear una rama nueva rama realizar un cambio y subir la nueva rama al servidor remoto (git branch, checkout rama).  
- b) Mergear cambios es decir llevar los cambios de la rama creada a la rama base. Una vez que se hizo commits en los cambios de la rama nos cambiamos de rama (checkout branch_name) y allí podemos traer los cambios de la rama modificada a la rama base (git merge rama_modificada)   
- c) Realizar un pull request del cambio (esto se realiza en git cuando se realizar un push, git nos va a sugerir realizar un pull request para llevar los cambios de la rama creada con cambios a la rama de la cual partió el cambio, por ejemplo, si nuestra rama base es master y creamos una nueva Ramita a partir de ella realizamos cambios y subimos la misma al repo remoto, el pull request que nos sugerirá github es hacerlo de la Ramita a master.   
- f) Tomando como base el repo XXXXXX(por ejemplo un repo de compañero) realizar un fork (esto en github que es llevar la copia de un repositorio de un tercero al propio realizar cambios y luego contribuir con ese repositorio realizando un pull request (ver link http://aprendegit.com/que-es-un-pull-request/) este pull request necesita de la autorización de quien tiene permisos para realizar cambios en ese repositorio. Una vez realizado el fork, clonamos el repo a nuestra maquina local realizamos cambios, subimos los cambios a github y una vez ahi probamos realizar el pull request  
- Hacer un cherry pick de otro commit

cambio



cambio hecho en clase
