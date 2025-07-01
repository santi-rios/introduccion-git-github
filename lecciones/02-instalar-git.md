Instalación de Git

Ahora necesitamos instalar las herramientas de Git en nuestra computadora. Utilizaremos CLI (interfaz de línea de comandos) para comunicarnos con GitHub.

**Instalación en diferentes sistemas operativos:**

*   **Para Ubuntu/Debian:**

    1.  Primero, actualiza tus paquetes:

    ```bash
    sudo apt update
    ```

    2.  A continuación, instala Git:

    ```bash
    sudo apt-get install git
    ```
*   **Para macOS:**

    Puedes instalar Git usando Homebrew:

    1.  Si no tienes Homebrew, instálalo desde la [página oficial](https://brew.sh/).

    2.  Luego, instala Git:

    ```bash
    brew install git
    ```

*   **Para Windows:**

    1.  Descarga el instalador de Git desde [git-scm.com](https://git-scm.com/download/windows).

    2.  Ejecuta el instalador y sigue las instrucciones.  Asegúrate de agregar Git a tu PATH durante la instalación.

**Verificación de la instalación:**

1.  Abre una terminal o símbolo del sistema.

2.  Verifica que Git se instaló correctamente:

```bash
git --version
```

Esto debería mostrar la versión de Git instalada.

**Configuración de Git:**

1.  Ejecuta los siguientes comandos con tu información para establecer un nombre de usuario y un correo electrónico predeterminados para cuando vayas a guardar tu trabajo.  Reemplaza `"MV Thanoshan"` con tu nombre y `"example@mail.com"` con tu correo electrónico.

```bash
git config --global user.name "MV Thanoshan"
git config --global user.email "example@mail.com"
```

**Crear una cuenta en GitHub:**

1.  Ve a [github.com](https://github.com/) en tu navegador web.

2.  Haz clic en el botón "Sign up" o "Regístrate".

3.  Sigue las instrucciones para crear una cuenta. Necesitarás proporcionar una dirección de correo electrónico, un nombre de usuario y una contraseña.

**Conectar Git con tu cuenta de GitHub:**

1.  **Generar una clave SSH (opcional, pero recomendado):**

    Las claves SSH te permiten conectarte a GitHub sin tener que ingresar tu nombre de usuario y contraseña cada vez.

    *   Abre tu terminal o Git Bash.

    *   Genera una nueva clave SSH usando el siguiente comando (reemplaza `your_email@example.com` con tu dirección de correo electrónico):

    ```bash
    ssh-keygen -t ed25519 -C "your_email@example.com"
    ```

    *   Cuando se te solicite, elige una ubicación para guardar la clave (la ubicación predeterminada suele ser `.ssh/id_ed25519`) y, opcionalmente, establece una contraseña.

    *   Inicia el agente SSH en segundo plano

    ```bash
    eval "$(ssh-agent -s)"
    ```

    *   Agrega tu clave SSH al agente SSH

    ```bash
    ssh-add ~/.ssh/id_ed25519
    ```

    *   Copia la clave SSH pública al portapapeles.  Puedes usar el siguiente comando (esto puede variar según tu sistema operativo):

    ```bash
    cat ~/.ssh/id_ed25519.pub
    ```

2.  **Agregar la clave SSH a tu cuenta de GitHub:**

    *   En GitHub, haz clic en tu foto de perfil en la esquina superior derecha y selecciona "Settings" (Configuración).

    *   En la barra lateral izquierda, haz clic en "SSH and GPG keys".

    *   Haz clic en el botón "New SSH key" o "Add SSH key".

    *   En el campo "Title", ingresa un nombre descriptivo para tu clave (por ejemplo, "Mi computadora portátil").

    *   Pega la clave SSH pública que copiaste en el campo "Key".

    *   Haz clic en el botón "Add SSH key".

3.  **Probar la conexión SSH (opcional):**

    ```bash
    ssh -T git@github.com
    ```

    Si todo está configurado correctamente, verás un mensaje que dice algo como:

    ```
    Hi username! You've successfully authenticated, but GitHub does not provide shell access.
    ```

Ahora estás listo para comenzar a trabajar con repositorios de GitHub.


## Configurar nombre y email con git config.