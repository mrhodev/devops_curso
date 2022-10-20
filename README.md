# devops_curso
Material, ejercicios y notas varias del curso de devops de enve

## Primer problema
Se quire obtener el repo de git por ssh
No se cuentan con las keys! asique a crear y agregar los certificados, los pasos en https://docs.github.com/es/authentication/connecting-to-github-with-ssh/about-ssh

## Creacion de vagrant file
se usa el comando vagrant init hashicorp/bionic64
luego se agregan algunas cosas, como el nombre de la vm y el nombre del host, el resto de deja por default. tambien se agrega un carpeta compartida para sync.

## gitIgnore
Se agrega el archivo de ignore para no que suba la carpeta de vagrant.
