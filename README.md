Creo el repositorio 'devjumpers' desde github.

--------------------------------------------------------------------------------------------------

Ctrl + alt + t ---> Desde mi PC (linux mint) abro el terminal.

--------------------------------------------------------------------------------------------------

ls ---> Muestro el listado de directorios.

Desktop    Downloads  Pictures  Repositories  Videos
Documents  Music      Public    Templates     Warpinator

--------------------------------------------------------------------------------------------------

cd Repositories/ ---> Cambio de directorio.

--------------------------------------------------------------------------------------------------

ls ---> Muestro el listado de directorios.

branches  CursoIngresoJS  nuevorepo  repositorio-devJump

--------------------------------------------------------------------------------------------------

git clone git@github.com:Vrodah/devjumpers.git ---> clono el repositorio (SSH).

--------------------------------------------------------------------------------------------------

cd devjumpers/ ---> Cambio de directorio.

--------------------------------------------------------------------------------------------------

touch README.md ---> Creo el archivo.

--------------------------------------------------------------------------------------------------

nano README.md ---> Abro el archivo con el editor 'nano' para hacer lo pedido en el ejercicio.

--------------------------------------------------------------------------------------------------

Ctrl + x ---> Salgo del editor habiendo guardado los cambios con 'Ctrl + O'.

--------------------------------------------------------------------------------------------------

git status ---> Veo los cambios realizados.

--------------------------------------------------------------------------------------------------

git add . / git commit -m  'mensaje'  / git push ---> Stageo los cambios realizados, realizo el 
commit y push inicial.

--------------------------------------------------------------------------------------------------

touch privado.txt / mkdir privada ---> Creo el archivo / Creo el directorio.

--------------------------------------------------------------------------------------------------

touch .gitignore / nano .gitignore ---> Creo el archivo / Edito el archivo y realizo los cambios
para que 'privado.txt- y 'privada' sean ignorados por git.

--------------------------------------------------------------------------------------------------

git status / git add . / git commit -m 'mensaje / git push

--------------------------------------------------------------------------------------------------

touch 1.txt ---> Creo el archivo.

--------------------------------------------------------------------------------------------------

git add . / git commit -m  'mensaje'

--------------------------------------------------------------------------------------------------

git branch v0.2 / git checkout v0.2 / git branch ---> Creo la nueva rama / Me posiciono sobre ella
/ verifico que ahora estoy en 'v0.2' y no en 'main'.

--------------------------------------------------------------------------------------------------

touch 1.txt / touch 2.txt ---> Creo los archivos.

--------------------------------------------------------------------------------------------------

git add . / git commit -m  'mensaje' / git checkout main / git status / git push

--------------------------------------------------------------------------------------------------

git branch --merged

* main

git branch --no-merged

  v0.2

--------------------------------------------------------------------------------------------------

git merge v0.2 ---> Mergea el branch v0.2 con el main

Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

--------------------------------------------------------------------------------------------------

nano 1.txt ---> Edito el archivo.

<<<<<<< HEAD
Hola
=======                  ---> Hola
Adios                         Adios   
>>>>>>> v0.2

--------------------------------------------------------------------------------------------------

git branch --merged

* main
  v0.2

git branch --no-merged
 
--------------------------------------------------------------------------------------------------


 


 
