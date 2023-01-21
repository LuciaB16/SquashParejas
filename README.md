# SquashParejas

## COMANDOS UTILIZADOS EN ESTA TAREA
Para realizar este ejercicio (mi rol fue de líder), usé la interfaz y por lo tanto no utilicé ningún comando, y los pasos que seguí fueron los siguientes:

En la barra de herramientas, le doy al botón VCS y create git repository.
Una vez hecho, aparece a la izquierda una pestaña para hacer los commits y la abro.
En la Main, hago los dos primeros commits (azules), me sitúo en la ventana, le pongo nombre primer al commit y selecciono la clase Main que es la que he modificado, 
y le doy al botón commit.
Hago lo mismo para el segundo commit.
Cuando tengo que crear la nueva rama (en este caso la rama líder), le doy al botón inferior que pone master, y le doy a new branch y le pongo el nombre líder.
Sobre el src le doy al botón derecho y creo una clase llamada Líder, donde haré los siguientes tres commits, y estoy en la rama líder, ya que me cambié pulsando 
sobre checkout.
Hago los commits correspondientes, manteniéndome en la rama líder.
Una vez hecho esto, hago un pull (flecha azul en la esquina superior derecha) para así actualizar los cambios que hizo el colaborador y poder hacer el merge.
Finalmente voy a la pestaña de Git, le doy a Merge y selecciono la rama que quiero traer a la Main, en este caso primero se hace merge con la rama colaborador según el
esquema.
Le doy a la opción de --squash.
Repito el proceso. Voy a la pestaña de Git, le doy a Merge y selecciono la rama que quiero traer a la Main, en este caso ahora se hace merge con la rama de líder.
Le doy a la opción de --squash.
Hago push dándole a la flecha verde situada en la esquina superior derecha.

En el caso de que se usaran comandos en la consola, serían los siguientes:

Git init
Git add src
Hago el commit en la main con git commit -m " "
Sigo haciendo los commits necesarios.
Creo una nueva rama: git branch líder
Me cambio a la rama exp: git checkout líder
Compruebo en que rama estoy: git branch
Creo la nueva clase Líder.
Sigo haciendo los commits como anteriormente.
Le doy a la flecha azul en la esquina superior derecha (ya que en consola me da errores) y así actualizo el repositorio local.
Una vez que acabo, hago el merge dándole al botón git, luego merge y seleccionando la rama con la que quiero hacer merge (en este caso colaborador), 
y seleccionando la opción --squash.
Hago lo mismo con la rama líder.
Creo el Readme.md con el comando echo>>Readme.md y escribo en él los comandos usados.
Hago push con el comando git push -u origin main.
