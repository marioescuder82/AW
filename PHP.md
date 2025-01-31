## Introducción a PHP

PHP (Hypertext Preprocessor) es un lenguaje de programación de código abierto especialmente diseñado para el desarrollo web. Se utiliza principalmente para crear páginas web dinámicas y aplicaciones del lado del servidor. PHP se integra fácilmente con HTML y se puede usar en diferentes sistemas operativos y servidores web.

### Ejemplo

```php
<?php
// Este es un comentario en PHP
echo "Hola, Mundo!";
?>
```

### Cómo Ejecutar el Código

1. **Instalar un Servidor Local**: Puedes usar software como XAMPP o WAMP para crear un servidor local en tu computadora.
2. **Crear un Archivo PHP**: Guarda el código anterior en un archivo llamado `hola_mundo.php`.
3. **Colocar el Archivo en la Carpeta del Servidor**: Mueve el archivo a la carpeta `htdocs` (en XAMPP) o `www` (en WAMP).
4. **Abrir en el Navegador**: Accede a `http://localhost/hola_mundo.php` en tu navegador.

Este script mostrará el texto "Hola, Mundo!" en la pantalla.

### Integración de HTML y PHP

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo</title>
</head>
<body>

	<?php
		echo '<div class="container">Hola mundo</div>';
	?>

</body>
</html>
```
