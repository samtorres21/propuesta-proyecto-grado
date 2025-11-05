---
# propuesta-proyecto-grado
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
---
# 🔄 Diagrama de Flujo del Sistema

```mermaid
flowchart TD

A[Inicio] --> B[Pantalla de Login]
B --> C[Usuario ingresa credenciales]
C --> D{Credenciales válidas?}

D -- No --> E[Mostrar mensaje de error]
E --> B

D -- Sí --> F{Rol del usuario}

F -- Administrador --> G[Panel de administración]
F -- Vendedor --> H[Panel de ventas]

G --> G1[Gestión de usuarios]
G --> G2[Gestión de inventario]
G --> G3[Reportes y estadísticas]

H --> H1[Registrar venta]
H --> H2[Consultar historial de ventas]
H --> H3[Gestionar clientes]

G1 --> I[Guardar cambios]
G2 --> I
G3 --> I
H1 --> I
H2 --> I
H3 --> I

I --> J[Cerrar sesión]
J --> K[Fin]
---
### Validación y Verificación del Proyecto

Esta sección tiene como propósito identificar posibles **casos de uso** y validar que el proyecto cumpla con los requerimientos antes de su desarrollo completo.

#### Objetivo
Asegurar que la propuesta del sistema sea viable, coherente y responda a las necesidades de los usuarios finales antes de su construcción.

#### Casos de Uso Identificados

1. **Registro de usuario:** El sistema debe permitir registrar nuevos usuarios con datos válidos (correo, contraseña).
2. **Inicio de sesión:** El sistema debe autenticar credenciales antes de permitir el acceso.
3. **Gestión de tareas/eventos:** Los usuarios podrán crear, editar y eliminar registros de su agenda.
4. **Visualización en calendario:** Las tareas deben mostrarse en un calendario interactivo.
5. **Recordatorios automáticos:** El sistema debe notificar al usuario sobre tareas próximas a vencer.

#### Validación
- Se revisaron los requerimientos del sistema con base en las funcionalidades esperadas.  
- Se confirmó la coherencia entre los casos de uso y los objetivos del proyecto.  
- Se verificó que las entradas, procesos y salidas sean lógicos y alcanzables.

#### Verificación
- Se analizó la viabilidad técnica con las tecnologías seleccionadas (HTML, CSS, JavaScript, Node.js y MongoDB).  
- Se evaluó la capacidad del sistema para cumplir los objetivos definidos en el cronograma.  
- Se propusieron mejoras en la organización y la estructura de la base de datos para optimizar el desarrollo futuro.

#### Conclusión
Con esta validación y verificación previa se asegura que el proyecto tiene una base sólida para su desarrollo, minimizando errores futuros y garantizando el cumplimiento de los objetivos planteados.
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


