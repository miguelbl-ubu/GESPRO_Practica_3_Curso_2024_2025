Autores:
  Diego Arbeloa
  Diego Guerrero

Preguntas
1) Url del proyecto
  https://github.com/GesProDiego2024-25/GESPRO_Practica_3_Curso_2024_2025

2)
 - Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local. (25%)
    * posicionarte en el commit para subir cambios
    * tener master al dia y estar posicionado en master
    * Crear rama a partir de tarea con nombre = a Gobees
    en github nos situamos en Issues, pulsamos sobre el Issue que vamos a crear la rama y creamos la rama con el nombre del Issue.
    * posicionarse en rama en local
    --> foto 1
    Una vez creada la rama en el github, hacemos fetch en gitkraken para ver la rama, nos aparecerá en el cuadro de "remote",
    tendremos que pulsar dos veces sobre esa rama y nos aparecerá en el cuadro de local, ahí es cuando tendremos la rama en el
    repositorio local y podremos subir los cambios.

    * Añadir cambios de carpeta gobees a la carpeta P3

    * Git Stage all * Git commit
    --> foto 2
    Cuando guardemos los cambios en algún fichero del proyecto en atom, dicho fichero aparecerá	sobresaltado en naranja, esto querrá decir
    que no se ha sincronizado con el repositorio local, para ellos vamos a gitkraken y hacemos fetch para comprobar si ha habido cambios.
    Nos saldrá a la derecha que ha habido cambios entonces añadimos los cambios y hacemos el commit.
    * Create PRQ (de nuestro proyecto a nuestro proyecto) master
    Cuando ya tienes todos los commits de la rama hechos, subes todos los cambios de tu rama a github y alli creas la pull request para sincronizar tu rama con la rama master, estonces la pull request necesita la aprovacion de otras personas,y se debe de confirmar por al menos un miembro.
    * Merge PRQ y actualizar Master en local
    Una vez creada la pull request, otro miembro del equipo la confirmara, por lo que se sincronizara automaticamente la rama creada y la rama master. Para actualizar la master en local primero se hace un fetch, y luego pulsas pull para traer los cambios del repositorio remoto al local.
    IMPORTANTE: Cuando hagas el pull para sincronizar ambas ramas master(local y remoto) en gitkraken tienes que tener la rama master seleccionada.
