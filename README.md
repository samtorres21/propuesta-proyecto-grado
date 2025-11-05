#  Entrega Final: Gestión de Requerimientos de Software

##  Objetivo
Reunir todos los conocimientos adquiridos a lo largo del curso en un solo repositorio, integrando conceptos, prácticas y herramientas aplicadas en la gestión de requerimientos de software.

---

##  Temas Analizados

### 1. Conceptos básicos de gestión de requerimientos
Aprendí los fundamentos de la gestión de requerimientos, entendiendo la diferencia entre requerimientos funcionales y no funcionales, y su papel en el éxito de un proyecto de software. Realicé ejemplos prácticos para identificar y clasificar distintos tipos de requerimientos.

---

### 2. Importancia de la recolección de requisitos
Analicé la relevancia de esta fase inicial para comprender las verdaderas necesidades del cliente. Realicé ejercicios donde se aplicaron entrevistas y observaciones simuladas, garantizando que los requerimientos fueran claros y medibles.

---

### 3. Ciclo de vida de desarrollo de software
Estudié las diferentes etapas del ciclo de vida (planificación, análisis, diseño, implementación, pruebas y mantenimiento). Identifiqué cómo cada fase impacta la gestión de requerimientos y documenté ejemplos dentro del repositorio.

---

### 4. Técnicas de recolección de requisitos
Implementé diversas técnicas como entrevistas, encuestas y sesiones de lluvia de ideas. Elaboré un resumen comparativo de ventajas y desventajas de cada técnica, aplicando los conceptos a un caso práctico de software.

---

### 5. Diagramas de procesos e Ishikawa
Desarrollé diagramas de flujo para representar procesos y un diagrama de Ishikawa para identificar las causas principales de los problemas detectados. Esto permitió visualizar de manera más clara los puntos críticos del sistema.

---

### 6. Herramientas para reporte y seguimiento de requisitos (Jira)
Exploré el uso de **Jira** para la gestión de requerimientos y seguimiento de tareas. Creé historias de usuario, las prioricé en un tablero ágil y documenté capturas del proceso de planificación y seguimiento de avances.

---

### 7. Gestión de historias de usuario
Aprendí a formular historias bajo el formato **“Como [rol], quiero [acción], para [beneficio]”**, incluyendo criterios de aceptación. Creé historias para los roles de administrador y vendedor, definiendo valor, prioridad y estimación.

---

### 8. Retos y mejores prácticas en el agilismo
Reflexioné sobre los desafíos comunes al aplicar metodologías ágiles, como la comunicación constante, la planificación adaptativa y la mejora continua. Documenté las buenas prácticas que permiten mantener equipos colaborativos y productivos.

---

### 9. Definición de funcionalidades de un sistema
Identifiqué y documenté las funcionalidades principales del sistema, clasificándolas según los módulos y roles de usuario. Elaboré una estructura clara para entender qué hace el sistema y cómo se relacionan sus componentes.

---

### 10. Escritura de requisitos de usuario (historias de usuario)
Desarrollé un conjunto de **10 historias de usuario (5 de administrador y 5 de vendedor)** con sus criterios de aceptación, valor, prioridad y estimación. Este documento se encuentra incluido en la rama `historias-usuario` del repositorio.

---

### 11. Verificación y Validación (V&V) de requisitos
Analicé las técnicas de **verificación** (revisión, inspección, trazabilidad) y **validación** (prototipos, pruebas con usuarios). Apliqué un ejercicio práctico donde revisé que las historias cumplieran con criterios SMART (específicos, medibles, alcanzables, relevantes y temporales).

---

### 12. Requisitos no funcionales (ISO/IEC 25000 – SQuaRE)
Estudié los criterios de calidad definidos por la norma ISO/IEC 25000 (SQuaRE), como usabilidad, rendimiento, seguridad y mantenibilidad. Clasifiqué ejemplos de requisitos no funcionales y documenté cómo afectan la experiencia del usuario final.

---

##  Conclusión
Este repositorio representa la integración de todos los conocimientos teóricos y prácticos adquiridos en el curso **Gestión de Requerimientos de Software**. A través de las diferentes ramas, se evidencia la aplicación de metodologías ágiles, el uso de herramientas de seguimiento y la documentación estructurada de requisitos funcionales y no funcionales.

---
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


