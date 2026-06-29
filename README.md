<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC" width="200"/>
</p>

<h1 align="center">UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</h1>
<h2 align="center">Facultad de Ingeniería</h2>
<h3 align="center">Carrera de Ingeniería de Software</h3>
<h3 align="center">1ASI0572- Desarrollo de soluciones IOT</h3>

<h2 align="center">Informe de Trabajo Final</h2>
<h3 align="center">Startup Celevi - Grotix </h3>
<p align="center"><strong>Docente:</strong> Marco Antonio León Baca</p>
<p align="center"><strong>Sección:</strong> 6772</p>

<h3 align="center">Integrantes</h3>

<div align="center">

| Código | Apellidos y Nombres |
|--------|---------------------|
| u202311157 | Binda Arbañil, Marcelo Alejandro |
| u202311701 | Castillo Garay, Ainhoa Lucía |
| u202312287 | Martel Andrade, Cassius Estefano |
| u20201F855 | Nakamurakare Teruya, Alex Tomio |
| U202312443 | Rodas Sotomayor, Ernesto |
</div>

<p align="center">202601</p>
<p align="center">Lima - Perú</p>
<p align="center">19 de junio de 2026</p>

<div style="page-break-after: always;"></div>

## Registro de versiones del informe

| Versión | Fecha | Autor(es) | Descripción de modificación |
|---|---|---|---|
| 1.0 AV1 | 11/04/2026 - 25/04/2026 | - Marcelo Alejandro Binda Arbañil<br>- Ainhoa Lucía Castillo Garay<br>- Cassius Estefano Martel Andrade<br>- Alex Tomio Nakamurakare<br>- Ernesto Rodas Sotomayor | Capítulo I: Introducción<br>Capítulo II: Requirements and Analysis<br>Capítulo III: Requirements Specification<br>Capítulo IV: Solution Software Design |
| 2.0 TP | 26/04/2026 - 14/05/2026 | - Marcelo Alejandro Binda Arbañil<br>- Ainhoa Lucía Castillo Garay<br>- Cassius Estefano Martel Andrade<br>- Alex Tomio Nakamurakare<br>- Ernesto Rodas Sotomayor | Capítulo V: Solution UI/UX Design<br>Capítulo VI: Product Implementation, Validation & Deployment - Sprint 1 |
| 3.0 AV2 | 15/05/2026 - 19/06/2026 | - Marcelo Alejandro Binda Arbañil<br>- Ainhoa Lucía Castillo Garay<br>- Cassius Estefano Martel Andrade<br>- Alex Tomio Nakamurakare<br>- Ernesto Rodas Sotomayor | Capítulo IV: Product Implementation, Validation & Deployment - Sprint 2<br>Validation Interviews |
| 4.0 TF | 21/06/2026 - 07/07/2026 | - Marcelo Alejandro Binda Arbañil<br>- Ainhoa Lucía Castillo Garay<br>- Cassius Estefano Martel Andrade<br>- Alex Tomio Nakamurakare<br>- Ernesto Rodas Sotomayor | Capítulo IV: Product Implementation, Validation & Deployment - Sprint 3 |

<div style="page-break-after: always;"></div>

## Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción del Startup](#111-descripción-del-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Nombre de producto](#121-nombre-de-producto)
    - [1.2.2. Antecedentes y Problemática](#122-antecedentes-y-problemática)
    - [1.2.3. Lean UX Process](#123-lean-ux-process)
      - [1.2.3.1. Lean UX Problem Statement](#1231-lean-ux-problem-statement)
      - [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
      - [1.2.3.3. Lean UX Hypothesis](#1233-lean-ux-hypothesis)
      - [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis Competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de Entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de Entrevistas](#223-análisis-de-entrevistas)
  - [2.3. NeedFinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Maps](#234-empathy-maps)
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Map](#32-impact-map)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flow Modeling](#4112-domain-message-flow-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagrams](#4131-software-architecture-system-landscape-diagrams)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.1. Bounded Context: Profile](#421-bounded-context-profile)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
    - [4.2.2. Bounded Context: Cultivation Area](#422-bounded-context-cultivation-area)
      - [4.2.2.1. Domain Layer](#4221-domain-layer)
      - [4.2.2.2. Interface Layer](#4222-interface-layer)
      - [4.2.2.3. Application Layer](#4223-application-layer)
      - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
      - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
        - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
    - [4.2.3. Bounded Context: Hardware Device](#423-bounded-context-hardware-device)
      - [4.2.3.1. Domain Layer](#4231-domain-layer)
      - [4.2.3.2. Interface Layer](#4232-interface-layer)
      - [4.2.3.3. Application Layer](#4233-application-layer)
      - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
      - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
        - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
    - [4.2.4. Bounded Context: Irrigation cycle](#424-bounded-context-irrigation-cycle)
      - [4.2.4.1. Domain Layer](#4241-domain-layer)
      - [4.2.4.2. Interface Layer](#4242-interface-layer)
      - [4.2.4.3. Application Layer](#4243-application-layer)
      - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
      - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
        - [4.2.4.6.2. Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)
    - [4.2.5. Bounded Context: Crop Analysis (AI)](#425-bounded-context-crop-analysis-ai)
      - [4.2.5.1. Domain Layer](#4251-domain-layer)
      - [4.2.5.2. Interface Layer](#4252-interface-layer)
      - [4.2.5.3. Application Layer](#4253-application-layer)
      - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
      - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams)
        - [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram)
    - [4.2.6. Bounded Context: Telemetry](#426-bounded-context-telemetry)
      - [4.2.6.1. Domain Layer](#4261-domain-layer)
      - [4.2.6.2. Interface Layer](#4262-interface-layer)
      - [4.2.6.3. Application Layer](#4263-application-layer)
      - [4.2.6.4. Infrastructure Layer](#4264-infrastructure-layer)
      - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams](#4265-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.6.6. Bounded Context Software Architecture Code Level Diagrams](#4266-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.6.6.1. Bounded Context Domain Layer Class Diagrams](#42661-bounded-context-domain-layer-class-diagrams)
        - [4.2.6.6.2. Bounded Context Database Design Diagram](#42662-bounded-context-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guide](#512-web-mobile-and-iot-style-guide)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization System](#521-organization-system)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
    - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
  - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Applications Wireframes](#541-applications-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
    - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
      - [Segmento Objetivo #2: Asociaciones Agrarias (Carlos Mendoza)](#segmento-objetivo-2-asociaciones-agrarias-carlos-mendoza)
  - [5.5. Applications Prototyping](#55-applications-prototyping)
  - [5.6. IoT Device Design](#56-iot-device-design)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
  - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
    - [6.2.1. Sprint 1](#621-sprint-1)
      - [6.2.1.1. Sprint Planning 1](#6211-sprint-planning-1)
      - [6.2.1.2. Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
      - [6.2.1.3. Sprint Backlog 1](#6213-sprint-backlog-1)
      - [6.2.1.4. Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
      - [6.2.1.5. Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
      - [6.2.1.6. Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
      - [6.2.1.7. Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
      - [6.2.1.8. Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
      - [6.2.1.9. Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
    - [6.2.2. Sprint 2](#622-sprint-2)
      - [6.2.2.1. Sprint Planning 2](#6221-sprint-planning-2)
      - [6.2.2.2. Aspect Leaders and Collaborators](#6222-aspect-leaders-and-collaborators)
      - [6.2.2.3. Sprint Backlog 2](#6223-sprint-backlog-2)
      - [6.2.2.4. Development Evidence for Sprint Review](#6224-development-evidence-for-sprint-review)
      - [6.2.2.5. Testing Suite Evidence for Sprint Review](#6225-testing-suite-evidence-for-sprint-review)
      - [6.2.2.6. Execution Evidence for Sprint Review](#6226-execution-evidence-for-sprint-review)
      - [6.2.2.7. Services Documentation Evidence for Sprint Review](#6227-services-documentation-evidence-for-sprint-review)
      - [6.2.2.8. Software Deployment Evidence for Sprint Review](#6228-software-deployment-evidence-for-sprint-review)
      - [6.2.2.9. Team Collaboration Insights during Sprint](#6229-team-collaboration-insights-during-sprint)
    - [6.2.3. Sprint 3](#623-sprint-3)
      - [6.2.3.1. Sprint Planning 3](#6231-sprint-planning-3)
      - [6.2.3.2. Aspect Leaders and Collaborators](#6232-aspect-leaders-and-collaborators)
      - [6.2.3.3. Sprint Backlog 3](#6233-sprint-backlog-3)
      - [6.2.3.4. Development Evidence for Sprint Review](#6234-development-evidence-for-sprint-review)
      - [6.2.3.5. Testing Suite Evidence for Sprint Review](#6235-testing-suite-evidence-for-sprint-review)
      - [6.2.3.6. Execution Evidence for Sprint Review](#6236-execution-evidence-for-sprint-review)
      - [6.2.3.7. Services Documentation Evidence for Sprint Review](#6237-services-documentation-evidence-for-sprint-review)
      - [6.2.3.8. Software Deployment Evidence for Sprint Review](#6238-software-deployment-evidence-for-sprint-review)
      - [6.2.3.9. Team Collaboration Insights during Sprint](#6239-team-collaboration-insights-during-sprint)
    - [6.2.4. Validation Interviews](#624-validation-interviews)
      - [6.2.4.1. Diseño de entrevistas](#6241-diseño-de-entrevistas)
      - [6.2.4.2. Registro de entrevistas](#6242-registro-de-entrevistas)
      - [6.2.4.3. Evaluaciones según heurísticas](#6243-evaluaciones-según-heurísticas)
- [Conclusiones](#conclusiones)
- [Recomendaciones](#recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
- [Links](#links)

<div style="page-break-after: always;"></div>

## Student Outcome
**ABET - EAC - Student Outcome 5**

**Criterio:** La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---|---|---|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Binda Arbañil, Marcelo Alejandro**<br>**AV1**<br>Desempeñó un rol de liderazgo técnico compartido, sincronizando los requerimientos de hardware con los modelos C4 y la topología IoT estructural.<br>**TP**<br>Articuló el trabajo de integración entre las áreas de hardware y software, mitigando fricciones técnicas en mesas de discusión colectivas.<br>**AV2**<br>Lideró el desarrollo frontend de la aplicación web e integró las reglas de inferencia visual en el Bounded Context de Crop Analysis.<br>**TF**<br>Desempeñó un rol de liderazgo técnico integrador a lo largo del proyecto, logrando sincronizar las restricciones del hardware IoT con los modelos arquitectónicos C4. Su dirección en el desarrollo frontend de la aplicación web y la integración del Bounded Context de Crop Analysis evidencian su capacidad para articular el trabajo entre distintas capas del software, mitigando fricciones técnicas mediante mesas de discusión colectivas que fortalecieron la cohesión del equipo.<br><br>**Castillo Garay, Ainhoa Lucía**<br>**AV1**<br>Dirigió de manera conjunta la delimitación estratégica de los Bounded Contexts aplicando principios de Domain-Driven Design (DDD).<br>**TP**<br>Guió la transición práctica de los modelos estructurales hacia el código fuente de los microservicios core (Profiles y Cultivation Area).<br>**AV2**<br>Lideró el desarrollo móvil en Flutter, implementando la lógica de autenticación JWT, flujo de pantallas y consumo de servicios cloud.<br>**TF**<br>Dirigió de manera conjunta la estrategia arquitectónica aplicando principios de Domain-Driven Design (DDD) para delimitar los Bounded Contexts. Su liderazgo fue fundamental durante la transición de los modelos estructurales hacia la implementación física, asumiendo la dirección del desarrollo móvil multiplataforma en Flutter, donde coordinó exitosamente la integración de flujos de autenticación y el consumo reactivo de servicios cloud junto al equipo de backend.<br><br>**Martel Andrade, Cassius Estefano**<br>**AV1**<br>Fomentó canales de comunicación equitativa durante el modelado inicial del dominio en las sesiones grupales de EventStorming.<br>**TP**<br>Facilitó las dinámicas de sincronización del equipo, distribuyendo de forma eficiente responsabilidades según áreas de especialidad.<br>**AV2**<br>Coordinó la evolución de la arquitectura del sistema a través de la ejecución y documentación de las iteraciones ADD 3, 4 y 5.<br>**TF**<br>Ejerció un liderazgo clave al fomentar canales de comunicación equitativa desde las sesiones iniciales de EventStorming hasta las iteraciones arquitectónicas de diseño (ADD). Su capacidad para distribuir responsabilidades según especialidad y coordinar la documentación técnica rigurosa (ADD 3, 4 y 5) garantizó una evolución ordenada del sistema, facilitando la sincronización técnica necesaria para orquestar microservicios y hardware físico.<br><br>**Nakamurakare Teruya, Alex Tomio**<br>**AV1**<br>Asumió la dirección del diseño y normalización del modelo de datos relacional para los contextos lógicos iniciales.<br>**TP**<br>Resolvió cuellos de botella críticos relacionados con la persistencia relacional durante la integración del API Gateway.<br>**AV2**<br>Dirigió la orquestación de APIs y esquemas distribuidos para asegurar la persistencia políglota entre MySQL y TimescaleDB.<br>**TF**<br>Asumió la dirección arquitectónica del ecosistema backend, liderando el diseño y normalización de los modelos de datos relacionales y distribuidos. Su capacidad para resolver colaborativamente cuellos de botella críticos, como la configuración de persistencia políglota (MySQL y TimescaleDB) y la integración del API Gateway, demostró un liderazgo técnico sólido enfocado en asegurar la escalabilidad y disponibilidad de los servicios cloud.<br><br>**Rodas Sotomayor, Ernesto**<br>**AV1**<br>Condujo la estructuración del Ubiquitous Language y la especificación de las Technical Stories como directrices de calidad.<br>**TP**<br>Coordinó sesiones de pair programming y revisión conjunta para resguardar la uniformidad.<br>**AV2**<br>Lideró la optimización del stack en la nube de Azure.<br>**TF**<br>Lideró la estructuración del Ubiquitous Language (Lenguaje Ubicuo) y la especificación de Technical Stories, estableciendo directrices de calidad claras para todo el equipo. Su coordinación de sesiones de pair programming y revisión conjunta garantizó la uniformidad del código, culminando con la dirección y optimización exitosa del stack tecnológico desplegado en la infraestructura de Azure. | **AV1**<br>El equipo consolidó un modelo de liderazgo técnico colaborativo al unificar las diversas competencias individuales. Esto permitió definir de manera colectiva la topología IoT y las fronteras de los contextos acotados del sistema.<br>**TP**<br>Se descentralizó la toma de decisiones técnicas mediante un esquema de supervisión cruzada. Los retos de mensajería asíncrona e integración en la nube se resolvieron mediante sesiones de diseño unificado y no como aportes aislados.<br>**AV3**<br>La sinergia del equipo permitió rotar orgánicamente el liderazgo según las necesidades del Sprint 2. El dominio compartido sobre microservicios, desarrollo móvil y visión artificial consolidó una solución resiliente y alineada a los estándares de producción de la industria.<br>**TF**<br>Como equipo, consolidamos un modelo de liderazgo técnico verdaderamente descentralizado y colaborativo, maximizando nuestras diversas competencias individuales. Desde la concepción de la topología IoT hasta el despliegue final del ecosistema (Edge-to-Cloud), las decisiones arquitectónicas y la orquestación de microservicios se resolvieron mediante esquemas de supervisión cruzada y sesiones de diseño unificado. La rotación orgánica del liderazgo según los retos del Sprint (desarrollo móvil, backend, firmware y visión artificial) nos permitió mitigar fricciones y construir una solución tecnológica resiliente, alineada con los estándares de producción de la industria. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Binda Arbañil, Marcelo Alejandro**<br>**AV1**<br>Planificó los hitos de entrega inicial empleando tableros visuales, garantizando un flujo estructurado de trabajo colaborativo.<br>**TP**<br>Monitoreó los plazos de desarrollo e integración mediante reuniones periódicas de seguimiento y sincronización técnica.<br>**AV2**<br>Adoptó de forma proactiva requerimientos de diseño responsivo y adaptabilidad de vistas basándose en el feedback del equipo.<br>**TF**<br>Garantizó un flujo de trabajo estructurado y transparente planificando los hitos de entrega mediante tableros visuales interactivos (Kanban). Su gestión proactiva al monitorear plazos de desarrollo e incorporar feedback continuo para adaptar vistas web responsivas, aseguró que las metas técnicas se cumplieran en los tiempos establecidos, fomentando un entorno de comunicación abierta y sincronización constante.<br><br>**Castillo Garay, Ainhoa Lucía**<br>**AV1**<br>Modeló la interacción de hardware y software a través de Context Maps, facilitando un entorno inclusivo de comprensión global.<br>**TP**<br>Estructuró los diagramas de componentes y clases del sistema definiendo metas a corto plazo para evitar retrasos.<br>**AV2**<br>Investigó e implementó de manera ágil componentes móviles reutilizables durante el Sprint, robusteciendo la consistencia de la interfaz.<br>**TF**<br>Fomentó un entorno inclusivo de comprensión global al modelar la interacción entre hardware y software mediante Context Maps. Estructuró eficazmente los diagramas de componentes definiendo metas a corto plazo, y mantuvo un enfoque ágil al investigar e implementar componentes móviles reutilizables. Esto previno retrasos y aseguró que el desarrollo de la aplicación móvil cumpliera con los objetivos de usabilidad y rendimiento del proyecto.<br><br>**Martel Andrade, Cassius Estefano**<br>**AV1**<br>Analizó con precisión las competencias individuales del equipo para estructurar una división de tareas equilibrada y eficiente.<br>**TP**<br>Replanteó la planificación del Sprint Backlog adaptándolo de forma dinámica a las restricciones reales de conectividad rural.<br>**AV2**<br>Incorporó buenas prácticas de arquitectura de software para asegurar la mantenibilidad a largo plazo de la plataforma de cara al usuario.<br>**TF**<br>Estructuró una división de tareas equilibrada y eficiente tras analizar con precisión las competencias individuales del equipo. Su flexibilidad para replantear la planificación del Sprint Backlog adaptándolo a restricciones físicas reales (como la conectividad intermitente IoT) y su enfoque en integrar buenas prácticas de ingeniería, aseguraron el cumplimiento de los objetivos garantizando la mantenibilidad a largo plazo de la plataforma de cara al usuario.<br><br>**Nakamurakare Teruya, Alex Tomio**<br>**AV1**<br>Integró las sugerencias técnicas de todos los integrantes dentro del Diagrama Global de Base de Datos para asegurar inclusividad.<br>**TP**<br>Mantuvo canales de comunicación abiertos y transparentes durante la fase crítica de despliegue de bases de datos relacionales.<br>**AV2**<br>Ajustó los esquemas distribuidos de telemetría y series de tiempo en Azure para satisfacer nuevas métricas analíticas del negocio.<br>**TF**<br>Aseguró la inclusividad técnica integrando las sugerencias de todos los miembros en el diseño global de la infraestructura de datos. Su habilidad para mantener canales de comunicación transparentes durante los despliegues críticos en Azure y su proactividad para ajustar esquemas de telemetría a nuevas métricas analíticas, fueron determinantes para cumplir los objetivos operativos del negocio sin sacrificar la estabilidad del entorno colaborativo.<br><br>**Rodas Sotomayor, Ernesto**<br>**AV1**<br>Facilitar el codiseño de los lienzos estratégicos de negocio (Lean UX Canvas) para alinear las metas académicas con las técnicas.<br>**TP**<br>Promovió talleres internos de revisión de código para asegurar la adaptabilidad del equipo frente a nuevas herramientas lógicas.<br>**AV2**<br>Optimizó los entornos de integración continua (CI/CD) en GitHub Actions, garantizando entregas de software estables y sin fallos.<br>**TF**<br>Promovió un entorno altamente adaptativo codiseñando los lienzos estratégicos de negocio (Lean UX Canvas) para alinear metas académicas y técnicas. Su iniciativa al facilitar talleres internos de revisión de código y su gestión para optimizar los flujos de Integración/Despliegue Continuo (CI/CD) en GitHub Actions, garantizaron entregas de software ágiles, estables y fieles a la planificación del equipo. | **AV1**<br>El grupo propició un espacio inclusivo unificado mediante herramientas visuales estratégicas (Lean UX, Context Maps). Esto facilitó que cada meta establecida contribuyera directamente a cimentar una solución IoT escalable.<br>**TP**<br>Se logró un cumplimiento del 100% de los objetivos trazados para el hito parcial mediante la estructuración del Sprint Backlog 1 con metas de corto plazo y revisiones semanales, integrando con éxito el flujo de maquetado con el despliegue cloud.<br>**AV3**<br>El equipo demostró una alta adaptabilidad y compromiso con el aprendizaje continuo frente a los desafíos del Sprint 2. La investigación conjunta, la resolución de cuellos de botella en la persistencia políglota y la automatización de despliegues en Azure validaron la madurez del equipo para cumplir con calidad de exportación los requerimientos del proyecto.<br>**TF**<br>Logramos un cumplimiento integral y exitoso de los objetivos del proyecto mediante una planificación táctica adaptativa. Fomentamos un entorno inclusivo al utilizar herramientas visuales estratégicas (EventStorming, Context Maps, Kanban) que garantizaron la participación de todos. Frente a desafíos complejos como la integración asíncrona, la persistencia políglota y los despliegues automatizados en Azure, nuestra capacidad para replantear el Sprint Backlog, establecer metas a corto plazo y mantener la comunicación constante demostró nuestra madurez para planificar, ejecutar y entregar un producto software-hardware con calidad de exportación. |

---

# CAPÍTULO I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción del Startup

Celevi es una startup de la Universidad Peruana de Ciencias Aplicadas (UPC) que impulsa la agricultura inteligente mediante Grotix, una plataforma IoT escalable diseñada para optimizar el riego a través de sensores de precisión y una arquitectura centralizada. Esta solución tecnológica maximiza la eficiencia hídrica y el rendimiento de las cosechas, sentando las bases para una modernización del agro peruano que garantice la producción de alimentos con estándares de calidad superiores.
El despliegue de esta plataforma contribuye directamente con los Objetivos de Desarrollo Sostenible 2 (Hambre Cero) y 3 (Salud y Bienestar), al fortalecer la seguridad alimentaria y fomentar una nutrición de mayor impacto en la población. Mediante la automatización y el uso de datos, la organización busca mitigar la hambruna y promover la salud pública, transformando la gestión de recursos agrícolas en un motor de bienestar social y sostenibilidad nacional.

* **Misión:** Impulsar la seguridad alimentaria y la sostenibilidad del agro peruano mediante Grotix, nuestra plataforma de agricultura inteligente. En Celevi, transformamos la gestión hídrica a través de tecnología IoT de precisión y analítica de datos, optimizando los recursos para garantizar cosechas de alta calidad que contribuyan directamente a la erradicación del hambre y al bienestar social.

* **Visión:** Ser el referente tecnológico de la modernización agrícola en el Perú y la región, liderando la transición hacia un modelo de producción eficiente y resiliente. Aspiramos a consolidar una red de agricultura inteligente que, alineada con los estándares globales de sostenibilidad, asegure la salud nutricional de la población y el uso responsable del agua para las futuras generaciones.

### 1.1.2. Perfiles de integrantes del equipo

| Nombre | Código | Carrera | Descripción |
|---|---|---|---|
| Binda Arbañil, Marcelo Alejandro <p align="center"> <img src="https://imgur.com/9XWdym2.jpg" alt="marcelo"> </p> | U202311157 | Ingeniería de Software | Mi nombre es Marcelo Binda y soy estudiante de séptimo ciclo de la carrera de Ingeniería de Software. Me defino como un profesional proactivo y orientado a resultados, con una capacidad natural para el trabajo colaborativo y la resolución de problemas complejos. Me caracteriza mi alto sentido de la responsabilidad y un compromiso inquebrantable con la calidad técnica en cada proyecto que emprendo. |
| Castillo Garay, Ainhoa Lucía <p align="center"> <img src="https://imgur.com/2UE04dl.jpg" alt="ainhoa"> </p> | U202311701 | Ingeniería de Software | Mi nombre es Ainhoa Castillo y estoy cursando mi séptimo ciclo en la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona activa y responsable. Me gusta trabajar en un ambiente tranquilo y divertido, pero siempre eficaz. Me gusta programar y resolver problemas mediante soluciones creativas. |
| Martel Andrade, Cassius Estefano <p align="center"> <img src="https://imgur.com/DNdObuQ.jpg" alt="cassius"> </p> | U202312287 | Ingeniería de Software | Mi nombre es Cassius Martel y soy estudiante de séptimo de la carrera de Ingeniería de Software. Me caracterizo por ser líder nato que siempre busca sacar lo mejor de cada uno de sus compañeros de equipo, así como por ser sumamente responsable y atento con los requerimientos de cada proyecto en el que me involucro. Tengo conocimientos técnicos en lenguajes como Python, Java, C++, así como en diversos frameworks de desarrollo Frontend, bases de datos y metodologías ágiles. |
| Nakamurakare Teruya, Alex Tomio <p align="center"> <img src="https://imgur.com/Z8IWHJL.jpg" alt="tomio"> </p> | U20201f855 | Ingeniería de Software | Mi nombre es Tomio Nakamurakare, estudiante de séptimo ciclo de la carrera de Ingeniería de Software. Me defino como un profesional en formación con una fuerte inclinación hacia el aprendizaje continuo y la aplicación práctica de nuevas tecnologías. Poseo una mentalidad orientada a la resolución de problemas complejos, viendo en los retos técnicos una oportunidad para fortalecer mi pensamiento crítico. |
| Rodas Sotomayor, Ernesto <p align="center"> <img src="https://imgur.com/PwXUZB1.png" alt="ernesto"> </p> | U202312443 | Ingeniería de Software | Mi nombre es Ernesto Rodas, soy estudiante de Ingeniería de Software, cursando actualmente el séptimo ciclo. Mi formación se enfoca en el desarrollo de soluciones tecnológicas y creación de software de calidad. Tengo experiencia en trabajo en equipo, desarrollo de proyectos académicos y creación de aplicaciones web básicas. Aportaré al equipo mi responsabilidad, creatividad, puntualidad y compromiso, además de mi disposición para seguir aprendiendo y contribuir al éxito del proyecto. |

## 1.2. Solution Profile
### 1.2.1. Nombre de producto
El nombre de nuestro proyecto, Grotix, proviene de la palabra growth en inglés, que significa crecimiento. Es la promesa básica del producto: asegurar que el cultivo crezca. Al usar la raíz "Gro", el usuario asocia instantáneamente la plataforma con vitalidad y resultados agrícolas. Por otro lado, el sufijo -tix evoca tecnología y analítica. En el mundo de las startups, la "X" final simboliza exponencialidad, precisión y el eje de coordenadas de los datos (la intersección entre el software y la tierra). Esta combinación resulta en un nombre conciso, de alta recordación y con una sonoridad moderna, proyectando una imagen de innovación y eficiencia en la gestión de recursos naturales.

### 1.2.2. Antecedentes y Problemática
La agricultura en el Perú enfrenta un manejo deficiente del recurso hídrico debido a la carencia de tecnología moderna de irrigación en los predios, lo que genera una baja eficiencia operativa agravada por pérdidas en la conducción y distribución. Según el Programa Subsectorial de Irrigaciones (PSI), del área agrícola explotada en el país, el 68% (3'747,908 hectáreas) se encuentra bajo régimen de secano, mientras que solo el 32% (1'729,068 hectáreas) cuenta con infraestructura de riego.

La infraestructura actual presenta deficiencias estructurales críticas: de acuerdo con el PSI, el 82% de las unidades agropecuarias poseen canales sin revestimiento y el 97.4% de las tierras irrigadas lo hacen exclusivamente mediante el método de gravedad. Esta situación se refleja en que, según el reporte del PSI, solo el 2.5% (128,220 hectáreas) del área agrícola total del país utiliza sistemas de riego tecnificado.

Esta precariedad tecnológica impacta directamente en el desperdicio del agua. Según Carlos Pagador Moya, jefe de la Autoridad Nacional del Agua (ANA), cerca del 80% del volumen de agua destinado al uso agrícola a nivel nacional se pierde al año por deficiencias en los sistemas de riego; esto equivale a la pérdida de 12,846 millones de metros cúbicos (MMC) de los 16,058 MMC destinados anualmente al sector.

En un contexto regional, la problemática de la ineficiencia hídrica es persistente. Según datos de la Comisión Nacional del Agua (Conagua) reportados por Excélsior Digital, el sector agrícola y ganadero desperdicia el 57% del agua debido a infraestructura obsoleta, fugas o sistemas en mal estado. De acuerdo con este mismo reporte, las pérdidas por factores como la infiltración y evaporación pueden ascender a más del 60% del agua almacenada para fines agrícolas.

Ante este escenario, donde las eficiencias promedio de riego en el país apenas varían entre el 30% y 35%, Grotix surge como una herramienta estratégica para revertir los bajos niveles de rendimiento y producción. Mediante la automatización basada en datos de humedad y temperatura, el sistema busca mitigar las pérdidas por conducción y aplicación, optimizando el uso de un recurso cuya disponibilidad per cápita en el Perú es una de las más altas de la región, pero cuya gestión actual es ineficiente.

Para comprender la magnitud de la intervención de Celevi, es imperativo desglosar la realidad del agro peruano utilizando el marco analítico de las 5 'W' y 2 'H'. Este enfoque permite identificar no solo el síntoma del problema, sino sus raíces estructurales y los mecanismos de solución que Grotix implementará.

#### Qué: Definición del Problema y su Relación con la Persona (What)

**¿Cuál es el problema?**

El problema central es la gestión ineficiente y precaria del recurso hídrico en la agricultura peruana, exacerbada por la falta de tecnificación en la toma de decisiones. El agricultor promedio riega sus cultivos basándose en calendarios fijos o en la observación visual, sin conocer el estado hídrico real del suelo o las necesidades metabólicas de la planta en su etapa fenológica específica (Garay, 2009). Esto resulta en una sobre-irrigación que lixivia nutrientes o en un déficit que reduce drásticamente el rendimiento (Ramos, 2025).

**¿Cuál es la relación con la persona en cuestión?**

La relación con la persona es directa y multidimensional. Para el productor, esta ineficiencia se traduce en pobreza: la pérdida de cultivos prolonga el ciclo de vulnerabilidad de familias donde el 27.5% vive por debajo del umbral de pobreza (Pontificia Universidad Católica del Perú, 2024).  Para el consumidor final, el problema se manifiesta en la inseguridad alimentaria; en 2023, la inseguridad alimentaria grave afectó a 1 de cada 5 peruanos debido a la contracción de la producción agrícola por condiciones climáticas extremas (Sociedad de Comercio Exterior del Perú, 2024).  Existe un vínculo intrínseco entre la productividad hídrica y la nutrición infantil: la expansión del riego tecnificado en zonas con estrés hídrico tiene el potencial de mejorar sustancialmente los indicadores de nutrición, siempre que se maneje con criterios de sostenibilidad (United Nations University Institute for Water, Environment and Health, s. f.). 

#### Quién: Actores Involucrados y Afectados (Who)
**¿Quiénes están involucrados?**

El ecosistema de la problemática hídrica en el Perú involucra a múltiples actores con roles diferenciados pero interconectados.
1. **Pequeños y Medianos Agricultores:** Son los actores principales a quienes les sucede el problema. Escobal, Trivelli y Revesz (2006) señalan que representan unidades agropecuarias donde menos del 8% posee más de 20 hectáreas. Se trata de un sector altamente heterogéneo, con una fuerte presencia de agricultura familiar que produce el 70% de los alimentos del país (Instituto Nacional de Estadística e Informática, 2024).
2. **Asociaciones Agrarias y Cooperativas:** Estas organizaciones permiten que los pequeños productores superen la fragmentación de la tierra, consolidando volúmenes de carga necesarios para el mercado internacional. Funcionan como el nexo técnico que garantiza el cumplimiento de estándares globales, supervisando que el uso del agua y los insumos cumplan con las exigencias de los compradores externos. 
3. **Hogares con Jefatura Femenina:** Son los más vulnerables ante la crisis agraria, enfrentando mayores dificultades para reducir la pobreza y mantener la actividad ante choques climáticos (Montaño, 2023).
4. **Niñez Rural:** Es la población más afectada indirectamente. Rivadeneira (2024) afirma que el acceso inadecuado a agua segura y la baja productividad agrícola resultan en desnutrición crónica (11.7% a nivel nacional) y anemia.
5. **Entidades Estatales:** El Ministerio de Desarrollo Agrario y Riego (MIDAGRI) y la Autoridad Nacional del Agua (ANA) son responsables de la política hídrica, pero enfrentan desafíos de ejecución presupuestal, habiendo ejecutado solo el 31.6% del presupuesto para emergencias en periodos críticos (Montaño, 2023).


#### Dónde: Localización Geográfica de la Problemática (Where)

**¿Dónde surge el problema?**

El estrés hídrico y la ineficiencia no se distribuyen uniformemente, sino que presentan matices regionales críticos.
* **La Costa:** Es una de las zonas con mayor estrés hídrico extremadamente alto, donde se extrae más del 80% del suministro de agua disponible (Centro Nacional de Planeamiento Estratégico, s. f.). Según Iberico (2016), concentra la mayor demanda para agroexportación y ciudades, pero dispone de menos del 2% del agua del país.
* **La Sierra Sur:** Regiones como Puno, Cusco, Huancavelica y Ayacucho enfrentan sequías severas. En Puno, el nivel del Lago Titicaca ha mostrado una tendencia alarmante al descenso debido al Niño Costero, afectando la siembra de quinua y otros cultivos altoandinos (AgroPerú, 2024).
* **La Selva Norte:** Aunque es una zona de alta precipitación, regiones como San Martín han empezado a emitir gritos de alerta por estrés hídrico, evidenciando que la mala gestión forestal y climática afecta incluso a las zonas tradicionalmente ricas en agua.

#### Cuándo: Temporalidad del Problema y Uso del Producto (When)
**¿Cuándo sucede el problema?**

El problema sucede de forma cíclica y se agrava en ventanas temporales específicas. De acuerdo con Pintado (2022), el déficit hídrico es una amenaza constante durante la campaña agrícola que suele iniciar entre agosto y diciembre para cultivos como la papa y el maíz. Es en estos meses cuando la escasez de lluvias retrasa las siembras y pone en riesgo la seguridad alimentaria del año siguiente.

**¿Cuándo utiliza el cliente el producto?**

El cliente (agricultor) utiliza Grotix de manera continua, pero el valor del producto se maximiza en los siguientes momentos:
1. **Periodo de Estiaje:** Cuando el agua de los reservorios es limitada y cada gota debe ser contabilizada.
2. **Fases Críticas del Cultivo:** Durante la floración y el llenado de tubérculos o granos, donde el estrés hídrico es fatal para el rendimiento (Garay Canales, 2009).
3. **Fenómenos Extremos:** Ante la llegada de olas de calor o retrasos de lluvias, la plataforma permite una respuesta inmediata ajustando el riego automáticamente según los datos de los sensores de luz solar y temperatura.

#### Por qué: Causas Raíz del Problema (Why)
**¿Cuál es la causa del problema?**

Las causas de la ineficiencia hídrica en el Perú son estructurales y ambientales:
* **Cambio Climático y Retroceso Glaciar:** Los glaciares tropicales del Perú, fuente de agua para la costa y sierra, han retrocedido un 40%, lo que reduce la disponibilidad de agua en la estación seca (Linares Nima, 2025).
* **Obsolescencia Tecnológica:** Según Iberico (2016), la persistencia del riego por gravedad o inundación, que desperdicia el 65% del agua aplicada, se debe a la falta de capital para invertir en sistemas presurizados. Las alternativas de solución existentes, como los sistemas de goteo automatizados importados, presentan barreras de entrada críticas: costos instalados que superan los US$ 3,500/ha y una alta dependencia de soporte técnico especializado ausente en zonas rurales (Ramos, 2025).
* **Falta de Información en Tiempo Real:** El agricultor no cuenta con datos sobre la evapotranspiración real de su cultivo ni la humedad en la zona radicular, lo que impide un riego de precisión (Ramos, 2025).
* **Subvaloración del Agua:** La retribución económica por el uso del agua en la agricultura es extremadamente baja (S/ 1 a S/ 3 por mil m³), lo que no incentiva el ahorro ni la inversión en tecnología (Iberico, 2016).
* **Baja Adopción de TIC:** Como menciona Nagel (2012), barreras como la dispersión poblacional y la orografía compleja han dificultado históricamente la llegada de soluciones IoT al campo, aunque la cobertura 4G está cerrando esta brecha. 

#### Cómo: Condiciones de Uso del Producto (How)
**¿En qué condiciones los clientes utilizan nuestro producto?**

Los usuarios operan en entornos de alta dispersión y orografía compleja. Grotix aprovecha la expansión de la red 4G rural (MTC, 2025) y la autonomía energética mediante paneles solares.

**¿Qué estrategia se considera antes de plantear la solución?**

Antes del despliegue técnico, la estrategia de Celevi contempla una fase de diagnóstico de compatibilidad edafoclimática. Según Nagel (2012), la transferencia tecnológica en el agro solo es efectiva si se precede de un análisis de la capacidad de campo y el punto de marchitez permanente específico de la zona. Por ello, la solución no se limita a la instalación de hardware, sino que incluye una configuración personalizada basada en la textura del suelo y el historial de precipitaciones local, asegurando que la automatización responda a una línea base científica y no solo a eventos aislados de humedad.

**¿Cómo nos conocieron los compradores?**

El descubrimiento de soluciones como Grotix sigue tres canales principales en el Perú:
* **Integración en Cadenas de Valor:** El 59.5% de pequeños productores vende a grandes empresas agroexportadoras, las cuales actúan como canal de difusión al brindar asistencia técnica y capacitación (44.2%) sobre nuevas tecnologías a sus proveedores.
* **Alianzas y Ferias Tecnológicas:** Los compradores suelen identificar estas herramientas a través de instituciones públicas (MIDAGRI), gremios (ProHass) y ferias especializadas donde se demuestran resultados concretos en campo.
* **Modelos de Proximidad:** La presencia local a través de redes de "Casas Agros" o centros de innovación universitarios (como el ecosistema UPC) genera la confianza necesaria para que el agricultor adopte el sistema mediante pruebas piloto o recomendaciones de sus cooperativas.

#### Cuánto: Estadísticas y Sustentación Numérica (How Much)
**Tabla 1.** _Eficiencia y Costos de Métodos de Riego en el Perú_

|Método de Riego|Eficiencia de Aplicación|Costo de Inversión (US$/ha)|Predominancia en el Agro|
|---|----|----|---|
|Gravedad / Surcos|35%|400|~85% en la costa|
|Aspersión|75%|2,600 - 4,115|2%|
|Goteo (Presurizado)|90%|2,775|13%|

_Nota. Adaptado de Abastecimiento de agua para la agricultura en la costa, por J. Iberico (2016), Revista Moneda, (168), Banco Central de Reserva del Perú, [BCRP](https://www.bcrp.gob.pe/docs/Publicaciones/Revista-Moneda/moneda-168/moneda-168-07.pdf?utm_source=chatgpt.com)_

Existe una relación inversa entre la predominancia del método y su eficiencia. El riego por gravedad, aunque es el más económico (US$ 400/ha), desperdicia el 65% del agua y domina el 85% del agro nacional. El sistema Grotix apunta a cerrar esta brecha permitiendo que, a través de la automatización e IoT, los agricultores migren hacia eficiencias del 90-95% (similares al goteo) optimizando la inversión tecnológica.

**Tabla 2.** _Indicadores de Salud y Seguridad Alimentaria (ODS 2 y 3)_

|Indicador|Valor (2022-2023)|Tendencia / Estado|
|---|----|---|
|Prevalencia de Anemia (niños < 3 años)|42.4%|Al alza (Incremento vs 2021)|
|Desnutrición Crónica Infantil|11.7%|Estancamiento|
|Incidencia de Déficit Calórico|36.2%|Al alza (era 23.9% en 2015)|
|Población Rural con Alta Inseguridad Alimentaria|> 70%|Crítica|

_Nota. Adaptado de Perú: Indicadores de Resultados de los Programas Presupuestales. Encuesta Demográfica y de Salud Familiar (ENDES) 2023, por el Instituto Nacional de Estadística e Informática (2024), [INEI](https://www.inei.gob.pe/?utm_source=chatgpt.com); de Sistema de monitoreo y seguimiento de los indicadores de los Objetivos de Desarrollo Sostenible, por el Instituto Nacional de Estadística e Informática (2023), [INEI ODS](https://ods.inei.gob.pe/ods/?utm_source=chatgpt.com); de El estado de la seguridad alimentaria y la nutrición en el mundo (SOFI) 2024, por la Organización de las Naciones Unidas para la Alimentación y la Agricultura (2024), [FAO SOFI](https://www.fao.org/publications/sofi/es/?utm_source=chatgpt.com); y de Índice Global del Hambre (IGH) 2024: Informe Perú, por el Centro Peruano de Estudios Sociales (2024), [CEPES](https://cepes.org.pe/?utm_source=chatgpt.com)_

Los datos muestran que el Perú se aleja de las metas de los ODS para 2030. La anemia infantil ha escalado al 42.4%, mientras que más de un tercio de la población sufre déficit calórico. Estas cifras validan la necesidad de Grotix: una agricultura ineficiente genera alimentos de menor calidad y mayor costo, impactando directamente en la nutrición de las familias rurales más vulnerables.

### 1.2.3. Lean UX Process
#### 1.2.3.1. Lean UX Problem Statement

##### Problem Statement 1: Productividad Agrícola

El rubro de la agricultura de precisión en el Perú enfrenta una brecha tecnológica crítica donde el 85% de los productores depende del riego por gravedad, desperdiciando el 65% del agua aplicada. Para nuestro segmento inicial de pequeños y medianos agricultores, los principales puntos de dolor se centran en decisiones basadas en la observación empírica, lo que genera una gestión precaria del recurso y una reducción del 30% en el rendimiento de las cosechas. Esta ineficiencia limita su competitividad y ven comprometida su seguridad alimentaria y estabilidad económica ante el cambio climático.

La oportunidad que la startup Celevi desea aprovechar radica en democratizar el acceso al IoT, dado que las alternativas actuales fallan al ser "ciegas" o económicamente prohibitivas para el campo local. Nuestra visión y estrategia es implementar Grotix como una plataforma que unifique sensores de bajo costo e Inteligencia Artificial para transformar la gestión hídrica en una ventaja competitiva sostenible. Al optimizar el metabolismo de la planta con datos exactos, buscamos que el agricultor deje de ser un sujeto pasivo del clima para convertirse en un gestor de datos eficiente, contribuyendo directamente al cumplimiento del ODS 2 (Hambre Cero).

¿Cómo podemos diseñar un ecosistema unificado que optimice el uso del agua en un 95% bajo las restricciones de conectividad rural limitada, falta de red eléctrica estable y la baja alfabetización digital del usuario? El propósito es garantizar que la tecnología de Grotix actúe como un motor de resiliencia productiva en las parcelas más vulnerables del país. La solución debe ser lo suficientemente robusta para operar en orografías complejas, asegurando que cada gota de agua se traduzca en una mayor disponibilidad de alimentos de calidad para la población peruana.

##### Problem Statement 2: Calidad Alimentaria y Competitividad Asociativa

En el ámbito de la agricultura familiar en el Perú, existe una correlación crítica entre la precaria gestión del riego y la baja densidad nutricional de los alimentos producidos, lo que contribuye a índices de anemia infantil del 42.4% en zonas rurales. Las asociaciones agrarias y cooperativas enfrentan la dificultad de no contar con herramientas para estandarizar la calidad de sus cosechas, lo que limita su acceso a mercados de mayor valor y compromete la seguridad alimentaria de las familias de sus asociados. Actualmente, la falta de datos técnicos impide que estas organizaciones certifiquen la calidad de sus productos, manteniendo a sus integrantes en un ciclo de baja rentabilidad y salud nutricional deficiente.

La oportunidad para Celevi radica en ofrecer a las asociaciones una infraestructura de monitoreo que conecte la productividad del campo con el ODS 3 (Salud y Bienestar). Nuestra visión es que las asociaciones adopten Grotix como una herramienta de gestión colectiva para estabilizar la oferta de alimentos superiores y reducir la dependencia de fuentes de agua contaminadas. Al tecnificar el riego de sus socios, las cooperativas pueden transformar su capacidad productiva en un impacto directo sobre el bienestar físico de sus comunidades, posicionando sus productos como alimentos de alta calidad nutricional tanto para el consumo interno como para la exportación que realizan a comercio externo.

¿Cómo podemos asegurar que la implementación de Grotix a través de asociaciones agrarias mejore los indicadores de salud y competitividad, superando las restricciones de la baja alfabetización digital de los socios? El objetivo es diseñar una solución escalable que permita a las asociaciones monitorear y garantizar el impacto de la agricultura inteligente en la calidad de vida de sus miembros.

#### 1.2.3.2. Lean UX Assumptions
**Features**
* Monitoreo Multivariable: Sensores de alta precisión para medir temperatura ambiental, humedad relativa, humedad del suelo y niveles de luz solar.
* Identificación Inteligente de Cultivos: Módulo de visión artificial integrado en el microcontrolador que reconoce automáticamente el tipo de planta para ajustar parámetros de riego específicos.
* Configuración Dual de Cultivo: Capacidad de configuración manual de cultivos para casos donde la cámara no sea el método preferido.
* Riego Automático Adaptativo: Sistema de bombeo con lógica de rango ajustable que se activa según las necesidades metabólicas de la planta y las condiciones del entorno.
* Control de Riego Manual/Remoto: Función de activación manual desde la aplicación para intervenciones directas del usuario.
* Dashboard de Telemetría en Tiempo Real: Visualización detallada del estado del ambiente de cultivo y gestión del modo de riego a través de una aplicación móvil y web.

**Business Outcomes**
* Eficiencia Hídrica: Lograr una reducción del desperdicio de agua de hasta un 60% en comparación con el riego por gravedad tradicional.
* Optimización del Rendimiento: Incrementar la productividad de las cosechas en un 25-30% mediante el mantenimiento de niveles óptimos de humedad.
* Escalabilidad de Mercado: Lograr la adopción del sistema en al menos 7 asociaciones agrarias durante el primer año de operación.
* Definition of Done: El proyecto se considera exitoso cuando el hardware logra ejecutar el riego de forma autónoma basándose en la identificación por IA y el usuario recibe los datos correctamente en la aplicación en un entorno de baja latencia.

**User benefits**
* Ahorro de Tiempo y Esfuerzo: Automatización de una de las tareas más críticas y demandantes de la agricultura.
* Seguridad y Resiliencia: Prevención de pérdida de cultivos ante fenómenos climáticos inesperados (olas de calor o sequías).
* Empoderamiento basado en Datos: Acceso a información técnica que antes era inaccesible para el pequeño productor, mejorando su toma de decisiones.
* Mejora de la Calidad de Vida: Al asegurar cosechas más sanas, se garantiza la seguridad alimentaria del hogar y un ingreso económico más estable.

**Análisis de Assumptions**
1. Creo que mis usuarios desean una solución integral que les permita gestionar sus cultivos de manera tecnificada sin requerir conocimientos avanzados en ingeniería o agronomía, eliminando la incertidumbre del riego empírico.
2. Esto se puede resolver mediante Grotix gracias a su sistema de sensores que monitorean el suelo y ambiente en tiempo real, sumado a la cámara con Inteligencia Artificial que automatiza las decisiones de riego según la planta detectada, cerrando la brecha entre la tecnología IoT y la labor de campo.
3. Mis usuarios iniciales son productores independientes de pequeña escala (especialmente aquellos con baja alfabetización digital) y asociaciones agrarias que buscan profesionalizar la producción de sus socios para mejorar su rentabilidad y salud.
4. El valor #1 que un usuario quiere de Grotix es la garantía de que sus plantas recibirán el agua exacta que necesitan para no morir ni desperdiciar recursos, asegurando la rentabilidad de su inversión.
5. El usuario también puede obtener el beneficio adicional de recibir alertas preventivas sobre condiciones ambientales extremas, permitiéndole actuar antes de que el cultivo sufra daños irreversibles.
6. Voy a adquirir la mayoría de mis usuarios mediante alianzas estratégicas con cooperativas agrarias y municipalidades rurales, demostraciones de campo presenciales para romper la barrera de desconfianza tecnológica, y contenido educativo en redes sociales sobre los beneficios del riego de precisión y cumplimiento de los ODS.
7. Haré dinero a través de la venta de kits de hardware (nodos y actuadores) bajo un modelo de compra única y un modelo de suscripción mensual (SaaS) para el almacenamiento de datos históricos avanzados y soporte técnico especializado.
8. Mi competencia principal son otras plataformas que ofrecen sistemas de riego presurizado convencionales sin inteligencia de datos y soluciones extranjeras de alto costo que no están adaptadas a la orografía ni conectividad peruana.
9. Los venceremos ofreciendo un producto de bajo costo diseñado específicamente para la realidad rural del Perú (autónomo energéticamente y con interfaz simplificada) y mediante el valor agregado de la identificación automática de plantas por IA.
10. Mi mayor riesgo de producto es que la baja alfabetización digital de los agricultores dificulte la adopción inicial o que las condiciones climáticas extremas dañen el hardware en campo.
11. Resolveremos esto mediante un diseño de hardware con protección industrial (IP67) y una interfaz de usuario extremadamente visual e intuitiva en la aplicación, minimizando la curva de aprendizaje mediante asistencia técnica local.

**Preguntas Finales**

_¿Quién es el usuario?_ El agricultor independiente que busca simplificar su trabajo diario y los líderes técnicos de asociaciones agrarias que necesitan visibilidad sobre la producción colectiva.

_¿Dónde encaja nuestro producto, en su trabajo o en su vida?_ Encaja directamente en su trabajo diario (gestión de parcelas), pero impacta su vida al asegurar el sustento económico y la salud alimentaria de su familia.

_¿Qué problemas tiene nuestro producto y cómo se puede resolver?_ La dependencia de conectividad 4G. Se resuelve implementando protocolos de comunicación de largo alcance y bajo consumo como LoRaWAN para zonas con baja señal celular.

_¿Cuándo y cómo es usado nuestro producto?_ Se usa 24/7 de forma pasiva (monitoreo y riego automático) y de forma activa cuando el agricultor revisa la aplicación para consultar alertas o activar el riego manual.

_¿Qué características son importantes?_ La precisión de los sensores de humedad del suelo, la efectividad del reconocimiento de plantas por IA y la durabilidad de la batería.

_¿Cómo debe verse nuestro producto y cómo comportarse?_ Debe verse robusto y profesional en hardware; en software, la interfaz debe ser limpia, usar íconos claros y colores que evoquen naturaleza y eficiencia, comportándose de manera ágil y predictiva.

#### 1.2.3.3. Lean UX Hypothesis
##### Hypothesis Statement 1: Eficiencia Hídrica y Ahorro de Costos

Creemos que, al automatizar el riego mediante una red de sensores IoT de humedad, temperatura y luz solar para los agricultores independientes y asociaciones agrarias, lograremos una reducción del 60% en el desperdicio de agua y una optimización de los costos operativos por campaña. Sabremos que esto es cierto cuando veamos que los agricultores reducen sus gastos de facturación hídrica o consumo de reservorios en un 40% durante el primer semestre de uso.

##### Hypothesis Statement 2: Precisión mediante Inteligencia Artificial

Creemos que, al implementar un módulo de visión artificial para la identificación automática de cultivos y fases fenológicas para agricultores con baja alfabetización digital o alta diversidad de siembra, lograremos eliminar el error humano en la configuración del riego y asegurar que cada planta reciba el aporte hídrico exacto según su especie. Sabremos que esto es cierto cuando veamos una tasa de éxito del 95% en la autonomía del sistema sin necesidad de intervención manual por parte del usuario en la aplicación.

##### Hypothesis Statement 3: Impacto en Salud Nutricional (ODS 3)

Creemos que, al estabilizar los niveles de hidratación y nutrientes de los cultivos mediante el riego de precisión de Grotix para los campos de cultivo de agricultores y asociaciones agrarias, lograremos una mejora en la calidad nutricional de los alimentos producidos y una reducción en la dependencia de fuentes de agua contaminadas. Sabremos que esto es cierto cuando veamos un incremento en el peso y calidad de la cosecha por hectárea, permitiendo a las familias acceder a productos más densos en nutrientes.

##### Hypothesis Statement 4: Gestión de Salud Pública Regional

Creemos que, al ofrecer una plataforma de monitoreo centralizada para asociaciones agrarias, lograremos que estas organizaciones certifiquen la calidad de sus cultivos y mejoren la salud alimentaria de sus socios. Sabremos que esto es cierto cuando veamos que las asociaciones logran vender sus productos en mercados de mayor valor o firmen acuerdos de suministro basados en datos de calidad nutricional.

#### 1.2.3.4. Lean UX Canvas

![Lean UX Canvas1](https://imgur.com/ReqQAIL.png)
![Lean UX Canvas2](https://imgur.com/wRBKets.png)

Celevi. 2026. _Lean UX Canvas_. https://docs.google.com/document/d/1v9oqi4oCp-7cLg5QIZMB1egRKy5mVaJw/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true

## 1.3. Segmentos objetivo

Con el objetivo de atraer eficazmente a futuros usuarios y brindar un producto que responda de manera precisa a sus necesidades, se han identificado los siguientes dos segmentos objetivo.

### Productores Independientes de Pequeña y Mediana Escala

Este segmento constituye el corazón de Grotix y abarca a los agricultores que gestionan sus parcelas de forma individual. Incluye tanto a productores habituados a técnicas empíricas heredadas, que presentan baja familiaridad con herramientas digitales, como a aquellos que buscan modernizarse. El objetivo principal para este grupo es democratizar la tecnología para que deje de ser un privilegio de las grandes agroindustrias. Se busca mejorar su calidad de vida al eliminar el esfuerzo físico del riego manual y la incertidumbre de perder su sustento por errores de cálculo hídrico, transformando su labor diaria en una actividad más segura, rentable y menos demandante.

#### Aspectos demográficos:
* **Sexo:** Masculino y femenino.
* **Rango de edad:** 20 a 70 años.
* **Nivel socioeconómico:** Clases B y C. Productores que dependen directamente de su cosecha para la estabilidad económica del hogar.

#### Aspectos geográficos:
* **Nacionalidad:** Peruana.
* **Zona geográfica:** Zonas rurales y periurbanas de la Costa, Sierra y Selva, especialmente en valles con acceso limitado a recursos hídricos.

#### Aspectos psicográficos:
* **Intereses:** Seguridad alimentaria familiar, reducción de la fatiga física, estabilidad de ingresos y preservación de sus tierras para futuras generaciones.
* **Estilo de vida:** Basado en el esfuerzo físico constante y el respeto por los ciclos de la naturaleza. Valoran la tecnología que se presenta como una "ayudante" y no como una complicación extra. Utilizan teléfonos móviles mayormente para comunicación esencial (llamadas/WhatsApp).
* **Actitudes:** Inicialmente cautelosos ante lo nuevo, pero profundamente pragmáticos. Valoran la durabilidad y la facilidad de uso. Su confianza se gana con resultados visuales: plantas más verdes y menos recibos de agua/luz.

Según la Encuesta Nacional Agropecuaria 2022, el sector enfrenta un desafío generacional y técnico crítico: el 40,2% de los productores tiene 60 años a más y el 35,9% se encuentra entre los 45 y 59 años, lo que exige interfaces de alta usabilidad. Además, solo el 3,8% de los productores recibió asistencia técnica, evidenciando una brecha de conocimiento que Grotix cubre mediante la automatización. A pesar de esto, el acceso a información agropecuaria vía dispositivos móviles alcanzó el 80,4%, validando la viabilidad de una solución basada en una App móvil para este perfil.

### Asociaciones Agrarias y Cooperativas

Este segmento incluye a organizaciones que agrupan a múltiples productores con el fin de mejorar su capacidad de negociación y estandarizar su producción. Estas entidades buscan soluciones escalables que les permitan monitorear el estado de las parcelas de todos sus socios desde una plataforma centralizada. Su objetivo es garantizar que la producción colectiva cumpla con estándares de calidad para la exportación o venta a grandes mercados, optimizando el uso compartido de recursos y conocimientos técnicos.

#### Aspectos demográficos:
* **Naturaleza:** Organizaciones formales (Cooperativas, Juntas de Usuarios, Asociaciones de Productores).
* **Representantes:** Dirigentes y técnicos agrarios (28 a 65 años) con capacidad de toma de decisiones grupales.
* **Nivel socioeconómico:** Instituciones con acceso a fondos colectivos, créditos agrarios o programas de apoyo estatal.

#### Aspectos geográficos:
* **Nacionalidad:** Peruana.
* **Zona geográfica:** Regiones con alta concentración de cultivos específicos donde la asociatividad es clave para la comercialización.

#### Aspectos psicográficos:
* **Intereses:** Competitividad gremial, estandarización de cultivos, acceso a certificaciones internacionales y gestión eficiente de la cuenca.
* **Estilo de vida:** Líderes y técnicos enfocados en la gestión administrativa y soporte técnico de sus asociados. Valoran la visualización de datos masivos y el reporte de estados de salud de múltiples campos.
* **Actitudes:** Colaborativas y estratégicas. Buscan tecnologías que permitan una integración fluida entre los socios y que faciliten la supervisión técnica a gran escala.

Los resultados de la ENA 2022 muestran que el 81,8% de la producción agrícola nacional se destina a la venta, lo que impulsa a las asociaciones a buscar tecnologías que aseguren estándares de calidad. Si bien el acceso a crédito es de solo el 9,1%, el 91,3% de quienes lo solicitaron lograron obtenerlo, lo que posiciona a las asociaciones como entes con capacidad financiera para adquirir sistemas IoT mediante financiamiento formal. La asociatividad permite que el despliegue de Grotix escale masivamente, impactando en las unidades agropecuarias que generan ingresos brutos conjuntos que llegan a los 26780 millones de soles anuales.





