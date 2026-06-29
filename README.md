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

# CAPÍTULO II: Requirements Elicitation & Analysis
## 2.1. Competidores

El ecosistema de agricultura inteligente en la región está compuesto por actores que buscan resolver la ineficiencia hídrica mediante la digitalización del campo. Sin embargo, la mayoría de estas soluciones están diseñadas para la gran agroexportación, dejando un espacio estratégico para que Grotix se posicione como una alternativa accesible y especializada en la mediana y pequeña escala. Estos competidores han validado el uso de tecnologías IoT y Big Data, estableciendo los estándares que Grotix busca democratizar para el agricultor local.
- **Hunter Agro (Hunter Perú):** Es la línea de agrotecnología de una corporación consolidada en seguridad y monitoreo. Su solución IoT se basa en un ecosistema de sensores inteligentes (suelo, clima, radiación y temperatura de hoja) y una plataforma en la nube diseñada específicamente para el sector agroexportador. Destacan por su capacidad de personalización mediante impresión 3D de componentes y su enfoque en tecnología limpia, ayudando a grandes fundos a prevenir enfermedades y optimizar el riego con hardware de alta gama.
- **Space AG (Perú):** Es una startup peruana líder en la transformación digital de operaciones agrícolas. Su plataforma centraliza la información recolectada en campo a través de una aplicación móvil y vuelos de drones, permitiendo digitalizar procesos como el control de plagas y la estimación de cosechas. Aunque su fuerte es la gestión operativa de grandes hectáreas, su presencia en el mercado peruano es un referente directo para cualquier arquitectura de software que busque centralizar datos agrícolas.
- **Kilimo (Argentina/Regional):** Esta startup se especializa en la gestión del riego mediante Inteligencia Artificial y Big Data. A diferencia de las soluciones basadas estrictamente en hardware, Kilimo utiliza datos satelitales y meteorológicos para enviar recomendaciones de riego directamente al dispositivo del agricultor. Su modelo de negocio se enfoca en generar "beneficios hídricos volumétricos" y sostenibilidad a gran escala, compitiendo con Grotix en el ámbito del soporte de decisiones estratégico y el ahorro de agua.

### 2.1.1. Análisis Competitivo

| Pregunta | Respuesta |
|---|---|
| ¿Por qué realizar este análisis? | Este análisis es fundamental para que Celevi identifique brechas de mercado y valide la diferenciación de Grotix frente a soluciones consolidadas. Al mapear las fortalezas y debilidades de la competencia, la startup puede posicionar su tecnología IoT como la opción más accesible y precisa para el sector desatendido, transformando riesgos en ventajas estratégicas que aseguren la escalabilidad del proyecto. |

| Perfil | Criterio | Grotix | Hunter Agro | SpaceAG | Kilimo |
|---|---|---|---|---|---|
| Identificación | Nombre | Grotix | Hunter Agro | SpaceAG | Kilimo |
| Identificación | Logo | <img src="https://imgur.com/1MiRLSx.png"> | <img src="https://imgur.com/GF45cgH.png"> | <img src="https://imgur.com/ryqU4x8.png"> | <img src="https://imgur.com/qnHh0C0.png"> |
| Perfil | Overview | Es una plataforma de agricultura inteligente para democratizar la tecnología de precisión en el agro peruano. Se enfoca en productores independientes y asociaciones agrarias, facilitando un sistema de riego automatizado y escalable basado en una arquitectura IoT centralizada. | Es la división tecnológica de Hunter Perú, orientada a la agroexportación de gran escala. Ofrece un ecosistema integral de sensores y software para el monitoreo de alta precisión de variables críticas como clima, radiación y salud foliar. | Startup peruana especializada en la digitalización de operaciones agrícolas mediante una plataforma que centraliza datos de campo, uso de drones y aplicaciones móviles para optimizar procesos como el control de plagas y estimación de cosechas. | Empresa regional de base tecnológica que utiliza Big Data e Inteligencia Artificial para la gestión del riego. Se apoya en datos meteorológicos y satelitales para enviar recomendaciones sin necesidad de hardware en campo. |
| Ventaja competitiva | ¿Qué valor ofrece a los clientes? | Ofrece precisión técnica local a bajo costo mediante sensores de humedad en terreno. Su valor reside en la simplicidad de su interfaz y en un modelo accesible para el agricultor que no cuenta con gran capital, asegurando sostenibilidad y cumplimiento de los ODS. | Resalta por su robustez corporativa y el uso de hardware de alta gama personalizable (impresión 3D). Su principal valor es la prevención de enfermedades y el soporte técnico de una marca consolidada en seguridad y monitoreo. | Posee una fuerte capacidad de gestión operativa masiva. Su ventaja competitiva es la integración de drones y software móvil que permite a los grandes fundos tener una “vista aérea” y administrativa total de sus hectáreas en una sola herramienta. | Ofrece una solución de “cero hardware”, lo que elimina costos de mantenimiento de sensores. Su propuesta de valor se centra en la facilidad de implementación inmediata y el ahorro volumétrico de agua basado en modelos climáticos regionales. |
| Perfil de marketing | Mercado objetivo | Pequeños y medianos agricultores independientes y asociaciones agrarias en vías de tecnificación. Se dirige a productores que buscan optimizar recursos sin inversiones prohibitivas y que están alineados con programas de sostenibilidad y ODS. | Grandes empresas agroexportadoras y corporaciones agrícolas con operaciones de alta intensidad. Su cliente busca tecnología de punta, soporte corporativo y personalización técnica para fundos de gran escala. | Gerentes de operaciones y administradores de fundos extensos que necesitan digitalizar la logística de campo. Su mercado es la gran agroindustria que maneja cientos de trabajadores y diversas variedades de cultivos. | Empresas agrícolas y corporaciones que buscan certificar su huella hídrica y sostenibilidad. Atiende a productores que prefieren soluciones de software puro sin la gestión de hardware físico en sus campos. |
| Perfil de marketing | Estrategias de marketing | Marketing de impacto social y educativo. Se apoya en alianzas, ferias tecnológicas y centros de innovación. Utiliza demostraciones de campo y casos de éxito locales para generar confianza en la efectividad del ahorro hídrico. | Estrategia de ventas B2B directa y relacional. Participación en ferias tecnológicas internacionales y marketing de autoridad, resaltando la robustez de sus dispositivos y su capacidad de fabricación a medida. | Inbound marketing enfocado en la gestión de datos. Ofrecen webinars técnicos y consultorías sobre digitalización agrícola, posicionándose como los líderes en la “oficina digital” para el campo peruano. | Marketing digital basado en resultados y sostenibilidad (ESG). Su comunicación se centra en el ahorro volumétrico de agua medible y en la facilidad de implementar IA para mejorar el ROI sin instalar sensores. |
| Perfil de producto | Productos y servicios | Sistema integral que combina nodos de sensores IoT (humedad/suelo) con una plataforma centralizada de monitoreo. Ofrece automatización de riego basada en umbrales personalizados y soporte técnico remoto. | Ecosistema de hardware de alta gama (sensores climáticos, radiación, hoja) integrado a una plataforma en la nube. Incluye mantenimiento preventivo y personalización de piezas mediante impresión 3D. | Software de gestión operativa (SaaS) que integra datos de campo, uso de drones y gestión de personal. Ofrece digitalización de cuadernos de campo y control de plagas/cosechas. | Software de inteligencia climática basado en Big Data. Proporciona recomendaciones de riego semanales y reportes de huella hídrica sin necesidad de instalación de hardware. |
| Perfil de producto | Precios y costos | Costo de hardware accesible (pago único inicial) y una cuota mensual por el uso y soporte de la plataforma de datos. | Inversión inicial de alto capital (CAPEX) por la adquisición del hardware robusto y contratos de servicio anuales por soporte y analítica de datos a medida. | Suscripción mensual o anual basada en el número de hectáreas gestionadas. Incluye costos adicionales por servicios especializados como vuelos de drones o consultoría. | Suscripción por servicio (SaaS) basada en hectáreas y tipo de cultivo. Al no usar hardware, se enfoca en un costo operativo directo (OPEX) por el soporte de decisiones. |
| Perfil de producto | Canales de distribución (Web y/o Móvil) | Híbrido: Aplicación móvil y web para el control en campo y landing page para distribución del producto. | B2B Directo: Consultoría técnica presencial, portal web corporativo para visualización de datos y ejecutivos de cuenta especializados. | Digital: Plataforma web robusta y aplicación móvil diseñada para trabajadores de campo (offline/online) y gestores de flota. | 100% Digital: Plataforma web y notificaciones vía móvil o correo electrónico. Su distribución es global/regional debido a su naturaleza de software puro. |
| Análisis FODA o SWOT | Fortalezas | **Enfoque Dual Único:** Capacidad de atender tanto la rentabilidad privada (ODS 2) como el bienestar público (ODS 3).<br><br>**Precisión Local:** Uso de sensores en terreno que garantizan la calidad del cultivo para exportación.<br><br>**Tecnología avanzada:** Mezcla de sensores con inteligencia artificial, microcontroladores y supervisión remota. | Cuentan con una infraestructura de postventa en todo el Perú. Sus equipos tienen certificaciones industriales que los grandes agroexportadores exigen por temas de seguros y auditorías. | Su interfaz es de las mejores del mercado; es muy visual y fácil de usar para gerentes agrícolas. Han logrado centralizar datos que antes estaban dispersos en papeles. | Tienen una capacidad de escalamiento brutal. Pueden cerrar un contrato en Piura y otro en Ica el mismo día porque no tienen que enviar técnicos a instalar nada físico. |
| Análisis FODA o SWOT | Oportunidades | **Licitaciones Públicas:** Alianzas con municipalidades para combatir la anemia mediante cultivos con riego controlado y nutritivo.<br><br>**Mercado de Exportación:** Creciente demanda de certificaciones de “uso eficiente del agua” para exportar a Europa/EE.UU.<br><br>**Estacionalidad:** El mercado peruano tiene periodos de estrés hídrico debido a condiciones climáticas.<br><br>**Demanda por certificaciones:** El mercado alimentario peruano requiere que sus proveedores cumplan con altos estándares de calidad. | Pueden absorber tecnologías emergentes comprando startups más pequeñas para integrarlas a su ecosistema corporativo. | El uso de IA para predecir plagas a través de fotos satelitales, lo cual es muy atractivo para el segmento exportador de monocultivos. | Venta de bonos de agua y certificados de sostenibilidad hídrica a empresas que cotizan en bolsa. |
| Análisis FODA o SWOT | Debilidades | **Curva de Implementación:** El tiempo que toma coordinar con entidades públicas (burocracia municipal).<br><br>**Escalabilidad Inicial:** Necesidad de un equipo técnico para mantenimiento en regiones diversas. | **Incompatibilidad con el Sector Público:** Su modelo de negocio se basa en márgenes altos por equipo. Para una municipalidad que busca combatir la anemia en 50 comunidades, el presupuesto de Hunter resultaría inviable, ya que no están diseñados para la “tecnología social” de bajo costo. | **Falta de uso de recursos del suelo:** Su fuerte es lo aéreo. Sin embargo, para cumplir con el ODS 3, se requiere un monitoreo químico y de humedad del suelo constante para asegurar la densidad nutricional del cultivo. Space AG ve la planta “por fuera”, pero Grotix la entiende “desde la raíz”. | **Desconfianza Técnica Local:** En regiones con orografía compleja (como la sierra peruana, donde las municipalidades combaten la anemia), los modelos climáticos generales fallan. El agricultor que exporta necesita la certeza del sensor en su tierra, no un cálculo basado en una estación meteorológica a 20 km de distancia. |
| Análisis FODA o SWOT | Amenazas | **Inestabilidad Política:** Cambios de gestión en municipalidades que puedan pausar proyectos de salud alimentaria.<br><br>**Brecha Digital:** Resistencia inicial de agricultores tradicionales a depender de una app para exportar. | La obsolescencia de hardware. Al fabricar sus propios sensores, una innovación en componentes más baratos y precisos (como los que usa Grotix) puede hacer que sus equipos caros se vean como “tecnología del pasado”. | Dependencia de terceros. Si los proveedores de imágenes satelitales o drones suben sus costos, su modelo de suscripción se encarece, alejándolos aún más del mediano productor. | Al ser un algoritmo cerrado, si el sistema recomienda regar y el cultivo se estresa, el agricultor pierde la confianza totalmente al no haber un sensor físico que respalde el dato. |

### 2.1.2. Estrategias y tácticas frente a competidores

#### Estrategia de Democratización Tecnológica (B2C)
**Objetivo:** Captar al pequeño agricultor independiente mediante un equilibrio entre propiedad del hardware y servicios inteligentes en la nube.

**Modelo Híbrido "Hardware-as-a-Service" (HaaS):** Ofrecer el kit de sensores a un precio de costo (pago único) vinculado a una suscripción mensual que habilita las funciones de Inteligencia Artificial y el Riego Automático Adaptativo.
* **Fortaleza aprovechada:** Tecnología avanzada (Sensores + IA + Azure).
* **Debilidad de la competencia aprovechada:** El modelo de Hunter Agro, donde el cliente debe pagar miles de dólares por adelantado. En Grotix, el agricultor "es dueño" de su equipo pero "se suscribe" a la inteligencia que lo hace funcionar.

**Suscripción con "Garantía de Cosecha":** Posicionar la cuota mensual de soporte y datos no como un gasto operativo, sino como un seguro técnico que garantiza actualizaciones del modelo de IA y soporte remoto ante fallos.
* **Fortaleza aprovechada:** Supervisión remota y soporte técnico.
* **Amenaza mitigada:** La Brecha Digital; el agricultor paga la suscripción para que el equipo de Celevi vigile sus datos por él, reduciendo su miedo a equivocarse al usar la aplicación.

**Interfaz de Micro-pagos o Prepago:** Evaluar una modalidad donde la suscripción solo se pague durante los meses de la campaña agrícola (agosto-diciembre), permitiendo que el agricultor no gaste dinero cuando su tierra está en descanso.
* **Oportunidad aprovechada:** Flexibilidad ante la estacionalidad del agro peruano.
* **Debilidad de la competencia aprovechada:** Los contratos anuales rígidos de SpaceAG o Kilimo, que obligan a pagar por hectárea incluso si el terreno no está sembrado.

#### Estrategia de Valor Agregado por Inteligencia de Suelo
**Objetivo:** Posicionarse frente a las asociaciones agrarias como la fuente de "la verdad en el campo".

**Sistema de Certificación de Riego para Asociaciones:** Proveer reportes automatizados que las asociaciones puedan usar para certificar ante compradores internacionales que sus socios cumplen con estándares de sostenibilidad (ODS 3).
* **Oportunidad aprovechada:** Creciente demanda de certificaciones para el Mercado de Exportación.
* **Debilidad de competencia aprovechada:** La Desconfianza técnica que genera Kilimo al no tener sensores físicos; Grotix ofrece el respaldo del dato real en la raíz.

#### Estrategia de Posicionamiento ODS
**Objetivo:** Utilizar el cumplimiento de ODS como herramienta de marketing y reputación, no como canal de venta burocrático.

**Sello "Cultivado con Grotix" para el consumidor final:** Ayudar a las asociaciones a etiquetar sus productos resaltando que su producción contribuye a la salud (ODS 3) y al ahorro de agua.
* **Fortaleza aprovechada:** El impacto en el bienestar público.
* **Debilidad de la competencia aprovechada:** La falta de propósito social de competidores meramente industriales, permitiendo que Grotix gane una Ventaja Competitiva emocional y reputacional.

## 2.2. Entrevistas
### 2.2.1. Diseño de Entrevistas
Las entrevistas se adaptan a cada segmento con el fin de obtener información relevante para comprender sus necesidades y expectativas.
#### Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala
1. Para comenzar, ¿podría describir su trayectoria en la agricultura y qué cultivos representan el sustento principal de su campaña actual?
2. ¿Cómo está compuesto su círculo familiar cercano y qué rol desempeña cada miembro en las decisiones o tareas diarias de la parcela?
3. En su jornada diaria, ¿cuál es la tarea que le demanda mayor esfuerzo físico o preocupación mental, y cómo afecta esto su calidad de vida?
4. ¿Cuáles son sus metas principales para su cosecha de este año y qué importancia tiene el éxito de esta producción para el futuro de su familia?
5. ¿Qué criterios o señales físicas utiliza actualmente para determinar el momento exacto en que una semilla o planta necesita agua y qué tan seguro se siente de esa decisión?
6. Cuéntenos sobre la última vez que una mala temporada de riego afectó sus planes personales o familiares; ¿qué fue lo que más le dolió de esa situación?
7. ¿De qué manera integra actualmente el uso del teléfono móvil en sus actividades diarias dentro del campo?

    a. Si lo utiliza: Basado en las aplicaciones que ya conoce, ¿qué características hacen que una herramienta le resulte fácil de usar y cuáles le generan tanta complicación que prefiere dejar de usarlas?

    b. Si NO lo utiliza: ¿A qué factores atribuye el no utilizar su teléfono para el trabajo y de qué manera prefiere gestionar o registrar la información de sus cultivos hoy en día?
8. Cuando se le presenta una plaga o un problema técnico que no sabe resolver, ¿a qué aplicaciones, redes sociales o contactos digitales acude primero para buscar consejo?
9. ¿Qué factores o condiciones técnicas tendrían que cumplirse para que usted confíe plenamente en una herramienta que ejecute el riego de forma autónoma?
10. ¿Ha evaluado anteriormente la posibilidad de invertir en sistemas para tecnificar sus parcelas? ¿Cuáles han sido los mayores impedimentos o riesgos identificados para concretar esa mejora?

#### Segmento Objetivo #2: Asociaciones Agrarias y Cooperativas
1. ¿Podría detallarnos su rol en la cadena productiva y qué trayectoria tiene trabajando como nexo entre los agricultores y los mercados finales?
2. ¿De qué manera logra usted equilibrar el respeto por las costumbres tradicionales de los agricultores con la necesidad de introducir nuevas tecnologías para mejorar la competitividad? ¿Cuáles son las resistencias más comunes que ellos manifiestan?
3. ¿Cómo es el proceso de supervisión que usted realiza para asegurar que los diversos productores con los que trabaja mantengan una calidad homogénea desde la siembra hasta la cosecha?
4. ¿Cuáles son sus metas comerciales de venta o exportación para el próximo periodo y qué exigencias técnicas de calidad son innegociables para cumplirlas?
5. ¿Qué estándares internacionales, certificaciones o instituciones agrarias son los que dictan hoy en día la pauta de calidad para los productos que usted comercializa?
6. ¿Cuáles son las principales limitaciones o "vacíos de información" que enfrenta usted al intentar monitorear el progreso de las parcelas de forma remota o centralizada?
7. ¿Podría describirnos una situación en la que la falta de control las parcelas haya comprometido un contrato de venta o la relación con un comprador importante?
8. ¿A través de qué plataformas digitales o formatos de reporte suele demostrar usted a sus compradores que la producción cumple con estándares de sostenibilidad y riego eficiente?
9. ¿Qué criterios específicos prioriza usted al momento de evaluar una inversión en tecnología o automatización para mejorar la producción de los agricultores bajo su gestión?
10. En su experiencia trabajando con diversos productores, ¿cuáles son las resistencias más comunes que ellos manifiestan cuando se les propone cambiar su forma tradicional de gestionar el agua?

### 2.2.2. Registro de Entrevistas

#### Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala

**Entrevistado N.º 1: Nicolás Medina**
* **Edad:** 22
* **Departamento:** Lima (Huaral)
* **Estado civil:** Soltero
* **Ocupación:** Productor de Agricultura Familiar

<img src="https://i.imgur.com/pUlEqBZ.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 1 Segmento 1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQBi8fHpjrklQJWqd5vH3HuSAbegq-6E9EchsLHWzlhryQI?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=mJKUh4)
* **Instante en el que inicia:** 0:00
* **Duración:** 8:05

Nicolás Medina es un joven agricultor de Huaral cuya familia mantiene una tradición agrícola centrada en cultivos de naranja, mandarina y manzana, además de productos para consumo personal como el maracuyá. Aunque sus padres han liderado la gestión de la parcela, Nicolás participa activamente en las tareas del campo, identificando la cosecha y el riego como las actividades de mayor exigencia física. Especialmente en verano, el traslado de mangueras y baldes bajo el sol representa un desgaste significativo que impacta directamente en su calidad de vida, sumado a la preocupación constante por el estado de las plantas.

En cuanto a la gestión del agua, el entrevistado destaca que actualmente se guían por el paso del tiempo y la observación visual de las hojas para decidir cuándo regar. Sin embargo, este método empírico ha fallado anteriormente, como en el caso de su viña de maracuyá, la cual se perdió por un exceso de riego que detuvo la producción. Esta experiencia subraya una oportunidad crítica para la implementación de sensores de humedad que eviten el error humano y optimicen el suministro de agua.

Respecto al uso de tecnología, Nicolás integra el teléfono móvil de forma funcional pero simplista, utilizando el calendario como una agenda para registrar fechas de riego y cosecha. Aunque ha intentado usar herramientas más complejas como Notion, las abandonó por considerarlas demasiado específicas o difíciles de configurar, lo que indica una clara preferencia por interfaces intuitivas y directas. Asimismo, utiliza Google Imágenes para diagnosticar plagas, aunque reconoce que no siempre obtiene resultados precisos o confiables.

Finalmente, el interés por la automatización en su parcela está condicionado a la fiabilidad del sistema. Nicolás se muestra abierto a soluciones autónomas siempre que existan pruebas verídicas de su funcionamiento y programación. Un dato clave es que su familia ya ha realizado inversiones importantes en infraestructura, como la construcción de un pozo propio para no depender de la red pública, lo que demuestra que están dispuestos a invertir en tecnología si esta garantiza autonomía, reducción de costos y mejores resultados en la producción.

**Entrevistado N.º 2: Leandro Machaca**
* **Edad:** 26
* **Departamento:** Oxapampa, Pasco
* **Estado civil:** Soltero
* **Ocupación:** Productor de agricultura familiar (5 años de trayectoria)

<img src="https://imgur.com/in5V239.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 2 Segmento 1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/IQBxLrXh3NBsTJ9ClOpcbnJtAUEVsDl0JL8L7q44-nb9UuU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=6v4VeH)
* **Instante en el que inicia:** 0:22
* **Duración:** 12:48

Leandro Machaca es un productor de Oxapampa que, junto a su familia, gestiona una unidad agrícola de mediana escala dedicada principalmente al cultivo de palta (Hass y Fuerte), granadilla y pituca. Con apenas cinco años en el sector y un año y medio de cosechas reales, Leandro se considera un "aprendiz" en la ciencia agrícola, delegando la administración a su madre mientras él y su padre supervisan las tareas de campo. Para ellos, el éxito de la campaña es crítico, ya que representa el 100% de los ingresos familiares, y su meta principal es alcanzar los estándares de calidad exigidos por las distribuidoras internacionales para evitar que su producto sea rechazado y vendido a bajo precio en el mercado local. En cuanto a la gestión fitosanitaria y de recursos, el entrevistado enfrenta el desafío de la falta de experiencia técnica.

Actualmente, ante cualquier sospecha de plaga o deficiencia, debe trasladar físicamente muestras de hojas o frutos hasta el pueblo para que expertos de la municipalidad realicen un diagnóstico. Este método, aunque funcional, evidencia una dependencia total de terceros y una falta de herramientas de monitoreo en tiempo real en la propia parcela. Leandro reconoce que la agricultura es una disciplina compleja donde factores como el color de la hoja o la presencia de insectos determinan la salud del cultivo, pero carece de un sistema que le permita anticiparse a estos problemas de forma autónoma.

Respecto al uso de tecnología, el teléfono móvil cumple un rol estrictamente logístico y de coordinación con los distribuidores. La principal barrera detectada es la inestabilidad de la red de internet en su zona de cultivo, lo que ha impedido que Leandro adopte aplicaciones de diagnóstico digital o herramientas de inteligencia artificial. Aunque tiene referencias de soluciones como ChatGPT para analizar imágenes, la brecha de conectividad en Oxapampa limita su uso a funciones básicas, manteniendo una preferencia por el asesoramiento humano presencial hasta que la infraestructura digital permita una alternativa confiable.

Finalmente, Leandro muestra un interés genuino en tecnificar su chacra mediante sistemas IoT y sensores de humedad, reconociendo el valor de automatizar el riego para optimizar el desarrollo de sus plantas. Sin embargo, su disposición a invertir está sujeta a la superación de obstáculos económicos y, fundamentalmente, de seguridad. Un riesgo crítico identificado por el productor es la vulnerabilidad de los equipos ante posibles robos, dado que no residen permanentemente en la parcela. Para él, una solución técnica exitosa no solo debe ser precisa y funcionar con baja señal, sino también ser lo suficientemente segura y accesible para garantizar un retorno de inversión en un negocio familiar aún en crecimiento.


**Entrevistado N.º 3: Joseph Medina**
* **Edad:** 23
* **Departamento:** Lima
* **Estado civil:** Soltero
* **Ocupación:** Productor de Agricultura Familiar

<img src="https://imgur.com/nOCm95N.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 3 Segmento 1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQCCmjlnReChQZ7sj4Np6kFOAe7iJb1K15lWL-JAr9bgitk?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=sdSari)
* **Instante en el que inicia:** 0:00
* **Duración:** 8:00

Joseph Medina posee una herencia agrícola directa de sus padres y abuelos, habiendo trabajado personalmente la tierra en el cultivo de hortalizas y tubérculos como zanahoria, cebolla, lechuga, papa y alfalfa. A pesar de su experiencia práctica, Joseph reconoce que la agricultura es una labor sumamente sacrificada donde el éxito de la cosecha es el pilar fundamental de la economía familiar. Para su entorno, la meta principal no es la expansión ambiciosa, sino la estabilidad; el objetivo es "mantenerse" y asegurar que el ciclo productivo se repita sin alteraciones que pongan en riesgo su sustento.

El riego es identificado como la tarea más crítica y compleja de la jornada, ya que su frecuencia y duración varían drásticamente según el tipo de cultivo. Actualmente, la familia toma decisiones basadas exclusivamente en el conocimiento empírico transmitido por generaciones; "simplemente saben" cuándo regar por pura práctica. No obstante, Joseph manifiesta una duda razonable sobre la precisión científica de estos métodos tradicionales, especialmente cuando factores externos como sequías, variaciones en el caudal de agua o desastres naturales (huaycos) impactan negativamente en la producción.

Existe una brecha digital marcada en su unidad familiar: mientras Joseph utiliza el teléfono móvil para investigar nuevos métodos que simplifiquen el trabajo, sus padres y abuelos mantienen una resistencia al uso de tecnología, confiando más en su memoria y en el intercambio de consejos con otros campesinos de la zona ante problemas como plagas. Esta red de contactos vecinales es su principal recurso de resolución de conflictos, desplazando cualquier herramienta digital o aplicación técnica que pudiera existir en el mercado actual.

Finalmente, el interés por la tecnificación de sus parcelas se ha visto frenado por la incertidumbre y el miedo al riesgo. Aunque la familia ha evaluado modernizar sus sistemas en el pasado, la falta de conocimiento técnico y el temor a que una herramienta nueva complique el trabajo en lugar de facilitarlo impidieron la inversión. Para que Joseph y su familia confíen en un sistema de riego autónomo como Grotix, la herramienta no solo debe demostrar que puede igualar la eficacia del trabajo manual, sino garantizar que reducirá la carga operativa sin añadir niveles de complejidad que no puedan manejar.

#### Segmento Objetivo #2: Asociaciones Agrarias y Cooperativas
**Entrevistado N.º 4: Jossimar Atoche Escobar**
* **Edad:** 29
* **Departamento:** Piura
* **Estado civil:** Soltero
* **Ocupación:** Gerente general de una exportadora

<img src="https://imgur.com/qI0pkZB.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 1 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311701_upc_edu_pe/IQDvOjh_Y_CTRr2USrz-vIFFAVDrnXe2OfXt0yPZ_Ca38Y8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=cLpP2K)
* **Instante en el que inicia:** 00:01
* **Duración:** 16:49

La entrevista con Jossimar Escobar, gerente de una exportadora en Piura, confirma que la trazabilidad y la uniformidad del producto son los pilares del éxito en el mercado internacional. Jossimar destaca que para cumplir con certificaciones exigentes como GlobalGAP o la FDA, es innegociable mantener un control estricto del riego que garantice "calibres uniformes". Para un exportador, la falta de datos en tiempo real es un cuello de botella; relata cómo la demora en obtener reportes manuales para un cliente de productos orgánicos puso en pausa una negociación, validando que una herramienta como Grotix facilitaría el cierre de contratos al ofrecer información instantánea desde el celular.

Por otro lado, el entrevistado identifica una marcada resistencia cultural y tecnológica en el campo. Los agricultores suelen ver la tecnificación como un costo elevado y no como una inversión, sumado al temor de que la automatización desplace la mano de obra humana. Sin embargo, Jossimar subraya que ante crisis hídricas críticas como las que vive el norte del Perú, la "costumbre al riego tradicional" ya no es sostenible. Existe una necesidad urgente de combatir la desinformación sobre el ahorro real de agua para asegurar la rentabilidad de campañas clave como las del mango y el limón.

Él piensa que el rol de las asociaciones y exportadoras es actuar como el nexo técnico que introduzca estas innovaciones de forma gradual. Jossimar priorizaría el retorno de inversión (ROI) y la facilidad de adaptación para el agricultor como criterios de compra. Para Grotix, esto significa que el valor no está solo en el ahorro de agua, sino en convertirse en un respaldo de calidad y transparencia frente a compradores extranjeros, transformando datos complejos de sensores en una ventaja comercial tangible para el productor y la exportadora.

**Entrevistado N.º 5: Jorge Luis Chanamé Miranda**
* **Edad:** 62
* **Departamento:** Chiclayo
* **Estado civil:** Casado
* **Ocupación:** Presidente de una pequeña asociación agraria

<img src="https://imgur.com/IRsG0E3.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 2 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311701_upc_edu_pe/IQA-rgERTQtqRLH70dwO_ks-AenzdjgfENUL99NIJK0VqjQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=QYeCMF)
* **Instante en el que inicia:** 00:01
* **Duración:** 09:57

La entrevista con Jorge Luis, presidente de una asociación de productores, revela que el mayor desafío de las cooperativas es la fragmentación de la información y la falta de homogeneidad en la producción. Actualmente, la supervisión es manual y reactiva, lo que genera una "brecha de datos" entre las visitas técnicas. Jorge Luis enfatiza que la falta de telemetría en tiempo real no solo afecta la calidad del fruto y el calibre, sino que pone en riesgo contratos internacionales; menciona que la incapacidad de reaccionar ante cambios climáticos imprevistos ha causado pérdidas de lotes enteros por no cumplir con los estándares de firmeza y grados Brix exigidos por los brokers.

El entrevistado señala que el uso de herramientas informales como Excel o fotos de WhatsApp ya no es suficiente para los compradores europeos, quienes ahora demandan reportes de "Huella Hídrica" y pruebas de sostenibilidad. La capacidad de Grotix para generar dashboards de telemetría y reportes automáticos de eficiencia hídrica (ahorro del 60%) se percibe como una ventaja competitiva crítica para transformar a la asociación en un exportador directo, eliminando la dependencia de reportes manuales tardíos.

Jorge Luis destaca que la identificación inteligente de cultivos por IA es el factor determinante para vencer la resistencia cultural del agricultor. Al ver que el dispositivo reconoce automáticamente su planta, se reduce el escepticismo inicial y el miedo a la complejidad técnica.

**Entrevistado N.º 6: Ana Otsuka**
* **Edad:** 64
* **Departamento:** Lima (Huaral)
* **Estado civil:** Casada
* **Ocupación:** Fiscal del Consagra de la Querencia (Comité de Sanidad Agraria) y Productora Exportadora

<img src="https://imgur.com/XYtKCwd.png">

**Acerca de la entrevista:** 
* **Link:** [Grotix 202610 - Entrevista 3 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQD85zV4Yde8T75p6W89L_yEAXnQdgmYi1tDIqYR61-pXg8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=cusvPf)
* **Instante en el que inicia:** 00:01
* **Duración:** 20:27

La entrevista con Ana Otsuka, productora exportadora en Huaral, confirma que la viabilidad de la agricultura de precisión depende de la capacidad del sistema para adaptarse a los ciclos biológicos específicos del cultivo. Ana destaca que en la producción de cítricos es vital el manejo del "estrés hídrico" (suspensión del riego por meses para forzar la floración), validando que Grotix debe ofrecer una programación inteligente que no se limite a mantener la humedad constante, sino que responda a las necesidades metabólicas de la planta. Para un exportador, la precisión en el riego es lo que determina el calibre de la fruta, factor crítico para cumplir con las exigencias diferenciadas de mercados como Japón (fruta pequeña) y Europa (fruta grande).

Por otro lado, la entrevistada identifica una falla crítica en el sistema de riego tradicional por turnos, donde la falta de control genera un desperdicio involuntario de agua. Relata que, debido a la rigidez de los horarios de riego del río, se ve obligada a "botar" el recurso sobrante que su parcela no puede absorber. Asimismo, subraya que el costo de la energía eléctrica es la principal barrera para usar sistemas de riego tecnificado existentes; Ana solo activa estos sistemas en emergencias de sequía, lo que valida la propuesta de Grotix de utilizar energía solar para eliminar el costo operativo y permitir un monitoreo constante sin afectar la rentabilidad.

Ella concluye que el valor de la tecnología en el campo radica en la facilidad de gestión y el ahorro de costos. Ana percibe la identificación automática de cultivos por IA como una herramienta para superar la complejidad técnica, permitiendo que el sistema configure automáticamente las fases de riego según el estado fenológico detectado. Para Grotix, esto significa que el éxito del proyecto está en convertirse en un gestor autónomo de recursos que garantice la calidad exportable del producto mientras elimina la dependencia de fuentes de energía costosas y reduce el desperdicio hídrico estructural.

### 2.2.3. Análisis de Entrevistas
#### Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala
El primer segmento identificado corresponde a familias agricultoras con una fuerte herencia generacional, donde el éxito de la campaña representa el sustento económico principal. De acuerdo con las entrevistas realizadas, se observa que el 100% de los sujetos dependen de un modelo de gestión empírica, basado en la observación visual y el conocimiento transmitido por sus ancestros. No obstante, este método tradicional presenta fallas críticas ante factores externos; por ejemplo, un 33.3% del segmento reportó la pérdida total de cultivos específicos, como el maracuyá, debido a errores humanos en el cálculo del riego. Esta problemática objetiva se complementa con una brecha en el diagnóstico técnico: el 66.7% de los entrevistados manifiesta dificultades para identificar plagas o deficiencias de forma autónoma, obligándolos a recurrir a herramientas imprecisas como Google Imágenes o a traslados físicos hacia centros urbanos en busca de expertos, como es el caso de Leandro en Oxapampa.

En cuanto al perfil tecnológico, el 100% de los productores posee y utiliza dispositivos móviles, pero su uso se limita a funciones logísticas y de comunicación básica. Existe una resistencia marcada hacia aplicaciones de gestión complejas; un 66.7% del segmento ha intentado o evaluado el uso de herramientas digitales más avanzadas, pero las terminaron descartando por considerarlas difíciles de configurar o ajenas a su realidad operativa. Este hallazgo es fundamental para la construcción del arquetipo, pues revela que la tecnología no es rechazada por falta de interés, sino por una excesiva complejidad percibida. Además, el factor de la infraestructura actúa como una barrera objetiva relevante para el 33.3% de los usuarios, cuya ubicación geográfica presenta inestabilidad en la red, lo que exige que cualquier solución propuesta sea resiliente a entornos de baja conectividad.

Desde una perspectiva subjetiva, el segmento está profundamente marcado por la carga emocional y el sacrificio físico que implica la labor del campo. El 100% de los entrevistados define la agricultura como una actividad de alta exigencia que impacta directamente en su calidad de vida y estabilidad familiar. Existe un sentimiento común de incertidumbre y miedo al riesgo que frena la inversión tecnológica; por ejemplo, Joseph y Nicolás coinciden en que solo confiarían en un sistema automatizado si existen pruebas contundentes de su fiabilidad. Por otro lado, un 33.3% introduce una preocupación subjetiva adicional: la vulnerabilidad física de los equipos ante posibles robos en parcelas no habitadas. En conclusión, el arquetipo de este segmento se define por la búsqueda de autonomía técnica y seguridad económica, valorando soluciones que garanticen mejores resultados productivos sin añadir niveles de complejidad que pongan en duda su capacidad de manejo.


#### Segmento Objetivo #2: Asociaciones Agrarias y Cooperativas
El segundo segmento objetivo se caracteriza por una orientación profesional hacia la exportación y la estandarización de la calidad. El 100% de los entrevistados coincide en que la uniformidad del producto y el control de calibres son los pilares del éxito comercial, vinculando directamente la precisión hídrica con la capacidad de cumplir con certificaciones internacionales como GlobalGAP o la FDA. Este segmento enfrenta un cuello de botella logístico: el 66.7% de los sujetos identifica una "brecha de datos" crítica debido al uso de métodos manuales e informales, como reportes en Excel o fotos por WhatsApp, que resultan insuficientes para las exigencias de sostenibilidad y trazabilidad demandadas por mercados europeos. Esta necesidad de información instantánea es objetiva, pues la demora en la obtención de reportes ha llegado a pausar negociaciones comerciales o causar la pérdida de lotes enteros por falta de firmeza en el fruto.

En términos de gestión de recursos y tecnología, el análisis revela una transición necesaria impulsada por factores externos. El 100% de los participantes reconoce que el riego tradicional por turnos o por inundación es insostenible ante crisis hídricas o la rigidez de los horarios de riego de los ríos. Sin embargo, surge una barrera económica específica para el 33.3% de los productores: el alto costo de la energía eléctrica para el riego tecnificado, lo que valida la implementación de energía solar en Grotix como un factor de viabilidad financiera. Asimismo, existe una demanda de especialización técnica; el caso de Ana Otsuka subraya que el sistema no debe ser solo un monitor de humedad, sino un gestor del ciclo biológico que permita aplicar técnicas avanzadas como el "estrés hídrico" para forzar la floración, demostrando que la tecnología debe adaptarse a las necesidades metabólicas de cada cultivo para garantizar la rentabilidad.

Desde la dimensión subjetiva, el segmento lidia con una marcada resistencia cultural y el escepticismo de los agricultores de campo. El 66.7% de los líderes menciona que la tecnificación es percibida erróneamente como un costo o una amenaza para la mano de obra humana. Para contrarrestar este miedo, se identifica un hallazgo psicológico clave: el 66.7% de los entrevistados considera que la identificación automática de cultivos por IA actúa como un "reductor de escepticismo", facilitando la adopción al simplificar la configuración inicial. Subjetivamente, el valor de Grotix para este segmento no reside solo en el ahorro de agua, sino en la paz mental que otorga la transparencia de datos frente a compradores extranjeros. El éxito para este grupo se define como la transformación de datos técnicos complejos en una ventaja comercial tangible que asegure el retorno de inversión (ROI) y posicione a la asociación como un exportador directo y sostenible.

## 2.3. NeedFinding
### 2.3.1. User Personas
La presente sección de User Personas sintetiza las características principales de los usuarios objetivo de Grotix, a partir del análisis de entrevistas, el estudio de la competencia y los resultados del proceso Lean UX. Estos perfiles semi ficticios permiten representar necesidades, comportamientos y limitaciones clave detectados en los agricultores y actores del ecosistema agrario, sirviendo como base para orientar las decisiones de diseño y desarrollo de la solución.

#### Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala

[foto]

#### Segmento Objetivo #2: Asociaciones Agrarias y Cooperativa

<img src="https://imgur.com/gIZYZJr.png">

### 2.3.2. User Task Matrix

La presente sección presenta el User Task Matrix, considerando los dos segmentos definidos: productores independientes y representantes de asociaciones agrarias. A partir de los User Personas, se identifican las tareas clave que estos usuarios realizan para cumplir sus objetivos, independientemente de la existencia de la solución propuesta. Este análisis permite comprender la frecuencia e importancia de cada actividad, sirviendo como base para identificar oportunidades de mejora y priorización en el desarrollo del sistema.

| User Task Matrix | Mateo Rojas |  | Carlos Mendoza |  |
|---|---|---|---|---|
|  | Frecuencia | Importancia | Frecuencia | Importancia |
| Monitorear humedad y salud del suelo | Siempre | Alta | Con frecuencia | Alta |
| Inspeccionar presencia de plagas y enfermedades | Siempre | Alta | Con frecuencia | Alta |
| Ejecutar y supervisar las jornadas de riego | Con frecuencia | Alta | Siempre | Alta |
| Gestionar logística de cosecha y venta | Con frecuencia | Alta | Siempre | Alta |
| Obtener certificaciones de calidad | A veces | Media | Con frecuencia | Alta |
| Reportar estado de cultivos a compradores finales | Rara vez | Baja | Siempre | Alta |
| Consultar pronósticos y alertas climáticas | Con frecuencia | Media | Con frecuencia | Media |
| Capacitarse o brindar asistencia técnica | A veces | Media | Con frecuencia | Media |
| Vigilar la seguridad de la infraestructura en campo | Siempre | Media | A veces | Media |


### 2.3.3. User Journey Mapping

Los User Journey Maps actúan como el sustento empírico de Grotix, permitiendo mapear el escenario actual (As-Is) para identificar las deficiencias críticas en la gestión agrícola. Al visibilizar los puntos de dolor y las ineficiencias operativas de nuestros usuarios, estos mapas transforman necesidades reales en oportunidades de ingeniería, garantizando que cada funcionalidad del proyecto esté alineada con la resolución de problemas tangibles y la optimización de recursos en el campo.

#### Productores Independientes de Pequeña y Mediana Escala
User journey mapping 1 de Productores Independientes de Pequeña y Mediana Escala

[foto]


#### Asociaciones Agrarias y Cooperativas
User journey mapping 2 de Asociaciones Agrarias y Cooperativas

[foto]

### 2.3.4. Empathy Maps

En esta sección se presenta el proceso de elaboración de los Empathy Maps para cada uno de los User Personas definidos en el contexto de Grotix. A partir del análisis de entrevistas, insights del sector agrícola y validación del problema, el equipo identificó comportamientos, necesidades y percepciones clave de los usuarios. Se abordaron aspectos como lo que el usuario ve, dice, hace, escucha, piensa y siente en su día a día, permitiendo reconocer sus principales pains (limitaciones en acceso a información, toma de decisiones y monitoreo) y gains (optimización de recursos, mejora en productividad y reducción de riesgos). Este análisis facilita una comprensión profunda del usuario y orienta el diseño de soluciones centradas en sus necesidades reales.

#### Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala

[foto]

#### Segmento Objetivo #2: Asociaciones Agrarias y Cooperativa

<img src="https://imgur.com/vPR6Qqt.png">

## 2.4. Big Picture EventStorming
En esta sección, se detalla el desarrollo del Big Picture Event Storming, una metodología colaborativa empleada para explorar y definir el dominio del proyecto Grotix. A través de este proceso, el equipo de trabajo ha logrado identificar los eventos clave, los roles de usuario y las dependencias tecnológicas que estructuran la solución, permitiendo establecer una visión compartida y exhaustiva del comportamiento del sistema en su conjunto. 

El proceso se llevó a cabo de manera incremental, iniciando con la identificación de Domain Events que representan cada cambio de estado significativo en el ciclo de vida del monitoreo agrícola. Posteriormente, estos eventos fueron organizados cronológicamente para dar coherencia al flujo de negocio, permitiendo la asignación precisa de Actores y la integración de Sistemas Externos críticos para la automatización e inteligencia del sistema. Las capturas y explicaciones presentadas a continuación evidencian la transición de una lluvia de ideas técnica hacia un modelo de arquitectura funcional y robusto. 

**Step 1: Generating Domain Events**

En esta fase de Big Picture Event Storming, el equipo se enfocó en el reconocimiento y definición de los Domain Events que integran el ecosistema de Grotix. A través de una lluvia de ideas masiva, se identificaron todos los eventos o cambios de estado relevantes para el negocio, abarcando desde la gestión de identidad y telemetría de sensores hasta la lógica inteligente de riego y análisis visual. Este inventario de eventos permite consolidar una visión compartida de todas las capacidades del sistema, sirviendo como base fundamental para la posterior identificación de actores y  sistemas externos. 

[foto]

**Step 2: Sorting Domain Events**

En esta etapa, el equipo procedió a organizar los eventos identificados siguiendo una línea de tiempo lógica y cronológica. Este proceso permitió estructurar el flujo del sistema desde el registro y vinculación del usuario hasta los ciclos automáticos de monitoreo, análisis visual por IA y riego inteligente. Al ordenar los eventos, se establecieron las relaciones de dependencia entre ellos, logrando una narrativa visual clara del recorrido del usuario y el comportamiento autónomo del hardware ante las condiciones del entorno. 

[foto]

**Step 3: Actors**

En esta fase, el equipo identificó y asignó los actores responsables de disparar o interactuar con los eventos de dominio previamente ordenados. Se determinó que, si bien el Usuario Agrícola centraliza la mayoría de las interacciones, existen roles especializados que enriquecen el flujo del sistema. Por ejemplo, se identificó la participación de un actor secundario para la solicitud de acceso a zonas de cultivo, permitiendo la colaboración en la parcela. Asimismo, se definió el rol del Supervisor Agrícola como el actor encargado de la gestión de datos de alto nivel y la visualización de reportes hídricos, diferenciándolo del usuario operativo para alinearse con las necesidades de gestión y toma de decisiones de las cooperativas agrarias. 

**Step 4: External Systems**

En la cuarta etapa del Event Storming, el equipo identificó y vinculó los sistemas externos que actúan como proveedores de servicios críticos para el cumplimiento de ciertos eventos de dominio. Se determinó la dependencia de un servicio de autenticación para la seguridad de acceso, un servicio de análisis visual con IA para el procesamiento de imágenes y un motor de inteligencia agronómica para la configuración experta de umbrales de cultivo. Asimismo, se integraron un servicio de notificaciones para la comunicación en tiempo real y un servicio meteorológico encargado de proporcionar datos climáticos para la optimización del riego. La identificación de estos sistemas permite definir claramente los límites de Grotix y asegurar que la arquitectura soporte integraciones robustas que potencien la autonomía y precisión del monitoreo agrícola. 

[foto]

**Step 5: Conclusion and Storytelling**

Tras concluir la integración de los sistemas externos en el Paso 4, el equipo procedió a realizar una fase de Storytelling. En esta etapa final, se validó narrativamente todo el flujo diseñado, confirmando que la interacción entre los eventos, los actores y los servicios externos mantiene una coherencia total con la experiencia de uso real de la aplicación. Este ejercicio permitió verificar que la lógica de Grotix responde de manera eficiente a las necesidades del entorno agrícola, asegurando que cada funcionalidad esté debidamente respaldada por la arquitectura propuesta. 

[foto]

## 2.5. Ubiquitous Language

| Término | Definición |
|---|---|
| Smart Agriculture (Agricultura Inteligente) | Modelo de producción que emplea plataformas tecnológicas, sensores IoT y analítica de datos para optimizar recursos, gestionar el agua eficientemente y garantizar cosechas de alta calidad. |
| Precision Irrigation (Riego de Precisión) | Método de gestión hídrica que suministra la cantidad exacta de agua requerida basándose en las condiciones físicas del entorno y en las necesidades metabólicas específicas del cultivo. |
| Gravity Irrigation (Riego por Gravedad) | Método de riego tradicional predominante y de baja eficiencia que ocasiona el desperdicio del 65% del agua aplicada debido a la falta de tecnificación en las parcelas. |
| Pressurized Irrigation (Riego Presurizado) | Sistema de suministro de agua, como el riego por goteo, que incrementa sustancialmente la eficiencia hídrica pero que suele implicar altas barreras de inversión inicial. |
| Water Stress (Estrés Hídrico) | Condición crítica originada por la escasez de agua que compromete el rendimiento del cultivo; o bien, una técnica aplicada intencionalmente durante meses para forzar el ciclo biológico de floración. |
| Phenological Stage (Fase Fenológica) | Etapa específica del desarrollo biológico de la planta (ej. floración, llenado de grano o germinación) que determina sus requerimientos hídricos y de iluminación particulares. |
| Crop Yield (Rendimiento de Cosecha) | Volumen y calidad de la producción agrícola obtenida por hectárea, la cual puede optimizarse directamente mediante la mitigación de déficits hídricos y el control de umbrales ambientales. |
| Food Security (Seguridad Alimentaria) | Condición que garantiza el acceso continuo a alimentos con densidad nutricional adecuada para la población, vinculada a la productividad agrícola y al Objetivo de Desarrollo Sostenible 2. |
| Agricultural Plot (Parcela Agrícola) | Unidad de tierra cultivable gestionada técnica y operativamente por los productores agrarios, donde se instalan los nodos de sensores para el monitoreo de variables ambientales. |
| Smallholder Farmer (Productor Independiente) | Agricultor de pequeña o mediana escala que tradicionalmente gestiona sus recursos mediante decisiones basadas en experiencia empírica y observación visual del entorno. |
| Agrarian Association (Asociación Agraria) | Organización formal que agrupa a múltiples agricultores con el propósito de centralizar el monitoreo técnico, estandarizar la producción colectiva y acceder a mercados internacionales de exportación. |
| Evapotranspiration (Evapotranspiración) | Volumen total de agua perdida tanto por la evaporación directa desde el suelo como por la transpiración intrínseca de las plantas cultivadas. |
| Crop Threshold (Umbral de Cultivo) | Valores máximos de temperatura, humedad e intensidad lumínica que una especie vegetal puede tolerar antes de que se vea comprometida su integridad biológica o la calidad de la cosecha. |
| Field Capacity (Capacidad de Campo) | Nivel máximo y óptimo de humedad que un suelo específico es capaz de retener antes de que se produzca la saturación, utilizado como parámetro base en diagnósticos previos a la instalación de riego. |
| Permanent Wilting Point (Punto de Marchitez Permanente) | Nivel mínimo crítico de retención de humedad en el cual la planta es incapaz de extraer agua del sustrato, sufriendo daños metabólicos irreversibles. |
| Water Footprint (Huella Hídrica) | Indicador técnico de sostenibilidad ambiental que documenta y cuantifica el volumen de agua utilizado para producir los alimentos, siendo una métrica exigida como certificación de exportación. |
| Fruit Caliber (Calibre del Fruto) | Estándar de tamaño, firmeza y uniformidad morfológica exigido por brokers y mercados internacionales (ej. FDA, GlobalGAP) para aceptar la producción de una campaña. |
| Brix Degrees (Grados Brix) | Unidad de medida analítica utilizada en campo para determinar la concentración de azúcares presentes en la fruta como indicador primario de madurez y calidad comercial. |
| Telemetry (Telemetría) | Sistema de comunicación y monitoreo constante que recolecta, transmite y visualiza datos del entorno agrícola a un panel de control para la toma de decisiones sin presencia física en campo. |
| Sensor Node (Nodo de Sensor) | Dispositivo de hardware de campo, energéticamente autónomo, encargado de registrar mediciones precisas de humedad, intensidad lumínica y temperatura del suelo. |
| Actuator / Valve (Actuador / Válvula) | Componente físico o electromecánico integrado al sistema de tuberías que se abre o cierra de forma remota para ejecutar el flujo y suministro de agua hacia las parcelas. |

