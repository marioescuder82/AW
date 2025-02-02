# Cómo Instalar WordPress en Local

## Requisitos Previos
1. **Servidor Local**: Necesitas un servidor local como XAMPP, WAMP o MAMP.
2. **Base de Datos**: WordPress requiere una base de datos MySQL.

## Pasos para Instalar WordPress en Local

### 1. Instalar un Servidor Local
- **XAMPP**: Descarga e instala [XAMPP](https://www.apachefriends.org/index.html).
- **WAMP**: Descarga e instala [WAMP](http://www.wampserver.com/en/).
- **MAMP**: Descarga e instala [MAMP](https://www.mamp.info/en/).

### 2. Crear una Base de Datos
1. Abre el panel de control de tu servidor local (por ejemplo, XAMPP Control Panel).
2. Inicia el módulo de **Apache** y **MySQL**.
3. Abre tu navegador y ve a `http://localhost/phpmyadmin`.
4. Haz clic en **Bases de datos** y crea una nueva base de datos (por ejemplo, `wordpress`).

### 3. Descargar WordPress
1. Ve al sitio oficial de [WordPress](https://es.wordpress.org/download/).
2. Descarga la última versión de WordPress en formato ZIP.

### 4. Descomprimir WordPress
- Descomprime el archivo ZIP y copia la carpeta `wordpress` en la carpeta `htdocs` de tu instalación de XAMPP (o la carpeta correspondiente de WAMP/MAMP).

### 5. Configurar WordPress
1. Renombra el archivo `wp-config-sample.php` a `wp-config.php`.
2. Abre `wp-config.php` y configura los siguientes parámetros:
   ```php
   define('DB_NAME', 'nombre_de_tu_base_de_datos'); // Ejemplo: 'wordpress'
   define('DB_USER', 'root'); // Usuario por defecto en XAMPP
   define('DB_PASSWORD', ''); // Contraseña por defecto en XAMPP
3. Guarda los cambios

### 6. Instalar WordPress
1. Abre tu navegador y ve a http://localhost/wordpress (o el nombre de la carpeta que hayas creado).
2. Selecciona el idioma y haz clic en Continuar.
3. Completa la información solicitada (nombre del sitio, usuario, contraseña, correo electrónico).
4. Haz clic en Instalar WordPress.

