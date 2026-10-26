- **Alumno:** Aarón Zaragoza García
- **Bloque:** Practica_02_Casa_Manual_Soporte
- **Fase / ejercicio:** Fase 0.2
- **Fecha de inicio:** 26/10/2026
- **Fecha de entrega:** 26/10/2026

---

## 🎯 Qué se pedía

Crear desde cero un manual de soporte informático usando Git y GitHub, guardar tres versiones del manual, consultar la primera versión y volver a `main`. Por último, completar y subir la bitácora con las respuestas y los enlaces de la entrega.

## ⌨️ Comandos y pasos importantes

- `git init`: inicializar el repositorio en `01_Proyecto`.
    
- `git status`: comprobar el estado de los archivos.
    
- `git diff`: ver cambios que todavía no se han preparado.
    
- `git add`: seleccionar los archivos para el siguiente commit.
    
- `git diff --cached`: revisar los cambios preparados.
    
- `git commit`: guardar una versión en el historial local.
    
- `git push`: subir los commits a GitHub.
    
- `git check-ignore -v`: comprobar qué regla ignora los clips.
    
- `git log --oneline`: consultar el historial.
    
- `git switch --detach`: consultar temporalmente la primera versión.
    
- `git switch main`: regresar a la versión actual.

## 🛠️ Qué he hecho

He creado una bóveda nueva en Obsidian y he separado el proyecto de la carpeta donde se guarda la grabación. Después, he inicializado Git en `01_Proyecto`, he conectado el repositorio con GitHub y he creado el manual inicial.

A continuación, he corregido el procedimiento de conexión, he añadido los procedimientos de impresora y sonido y una imagen de diagnóstico. He preparado los archivos por separado, he comprobado los cambios antes de cada commit y he subido las versiones a GitHub. Finalmente, he consultado el primer commit, he regresado a `main` y he completado la bitácora.
## 🚩 Qué me ha fallado y cómo lo he resuelto

No he tenido errores importantes, como mucho equivocarme al escribir un comando.

## 🤔 Respuestas a las preguntas
¿Por qué Git se inicializa solo en 01_Proyecto y la grabación queda fuera?

Porque así Git controla únicamente los archivos del proyecto y del manual. La grabación se guarda en `00_Grabaciones`, fuera del repositorio, para evitar subir un vídeo pesado e innecesario a GitHub.

¿Qué muestran status y diff antes de preparar la corrección del procedimiento? Cita la instrucción anterior y la nueva.

`git status` muestra que `sin-conexion.md` está modificado. `git diff` permite ver qué líneas han cambiado.

- Antes: «Abre el navegador y prueba la página interna».
    
- Después: «Comprueba visualmente que el cable de red está conectado».
    

El cable pasa a ser la primera comprobación y la prueba del navegador, la segunda.

¿Por qué un archivo nuevo aparece en status pero no en el diff de README.md?

Porque `git status` muestra los archivos nuevos sin seguimiento, mientras que `git diff -- README.md` solo muestra los cambios de `README.md`. Los archivos nuevos todavía no están preparados y no aparecen en ese diff.

¿Qué preparas con cada add y qué compruebas con diff --cached antes del commit?

En la primera versión preparo `.gitignore`, la bitácora, `README.md` y `sin-conexion.md`. En la segunda preparo únicamente `sin-conexion.md`. En la tercera preparo individualmente `impresora.md`, `sin-sonido.md`, `diagnostico.png` y el `README.md` modificado.

Con `git diff --cached` compruebo el contenido que voy a guardar y con `git status` verifico que solo estén preparados los archivos correspondientes a esa versión.

¿Qué demuestra check-ignore y qué comprobaste además para saber que los clips existen?

`git check-ignore -v` muestra qué regla de `.gitignore` excluye los archivos `revision-01.mp4` y `revision-02.mp4`. Además, compruebo en el gestor de archivos que ambos existen en el disco y los reproduzco para verificar que son vídeos reales.

¿Qué diferencias concretas observaste en el manual del primer commit y qué recuperaste al volver a main?


En el primer commit, el procedimiento de conexión empieza probando el navegador y después comprobando el cable. Tampoco aparecen los procedimientos de impresora y sonido, los enlaces añadidos ni la imagen de diagnóstico. Al volver a `main`, recupero la corrección del orden de comprobación, los tres enlaces del índice y la imagen.

¿Qué aporta un historial cuando dos técnicos necesitan conocer el procedimiento vigente?

Permite consultar las versiones anteriores, comparar los cambios y saber qué instrucciones se modificaron en cada entrega. Así, los técnicos pueden identificar la versión actual y entender cómo ha evolucionado el procedimiento.

¿Por qué commit y push son acciones diferentes y qué miraste en GitHub?

`commit` guarda una versión en el repositorio local, mientras que `push` envía los commits al repositorio remoto de GitHub. En GitHub compruebo que aparecen los archivos y las modificaciones de cada versión, que los enlaces y la imagen funcionan y que los vídeos ignorados no se han subido.

¿Qué pasos repetirías para corregir otra instrucción y cuáles se hicieron una sola vez?

Para corregir otra instrucción, modificaría el archivo, ejecutaría `git status` y `git diff`, prepararía el cambio con `git add`, revisaría `git diff --cached` y `git status`, y finalmente haría `git commit` y `git push`.

Solo se hicieron una vez por proyecto la inicialización con `git init`, la configuración de la rama `main` y la conexión del remoto con `git remote add origin`. La creación de la bóveda también se hizo una sola vez.
## 🔗 Enlaces



- **Vídeo de esta fase:** https://youtu.be/LVY8Sq1Ok9I
- **Playlist:** https://www.youtube.com/playlist?list=PLTMRumQf9dtE

## 💭 Dudas / a repasar



- [ ]  nada.