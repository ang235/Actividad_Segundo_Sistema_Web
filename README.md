# Sistema Web CRUD de Gestión de Préstamos - Biblioteca Internacional

Sistema web modular para la gestión de catálogo de libros, alta/baja de empleados y administración de préstamos de libros para la Biblioteca Internacional. Desarrollado en PHP, JavaScript (ES6), HTML5, CSS3 y MariaDB.

---

## 🎨 Paleta de Colores y Tipografía

* **Taupe:** `#93827F`
* **Cream:** `#F3F9D2`
* **Dry Sage:** `#BDC4A7`
* **Graphite:** `#2F2F2F`
* **Muted Teal:** `#92B4A7`
* **Tipografía:** *Libre Caslon Condensed* (Google Fonts)

---

## 📁 Estructura del Proyecto

```text
sitio web 2/
├── backend/
│   ├── apis/            # Endpoints REST (auth, libros, prestamos, usuarios)
│   ├── connection/      # Conexión PDO a MariaDB
│   ├── controllers/     # Controladores de la lógica de negocio
│   ├── models/          # Modelos de datos
│   └── services/        # Manejo de sesiones y seguridad
├── Docs/
│   └── schema.sql       # Script de creación de base de datos (7 tablas)
├── frontend/
│   ├── img/             # Logotipos y recursos visuales
│   ├── pages/           # Vistas HTML (Admin, Empleados, Categorías, Login)
│   ├── scripts/         # Lógica JS (autenticación, selección doble clic, CRUD)
│   └── styles/          # Estilos CSS globales
├── .env                 # Variables de entorno
├── .gitignore           # Archivo de exclusión de Git
├── index.php            # Página de inicio institucional
└── README.md            # Documentación del proyecto