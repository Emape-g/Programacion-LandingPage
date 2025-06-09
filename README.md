# Alcaidiomas Landing Page – Proyecto Final

Este repositorio contiene el **proyecto final del grupo**, una landing page moderna y funcional para la academia de idiomas **Alcaidiomas**. La aplicación fue desarrollada con **HTML**, **CSS** y **JavaScript**, e incorpora un **sistema de login conectado a una base de datos relacional PostgreSQL**. Todo el sistema está correctamente **contenedorizado con Docker** usando `docker-compose`, con contenedores separados para la app y la base de datos.

---

## ⚙️ Requisitos técnicos cumplidos

✅ **Landing page con:**

- Sección principal de presentación
- Descripción del emprendimiento/servicio
- Formulario de contacto (simulado, sin funcionalidad real de envío)

✅ **Sistema de login:**

- Login y registro con validación de usuario
- Conexión al backend mediante JavaScript
- Almacenamiento de usuarios en base de datos relacional PostgreSQL (a través de Supabase)

✅ **Base de datos relacional:**

- PostgreSQL usando Supabase (servicio en la nube)
- Opcionalmente puede reemplazarse por un contenedor local

✅ **Contenedorización con Docker:**

- Uso de Docker y Docker Compose
- Contenedor para la aplicación web (servido por Nginx)
- Posibilidad de agregar contenedor para base de datos local

✅ **Exposición del servicio:**

- El servicio se expone en el **puerto 80**  
- Accesible desde: `http://localhost`

---

## 🛠 Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript  
- Supabase (PostgreSQL + Auth + Storage)  
- Docker + Docker Compose  
- Nginx  
- Font Awesome

---

## 🚀 Características principales

- Diseño responsivo y moderno
- Registro y login de usuarios
- Validación de credenciales contra base de datos
- Subida de imagen de perfil (almacenada en Supabase)
- Navbar dinámico según el estado de login
- Página de perfil editable






