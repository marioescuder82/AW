# Cambiar el Color del Texto en Bootstrap

Bootstrap ofrece varias clases de utilidad para cambiar el color del texto. A continuación, se detallan las opciones disponibles.

## Clases de Color de Texto

Bootstrap proporciona clases predefinidas para aplicar diferentes colores al texto. Aquí tienes algunas de las más comunes:

- **Texto Primario**: `text-primary`
- **Texto Secundario**: `text-secondary`
- **Texto de Éxito**: `text-success`
- **Texto de Peligro**: `text-danger`
- **Texto de Advertencia**: `text-warning`
- **Texto de Información**: `text-info`
- **Texto Claro**: `text-light`
- **Texto Oscuro**: `text-dark`
- **Texto Blanco**: `text-white`

## Ejemplo de Uso

Aquí tienes un ejemplo de cómo aplicar estas clases en un documento HTML:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Cambiar Color del Texto en Bootstrap</title>
</head>
<body>
    <div class="container">
        <h1 class="mt-5 text-primary">Texto en Color Primario</h1>
        <p class="text-success">Este texto es de éxito.</p>
        <p class="text-danger">Este texto es de peligro.</p>
        <p class="text-warning">Este texto es de advertencia.</p>
        <p class="text-info">Este texto es informativo.</p>
        <p class="text-dark">Este texto es oscuro.</p>
        <p class="text-light bg-dark">Este texto es claro sobre un fondo oscuro.</p>
    </div>
</body>
</html>
