# Temario de Aplicaciones Web

## Propósito de Aprendizaje 1: Comprender los Fundamentos del Desarrollo de Aplicaciones Web

---

### 1. ¿Qué es un Componente en el Desarrollo Web?

Un **componente** es una unidad independiente y reutilizable de una interfaz de usuario. Pueden ser botones, formularios, menús, tarjetas, etc. Son esenciales en frameworks modernos como **React**, **Vue** o **Angular**, pero también aplican a cualquier desarrollo modular.

<img width="260" height="175" alt="image" src="https://github.com/user-attachments/assets/ecebcb36-7fd1-4462-9f87-aee2e5f73abe" />


> *Jerarquía de componentes en React*

**Ventajas:**  
- Facilitan el mantenimiento  
- Permiten la reutilización  
- Mejoran el trabajo en equipo

**Ejemplo:**  
Un “componente botón” que puedes reutilizar en varias partes de una web.

---

### 2. Principales Funcionalidades de una Aplicación Web

Las funcionalidades varían según el tipo de aplicación, pero generalmente incluyen:

- **Registro y autenticación de usuarios:** Formularios de login, registro y recuperación de contraseña.
- **Gestión de datos (CRUD):** Crear, Leer, Actualizar y Borrar datos.
- **Interacción con bases de datos:** Acceso a sistemas como MySQL, PostgreSQL, MongoDB, etc.
- **Navegación y rutas:** Menús, enlaces internos y rutas amigables (usando routers).
- **Validación de formularios:** Comprobar que los datos ingresados sean correctos y seguros.
- **Consumo de APIs:** Obtener o enviar datos a servicios externos (REST, GraphQL).
- **Notificaciones y mensajes:** Informar al usuario sobre acciones o errores.

---

### 3. Ejemplo de División en Componentes

Si desarrollas una tienda online básica podrías dividir así:

- **Header:** Barra de navegación
- **ProductList:** Visualización de productos
- **ProductDetail:** Detalle de un producto
- **Cart:** Carrito de compras



Cada componente puede tener su propio archivo de HTML, CSS y JS, o estar definido como una clase/función en frameworks modernos.

---

### 4. Tecnologías Usadas

- **Frontend:** HTML, CSS, JavaScript, frameworks (React, Vue, Angular)
- **Backend:** PHP, Node.js, Python, Java, etc.
- **Base de datos:** MySQL, PostgreSQL, MongoDB, etc.
- **APIs:** Para la comunicación entre frontend y backend

> 

---

## Propósito de Aprendizaje 2: Desarrollar Componentes y Funcionalidades de una Aplicación Web

---

### 1. Diseño e Implementación del Frontend

- **Maquetación/Wireframe/Mockup:** Bocetos y prototipos visuales para planificar la interfaz.
  
  <img width="184" height="180" alt="image" src="https://github.com/user-attachments/assets/4633ba21-89a2-4c65-833a-778d84918d83" />


- **Desarrollo Frontend:** Uso de HTML, CSS y JavaScript (o frameworks) para crear componentes reutilizables, responsivos y accesibles.
- **Consumo de APIs:** El frontend se comunica con el backend usando APIs REST/GraphQL para enviar y recibir datos dinámicos.

### 2. Diseño e Implementación del Backend

- **Servidor:** Programa que recibe peticiones del usuario (Node.js, PHP, Python, etc.).
- **Manejo de peticiones y respuestas HTTP:** Procesa solicitudes (GET, POST, PUT, DELETE) y responde con datos o páginas.
- **Conexión a bases de datos:** El backend se conecta a bases de datos como MySQL, PostgreSQL o MongoDB para guardar y consultar información.



### 3. Bases de Datos

- **Modelado de datos y relaciones:** Definición de la estructura de la base de datos (tablas, campos, relaciones).
- **ORM (Object Relational Mapping):** Herramientas que conectan el código backend con la base de datos (ej: Sequelize, Doctrine, SQLAlchemy).
- **Operaciones CRUD desde el backend:** Crear, Leer, Actualizar y Eliminar registros.

### 4. Seguridad Básica en Aplicaciones Web

- **Validación de formularios:** Comprobar que los datos enviados por el usuario sean correctos y seguros.
- **Autenticación:** Verificar la identidad del usuario (login, sesiones, tokens JWT).
- **Autorización:** Controlar los permisos y accesos de cada usuario.


---

## Propósito de Aprendizaje 3: Implementar y Desplegar una Aplicación Web Funcional

---

### 1. Integración de Frontend y Backend

- **Interfaz de usuario (Frontend):** Parte visual hecha con HTML, CSS, JavaScript, frameworks, etc.
- **Manejo de API:** El frontend consume las APIs del backend para mostrar y manipular datos.
- **Proceso Solicitud-Respuesta:** El backend recibe peticiones del frontend, ejecuta lógica y responde con datos o resultados.

<img width="297" height="170" alt="image" src="https://github.com/user-attachments/assets/d1a76f5e-4285-4a9e-9865-0a748b3060de" />


### 2. Almacenamiento en Servidor

- **Tipos de servidores:** Físicos (on-premise) o en la nube (cloud, VPS).
- **Servicios de hosting:** Plataformas como Heroku, Vercel, Netlify, AWS, Azure, permiten alojar aplicaciones web.
- **Proveedores de almacenamiento:** Amazon S3, Google Cloud Storage, Dropbox, etc., para guardar archivos e imágenes.

> 

### 3. Optimización y Rendimiento

- **Optimización de recursos:** Reducir el tamaño de imágenes/scripts, usar compresión, cargar recursos bajo demanda (lazy loading).
- **Despliegue:** Proceso de poner la app en línea, accesible a los usuarios.
- **CI/CD básico:** Automatizar pruebas y despliegues usando herramientas como GitHub Actions, GitLab CI, Jenkins, etc.
- **Documentación:** Explicar la estructura, instalación y uso del proyecto para facilitar el mantenimiento y la colaboración.


---

