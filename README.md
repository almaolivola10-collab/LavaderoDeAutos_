# ALMA Detailing – Lavadero de Autos

Sitio web para reservar turnos de lavado y detailing. Los datos del cliente, el vehículo y el turno se guardan en una base de datos MySQL.

## Tecnologías
- PHP 8 + MySQL (mysqli con consultas preparadas)
- HTML, CSS y JavaScript

## Cómo ejecutarlo en tu computadora
1. Instalá [XAMPP](https://www.apachefriends.org/) y encendé **Apache** y **MySQL**.
2. Copiá esta carpeta dentro de `C:\xampp\htdocs\`.
3. Entrá a `http://localhost/phpmyadmin`, andá a **Importar** y cargá `lavaderodeautos.sql`.
4. Abrí `http://localhost/<nombre-de-la-carpeta>/index.php`.

Si tu MySQL tiene contraseña, cambiala en `conexion.php`.

## Archivos
| Archivo | Para qué sirve |
|---|---|
| `index.php` | Página principal y formulario de reserva |
| `style.css` | Estilos (los colores se cambian en `:root`) |
| `script.js` | Servicio elegido, horarios, resumen y validación |
| `conexion.php` | Conexión a la base de datos |
| `guardar_turno.php` | Guarda cliente, vehículo y turno |
| `horarios.php` | Informa qué horarios ya están ocupados |
| `datos.php` | Lista de clientes y vehículos registrados |
| `lavaderodeautos.sql` | Estructura y datos iniciales de la base |
| `img/` | Fotos de la página |
