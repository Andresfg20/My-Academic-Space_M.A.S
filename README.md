# My Academic Space
 
## Descripción del Proyecto
 
**My Academic Space** es una aplicación móvil orientada a la organización y gestión de actividades académicas para estudiantes y docentes. Permite administrar materias, actividades académicas, calificaciones, eventos, recordatorios, fechas importantes, calendario académico y promedio académico desde un espacio personal.
 
La aplicación busca responder de forma rápida y clara a tres preguntas cotidianas del usuario académico:
 
- ¿Qué debo hacer hoy?
- ¿Qué actividades tengo pendientes?
- ¿Cómo va mi progreso académico?
**My Academic Space no es un sistema institucional.** No reemplaza a Moodle, Google Classroom ni ningún sistema universitario. Es un organizador académico personal: cada usuario administra exclusivamente su propia información, y no existe interacción, mensajería ni gestión de cursos institucionales entre estudiantes y docentes.
 
Este proyecto se desarrolla en el marco de la asignatura de Programación Móvil, empleando Ionic, React y TypeScript, con una evolución técnica planificada hacia persistencia local (SQLite), consumo de API REST y despliegue en Android.
 
---
 
## Problema que Resuelve
 
En el día a día académico, la información relevante suele estar dispersa entre agendas físicas, notas sueltas, mensajes y plataformas institucionales que no siempre están pensadas para una consulta rápida y personal. Esto genera:
 
- Dificultad para tener una visión unificada de tareas, parciales y eventos pendientes.
- Pérdida de control sobre el progreso académico (calificaciones y promedio).
- Ausencia de una herramienta ligera y personal que no dependa de la infraestructura institucional.
- Falta de organización en la priorización de actividades según su fecha e importancia.
My Academic Space resuelve estos problemas ofreciendo un espacio personal, simple y accesible desde el móvil, donde el usuario centraliza y consulta su información académica sin fricción.
 
---
 
## Usuarios Objetivo
 
### Estudiante
 
Puede gestionar:
 
- Materias
- Tareas y parciales
- Calificaciones
- Recordatorios
- Calendario
### Docente
 
Puede gestionar:
 
- Materias
- Actividades académicas
- Eventos
- Recordatorios
- Calendario
> **Nota:** Estudiantes y docentes operan de manera completamente independiente. No existe comunicación, mensajería ni visibilidad cruzada entre usuarios.
 
---
 
## Objetivo General
 
Desarrollar una aplicación móvil que permita a estudiantes y docentes organizar, registrar y consultar de manera centralizada su información académica personal, facilitando el seguimiento de su progreso académico de forma sencilla, práctica y accesible.
 
---
 
## Objetivos Específicos
 
1. Diseñar un modelo de datos simple que represente las entidades académicas fundamentales (usuario, materia, actividad, calificación y evento).
2. Implementar un módulo de gestión de materias con horario, aula, créditos y color identificador.
3. Desarrollar un módulo de gestión de actividades académicas (tareas, quices, parciales, talleres, proyectos y exposiciones) con prioridad y estado.
4. Implementar un módulo de calificaciones que permita calcular el promedio académico por materia y de forma general.
5. Construir un dashboard que resuma dinámicamente la información de los demás módulos, sin almacenar datos propios.
6. Diseñar un calendario académico que permita visualizar actividades y eventos por fecha.
7. Establecer una arquitectura de proyecto en Ionic + React + TypeScript, escalable hacia SQLite y API REST en fases posteriores.
---
 
## MVP (Producto Mínimo Viable)
 
La primera versión del proyecto incluirá únicamente los siguientes módulos:
 
- **Dashboard**
- **Materias**
- **Actividades**
- **Calificaciones**
- **Calendario**
Cualquier funcionalidad fuera de este listado queda explícitamente excluida de la primera entrega, sin importar su relevancia potencial para versiones futuras.
 
---
 
## Funcionalidades Principales
 
- Registro y administración de materias (nombre, horario, aula, créditos, color).
- Gestión de actividades académicas por tipo: tarea, quiz, parcial, taller, proyecto y exposición.
- Registro de calificaciones por materia, con porcentajes y cálculo de promedio.
- Calendario con visualización de actividades y eventos por fecha.
- Dashboard con resumen de: materias del día, actividades pendientes, próximos parciales, promedio académico y próximos eventos.
- Gestión de recordatorios y fechas importantes.
- Diferenciación de funcionalidades según el rol del usuario (estudiante o docente).
---
 
## Funcionalidades Futuras
 
Estas funcionalidades quedan fuera del alcance del MVP y podrán evaluarse en versiones posteriores del proyecto:
 
- Persistencia local robusta mediante SQLite.
- Consumo de servicios mediante API REST.
- Notificaciones push avanzadas.
- Mejoras de experiencia de usuario basadas en el uso real de la aplicación.
- Adaptación y despliegue completo para Android mediante Android Studio.
**Quedan excluidas de forma permanente** del alcance del proyecto, por no ser coherentes con su naturaleza personal ni con el nivel académico de la asignatura: chat, videollamadas, inteligencia artificial, integración con Moodle, integración con Classroom, redes sociales y sistemas multiusuario avanzados.
 
---
 
## Beneficios de la Aplicación
 
**Para estudiantes:**
 
- Visión clara y centralizada de sus obligaciones académicas.
- Seguimiento en tiempo real de su promedio académico.
- Mejor priorización de tareas según fecha e importancia.
**Para docentes:**
 
- Organización personal de materias y actividades a cargo.
- Visualización rápida de eventos y fechas relevantes.
- Apoyo en la planificación de su carga académica.
**De carácter general:**
 
- Reducción de la dispersión de información académica.
- Herramienta ligera, sin dependencia de sistemas institucionales.
- Interfaz simple, adecuada para uso diario y consulta rápida.
---
 
## Tecnologías Previstas
 
**Tecnologías principales:**
 
- Ionic
- React
- TypeScript
**Tecnologías futuras:**
 
- SQLite (persistencia local)
- API REST (integración con backend)
- Android Studio (compilación y despliegue en Android)
**Herramientas de desarrollo:**
 
- Node.js
- npm
- Visual Studio Code
---
 
## Alcance del Proyecto
 
El proyecto abarca el diseño, desarrollo y documentación de una aplicación móvil funcional de organización académica personal, construida con Ionic, React y TypeScript, orientada a un único usuario por sesión (estudiante o docente).
 
No contempla comunicación entre usuarios, integración con sistemas institucionales ni funcionalidades colaborativas. El desarrollo se enmarca en un semestre universitario de la asignatura de Programación Móvil y cubre el ciclo completo del proyecto: análisis funcional, modelo de datos, diseño de interfaz (wireframes y mockups), navegación, estructura del proyecto en Ionic, operaciones CRUD locales, y evolución técnica hacia SQLite, API REST y Android como mejoras incrementales posteriores al MVP.
 
---
 
## Roadmap General
 
1. Definición de la idea y el MVP.
2. Documentación funcional (descripción, objetivos, usuarios, problemas que resuelve).
3. Historias de usuario y requerimientos (funcionales y no funcionales).
4. Casos de uso.
5. Modelo de datos.
6. Wireframes y mockups.
7. Definición de navegación.
8. Estructura del proyecto en Ionic + React + TypeScript.
9. Implementación de persistencia local con SQLite.
10. Implementación de operaciones CRUD.
11. Integración con API REST.
12. Adaptación y pruebas en Android mediante Android Studio.
13. Evaluación de mejoras futuras.
---
 
## Filosofía de Desarrollo
 
El desarrollo de **My Academic Space** sigue una metodología progresiva e incremental, propia de un proyecto académico de Programación Móvil, donde cada etapa se construye sobre la base sólida de la anterior:
 
1. **Documentación primero.** Antes de escribir código, se define con claridad el propósito del proyecto, sus usuarios, su alcance y su modelo de datos. Esta base conceptual evita decisiones improvisadas y asegura coherencia a lo largo de todo el desarrollo.
2. **Interfaz como segunda etapa.** Una vez definida la documentación, se diseña la experiencia visual e interactiva de la aplicación (wireframes, mockups y navegación), garantizando que la interfaz responda directamente a las necesidades identificadas en la fase anterior.
3. **Persistencia local como tercera etapa.** Con la interfaz definida, se incorpora el almacenamiento local de datos mediante SQLite, permitiendo que la aplicación funcione de manera autónoma y confiable sin depender aún de servicios externos.
4. **Integración mediante API REST como cuarta etapa.** Posteriormente, se habilita la comunicación con servicios externos a través de una API REST, ampliando las capacidades de la aplicación sin comprometer su simplicidad inicial.
5. **Adaptación para Android como etapa final.** Finalmente, el proyecto se ajusta y se prueba en el entorno Android mediante Android Studio, validando su funcionamiento como aplicación móvil completa.
Esta progresión —documentación, interfaz, persistencia local, integración con API REST y adaptación a Android— refleja un enfoque disciplinado y realista, apropiado para el desarrollo de una aplicación móvil dentro del contexto de un semestre universitario, priorizando siempre la simplicidad, la coherencia técnica y el cumplimiento gradual de los objetivos del proyecto.
 
