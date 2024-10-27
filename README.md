
# Proyecto CRUD

Este proyecto implementa un sistema CRUD (Crear, Leer, Actualizar y Eliminar) con dos ventanas, diseñado para gestionar diferentes tipos de datos. A continuación, se detallan las funcionalidades disponibles en cada ventana.

## Funcionalidades CRUD

### Ventana Principal

Esta ventana permite gestionar los datos principales del sistema. Las funcionalidades incluidas son:

- **Listar**: Muestra en una tabla todos los registros de la base de datos.
- **Agregar**: Permite agregar nuevos registros ingresando información en los campos correspondientes.
- **Modificar**: Facilita la actualización de registros existentes.
- **Eliminar**: Permite eliminar registros seleccionados de la base de datos.

### Segunda Ventana

Esta ventana está dedicada a gestionar otros tipos de datos que complementan la información de la ventana principal. Incluye las siguientes funcionalidades:

- **Listar Otros Datos**: Muestra los registros relacionados en una tabla.
- **Agregar Otros Datos**: Permite agregar nuevos registros de otros tipos específicos.
- **Modificar Otros Datos**: Facilita la modificación de registros en esta sección.
- **Eliminar Otros Datos**: Permite eliminar registros seleccionados de esta sección.

## Requisitos

- **JDK**: Versión 11 o superior.
- **Dependencias**: Necesarias para la conexión a la base de datos (configuradas en el archivo `pom.xml`, si es un proyecto Maven).

## Instalación y Ejecución

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/ShantalNinasivincha/poo_27_ShantalNinasivincha.git
   ```

2. **Navegar al directorio del proyecto**:
   ```bash
   cd poo_27_ShantalNinasivincha
   ```

3. **Compilar el proyecto**:
   ```bash
   mvn clean install
   ```

4. **Ejecutar la aplicación**:
   ```bash
   mvn exec:java


