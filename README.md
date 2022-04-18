1. Estudia el estado del repositorio local: Todos los commits (hasta "mi imagen") y con tu directorio de trabajo limpio (sin ningún cambio por añadir al repositorio). Confirma que no estás en modo detached HEAD (el último commit debe reflejar HEAD -> master)
   
   ![Status](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2017.04.52.png)
2. Acepta esta tarea de GitHub. Crearás un repositorio remoto VACÍO. No tiene ni README.md. 
   
   ![AceptarTarea](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2017.15.53.png)
3. Fíjate en las sugerencias de GitHub. Como partes de un repositorio local ya creado, sigue las siguientes instrucciones que te sugiere GitHub... PERO RECUERDA que tu rama NO TIENE POR QUÉ ser la indicada
…or push an existing repository from the command line
git remote add origin 
git branch -M main
git push -u origin main

    ![AddRemote](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2017.51.46.png)
    ![BranchMaster](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2017.53.09.png)
        
    Para subir los commit al repositorio hemos tenido que hacernos un token
    ![Push](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2017.54.16.png)

    Ya aparecen los commits hechos en el repositorio

    ![Commits](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2018.03.21.png)


1. En local (no debes trabajar en el remoto) y siempre desde git Bash añade el fichero README.md con estas instrucciones y sus pantallazos.

    ![GitStatus](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2018.00.16.png)

    ![GitAdd](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2019.13.00.png)

    ![GitCommit](images/Captura%20de%20pantalla%202022-04-18%20a%20las%2019.17.15.png)

2. Sincroniza tus cambios con el repositorio remoto (git push)