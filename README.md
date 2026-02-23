WebApp Full Stack – React + Flask + MySQL
Descripción del Proyecto

Este proyecto es una aplicación web full stack desarrollada para ofrecer una plataforma de ventas online con gestión de productos, pagos y usuarios. El frontend fue construido con React.js, HTML, CSS y Bootstrap, mientras que el backend utiliza Python con Flask para construir una API REST que gestiona productos, usuarios y transacciones.

El proyecto incluye integración con JWT para autenticación segura de usuarios y Stripe para procesamiento de pagos online, ofreciendo un flujo seguro y profesional para comercio electrónico.

El proyecto se ejecuta dentro de un entorno virtual usando Pipenv y está conectado a una base de datos MySQL, asegurando persistencia, escalabilidad y control de la información.

Tecnologías Utilizadas

Frontend: React.js, HTML5, CSS3, Bootstrap 5

Backend: Python, Flask, API REST

Autenticación: JSON Web Tokens (JWT)

Procesamiento de pagos: Stripe API

Base de datos: MySQL

Gestión de dependencias: Pipenv (entorno virtual)

Integración y despliegue: Configuración lista para Render o Heroku

Funcionalidades Principales

Gestión de Productos: API REST que permite listar, crear, editar y eliminar productos.

Usuarios y Seguridad: Registro, login y autenticación mediante JWT.

Carrito y Pagos: Procesamiento seguro de pagos con Stripe.

Frontend Responsivo: Interfaces construidas con React y Bootstrap, adaptadas a dispositivos móviles y escritorio.

Gestión de Base de Datos: MySQL como motor principal, conectada mediante SQLAlchemy para abstracción y manejo eficiente de modelos.

Instalación y Ejecución

Clonar el repositorio:

git clone <REPO_URL>
cd <PROJECT_FOLDER>

Configurar entorno virtual con Pipenv e instalar dependencias:

pipenv install
pipenv shell

Crear archivo .env basado en .env.example y configurar las variables de entorno, incluyendo DATABASE_URL y claves de Stripe.

Ejecutar migraciones y poblar base de datos si es necesario:

pipenv run migrate
pipenv run upgrade
pipenv run insert-test-data

Iniciar el backend:

pipenv run start

Instalar dependencias del frontend y ejecutar la aplicación:

cd client
npm install
npm run start
Estructura del Proyecto
/src
 ├─ /api           # Flask API REST
 │    ├─ models.py # Modelos de base de datos
 │    ├─ routes.py # Endpoints de productos y usuarios
 │    └─ commands.py # Scripts de prueba y migraciones
 ├─ /client        # Frontend en React
 │    ├─ public
 │    └─ src
 │         ├─ components
 │         ├─ pages
 │         └─ services # Comunicación con API y Stripe
 └─ .env.example   # Variables de entorno de ejemplo
Consideraciones

Cada entorno de desarrollo puede tener su propia base de datos; se recomienda usar scripts automatizados para poblar datos de prueba.

El proyecto está listo para despliegue rápido en Render.com o Heroku, con configuración mínima.

Stripe permite pagos seguros en entornos de prueba y producción.

Autores

Proyecto desarrollado como parte del Bootcamp Full Stack 4Geeks Academy por Erwin González Bonilla y Rosbelys Pinto, Hannah Ia Assad, y >Guillermo MOrales.
