#Configuracion
Conocer la version de github
  - git -v
  - git --version

comandos para configurar git por primera vez:

  - git config --global user.name "Your name"
  - git config --global user.email "Your email"

Comando para ver que usuario o correo esta configurado
  
  - git config --global user.name 
  - git config --global user.email
  - git config --list 

Comando para inicializar git en un directorio
  
  - git init

Comando para ver el estado de los archivos

  - git status

Comando para ver todas las versiones de mi proyecto

  - git log --oneline
  
  para ver mas detalles:
  - git log 

Pasos para crear una version de mi codigo

1.  Agregar cambios

  - git add . // agrega todo
  - git add *.js // agrega solo archivos que tengan esa extension
  - git add home.html // agrega solo un archivo

2. comprometer los archivos

  - git commit -m "Descripcion del commit"

Volver a una version anterior

  - git checkout "identificador del commit al que nos queremos devolver" //version en especifico
  - git checkout --. // atajo // version anterior
  - git checkout "master/main" //volver a la version segura o ultima version