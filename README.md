### CRUD Completo con Python - Django y MySQL

##### Con este Crud aprenderas a realizar las operaciones básicas como: crear, leer, actualizar y eliminar registros en una base de datos MySQL, también ofrece la posibilidad de cargar datos desde un archivo Excel en la base de datos MySQL, así como exportar registros de la base de datos a archivos Excel, entre muchas cosas mas.


### Poner en marcha la aplicación CRUD con Python - Django y MySQL

#### Pasos a seguir

1. **Crear un entorno virtual**
   - `python -m venv env`

2. **Activar el entorno virtual**
   - Windows: `.env/Scripts/activate`
   - Mac: `.env/bin/activate`

3. **Instalar las dependencias**
   - `pip install -r requirements.txt`

4. **Crear la Base de Datos en MySQL**
   - Crear una base de datos llamada `bd_django_mysql`

5. **Configurar los parámetros de la base de datos**
   - Copiar el archivo `.env.example.txt` y renombrarlo a `.env`
   - Editar el archivo `.env` y configurar los siguientes parámetros con los datos de tu base de datos MySQL:
     ```
     DB_NAME=bd_django_mysql
     DB_USER=tu_usuario
     DB_PASSWORD=tu_contraseña
     DB_HOST=localhost
     DB_PORT=3306
     ```

6. **Configurar la conexión a la base de datos en Django**
   - Django leerá los parámetros de la base de datos del archivo `.env`
   - No es necesario editar manualmente el archivo `settings.py`

7. **Realizar las migraciones**
   - `python manage.py makemigrations`
   - `python manage.py migrate`

8. **Correr el servidor de desarrollo**
   - `python manage.py runserver`

9. **Acceder a la aplicación**
   - Abrir un navegador web y visitar `http://127.0.0.1:8000`

