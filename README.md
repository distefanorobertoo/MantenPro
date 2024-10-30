# MantenPro

**MantenPro** es una aplicación web basada en **Flask** para la gestión de activos y usuarios. La aplicación permite registrar, asigna
r y administrar activos en un entorno de mantenimiento, integrando funcionalidades para importar datos desde archivos CSV, visualizar 
los activos por categoría, editar detalles y ejecutar consultas SQL personalizadas. Utiliza **SQLite** como base de datos para un alma
cenamiento simple y eficiente.

## Funcionalidades

- **Importar Activos**: Los usuarios pueden importar datos de activos desde un archivo CSV. La aplicación valida el formato y permite 
agregar esta información a la base de datos.
  
- **Importar Usuarios**: Similar al manejo de activos, los datos de los usuarios se pueden importar mediante archivos CSV. La aplicaci
ón valida el archivo y almacena la información en la base de datos.

- **Asignar Activos**: Los usuarios pueden asignar activos a usuarios específicos, estableciendo una relación de muchos a muchos entre
 activos y usuarios, permitiendo una fácil administración del mantenimiento.

- **Visualizar Activos**: Se pueden visualizar los activos filtrados por categoría, facilitando la navegación por diferentes tipos de 
activos en el sistema.

- **Editar Activos**: Los usuarios pueden editar los detalles de los activos, como nombre, categoría, número de identificación único, 
y fecha de adquisición.

- **Consola SQL**: La aplicación incluye una consola SQL que permite a los usuarios ejecutar consultas SQL personalizadas, brindando a
cceso avanzado a los datos.

## Primeros Pasos
### 1. Clonar el Repositorio

git clone https://github.com/distefanorobertoo/MantenPro
cd MantenPro

### 2. Instalar Dependencias

pip install -r requirements.txt

### 3. Ejecutar la Aplicación

python app.py

La aplicación será accesible en http://localhost:5000.
Capturas de Pantalla

    Página de Bienvenida:

    Visualizar Activos:

    Asignar Activos a Usuarios:

    Editar Detalles del Activo:

    Consola SQL:


Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

