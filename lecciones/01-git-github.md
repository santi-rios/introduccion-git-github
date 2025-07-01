## Qué es Git?

Git es un software de control de versiones gratis y de código abierto. Fue creado por Linus Torvalds en 2005. Esta herramienta es un sistema de control de versiones que fue inicialmente desarrollado para trabajar con varios desarrolladores en el núcleo de Linux.

Esto significa básicamente que Git es un rastreador de contenido. Así que Git puede ser utilizado para almacenar contenido — y se usa principalmente para almacenar código debido a otras características que proporciona.

Los proyectos de la vida real generalmente tienen múltiples desarrolladores trabajando en paralelo. Así que necesitan un sistema de control de versiones como Git para asegurarse de que no hay conflictos de código entre ellos.

Además, los requerimientos en este tipo de proyectos cambian constantemente. Así que un sistema de control de versiones permite a los desarrolladores revertir y regresar a una versión anterior de su código.

El sistema de ramas en Git permite a los desarrolladores trabajar individualmente en una tarea (Por ejemplo: una rama -> una tarea O una Rama -> un desarrollador). Básicamente, se puede pensar en Git como una aplicación de software pequeña que controla tu código base, si eres un desarrollador.

![](https://www.freecodecamp.org/news/content/images/2019/11/vcs.png)

# Introducción a GitHub

GitHub es utilizado por personas de todo el mundo para construir algunas de las tecnologías más avanzadas. Ya sea que estés visualizando datos o creando un nuevo juego, hay una comunidad completa y un conjunto de herramientas en GitHub que pueden ayudarte a hacerlo aún mejor. El ejercicio "Introducción a GitHub"te guía a través de todo lo que necesitas para comenzar en menos de una hora.

*   **¿Para quién es esto?**: Nuevos desarrolladores, nuevos usuarios de GitHub y estudiantes.
*   **¿Qué aprenderás?**: Introduciremos los repositorios, las ramas, los commits y las pull requests.
*   **¿Qué construirás?**: Crearemos un archivo Markdown corto que puedes usar como tu README de perfil.
*   **Prerrequisitos**: Ninguno. Este ejercicio es una excelente introducción para tu primer día en GitHub.
*   **¿Cuánto tiempo?**: Este ejercicio toma menos de una hora en completarse.

En este ejercicio, podrás:

*   Crear una rama
*   Hacer un commit de un archivo
*   Abrir una pull request
*   Fusionar tu pull request

Los desarrolladores utilizan "issues" (incidencias) para organizar su trabajo y colaborar. ¡Nosotros haremos lo mismo! Esa es otra lección, pero hoy, te introduciremos a los conceptos básicos.

## ¿Qué es GitHub?

GitHub es una plataforma de colaboración que utiliza Git para el control de versiones. Git es un programa de código abierto para rastrear cambios en archivos de texto. Fue escrito por el autor del sistema operativo Linux, y es la tecnología central sobre la que se construye GitHub, la interfaz social y de usuario.

GitHub es un lugar popular para compartir y contribuir al software de código abierto.

[https://www.youtube.com/watch?v=pBy1zgt0XPc](https://www.youtube.com/watch?v=pBy1zgt0XPc)

## ¿Qué es un repositorio?

Un repositorio es un proyecto que contiene archivos y carpetas. Un repositorio rastrea las versiones de archivos y carpetas. Para obtener más información, consulta "Acerca de los repositorios" en la documentación de GitHub.

## ¿Qué es una rama?

Una rama es una versión paralela de tu repositorio. De forma predeterminada, tu repositorio tiene una rama llamada "main" y se considera la rama definitiva. Crear ramas adicionales te permite copiar la rama principal de tu repositorio y realizar cambios de forma segura sin interrumpir el proyecto principal. Mucha gente usa ramas para trabajar en características específicas sin afectar otras partes del proyecto.

## ¿Qué es un perfil README?

Un README de perfil es esencialmente una sección "Acerca de mí" en tu perfil de GitHub donde puedes compartir información sobre ti mismo con la comunidad en GitHub.com. GitHub muestra tu README de perfil en la parte superior de tu página de perfil.

## Profundizando en Git

Git es un sistema de control de versiones distribuido, lo que significa que cada desarrollador tiene una copia completa del historial del repositorio. Esto permite trabajar sin conexión y facilita la colaboración.

### Comandos básicos de Git:

*   `git init`: Inicializa un nuevo repositorio Git en un directorio.
*   `git clone <url>`: Clona un repositorio existente desde una URL.
*   `git add <archivo>`: Agrega un archivo al área de preparación (staging area).
*   `git commit -m "Mensaje"`: Guarda los cambios en el repositorio con un mensaje descriptivo.
*   `git push`: Envía los commits a un repositorio remoto.
*   `git pull`: Descarga los cambios desde un repositorio remoto.
*   `git branch`: Lista, crea o elimina ramas.
*   `git checkout <rama>`: Cambia a una rama específica.
*   `git merge <rama>`: Fusiona una rama en la rama actual.

### Flujo de trabajo típico con Git y GitHub:

1.  **Clonar el repositorio:** `git clone <url>`
2.  **Crear una rama para tu trabajo:** `git branch <nombre-de-la-rama>` y `git checkout <nombre-de-la-rama>`
3.  **Realizar cambios y agregarlos al área de preparación:** `git add .` (para agregar todos los cambios)
4.  **Hacer commit de los cambios:** `git commit -m "Descripción de los cambios"`
5.  **Subir la rama al repositorio remoto:** `git push origin <nombre-de-la-rama>`
6.  **Crear una Pull Request:** En GitHub, desde tu rama a la rama principal (main).
7.  **Revisar y fusionar la Pull Request:** Otros colaboradores revisan tu código y, si todo está bien, se fusiona a la rama principal.

## Recursos adicionales

*   **Documentación oficial de Git:** [https://git-scm.com/doc](https://git-scm.com/doc)
*   **Documentación de GitHub:** [https://docs.github.com/](https://docs.github.com/)
*   **GitHub Learning Lab:** [https://lab.github.com/](https://lab.github.com/) (Cursos interactivos)

Espero que esta lección ampliada te sea útil. ¡No dudes en preguntar si tienes más dudas!