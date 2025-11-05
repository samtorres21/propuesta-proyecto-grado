# Agenda Personal Digital

## propuesta-proyecto-grado
Repositorio que contendrá todo lo relacionado al proyecto final de grado de la tecnología en desarrollo de software.

###  Descripción
Aplicación web que permite a los usuarios organizar sus tareas y eventos diarios de forma sencilla y visual.

###  Funcionalidades
- Registro de tareas y eventos
- Visualización en calendario
- Filtros por fecha y prioridad
- Edición y eliminación de registros

###  Tecnologías
- HTML, CSS, JavaScript
- Backend: Node.js + Express
- Base de datos: SQLite o MongoDB

###  Estructura del repositorio
- `/frontend`: Interfaz de usuario
- `/backend`: API y lógica del servidor
- `/docs`: Documentación técnica

###  Cronograma sugerido
- Semana 1: Diseño de interfaz y base de datos
- Semana 2: Desarrollo de funcionalidades básicas
- Semana 3: Pruebas y mejoras
- Semana 4: Documentación y presentación

- # Diagrama de ishikawa del proyecto de aula
![Diagrama de ishikawa](carpeta/diagrama_de_ishikawa.png)

# Historias de Usuario

## Rol: Administrador

### 1. Gestión de usuarios
**Como administrador**,  
**quiero** crear, editar y eliminar usuarios,  
**para** mantener actualizado el acceso al sistema.  

**Criterios de aceptación:**
- Puedo agregar nuevos usuarios con nombre, correo y rol.
- Puedo editar la información existente.
- Puedo eliminar usuarios inactivos.

---

### 2. Control de roles y permisos
**Como administrador**,  
**quiero** asignar roles y permisos específicos,  
**para** garantizar que cada usuario tenga acceso solo a lo necesario.  

**Criterios de aceptación:**
- Puedo asignar o cambiar el rol de un usuario.
- El sistema valida que solo los administradores puedan cambiar roles.

---

### 3. Visualización de reportes generales
**Como administrador**,  
**quiero** ver reportes de ventas y desempeño de los vendedores,  
**para** tomar decisiones estratégicas basadas en datos.  

**Criterios de aceptación:**
- El sistema genera reportes filtrados por fechas y vendedores.
- Puedo exportar los reportes en PDF o Excel.

---

### 4. Configuración del sistema
**Como administrador**,  
**quiero** configurar parámetros generales (moneda, impuestos, políticas),  
**para** adaptar el sistema a las necesidades de la empresa.  

**Criterios de aceptación:**
- Puedo cambiar la tasa de impuestos y moneda.
- Los cambios se aplican automáticamente en todo el sistema.

---

### 5. Control de inventario global
**Como administrador**,  
**quiero** tener acceso a todo el inventario,  
**para** supervisar el stock y garantizar disponibilidad de productos.  

**Criterios de aceptación:**
- Puedo ver productos agotados o con bajo stock.
- Puedo generar alertas de reabastecimiento.

---

## Rol: Vendedor

### 1. Registro de ventas
**Como vendedor**,  
**quiero** registrar cada venta realizada,  
**para** mantener un historial actualizado de mis transacciones.  

**Criterios de aceptación:**
- Puedo agregar cliente, producto, cantidad y forma de pago.
- El sistema guarda automáticamente la fecha y hora de la venta.

---

### 2. Consulta de historial de ventas
**Como vendedor**,  
**quiero** visualizar mi historial de ventas,  
**para** revisar mis transacciones pasadas y detectar errores o tendencias.  

**Criterios de aceptación:**
- Puedo filtrar ventas por fecha o cliente.
- Puedo descargar el historial en formato Excel.

---

### 3. Gestión de clientes
**Como vendedor**,  
**quiero** registrar y actualizar información de mis clientes,  
**para** mantener una base de datos confiable para futuras ventas.  

**Criterios de aceptación:**
- Puedo agregar nuevos clientes con datos de contacto.
- Puedo editar la información de clientes existentes.

---

### 4. Generación de facturas
**Como vendedor**,  
**quiero** generar facturas automáticas al registrar una venta,  
**para** entregar comprobantes oficiales a los clientes.  

**Criterios de aceptación:**
- El sistema genera una factura en PDF con los datos de la venta.
- Puedo enviar la factura por correo al cliente.

---

### 5. Control de stock personal
**Como vendedor**,  
**quiero** consultar el inventario disponible,  
**para** saber qué productos puedo ofrecer a mis clientes.  

**Criterios de aceptación:**
- Puedo buscar productos por nombre o categoría.
- El sistema muestra cantidad disponible y precio actual.


