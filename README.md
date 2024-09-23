
# **Cómo Crear un Repositorio en GitHub**

## 1. Si no tienes cuenta en GitHub, crea una

1. Ve a [GitHub.com](https://github.com/).
2. Haz clic en **Sign up** (Registrarse) para abrir una cuenta.
3. Completa los campos con tu nombre de usuario, correo y contraseña.
4. Sigue las instrucciones para confirmar tu cuenta (te enviarán un correo).

---

## 1. Crear un repositorio en GitHub

1. Entra en tu cuenta de GitHub.
2. En la esquina superior derecha, haz clic en el icono de **+** y selecciona **New repository**.

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

#

### Usando Git en tu pc

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
   git commit 
   ```

7. Sube los archivos a GitHub:

   ```bash
   git push origin main
   ```


---

## 4. Clonar un repositorio de GitHub

1. Copia la URL del repositorio de GitHub que quieres clonar.
2. Abre la terminal y escribe:

   ```bash
   git clone https://github.com/usuario/nombre-del-repositorio.git
   ```

Esto descargará el repositorio en tu pc.

---

## 6. Comandos básicos de Git

- **Añadir archivos para prepararlos para subirlos**:

   ```bash
   git add archivo.txt
   ```

- **Hacer un commit** **(guardarlo con una descripción)**:

   ```bash
   git commit
   ```

- **Subir los cambios a GitHub**:

   ```bash
   git push origin main
   ```

- **Actualizar tu repositorio local con los últimos cambios de GitHub**:

   ```bash
   git pull
   ```

[Informacíon basada](https://github.com/davidgchaves/primeros-pasos-con-git-y-github?tab=readme-ov-file#6-receta-4-crear-un-repositorio-github-y-asociarlo-al-repositorio-local)