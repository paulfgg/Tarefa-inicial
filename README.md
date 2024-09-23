# manual 

---

# **Cómo Crear un Repositorio en GitHub**

## 1. Si no tienes cuenta en GitHub, crea una

1. Ve a [GitHub.com](https://github.com/).
2. Haz clic en **Sign up** (Registrarse) para abrir una cuenta.
3. Completa los campos con tu nombre de usuario, correo y contraseña.
4. Sigue las instrucciones para confirmar tu cuenta (te enviarán un correo).

---

## 1. Crear un repositorio en GitHub

1. Entra en tu cuenta de GitHub.
2. En la esquina superior derecha, haz clic en el icono de **+** y selecciona **New repository** (Nuevo repositorio).

3. Completa los campos de la siguiente manera:
   - **Repository name** (Nombre del repositorio): Ponle el nombre que quieras a tu repositorio.
   - **Description** (Descripción, opcional): Describe brevemente tu proyecto (ej. "Mi primer repo").
   - **Public** o **Private**:
     - **Public**: Todos pueden ver tu repositorio.
     - **Private**: Solo tú y las personas que invites podrán verlo.
   - Si quieres que te cree un archivo `README.md`, marca la casilla **Initialize this repository with a README**.

4. Haz clic en **Create repository**.

---

## 2. Subir archivos a tu repositorio

### Opción 1: Directamente desde GitHub

1. Una vez que hayas creado el repositorio, haz clic en **Add file**.
2. Luego selecciona **Upload files**.
3. Arrastra los archivos que quieras subir o selecciona los archivos desde tu pc.
4. Escribe un mensaje en **Commit message** (es una pequeña descripción de los archivos que estás subiendo).
5. Haz clic en **Commit changes** para guardar los archivos en el repositorio.

### Opción 2: Usando Git en tu pc

1. En la página de tu repositorio en GitHub, haz clic en el botón **Code**.
2. Copia la URL del repositorio.

#### Luego, en la terminal:

3. Clona el repositorio en tu computadora:

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```

4. Ve a la carpeta del repositorio recién clonado:

   ```bash
   cd nombre-del-repositorio
   ```

5. Añade los archivos que quieras subir:

   ```bash
   git add .
   ```

6. Crea un commit con un mensaje para describir los cambios:

   ```bash
   git commit -m "Descripción breve de los cambios"
   ```

7. Sube los archivos a GitHub:

   ```bash
   git push origin main
   ```

---

## 4. Trabajar con ramas y pull requests

### Crear una nueva rama (branch)

1. En la página de tu repositorio en GitHub, en la parte superior donde dice **main**, haz clic y escribe el nombre de la nueva rama (ej. "nueva-rama").
2. Pulsa **Enter** y ya tendrás tu rama nueva.

### Hacer un Pull Request

1. Si has hecho cambios en una rama y quieres que pasen a la rama principal (main), abre un **pull request**.
2. Ve a la pestaña **Pull requests** en la página de tu repositorio.
3. Haz clic en **New pull request**.
4. Describe qué cambios has hecho y haz clic en **Create pull request**.

---

## 5. Clonar un repositorio de GitHub

1. Copia la URL del repositorio de GitHub que quieres clonar.
2. Abre la terminal y escribe:

   ```bash
   git clone https://github.com/usuario/nombre-del-repositorio.git
   ```

Esto descargará el repositorio en tu computadora.

---

## 6. Comandos básicos de Git

- **Añadir archivos para prepararlos para subirlos**:

   ```bash
   git add archivo.txt
   ```

- **Hacer un commit** **(guardarlo con una descripción)**:

   ```bash
   git commit -m "Descripción del cambio"
   ```

- **Subir los cambios a GitHub**:

   ```bash
   git push origin main
   ```

- **Actualizar tu repositorio local con los últimos cambios de GitHub**:

   ```bash
   git pull
   ```
[Información documentada](https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories)
---