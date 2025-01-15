# Cambiar el Color de Fondo de un `div` en Bootstrap

Bootstrap ofrece varias clases de utilidad para establecer colores de fondo. A continuación, se detallan las opciones disponibles.

## Clases de Color de Fondo

Bootstrap proporciona clases predefinidas para aplicar diferentes colores de fondo. Aquí tienes algunas de las más comunes:

- **Fondo Primario**: `bg-primary`
- **Fondo Secundario**: `bg-secondary`
- **Fondo de Éxito**: `bg-success`
- **Fondo de Peligro**: `bg-danger`
- **Fondo de Advertencia**: `bg-warning`
- **Fondo de Información**: `bg-info`
- **Fondo Claro**: `bg-light`
- **Fondo Oscuro**: `bg-dark`
- **Fondo Blanco**: `bg-white`

## Ejemplo de Uso

Aquí tienes un ejemplo de cómo aplicar estas clases en un documento HTML:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Cambiar Color de Fondo en Bootstrap</title>
</head>
<body>
    <div class="container">
        <h1 class="mt-5">Ejemplo de Cambio de Color de Fondo</h1>
        <div class="bg-primary text-white p-3">
            Este div tiene un fondo azul.
        </div>
        <div class="bg-success text-white p-3 mt-3">
            Este div tiene un fondo verde.
        </div>
        <div class="bg-danger text-white p-3 mt-3">
            Este div tiene un fondo rojo.
        </div>
    </div>
</body>
</html>
