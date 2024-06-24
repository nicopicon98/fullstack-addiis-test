# Evaluación Técnica para Desarrollador Fullstack (Spring Boot y Next.js)

## Introducción
Este proyecto tiene como objetivo evaluar la proficiencia en el desarrollo fullstack utilizando Spring Boot para el backend y Next.js para el frontend. El tema del proyecto es una aplicación para entrenar perros, donde los usuarios pueden gestionar entrenamientos, registrar progresos y acceder a recursos educativos.

## Requisitos Funcionales

1. **Autenticación y Autorización**
   - Los usuarios deben poder registrarse y autenticarse en la aplicación.
   - Implementar roles de usuario: Administrador y Entrenador.
   - Los administradores pueden gestionar (crear, actualizar, eliminar) entrenadores y entrenamientos.
   - Los entrenadores pueden gestionar los perros asignados y registrar el progreso de los entrenamientos.

2. **Gestión de Perros**
   - Los entrenadores pueden agregar, actualizar y eliminar información de los perros que están entrenando.
   - Cada perro tiene información básica: nombre, edad, raza, nivel de entrenamiento.

3. **Gestión de Entrenamientos**
   - Los administradores pueden crear y asignar programas de entrenamiento.
   - Los entrenadores pueden ver los programas asignados y registrar el progreso diario de cada perro.
   - El progreso incluye actividades realizadas, notas y cualquier observación relevante.

4. **Recursos Educativos**
   - Sección para acceder a artículos, videos y guías sobre entrenamiento de perros.
   - Los administradores pueden gestionar estos recursos.

## Requisitos Técnicos

1. **Backend (Spring Boot)**
   - Utilizar Spring Boot para construir una API RESTful.
   - Utilizar Spring Security para la autenticación y autorización.
   - Persistencia de datos utilizando JPA y una base de datos relacional (MySQL o PostgreSQL).
   - Documentar la API utilizando Swagger.

2. **Frontend (Next.js)**
   - Utilizar Next.js para construir una SPA (Single Page Application).
   - Implementar un sistema de rutas privadas para proteger las páginas que requieren autenticación.
   - Utilizar Redux o Context API para el manejo del estado global de la aplicación.
   - Consumir la API del backend para todas las operaciones de CRUD.

3. **Despliegue**
   - Configurar el despliegue del backend en un servicio cloud (Heroku, AWS, etc.).
   - Configurar el despliegue del frontend en un servicio cloud (Vercel, Netlify, etc.).
   - Proveer enlaces a las aplicaciones desplegadas y un repositorio público con el código fuente (GitHub, GitLab).

## Entregables

1. **Código Fuente**
   - Repositorio en GitHub con el código del backend y frontend.
   - Instrucciones claras para levantar el entorno de desarrollo localmente.

2. **Documentación**
   - Documentación de la API generada con Swagger.
   - Documentación del frontend explicando la estructura del proyecto y cómo se conectan con la API.
   - Archivos README en ambos repositorios detallando cómo ejecutar y desplegar las aplicaciones.

3. **Tiempo de entrega**
   - El tiempo máximo para completar la evaluación es de 24 horas a partir de las 8:00 Am del dia Lunes 24 de Junio de 2024. Así que la entrega debe ser antes de las 8:00 Am del dia Martes 25 de Junio de 2024 con el subject `Evaluación Técnica Fullstack - [Nombre del Candidato]` al correo contacto@addiis.com.co con copia al correo nicolaspicon98@gmail.com.

## Criterios de Evaluación

1. **Funcionalidad**
   - Cumplimiento de todos los requisitos funcionales.
   - Correcta implementación de las operaciones de CRUD.

2. **Calidad del Código**
   - Organización y limpieza del código.
   - Uso adecuado de patrones de diseño y mejores prácticas.

3. **Seguridad**
   - Implementación adecuada de la autenticación y autorización.
   - Manejo seguro de datos sensibles.

4. **Despliegue**
   - Despliegue exitoso en un servicio cloud.
   - Enlaces a las aplicaciones desplegadas funcionan correctamente.

5. **Documentación**
   - Calidad y claridad de la documentación proporcionada.
   - Facilidad para seguir las instrucciones y levantar el entorno localmente.

6. **No se aceptarán preguntas de ningún tipo.**


Mucha suerte!
