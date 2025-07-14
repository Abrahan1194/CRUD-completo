CrudNote - Aplicación de Notas Colaborativas
CrudNote es una Aplicación de Una Sola Página (SPA) diseñada para gestionar notas, con funcionalidades personales y colaborativas. Te permite registrarte, iniciar sesión y administrar tus notas de forma eficiente, incluyendo la opción de compartirlas y controlar los permisos de acceso. Además, cuenta con un robusto rol de administrador para una gestión integral del sistema.

🌟 Características Principales
Para Usuarios
Autenticación Segura: Sistema completo de registro e inicio de sesión para mantener tus notas privadas.

Gestión Completa de Notas (CRUD): Crea, lee, actualiza y elimina tus notas personales fácilmente.

Editor de Notas Intuitivo: Cada nota puede incluir:

Un título claro.

Contenido de texto detallado.

La opción de adjuntar una imagen, ya sea desde una URL externa o subiendo un archivo local.

Colaboración en Notas:

Comparte notas selectivamente con otros usuarios registrados.

Asigna permisos específicos: solo lectura (readonly) o edición (edit).

Visualiza notas compartidas por otros, con los permisos que te hayan sido otorgados.

Perfil de Usuario Detallado:

Accede y visualiza tu información personal.

Actualiza tu contraseña para mayor seguridad.

Obtén un resumen rápido de las notas que has compartido.

Tema Personalizable: Cambia entre un tema claro y un tema oscuro para mayor comodidad visual. Tu preferencia se guarda automáticamente.

Diseño Responsivo: Disfruta de una interfaz adaptada para una visualización perfecta en cualquier dispositivo, desde ordenadores de escritorio hasta móviles.

Para Administradores
Panel de Administración Centralizado: Una sección exclusiva que te da control total y una visión general de la aplicación.

Gestión Integral de Usuarios:

Visualiza a todos los usuarios registrados.

Puedes eliminar usuarios cuando sea necesario.

Control Total sobre Notas:

Accede, edita y elimina notas de CUALQUIER usuario del sistema.

Estadísticas Generales: Un contador simple que muestra el número total de usuarios y notas activas, facilitando la monitorización del crecimiento.

Gestión de Suscripciones: Visualiza y elimina las suscripciones al boletín.

Funcionalidad para Enviar Correo a Suscriptores: (Nota: Esta característica es un placeholder en el demo y requeriría un backend real para su implementación completa).

🛠️ Tecnologías Utilizadas
Frontend
HTML5: Para la estructura semántica de la página.

CSS3: Para el estilado y diseño visual.

JavaScript (ES6+ Modules): Para la lógica del lado del cliente, el enrutamiento SPA y la interacción dinámica.

Frameworks/Librerías
Bootstrap 5: Para un diseño responsivo robusto y componentes de interfaz pre-estilizados.

Bootstrap Icons: Para una iconografía moderna y escalable.

Backend (Simulado)
json-server: Una herramienta ligera que simula una API RESTful, usando un archivo db.json como base de datos. Ideal para el desarrollo rápido y prototipos.

📂 Estructura de Carpetas
La organización del proyecto sigue una estructura modular para facilitar la claridad y el mantenimiento del código:

CrudNote/
├── css/
│   └── style.css
├── js/
│   ├── main.js
│   ├── ui.js
│   ├── services.js
│   └── auth.js
├── db.json
├── index.html
└── README.md
CrudNote/: El directorio principal del proyecto.

css/: Contiene tus hojas de estilo CSS personalizadas (style.css).

js/: Almacena todos los archivos JavaScript modularizados:

main.js: Punto de entrada principal; gestiona el enrutamiento y la orquestación de la aplicación.

ui.js: Funciones para renderizar las vistas de la interfaz de usuario.

services.js: Maneja las interacciones con la API (simulada por json-server).

auth.js: Gestiona la lógica de autenticación y sesión del usuario.

db.json: El archivo de datos JSON que json-server utiliza como "base de datos".

index.html: El único archivo HTML; es el punto de entrada de tu SPA.

README.md: Este archivo de documentación del proyecto.

🚀 Cómo Iniciar el Proyecto
Para poner en marcha CrudNote en tu entorno de desarrollo local, sigue estos sencillos pasos:

📋 Prerrequisitos
Asegúrate de tener instalado Node.js y su gestor de paquetes npm en tu sistema.

👣 Pasos para la Configuración
Clona o descarga el repositorio:
Abre tu terminal o línea de comandos y ejecuta:

Bash

git clone https://github.com/tu-usuario/CrudNote.git # Reemplaza con la URL real de tu repositorio
cd CrudNote
Instala json-server (si no lo tienes):
json-server es fundamental para simular la API. Instálalo globalmente:

Bash

npm install -g json-server
Inicia el servidor de la API:
Desde la raíz del directorio CrudNote en tu terminal, ejecuta este comando. El servidor se lanzará en http://localhost:3000, sirviendo los datos de db.json.

Bash

json-server --watch db.json
Abre la aplicación en tu navegador:
No necesitas un servidor web adicional para el frontend. Simplemente abre el archivo index.html directamente en tu navegador (doble clic o arrastrar y soltar).

Importante: Para que la aplicación funcione, la página index.html debe estar abierta en tu navegador y el json-server debe estar ejecutándose en la terminal.

🔑 Credenciales de Prueba
Para explorar CrudNote, puedes usar estas credenciales:

Administrador:

Usuario: admin

Contraseña: 123

Usuario Normal:

Puedes registrar un nuevo usuario directamente desde la interfaz de la aplicación.
