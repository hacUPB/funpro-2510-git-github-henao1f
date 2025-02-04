1. Crear el repositorio remoto en GitHub
Inicia sesión en GitHub.
Haz clic en el botón "New" para crear un nuevo repositorio.
Asigna un nombre y, si lo deseas, una descripción.
No selecciones la opción de inicializar con README (ya que ya tienes un repositorio local).
Haz clic en "Create repository".

2. Vincular el repositorio local con el remoto
Copia la URL del repositorio remoto (por ejemplo: https://github.com/usuario/nombre-repo.git).

3. Agregar el repositorio remoto al local
Abre la terminal en tu repositorio local y agrega el repositorio remoto con:
bash
Copiar
git remote add origin https://github.com/usuario/nombre-repo.git

4. Subir los cambios al repositorio remoto
Realiza un push de tus cambios locales al repositorio remoto:
bash
Copiar
git push -u origin master
[remoto](../images/repositorio.jpg)

