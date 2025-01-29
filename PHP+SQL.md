## PHP + SQL

### Paso 1: Conectar PHP a MySQL

Crea un archivo PHP llamado `conexion.php` con el siguiente contenido:

```php
<?php
$host = 'localhost';
$usuario = 'root'; // Cambia si tienes otro usuario
$contraseña = ''; // Cambia si tienes otra contraseña
$base_datos = 'mi_base_datos';

// Crear conexión
$conn = new mysqli($host, $usuario, $contraseña, $base_datos);

// Verificar conexión
if ($conn->connect_error) {
    die("Conexión fallida: " . $conn->connect_error);
}
echo "Conexión exitosa";
?>
```

### Paso 2: Realizar una Consulta

Ahora, puedes realizar una consulta para obtener los datos de la tabla `alumnos`. Crea un archivo llamado `consultar.php`:

```php
<?php
include 'conexion.php'; // Incluir el archivo de conexión

$sql = "SELECT * FROM alumnos";
$result = $conn->query($sql);

if ($result->num_rows > 0) {
    // Salida de datos de cada fila
    while($row = $result->fetch_assoc()) {
        echo "id: " . $row["id"]. " - Nombre: " . $row["nombre"]. " - Email: " . $row["email"]. "<br>";
    }
} else {
    echo "0 resultados";
}

$conn->close(); // Cerrar conexión
?>
```


