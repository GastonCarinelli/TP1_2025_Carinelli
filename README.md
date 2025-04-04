# TP1_2025_Carinelli
Gaston Carinelli
gastoncarinelli99@gmail.com
19257
Bruno Palacios
palaciosbruno@hotmail.com
12345

Responda entre líneas a cada una de las siguientes preguntas:

¿Qué ocurrió durante el merge?
Git detectó que ambas ramas modificaron el mismo bloque del archivo README, lo que generó un conflicto.

¿Por qué ocurrió?
Porque tanto el alumno como el JTP editaron la misma sección del archivo, y Git no pudo decidir automáticamente cuál versión conservar.

¿Cómo lo soluciono?
Editando manualmente el archivo para dejar el contenido final deseado, eliminando las marcas de conflicto y conservando lo deseado.

¿Qué significa lo indicado como: 
<<<<<<< HEAD 
=========== 
>>>>>>> Rama Actual?
Son marcas que coloca Git para mostrar las diferencias entre lo que hay en la rama actual HEAD y la rama que estás intentando fusionar. Te ayudan a resolver manualmente los conflictos.
