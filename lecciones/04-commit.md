Crear una rama te permite editar tu proyecto sin modificar la rama principal. Ahora que tienes una rama, ¡es hora de crear un archivo y hacer tu primer commit!

¿Qué es un commit?: Un commit es un conjunto de cambios a los archivos y carpetas en tu proyecto. Un commit existe en una rama. Para más información, consulta "Acerca de los commits".

⌨️ Actividad: Tu primer commit

Los siguientes pasos te guiarán a través del proceso de hacer un commit en GitHub. Un commit registra cambios al proyecto, como agregar/eliminar/renombrar archivos y modificar el contenido de los archivos. Para este ejercicio, hacer un commit será agregar un nuevo archivo a tu nueva rama.

Nota:

`.md` es una extensión de archivo que crea un archivo Markdown. Puedes aprender más sobre Markdown visitando "Sintaxis básica de escritura y formato" en nuestra documentación o realizando el ejercicio de habilidades "Comunicación usando Markdown".

1.  En la pestaña `<> Código` en el menú del encabezado de tu repositorio, asegúrate de estar en tu nueva rama `mi-primera-rama`.
2.  Selecciona el menú desplegable `Agregar archivo` y haz clic en `Crear nuevo archivo`.
3.  En el campo de nombre, escribe `PROFILE.md`. Esto creará un nuevo archivo llamado `PROFILE.md`.
4.  En el editor de archivos, agrega la siguiente información:

```markdown
# Mi Perfil

¡Hola! Soy [Tu Nombre] y estoy aprendiendo a usar GitHub.
```

5.  Haz clic en `Commit changes...` en la esquina superior derecha, arriba del cuadro de contenido. Aparecerá un diálogo.
6.  GitHub ofrece un mensaje predeterminado simple, pero cambiémoslo ligeramente para practicar. Escribe `Agregar PROFILE.md` en el campo `Commit message`.

    *   Un mensaje de commit y una descripción extendida opcional ayudan a brindar claridad para tus cambios. Esto es particularmente útil cuando tu commit involucra varios archivos.  Intenta ser conciso pero descriptivo en tus mensajes de commit.

7.  En esta lección, ignoraremos los otros campos por ahora y haremos clic en `Commit changes`.

¡Felicidades! Has realizado tu primer commit.

Ahora que has cambiado un archivo, Mona ya debería estar ocupada revisando tu trabajo. Dale un momento y observa los comentarios. Verás que ella responde con información del progreso y la siguiente lección.

**Información Adicional sobre Commits:**

*   **Buenas prácticas para mensajes de commit:**  Escribe mensajes de commit claros y concisos.  Comienza con un resumen en la primera línea (máximo 50 caracteres), seguido de una línea en blanco y luego una descripción más detallada si es necesario.  Usa un lenguaje imperativo (por ejemplo, "Agregar característica" en lugar de "Se agregó característica").
*   **Commits atómicos:** Intenta hacer commits pequeños y enfocados que representen un solo cambio lógico.  Esto facilita la revisión y la reversión de cambios si es necesario.
*   **Revertir commits:** Si cometes un error, puedes revertir un commit para deshacer los cambios que introdujo.  GitHub proporciona herramientas para facilitar este proceso.


------

Nuevo: Explicar el ciclo: directorio de trabajo, área de preparación (staging) y repositorio.
Nuevo: Usar git status para ver el estado de los archivos.
Nuevo: Añadir archivos al staging area con git add.
Hacer commit de los cambios.
Nuevo: Revisar el historial con git log.
