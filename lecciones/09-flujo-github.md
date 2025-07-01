Flujo de GitHub

Sigue el flujo de GitHub para colaborar en los proyectos.
En este artículo

    Introducción
    Prerrequisitos
    Seguir el flujo de GitHub

Introducción

El flujo de GitHub es un flujo de trabajo ligero basado en ramas. El flujo de GitHub es útil para todos, no solo para los desarrolladores. Por ejemplo, en GitHub, se usa el flujo de GitHub para la directiva del sitio, la documentación y la hoja de ruta.
Prerrequisitos

Para seguir el flujo de GitHub, necesitarás una cuenta de GitHub y un repositorio. Para obtener información sobre cómo crear una cuenta, consulta Creación de una cuenta en GitHub. Para obtener información sobre cómo crear un repositorio, consulta Inicio rápido para repositorios. Para obtener información sobre cómo buscar un repositorio existente al que contribuir, consulta Encontrar maneras para colaborar con el código abierto en GitHub.
Seguir el flujo de GitHub

Sugerencia

Puedes completar todos los pasos del flujo de GitHub desde la interfaz web de GitHub, la línea de comandos y GitHub CLI o GitHub Desktop. Para obtener más información sobre las herramientas que puedes usar para conectarte a GitHub, consulta Conexión a GitHub.
Crear una rama

Crear una rama en tu repositorio. Un nombre de rama corto y descriptivo permite que tus colaboradores vean el trabajo contínuo de un vistazo. Por ejemplo, increase-test-timeout o add-code-of-conduct. Para más información, consulta Crear y eliminar ramas en tu repositorio.

Si creas una rama, creas un espacio para trabajar sin afectar a la rama predeterminada. Adicionalmente, otorgas a los colaboradores una oportunidad de revisar tu trabajo.
Realización de cambios

En tu rama, haz cualquier cambio que quieras en el repositorio. Para más información, consulta Crear nuevos archivos, Editar archivos, cambiar el nombre de un archivo, Mover un archivo a otra ubicación o Borrar los archivos en un repositorio.

Tu rama es un lugar seguro para hacer cambios. Si cometes un error, peudes revertir tus cambios o subir cambios adicionales para arreglar el error. Tus cambios no terminrán en la rama predeterminada hasta que fusiones tu rama.

Confirmar y subir tus cambios a tu rama. Dale un mensaje descriptivo a cada confirmación para ayudarte a ti mismo y a tus contribuyentes futuros a entender qué cambios contienen dichas confirmaciones. Por ejemplo, fix typo o increase rate limit.

Idealmente, cada confirmación contiene un cambio completo y aislado. Esto facilita que reviertas tus cambios si decides adoptar otro enfoque. Por ejemplo, si quieres renombrar una variable y agregar algunas pruebas, pon el nuevo nombre de la variable en una confirmación y las pruebas en otra. Posteriormente, si quieres mantener las pruebas pero quieres revertir el renombramiento de variable, puedes revertir la confirmación específica que contenía dicho renombramiento. Si pones el renombre de variable y las pruebas en la misma confirmación o si propagas el renombre de variable a través de varias confirmaciones, harías más esfuerzo en revertir tus cambios.

Si confirmas y subes tus cambios, respaldas tu trabajo en un almacenamiento remoto. Esto significa que puedes acceder a tu trabajo desde cualquier dispositivo. Esto también significa que tus colaboradores pueden ver tu trabajo, responder tus preguntas y hacer sugerencias o contribuciones.

Sigue haciando, confirmando y subiendo cambios a tu rama hasta que estés listo para solicitar retroalimentación.

Sugerencia

Crea una rama distinta para cada conjunto de cambios no relacionados. Esto facilita a los revisores dar retroalimentación. También te facilita tanto a ti mismo como alos colaboradores futuros entender los cambios y revertir o compilar sobre ellos. Adicionalmente, si hay un retraso en un conjunto de cambios, tus otros cambios tampoco se retrasarán.
Creación de una solicitud de incorporación de cambios

Crea una solicitud de cambios para pedir a los colaboradores retroalimentación sobre ellos. La revisión de solicitude sde cambios es tan valiosa que algunos repositorios requieren una revisión aprobatoria antes de que estas se puedan fusionar. Si quieres tener retroalimentación o consejos tempranos antes de que completes tus cambios, peudes marcar tu solicitud de cambios como borrador. Para más información, consulta Crear una solicitud de incorporación de cambios.

Cuando creas una solicitud de cambios, incluye un resumen de estos, así como la explicación del problema que solucionan. Puedes incluir imágenes, enlaces y tablas para ayudar a transmitir esta información. Si tu solicitud de cambios aborda un problema, vincula la propuesta para que los interesados en ella estén conscientes de la solicitud de cambios y viceversa. Si la enlazas con una palabra clave, la propuesta se cerrará automáticamente cuando se fusione la solicitud de cambios. Para más información, consulta Sintaxis de escritura y formato básicos y Vincular una solicitud de cambios a una propuesta.

Adicionalmente a llenar el cuerpo de la solicitud de cambios, puedes agregar comentarios a las líneas específicas de la solicitud de cambios para señalar algo explícitamente para los revisores.

Tu repositorio podría estar configurado para solicitar una revisión de usuarios o equipos específicos automáticamente cuando se crea una solicitud de cambios. También puede @mention manualmente o solicitar una revisión de personas o equipos específicos.

Si tu repositorio tiene verificaciones configuradas para que se ejecuten en las solicitudes de cambios, verás cualquier verificación que falló en tu solicitud de cambios. Esto te ayuda a detectar errores antes de fusionar tu rama. Para más información, consulta Acerca de las verificaciones de estado.
Abordar comentarios de revisión

Los revisores deben dejar preguntas, comentarios y sugerencias. Los revisores pueden comentar toda la solicitud de cambios, o bien agregar comentarios a líneas o archivos específicos. Tanto tú como los revisores pueden insertar imágenes o sugerencias de código para clarificar los comentarios. Para más información, consulta Revisión de cambios en las solicitudes de incorporación de cambios.

Puedes seguir confirmando y subiendo cambios como respuesta a las revisiones. Tu solicitud de extracción se actualizará de manera automática.
Fusiona tu solicitud de cambios

Una vez que se apruebe tu solicitud de cambios, fusiónala. Esto fusionará tu rama automáticamente para que tus cambios aparezcan en la rama predeterminada. GitHub retiene el historial de comentarios y confirmaciones en la solicitud de cambios para ayudar a los contribuyentes futuros a entender tus cambios. Para más información, consulta Combinación de una solicitud de incorporación de cambios.

GitHub te dirá si tu solicitud de cambios tiene conflictos que se deban resolver antes de fusionarse. Para más información, consulta Cómo abordar los conflictos de combinación.

La configuación de protección de rama podría bloquear la fusión si tu solicitud de cambios no cumple con algunos de los requisitos. Por ejemplo, necesitas cierto número de revisiones de aprobación o una revisión de aprobación de algún equipo específico. Para más información, consulta Acerca de las ramas protegidas.
Borra tu rama

Después de que fusiones tu solicitud de cambios, borra tu rama. Esto indica que se ha completado el trabajo en la rama y te previene tanto a tí como a otras personas de que utilices ramas antiguas por acidente. Para más información, consulta Eliminar y restaurar ramas en una solicitud de extracción.

No te preocupes por perder la información. No se borrará tu solicitud de cambios ni tu historial de confirmación. Siempre puedes restablecer la rama que borraste o revertir tu solicitud de cambios en caso de que lo necesites.