## Introducción a SQL

SQL (Structured Query Language) es un lenguaje de programación estándar utilizado para gestionar y manipular bases de datos relacionales. Permite a los usuarios realizar diversas operaciones, como insertar, actualizar, eliminar y consultar datos.

### Características Principales

- **Lenguaje Declarativo**: SQL se centra en "qué" se quiere hacer, no en "cómo" hacerlo.
- **Interacción con Bases de Datos**: SQL se utiliza para interactuar con sistemas de gestión de bases de datos (DBMS) como MySQL, PostgreSQL, Oracle y SQL Server.
- **Estandarización**: Aunque hay ligeras variaciones entre diferentes DBMS, SQL es un estándar ampliamente aceptado.

### Comandos Básicos de SQL

1. **SELECT**: Recupera datos de una o más tablas.
   ```sql
   SELECT * FROM usuarios;
   ```

2. **INSERT**: Agrega nuevos registros a una tabla.
   ```sql
   INSERT INTO usuarios (nombre, email) VALUES ('Juan Pérez', 'juan@example.com');
   ```

3. **UPDATE**: Modifica registros existentes en una tabla.
   ```sql
   UPDATE usuarios SET email = 'nuevo_email@example.com' WHERE id = 1;
   ```

4. **DELETE**: Elimina registros de una tabla.
   ```sql
   DELETE FROM usuarios WHERE id = 1;
   ```

### Estructura de una Base de Datos

Una base de datos relacional está compuesta por tablas, que son estructuras que organizan los datos en filas y columnas. Cada tabla tiene:

- **Filas**: Representan registros individuales.
- **Columnas**: Representan atributos de los registros.

### Ejemplo de Uso

Supongamos que tenemos una tabla llamada `usuarios` con las siguientes columnas: `id`, `nombre` y `email`. Aquí hay un ejemplo de cómo utilizar SQL para interactuar con esta tabla:

```sql
-- Crear la tabla
CREATE TABLE usuarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL
);

-- Insertar datos
INSERT INTO usuarios (nombre, email) VALUES ('Juan Pérez', 'juan@example.com');

-- Consultar datos
SELECT * FROM usuarios;

-- Actualizar datos
UPDATE usuarios SET email = 'juanp@example.com' WHERE id = 1;

-- Eliminar datos
DELETE FROM usuarios WHERE id = 1;
```
