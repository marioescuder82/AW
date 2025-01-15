# Cambiar el Tamaño de Texto en Bootstrap

En Bootstrap, puedes cambiar el tamaño del texto utilizando las clases de utilidad que el framework proporciona. Aquí te muestro cómo hacerlo:

## Clases de Tamaño de Texto

Bootstrap ofrece varias clases para ajustar el tamaño del texto:

- **Tamaños de texto**:
  - `fs-1`: Tamaño de texto más grande
  - `fs-2`: Grande
  - `fs-3`: Mediano
  - `fs-4`: Pequeño
  - `fs-5`: Muy pequeño
  - `fs-6`: Tamaño mínimo

## Ejemplo de Uso

Aquí tienes un ejemplo de cómo utilizar estas clases en un archivo HTML:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Tamaño de Texto en Bootstrap</title>
</head>
<body>
    <div class="container">
        <h1 class="mt-5">Ejemplo de Tamaño de Texto</h1>
        
        <h2 class="mt-4 fs-1">Texto Tamaño 1</h2>
        <p class="fs-2">Este es un texto de tamaño 2.</p>
        <p class="fs-3">Este es un texto de tamaño 3.</p>
        <p class="fs-4">Este es un texto de tamaño 4.</p>
        <p class="fs-5">Este es un texto de tamaño 5.</p>
        <p class="fs-6">Este es un texto de tamaño 6.</p>
    </div>
</body>
</html>
