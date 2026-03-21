# ItescamKaab
Sistema Web de Gestión Ganadera
Sistema web desarrollado en WordPress orientado a la administración integral de información ganadera, permitiendo el registro, control y seguimiento del ganado como parte de un proyecto de tesis.

## 🎯 Objetivo
Desarrollar una plataforma web que facilite la gestión eficiente del ganado, optimizando procesos administrativos, control sanitario y registro de información productiva mediante herramientas digitales accesibles.

---
## Funcionalidades principales

- 📋 Registro de animales (ID, raza, edad, peso, estado)
- 💉 Control de vacunación y sanidad
- 📊 Seguimiento y monitoreo del ganado
- 🧑‍🌾 Administración de usuarios (roles)
- 📁 Gestión de información y reportes
- 🌐 Acceso desde navegador web

---
##  Arquitectura del sistema

El sistema está basado en la arquitectura de WordPress:

Cliente (Navegador)  
↓  
Servidor Web (Apache / Nginx)  
↓  
WordPress (PHP)  
↓  
Base de Datos (MySQL)
---

## Tecnologías utilizadas

- WordPress (CMS)
- PHP
- MySQL
- HTML5
- CSS3
- JavaScript

---
## ⚙️ Instalación

1. Clonar el repositorio:

git clone https://github.com/tuusuario/turepo.git

2. Colocar los archivos en el servidor web

3. Crear una base de datos en MySQL

4. Importar la base de datos (archivo `.sql`)

5. Configurar el archivo `wp-config.php`:

define('DB_NAME', 'nombre_db');
define('DB_USER', 'usuario');
define('DB_PASSWORD', 'password');
define('DB_HOST', 'localhost');

6. Acceder al sistema:

http://localhost/wp-admin

---
## 🔐 Consideraciones

- La base de datos no está incluida en el repositorio
- La carpeta `uploads` no se incluye por tamaño
- Configurar credenciales antes de ejecutar

---
##  Contexto académico

Este proyecto forma parte de un trabajo de tesis enfocado en la digitalización de procesos ganaderos mediante tecnologías web, contribuyendo a la modernización del sector agropecuario.

---

## Autor

- Carlos Alfonso May Noh 

---

##  Licencia 

Uso académico y educativo.
