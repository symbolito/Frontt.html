# Front.html

📋 Gestor de Tareas — Frontend

Interfaz web para gestionar tareas diarias, desarrollada con HTML, CSS y JavaScript, conectada a un backend en Node.js + PostgreSQL.

🚀 Características principales

➕ Crear nuevas tareas

✏️ Editar tareas existentes

✔️ Marcar tareas como completadas / pendientes

🗑 Eliminar tareas

📅 Manejo de fecha por tarea

🔄 Actualización dinámica de la lista

🎯 Contador de tareas en tiempo real

🖥 Interfaz moderna y responsive

🏗 Tecnologías utilizadas

HTML5

CSS3

JavaScript

Fetch API

Backend externo en Node.js / Express

Base de datos PostgreSQL (AWS)

📡 Configuración del API

En el archivo del frontend, la URL del backend se define así:

const API = "http://3.96.196.226:8000/tareas";


⚠️ Recuerda cambiar "localhost" por la IP pública de tu EC2.

📁 Estructura del proyecto
frontend/
│── index.html
│── styles.css
└── (opcional) assets/

▶️ Cómo ejecutarlo

Clona este repositorio:

git clone https://github.com/tu_usuario/gestor-tareas-front.git


Abre el archivo:

index.html


Asegúrate de que el backend esté corriendo:

http://3.96.196.226:8000/tareas


El frontend se conectará automáticamente al backend.

🔌 Requisitos del backend

Este frontend requiere un backend que exponga los siguientes endpoints:

Método	Endpoint	Descripción
GET	/tareas	Obtener todas las tareas
POST	/tareas	Crear nueva tarea
PUT	/tareas/:id	Editar o actualizar una tarea
DELETE	/tareas/:id	Eliminar tarea


✨ Sebastian Blanco Baron

Tu Nombre
Proyecto académico — Desarrollo de apps en la nube
