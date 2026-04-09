 Full Stack – React + Flask + MySQL 🐱💻🐶
 🐾 Patitas Club 🐾
Tu e-commerce favorito para consentir a tus mascotas 🐶🐱
Descripción del Proyecto

Esta aplicación web full stack está diseñada para ofrecer una plataforma de ventas online con gestión de productos, pagos y usuarios.

🖥️ Frontend: React.js, HTML, CSS y Bootstrap
🐍 Backend: Python + Flask con API REST
🔐 Seguridad: JWT para autenticación de usuarios
💳 Pagos: Stripe para procesamiento seguro

La app se ejecuta en un entorno virtual con Pipenv y utiliza MySQL como base de datos, asegurando persistencia, escalabilidad y control de la información.

🛠 Tecnologías Utilizadas
Área	Tecnologías
🌐 Frontend	React.js, HTML5, CSS3, Bootstrap 5
🐍 Backend	Python, Flask, API REST
🔐 Autenticación	JSON Web Tokens (JWT)
💳 Pagos	Stripe API
🗄 Base de Datos	MySQL + SQLAlchemy
📦 Gestión de dependencias	Pipenv
🚀 Despliegue	Render / Heroku
✨ Funcionalidades Principales
🛒 Gestión de Productos: Crear, editar, eliminar y listar productos mediante API REST
👤 Usuarios y Seguridad: Registro, login y autenticación con JWT
💳 Carrito y Pagos: Integración segura con Stripe
📱 Frontend Responsivo: Interfaces adaptadas a móviles y escritorio
🗄 Gestión de Base de Datos: SQLAlchemy para abstracción y manejo eficiente de modelos
⚡ Instalación y Ejecución
Clonar el repositorio:
git clone <REPO_URL>
cd <PROJECT_FOLDER>
Configurar entorno virtual e instalar dependencias:
pipenv install
pipenv shell
Configurar variables de entorno:
Crear archivo .env basado en .env.example
Configurar DATABASE_URL y claves de Stripe
Ejecutar migraciones y poblar base de datos (opcional):
pipenv run migrate
pipenv run upgrade
pipenv run insert-test-data
Iniciar el backend:
pipenv run start
Instalar dependencias del frontend y ejecutar la aplicación
⚠ Consideraciones
Cada entorno de desarrollo puede tener su propia base de datos 🗄️
Listo para despliegue rápido en Render.com o Heroku 🚀
Stripe permite pagos seguros en modo prueba y producción 💳
👨‍💻 Autores

Proyecto desarrollado como parte del Bootcamp Full Stack 4Geeks Academy:

🐶 Erwin González Bonilla
🐱 Rosbelys Pinto
🐾 Hannah Ia Assad
🐰 Guillermo Morales
![PatitasClub](https://github.com/user-attachments/assets/6da98e10-4b76-45a7-b76b-3b467baa6d09)



