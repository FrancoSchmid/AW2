# AW2
Proyecto TP1-TP4 – Aplicaciones Web II – Backend con Node.js + Express + CRUD + Seguridad

### 1.1. Equipo y roles

El equipo está conformado por cuatro integrantes con roles fijos que aportan claridad y responsabilidad durante todo el desarrollo del proyecto. Estos roles no rotan, pero las responsabilidades técnicas específicas sí rotan entre los TPs para garantizar que todos los miembros adquieran experiencia completa en backend (Node.js, Express, bases de datos y seguridad), tal como exige la orientación backend-heavy de la materia.

**Roles fijos:**

| Integrante   | Rol                                              |
|--------------|--------------------------------------------------|
| Franco       | Chief Project Orchestrator & Delivery Manager    |
| Joaquin      | Principal Software Architect & Technical Lead    |
| Tomas        | Full-Stack Integration Engineer                  |
| Baltazar     | Systems Quality & DevOps Specialist              |

**Rotación de responsabilidades técnicas por TP**  
(Esto asegura que cada integrante implemente código backend en todos los entregables y aprenda de lo realizado por los demás):

| TP  | Chief Project Orchestrator & Delivery Manager (Franco) | Principal Software Architect & Technical Lead (Joaquin) | Full-Stack Integration Engineer (Tomas) | Systems Quality & DevOps Specialist (Baltazar) |
|-----|--------------------------------------------------------|---------------------------------------------------------|-----------------------------------------|------------------------------------------------|
| TP2 | Configuración del servidor Express + rutas base        | Estructura de módulos y organización del proyecto       | Integración con MockAPI + fetch del front | Testing de endpoints + documentación           |
| TP3 | Implementación MVC + controladores                     | Diseño de la base de datos + modelos                    | CRUD completo (5 endpoints)             | Frontend de administración + integración       |
| TP4 | Variables de entorno + CORS                            | JWT + middleware de autenticación                       | Registro/login de usuarios + hashing bcrypt | Persistencia de usuarios en BD + testing de seguridad |

**Justificación de la rotación**: Permite que el conocimiento se comparta en tiempo real y que cada miembro domine todas las capas del backend, cumpliendo con el espíritu de la materia y preparando al equipo para el mundo profesional real.

### 1.3. Cronograma de avances y presentaciones

Se utilizará **GitHub Projects** con método Kanban como herramienta de organización de tareas (ver sección 1.4). El cronograma general de entregas es el siguiente:

- **TP1 – Propuesta por escrito**: Viernes [poné la fecha exacta de entrega]  
- **TP2 – Back-end para servir el sitio web**: [fecha que indique el profesor]  
- **TP3 – Creación del CRUD para administrar Front-End**: [fecha que indique el profesor]  
- **TP4 – Implementación de autenticación, accesos y seguridad**: [fecha que indique el profesor]  

Dentro de cada TP se definirán hitos semanales en el tablero Kanban (Backlog → To Do → In Progress → Review → Done) para mantener un flujo continuo y detectar cuellos de botella tempranamente.

### 1.4. Uso de una herramienta de seguimiento y de control de versiones

- **Control de versiones**: Git + GitHub (repositorio privado del grupo).  
  Se trabajará con branches por funcionalidad, Pull Requests obligatorios y revisión de al menos un compañero antes de mergear a main. Esto permite controlar los cambios y mantener la trazabilidad completa del proyecto.

- **Seguimiento y organización de tareas**: **GitHub Projects** con tablero Kanban.  
  **¿Por qué GitHub Projects y no Trello o Notion?** Porque el proyecto es 100 % código backend. Las tarjetas se convierten automáticamente en Issues y Pull Requests, por lo que no hay doble trabajo ni copiar-pegar links. Es la herramienta más profesional, gratuita y nativa para un equipo que va a escribir Node.js + Express durante todo el semestre.

**Flujo Kanban definido:**
- **Backlog** → ideas y tareas pendientes  
- **To Do** → tareas listas para tomar (con descripción clara y criterios de aceptación)  
- **In Progress** → máximo 2 tarjetas por persona (evita multitasking)  
- **Review** → código listo para revisión por pares  
- **Done** → mergeado y probado  

Esta combinación de Git + GitHub Projects cumple perfectamente con las consignas 1.3 y 1.4 y nos da visibilidad total del progreso en tiempo real.
