# ¡Hola! Soy Byron Pineda (ByronKinal) 👋
### 🚀 Desarrollador Full Stack & Mobile | Estudiante del Centro Educativo Técnico Kinal

¡Bienvenido a mi perfil de GitHub! Soy un desarrollador apasionado por crear soluciones tecnológicas robustas, eficientes y modernas. Actualmente me encuentro cursando mis estudios en el **Centro Educativo Técnico Kinal**, donde he perfeccionado mis habilidades en el desarrollo de software tanto en el lado del servidor como en el cliente y en plataformas móviles.

Me encanta diseñar arquitecturas limpias, explorar la integración de múltiples bases de datos, implementar microservicios y trabajar con tecnologías de vanguardia como **React 19**, **Vite 8**, **Tailwind CSS v4**, **Node.js (Express 5)**, **Java 21 / Spring Boot 3.5** y **React Native**.

---

## 🛠️ Tecnologías y Herramientas

### **Frontend & Mobile**
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_8-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white)

### **Backend & APIs**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_5-000000?style=for-the-badge&logo=express&logoColor=white)
![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

### **Bases de Datos & Almacenamiento**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

---

## 🏛️ Arquitecturas y Patrones de Diseño
Para garantizar la escalabilidad, mantenibilidad y el bajo acoplamiento en mis aplicaciones, aplico metodologías y patrones estandarizados en la industria:
*   **Clean Architecture (Arquitectura Limpia):** Separación rigurosa de responsabilidades (Presentation, Domain, Data) aplicada principalmente en mis aplicaciones móviles con **React Native**.
*   **Microservicios:** Arquitecturas distribuidas con comunicación inter-servicio mediante endpoints internos y clientes REST dedicados.
*   **MVC & MVVM:** Estructuración de aplicaciones web y de escritorio separando la interfaz de usuario, los controladores/viewmodels y los modelos de datos.
*   **Seguridad Avanzada:** Autenticación robusta basada en JWT, rotación de tokens (refresh tokens), control de acceso basado en roles (RBAC), encriptación con Argon2 y Bcrypt, limitadores de peticiones (rate limiting) y configuraciones de seguridad HTTP (Helmet).

---

## 📁 Proyectos Destacados

### 🩸 **BloodLink** — *Sistema de Gestión de Donación de Sangre*
Una solución tecnológica integral para optimizar y dinamizar los procesos de donación de sangre, estructurada bajo una arquitectura moderna de microservicios:
*   **Arquitectura:** Microservicios y Clean Architecture.
*   **Backend:** División híbrida de servicios:
    *   **MongoDB (Mongoose):** Gestiona perfiles, citas, triaje, auditorías, reportes de stock, IoT y un asistente inteligente de donación por IA.
    *   **PostgreSQL (Sequelize):** Controla el sistema de autenticación centralizado (auth), usuarios, y un motor de gamificación mediante incentivos y canje de recompensas.
*   **Asistente IA:** Integración de Inteligencia Artificial (OpenAI / OpenRouter API) para soporte y orientación pre-donación.
*   **IoT & Monitoreo:** Simulación de telemetría IoT para registrar la temperatura e historial de bolsas de sangre en tiempo real.
*   **Frontend Móvil:** App moderna desarrollada en **React Native (Expo)** para los donantes.

### 🏆 **Ktournaments** — *Sistema de Gestión de Torneos*
Plataforma robusta diseñada para organizar y administrar torneos deportivos de forma automatizada y eficiente.
*   **Tecnologías:** Java 21 & Spring Boot 3.5.
*   **Bases de Datos:** MySQL con Spring Data JPA.
*   **Seguridad:** Spring Security con flujo de autenticación local y soporte OAuth2 (Google/GitHub), validaciones estrictas y protección de endpoints.
*   **Interactividad:** WebSockets para actualización de marcadores y posiciones en tiempo real.
*   **Interfaz de Usuario Híbrida:** 
    *   **JoinFaces (PrimeFaces + JSF):** Panel administrativo web elegante y reactivo.
    *   **FlatLaf (Swing Desktop):** Cliente de escritorio nativo con diseño plano y moderno para visualización rápida de torneos.
*   **Herramientas adicionales:** Lombok, MapStruct (para mapeo DTO óptimo) y Springdoc OpenAPI (Swagger).

### 🖥️ **Client-Admin & Server-Admin** — *Panel Administrativo Completo*
Un sistema administrativo integral que conecta un cliente altamente interactivo y veloz con un servidor modular de última generación.
*   **Server-Admin:** API REST en **Express 5** y **Node.js** con conexión a **MongoDB** mediante Mongoose. Cuenta con auditorías, validadores de datos, protección HTTP (Helmet), y almacenamiento de imágenes integrado con **Multer** y **Cloudinary**.
*   **Client-Admin:** Panel web desarrollado con **React 19**, **Vite 8** y **Tailwind CSS v4** con soporte nativo de compilación rápida. Manejo del estado global mediante **Zustand**, rutas optimizadas con **React Router 7**, formularios reactivos con **React Hook Form** y componentes visuales estilizados con **Material Tailwind**.

### 💬 **ProyectoGestorOpiniones** — *API REST de Autenticación y Opiniones*
Una API robusta enfocada en la seguridad del usuario y el manejo de opiniones/reseñas en línea.
*   **Backend:** Node.js y Express 5.
*   **Base de Datos:** PostgreSQL con **Sequelize** y soporte para **Mongoose**.
*   **Seguridad:** Hashing seguro con **Argon2**, protección contra ataques de fuerza bruta mediante `express-rate-limit`, rotación de JWT y envío automático de correos con **Nodemailer**.

---

## 📈 Estadísticas de GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ByronKinal&show_icons=true&theme=tokyonight&count_private=true" alt="Estadísticas de GitHub de Byron" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ByronKinal&layout=compact&theme=tokyonight" alt="Lenguajes más usados por Byron" width="48%" />
</p>

---

## 📫 Contáctame
*   **Correo Institucional:** [bpineda-2024427@kinal.edu.gt](mailto:bpineda-2024427@kinal.edu.gt)
*   **GitHub:** [@ByronKinal](https://github.com/ByronKinal)

---
*«La tecnología es mejor cuando une a las personas y resuelve problemas reales.»* 💻✨
