# **QuickFix**

## **Proyecto Trabajo Final - MVP**

**QuickFix** es una plataforma web diseñada para conectar usuarios con profesionales de servicios a domicilio. Su objetivo es optimizar el proceso de reserva y gestión de órdenes, garantizando una experiencia fluida y eficiente tanto para los usuarios como para los profesionales.

### **Características principales**
- Reserva de servicios a domicilio en tiempo real.
- Gestión de turnos eficiente y transparente para los profesionales.
- Interfaz intuitiva para facilitar la experiencia del usuario.
- Soporte para múltiples categorías de servicios.

---

## **Tecnologías utilizadas**
- **Backend:** Golang, para un manejo eficiente de la lógica de negocio y concurrencia.
- **Frontend:** Svelte, para una experiencia de usuario rápida y responsiva.
- **Base de datos:** PostgreSQL, para el almacenamiento seguro y estructurado de la información.
- **API-REST:** Protocolo que permite la comunicación entre el cliente y el servidor utilizando JSON para el intercambio de datos.
- **Docker Compose:** Herramienta para orquestar el despliegue local del proyecto.

---

## **Despliegue local**

### **Requisitos previos**
- Docker y Docker Compose instalados en el sistema.
- Configuración de las variables de entorno necesarias para conectar el frontend, backend y la base de datos.

### **Pasos para levantar el entorno**
1. Clona el repositorio:
   ```bash
   git clone <URL del repositorio>
   cd quickfix
   docker-compose up --build

