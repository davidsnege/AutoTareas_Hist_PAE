# Auto_Tareas_Historial_PAE
- Personal automation to work tasks.

- Stack a utilizar.
- - PHP JS HTML CSS JSON

```
Todo Backend será contruido con PHP y las informaciones serán grabadas en un JSON para cada Tarea dentro de su respectiva carpeta en el formato "/tareas/2024/03/02/nombre_de_la_tarea.json" donde la información estará organizada por categorias.
El front debera fornecer la capacidade de exhibir, interactuar, llamar los cambios al Backend en PHP, el PHP será el responsable por grabar y cambiar las informaciones dentro del JSON para cada tarea.

```

- - El objectivo no es solo automatizar la creación del PAE al final, pero también crear una herramienta para mantener las tareas organizadas y con un historial accesible en futuras consultas de que se ha cambiado y por que motivo, posibilitando que nosotros recuperemos informaciones importantes que necesitamos cambiar en algun momento y poder hacer un debug de nuevos cambios si necesário basandonos en lo que ya hemos hecho.

- - Es un server local para ser ejecutado en cada uno, solo para uso personal de los colegas de trabajo.

## Historial de Tareas.

- Tipo de Tarea. (Flujos o MPA).
- OB o ES o OB/ES.

### Rama de Tarea.

- Rama dentro de Orchestation Studio de la tarea.

### CPs/Flujos usados cambiados o creados en la Tarea.

- CPs cambiados o creados.
- - Flujos de los CPs cambiados o creados.
- - - Cambios hechos:
```
Que cambiamos, donde y por quê?
```

### Datos de ejecución, ficheros, inputs, etc.

- Se debe guardar las informaciones para futuras ejecuciones.
- - Ficheros Json (Serán añadidos a la carpeta como archivos, y se podra leer).
- - Inputs de flujos (Serán incluidos los utilzados en el testeo).
- - Otros datos de ejecución (texto plano para describir una o otra cosa particular).
- - Ejecuciones en WEB "link" + resultado (Success/Error).

### Ficheros usados cambiados o creados en la Tarea.

- Rutas y loc de ficheros (RAS, LOCAL, ETC).
- - Nombres de ficheros.
- - - Cambios realizados para documentación/historial.

### Commits.

- Commits de Studio.
- Commits de Fichero de Configuración.
- Commits de Content Packs.

### Texto PAE (Generado/Modificado)

- Se debe generar un texto de PAE automatico con los datos extraidos del historial.
- Se debe poder cambiar elementos dentro del PAE para casos concretos o añadir información.
- Se debe poder añadir el INC del PAE en el texto.
- Se debe generar un modelo de mensage para envio en Telegram pedindo el PAE.