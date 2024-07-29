<div>
<img src="https://i.ibb.co/v3CvVz9/udd-short.png" width="150"/>
    <br>
    <strong>Universidad del Desarrollo</strong><br>
    <em>Magíster en Data Science</em><br>
    <em>Profesor: Víctor Navarro Aránguiz</em><br>
    <em>Autor: Giuseppe Lavarello</em><br>
</div>

# Python para Data Science: Repaso grupal 

**Fecha de creación**: 28 de Julio de 2024

# Objetivos:
- Repasar el uso de Git y la creación de repositorios vistos en clase.



## Creacion de un repositorio
Existen varias formas de crear repositorios para github, y en la ultima clase vimos todo de manera muy rapida, aqui tratare de explicarlas en mas detalle.  

**IMPORTANTE** Solo necesitan saber 1, el resto es opcional  

### Prerequisitos: Instalar Git. 

Instalación de Git en Windows

#### Paso 1: Descargar Git
- Visita el sitio web oficial de Git: [git-scm.com](https://git-scm.com).
- Haz clic en "Download" y selecciona la versión adecuada a tu pc de Git para Windows.

#### Paso 2: Ejecutar el instalador
- Una vez descargado, ejecuta el archivo `.exe` para iniciar el proceso de instalación.

#### Paso 3: Configurar la instalación 
- **Para mas detalle visita**: [Como Instalar git ](https://phoenixnap.com/kb/how-to-install-git-windows) en Ingles pero tiene fotos.
- **Aceptar el acuerdo de licencia**: Haz clic en "Next" para aceptar el acuerdo de licencia.
- **Elegir la carpeta de instalación**: Puedes dejar la ubicación predeterminada y hacer clic en "Next".
- **Seleccionar los componentes**: Deja las opciones predeterminadas seleccionadas, que incluyen Git Bash y Git GUI, y haz clic en "Next".
- **Configurar el editor predeterminado**: Selecciona tu editor preferido (puede ser Vim, Visual Studio Code, Atom, etc.) y haz clic en "Next".
- **Ajustar las variables de entorno PATH**: Selecciona "Git from the command line and also from 3rd-party software" y haz clic en "Next".
- **Seleccionar el método de transporte HTTPS**: Deja la opción predeterminada "Use the OpenSSL library" y haz clic en "Next".
- **Configurar el formato de final de línea**: Selecciona "Checkout Windows-style, commit Unix-style line endings" y haz clic en "Next".
- **Seleccionar la opción para la terminal de Git**: Deja la opción predeterminada "Use MinTTY (the default terminal of MSYS2)" y haz clic en "Next".
- **Configuraciones adicionales**: Puedes dejar las opciones predeterminadas y hacer clic en "Next".

#### Paso 4: Completar la instalación
- Haz clic en "Install" para completar la instalación de Git.  

# Cómo Crear un Repositorio desde GitHub

### Paso 1: Crear una Cuenta en GitHub
1. Visita [github.com](https://github.com).
2. Si no tienes una cuenta, regístrate proporcionando un nombre de usuario, correo electrónico y contraseña.

### Paso 2: Iniciar Sesión en GitHub
1. Inicia sesión con tu nombre de usuario y contraseña.

### Paso 3: Crear un Nuevo Repositorio
1. En la esquina superior derecha, haz clic en el icono "+" y selecciona **New repository**.  
![nuevo repositorio](/Imagenes/nuevo_repositorio.jpg)

### Paso 4: Configurar el Nuevo Repositorio
1. **Nombre del repositorio**: Introduce un nombre único.
2. **Descripción** (opcional): Proporciona una descripción sobre el propósito del repositorio.
3. **Privacidad**:
   - Selecciona **Public** si quieres que el repositorio sea visible para todos.
   - Selecciona **Private** si quieres que el repositorio sea visible solo para ti y las personas que invites.
4. **Inicializar el repositorio con un README** (opcional): Marca esta opción si deseas añadir un archivo README.md inicial.
5. **Añadir un .gitignore**: Elige el lenguaje con el que trabajarás, en nuestro caso Python.
6. **Elegir una licencia**: Si quieres cubrir tu código bajo los términos de uso de alguna licencia en particular.
7. Haz clic en **Create repository** para finalizar.  
![crear_repo_github](/Imagenes/crear_repo_github.jpg)

### Paso 5: Clonar el Repositorio
1. Abre tu shell de preferencia (PowerShell, Git Bash, Anaconda Prompt, etc.) en la carpeta donde deseas guardar el repositorio.
   - Navega a la carpeta deseada en el explorador de archivos.
   - Haz clic en la barra de direcciones de la carpeta 

   ![abrir shell 01](/Imagenes/abrir_shell_01.jpg)
   - Escribe el shell que prefieras. Yo usaré PowerShell, ya que viene con Windows y todos deberían tener acceso a él.

   ![abrir shell 02](/Imagenes/abrir_shell_02.jpg)
   
3. Ejecuta el siguiente comando, donde `$URL_DEL_REPOSITORIO` es la URL del repositorio que creaste:
   ```sh
   git clone $URL_DEL_REPOSITORIO
   ```  
 ![abrir shell 03](/Imagenes/abrir_shell_03.jpg)

4. Al finalizar, los archivos que estaban en GitHub quedarán copiados en tu disco para un acceso y uso más fácil.

# Cómo Crear un Repositorio con GitHub Desktop

### Paso 1: Descargar e Instalar GitHub Desktop
1. Visita [desktop.github.com](https://desktop.github.com) y descarga GitHub Desktop.
2. Ejecuta el instalador y sigue las instrucciones para completar la instalación. [Instalacion](https://techviewleo.com/install-and-using-github-desktop-on-windows/) Está en inglés, pero incluye fotos.


### Paso 2: Iniciar Sesión en GitHub Desktop
1. Abre GitHub Desktop.
2. En la pantalla de bienvenida, haz clic en **Sign in to GitHub.com**.
3. Inicia sesión con tus credenciales de GitHub.

### Paso 3: Crear un Nuevo Repositorio
1. En GitHub Desktop, haz clic en **File** en la barra de menú.
2. Selecciona **New repository**.  
![crear_repo_desk_01](/Imagenes/crear_repo_desk_01.png)

### Paso 4: Configurar el Nuevo Repositorio
1. **Nombre del repositorio**: Introduce un nombre único y descriptivo.
2. **Descripción** (opcional): Proporciona una breve descripción sobre el propósito del repositorio.
3. **Local Path**: Selecciona la ubicación en tu computadora donde se creará el repositorio.
4. **Git Ignore Template**: Si deseas ignorar archivos específicos, selecciona una plantilla adecuada para tu proyecto. (en nuestro caso **Python**)
5. **Licencia**: Si deseas añadir una licencia, selecciona una de la lista.
6. Haz clic en **Create repository**.  
![crear_repo_desk_02](/Imagenes/crear_repo_desk_02.png)

### Paso 5: Subir a la pagina de Github
1. En GitHub Desktop, haz clic en **Publish repository**  
![crear_repo_desk_03](/Imagenes/crear_repo_desk_03.png)

- Con esto, los archivos en tu PC y en tu GitHub estarán sincronizados.
