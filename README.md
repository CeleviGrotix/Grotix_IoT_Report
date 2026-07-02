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

# CAPÍTULO III: Requirements Specification 

## 3.1. User Stories

En esta sección se detallan las Historias de Usuario (US) que definen el alcance funcional y técnico de Grotix. El objetivo principal de este apartado es traducir los requisitos del sistema en necesidades reales desde la perspectiva del agricultor, asegurando que cada desarrollo aporte un valor tangible a la gestión del cultivo.

Para garantizar la calidad en la implementación y facilitar las pruebas de software, cada historia ha sido estructurada bajo el formato estándar (Como... quiero... para...) y validada mediante Criterios de Aceptación redactados en lenguaje Gherkin (Dado que, Cuando, Entonces). Este enfoque permite al equipo de desarrollo mantener una trazabilidad clara entre los objetivos de negocio —como la sostenibilidad hídrica y la automatización mediante Inteligencia Artificial— y la ejecución técnica en el hardware y la plataforma web.

Las historias están organizadas en 8 épicas que cubren todo el ciclo de vida del producto: desde la adquisición de datos sensoriales y el diagnóstico visual, hasta la gestión del modelo de suscripción y los estándares de seguridad de la información.

#### US01 - Visualización de propuesta de valor y servicios

| Story ID | US01 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Visualización de propuesta de valor y servicios |
| Descripción | Como visitante, quiero visualizar la información principal del servicio para comprender cómo Grotix soluciona mis problemas de germinación y riego mediante tecnología. |
| Criterios de Aceptación | **Escenario 1: Explicación clara de la propuesta de valor (Hero Section)**<br>Dado que el usuario ingresa a la URL de la landing page, Cuando la página cargue completamente, Entonces el usuario debe visualizar un título impactante (Headline) y una breve descripción que resuma que Grotix es una plataforma de riego inteligente con Inteligencia Artificial.<br><br>**Escenario 2: Detalle de las funcionalidades principales**<br>Dado que el usuario se encuentra en la sección de inicio, Cuando el usuario se dirija hacia la sección de Servicios, Entonces el sistema debe mostrar al menos tres pilares clave: Monitoreo por sensores, Reconocimiento de germinación (IA) y Riego automatizado.<br><br>**Escenario 3: Comprensibilidad del lenguaje**<br>Dado que el usuario lee el contenido de la landing page, Cuando navega por las diferentes secciones de información, Entonces el texto debe ser legible, sin tecnicismos excesivos que impidan a un agricultor o usuario no técnico entender el beneficio del producto.<br><br>**Escenario 4: Fallo en la carga de recursos visuales**<br>Dado que el usuario tiene una conexión a internet inestable o lenta, Cuando accede a la landing page y las imágenes pesadas no cargan, Entonces el sistema debe mostrar un color de fondo sólido coherente y asegurar que el texto sea legible de inmediato para no perder el interés del visitante. |

#### US02 - Enlaces de acceso a la aplicación móvil

| Story ID | US02 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Enlaces de acceso a la aplicación móvil |
| Descripción | Como visitante, quiero tener botones claros de acceso para dirigirme rápidamente a la plataforma donde gestionaré mis cultivos. |
| Criterios de Aceptación | **Escenario 1: Redirección a la aplicación Móvil**<br>Dado que el usuario desea instalar la aplicación en su dispositivo, Cuando el usuario seleccione en el link de “GET NOW!”, Entonces el sistema debe redirigirlo a la tienda de aplicaciones oficial correspondiente al sistema operativo de su smartphone.<br><br>**Escenario 2: Validación de enlaces operativos**<br>Dado que la landing page se encuentra disponible para los usuarios, Cuando un usuario intenta usar cualquiera de los botones de redirección, Entonces el sistema debe asegurar que no existan enlaces rotos (error 404) y que el destino sea el entorno correcto. |

#### US03 - Implementación de CTA

| Story ID | US03 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Implementación de CTA |
| Descripción | Como visitante, quiero encontrar botones de acción claros y visibles para interactuar con la plataforma sin tener que buscar los accesos. |
| Criterios de Aceptación | **Escenario 1: Ubicación estratégica en la sección principal (Hero)**<br>Dado que el usuario accede la landing page, Cuando visualiza la primera sección (Hero Section), Entonces debe aparecer al menos un botón de acción principal ("Comienza ahora") resaltado visualmente.<br><br>**Escenario 2: Persistencia en la barra de navegación (Sticky Header)**<br>Dado que el usuario se desplaza hacia abajo para leer más información, Cuando la barra de navegación se mantenga fija en la parte superior, Entonces un botón de CTA secundario debe permanecer visible para permitir el acceso en cualquier momento.<br><br>**Escenario 3: Tiempo de respuesta excedido (Timeout)**<br>Dado que el usuario hace clic en el CTA "Comienza ahora", Cuando el servidor de la aplicación está bajo mantenimiento o caído, Entonces el sistema debe mostrar una página de error personalizada en lugar de un error genérico del navegador. |

#### US04 - Visualización de misión, visión y equipo

| Story ID | US04 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Visualización de misión, visión y equipo |
| Descripción | Como visitante, quiero conocer la historia, misión y quiénes están detrás de Grotix para generar confianza en la solución tecnológica que ofrecen. |
| Criterios de Aceptación | **Escenario 1: Exposición de la misión y visión del proyecto**<br>Dado que el usuario navega hacia la sección "Nosotros", Cuando visualice el contenido, Entonces el sistema debe presentar de forma clara el nombre del startup y su descripción<br><br>**Escenario 2: Presentación del equipo de trabajo**<br>Dado que el usuario se encuentra en la sección de equipo, Cuando la página cargue los elementos visuales, Entonces el usuario puede leer la misión del startup a través de Grotix.<br><br>**Escenario 3: Fallo en la carga de imágenes de perfil**<br>Dado que el servidor de imágenes tiene un problema de latencia, Cuando el usuario entra a la sección del equipo, Entonces el sistema debe mostrar placeholders (avatares genéricos) con el nombre y cargo del integrante, evitando que la sección se vea vacía o rota. |

#### US05 - Implementación de formulario y canales de contacto

| Story ID | US05 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Implementación de formulario y canales de contacto |
| Descripción | Como visitante, quiero tener un medio de comunicación directo para enviar consultas, reportar problemas o solicitar información personalizada sobre Grotix. |
| Criterios de Aceptación | **Escenario 1: Envío exitoso del formulario de contacto**<br>Dado que el usuario se encuentra en la sección de Contacto, Cuando completa los campos obligatorios (Nombre, Correo, Asunto y Mensaje) y envíe el formulario, Entonces el sistema debe procesar la información y mostrar un mensaje de éxito indicando que el mensaje ha sido enviado correctamente.<br><br>**Escenario 2: Validación de campos obligatorios**<br>Dado que el usuario intenta enviar el formulario, Cuando deja uno o más campos obligatorios vacíos y lo envía, Entonces el sistema debe impedir el envío y resaltar los campos faltantes con un mensaje de error descriptivo.<br><br>**Escenario 3: Disponibilidad de métodos de contacto alternativos**<br>Dado que el usuario prefiere no usar el formulario, Cuando visualiza la sección de contacto, Entonces el sistema debe mostrar claramente otros medios como el correo corporativo o un enlace directo a WhatsApp.<br><br>**Escenario 4: Fallo en el envío por pérdida de conexión**<br>Dado que el usuario envía el formulario, Cuando el servicio de mensajería falla o no hay internet, Entonces el sistema debe mostrar un mensaje de error y no borrar los datos que el usuario ya escribió en el formulario.<br><br>**Escenario 5: Validación de formato de correo**<br>Dado que el usuario ingresa un texto que no es un correo, Cuando intenta enviar el formulario, Entonces el sistema debe detectar el formato inválido y pedir un correo electrónico real. |

#### US06 - Enlaces a redes sociales

| Story ID | US06 |
|---|---|
| Epic ID | E01 - Presencia Digital y Propuesta de Valor |
| Título | Enlaces a redes sociales |
| Descripción | Como visitante, quiero encontrar los accesos a las redes sociales oficiales de Grotix para mantenerme actualizado sobre las novedades y el desarrollo del proyecto. |
| Criterios de Aceptación | **Escenario 1: Ubicación en el pie de página (Footer)**<br>Dado que el usuario se desplaza hasta el final de la landing page, Cuando visualice el área del footer, Entonces el sistema debe mostrar enlaces de acceso de las redes sociales oficiales (Instagram, LinkedIn, Facebook.<br><br>**Escenario 2: Uso de iconografía oficial y reconocible**<br>Dado que el usuario observa la sección de redes sociales, Cuando carguen los elementos visuales, Entonces los iconos utilizados deben corresponder a los logotipos oficiales de cada plataforma para facilitar su identificación inmediata.<br><br>**Escenario 3: Validación de enlaces externos activos**<br>Dado que el sitio está en producción, Cuando el administrador del sitio actualice las URLs de las redes sociales, Entonces el sistema debe asegurar que los enlaces dirijan exactamente a los perfiles oficiales de Grotix y no a páginas de inicio genéricas de las plataformas.<br><br>**Escenario 4: Apertura de enlaces en ventana nueva**<br>Dado que el usuario selecciona un ícono de red social, Cuando el enlace se activa, Entonces el sistema debe abrir la red social en una pestaña nueva para asegurar que el usuario no abandone la landing page de Grotix accidentalmente. |

#### US07 - Implementación de sistemas de navegación simplificada

| Story ID | US07 |
|---|---|
| Epic ID | E02 - Optimización de Usabilidad y Rendimiento Web |
| Título | Implementación de sistemas de navegación simplificada |
| Descripción | Como visitante, quiero disponer de elementos de navegación claros y accesibles para encontrar la información que busco sin esfuerzo y reducir la tasa de abandono. |
| Criterios de Aceptación | **Escenario 1: Menú de navegación persistente**<br>Dado que el usuario se desplaza hacia abajo en la página, Cuando la navegación principal se mantenga fija en el borde superior, Entonces el usuario debe poder acceder a las secciones del sitio en cualquier momento sin tener que volver al inicio manualmente.<br><br>**Escenario 2: Implementación de navegación móvil**<br>Dado que el usuario accede desde un dispositivo con pantalla reducida (móvil/tablet), Cuando el ancho de la pantalla sea inferior al punto de quiebre (breakpoint) definido, Entonces el menú horizontal debe colapsar en un icono de "hamburguesa" que despliegue las opciones de forma vertical y legible.<br><br>**Escenario 3: Desplazamiento suave entre secciones**<br>Dado que el usuario selecciona un enlace del menú que apunta a una sección de la misma página, Cuando el navegador realice la transición, Entonces el desplazamiento debe ser fluido y no un salto brusco, permitiendo al usuario mantener el contexto visual.<br><br>**Escenario 4: Resaltado de sección activa en el menú**<br>Dado que el usuario se encuentra visualizando una sección específica, Cuando el elemento del menú correspondiente esté activo, Entonces este debe cambiar su estilo para indicar visualmente al usuario en qué parte de la página se encuentra ubicado.<br><br>**Escenario 5: Cierre del menú móvil tras selección o acción externa**<br>Dado que el usuario tiene abierto el menú de hamburguesa en su móvil, Cuando haga clic en un enlace o toque el área fuera del menú, Entonces el sistema debe cerrar el menú automáticamente para permitir la visualización de la sección seleccionada sin obstrucciones.<br><br>**Escenario 6: Prevención de superposición**<br>Dado que el usuario utiliza el menú persistente, Cuando se desplaza sobre secciones con elementos flotantes o imágenes pesadas, Entonces el menú debe permanecer siempre en la capa superior sin que el contenido de la página lo tape. |

#### US08 - Implementación de Identidad y Consistencia Visual

| Story ID | US08 |
|---|---|
| Epic ID | E02 - Optimización de Usabilidad y Rendimiento Web |
| Título | Implementación de Identidad y Consistencia Visual |
| Descripción | Como visitante de la landing page, quiero una interfaz visual coherente para navegar de forma clara y agradable. |
| Criterios de Aceptación | **Escenario 1: Aplicación de la paleta de colores y temas**<br>Dado que el usuario navega por cualquier sección de la landing page, Cuando se visualicen los elementos de la interfaz, Entonces estos deben seguir una jerarquía de colores basada con contrastes que cumplan los estándares de accesibilidad WCAG.<br><br>**Escenario 2: Jerarquía Tipográfica estandarizada**<br>Dado que se presenta contenido textual en la página, Cuando el navegador renderice los textos, Entonces el sistema debe aplicar una escala tipográfica clara que facilite la lectura rápida. |

#### US09 - Optimización de tiempos de respuesta y carga inicial

| Story ID | US09 |
|---|---|
| Epic ID | E02 - Optimización de Usabilidad y Rendimiento Web |
| Título | Optimización de tiempos de respuesta y carga inicial |
| Descripción | Como visitante, quiero que la landing page cargue de forma inmediata para acceder a la información sin frustraciones y evitar el abandono del sitio. |
| Criterios de Aceptación | **Escenario 1: Tiempo de carga**<br>Dado que el usuario ingresa la URL de Grotix en su navegador, Cuando se inicie la petición al servidor, Entonces la página debe cargar en menos de 1.5 segundos en condiciones normales de red.<br><br>**Escenario 2: Implementación de carga diferida**<br>Dado que la landing page tiene secciones extensas, Cuando el usuario abra la página, Entonces solo se deben cargar los recursos visibles en la pantalla inicial, posponiendo la carga de las imágenes inferiores hasta que el usuario se desplaza hacia ellas.<br><br>**Escenario 3: Rendimiento en dispositivos móviles**<br>Dado que un usuario accede desde una conexión de datos móviles, Cuando interactúe con la landing page, Entonces el tiempo total de interacción no debe superar los 3.5 segundos, garantizando una experiencia fluida incluso en redes de velocidad media.<br><br>**Escenario 4: Tiempo de espera de respuesta de red**<br>Dado que la red del usuario es lenta, Cuando el tiempo de carga supera los 5 segundos, Entonces el sistema debe dar prioridad a la carga del texto (HTML/CSS) sobre los scripts pesados para que el usuario pueda empezar a leer aunque las animaciones no estén listas. |

#### US10 - Vinculación del Microcontrolador con la Aplicación

| Story ID | US10 |
|---|---|
| Epic ID | E03 - Monitoreo Sensorial y Sincronización de Dispositivos |
| Título | Vinculación del Microcontrolador con la Aplicación |
| Descripción | Como usuario de Grotix, quiero vincular mi microcontrolador con la aplicación para establecer un canal de comunicación seguro y visualizar la telemetría de mis plantas. |
| Criterios de Aceptación | **Escenario 1: Emparejamiento exitoso del dispositivo**<br>Dado que el microcontrolador se encuentra en modo de configuración y la aplicación está abierta, Cuando el usuario ingresa el ID único del dispositivo, Entonces el sistema debe validar el identificador y confirmar el enlace exitoso, mostrando el dispositivo como "Activo" en el perfil del usuario.<br><br>**Escenario 2: Persistencia de la conexión tras reinicio**<br>Dado que el microcontrolador ya ha sido vinculado con éxito previamente, Cuando el hardware se reinicie debido a un corte de energía o mantenimiento, Entonces el sistema debe reconectarse automáticamente a la red y a la aplicación sin requerir que el usuario repita el proceso de vinculación manual.<br><br>**Escenario 3: Validación de identificador único existente**<br>Dado que el usuario intenta vincular un dispositivo, Cuando ingresa un ID que no existe en la base de datos de manufactura de Grotix o que ya está vinculado a otra cuenta, Entonces el sistema debe mostrar un mensaje de error. |

#### US11 - Monitoreo fiel de las condiciones del entorno

| Story ID | US11 |
|---|---|
| Epic ID | E03 - Monitoreo Sensorial y Sincronización de Dispositivos |
| Título | Monitoreo fiel de las condiciones del entorno |
| Descripción | Como usuario de Grotix, quiero que mi sistema detecte con precisión los cambios en mi cultivo para confiar en que la información que veo en la app es el reflejo real de mis plantas. |
| Criterios de Aceptación | **Escenario 1: Reflejo inmediato de cambios físicos**<br>Dado que el usuario está observando el dashboard de la aplicación, Cuando ocurra un cambio físico en el cultivo (ej. se empieza a regar o sale el sol), Entonces el sistema debe procesar la señal del sensor y actualizar el valor en la pantalla.<br><br>**Escenario 2: Verificación de la integridad del sensor**<br>Dado que el sistema está monitoreando en segundo plano, Cuando un sensor se desconecte o falle, Entonces el usuario debe recibir una notificación o aviso visual de "Sensor no disponible" para que pueda revisar la instalación física.<br><br>**Escenario 3: Correspondencia entre el estado físico y el dato digital**<br>Dado que el usuario introduce el sensor en un sustrato más húmedo, Cuando el sistema procese la señal eléctrica, Entonces el valor porcentual de humedad en la app debe aumentar proporcionalmente, validando la correcta comunicación hardware-software. |

#### US12 - Actualización periódica y automática de telemetría

| Story ID | US12 |
|---|---|
| Epic ID | E03 - Monitoreo Sensorial y Sincronización de Dispositivos |
| Título | Actualización periódica y automática de telemetría |
| Descripción | Como usuario de Grotix, quiero que mi sistema capture datos cada 15 minutos para mantener un seguimiento detallado de la evolución de mi cultivo sin intervención manual. |
| Criterios de Aceptación | **Escenario 1: Ejecución del ciclo de lectura programado**<br>Dado que el microcontrolador se encuentra encendido y conectado a la red, Cuando el temporizador interno alcance el intervalo de 15 minutos, Entonces el sistema debe activar los sensores, realizar la captura de datos y enviarlos automáticamente a la nube.<br><br>**Escenario 2: Visualización de la última actualización**<br>Dado que el usuario consulta el estado de su planta en la aplicación, Cuando se reciba una nueva lectura programada, Entonces la interfaz debe actualizar el mensaje de "Última sincronización" con la hora y fecha exacta del reporte para dar certeza de la vigencia del dato..<br><br>**Escenario 3: Optimización de recursos del dispositivo**<br>Dado que el sistema opera bajo una frecuencia de 15 minutos, Cuando el dispositivo termine de enviar la lectura, Entonces debe entrar en un estado de espera o bajo consumo hasta el siguiente ciclo, evitando el sobrecalentamiento del hardware o el uso innecesario de ancho de banda.<br><br>**Escenario 4: Reanudación del ciclo tras desconexión**<br>Dado que el dispositivo sufre una desconexión temporal durante el intervalo de espera, Cuando la conexión se restablezca, Entonces el sistema debe sincronizar el reloj interno y retomar el ciclo de lectura de 15 minutos de forma inmediata para minimizar los vacíos de información. |

#### US13 - Garantía de exactitud en la medición de datos

| Story ID | US13 |
|---|---|
| Epic ID | E03 - Monitoreo Sensorial y Sincronización de Dispositivos |
| Título | Garantía de exactitud en la medición de datos |
| Descripción | Como usuario, quiero que las mediciones tengan un margen de error máximo del 2% para asegurar que mis plantas reciban el tratamiento exacto que necesitan sin riesgos de sobre-riego o sequedad. |
| Criterios de Aceptación | **Escenario 1: Validación contra valores de referencia**<br>Dado que el microcontrolador está realizando lecturas en un entorno con condiciones controladas, Cuando el sistema procese los datos de los sensores de humedad y temperatura, Entonces el valor digital reportado debe tener una desviación máxima del 2% en comparación con un instrumento de medición patrón o de referencia industrial.<br><br>**Escenario 2: Filtrado de ruido eléctrico en la señal**<br>Dado que el sensor realiza múltiples capturas rápidas para promediar un dato, Cuando existan fluctuaciones eléctricas menores en el ambiente, Entonces el sistema debe aplicar algoritmos de suavizado (como media móvil) para eliminar valores atípicos y asegurar que el dato final enviado a la nube sea estable y preciso.<br><br>**Escenario 3: Resolución de la conversión Analógico-Digital (ADC)**<br>Dado que el sensor entrega una señal de voltaje analógica, Cuando el microcontrolador (ESP32) convierta dicha señal a un valor digital, Entonces el mapeo del algoritmo debe garantizar que la resolución sea lo suficientemente fina para detectar cambios mínimos, manteniendo el error de cuantización por debajo del umbral de precisión requerido.<br><br>**Escenario 4: Detección de inconsistencias físicas**<br>Dado que el sistema recibe una serie de lecturas constantes, Cuando ocurra un salto brusco o físicamente imposible en los datos (ej: la humedad pasa de 40% a 90% en un segundo sin riego activo), Entonces el sistema debe marcar la lectura como "pendiente de validación" y repetir la captura para confirmar que el dato reportado al usuario sea real y exacto. |

#### US14 - Dashboard de Monitoreo Integral y Resumen de Estado

| Story ID | US14 |
|---|---|
| Epic ID | E04 - Administración de Cultivos y Monitoreo Multi-Entorno |
| Título | Dashboard de Monitoreo Integral y Resumen de Estado |
| Descripción | Como usuario de Grotix, quiero contar con un dashboard que resuma las variables de humedad, luz y temperatura para visualizar el estado de salud de mi cultivo de forma rápida y centralizada. |
| Criterios de Aceptación | **Escenario 1: Vista consolidada del Dashboard (Resumen)**<br>Dado que el usuario abre la aplicación y se dirige a la vista principal del cultivo, Cuando el sistema cargue los datos, Entonces el usuario debe visualizar un dashboard que agrupe de forma simultánea los indicadores actuales de humedad, luz y temperatura en una sola pantalla sin necesidad de navegación adicional.<br><br>**Escenario 2: Interpretación de la humedad del suelo**<br>Dado que el sensor de humedad está enviando datos en tiempo real, Cuando el usuario observe el dashboard, Entonces el sistema debe mostrar el valor porcentual (0% a 100%) y una etiqueta descriptiva que indique si el nivel es "Bajo", "Óptimo" o "Excesivo".<br><br>**Escenario 3: Reporte de intensidad lumínica y radiación**<br>Dado que la planta requiere luz para la fotosíntesis, Cuando el sistema procese la señal del sensor de luz, Entonces el dashboard debe representar la intensidad en una escala legible (ej. Lux o niveles bajo/medio/alto) para que el usuario determine si la ubicación es adecuada.<br><br>**Escenario 4: Actualización dinámica de temperatura**<br>Dado que el ambiente del cultivo sufre variaciones térmicas, Cuando el sensor de temperatura realice una nueva lectura, Entonces el valor en pantalla debe actualizarse automáticamente en grados Celsius (°C), permitiendo al usuario detectar posibles riesgos de estrés térmico de inmediato.<br><br>**Escenario 5: Identificación visual de alertas en el resumen**<br>Dado que el sistema detecta que una de las variables está fuera de los umbrales seguros, Cuando el usuario visualice el dashboard de resumen, Entonces el indicador de la variable afectada debe cambiar de color para resaltar la anomalía y facilitar una respuesta rápida. |

#### US15 - Organización de dispositivos por zonas y especies

| Story ID | US15 |
|---|---|
| Epic ID | E04 - Administración de Cultivos y Monitoreo Multi-Entorno |
| Título | Organización de dispositivos por zonas y especies |
| Descripción | Como usuario de Grotix, quiero organizar mis dispositivos por zonas geográficas y tipos de cultivo para administrar diversos tipos de plantas de manera simultánea y ordenada. |
| Criterios de Aceptación | **Escenario 1: Creación y personalización de zonas de cultivo**<br>Dado que el usuario se encuentra en la sección de configuración de la aplicación, Cuando seleccione la opción para añadir una zona, Entonces el sistema debe permitirle asignar un nombre personalizado (ej. "Bandeja Norte", "Invernadero 1") para diferenciar las áreas de trabajo.<br><br>**Escenario 2: Asignación de hardware a zonas y tipos de planta**<br>Dado que el usuario cuenta con un nuevo microcontrolador vinculado, Cuando proceda a configurar el dispositivo, Entonces el sistema debe permitirle asociar dicho hardware a una zona específica y seleccionar el tipo de planta (ej. Rabanito, Albahaca) que será monitoreada en ese punto.<br><br>**Escenario 3: Visualización de múltiples áreas en el panel principal**<br>Dado que el usuario tiene configuradas al menos dos zonas de cultivo diferentes, Cuando acceda a la vista general de la aplicación, Entonces el sistema debe presentar tarjetas o secciones independientes para cada zona, permitiendo observar el estado de cada una de forma simultánea.<br><br>**Escenario 4: Filtrado y búsqueda por tipo de cultivo**<br>Dado que el usuario gestiona una cantidad considerable de dispositivos y plantas, Cuando utilice la barra de búsqueda o filtros de la aplicación, Entonces el sistema debe mostrar únicamente las zonas o dispositivos que coincidan con el tipo de planta seleccionado (ej. mostrar solo "Lechugas").<br><br>**Escenario 5: Reubicación de dispositivos entre zonas**<br>Dado que un dispositivo ya está operativo en una zona determinada, Cuando el usuario decida mover el hardware físicamente a otro cultivo, Entonces el sistema debe permitir editar la información de la zona y el tipo de planta asociada al dispositivo sin necesidad de desvincularlo y volverlo a registrar. |

#### US16 - Configuración de parámetros y umbrales de control

| Story ID | US16 |
|---|---|
| Epic ID | E04 - Administración de Cultivos y Monitoreo Multi-Entorno |
| Título | Configuración de parámetros y umbrales de control |
| Descripción | Como usuario que busca optimizar su cosecha, quiero configurar los rangos ideales de humedad, luz y temperatura para que el sistema Grotix actúe según las necesidades específicas de mi tipo de cultivo. |
| Criterios de Aceptación | **Escenario 1: Carga de valores predeterminados por especie**<br>Dado que el usuario ha seleccionado un tipo de planta (ej. Lechuga) en una zona, Cuando acceda a la configuración de parámetros, Entonces el sistema debe sugerir automáticamente los umbrales óptimos de humedad, luz y temperatura basados en una biblioteca técnica inteligente.<br><br>**Escenario 2: Ajuste manual de rangos de operación**<br>Dado que el usuario desea experimentar con condiciones específicas, Cuando modifique manualmente el valor mínimo o máximo de una variable (ej. subir el umbral de riego del 40% al 50%), Entonces el sistema debe guardar esta nueva configuración como la regla activa para ese dispositivo específico.<br><br>**Escenario 3: Validación de rangos lógicos**<br>Dado que el usuario introduce nuevos valores de configuración, Cuando intente guardar un valor que sea físicamente imposible o incoherente (ej. humedad del 150% o temperatura de -100 °C), Entonces el sistema debe impedir el guardado y mostrar una alerta solicitando valores dentro del rango de operación del sensor.<br><br>**Escenario 4: Sincronización de parámetros con el controlador**<br>Dado que el usuario ha guardado una nueva configuración en la aplicación, Cuando el microcontrolador realice su siguiente ciclo de comunicación, Entonces el sistema debe actualizar los umbrales en el hardware para que la lógica de riego autónomo se ejecute con los nuevos parámetros. |

#### US17 - Persistencia de datos ante pérdida de conectividad

| Story ID | US17 |
|---|---|
| Epic ID | E04 - Administración de Cultivos y Monitoreo Multi-Entorno |
| Título | Persistencia de datos ante pérdida de conectividad |
| Descripción | Como usuario, quiero que el sistema guarde los datos localmente cuando no haya señal para no perder el historial de monitoreo de mis plantas durante fallos de internet. |
| Criterios de Aceptación | **Escenario 1: Almacenamiento local por falta de señal**<br>Dado que el microcontrolador intenta enviar una lectura programada (cada 15 min), Cuando el sistema detecte que no hay conexión al servidor o a la red Wi-Fi, Entonces el dispositivo debe almacenar el dato (humedad, luz, temperatura y timestamp) en su memoria local interna de forma temporal.<br><br>**Escenario 2: Sincronización automática al recuperar conexión**<br>Dado que el dispositivo tiene datos guardados en su memoria local por una desconexión previa, Cuando se restablezca la conexión a internet, Entonces el sistema debe enviar automáticamente todos los registros acumulados al servidor antes de continuar con las lecturas en tiempo real. |

#### US18 - Notificaciones automáticas por condiciones críticas y cambios de estado

| Story ID | US18 |
|---|---|
| Epic ID | E04 - Administración de Cultivos y Monitoreo Multi-Entorno |
| Título | Notificaciones automáticas por condiciones críticas y cambios de estado |
| Descripción | Como usuario, quiero recibir alertas automáticas en mi dispositivo para estar informado cuando empiecen ciclos de riego o un dispositivo deje de estar disponible. |
| Criterios de Aceptación | **Escenario 1: Notificación de inicio de riego**<br>Dado que el sistema activa un ciclo de riego para una zona específica, Cuando el registro de inicio (ActuatorLog) es guardado exitosamente en la base de datos, Entonces el sistema debe disparar una notificación push al dispositivo del usuario confirmando que el riego ha comenzado en dicha zona.<br><br>**Escenario 2: Notificación de fin de riego**<br>Dado que el ciclo de riego se completa satisfactoriamente según la duración programada, Cuando se actualiza el registro de finalización en el ActuatorLog, Entonces el sistema debe enviar una notificación push al usuario informando que el ciclo de riego ha finalizado y el sistema ha vuelto a estado de espera.<br><br>**Escenario 3: Notificación por dispositivo offline**<br>Dado que la tarea de segundo plano detecta que el lastSeen de un microcontrolador no se ha actualizado en el periodo de gracia configurado, Cuando el estado del dispositivo es marcado como "Desconectado" en el sistema, Entonces el sistema debe emitir una alerta crítica al usuario indicando que el dispositivo se encuentra offline y requiere revisión técnica. |

#### US19 - Activación manual del sistema de irrigación

| Story ID | US19 |
|---|---|
| Epic ID | E05 - Gestión de Irrigación Autónoma y Control Hídrico |
| Título | Activación manual del sistema de irrigación |
| Descripción | Como usuario de Grotix, quiero poder activar o desactivar el riego manualmente desde la aplicación para intervenir en el cuidado de mi planta sin depender exclusivamente de la autonomía del sistema. |
| Criterios de Aceptación | **Escenario 1: Activación remota del actuador**<br>Dado que el usuario se encuentra en el panel de control de una zona de cultivo, Cuando active el riego manual, Entonces el sistema debe enviar una señal inmediata al microcontrolador para abrir la válvula de agua e indicar que el riego está en curso desde la app.<br><br>**Escenario 2: Desactivación manual**<br>Dado que el riego manual está activo y el agua está fluyendo, Cuando el usuario detenga el riego, Entonces el sistema debe cerrar la válvula de forma instantánea y actualizar el estado en la interfaz para confirmar que el flujo se ha detenido.<br><br>**Escenario 3: Prioridad del mando manual sobre el automático**<br>Dado que el sistema se encuentra en modo autónomo, Cuando el usuario ejecute una acción manual de riego, Entonces el sistema debe pausar temporalmente la lógica automática para obedecer la orden directa del usuario, evitando conflictos de decisión.<br><br>**Escenario 4: Temporizador de seguridad para riego manual**<br>Dado que el usuario ha activado el riego manualmente, Cuando transcurra un tiempo máximo de seguridad definido sin que el usuario lo detenga, Entonces el sistema debe cerrar la válvula automáticamente para prevenir inundaciones o desperdicio de agua por olvido. |

#### US20 - Automatización del riego mediante modelos de aprendizaje automático

| Story ID | US20 |
|---|---|
| Epic ID | E05 - Gestión de Irrigación Autónoma y Control Hídrico |
| Título | Automatización del riego mediante modelos de aprendizaje automático |
| Descripción | Como usuario, quiero que el sistema active el riego por sí solo para garantizar que mis plantas reciben agua sólo cuando lo necesitan. |
| Criterios de Aceptación | **Escenario 1: Activación por detección de necesidad hídrica**<br>Dado que el sistema está operando en modo autónomo, Cuando procese los datos de los sensores y determine que la planta requiere hidratación, Entonces el sistema debe enviar la orden de apertura a la válvula de riego sin intervención del usuario.<br><br>**Escenario 2: Optimización del suministro de agua**<br>Dado que se ha iniciado un evento de riego automático, Cuando el sistema calcule la cantidad de agua a suministrar, Entonces debe ajustar el tiempo de apertura de la válvula según el tipo de cultivo y su etapa de crecimiento, buscando el consumo más eficiente posible.<br><br>**Escenario 3: Registro de fin de ciclo de riego**<br>Dado que el sistema ha suministrado la cantidad de agua calculada, Cuando el sensor de humedad confirme el incremento en el sustrato, Entonces el sistema debe cerrar la válvula, volver al modo de monitoreo y registrar la duración del riego en el historial.<br><br>**Escenario 4: Postergación de riego por pronóstico de lluvia**<br>Dado que el sistema ha determinado una necesidad hídrica según los sensores de humedad, Cuando el sistema consulte el Servicio Meteorológico Externo y detecte una alta probabilidad de lluvia durante la jornada, Entonces el sistema debe postergar la activación del riego automático, registrar la decisión como "Ahorro por clima" y enviar una notificación al usuario informando la decisión de optimización. |

#### US21 - Generación y descarga de reportes históricos

| Story ID | US21 |
|---|---|
| Epic ID | E05 - Gestión de Irrigación Autónoma y Control Hídrico |
| Título | Generación y descarga de reportes históricos |
| Descripción | Como usuario, quiero generar y descargar reportes detallados de riego para analizar el consumo de agua y la eficiencia del sistema en periodos de tiempo específicos. |
| Criterios de Aceptación | **Escenario 1: Selección de rangos de tiempo predefinidos**<br>Dado que el usuario se encuentra en la sección de Reportes, Cuando despliegue las opciones de tiempo, Entonces el sistema debe permitirle seleccionar periodos específicos: semanal, mensual, trimestral (3 meses), semestral (6 meses) y anual (12 meses).<br><br>**Escenario 2: Visualización previa de métricas clave**<br>Dado que el usuario ha seleccionado un periodo de reporte, Cuando el sistema procese la información, Entonces debe mostrar en pantalla un resumen con la telemetria promedio y la frecuencia de riego.<br><br>**Escenario 3: Exportación a formatos estándar**<br>Dado que el reporte ha sido generado correctamente en la interfaz, Cuando el usuario seleccione la opción para descargar, Entonces el sistema debe permitir elegir entre un formato PDF o un archivo CSV/Excel. |

#### US22 - Gestión de registro fotográfico de cultivos.

| Story ID | US22 |
|---|---|
| Epic ID | E06 - Subsistema de Visión Artificial y Diagnóstico Fenológico. |
| Título | Gestión de registro fotográfico de cultivos. |
| Descripción | Como usuario, quiero que el sistema reconozca fotos de mis cultivos para poder subir imágenes. |
| Criterios de Aceptación | **Escenario 1: Acceso a la funcionalidad de captura o carga**<br>Dado que estoy en la pantalla de detalle de una zona de cultivo, Cuando presiono el botón de "Añadir registro visual", Entonces el sistema debe desplegar un menú contextual que me permita elegir entre tomar una fotografía nueva con la cámara o seleccionar un archivo existente desde la galería del dispositivo.<br><br>**Escenario 2: Validación de formato y calidad de imagen**<br>Dado que he seleccionado o capturado una imagen, Cuando el sistema procesa el archivo antes de la subida, Entonces debe verificar que el formato sea compatible (JPG o PNG) y que la resolución cumpla con el estándar mínimo definido (640x480 píxeles) para asegurar la claridad del registro visual.<br><br>**Escenario 3: Confirmación de subida y persistencia**<br>Dado que la imagen cumple con los criterios de validación, Cuando el proceso de subida al servidor finaliza exitosamente, Entonces la aplicación debe mostrar un mensaje de confirmación al usuario y efectuar el diagnóstico del cultivo. |

#### US23 - Clasificación del estado fenológico mediante Inteligencia Artificial

| Story ID | US23 |
|---|---|
| Epic ID | E06 - Subsistema de Visión Artificial y Diagnóstico Fenológico. |
| Título | Clasificación del estado fenológico mediante Inteligencia Artificial |
| Descripción | Como usuario de Grotix, quiero que el sistema identifique automáticamente la etapa de crecimiento de mi planta para conocer su progreso biológico sin necesidad de ser un experto en botánica. |
| Criterios de Aceptación | **Escenario 1: Categorización exitosa de estados de crecimiento**<br>Dado que la Inteligencia Artificial ha recibido una imagen pre-procesada, Cuando se ejecute el algoritmo de inferencia, Entonces el sistema debe clasificar la planta en una de las categorías definidas con base en el dataset de entrenamiento.<br><br>**Escenario 2: Umbral de confianza de la inferencia**<br>Dado que el modelo genera un resultado de clasificación, Cuando el nivel de confianza sea inferior al 75%, Entonces el sistema debe marcar el estado como "Indeterminado" y disparar la lógica de reintento de la US22 para evitar diagnósticos erróneos.<br><br>**Escenario 3: Actualización automática del perfil del cultivo**<br>Dado que el modelo ha identificado un cambio de etapa (ej: de Semilla a Germinación), Cuando se valide el resultado, Entonces el sistema debe actualizar automáticamente el estado actual en la base de datos y reflejarlo de inmediato en el dashboard del usuario. |

#### US24 - Registro, inicio y cierre de sesión de usuario

| Story ID | US24 |
|---|---|
| Epic ID | E07 - Gestión de Identidad |
| Título | Registro, inicio y cierre de sesión de usuario |
| Descripción | Como usuario de Grotix, quiero contar con un sistema de autenticación seguro para proteger mis datos agrícolas y asegurar que solo yo pueda gestionar mis dispositivos y suscripciones. |
| Criterios de Aceptación | **Escenario 1: Registro exitoso de nuevo usuario**<br>Dado que el usuario se encuentra en la pantalla de creación de cuenta, Cuando ingresa un correo electrónico válido, una contraseña segura y completa los datos requeridos, Entonces el sistema debe crear su perfil en la base de datos, enviar un correo de confirmación y redirigirlo al dashboard inicial.<br><br>**Escenario 2: Inicio de sesión con credenciales válidas**<br>Dado que el usuario ya tiene una cuenta registrada y activa, Cuando ingresa sus credenciales correctas (email y password) en el formulario de login, Entonces el sistema debe validar la identidad, generar un token de sesión seguro y otorgar acceso total a las funcionalidades de la aplicación.<br><br>**Escenario 3: Validación de seguridad en el inicio de sesión**<br>Dado que el usuario intenta acceder a su cuenta, Cuando introduce un correo no registrado o una contraseña incorrecta, Entonces el sistema debe denegar el acceso y mostrar un mensaje de error genérico para evitar dar pistas a posibles atacantes.<br><br>**Escenario 4: Cierre de sesión seguro**<br>Dado que el usuario ha finalizado su actividad en la aplicación, Cuando seleccione la opción de cerrar sesión, Entonces el sistema debe invalidar el token de sesión actual, limpiar los datos sensibles de la caché del navegador y redirigirlo a la pantalla de bienvenida.<br><br>**Escenario 5: Validación de formato y fortaleza de datos**<br>Dado que el usuario está completando el formulario de registro o login, Cuando el sistema detecte un formato de email inválido o una contraseña que no cumple con los requisitos mínimos de seguridad, Entonces debe impedir el envío del formulario y resaltar los campos erróneos con mensajes de ayuda en tiempo real. |

#### US25 - Modificación de datos personales y de contacto

| Story ID | US25 |
|---|---|
| Epic ID | E07 - Gestión de Identidad |
| Título | Modificación de datos personales y de contacto |
| Descripción | Como usuario de Grotix, quiero poder actualizar mi información personal para asegurar que las notificaciones, reportes y facturación se dirijan a los canales de contacto correctos. |
| Criterios de Aceptación | **Escenario 1: Edición de campos básicos**<br>Dado que el usuario se encuentra en la sección de perfil, Cuando modifique campos como nombre, apellidos o teléfono y guarde los cambios, Entonces el sistema debe actualizar la base de datos y mostrar un mensaje de confirmación exitosa.<br><br>**Escenario 2: Validación de datos en tiempo real**<br>Dado que el usuario intenta modificar su información, Cuando ingrese un número de teléfono con formato inválido o deje campos obligatorios vacíos, Entonces el sistema debe resaltar el error y deshabilitar la opción de guardado hasta que los datos sean lógicos.<br><br>**Escenario 3: Cambio de correo electrónico con verificación**<br>Dado que el usuario solicita cambiar su dirección de correo electrónico principal, Cuando el sistema guarde el cambio, Entonces debe enviar automáticamente un mensaje de validación a la nueva dirección para confirmar que el usuario tiene acceso a dicho buzón antes de dar por definitivo el cambio.<br><br>**Escenario 4: Seguridad ante cambios sensibles**<br>Dado que el usuario intenta realizar cambios críticos en su perfil (como el correo o la contraseña), Cuando el sistema procese la solicitud, Entonces debe solicitar la contraseña actual del usuario como medida de re-autenticación para prevenir cambios no autorizados en caso de descuido del dispositivo. |

#### US26 - Configuración y gestión de alertas de usuario

| Story ID | US26 |
|---|---|
| Epic ID | E07 - Gestión de Identidad |
| Título | Configuración y gestión de alertas de usuario |
| Descripción | Como usuario de Grotix, quiero personalizar mis preferencias de notificación para recibir información relevante si es que lo deseo. |
| Criterios de Aceptación | **Escenario 1: Activar/Desactivar notificaciones**<br>Dado que el usuario se encuentra en los ajustes de notificación, Cuando active o desactive el toggle de cada canal (Push y Correo electrónico), Entonces el sistema debe guardar estas preferencias y enviar las futuras alertas únicamente a través de los medios seleccionados por el usuario.<br><br>**Escenario 2: Filtrado por categoría de alerta**<br>Dado que Grotix genera diferentes tipos de avisos, Cuando el usuario elija qué categorías desea recibir (ej: solo "Alertas Críticas de Riego" y no "Actualizaciones de Germinación"), Entonces el sistema debe filtrar los envíos para que el usuario solo sea interrumpido por los eventos que él mismo marcó como prioritarios.<br><br>**Escenario 3: Persistencia y sincronización de preferencias**<br>Dado que el usuario ha modificado sus preferencias de notificación, Cuando guarde los cambios y cierre la aplicación, Entonces el servidor de Grotix debe actualizar estas reglas de inmediato, garantizando que el motor de notificaciones aplique la nueva configuración sin retrasos. |

#### US27 - Visualización de estado de servicios

| Story ID | US27 |
|---|---|
| Epic ID | E07 - Gestión de Identidad |
| Título | Visualización de estado de servicios |
| Descripción | Como usuario, quiero visualizar el estado de mis servicios inteligentes, para estar informado sobre la disponibilidad de la analítica y el riego automático sin gestionar pagos complejos desde el móvil. |
| Criterios de Aceptación | **Escenario 1: Consulta de estado de servicios inteligentes**<br>Dado que el usuario se encuentra en la sección de Perfil, Cuando acceda al detalle de "Estado del Servicio", Entonces el sistema debe mostrar si las funciones de IA y Riego Automático están Habilitadas o Suspendidas según el pago realizado en la web.<br><br>**Escenario 2: Visualización del cronograma de campaña**<br>Dado que el agricultor tiene una campaña activa, Cuando consulte la sección de suscripción en la App, Entonces el sistema debe mostrar la fecha de inicio, la fecha de fin de la campaña actual y los días restantes de servicio inteligente.<br><br>**Escenario 3: Acceso restringido por periodo de descanso**<br>Dado que la campaña ha finalizado y el servicio está suspendido, Cuando el usuario intente activar manualmente un análisis de IA o riego automático, Entonces la App debe mostrar un mensaje informativo explicando que el servicio está en "Modo Lectura" y requiere reactivación vía web. |

#### US28 - Diseño consistente y adaptabilidad multiplataforma

| Story ID | US28 |
|---|---|
| Epic ID | E08 - Experiencia de Usuario y Atributos de Calidad del Software |
| Título | Diseño consistente y adaptabilidad multiplataforma |
| Descripción | Como usuario de Grotix, quiero una interfaz intuitiva que siga estándares de diseño modernos para navegar por la aplicación fácilmente. |
| Criterios de Aceptación | **Escenario 1: Consistencia visual**<br>Dado que el usuario navega por las diferentes secciones de la aplicación, Cuando interactúe con botones, tarjetas, menús y formularios, Entonces todos los elementos deben cumplir con los estándares de diseño (elevación, tipografía, iconografía y paleta de colores), garantizando una experiencia visual profesional y cohesiva.<br><br>**Escenario 2: Navegación intuitiva y de bajo esfuerzo cognitivo**<br>Dado que un agricultor puede no estar familiarizado con términos técnicos complejos, Cuando intente realizar tareas críticas (como regar o ver la cámara), Entonces el sistema debe ofrecer un menú de navegación claro, iconos representativos y etiquetas directas que le permitan completar la acción rápidamente desde la pantalla de inicio.<br><br>**Escenario 3: Tiempo de respuesta visual**<br>Dado que el usuario solicita un cambio de sección o la carga de datos, Cuando la red sea lenta o el servidor esté procesando la información, Entonces la aplicación debe mostrar estados de carga (ej: spinners) para informar al usuario que el sistema está trabajando y evitar la sensación de que la app se ha congelado. |

#### US29 - Acceso garantizado y fluidez en la consulta de datos

| Story ID | US29 |
|---|---|
| Epic ID | E08 - Experiencia de Usuario y Atributos de Calidad del Software |
| Título | Acceso garantizado y fluidez en la consulta de datos |
| Descripción | Como usuario, quiero que la aplicación esté siempre disponible y cargue rápido para tomar decisiones a tiempo sin frustraciones por fallos técnicos. |
| Criterios de Aceptación | **Escenario 1: Confianza en el acceso**<br>Dado que el usuario necesita revisar el estado de su cultivo en cualquier momento del día, Cuando intente ingresar a la plataforma, Entonces el sistema debe estar operativo el 99.9% del tiempo, asegurando que el agricultor nunca se encuentre con una pantalla de error en momentos críticos.<br><br>**Escenario 2: Agilidad en la carga de información**<br>Dado que el tiempo del agricultor es valioso, Cuando el usuario abra la aplicación o cambie entre secciones, Entonces la información debe aparecer en pantalla en menos de 2 segundos, permitiendo una navegación ágil y sin esperas que entorpezcan su jornada.<br><br>**Escenario 3: Estabilidad durante el uso masivo**<br>Dado que muchos agricultores podrían estar usando la app al mismo tiempo (ej: durante una alerta climática regional), Cuando haya una alta concurrencia de usuarios, Entonces la experiencia del usuario debe mantenerse fluida y sin cierres inesperados, garantizando que todos reciban sus datos por igual. |

#### US30 - Protección y privacidad de los datos

| Story ID | US30 |
|---|---|
| Epic ID | E08 - Experiencia de Usuario y Atributos de Calidad del Software |
| Título | Protección y privacidad de los datos |
| Descripción | Como usuario, quiero que mis datos personales y agrícolas estén protegidos bajo estándares de seguridad para sentirme tranquilo de que mi información no será vista ni utilizada por terceros sin mi permiso. |
| Criterios de Aceptación | **Escenario 1: Cifrado de información sensible**<br>Dado que el sistema almacena y transmite datos del usuario, Cuando la información viaje entre el dispositivo y la nube, Entonces el sistema debe emplear protocolos de cifrado para asegurar que nadie pueda interceptar o leer los datos privados del agricultor.<br><br>**Escenario 2: Gestión transparente de permisos**<br>Dado que la aplicación requiere acceso a ciertos datos o funciones del dispositivo (como la ubicación), Cuando el usuario utilice estas funciones por primera vez, Entonces el sistema debe solicitar permiso explícito y explicar claramente para qué se usará esa información, dándole al usuario el control total sobre su privacidad.<br><br>**Escenario 3: Recuperación de cuenta segura**<br>Dado que el usuario ha olvidado su contraseña, Cuando solicite restablecerla, Entonces el sistema debe enviar un enlace de un solo uso y con tiempo limitado al correo verificado, asegurando que solo el dueño legítimo de la cuenta pueda recuperar el acceso.<br><br>**Escenario 4: Cumplimiento con la Protección de Datos**<br>Dado que el usuario se registra en la plataforma, Cuando acceda a los términos y condiciones, Entonces el sistema debe presentar una política de privacidad clara que cumpla con la Ley de Protección de Datos Personales de Perú, garantizando que el usuario puede solicitar la eliminación de sus datos en cualquier momento (Derechos ARCO). |

#### US31 - Compartir acceso de lectura y monitoreo a otros usuarios

| Story ID | US31 |
|---|---|
| Epic ID | E03 - Monitoreo Sensorial y Sincronización de Dispositivos |
| Título | Compartir acceso de lectura y monitoreo a otros usuarios |
| Descripción | Como usuario, quiero invitar a otros usuarios a visualizar la telemetría de mi dispositivo para permitir un monitoreo colaborativo y recibir asesoría técnica basada en datos reales sin compartir mis credenciales personales. |
| Criterios de Aceptación | **Escenario 1: Invitación exitosa de un colaborador**<br>Dado que el usuario es el dueño registrado de un microcontrolador, Cuando ingrese el correo electrónico de otro usuario registrado y seleccione el rol de observador, Entonces el sistema debe vincular el dispositivo a la cuenta del invitado y enviarle una notificación de acceso compartido.<br><br>**Escenario 2: Restricción de permisos administrativos**<br>Dado que un usuario ha sido invitado como observador a un dispositivo, Cuando intente modificar los umbrales de riego o eliminar el dispositivo, Entonces el sistema debe denegar la acción y mostrar un mensaje indicando que solo el dueño tiene permisos de escritura.<br><br>**Escenario 3: Revocación de acceso**<br>Dado que un dispositivo tiene varios usuarios asociados, Cuando el dueño decida eliminar a un colaborador de la lista de acceso, Entonces el dispositivo debe desaparecer instantáneamente del dashboard del colaborador revocado.<br><br>**Escenario 4: Visualización multi-usuario en tiempo real**<br>Dado que dos o más usuarios tienen acceso al mismo microcontrolador, Cuando el dispositivo envíe una nueva lectura de humedad, Entonces la interfaz debe actualizar los gráficos de todos los usuarios autorizados de forma simultánea. |

#### TS01 - Implementación de Endpoints de Monitoreo de Salud (Health Checks)

| Story ID | TS01 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Implementación de Endpoints de Monitoreo de Salud (Health Checks) |
| Descripción | Como Developer, quiero implementar un sistema de Health Checks en la API REST para asegurar que la infraestructura de Grotix detecte y reporte caídas de servicios automáticamente, garantizando el cumplimiento del 99.9% de uptime. |
| Criterios de Aceptación | **Escenario 1: Verificación de estado del servidor**<br>Dado que el servicio de la API está en ejecución, Cuando el sistema de monitoreo realice una petición GET al endpoint /health/live, Entonces la API debe responder con un status 200 OK y un JSON indicando que el proceso del servidor está activo.<br><br>**Escenario 2: Verificación de dependencias críticas**<br>Dado que la API depende de una base de datos para funcionar, Cuando se consulte el endpoint /health/ready, Entonces el sistema debe verificar la conexión activa con la BD y devolver 503 Service Unavailable si la conexión está caída, evitando procesar peticiones que fallarán.<br><br>**Escenario 3: Registro de disponibilidad del microcontrolador**<br>Dado que los dispositivos IoT pueden perder conexión, Cuando el hardware envíe una señal periódica que indique que se encuentra activo, Entonces el backend debe actualizar el estado de disponibilidad del dispositivo en la base de datos para que el sistema sepa que sigue en línea.<br><br>**Escenario 4: Alerta técnica ante fallos persistentes**<br>Dado que un componente crítico reporta un estado de error, Cuando el fallo persista por más de 3 chequeos consecutivos, Entonces el sistema debe disparar una notificación automática hacia el equipo de desarrollo para una intervención inmediata. |

#### TS02 - Estandarización de Contratos de Interoperabilidad IoT

| Story ID | TS02 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Estandarización de Contratos de Interoperabilidad IoT |
| Descripción | Como Developer, quiero definir un contrato de datos RESTful estandarizado para garantizar que el hardware, el backend y el servicio de IA intercambien información de forma consistente y sin errores de formato. |
| Criterios de Aceptación | **Escenario 1: Procesamiento de telemetría con esquema válido**<br>Dado que un dispositivo de campo realiza una petición POST al endpoint /api/v1/telemetry, Cuando el cuerpo del mensaje cumpla estrictamente con el esquema JSON definido, Entonces la API debe responder con un status 201 Created y confirmar la persistencia del dato.<br><br>**Escenario 2: Rechazo de peticiones por esquema inválido**<br>Dado que un componente envía una trama de datos con campos faltantes o nombres de atributos incorrectos, Cuando el servicio de validación de la API procese el request, Entonces debe retornar un status 400 Bad Request indicando exactamente qué campo no cumple con el contrato.<br><br>**Escenario 3: Ciclo de confirmación de comandos**<br>Dado que el backend envía una orden de activación a un actuador (ej. válvula), Cuando el dispositivo confirme la ejecución mediante una respuesta de confirmación técnica, Entonces la API debe actualizar el estado del recurso mediante un PATCH exitoso para cerrar el ciclo de comunicación. |

#### TS03 - Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias

| Story ID | TS03 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias |
| Descripción | Como Developer, quiero implementar el patrón de Inyección de Dependencias y el patrón Repository en .NET para garantizar que la lógica de Grotix sea modificable y no dependa de implementaciones específicas de infraestructura. |
| Criterios de Aceptación | **Escenario 1: Abstracción de la persistencia de datos**<br>Dado que la lógica de negocio requiere guardar datos de telemetría, Cuando el servicio solicite la persistencia, Entonces debe interactuar únicamente con una interfaz (ITelemetryRepository), permitiendo cambiar el motor de base de datos en el archivo Program.cs sin tocar la lógica de cálculo.<br><br>**Escenario 2: Validación de Lógica Independiente**<br>Dado que se recibe un request para procesar una regla de riego, Cuando se ejecute la validación, Entonces el controlador de la API solo debe actuar como mediador, delegando la lógica a un "Domain Service" puro, facilitando futuras modificaciones en las reglas de negocio.<br><br>**Escenario 3: Uso de DTOs para contratos de API estables**<br>Dado que la estructura de las tablas de la base de datos puede cambiar, Cuando la API devuelva una respuesta al frontend, Entonces debe usar Objetos de Transferencia de Datos (DTOs) en lugar de las entidades de base de datos, para que los cambios internos no rompan la integración con el cliente. |

#### TS04 - Optimización de Latencia y Eficiencia en el Procesamiento

| Story ID | TS04 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Optimización de Latencia y Eficiencia en el Procesamiento |
| Descripción | Como Developer, quiero implementar procesamiento asíncrono en .NET y optimización de recursos en el frontend para minimizar el tiempo de respuesta de la API y el tiempo de renderizado en el cliente. |
| Criterios de Aceptación | **Escenario 1: Procesamiento asíncrono de peticiones de telemetría**<br>Dado que la API de telemetría recibe múltiples peticiones de sensores, Cuando el controlador de procese el request, Entonces debe utilizar programación asíncrona para evitar el bloqueo de hilos del servidor, permitiendo una mayor concurrencia.<br><br>**Escenario 2: Minimización de carga en el Frontend**<br>Dado que la aplicación en Vue contiene múltiples vistas y componentes, Cuando se genere el bundle de producción, Entonces el sistema debe implementar code-splitting y lazy loading, asegurando que el navegador solo descargue los recursos estrictamente necesarios para la vista actual.<br><br>**Escenario 3: Reducción del tamaño del Payload JSON**<br>Dado que se solicitan grandes volúmenes de datos históricos de sensores, Cuando la API envíe la respuesta al frontend, Entonces debe omitir valores nulos y utilizar DTOs optimizados para que el peso del archivo JSON se reduzca, acelerando la transferencia de datos sobre la red.<br><br>**Escenario 4: Gestión eficiente del estado en el cliente**<br>Dado que los datos de los sensores se actualizan frecuentemente, Cuando el frontend reciba la información, Entonces el sistema debe actualizar reactivamente solo los componentes afectados en el frontend, evitando re-renderizados innecesarios de toda la interfaz. |

#### TS05 - Implementación de Protocolos de Autenticación y Protección de Recursos

| Story ID | TS05 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Implementación de Protocolos de Autenticación y Protección de Recursos |
| Descripción | Como Developer, quiero implementar autenticación basada en JWT en el backend y guardias de navegación en el frontend para asegurar que solo los usuarios y dispositivos autorizados accedan a la API y a los datos de Grotix. |
| Criterios de Aceptación | **Escenario 1: Autenticación robusta mediante JWT**<br>Dado que un usuario o dispositivo intenta acceder a un endpoint protegido de la API, Cuando envíe sus credenciales válidas, Entonces el backend debe generar un JSON Web Token (JWT) firmado digitalmente que expire tras un tiempo determinado, asegurando que las sesiones no queden abiertas indefinidamente.<br><br>**Escenario 2: Restricción de acceso mediante Política de CORS**<br>Dado que la API de Grotix está expuesta en la nube, Cuando reciba una petición desde un dominio no autorizado, Entonces el backend debe rechazar la solicitud mediante una política de CORS (Cross-Origin Resource Sharing) configurada estrictamente para proteger el servidor.<br><br>**Escenario 3: Protección de rutas en el cliente**<br>Dado que un usuario intenta acceder manualmente a una ruta protegida (ej: /dashboard), Cuando el sistema detecte que no existe un token válido en el estado de la aplicación, Entonces el frontend debe redirigir automáticamente al usuario a la pantalla de Login, impidiendo la visualización de la interfaz privada.<br><br>**Escenario 4: Almacenamiento seguro de credenciales**<br>Dado que se deben persistir contraseñas de usuarios en la base de datos, Cuando se registre un nuevo usuario, Entonces el backend debe aplicar un algoritmo de hashing robusto, garantizando que las contraseñas nunca se guarden en texto plano. |

#### TS06 - Implementación de Infraestructura de Pruebas Automatizadas

| Story ID | TS06 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Implementación de Infraestructura de Pruebas Automatizadas |
| Descripción | Como Developer, quiero configurar un entorno de pruebas unitarias e integrales para garantizar la detección temprana de errores y asegurar la estabilidad del sistema ante nuevos cambios. |
| Criterios de Aceptación | **Escenario 1: Pruebas unitarias para lógica de negocio**<br>Dado que se ha desarrollado una nueva regla de cálculo para el riego automático, Cuando el desarrollador ejecute el motor de pruebas, Entonces el sistema debe validar los algoritmos de forma aislada, asegurando que los resultados coincidan con los valores esperados sin necesidad de conectar la base de datos real.<br><br>**Escenario 2: Simulación de dependencias externas**<br>Dado que un servicio de la API depende de Inteligencia Artificial o de la base de datos de Azure, Cuando se ejecute una prueba técnica, Entonces el sistema debe permitir el uso de objetos simulados para sustituir estas dependencias, garantizando que los tests sean rápidos y no dependan de la conexión a internet.<br><br>**Escenario 3: Pruebas de componentes en el frontend**<br>Dado que se ha creado un componente crítico (ej: el indicador de humedad en tiempo real), Cuando se ejecute la suite de pruebas, Entonces el sistema debe verificar que el componente renderice los datos correctamente y responda adecuadamente a los cambios de estado.<br><br>**Escenario 4: Ejecución automatizada en el flujo de trabajo**<br>Dado que el desarrollador sube un nuevo cambio al repositorio, Cuando se active el pipeline de integración continua, Entonces todos los tests deben ejecutarse automáticamente, bloqueando el despliegue si alguna prueba falla para evitar errores en producción. |

#### TS07 - Estandarización de la Experiencia del Desarrollador y Documentación

| Story ID | TS07 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica. |
| Título | Estandarización de la Experiencia del Desarrollador y Documentación |
| Descripción | Como Developer, quiero contar con una API documentada y una librería de componentes reutilizables para agilizar el desarrollo de nuevas funcionalidades y facilitar el mantenimiento del código a largo plazo. |
| Criterios de Aceptación | **Escenario 1: Autodocumentación de la API**<br>Dado que el backend en expone múltiples servicios REST, Cuando el desarrollador acceda a la ruta /swagger, Entonces el sistema debe mostrar una interfaz interactiva con todos los endpoints, sus modelos de datos y permitir realizar pruebas de petición/respuesta en tiempo real.<br><br>**Escenario 2: Librería de componentes UI reutilizables**<br>Dado que el frontend requiere interfaces consistentes, Cuando el desarrollador necesite crear una nueva vista, Entonces debe poder utilizar un catálogo de componentes base (botones, selectores, modales) ya definidos, evitando la duplicación de código CSS y lógica de interfaz.<br><br>**Escenario 3: Estandarización de Respuestas de la API**<br>Dado que la API devuelve resultados al cliente, Cuando se envíe cualquier respuesta (éxito o error), Entonces el JSON debe seguir una estructura uniforme (ej: data, message, errors, statusCode), permitiendo que el desarrollador del frontend maneje las respuestas de forma predecible.<br><br>**Escenario 4: Legibilidad y Guía de Estilos de Código**<br>Dado que varios desarrolladores colaboran en el repositorio, Cuando se realice un análisis estático del código, Entonces el código debe cumplir con las convenciones de nomenclatura, garantizando que cualquier miembro del equipo pueda entender el código de otros rápidamente. |

#### TS08 - Dashboard web con indicadores clave del sistema

| Story ID | TS08 |
|---|---|
| Epic ID | E10 - Gestión de Clientes y Contratos |
| Título | Dashboard web con indicadores clave del sistema |
| Descripción | Como Administrador, quiero visualizar un panel de control centralizado y optimizado para pantallas táctiles con los KPIs más relevantes de Grotix para obtener en tiempo real una visión global del estado de la plataforma desde cualquier lugar (clientes activos, contratos, dispositivos y alertas) |
| Criterios de Aceptación | **Escenario 1: Visualización del dashboard principal**<br>Dado que el administrador accede a la pantalla principal de la app, Cuando los datos terminan de cargar, Entonces el sistema muestra tarjetas de resumen apilables verticalmente (scroll) con: número de clientes activos, contratos vigentes, próximos a vencer, y dispositivos en línea/offline.<br><br>**Escenario 2: Resaltado visual de alertas críticas**<br>Dado que existen contratos vencidos o alertas críticas, Cuando el administrador visualiza el dashboard, Entonces estas tarjetas se resaltan en color rojo y permiten hacer "tap" para navegar directamente al detalle.<br><br>**Escenario 3: Tolerancia a fallos de red (Offline mode)**<br>Dado que el dispositivo pierde conexión a internet, Cuando se intenta cargar el dashboard, Entonces la app muestra los últimos datos cacheados localmente con un indicador visual de "Sin conexión".<br><br>**Escenario 4: Actualización manual de datos (Pull to refresh)**<br>Dado que el administrador desea ver los datos más recientes en el dashboard, Cuando realiza el gesto de arrastrar hacia abajo (pull-to-refresh), Entonces la app sincroniza los datos con el servidor y actualiza los indicadores en pantalla. |

#### TS09 - Gestión web de clientes agricultores

| Story ID | TS09 |
|---|---|
| Epic ID | E10 - Gestión de Clientes y Contratos |
| Título | Gestión web de clientes agricultores |
| Descripción | Como Administrador, quiero consultar y editar perfiles de clientes agricultores desde mi dispositivo para mantener actualizado el directorio de usuarios finales y su estado de servicio en cualquier momento |
| Criterios de Aceptación | **Escenario 1: Búsqueda y filtrado en tiempo real**<br>Dado que el administrador busca un cliente específico, Cuando ingresa a la sección de búsqueda Y usa la barra de búsqueda superior en la app, Entonces el sistema filtra los resultados en tiempo real mostrando una lista con el nombre, ubicación y un indicador semafórico de su estado contractual (activo/vencido).<br><br>**Escenario 2: Registro de nuevo agricultor mediante Stepper**<br>Dado que el administrador necesita registrar un nuevo agricultor, Cuando completa el formulario móvil (dividido en pasos/stepper para mejor UX) y guarda, Entonces el sistema crea el perfil en estado 'Pendiente de contrato'.<br><br>**Escenario 3: Desactivación segura de cliente**<br>Dado que un agricultor deja de operar con Grotix, Cuando el administrador cambia su estado a 'Inactivo' mediante un toggle switch, Entonces el sistema requiere una confirmación doble (modal) para desvincular sus dispositivos y suspender el acceso.<br><br>**Escenario 4: Edición rápida de datos de contacto**<br>Dado que un cliente cambia su número de teléfono o dirección, Cuando el administrador edita el perfil desde la vista de detalle y guarda los cambios, Entonces el sistema actualiza la información inmediatamente y la refleja en la base de datos central. |

#### TS10 - Registro de contratos externos en campo

| Story ID | TS10 |
|---|---|
| Epic ID | E10 - Gestión de Clientes y Contratos |
| Título | Registro de contratos externos en campo |
| Descripción | Como Administrador, quiero registrar los contratos firmados con clientes, incluyendo fechas y planes para mantener la trazabilidad contractual de forma inmediata, incluso si me encuentro visitando al cliente en campo |
| Criterios de Aceptación | **Escenario 1: Registro de nuevo contrato**<br>Dado que el administrador firma un contrato físico, Cuando registra los datos (fechas, plan, cliente) en la app, Entonces el sistema crea el contrato con estado 'Activo' y habilita los servicios IoT correspondientes.<br><br>**Escenario 2: Historial de contratos del cliente**<br>Dado que el administrador consulta el historial de un cliente en la app, Cuando navega a la pestaña de 'Contratos', Entonces la app lista todos los contratos históricos (Activos/Vencidos/Cancelados) en un formato de línea de tiempo o lista simplificada.<br><br>**Escenario 3: Validación de superposición de fechas**<br>Dado que el administrador intenta registrar un nuevo contrato para un cliente, Cuando las fechas de inicio y fin ingresadas se superponen con un contrato ya vigente, Entonces la app muestra un mensaje de error advirtiendo el conflicto y deshabilita el botón de guardar. |

#### TS11 - Gestión de suspensión de servicios (Push & Manual)

| Story ID | TS11 |
|---|---|
| Epic ID | E11- Supervisión y Operación de Infraestructura IoT |
| Título | Gestión de suspensión de servicios (Push & Manual) |
| Descripción | Como Administrador, quiero visualizar los servicios suspendidos automáticamente por el sistema y poder activar suspensiones manuales para proteger los recursos de la plataforma e impedir el uso no autorizado de la infraestructura IoT. |
| Criterios de Aceptación | **Escenario 1: Notificación Push de suspensión automática**<br>Dado que la fecha de fin de un contrato llega a su término, Cuando el sistema central ejecuta la validación y suspende el servicio, Entonces el administrador recibe una notificación Push en su dispositivo móvil alertando del cambio de estado.<br><br>**Escenario 2: Reactivación rápida mediante gestos (Swipe)**<br>Dado que el administrador revisa la lista de clientes suspendidos, Cuando aplica el filtro rápido de 'Suspendidos' en la app, Entonces se muestran los clientes afectados con opción de "Deslizar (Swipe) para reactivar".<br><br>**Escenario 3: Suspensión manual inmediata**<br>Dado que el administrador activa manualmente la suspensión de un cliente, Cuando cambia el estado desde el perfil móvil, Entonces la app envía el comando de suspensión inmediata a los dispositivos y registra la acción.<br><br>**Escenario 4: Visualización de detalles de suspensión**<br>Dado que el administrador consulta a un cliente suspendido, Cuando presiona el icono de información en el estado de suspensión, Entonces la app despliega un modal con la fecha exacta de la suspensión, el usuario o proceso que la ejecutó y el motivo (vencimiento o manual). |

#### TS12 - Gestión de mantenimiento de dispositivos IoT

| Story ID | TS12 |
|---|---|
| Epic ID | E11- Supervisión y Operación de Infraestructura IoT |
| Título | Gestión de mantenimiento de dispositivos IoT |
| Descripción | Como Administrador, quiero gestionar el mantenimiento preventivo y correctivo de los dispositivos IoT desde mi celular para asegurar la continuidad operativa de los sensores en campo y prevenir fallas críticas en el monitoreo de los cultivos. |
| Criterios de Aceptación | **Escenario 1: Reporte de inicio de mantenimiento**<br>Dado que un dispositivo requiere una revisión técnica o limpieza, Cuando el administrador selecciona el equipo y cambia su estado a "En Mantenimiento", Entonces el sistema suspende temporalmente las alertas de telemetría para ese ID y registra el inicio de la intervención con la marca de tiempo actual.<br><br>**Escenario 2: Registro de acciones de mantenimiento**<br>Dado que el administrador está realizando una intervención técnica en campo, Cuando completa el formulario de "Bitácora" con la descripción de la acción realizada (ej: limpieza de sensor o cambio de batería), Entonces el sistema guarda la nota técnica vinculada al historial del dispositivo para mantener la trazabilidad de su vida útil.<br><br>**Escenario 3: Finalización y reactivación del equipo**<br>Dado que el mantenimiento del dispositivo ha concluido con éxito, Cuando el administrador presiona el botón "Finalizar Mantenimiento”, Entonces la app reactiva la recepción de datos en tiempo real y actualiza el estado visual del sensor a "Activo".<br><br>**Escenario 4: Consulta de historial de intervenciones**<br>Dado que el administrador necesita conocer los antecedentes técnicos de un sensor, Cuando accede a la sección "Historial de Mantenimiento" dentro del detalle del dispositivo, Entonces la app muestra una lista cronológica de todas las intervenciones pasadas, incluyendo fechas y el resumen de las acciones realizadas |

#### TS13 - Consulta rápida del catálogo de cultivos

| Story ID | TS13 |
|---|---|
| Epic ID | E11- Supervisión y Operación de Infraestructura IoT |
| Título | Consulta rápida del catálogo de cultivos |
| Descripción | Como Administrador, quiero consultar y ajustar los parámetros del catálogo de cultivos para tener acceso a la información técnica de umbrales (humedad, luz, temperatura) mientras superviso zonas de cultivo |
| Criterios de Aceptación | **Escenario 1: Visualización de rangos óptimos**<br>Dado que el administrador necesita ver los tipos de cultivos, Cuando navega al módulo de cultivos, Entonces la app muestra una lista con tarjetas que resumen los rangos óptimos de cada planta.<br><br>**Escenario 2: Actualización táctil de umbrales**<br>Dado que el administrador actualiza un parámetro, Cuando edita el rango de humedad mediante controles deslizantes (Sliders) táctiles y guarda, Entonces el sistema actualiza los valores y notifica la propagación a los dispositivos asociados.<br><br>**Escenario 3: Búsqueda dinámica de cultivo**<br>Dado que el catálogo contiene múltiples variedades de plantas, Cuando el administrador utiliza la barra de búsqueda e ingresa el nombre de un cultivo, Entonces la app filtra la lista instantáneamente para mostrar solo las coincidencias relevantes.<br><br>**Escenario 4: Manejo de errores al actualizar parámetros**<br>Dado que existe una falla de conexión temporal, Cuando el administrador edita un umbral y presiona guardar, Entonces la app muestra un mensaje emergente informando que los cambios no pudieron aplicarse y revierte los controles a su valor original. |

#### TS14 - Autenticación y Control de Acceso para el Portal de Administración

| Story ID | TS14 |
|---|---|
| Epic ID | E11- Supervisión y Operación de Infraestructura IoT |
| Título | Autenticación y Control de Acceso para el Portal de Administración |
| Descripción | Como Administrador de Grotix, quiero contar con un sistema de inicio y cierre de sesión exclusivo para acceder al portal web administrativo, asegurando la protección de la gestión de clientes y dispositivos. |
| Criterios de Aceptación | **Escenario 1: Login de Administrador**<br>Dado que el administrador ingresa sus credenciales en el portal web, Cuando los datos son validados contra el rol de 'Admin' en el backend, Entonces el sistema debe otorgar un token JWT con privilegios elevados y redirigir al Dashboard Administrativo<br><br>**Escenario 2: Cierre de Sesión**<br>Dado que el administrador finaliza su jornada, Cuando selecciona "Salir", Entonces el sistema debe invalidar el token de sesión y denegar el acceso a las rutas protegidas del portal. |

#### TS15 - Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter)

| Story ID | TS15 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) |
| Descripción | Como Developer de Grotix, quiero configurar la estructura base del proyecto móvil en Flutter aplicando Clean Architecture, para asegurar la escalabilidad, la correcta separación de capas y la mantenibilidad del frontend móvil. |
| Criterios de Aceptación | **Escenario 1: Inicialización del proyecto y dependencias Core**<br>Dado que el desarrollador inicializa el repositorio móvil de Flutter, Cuando se configuren los paquetes base de inyección de dependencias y el cliente HTTP para las solicitudes, Entonces el sistema debe compilar correctamente el entorno inicial sin errores de dependencias cruzadas.<br><br>**Escenario 2: Estructura de carpetas por capas limpias**<br>Dado que el equipo técnico inspecciona la estructura del proyecto en Flutter, Cuando se verifique la distribución del código fuente, Entonces las carpetas deben estar divididas estrictamente en las capas de Data, Domain y Presentation para aislar la lógica del cliente. |

#### TS16 - Implementación del Microservicio de Telemetría e Ingesta IoT (.NET)

| Story ID | TS16 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) |
| Descripción | Como Developer de Grotix, quiero construir el microservicio telemetry.api en .NET (C#) integrado con controladores de mensajería, para procesar, validar y estructurar de forma asíncrona las tramas de datos JSON de telemetría. |
| Criterios de Aceptación | **Escenario 1: Procesamiento asíncrono de tramas JSON**<br>Dado que el microservicio de telemetría en .NET se encuentra activo, Cuando el sistema reciba un paquete JSON con lecturas de sensores, Entonces el backend debe capturar las tramas asíncronamente sin bloquear los hilos principales del servidor.<br><br>**Escenario 2: Validaciones de contratos técnicos establecidos**<br>Dado que la API de telemetría recibe un request, Cuando se ejecute la validación de tipos de datos, Entonces el sistema debe confirmar la correcta estructura o rechazar el objeto si los parámetros obligatorios son nulos. |

#### TS17 - Implementación del Microservicio de Control y Orquestación de Riego (.NET)

| Story ID | TS17 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Implementación del Microservicio de Control y Orquestación de Riego (.NET) |
| Descripción | Como Developer de Grotix, quiero desarrollar el microservicio irrigation.api en .NET (C#) que evalúe las reglas hídricas autónomas y despache estados de riego, asegurando el desacoplamiento de la lógica de control. |
| Criterios de Aceptación | **Escenario 1: Evaluación de reglas automáticas según umbrales agronómicos**<br>Dado que el microservicio de riego en .NET recibe nuevas lecturas del suelo, Cuando los valores porcentuales de humedad caigan por debajo del umbral mínimo configurado para la especie, Entonces el backend debe calcular las necesidades hídricas y registrar un nuevo evento automático de riego.<br><br>**Escenario 2: Despacho de comandos lógicos de irrigación**<br>Dado que el sistema procesa una activación de riego (manual o automática) en el backend, Cuando el controlador actualice el estado del actuador lógico en la base de datos, Entonces la respuesta debe ser inmediata y consistente para los clientes conectados. |

#### TS18 - Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python)

| Story ID | TS18 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python) |
| Descripción | Como Developer de Grotix, quiero construir el microservicio cropanalysis.api en Python (FastAPI) para gestionar la recepción programada de capturas fotográficas y conectarlo con los servicios de clasificación fenológica, asegurando la inferencia de Inteligencia Artificial. |
| Criterios de Aceptación | **Escenario 1: Recepción y procesamiento de imágenes en FastAPI**<br>Dado que el frontend envía una fotografía del cultivo, Cuando el endpoint en Python reciba el archivo a través de una petición HTTP optimizada, Entonces el sistema debe almacenar el recurso de forma segura y asociarlo al ID del cultivo correspondiente.<br><br>**Escenario 2: Orquestación del modelo de Inteligencia Artificial**<br>Dado que la imagen ha sido cargada con éxito en el backend de Python, Cuando se ejecute el script del modelo convolucional entrenado, Entonces el sistema debe retornar el estado de germinación del cultivo junto a su nivel de confianza. |

#### TS19 - Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET)

| Story ID | TS19 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET) |
| Descripción | Como Developer de Grotix, quiero construir el microservicio hardware.api en .NET (C#) para centralizar el registro, inventario, asignación y estado lógico de los dispositivos asociados a los clientes agrícolas. |
| Criterios de Aceptación | **Escenario 1: CRUD e inventariado de dispositivos en el Backend**<br>Dado que un administrador necesita registrar un lote de dispositivos, Cuando envíe los identificadores únicos a los endpoints correspondientes, Entonces el sistema debe persistir los registros asignándoles el estado inicial de "Inactivo".<br><br>**Escenario 2: Actualización de estado operativo del hardware**<br>Dado que el sistema requiere auditar los equipos, Cuando el backend actualice el estado de conexión de un identificador de hardware, Entonces los cambios deben reflejarse de forma inmediata en las consultas globales del sistema. |

#### TS20 - Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos

| Story ID | TS20 |
|---|---|
| Epic ID | E09 - Arquitectura de Software y Atributos de Calidad Técnica |
| Título | Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos |
| Descripción | Como Developer de Grotix, quiero diseñar un motor interno de simulación de datos en el backend, para mockear la inserción continua de lecturas de sensores y flujos de red sin depender de un hardware físico conectado. |
| Criterios de Aceptación | **Escenario 1: Generación automatizada de lecturas mockeadas**<br>Dado que el simulador de telemetría está activo en el entorno de desarrollo, Cuando se dispare el cronómetro interno, Entonces el sistema debe autogenerar tramas lógicas de humedad, temperatura y luz dentro de rangos realistas para alimentar las interfaces de usuario.<br><br>**Escenario 2: Inyección de estados de conexión simulados**<br>Dado que el sistema requiere simular escenarios de conectividad, Cuando el administrador alterne el switch de simulación, Entonces el mock debe inyectar caídas de red lógicas para validar el comportamiento del software en condiciones de error. |

## 3.2. Impact Map

### Business Goal 1: Maximizar la rentabilidad del productor mediante el uso eficiente del agua.

**Objetivo SMART:** Reducir el consumo de agua en un 25% para los usuarios de Grotix mediante el sistema de riego automatizado en un periodo de 12 meses tras la implementación.

[foto]

### Business Goal 2: Establecer una presencia digital sólida para convertir visitantes en usuarios registrados.

**Objetivo SMART:** Lograr una tasa de conversión del 10% de visitantes a usuarios registrados en la plataforma web durante los primeros 6 meses de operación.

[foto]

### Business Goal 3: Asegurar la sostenibilidad financiera del proyecto mediante la recurrencia del servicio.

**Objetivo SMART:** Alcanzar una tasa de retención del 80% en suscripciones inteligentes al finalizar cada campaña agrícola en el primer año.

[foto]

### Business Goal 4: Elevar el estándar de la producción para facilitar el acceso a mercados internacionales.

**Objetivo SMART:** Lograr que el 90% de las parcelas monitoreadas alcancen calibres uniformes de exportación, reduciendo las mermas en un 15% para finales de 2026.

[foto]

### Riesgo para Grotix:
Tras elaborar los Impact Maps, el equipo ha identificado que el mayor riesgo que puede afectar el impacto del proyecto es la inestabilidad de la infraestructura de conectividad en zonas rurales. Este riesgo invalidaría el impacto esperado al interrumpir el flujo de datos. Por ello, se han definido entregables específicos de resiliencia y persistencia de datos vinculados a las historias técnicas de arquitectura para asegurar que el comportamiento del usuario no se vea frustrado por factores externos, garantizando así el cumplimiento de nuestros Business Goals.

## 3.3. Product Backlog

| Prioridad | User Story Id | Título | Story Points |
|---:|---|---|---:|
| 1 | TS02 | Estandarización de Contratos de Interoperabilidad IoT | 3 |
| 2 | US11 | Monitoreo fiel de las condiciones del entorno | 5 |
| 3 | US12 | Actualización periódica y automática de telemetría | 5 |
| 4 | US13 | Garantía de exactitud en la medición de datos | 3 |
| 5 | US14 | Dashboard de Monitoreo Integral y Resumen de Estado | 3 |
| 6 | US19 | Activación manual del sistema de irrigación | 3 |
| 7 | US20 | Automatización del riego mediante modelos de aprendizaje automático | 8 |
| 8 | US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | 13 |
| 9 | US10 | Vinculación del Microcontrolador con la Aplicación | 5 |
| 10 | US22 | Gestión de registro fotográfico de cultivos. | 5 |
| 11 | TS01 | Implementación de Endpoints de Monitoreo de Salud (Health Checks) | 3 |
| 12 | US21 | Generación y descarga de reportes históricos | 1 |
| 13 | US30 | Protección y privacidad de los datos | 5 |
| 14 | TS07 | Estandarización de la Experiencia del Desarrollador y Documentación | 3 |
| 15 | TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | 5 |
| 16 | US17 | Persistencia de datos ante pérdida de conectividad | 3 |
| 17 | US18 | Notificaciones automáticas por condiciones críticas y cambios de estado | 1 |
| 18 | US15 | Organización de dispositivos por zonas y especies | 3 |
| 19 | US16 | Configuración de parámetros y umbrales de control | 1 |
| 20 | TS08 | Dashboard web con indicadores clave del sistema | 5 |
| 21 | TS12 | Gestión de mantenimiento de dispositivos IoT | 5 |
| 22 | TS13 | Consulta rápida del catálogo de cultivos | 3 |
| 23 | TS09 | Gestión móvil de clientes agricultores | 5 |
| 24 | TS10 | Registro de contratos externos en campo | 5 |
| 25 | TS11 | Gestión de suspensión de servicios (Push & Manual) | 3 |
| 26 | US27 | Visualización de estado de servicios y periodos de campaña | 3 |
| 27 | US26 | Configuración y gestión de alertas de usuario | 1 |
| 28 | US25 | Modificación de datos personales y de contacto | 1 |
| 29 | US24 | Registro, inicio y cierre de sesión de usuario | 1 |
| 30 | US29 | Acceso garantizado y fluidez en la consulta de datos | 3 |
| 31 | US28 | Diseño consistente y adaptabilidad multiplataforma | 3 |
| 32 | TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | 5 |
| 33 | TS04 | Optimización de Latencia y Eficiencia en el Procesamiento | 3 |
| 34 | TS06 | Implementación de Infraestructura de Pruebas Automatizadas | 5 |
| 35 | US01 | Visualización de propuesta de valor y servicios | 1 |
| 36 | US02 | Enlaces de acceso a la aplicación móvil | 1 |
| 37 | US03 | Implementación de CTA | 1 |
| 38 | US04 | Visualización de misión, visión y equipo | 1 |
| 39 | US05 | Implementación de formulario y canales de contacto | 1 |
| 40 | US06 | Enlaces a redes sociales | 1 |
| 41 | US07 | Implementación de sistemas de navegación simplificada | 1 |
| 42 | US08 | Implementación de Identidad y Consistencia Visual | 1 |
| 43 | US09 | Optimización de tiempos de respuesta y carga inicial | 3 |
| 44 | TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) | 3 |
| 45 | TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | 5 |
| 46 | TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | 5 |
| 47 | TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python) | 8 |
| 48 | TS19 | Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET) | 5 |
| 49 | TS20 | Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos | 3 |

### Product Backlog Funcional:

| Prioridad | ID | Título | Story Points |
|---:|---|---|---:|
| 2 | US11 | Monitoreo fiel de las condiciones del entorno | 5 |
| 3 | US12 | Actualización periódica y automática de telemetría | 5 |
| 5 | US14 | Dashboard de Monitoreo Integral y Resumen de Estado | 3 |
| 6 | US19 | Activación manual del sistema de irrigación | 3 |
| 7 | US20 | Automatización del riego mediante modelos de aprendizaje automático | 8 |
| 8 | US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | 13 |
| 9 | US10 | Vinculación del Microcontrolador con la Aplicación | 5 |
| 10 | US22 | Gestión de registro fotográfico de cultivos. | 5 |
| 12 | US21 | Generación y descarga de reportes históricos | 1 |
| 17 | US18 | Notificaciones automáticas por condiciones críticas y cambios de estado | 1 |
| 18 | US15 | Organización de dispositivos por zonas y especies | 3 |
| 19 | US16 | Configuración de parámetros y umbrales de control | 1 |
| 20 | TS08 | Dashboard web con indicadores clave del sistema | 5 |
| 21 | TS12 | Gestión de mantenimiento de dispositivos IoT | 5 |
| 22 | TS13 | Consulta rápida del catálogo de cultivos | 3 |
| 23 | TS09 | Gestión web de clientes agricultores | 5 |
| 24 | TS10 | Registro de contratos externos en campo | 5 |
| 25 | TS11 | Gestión de suspensión de servicios (Push & Manual) | 3 |
| 26 | US27 | Visualización de estado de servicios y periodos de campaña | 3 |
| 27 | US26 | Configuración y gestión de alertas de usuario | 1 |
| 28 | US25 | Modificación de datos personales y de contacto | 1 |
| 29 | US24 | Registro, inicio y cierre de sesión de usuario | 1 |
| 35 | US01 | Visualización de propuesta de valor y servicios | 1 |
| 36 | US02 | Enlaces de acceso a la aplicación móvil | 1 |
| 37 | US03 | Implementación de CTA (Botones de acción) | 1 |
| 38 | US04 | Visualización de misión, visión y equipo | 1 |
| 39 | US05 | Implementación de formulario y canales de contacto | 1 |
| 40 | US06 | Enlaces a redes sociales | 1 |

### Product Backlog No Funcional:

| Prioridad | ID | Título | Story Points |
|---:|---|---|---:|
| 1 | TS02 | Estandarización de Contratos de Interoperabilidad IoT | 3 |
| 4 | US13 | Garantía de exactitud en la medición de datos | 3 |
| 11 | TS01 | Implementación de Endpoints de Monitoreo de Salud | 3 |
| 14 | US30 | Protección y privacidad de los datos | 5 |
| 15 | TS07 | Estandarización de la Exp. del Desarrollador y Documentación | 3 |
| 16 | TS05 | Implementación de Protocolos de Autenticación | 5 |
| 17 | US17 | Persistencia de datos ante pérdida de conectividad | 3 |
| 31 | US29 | Acceso garantizado y fluidez en la consulta de datos | 3 |
| 32 | US28 | Diseño consistente y adaptabilidad multiplataforma | 3 |
| 33 | TS03 | Desacoplamiento de Lógica mediante DI/Repository | 5 |
| 34 | TS04 | Optimización de Latencia y Eficiencia (Async) | 3 |
| 35 | TS06 | Infraestructura de Pruebas Automatizadas | 5 |
| 42 | US07 | Implementación de sistemas de navegación simplificada | 1 |
| 43 | US08 | Implementación de Identidad y Consistencia Visual | 1 |
| 44 | US09 | Optimización de tiempos de respuesta y carga inicial | 3 |
| 45 | TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) | 3 |
| 46 | TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | 5 |
| 47 | TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | 5 |
| 48 | TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (.NET) | 8 |
| 49 | TS19 | Integración de Hardware IoT y Configuración del Microcontrolador (ESP32) | 5 |
| 50 | TS20 | Configuración de Persistencia de Datos para Telemetría Masiva | 3 |

### Product Backlog en Jira: 

<img src="https://imgur.com/1kBAtuw.png">

<img src="https://imgur.com/lOUHtEA.png">

<img src="https://imgur.com/BFsJeUl.png">

# CAPÍTULO IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design 

En esta sección, el equipo detalla la aplicación de los principios de Domain-Driven Design (DDD) a nivel estratégico para definir la estructura fundamental de Grotix. El objetivo de este análisis es alinear estrechamente la solución de software con las necesidades reales del dominio agrícola, garantizando una arquitectura escalable y mantenible.

El proceso comienza con el Design-Level EventStorming, donde profundizamos en el descubrimiento de contextos candidatos y el modelado de flujos de mensajes para entender la interacción entre los distintos componentes del sistema. Posteriormente, se formalizan los Bounded Context Canvases y el Context Mapping para establecer límites claros de responsabilidad y definir las relaciones entre los subdominios. Finalmente, este diseño estratégico se traduce en la Arquitectura de Software, representada a través del modelo C4 (System Landscape, Context, Container) y diagramas de despliegue, asegurando una transición coherente desde la lógica de negocio hacia la implementación técnica del sistema.

### 4.1.1. Design-Level EventStorming

Se realizó una sesión colaborativa con todos los integrantes del equipo. Basándonos en los principios de Domain-Driven Design (DDD), se modeló el software de Grotix, detallando la interacción entre comandos, eventos y demás elementos del dominio. El objetivo de la reunión fue traducir procesos de negocio en diseños técnicos, identificando componentes como políticas, comandos, actores, read models, sistemas externos y pain points. Asimismo, este proceso representó un primer acercamiento a la definición y delimitación de los bounded contexts del negocio.
Leyenda:

[foto]

**Enlace:**
https://miro.com/welcomeonboard/RHE0Z0ZHYlYxSVU3Y0ozTjEya3JETTc1NzIyVmsyYy9UMHBEN0ovRUF2RDdEbjRQZFBpUEZ3a3lubXRFc0d1NzhHdkNvZUZHeElDWDFRc0lsZEVWUy9GYTVRRWtwZVF5enJyVlpZUzdXQmtYVUp1a2FIVXdESDJDVllXSEZYaXh3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=31489203478

* **Step 1: Unstructured Exploration**

[foto]

El Step 1: Unstructured Exploration es una fase de lluvia de ideas masiva diseñada para identificar y capturar, a través de post-its naranjas, todos los Eventos de Dominio relevantes para el ecosistema de Grotix. Al registrar estos sucesos exclusivamente en tiempo pasado, se busca mapear hechos significativos del negocio sin la rigidez de una estructura jerárquica o cronológica inicial. Este ejercicio es fundamental para consolidar un lenguaje común entre los integrantes del equipo, permitiendo visibilizar la complejidad técnica de la solución agrotecnológica y asegurar que ninguna interacción crítica entre el hardware, la inteligencia artificial y el usuario quede fuera del diseño preliminar del sistema.

* **Step 2: Timelines**

[foto]

El Step 2: Timelines consiste en la organización cronológica de los eventos de dominio identificados previamente, disponiéndolos secuencialmente de izquierda a derecha para establecer un flujo narrativo coherente dentro del ecosistema de Grotix. Durante esta fase, el equipo estructura las interacciones temporales de los diversos hilos de ejecución —como el monitoreo de telemetría, la gestión de riegos y el procesamiento de visión artificial—, lo que permite detectar inconsistencias lógicas, eliminar redundancias y revelar vacíos de información donde faltan hechos de negocio esenciales. Esta transición de una exploración desordenada hacia un orden lineal es crítica para validar la viabilidad del proceso y asegurar que el modelo refleje con precisión la realidad operativa del entorno agrícola y los protocolos de automatización del software. 

* **Step 3: Pain Points**

[foto]

El Step 3: Pain Points representa una fase de auditoría crítica donde se identifican riesgos, cuellos de botella y ambigüedades técnicas o de negocio dentro de los procesos de Grotix. Mediante el uso de post-its rosados en forma de rombo, el equipo señala interrogantes vitales y puntos de fricción, como la precisión del hardware bajo condiciones climáticas adversas o la fiabilidad de las predicciones de la IA, con el fin de visibilizar las áreas de mayor vulnerabilidad del sistema. Esta etapa es fundamental para anticipar fallos operativos y priorizar la investigación en los componentes que presentan mayor incertidumbre, garantizando así un diseño de software más resiliente y alineado a los desafíos reales del entorno agrícola peruano. 

* **Step 4: Pivotal Points**

[foto]

El Step 4: Pivotal Points consiste en la identificación de aquellos hitos dentro del flujo de Grotix que representan cambios de estado determinantes o transiciones críticas entre distintas fases del negocio. Estos eventos no son simples pasos operativos, sino puntos de inflexión que disparan consecuencias significativas a lo largo del sistema —como la activación de un ciclo de riego o la validación de un análisis de germinación—, permitiendo establecer las fronteras lógicas entre subdominios. Al resaltar estos momentos clave mediante marcas visuales, el equipo logra segmentar la complejidad del proyecto y definir con mayor precisión los límites de responsabilidad de cada componente tecnológico, sentando las bases estratégicas para la futura delimitación de los contextos acotados.

* **Step 5: Commands**

[foto]

El Step 5: Commands introduce las acciones deliberadas que disparan los eventos de dominio dentro del ecosistema de Grotix, representadas mediante post-its azules y amarillos respectivamente. Los comandos simbolizan la intención de ejecutar una operación específica, como la activación de un actuador de riego o la solicitud de un análisis de imagen, y se expresan siempre mediante verbos en infinitivo para denotar una orden al sistema. Por su parte, los actores identifican la entidad responsable de ejecutar dicha acción, ya sea un usuario humano (Productor Agrícola) o un componente automatizado (Sistema/IA), permitiendo mapear la interacción entre los requerimientos funcionales y la lógica de ejecución necesaria para movilizar el flujo de negocio. 

* **Step 6: Policies**

[foto]

El Step 6: Policies constituye la formalización de las reglas de negocio reactivas que orquestan el comportamiento autónomo del sistema Grotix, actuando como el nexo lógico entre los eventos de dominio y los comandos resultantes. Representadas mediante post-its de color morado, estas políticas encapsulan la lógica de decisión automatizada bajo la estructura condicional "Siempre que ocurra un evento específico, entonces debe ejecutarse un comando determinado". Este paso es fundamental para implementar la inteligencia del sistema, permitiendo que la solución responda dinámicamente a cambios en el entorno, como la optimización del riego ante pronósticos de lluvia o el escalamiento de alertas ante riesgos en el cultivo, asegurando así la integridad operativa y la eficiencia en el uso de los recursos hídricos. 

* **Step 7: Read Models**

[foto]

El Step 7: Read Models se centra en identificar la información y las representaciones de datos necesarias para que los actores tomen decisiones fundamentadas dentro del dominio de Grotix, plasmándolas en post-its de color verde. Estos modelos actúan como vistas o proyecciones que el usuario consume antes de disparar un comando, facilitando la visualización del estado actual del sistema de manera estructurada. Esta etapa es crucial para definir los requisitos de la interfaz de usuario y asegurar que el agricultor cuente con la visibilidad necesaria sobre sus cultivos, garantizando un flujo de trabajo intuitivo donde la información analítica precede y justifica cada acción operativa. 

* **Step 8: External Systems**

[foto]

El Step 8: External Systems identifica los componentes de hardware o servicios de software que operan fuera de los límites de control directo de Grotix, pero que son indispensables para el cumplimiento de sus procesos de negocio. Representados mediante post-its de color rosado, estos sistemas externos actúan como proveedores de datos o ejecutores de acciones físicas con los cuales el sistema debe interactuar asincrónicamente. Esta fase es crítica para definir las interfaces de integración, estableciendo cómo el dominio central se comunica con infraestructuras de terceros o dispositivos físicos para extender la funcionalidad de la plataforma hacia el mundo real y servicios especializados. 


#### 4.1.1.1. Candidate Context Discovery

Al finalizar el mapeo masivo, entramos en la fase de Candidate Context Discovery para "limpiar" el tablero y trazar las fronteras lógicas del software. Aplicamos la técnica de look-for-pivotal-events enfocándonos en los momentos donde el hardware interactúa con la lógica de negocio, como cuando un umbral crítico de humedad dispara forzosamente el análisis de la IA. Mediante start-with-value, priorizamos el ahorro hídrico como el núcleo del sistema, separando las acciones administrativas de los flujos de decisión automática, lo que nos permitió descomponer la línea de tiempo en etapas operativas claras y funcionales.

Este análisis estratégico permitió agrupar los comandos, eventos y modelos de lectura bajo fronteras semánticas coherentes, asegurando que cada sección del modelo responda a un propósito único dentro del ecosistema. Al aplicar estas técnicas de descubrimiento, logramos aislar la lógica más crítica y de mayor valor —como los protocolos de automatización y los controles de auditoría— de las funciones periféricas del sistema. Como resultado, el modelo evoluciona hacia una arquitectura desacoplada que garantiza la integridad de los datos y facilita la futura implementación técnica de los módulos, sin que los cambios en una parte del dominio afecten la estabilidad global de la operación en el campo.

[foto]

El Bounded Context de Profile centraliza la gestión de identidad y seguridad de Grotix, administrando el ciclo de vida del usuario desde el registro y la autenticación hasta el control de sesiones. Su propósito es garantizar un acceso protegido a la plataforma y permitir la personalización de la experiencia del agricultor mediante la edición de datos personales y la configuración de preferencias de notificaciones. Al aislar estas funciones, el sistema asegura que la administración de credenciales y la privacidad del productor se manejen de forma independiente a la lógica operativa del campo, sirviendo como la puerta de acceso segura para todas las funcionalidades del ecosistema. 

[foto]

El Bounded Context de Cultivation Area se encarga de la definición y gestión estructural de las áreas de plantación dentro de la plataforma. Su objetivo principal es administrar la configuración de cada parcela, incluyendo datos críticos como el tipo de cultivo, el área física y los umbrales operativos de humedad y temperatura necesarios para su desarrollo. Además, este contexto regula la seguridad y el control de acceso a las zonas, gestionando las solicitudes de ingreso y permisos para los distintos usuarios. Al centralizar estos parámetros agronómicos y de autorización, el sistema establece el marco de referencia esencial sobre el cual se ejecutan los procesos de monitoreo y riego automatizado. 

[foto]

El Bounded Context de Hardware Device actúa como el puente entre el mundo físico y digital de Grotix, gestionando integralmente el aprovisionamiento y ciclo de vida de los componentes IoT. Su responsabilidad principal es orquestar la detección de microcontroladores, establecer conexiones de red seguras y administrar la vinculación de sensores físicos con la plataforma lógica. Mediante políticas de asignación, este contexto garantiza que cada dispositivo esté correctamente mapeado a una zona de cultivo específica y mantiene actualizado el estado de disponibilidad y actividad del hardware en tiempo real. Al centralizar la gestión de la infraestructura física, permite que el resto del sistema interactúe con el campo de manera abstracta, asegurando una comunicación robusta entre los actuadores, los sensores y la lógica de control superior. 

[foto]

El Bounded Context de Irrigation Cycle constituye el motor de ejecución hídrica de Grotix, responsable de gestionar integralmente los ciclos de riego tanto manuales como automáticos. Este dominio orquesta la interacción directa con los actuadores físicos y aplica políticas de decisión críticas, como el ajuste de condiciones o la postergación de actividades ante pronósticos de lluvia para maximizar el ahorro de recursos. Además, supervisa el cumplimiento de límites de consumo de agua y garantiza la trazabilidad operativa mediante la generación de reportes detallados al finalizar cada intervención. Al aislar esta lógica, el sistema asegura una administración eficiente y autónoma del agua, respondiendo dinámicamente tanto a las órdenes directas del usuario como a las variables ambientales detectadas en tiempo real. 

[foto]

El Bounded Context de Crop Analysis (AI) representa el núcleo de inteligencia visual de Grotix, encargado de monitorear y diagnosticar el desarrollo biológico del cultivo mediante visión artificial. Este dominio orquesta el ciclo de vida de la imagen, desde la captura técnica y el control de iluminación hasta el procesamiento profundo para identificar estados fenológicos y de germinación. Al integrar modelos de IA para el análisis de salud vegetal, este contexto automatiza el seguimiento de los ciclos biológicos, generando reportes históricos y alertas preventivas sobre el estado real de la planta. Su aislamiento garantiza que el procesamiento analítico sea independiente de la mecánica de riego, proporcionando la información crítica necesaria para validar la efectividad de las estrategias agronómicas aplicadas en el campo.

[foto]

El Bounded Context de Telemetry es el pilar de monitoreo y análisis de datos de Grotix, encargado de la ingesta, almacenamiento y visualización de las variables ambientales recolectadas por los sensores de campo. Su responsabilidad abarca desde el procesamiento en tiempo real de niveles de temperatura, luz y humedad, hasta el despliegue de dashboards informativos y la activación de alertas críticas cuando se alcanzan umbrales de riesgo para el cultivo. Al centralizar la telemetría, este contexto permite una supervisión constante de las condiciones del entorno y facilita la auditoría del rendimiento mediante la generación de reportes de eficiencia hídrica, proporcionando la base analítica necesaria para optimizar el uso de recursos y garantizar la salud de la plantación. 

#### 4.1.1.2. Domain Message Flow Modeling
En esta sección se modelan los Domain Message Flows para representar la colaboración entre los bounded contexts de Grotix al resolver los procesos críticos de negocio. Se emplea la técnica de Domain Storytelling para narrar e ilustrar el intercambio de mensajes entre los actores, los dispositivos IoT y los servicios de software. 

* **Escenario 1: Registro de Nueva Zona de Cultivo y Vinculación de Hardware**

[foto]

Este flujo describe la orquestación técnica que ocurre cuando un usuario registra una nueva zona de cultivo en Grotix, iniciando con el comando Crear Zona de Cultivo que, tras superar una política de validación de campos, activa el Bounded Context de Cultivation Area para generar tanto una notificación de éxito como la actualización visual en la interfaz. Simultáneamente, el sistema escala la operación hacia el contexto de Hardware Device mediante el comando Asignar microcontrolador, donde el sistema de sensores valida la vinculación física del dispositivo y ejecuta finalmente el comando de vinculación técnica entre el microcontrolador y la zona lógica, asegurando que los datos de telemetría queden correctamente mapeados desde el primer momento.

* **Escenario 2: Riego Automático por Identificación de IA**

[foto]

Este flujo describe la orquestación técnica que comienza en el Bounded Context de Crop Analysis (IA) con el procesamiento de imágenes y la identificación del tipo de cultivo, generando eventos clave que activan la lógica de decisión del sistema. Tras superar una política de validación de umbrales basada en la especie detectada, el contexto de Irrigation cycle colabora con Cultivation area para obtener los parámetros hídricos óptimos, escalando la operación hacia el Bounded Context de Hardware Device mediante el comando de inicio de riego automático. Finalmente, el sistema interactúa con el actuador físico para ejecutar el comando de activación de la bomba de agua, culminando el proceso con la emisión del evento Riego Iniciado, lo que garantiza que la ejecución hídrica esté perfectamente alineada con las necesidades biológicas detectadas por la inteligencia artificial en tiempo real. 

* **Escenario 3: Respuesta a Umbral Crítico de Telemetría (Alerta)**

[foto]

Este flujo detalla la respuesta reactiva del sistema ante condiciones críticas en el campo, comenzando cuando el Sensor emite el evento Lectura de sensor de nivel de humedad, el cual es captado por el contexto de Hardware Device y validado mediante una política que confirma la relación entre el microcontrolador y la zona de cultivo. Una vez verificada la identidad del dispositivo, el flujo se traslada al contexto de Cultivation Area para emitir el evento Nivel de humedad leído, que sirve como entrada para el contexto de Telemetry; allí, una Política de validación de umbral analiza el dato y, al detectar niveles fuera de rango, dispara el evento Umbral crítico de humedad alcanzado. Finalmente, este evento activa el comando Generar alerta de umbral excedido dentro del contexto de Profile, culminando en una Notificación (Toast) enviada directamente al usuario para informarle sobre la anomalía y permitir una toma de decisiones inmediata basada en los datos de telemetría.

* **Escenario 4: Intervención manual remota**

[foto]

Este flujo describe la orquestación técnica que ocurre cuando el Usuario de Grotix decide actuar sobre el campo mediante el comando Iniciar riego manual, especificando el ID del área y la duración requerida. Esta instrucción es procesada por el Bounded Context de Irrigation Cycle, que escala la operación hacia el contexto de Hardware Device a través del envío de un mensaje de control manual para la zona afectada. Finalmente, el sistema interactúa con la infraestructura física ejecutando el comando Activar bomba de agua sobre el actuador correspondiente (Bomba/Válvula), culminando el proceso con la emisión del evento Riego iniciado manualmente, lo que asegura la trazabilidad del inicio de la operación y la sincronización del estado hídrico en todo el ecosistema.

#### 4.1.1.3. Bounded Context Canvases

Esta sección presenta el diseño estratégico de los Bounded Contexts de Grotix, la plataforma de agricultura inteligente desarrollada por la startup Celevi. Cada canvas modela uno de los seis contextos identificados en el dominio, describiendo sus responsabilidades, el lenguaje ubicuo que lo rige, las comunicaciones de entrada y salida con otros contextos, y las decisiones de negocio que encapsula.Gratix integra sensores IoT, automatización de riego y visión artificial por IA para democratizar la agricultura de precisión en el Perú. Su arquitectura de dominio responde a esta complejidad técnica distribuyendo las responsabilidades en seis contextos diferenciados

**Profile Bounded Context**

[foto]

**Cultivation Area Bounded Context:**

[foto]

**Hardware Device Bounded Context:**

[foto]

**Irrigation cycle Bounded Context:**

[foto]

**Crop Analysis (AI) Bounded Context:**

[foto]

**Telemetry Bounded Context:**

[foto]

### 4.1.2. Context Mapping
El Context Mapping de Grotix representa la estructura estratégica de nuestra solución, definiendo las fronteras de responsabilidad y los patrones de relación entre los seis Bounded Contexts identificados. Este mapeo no solo facilita la organización técnica del sistema, sino que establece contratos de comunicación claros que protegen el Core Domain —centrado en la inteligencia de riego y eficiencia hídrica—. Al aplicar diferentes patrones, aseguramos una arquitectura resiliente, desacoplada y preparada para escalar conforme a las exigencias de sostenibilidad y trazabilidad que el sector agrario demanda.

**Conexión 1: Crop Analysis (AI) → Irrigation Cycle**

[foto]

La relación entre Crop Analysis (AI) e Irrigation Cycle se define bajo el patrón Upstream/Downstream, donde el contexto de IA provee información crítica sobre la identidad y etapa de crecimiento del cultivo hacia el sistema de riego. Para proteger la estabilidad del núcleo del negocio, se ha implementado una Anti-Corruption Layer (ACL) en el lado del Ciclo de Riego. Esta capa actúa como un mediador técnico que traduce los datos complejos generados por los modelos de visión artificial en parámetros de riego estandarizados, evitando que cambios en los modelos de IA o en el hardware de la cámara afecten directamente la lógica de bombeo.

Esta decisión arquitectónica se tomó tras evaluar la posibilidad de fusionar ambos contextos, lo cual fue descartado para evitar la creación de un servicio monolítico y difícil de mantener. Al mantener el aislamiento mediante el ACL, el sistema gana flexibilidad para actualizar o reemplazar sus capacidades de visión artificial de forma independiente. De esta manera, Grotix asegura una operación autónoma resiliente, donde la inteligencia de reconocimiento alimenta al sistema de riego sin comprometer la integridad de la ejecución física en el campo.


**Conexión 2: Hardware Device ←→ Telemetry**

[foto]

La relación entre Hardware Device y Telemetry se establece mediante un patrón de Partnership, reflejando una dependencia mutua donde ambos contextos deben evolucionar en sincronía para garantizar la integridad de los datos. En este flujo, el contexto de hardware actúa como el emisor de los Datos del sensor y el Estado del dispositivo, enviando lecturas en bruto de humedad, temperatura y luz, así como actualizaciones sobre la disponibilidad de los microcontroladores. El contexto de Telemetría recibe esta información para procesarla, almacenarla y validar umbrales críticos, permitiendo que la lógica de negocio se base en un estado físico veraz y actualizado.

Se seleccionó este patrón tras descartar una relación de Cliente/Proveedor, debido a que cualquier cambio en la especificación técnica de los sensores o en el firmware del hardware impacta directamente en cómo Telemetría interpreta las señales. Al trabajar como socios, se asegura que las capacidades de monitoreo y la generación de reportes de eficiencia hídrica se mantengan alineadas con las capacidades reales del equipo físico. Esta cohesión es fundamental para Grotix, ya que permite una trazabilidad completa desde la señal eléctrica captada en el campo hasta la visualización de datos en el dashboard del usuario.

**Conexión 3: Irrigation Cycle → Hardware Device**

[foto]

La relación entre Irrigation Cycle y Hardware Device se define bajo el patrón Upstream/Downstream, donde el ciclo de riego actúa como el lado Upstream (U) al ser el responsable de tomar las decisiones lógicas y estratégicas. Este contexto emite los Comandos de acción (Encendido/Apagado) que el contexto de Hardware Device, en posición Downstream (D), debe ejecutar físicamente a través de los actuadores y bombas de agua en el campo.

Esta jerarquía asegura que la responsabilidad del "cuándo" y "por qué" regar recaiga exclusivamente en la lógica de negocio, mientras que el contexto de hardware se limita a traducir esas órdenes en impulsos eléctricos. Al separar la decisión de la ejecución, Grotix permite que el sistema de riego funcione de manera agnóstica a la marca o modelo de los actuadores utilizados; si el hardware físico cambia, solo se ajusta la implementación técnica en el lado receptor, manteniendo intacta la inteligencia de riego adaptativo y manual del sistema.

**Conexión 4: Cultivation Area ←→ Telemetry**

[foto]

La relación entre Cultivation Area y Telemetry se materializa a través de un Shared Kernel (Núcleo Compartido), donde ambos contextos gestionan de forma conjunta el Umbral de cultivo y el mapeo de áreas. Esta intersección es vital para el sistema, ya que la telemetría necesita conocer las coordenadas y dimensiones de las zonas definidas en el área de cultivo para asignar correctamente las lecturas de los sensores, mientras que el área de cultivo requiere que la telemetría valide si las condiciones ambientales actuales respetan los umbrales específicos de cada planta.

Se optó por este patrón para garantizar una consistencia inmediata en los datos compartidos, evitando la duplicación de lógica relacionada con los parámetros biológicos de los cultivos. Al compartir este núcleo, cualquier actualización en los límites de humedad o temperatura permitidos se refleja automáticamente en ambos contextos, permitiendo que el dashboard de telemetría y la configuración de las zonas agrícolas operen bajo una "única fuente de verdad". Esta sinergia es clave en Grotix para asegurar que los reportes de eficiencia hídrica sean precisos y estén vinculados correctamente a cada parcela específica.

**Conexión 5: Telemetry → Irrigation Cycle**

[foto]

La relación entre Telemetry e Irrigation Cycle se establece bajo el patrón Upstream/Downstream, donde el contexto de telemetría actúa como el lado Upstream (U). Este contexto es el encargado de suministrar los Datos Ambientales y alertas (como niveles de humedad, temperatura y luz) que son fundamentales para que el sistema tome decisiones informadas. El contexto de Irrigation Cycle se sitúa como el Downstream (D), ya que su capacidad para ajustar o postergar el riego automático depende enteramente de la validez y precisión de la información recibida desde la telemetría.

Esta conexión es el motor del riego inteligente en Grotix, permitiendo que el sistema reaccione dinámicamente a las condiciones del entorno. Al separar la recolección de datos de la ejecución del riego, se logra que el ciclo de irrigación sea más eficiente y resiliente; por ejemplo, ante una alerta de umbral de humedad alcanzado emitida por telemetría, el ciclo de riego puede decidir detener el bombeo inmediatamente para evitar el desperdicio de agua. Esta estructura garantiza que la lógica de optimización hídrica esté siempre respaldada por datos ambientales en tiempo real, cumpliendo con el objetivo de sostenibilidad del proyecto

**Conexión 6: Profile → All**

[foto]

Finalmente, cerramos el mapeo con la relación entre Profile y el resto de los contextos del sistema, la cual se define mediante el patrón Open Host Service (OHS) con un Published Language (PL).

En esta arquitectura, el contexto de Profile actúa como el proveedor Upstream (U) de servicios de identidad, sesiones y permisos. Al implementarse como un Open Host Service, Profile expone una interfaz pública estandarizada y estable que permite a todos los demás contextos (Telemetry, Irrigation, etc.) consumir datos de usuario sin necesidad de negociar cambios individuales. El uso de un lenguaje común (PL) garantiza que conceptos como el "ID de usuario" o los "Niveles de acceso" sean interpretados de la misma manera en toda la plataforma, facilitando la integración de nuevas funcionalidades.

Se eligió este patrón para evitar que el contexto de perfil se convierta en un cuello de botella o que dependa de las necesidades específicas de cada módulo. Al centralizar la gestión de usuarios y notificaciones bajo un estándar abierto, Grotix asegura un control de acceso robusto y una experiencia de usuario coherente, permitiendo que el sistema crezca en complejidad mientras mantiene un protocolo de comunicación simplificado y altamente escalable para todas sus operaciones de seguridad y personalización.

### 4.1.3. Software Architecture

Para abordar el diseño de la arquitectura de software de Grotix, se ha adoptado el Modelo C4, una técnica que permite visualizar el sistema en niveles de abstracción crecientes para facilitar la comprensión tanto de su interacción macro con los productores y servicios externos como de la orquestación técnica micro de sus dispositivos IoT y módulos de IA. Esta representación arquitectónica no solo detalla la composición interna de la solución, sino que también ilustra las responsabilidades y flujos críticos entre el software y el hardware, asegurando un diseño robusto y escalable que responde en tiempo real a las exigencias de eficiencia hídrica y sostenibilidad que definen la visión del proyecto. 

La siguiente leyenda define los elementos visuales y semánticos utilizados para representar la estructura y las interacciones del ecosistema Grotix:

[foto]

* **Boundary, Software System**: Representa el límite físico o lógico que encierra a todos los contenedores que forman parte del sistema (Grotix). Ayuda a distinguir qué piezas desarrolla el equipo y cuáles son externas.
* **Container, Browser**: Representa una aplicación web o Single Page Application (SPA) que se ejecuta en el navegador del cliente.
* **Container, Database**: Representa cualquier sistema de almacenamiento de datos persistente. 
* **Container, Gateway**: Representa un punto de entrada único (API Gateway) que gestiona el tráfico, la seguridad y el enrutamiento hacia microservicios internos.
* **Container, Microservice**: Representa un servicio independiente con su propia lógica de negocio y base de datos.
* **Container, Mobile App**: Representa la aplicación nativa o híbrida que el agricultor instala en su dispositivo.
* **Container, Web App**: Representa la aplicación web a la que accede el staff y la Landing Page en donde los usuarios se informan sobre qué es grotix.
* **Person**: El actor humano que interactúa con los contenedores (Usuario final).
* **Software System, External**: Sistemas externos con los que tus contenedores se comunican.
* **Software System, External Hardware**: El hardware de Grotix (microcontroladores, sensores, etc.).
* **Relationship (Flecha punteada)**: Representa la comunicación y dependencia entre dos elementos. La flecha indica la dirección de la interacción y suele ir acompañada de una descripción del protocolo o tipo de dato transferido.

#### 4.1.3.1. Software Architecture System Landscape Diagrams

El System Landscape de Grotix representa el ecosistema empresarial completo de la organización, no limitándose únicamente a la plataforma agrícola inteligente, sino abarcando todos los sistemas que sostienen su operación como empresa. Además del Sistema Grotix — núcleo tecnológico que integra el hardware IoT de campo con la plataforma cloud de monitoreo — se identifican cuatro sistemas internos de soporte: el Sistema de Ventas & CRM, que gestiona el pipeline comercial y la captación de asociaciones agrarias como clientes; el Sistema Financiero, responsable de la facturación y cobranza de suscripciones; el Sistema de Logística, que controla el inventario y despacho de dispositivos IoT hacia las parcelas; y el Sistema de RRHH, que administra al equipo humano de Grotix. Estos sistemas internos interactúan entre sí y con la plataforma principal, reflejando cómo el cierre de un contrato comercial activa automáticamente una cuenta en el sistema agrícola, o cómo el despacho logístico de un sensor queda registrado en la plataforma. Externamente, Grotix se apoya en un servicio de autenticación, una plataforma de notificaciones, una API meteorológica y una pasarela de pagos para completar sus capacidades.

[foto]

#### 4.1.3.2. Software Architecture Context Level Diagrams

El diagrama de System Context sitúa al Sistema Grotix como el núcleo de la solución, definiendo sus límites operativos y las interacciones directas con su entorno. En este nivel de abstracción, el Hardware Grotix se identifica como un sistema externo con el cual se establece un flujo bidireccional de telemetría y control. Asimismo, se detallan las interfaces con actores humanos (Agricultor, Asociación y Staff) y la dependencia con servicios de terceros (Auth, Notificaciones y Clima). Este diagrama permite visualizar de manera clara cómo el sistema central actúa como orquestador, consumiendo datos externos y comandos de usuario para transformarlos en acciones de riego precisas y reportes de valor agregado.

[foto]

Para robustecer su operatividad, el Sistema Grotix se integra con diversos servicios externos y componentes físicos que complementan su lógica de negocio. La seguridad y validación de identidad se delegan a un Servicio de Autenticación, mientras que la comunicación proactiva con el usuario se canaliza mediante un Servicio de Notificaciones para alertas push y un Servicio de Correo para envíos informativos. Asimismo, el sistema consume datos críticos de una API de Clima para la planificación del riego y mantiene una comunicación bidireccional con el Hardware Grotix, recibiendo lecturas de sensores e imágenes, y enviando comandos de actuación a las bombas. Esta arquitectura asegura una orquestación eficiente entre el software, los servicios en la nube y la infraestructura física desplegada.

#### 4.1.3.3. Software Architecture Container Level Diagrams

[foto]

El diagrama de contenedores del Sistema Grotix presenta la arquitectura completa del ecosistema IoT organizada en cuatro capas diferenciadas. La capa de usuario agrupa tres interfaces: la Landing Page, que sirve como portal informativo y redirige a los visitantes a la descarga de la aplicación móvil; la Mobile App en Flutter, utilizada por agricultores y asociaciones agrarias para el monitoreo y control operativo de sus cultivos; y la Staff Web App, destinada al equipo administrativo de Grotix para la gestión de dispositivos y usuarios. La capa edge es el puente entre el mundo físico y la nube: el Embedded App ejecuta el firmware que lee los sensores y acciona las bombas de riego, reportando los estados físicos al Edge App, que procesa localmente las reglas críticas y sincroniza los datos en una base de datos SQLite para garantizar la persistencia ante pérdidas de conectividad. La capa cloud está compuesta por un API Gateway basado en YARP como punto de entrada único que enruta las solicitudes hacia seis microservicios especializados: el Profile Service para la gestión de cuentas e identidad, el Cultivation Service para la administración de granjas y zonas, el Telemetry Service para la ingesta de datos de sensores almacenados en TimescaleDB, el Irrigation Service para la orquestación del riego automático con consulta de datos meteorológicos externos, el Crop Analysis Service para el diagnóstico fenológico mediante inteligencia artificial, y el Hardware Service para el inventario y vinculación de dispositivos IoT. Los servicios transaccionales persisten en una base de datos MySQL centralizada. Finalmente, el Message Broker (RabbitMQ) actúa como columna vertebral de la comunicación asíncrona, canalizando eventos de integración como UserRegistered, TelemetryReceived, AlertTriggered, IrrigationCompleted, GrowthStateChanged y DeviceStatusChanged, desacoplando los microservicios y permitiendo que el sistema reaccione en tiempo real ante cambios en el entorno de cultivo y dispare notificaciones push a los agricultores a través del Servicio de Notificaciones externo.

#### 4.1.3.4. Software Architecture Deployment Diagrams

El Deployment Diagram de Grotix describe la distribución física de los componentes del sistema en un entorno de producción real. En la capa de usuario, los agricultores y asociaciones acceden a la plataforma mediante una aplicación móvil desarrollada en Flutter, mientras que el equipo de Staff opera desde un navegador web con la Staff Web App construida en Vue.js. En campo, cada zona de cultivo cuenta con una Raspberry Pi que ejecuta el Edge App en un contenedor Docker, permitiendo procesamiento local y operación offline ante pérdidas de conectividad, complementada por nodos ESP32 con firmware embebido que interactúan directamente con los sensores y actuadores físicos. Toda la infraestructura cloud se despliega sobre Microsoft Azure en la región Chile Central: el API Gateway, implementado con ASP.NET Core y YARP, actúa como punto de entrada único y enruta el tráfico hacia los microservicios especializados — Profiles, CultivationArea, Telemetry, Irrigation, Hardware y Crop Analysis — cada uno desplegado de forma independiente como Azure App Service. La comunicación asíncrona entre servicios se gestiona a través de RabbitMQ, mientras que la persistencia se distribuye entre Azure Database for MySQL para los datos maestros y transaccionales, y TimescaleDB para el almacenamiento de series temporales de telemetría. Finalmente, el sistema se integra con servicios externos de terceros para autenticación, notificaciones push y datos meteorológicos.

[foto]

## 4.2. Tactical-Level Domain-Driven Design 

### 4.2.1. Bounded Context: Profile

#### 4.2.1.1. Domain Layer

**Aggregates:**
*   **UserAggregate:** Raíz que agrupa la información del usuario, su identidad y su rol asignado para garantizar la consistencia en los cambios de perfil.

**Entities:**
*   **Role:** Entidad que define el conjunto de permisos (Admin, Agricultor, etc.) vinculados a un usuario.
*   **Identity:** Entidad responsable de las credenciales de acceso, como el PasswordHash.
*   **Association:** Entidad que representa a la asociación agraria a la que pertenece el usuario, con sus datos de contacto (Name, Email).

**Value Objects:**
*   **UserEmail:** Valida que el formato del correo electrónico sea correcto antes de la creación de la cuenta.
*   **PermissionCode:** Representa los códigos de acción específicos permitidos en el sistema.
*   **UserPhone:** Valida el formato internacional del número telefónico.
*   **UserPreferences:** Un Value Object que encapsula y valida la estructura del JSON de preferencias ({"push": true, "email": false}).

**Domain Services:**
*   **PasswordHasher:** Servicio encargado de encriptar las contraseñas antes de persistirlas.

**Interfaces (Repositories):**
*   **IUserRepository:** Define los métodos para buscar usuarios por identidad y persistir nuevos registros.

#### 4.2.1.2. Interface Layer

**Controllers:**
*   **AuthController:** Gestiona las peticiones de Iniciar Sesión y Cerrar Sesión.
*   **UserProfileController:** Expone endpoints para que el usuario pueda Modificar Datos de perfil o Activar envío de notificaciones.
*   **AssociationController:** Podrías agregar este controlador para que el Staff pueda registrar nuevas asociaciones en el sistema.

**Consumers:**
*   **ProfileSyncConsumer:** Escucha eventos de otros contextos si se requiere una actualización de perfil en cascada.

#### 4.2.1.3. Application Layer

**Command Handlers:**
*   **CreateAccountHandler:** Orquesta el flujo completo de creación de cuenta: validación de correo, asignación de nombre y foto, y persistencia inicial.
*   **UpdatePreferencesHandler:** Maneja la lógica para activar o desactivar notificaciones según la elección del usuario.

**Event Handlers:**
*   **UserRegisteredEventHandler:** Dispara acciones posteriores al registro, como el envío de un correo de bienvenida a través del servicio externo de notificaciones.

#### 4.2.1.4. Infrastructure Layer

**Repositories Implementation:**
*   **CoreDbUserRepository:** Implementación en SQL (Core DB) que accede a las tablas de user, role e identity.

**External Service Clients:**
*   **AuthServiceClient:** Conexión con el servicio externo de identidad para validación de tokens o sesiones.
*   **NotificationServiceAdapter:** Cliente que se comunica con Firebase para gestionar el estado de las notificaciones push configuradas en el perfil.

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Profile Service refleja la arquitectura en capas del bounded context de perfil e identidad. Las peticiones entrantes llegan a través del API Gateway y son atendidas por tres controladores REST: el Auth Controller para registro y login, el User Profile Controller para consulta y edición del perfil propio, y el Admin Users Controller para operaciones administrativas restringidas al rol admin. Cada controlador delega la lógica a handlers MediatR o application services: el Create Account Handler orquesta el alta validando la invitación, hasheando la contraseña con BCrypt y publicando el evento UserRegistered al broker; el Login Command Handler valida credenciales y genera el JWT con roles y permisos embebidos; y los services de comando y consulta operan directamente sobre los repositorios EF Core que persisten en la Core DB (MySQL). Los servicios de dominio Invite Token Hasher y BCrypt Password Hasher encapsulan la lógica de seguridad pura, mientras que el RabbitMQ Publisher desacopla la notificación de registro hacia los demás microservicios del ecosistema. 

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases del bounded context de Profile muestra el modelo de dominio organizado en dos paquetes. En el paquete IAM Domain, el agregado raíz Identity encapsula las credenciales de acceso del usuario, almacenando el correo como nombre de usuario y la contraseña como el value object PasswordHash, garantizando que nunca se persista en texto plano; además expone el método estático VerifyPasswordStrength que aplica las reglas de seguridad de contraseña. En el paquete Profile Domain, el agregado raíz User centraliza el perfil de negocio, referenciando a Identity mediante identityId y componiendo los value objects UserEmail, UserPhone y UserPreferences para encapsular validaciones de formato y preferencias de notificación; se vincula además a la entidad Role, la cual agrega permisos mediante la tabla de unión RolePermissionLink en una relación N:N con Permission, cuyo código se valida a través del value object PermissionCode. La entidad AssociationInvite modela las invitaciones de acceso, cuyo token es procesado por el domain service estático InviteTokenHasher. Finalmente, las interfaces de repositorio IUserRepository, IIdentityRepository, IRoleRepository e IAssociationInviteRepository definen los contratos de persistencia que desacoplan el dominio de la infraestructura, junto con IPasswordHasher que abstrae el algoritmo de hashing.

##### 4.2.1.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Profile ha sido cuidadosamente estructurado bajo el patrón de Agregado, estableciendo a la tabla user como la raíz de agregado (Aggregate Root) encargada de centralizar la gestión de identidad y acceso dentro del ecosistema Grotix. Esta arquitectura de datos se fundamenta en una separación física de responsabilidades mediante una relación de cardinalidad uno a uno entre las tablas user e identity, lo cual permite que la información de contacto y fiscal del agricultor, como su nombre y el identificador tributario, resida en una capa lógica distinta a las credenciales sensibles. Esta normalización es crítica para la seguridad del sistema, ya que permite que el servicio de dominio encargado de la encriptación de contraseñas interactúe exclusivamente con el registro de identidad sin comprometer la integridad de los datos personales, facilitando además la interoperabilidad con servicios externos de autenticación y la futura rotación de claves sin afectar el historial del usuario.

Para dar soporte a la lógica de autorización definida en la capa de dominio, el esquema implementa un modelo de Control de Acceso Basado en Roles que permite una gestión granular de las capacidades de cada perfil. Esta estructura se materializa a través de las tablas role y permission, las cuales se vinculan mediante una tabla asociativa que resuelve la relación de muchos a muchos necesaria para asignar múltiples códigos de permisos a un rol específico. Gracias a este diseño, el repositorio de datos puede recuperar un objeto de usuario completamente hidratado con su mapa de permisos en una sola operación transaccional, lo que optimiza significativamente la respuesta de la API ante solicitudes de validación de acciones críticas. El esquema se completa con restricciones de integridad referencial y de unicidad en columnas clave como el nombre de usuario, garantizando que la persistencia sea robusta y capaz de escalar ante la incorporación de nuevos niveles de acceso o la expansión de las preferencias de notificación del agricultor sin requerir cambios estructurales en la base de datos maestra.

### 4.2.2. Bounded Context: Cultivation Area
#### 4.2.2.1. Domain Layer

**Aggregates:**
* **FarmAggregate**: Raíz que agrupa las zonas de cultivo para asegurar la integridad de la ubicación, propiedad del terreno y su vinculación a un usuario/agricultor. 

**Entities:**
* **Zone**: Representa una subdivisión física. Se han añadido atributos de geolocalización (Lat/Long), la fase actual del cultivo (currentPhase), la fecha de inicio de dicha fase (phaseStartDate) y la URL de la imagen de referencia (imageUrl) para auditoría visual.
* **Crop**: Define las características biológicas maestras (nombre científico, variedad).
* **GrowthStage**: Define las etapas por las que pasa el cultivo y su duración estimada.
* **Microcontroller**: Representa el hardware físico vinculado a la zona para monitoreo.

**Value Objects:**
* **BiologicalThresholds**: Encapsula los niveles óptimos de temperatura, luz y humedad.
* **LocationCoordinates**: Objeto inmutable que valida y contiene la latitud y longitud de la zona..

**Domain Services:**
* **CropLifecycleManager**: Servicio que determina el cambio de fases fenológicas basado en el tiempo transcurrido desde la siembra.

**Interfaces (Repositories):**
* **IFarmRepository**: Contrato para la persistencia de granjas y zonas.
* **ICropRepository**: Contrato para gestionar el catálogo de cultivos y sus umbrales.

#### 4.2.2.2. Interface Layer

**Controllers:**
* **FarmController**: Expone endpoints para crear granjas, añadir zonas y asignar microcontroladores.
* **CatalogController**: Permite al staff de Grotix gestionar el catálogo maestro de cultivos y sus parámetros biológicos.

**Consumers:**
* **TelemetrySyncConsumer**: Escucha si otros contextos necesitan datos actualizados de mapeo de áreas o umbrales.

#### 4.2.2.3. Application Layer

**Command Handlers:**
* **RegisterFarmHandler**: Coordina la creación inicial del terreno y la asignación del usuario propietario.
* **SetupZoneHandler**: Maneja la lógica de vincular un microcontrolador específico a una zona y definir su tipo de cultivo.

**Event Handlers:**
* **ThresholdUpdatedEventHandler**: Reacciona cuando se modifican los parámetros biológicos, notificando a Telemetry para que actualice sus validaciones en tiempo real.

#### 4.2.2.4. Infrastructure Layer

**Repositories Implementation:**
* **EntityFrameworkFarmRepository**: Implementación en SQL (Core DB) que gestiona las tablas farm, zone y microcontroller.

**Message Brokers:**
* **RabbitMQPublisher**: Publica cambios en los umbrales de cultivo hacia el bus de eventos para que sean consumidos por el contexto de Telemetry.

**External Services:**
* **MapsServiceAdapter**: Integración opcional con servicios de mapas para validar la ubicación geográfica de las granjas.

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Cultivation Service refleja la arquitectura en capas del bounded context de administración de cultivos. Las peticiones entrantes llegan a través del API Gateway y son atendidas por tres controladores REST: el Farms Controller para la gestión de granjas y creación de zonas por granja, el Zones Controller para la consulta y edición individual de zonas, y el Catalog Controller para el mantenimiento del catálogo maestro de cultivos, con escritura restringida a roles admin y staff. Cada controlador delega la lógica a sus respectivos command y query services: el Farm Command Service y Zone Command Service orquestan las operaciones de creación y actualización validando reglas de negocio como la existencia del cultivo antes de crear una zona, mientras que el Crop Command Service impide la eliminación de un cultivo si hay zonas que lo referencian. Los repositorios EF Core persisten los datos en la Core DB (MySQL), y el RabbitMQ Consumer se encarga de consumir el evento UserRegistered publicado por el Profile Service para mantener la sincronización entre bounded contexts.

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases del bounded context de Cultivation Area presenta tres elementos principales. Farm es el agregado raíz que representa la unidad física de cultivo de un agricultor, identificando al propietario mediante userId como referencia al contexto de Profile, y agrupando sus zonas de cultivo. Zone es una entidad que pertenece a una granja específica y referencia un cultivo del catálogo mediante cropId, registrando además la fase fenológica actual, las coordenadas geográficas y una imagen del estado de la planta. Crop es también un agregado raíz independiente que modela el catálogo maestro de especies, encapsulando los parámetros biológicos óptimos como temperatura, humedad, luz y tiempo máximo de estrés. Las interfaces IFarmRepository, IZoneRepository e ICropRepository definen los contratos de persistencia desacoplando el dominio de la infraestructura, destacando métodos especializados como ListByUserIdAsync, ListByFarmIdAsync y AnyByCropIdAsync que soportan las reglas de negocio del servicio.

##### 4.2.2.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Cultivation Area ha sido desarrollado para soportar el FarmAggregate, garantizando una jerarquía clara que va desde la propiedad del terreno hasta el despliegue de hardware en campo. La estructura de datos se organiza en un modelo relacional que prioriza la integridad de la ubicación y la precisión de los parámetros biológicos. La tabla farm funciona como el punto de entrada principal, vinculando al propietario con sus extensiones de tierra, mientras que la tabla zone actúa como el eje de articulación del contexto. En esta última se consolidan las dependencias críticas: la relación con la tabla crop, que provee el conocimiento agronómico necesario, y la vinculación con el microcontroller, estableciendo así la conexión física entre el software de gestión y el dispositivo IoT asignado a dicha área.

La persistencia del conocimiento biológico se gestiona de forma centralizada a través de la tabla crop, la cual funciona como un catálogo maestro donde se almacenan los BiologicalThresholds. Estos umbrales, representados por columnas de valores óptimos y tiempos de estrés máximos, son fundamentales para que el CropLifecycleManager pueda determinar las transiciones de fase fenológica sin necesidad de realizar cálculos externos costosos. Al almacenar estos parámetros de forma tipada, se asegura que cualquier actualización en el catálogo biológico se propague de manera consistente hacia las zonas de cultivo activas. Finalmente, la inclusión de la tabla microcontroller dentro de este esquema de persistencia permite que el repositorio de infraestructura valide la disponibilidad del hardware antes de su asignación, evitando conflictos de duplicidad y asegurando que cada nodo sensor esté correctamente geolocalizado dentro de la estructura de zonas de la granja.

### 4.2.3. Bounded Context: Hardware Device
#### 4.2.3.1. Domain Layer

**Aggregates:**
* **DeviceAggregate**: Raíz que representa el microcontrolador físico. Garantiza que el estado de los sensores y actuadores conectados sea consistente con la configuración de la zona.

**Entities:**
* **Actuator**: Representa los componentes físicos de acción, como las electroválvulas de riego.
* **InternalSensor**: Representa los componentes de lectura (Humedad de suelo, temperatura, etc.) integrados al hardware.

**Value Objects:**
* **ConnectivityStatus**: Define si el dispositivo está Online, Offline o en modo Maintenance.
* **PowerLevel**: Objeto inmutable que gestiona el porcentaje de batería y el estado de carga (Solar/Batería).

**Domain Services:**
* **HeartbeatMonitor**: Servicio que valida la frecuencia de reporte del hardware para detectar desconexiones prematuras.

**Interfaces (Repositories/Gateways):**
* **IDeviceRepository**: Interfaz para persistir el estado y metadatos del hardware.
* **IHardwareInterface**: Abstracción para el control de pines GPIO o protocolos industriales.

#### 4.2.3.2. Interface Layer

**Controllers:**
* **HardwareStatusController**: Expone el estado de salud del hardware (CPU, RAM, señal) para el dashboard técnico.

**Consumers:**
* **IrrigationCommandConsumer**: Escucha las órdenes de apertura/cierre enviadas por el Bounded Context de Irrigation Cycle.
* **ConfigSyncConsumer**: Recibe actualizaciones sobre cambios en la frecuencia de muestreo de sensores.

#### 4.2.3.3. Application Layer

**Command Handlers:**
* **ExecuteIrrigationCommandHandler**: Orquesta la apertura física del actuador y verifica que el flujo de agua se haya iniciado.
* **CaptureTelemetryHandler**: Coordina la lectura sincronizada de todos los sensores conectados al dispositivo.

**Event Handlers:**
* **ConnectionLostEventHandler**: Reacciona cuando el dispositivo pierde el enlace con el broker, activando protocolos de almacenamiento local (Fail-safe).
* **LowBatteryEventHandler**: Dispara una alerta de prioridad alta hacia el contexto de Profile para notificar al agricultor.

#### 4.2.3.4. Infrastructure Layer

**Repositories Implementation:**
* **PostgresDeviceRepository**: Implementación que utiliza la tabla microcontroller de la Core DB para guardar el inventario de hardware.

**Messaging Systems:**
* **MqttBrokerAdapter**: Implementación del cliente MQTT para el envío del "Raw Sensor Data" hacia Telemetry.

**Hardware Implementation:**
* **Esp32GpioController**: Implementación específica para el control de hardware basada en el microcontrolador utilizado (ej. ESP32 o Raspberry Pi).

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Hardware Device ilustra la arquitectura interna de la estación de control en el borde, donde el MQTT Broker Adapter actúa como el puente de comunicación bidireccional para el envío de telemetría y la recepción de comandos. La lógica operativa se divide en handlers de aplicación: el Capture Telemetry Handler, que orquesta la lectura de variables ambientales, y el Execute Irrigation Handler, que traduce las órdenes del servicio de riego en acciones físicas mediante el ESP32 GPIO Controller. En el núcleo, el Device Aggregate mantiene el estado de integridad del hardware (niveles de batería y conectividad), mientras que el Heartbeat Monitor garantiza que el dispositivo permanezca visible para el sistema, permitiendo una supervisión técnica constante a través del Hardware Status Controller.

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases de la capa de dominio de Hardware Device modela la estación física como el Agregado Raíz HardwareDevice, encargado de orquestar el ciclo de vida de los componentes electrónicos en el campo. El sistema distingue entre Sensors, que producen objetos de valor del tipo RawData mediante lecturas ambientales, y Actuators, que ejecutan acciones físicas como la activación de bombas o válvulas. La integridad operativa se mantiene a través del objeto de valor BatteryLevel y el estado enumerado DeviceStatus, mientras que el servicio de dominio DeviceHeartbeatService asegura que la sincronización con la nube sea constante. Finalmente, la interfaz IHardwareInterface actúa como una capa de abstracción (HAL), permitiendo que la lógica de negocio interactúe con los pines físicos del microcontrolador sin quedar acoplada a un modelo de hardware específico (ej. ESP32 vs Raspberry Pi).

##### 4.2.3.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Hardware Device se ha estructurado para representar fielmente la topología física del sistema en el campo, utilizando la tabla microcontroller como la raíz de agregado (Aggregate Root). Esta tabla no solo funciona como un inventario de dispositivos, sino que centraliza el estado de salud del hardware mediante columnas dedicadas al Status y LastSeen, permitiendo que el HeartbeatMonitor persista la disponibilidad del equipo en tiempo real. Al actuar como el nodo central, el microcontrolador extiende su autoridad hacia las entidades dependientes de sensores y actuadores, garantizando que cualquier componente electrónico esté lógicamente vinculado a un controlador físico antes de su operación.

La persistencia de los componentes periféricos se gestiona a través de las tablas sensor y actuator, las cuales mantienen una relación de dependencia funcional con el microcontrolador. En estas tablas, el diseño enfatiza la configuración técnica necesaria para la capa de infraestructura, almacenando metadatos críticos como el Pin físico de conexión y el Type de componente. Esta estructura permite que el IDeviceRepository recupere la configuración completa de pines del hardware en una sola consulta, facilitando que el servicio de abstracción de hardware (HAL) mapee las órdenes lógicas de la capa de aplicación hacia las señales eléctricas correspondientes. Además, el seguimiento del estado individual de cada periférico asegura que el sistema pueda aislar fallos en sensores específicos sin marcar la estación completa como inoperativa, optimizando así las labores de mantenimiento preventivo y correctivo.

### 4.2.4. Bounded Context: Irrigation cycle
#### 4.2.4.1. Domain Layer

**Aggregates:**
* **IrrigationCycleAggregate**: Raíz que gestiona la ejecución de un riego individual, asegurando que se cumplan los tiempos y volúmenes calculados.
* **IrrigationSchedule**: Agregado que mantiene la planificación de riegos automáticos para una zona específica.

**Entities:**
* **IrrigationLog**: Registro detallado de una sesión de riego finalizada (agua consumida, duración real).

**Value Objects:**
* **WaterQuantity**: Representa el volumen de agua (litros o milímetros) con su respectiva unidad.
* **IrrigationStatus**: Estado del ciclo (Programado, En Proceso, Completado, Abortado).

**Domain Services:**
* **IrrigationCalculator**: Servicio que calcula la necesidad hídrica comparando la humedad actual (de Telemetry) con el umbral óptimo (de Cultivation Area).

**Interfaces (Repositories):**
* **IIrrigationRepository**: Contrato para persistir ciclos y planes de riego.

#### 4.2.4.2. Interface Layer

**Controllers:**
* **IrrigationController**: Endpoints para iniciar riegos manuales, detener ciclos en curso y configurar calendarios.

**Consumers:**
* **ThresholdAlertConsumer**: Escucha eventos de "Umbral Crítico" provenientes del contexto de Telemetry para activar riegos de emergencia.
* **TelemetryDataConsumer**: Recibe actualizaciones constantes de humedad para que el servicio de riego pueda decidir si adelanta un ciclo programado.

#### 4.2.4.3. Application Layer

**Command Handlers:**
* **StartIrrigationHandler**: Orquesta el inicio de un riego: verifica el estado del hardware, valida la disponibilidad de agua y emite la orden de apertura.
* **AbortIrrigationHandler**: Detiene inmediatamente cualquier ciclo activo ante una emergencia o comando del usuario.

**Event Handlers:**
* **SoilMoistureOptimizedEventHandler**: Reacciona cuando los niveles de humedad llegan al punto ideal para cerrar las válvulas.
* **IrrigationCompletedEventHandler**: Registra el consumo final de agua y actualiza las estadísticas de eficiencia del usuario.

#### 4.2.4.4. Infrastructure Layer

**Repositories Implementation:**
* **PostgresIrrigationRepository**: Implementación sobre la base de datos relacional para gestionar las tablas de irrigation_cycle y schedule.

**Message Brokers:**
* **HardwareCommandPublisher**: Implementación que envía el comando OpenValve o CloseValve directamente al Bounded Context de Hardware Device.

**External Service Adapters:**
* **WeatherForecastAdapter**: Consulta servicios meteorológicos externos para posponer riegos si existe una alta probabilidad de lluvia inminente.

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Irrigation Service detalla la orquestación del riego inteligente, donde el Irrigation Controller y el Threshold Alert Consumer actúan como los disparadores de procesos manuales y reactivos, respectivamente. La inteligencia del sistema reside en el Irrigation Calculator, un servicio de dominio que evalúa la humedad reportada por el contexto de Telemetry frente a los límites definidos por el Cultivation Service, permitiendo que el Start Irrigation Handler tome decisiones informadas sobre la activación de válvulas. El flujo se completa mediante el Hardware Command Publisher, que traduce las decisiones de negocio en comandos ejecutables para el hardware, mientras que el Schedule Manager garantiza la autonomía del sistema al gestionar calendarios de riego persistidos en la Core DB, optimizando el recurso hídrico incluso ante condiciones externas desfavorables consultadas vía el Weather Forecast Adapter.

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases de la capa de dominio de Irrigation Cycle establece a IrrigationCycle como el Agregado Raíz encargado de gestionar el ciclo de vida de un evento de riego, desde su inicio hasta su culminación o aborto, manteniendo la integridad del volumen de agua consumido mediante el objeto de valor WaterQuantity. La planificación se desacopla a través del agregado IrrigationSchedule, que permite definir frecuencias y duraciones personalizadas para cada zona de cultivo. El motor inteligente del contexto reside en el IrrigationCalculator, un servicio de dominio que evalúa si un riego debe ejecutarse o posponerse comparando la telemetría actual con los umbrales biológicos, mientras que las interfaces de repositorio aseguran que tanto el historial de ejecuciones (registrado en IrrigationLog) como los calendarios activos se persistan correctamente en la infraestructura de datos de Grotix.

##### 4.2.4.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Irrigation Cycle ha sido desarrollado para soportar la ejecución y auditoría de los ciclos hídricos, centrado su arquitectura en la gestión del IrrigationCycleAggregate. La estructura se fundamenta en la capacidad de transformar decisiones lógicas en comandos físicos y registrarlos con precisión. La tabla action_queue funciona como el eje de ejecución inmediata, actuando como una persistencia de estado para el comando actual (abrir o cerrar válvula) y permitiendo que el sistema mantenga la consistencia de la orden incluso ante interrupciones en la comunicación con el hardware. Esta tabla asegura que el StartIrrigationHandler pueda emitir órdenes que queden registradas bajo un estado específico hasta que el dispositivo físico confirme su recepción y ejecución.

Para cumplir con los requerimientos de la capa de dominio respecto a la trazabilidad y el consumo de recursos, el diseño utiliza la tabla actuator_log como el repositorio definitivo de los IrrigationLog. Esta tabla persiste el historial detallado de cada sesión de riego finalizada, almacenando datos críticos como la Duration y el Timestamp de ejecución. Esta información es vital para que el IrrigationCalculator realice análisis de eficiencia hídrica en ciclos posteriores, permitiendo comparar el agua proyectada por el objeto de valor WaterQuantity frente a lo realmente ejecutado en el campo. Al estar vinculada directamente al ActuatorID, la persistencia garantiza una auditoría completa por zona, facilitando que el agricultor visualice el uso del recurso hídrico de forma histórica y permitiendo que el sistema genere reportes de sostenibilidad basados en datos reales de operación.

### 4.2.5. Bounded Context: Crop Analysis (AI)

#### 4.2.5.1. Domain Layer
**Aggregates:**
* **AnalysisReport**: Raíz de agregado que consolida los hallazgos de un diagnóstico específico, incluyendo el estado de salud detectado y las sugerencias de acción.

**Entities:**
* **AgriculturalInsight**: Representa un descubrimiento específico o patrón detectado (ej. "Deficiencia de Nitrógeno detectada en zona A").

**Value Objects:**
* **HealthScore**: Un valor numérico o categórico (Óptimo, Alerta, Crítico) que representa el bienestar de la zona.
* **GrowthMetric**: Datos procesados que indican el progreso del cultivo comparado con el estándar biológico.

**Domain Services:**
* **DiagnosisEngine**: Servicio que aplica algoritmos de IA o lógica heurística para interpretar la telemetría y generar el reporte.

**Interfaces (Repositories):**
* **IAnalysisRepository**: Interfaz para persistir y recuperar el historial de análisis y reportes.

#### 4.2.5.2. Interface Layer
**Controllers:**
* **AnalysisController**: Expone endpoints para solicitar reportes históricos y consultar el estado de salud actual de una granja desde la App móvil.

**Consumers:**
* **TelemetryAggregatedConsumer**: Escucha eventos de datos ya procesados (promedios de humedad/luz) del Bounded Context de Telemetry para iniciar nuevos análisis.
* **CropThresholdConsumer**: Recibe actualizaciones de los límites biológicos desde el contexto de Cultivation Area.

#### 4.2.5.3. Application Layer
**Command Handlers:**
* **GenerateCropAnalysisHandler**: Orquesta el flujo de tomar datos de telemetría, invocar al motor de diagnóstico y crear un nuevo reporte de salud.

**Event Handlers:**
* **PlantStressDetectedHandler**: Reacciona cuando el diagnóstico arroja resultados críticos, activando flujos de notificación inmediata.
* **AnalysisFinalizedHandler**: Coordina la actualización de dashboards una vez que el reporte ha sido generado con éxito.

#### 4.2.5.4. Infrastructure Layer
**Repositories Implementation:**
* **PostgresAnalysisRepository**: Implementación técnica que utiliza Spring Data JPA o Entity Framework para almacenar los reportes en la Core DB.
**External Service Adapters:**
* **MLModelAdapter**: Clase que se comunica con un microservicio externo de Python/TensorFlow para realizar predicciones de crecimiento o detección de enfermedades por imagen.

**Messaging Systems:**
* **NotificationEventPublisher**: Implementación que envía eventos a un Message Broker para que el sistema de notificaciones avise al agricultor sobre nuevos hallazgos.

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Crop Analysis Service ilustra su rol como el cerebro analítico del ecosistema Grotix, donde el proceso puede ser desencadenado manualmente vía el Analysis Controller o de forma automática cuando el Telemetry Aggregated Consumer recibe nuevos lotes de datos ambientales. La orquestación recae sobre el Generate Crop Analysis Handler, el cual delega la validación de reglas agrónomas al Diagnosis Engine; este servicio de dominio cruza los umbrales biológicos y se apoya en el ML Model Adapter para solicitar inferencias complejas (como predicción de estrés hídrico o enfermedades) a un microservicio externo de IA. Una vez que el diagnóstico está completo, el resultado se encapsula en el Analysis Report Aggregate para su almacenamiento en la Core DB, y, en caso de detectar métricas críticas, se invoca asíncronamente al Plant Stress Detected Handler para emitir alertas inmediatas al agricultor mediante el Notification Event Publisher. 

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases de la capa de dominio estructura el núcleo analítico de Grotix, estableciendo a AnalysisReport como el Agregado Raíz responsable de unificar los hallazgos de un ciclo de evaluación para una zona de cultivo específica. Este agregado mantiene la integridad de los resultados utilizando objetos de valor inmutables como HealthScore (que determina el estado general mediante el enumerador HealthStatus) y GrowthMetric (que compara el rendimiento real contra el esperado), mientras que las anomalías específicas se modelan mediante entidades AgriculturalInsight para permitir un seguimiento individualizado de alertas agronómicas. La complejidad heurística y predictiva reside en el servicio de dominio DiagnosisEngine, encargado de procesar la telemetría cruda y los umbrales biológicos para instanciar reportes coherentes, los cuales son finalmente abstraídos para su persistencia a través del contrato definido en IAnalysisRepository.

##### 4.2.5.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Crop Analysis ha sido estructurado para transformar la telemetría cruda en información accionable, centrando su arquitectura en la persistencia del AnalysisReportAggregate. A diferencia de los registros técnicos de sensores, este esquema prioriza el almacenamiento de diagnósticos e interpretaciones biológicas. La tabla system_alert funciona como el repositorio principal de este contexto, donde se persisten los resultados del DiagnosisEngine bajo una estructura de severidad y mensajes detallados. Esta tabla no solo registra un evento, sino que encapsula el HealthScore resultante de los modelos de inteligencia artificial, permitiendo que el GenerateCropAnalysisHandler guarde una traza histórica del bienestar de la zona de cultivo para su posterior consulta en el dashboard móvil.

Para garantizar que cada reporte tenga el contexto adecuado, la persistencia se apoya en una relación directa con las tablas microcontroller y zone, vinculando cada hallazgo del AgriculturalInsight con una ubicación física y un tipo de cultivo específico. Esto permite que el sistema no solo informe "qué" está ocurriendo, sino "dónde" y "bajo qué parámetros" se detectó la anomalía, utilizando los datos de la tabla crop como referencia para validar si el estado actual se desvía del estándar biológico esperado. Este diseño permite que el IAnalysisRepository recupere series de tiempo de diagnósticos pasados, facilitando al agricultor la identificación de patrones recurrentes de estrés vegetal y asegurando que las sugerencias de acción sugeridas por el MLModelAdapter queden debidamente registradas para auditorías de rendimiento agrícola y mejora continua del cultivo.


### 4.2.6 Bounded Context: Telemetry

#### 4.2.6.1. Domain Layer

**Aggregates:**
* **TelemetryReading**: Raíz de agregado que representa una captura única de datos (humedad, temperatura, etc.) en un momento específico, asegurando que la lectura sea coherente.

**Entities:**
* **SensorSource**: Representa el origen físico de la telemetría, vinculado a un identificador único del hardware.

**Value Objects:**
* **MeasurementValue**: Encapsula el valor numérico y su unidad de medida (e.g., Celsius, %).
* **CaptureTimestamp**: Garantiza la precisión temporal de la lectura, esencial para el análisis de series de tiempo.

**Domain Services:**
* **ThresholdValidator**: Servicio encargado de evaluar si una lectura entrante supera los límites de seguridad definidos (e.g., temperatura crítica), disparando alertas inmediatas.

**Interfaces (Repositories):**
* **ITelemetryRepository**: Contrato para la persistencia de datos históricos y consultas de series temporales.

#### 4.2.6.2. Interface Layer

**Controllers:**
* **TelemetryQueryController**: Provee endpoints para que la aplicación móvil consulte el estado actual de los sensores y gráficos históricos.

**Consumers:**
* **IoTDataConsumer**: Escucha los mensajes crudos provenientes del broker (MQTT/RabbitMQ) enviados por los dispositivos físicos, actuando como el principal punto de entrada de datos.

#### 4.2.6.3. Application Layer

**Command Handlers:**
* **RegisterMeasurementHandler**: Orquesta el proceso de recibir una lectura, validarla mediante el dominio, persistirla y determinar si debe notificar a otros contextos.

**Event Handlers:**
* **CriticalThresholdReachedHandler**: Reacciona cuando se detecta un valor fuera de rango, coordinando el envío de eventos hacia los contextos de Irrigation Cycle o Notification.

**Capabilities:** Incluye capacidades de filtrado de ruido en datos y agregación de métricas por periodos de tiempo.

#### 4.2.6.4. Infrastructure Layer

**Repositories Implementation:**
* **TimeSeriesTelemetryRepository**: Implementación optimizada para bases de datos de series de tiempo (como InfluxDB o tablas particionadas en PostgreSQL) para manejar grandes volúmenes de lecturas.

**Messaging Systems:**
* **TelemetryEventPublisher**: Implementación encargada de publicar eventos de integración (e.g., SoilMoistureUpdated) en el Message Broker para que contextos como Crop Analysis puedan reaccionar.

**External Adapters:**
* **HardwareBridgeAdapter**: Clase que traduce los protocolos específicos del hardware (JSON/Protobuf) al modelo de dominio de telemetría.

#### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams

[foto]

El diagrama de componentes del Telemetry Service modela el flujo de ingesta y análisis de datos de sensores en tiempo real. El punto de entrada principal no es el API Gateway sino el Telemetry Consumer, que recibe el evento TelemetryReceived publicado por el Edge App a través del Message Broker — reflejando la naturaleza asíncrona e IoT del sistema. Este consumer delega al Ingest Command Service, que orquesta la pipeline de procesamiento: primero el Anomaly Detector descarta lecturas físicamente imposibles, luego el Moving Average Filter suaviza la señal para eliminar ruido eléctrico, y finalmente la lectura validada se persiste en TimescaleDB a través del Telemetry Repository. Paralelamente, el Alert Evaluation Service consulta los umbrales biológicos del cultivo asignado a la zona mediante el Zone Threshold Repository y, si una condición crítica persiste durante 4 o más ciclos consecutivos, el Alert Publisher dispara el evento AlertTriggered al broker para que el Irrigation Service y el Servicio de Notificaciones reaccionen de forma autónoma. El Telemetry Controller expone endpoints REST para que la aplicación móvil consulte el historial y estado actual de los sensores por zona. 

#### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams

[foto]

El diagrama de clases del bounded context de Telemetry presenta el modelo de dominio orientado a la captura y evaluación de datos de sensores. El agregado raíz SensorReading encapsula una lectura completa de una zona en un instante dado, componiendo el value object ReadingValue que agrupa los tres valores medibles — humedad, temperatura e intensidad lumínica — y expone el método IsPhysicallyValid para detectar datos fuera de rango antes de persistirlos. La entidad ZoneThreshold modela los límites operativos configurados para cada zona según el cultivo asignado, con métodos de validación por variable que son consumidos por el domain service ThresholdEvaluator. Cuando se detecta una condición anómala, se genera una entidad AlertEvent clasificada mediante el enum AlertType, que cubre todas las variables monitoreadas en ambas direcciones. Los domain services AnomalyDetector y MovingAverageFilter encapsulan la lógica de limpieza de señal de forma pura y sin dependencias de infraestructura. Las interfaces ISensorReadingRepository, IZoneThresholdRepository e IAlertEventRepository desacoplan el dominio de la persistencia, con métodos especializados como GetLastNReadingsAsync y CountRecentByZoneAndTypeAsync que soportan la lógica de detección de condiciones persistentes.


##### 4.2.6.6.2. Bounded Context Database Design Diagram

[foto]

El diseño de persistencia para el Bounded Context de Telemetry ha sido optimizado para el manejo de flujos masivos de datos y la integridad de series temporales, centrando su arquitectura en el ciclo de vida del TelemetryReadingAggregate. La estructura se divide en dos capas de persistencia que garantizan la disponibilidad del sistema bajo cualquier condición de red. En la capa de borde, la tabla pending_telemetry actúa como una cola de persistencia efímera que asegura que ninguna lectura capturada por el IoTDataConsumer se pierda ante fallos de conectividad, permitiendo que el objeto de valor CaptureTimestamp mantenga la precisión cronológica del dato original antes de su sincronización definitiva con la nube.

Una vez que los datos son procesados por el RegisterMeasurementHandler, la persistencia definitiva se realiza en la tabla sensor_reading dentro de la base de datos maestra. Esta tabla ha sido diseñada siguiendo principios de bases de datos de series de tiempo, utilizando tipos de datos de alta capacidad como BigInt para el ReadingID y Float para el MeasurementValue, lo que permite almacenar millones de registros sin degradación del rendimiento. La vinculación con la entidad SensorSource se resuelve mediante una clave foránea hacia el SensorID, permitiendo que el TimeSeriesTelemetryRepository realice agregaciones y consultas históricas eficientes por zona o tipo de sensor. Además, el servicio de dominio ThresholdValidator utiliza esta estructura de persistencia para comparar en tiempo real la lectura entrante con los registros históricos, asegurando que solo los datos validados y consistentes alimenten los gráficos y motores de análisis del agricultor.

# CAPÍTULO V: Solution UI/UX Design

## 5.1. Style Guidelines
Para asegurar la integridad visual y funcional del ecosistema Grotix, se define este marco de Style Guidelines como el eje central de diseño y estandarización para el equipo de desarrollo. Esta sección establece las normas fundamentales para el uso de activos, tipografías y elementos gráficos, garantizando una transición fluida y profesional entre la landing page, la aplicación móvil y las interfaces de gestión IoT. Al centralizar estas directrices, no solo se refuerza la identidad de marca orientada a la innovación agrícola y tecnológica, sino que se optimiza la eficiencia operativa del equipo al proporcionar un lenguaje visual común que responde estrictamente a los criterios de usabilidad, accesibilidad y consistencia multiplataforma definidos en los requerimientos del sistema.

### 5.1.1. General Style Guidelines
Las General Style Guidelines de Grotix se fundamentan en la creación de una identidad visual que equilibre la innovación tecnológica con la confiabilidad agrícola. Basándonos en principios de diseño centrados en el usuario, hemos seleccionado una paleta de colores y una jerarquía tipográfica que garantizan la legibilidad y accesibilidad (WCAG), facilitando la interacción de los agricultores con datos complejos de telemetría e IA. En cuanto al tono de comunicación, Grotix adopta una dimensión entusiasta, respetuosa y profesional, eliminando tecnicismos innecesarios para asegurar que el lenguaje sea sereno y comprensible, transformando así la experiencia técnica en una herramienta de gestión cotidiana cercana y efectiva.

#### Branding y Logo

<img src="https://imgur.com/mBeabdf.png>

El branding de Grotix se ha diseñado para proyectar una identidad que fusiona la naturaleza con la precisión tecnológica. El logotipo utiliza una tipografía moderna y de alta legibilidad, donde el isotipo destaca por la integración de hojas verdes que simbolizan la vida y el crecimiento agrícola. La incorporación de un elemento circular y una letra "i" en tonos celestes refuerza el concepto de inteligencia y fluidez hídrica, comunicando visualmente que Grotix no es solo una herramienta de monitoreo, sino una solución inteligente enfocada en la sostenibilidad y el éxito de la germinación. Esta composición visual garantiza que la marca sea fácilmente reconocible tanto en interfaces digitales como en dispositivos físicos, manteniendo una estética profesional y vanguardista.

#### Paleta de Colores (Colors)

<img src="https://imgur.com/e5Q3Lve.png>

La paleta de colores de Grotix ha sido seleccionada estratégicamente para evocar un equilibrio entre la vitalidad del campo y la innovación digital. Los tonos principales, como el Verde Pasto (#4FD16C) y el Azul Cerúleo (#40BFE2), refuerzan la conexión con la agricultura y la gestión inteligente de recursos hídricos, mientras que el Rojo Coral (#FF5757) actúa como un color de acento crítico para alertas y notificaciones prioritarias. Esta gama se complementa con una paleta secundaria que incluye el Verde Esmeralda (#01A070) para dar profundidad visual, y tonos neutros como el Gris Claro (#DDDDDD), Negro (#000000) y Blanco (#FFFFFF), que aseguran un alto contraste y una interfaz limpia, facilitando la legibilidad de datos técnicos en diversas condiciones de iluminación ambiental.

#### Tipografía (Typography)

<img src="https://imgur.com/dIMdRhK.png">

La elección tipográfica para Grotix se centra en la familia Gabarito, una fuente de estilo geométrico y moderno que refuerza la identidad tecnológica del proyecto. Se han definido cuatro variantes principales (Regular, Semibold, Bold y Extrabold) para establecer una jerarquía visual clara y estructurada en todas las interfaces. Mientras que las variantes Bold y Extrabold se reservan para títulos e indicadores de datos críticos, permitiendo una rápida lectura en entornos de campo, las versiones Regular y Semibold garantizan una legibilidad óptima para textos descriptivos y navegación. Esta versatilidad asegura una presentación consistente, facilitando que el usuario identifique de manera intuitiva los diferentes niveles de información dentro de la plataforma.

#### Iconografía (Iconography)

La iconografía de Grotix ha sido seleccionada para ser intuitiva y funcional, permitiendo que el agricultor interprete el estado de su cultivo de un vistazo sin necesidad de leer textos extensos.

* **Estilo:** Se utilizan iconos de estilo lineal (outline) con terminaciones redondeadas para mantener una estética moderna, limpia y profesional.

* **Tamaño Estándar:** Se establece un formato base de 24px para garantizar la nitidez en pantallas de dispositivos móviles y paneles de control industriales.

* **Propósito:** El set incluye iconos especializados en IoT y agricultura (gotas de agua para riego, sol para radiación UV, termómetros para clima y brotes para etapas de germinación), además de iconos de gestión (alertas críticas, configuraciones y reportes), asegurando que cada interacción técnica tenga un soporte visual claro.

#### Espaciado (Spacing)

La organización visual de Grotix se basa en un sistema de rejilla modular que garantiza que la densidad de información (gráficos de telemetría y alertas) no abrume al usuario.

* **Sistema de 8 Puntos:** Se adopta una escala basada en múltiplos de 8px (8, 16, 24, 32, 40, etc.) para definir márgenes, paddings y la separación entre tarjetas de datos. Este estándar asegura que los elementos se alineen de forma armónica en cualquier resolución de pantalla.

* **Agrupación y Claridad:** El espaciado se utiliza estratégicamente para separar las zonas de monitoreo de las de control (actuadores), evitando activaciones accidentales del riego manual y mejorando la legibilidad de las métricas históricas.

#### Tono de Comunicación y Lenguaje Aplicado

El Tono de Comunicación de Grotix es Profesional, Confiable y Sereno, diseñado para transmitir la precisión de una herramienta tecnológica avanzada mientras se mantiene una conexión cercana con la labor del campo.

* **Personalidad:** Se define como un acompañante técnico experto que es Entusiasta respecto al éxito de la cosecha, pero Sereno al reportar alertas, evitando generar pánico innecesario en el usuario.

* **Lenguaje Aplicado:** Se prioriza la Simplicidad Técnica; aunque el sistema maneja conceptos complejos de IA y telemetría, el lenguaje hacia el usuario evita tecnicismos de programación, optando por términos agrícolas directos y de fácil comprensión para usuarios de diversos niveles de experiencia tecnológica. El estilo es Formal pero Accesible, asegurando una experiencia de uso auténtica que refuerza la confianza en la autonomía del sistema.

### 5.1.2. Web, Mobile and IoT Style Guide

1. **Estándares Visuales y de Interacción para Responsive Web Interfaces**

El diseño web (Landing Page y Staff Web App) se centra en la conversión, accesibilidad y eficiencia administrativa:

* **Identidad y Accesibilidad:** La interfaz debe aplicar una jerarquía de colores con contrastes que cumplan estrictamente los estándares de accesibilidad WCAG.
* **Tipografía y Legibilidad:** Se aplicará una escala tipográfica estandarizada y clara que facilite la lectura rápida, evitando tecnicismos excesivos.
* **Navegación e Interacción:** El menú de navegación debe ser persistente (sticky header) e incluir resaltado visual de la sección activa. En pantallas menores al "breakpoint" definido, el menú colapsará en un ícono de hamburguesa legible. Las transiciones entre secciones en una misma página deben usar desplazamiento suave (smooth scrolling).
* **Manejo de Estados y Errores:** Se implementará la carga diferida (lazy loading) para imágenes inferiores. En los formularios, los errores por campos vacíos o inválidos se resaltarán en tiempo real con mensajes de ayuda descriptivos.

<img src="https://imgur.com/FZYMgOV.png">

2. **Estándares para Mobile Application Interfaces**

La aplicación móvil prioriza un bajo esfuerzo cognitivo y la tolerancia a contextos de campo (mala conectividad, uso con una sola mano):

* **Navegación Intuitiva:** Se utilizará un menú de navegación claro con iconos representativos y etiquetas directas para asegurar una curva de aprendizaje mínima.
* **Interacción Táctil (Touch-Optimized):** Se implementarán gestos nativos como "Pull-to-refresh" (arrastrar hacia abajo) para sincronización manual de datos y "Swipe" (deslizar) para acciones rápidas como reactivar servicios. Los ajustes de umbrales se realizarán mediante controles deslizantes (sliders) táctiles.
* **Jerarquía Visual y Alertas:** La vista principal utilizará tarjetas de resumen apilables verticalmente (scroll). Ante anomalías o estados críticos (ej. contratos vencidos o humedad baja), las tarjetas e indicadores cambiarán de color (rojo) para resaltar la alerta.
* **Tolerancia a Fallos de Red y Carga:** Se mostrarán estados de carga visuales (spinners) para evitar la sensación de congelamiento de la app. Si se pierde la conexión, la interfaz mostrará datos cacheados localmente acompañados de un indicador visual de "Sin conexión".
* **Prevención de Errores:** La captura de datos complejos usará formularios divididos en pasos (stepper). Acciones destructivas (como desactivar un cliente) requerirán una doble confirmación mediante ventanas modales.

<img src="https://imgur.com/uk01NQF.png">

3. **Estándares de Interacción con la Interfaz Física (IoT)**

La interacción del usuario a través de la interfaz digital debe reflejar con fidelidad el estado del hardware físico en el campo:

* **Correspondencia Físico-Digital:** Cualquier cambio en el entorno o fallo del sensor debe reflejarse inmediatamente en la interfaz, mostrando avisos explícitos como "Sensor no disponible". Además, se debe mostrar un indicador de "Última sincronización" con fecha y hora exacta para garantizar la vigencia del dato.
* **Feedback de Actuación Manual:** Cuando el usuario acciona manualmente un actuador (ej. válvula de riego), el sistema debe confirmar la acción visualmente. Si el comando falla, la interfaz debe explicar el motivo (ej. "Sensor desconectado").
* **Control y Aborto de Emergencia:** La interfaz debe proveer un mecanismo visible e inmediato para cancelar un ciclo de riego en curso, otorgando prioridad al mando manual sobre las reglas autónomas de la IA.

<img src="https://imgur.com/FO2aJui.png">

## 5.2. Information Architecture

La arquitectura de información es fundamental para plantear la manera en que se organizarán los diferentes componentes de Grotix, de modo que el usuario pueda interactuar y adaptarse a ellos de manera intuitiva. La buena organización de la información se debe priorizar para retener la atención del usuario e incentivar el uso constante de la aplicación.

### 5.2.1. Organization System
Los diagramas presentados a continuación están organizados de manera jerárquica y en categorías para ilustrar las relaciones entre los componentes de manera visual. Estos sistemas de organización de información contribuyen a una navegación más intuitiva para los usuarios, lo que mejorará su experiencia de uso.

#### Landing Page

<img src="https://imgur.com/85Kn2Fx.png">

#### Web App Page (For Staff)

<img src="https://imgur.com/KDxyzhu.png">

#### Mobile App (For Clients)

<img src="https://imgur.com/U5CvC67.png">

### 5.2.2. Labeling Systems

La interfaz de Livria ha sido diseñada de manera eficiente y organizada, ofreciéndole al cliente una experiencia de uso dinámica que le permitirá encontrar una ruta rápida hacia la información que quiere consultar o las herramientas que quiere utilizar sin complicaciones. Para lograr esto, nuestro equipo ha propuesto un diseño que emplea etiquetas concisas y efectivas, favoreciendo una experiencia intuitiva. A continuación, se dará una descripción detallada de aquellas que se encuentran en nuestro proyecto.

#### Landing Page

<img src="https://imgur.com/ARaiiQR.png">

Al ingresar a la plataforma, el usuario se encontrará primero con el encabezado (Header). En esta sección, se presentan las etiquetas diseñadas para facilitar una navegación intuitiva y un acceso rápido a la propuesta de valor de Grotix:

* **GENERAL:** Esta etiqueta permite al usuario regresar al inicio de la Landing Page desde cualquier sección, ofreciendo una visión global de la plataforma y su propósito principal.
* **SERVICES:** Provee un acceso directo a la descripción detallada de los servicios tecnológicos de Grotix, como el monitoreo de cultivos, automatización de riego y análisis de datos.
* **APP:** Esta etiqueta redirige al usuario a la sección informativa sobre la aplicación móvil, destacando sus funcionalidades de control remoto y visualización de telemetría en tiempo real.
* **US:** Esta ruta lleva a la sección "Nosotros", donde se presenta la visión de la startup, el equipo detrás del proyecto y el compromiso con la innovación en la agricultura.
* **CONTACT:** Tiene la función de acceso directo al área de contacto, facilitando un formulario para consultas comerciales, soporte técnico o alianzas estratégicas.
* **SOCIAL:** Esta etiqueta agrupa los enlaces a las redes sociales oficiales, permitiendo al usuario interactuar con la marca fuera de la plataforma web.
* **GET NOW!:** Es la etiqueta de llamada a la acción (CTA) principal. Resaltada visualmente, dirige al usuario al proceso de adquisición, registro o contratación de los servicios de Grotix.
* **EN/ES:** Esta etiqueta permite alternar el idioma del sitio web entre inglés (EN) y español (ES), adaptando el contenido a las preferencias lingüísticas del usuario global o local.

#### Web App (For Staff)

<img src="https://imgur.com/Z7TeSEa.png">

La Web App para el staff administrativo utiliza una barra de navegación lateral (Sidebar) con iconos intuitivos. Cada etiqueta ha sido seleccionada para representar con precisión el módulo de gestión correspondiente, asegurando que el personal operativo pueda identificar y acceder a las métricas y registros de manera inmediata:

* **HOME:** Esta etiqueta dirige al Dashboard Principal, donde el staff visualiza una vista previa del estado general del sistema, incluyendo indicadores clave sobre clientes activos, contratos vigentes y el estado de salud de los dispositivos desplegados.
* **SEARCH:** Provee una herramienta de filtrado y búsqueda global. Permite al administrador localizar rápidamente expedientes específicos de agricultores, números de serie de dispositivos o contratos mediante términos de búsqueda clave.
* **AGRICULTURISTS:** Da acceso al módulo de Gestión de Clientes. Aquí se administra el directorio completo de los agricultores registrados en la plataforma, permitiendo la edición de perfiles, revisión de datos de contacto y estatus de cuenta.
* **CONTRACTS:** Representa el repositorio de Gestión de Contratos. En esta sección, el staff puede revisar los términos de servicio, fechas de vencimiento y el historial de facturación vinculado a cada agricultor y dispositivo.
* **DEVICES:** Esta ruta lleva al inventario técnico de Hardware e IoT. Permite monitorear el estado de conectividad, batería y telemetría de cada sensor y actuador instalado en el campo, facilitando el mantenimiento preventivo.
* **CROPS:** Esta etiqueta permite acceder al catálogo de Tipos de Cultivos. Es el área donde se configuran los parámetros óptimos de humedad, temperatura y nutrientes para cada especie vegetal soportada por la IA de Grotix.
* **SETTINGS:** Representa el acceso a la Configuración y Perfil. En esta sección, el personal de staff puede gestionar sus credenciales de acceso, preferencias de la interfaz y ajustes de seguridad de la cuenta administrativa.

#### Mobile App (For Clients)

<img src="https://imgur.com/xr2b4vt.png">

La aplicación móvil utiliza un menú de navegación inferior (Bottom Navigation Bar) con iconos de alto contraste y etiquetas directas. Este sistema permite al agricultor desplazarse entre el monitoreo en tiempo real, el análisis predictivo de la IA y la gestión administrativa con un solo toque:

<img src="https://imgur.com/3jmdhqT.png">

* **DASHBOARD:** Representada por el icono de gráfica, esta etiqueta dirige a la pantalla principal de monitoreo. Aquí el usuario visualiza los niveles críticos (humedad, temperatura, luz) de la zona de cultivo seleccionada y el listado de participantes o colaboradores con acceso a dicha zona.
* **AI ADVISOR:** Identificada con el icono de destello (star), esta sección centraliza las capacidades de inteligencia artificial de Grotix. El usuario puede consultar el estado de germinación detallado por zona y recibir recomendaciones predictivas basadas en la telemetría recolectada.
* **ZONES:** Es el botón central y destacado de la interfaz (icono de brote). Esta etiqueta da acceso al listado completo de las parcelas o sectores de cultivo registrados. Permite al usuario conmutar rápidamente entre diferentes áreas geográficas para actualizar los datos del Dashboard.
* **REPORTS:** Esta etiqueta, asociada al icono de documento, permite acceder al historial de datos y reportes de rendimiento. Aquí el agricultor puede revisar eventos pasados, ciclos de riego completados y descargar resúmenes de actividad para la toma de decisiones estratégicas.
* **PROFILE:** Representada por el icono de usuario, esta etiqueta dirige a la gestión de la cuenta personal. Incluye la configuración de notificaciones de alerta, datos de contacto del suscriptor y opciones de seguridad de la aplicación.
* **NOTIFICACIONES:** Muestra las notificaciones importantes del usuario, así como su configuración. Puede elegir de qué tipo y categoría recibe.

### 5.2.3. SEO Tags and Meta Tags

#### Landing Page

**Title**

[foto]

En este meta tag, se define el título que tendrá el sitio web del proyecto. El equipo decidió usar el nombre de la startup seguido del nombre del producto para resaltar nuestra autoría sobre la idea, optando por una mayor simplicidad que facilite la lectura por parte del usuario.

**Meta Tags**

[foto]

Para garantizar que la Landing Page de Grotix sea indexada correctamente y presente una identidad visual coherente al ser compartida en plataformas digitales, se ha implementado un sistema de Meta Tags técnicos y descriptivos.

* **charset="UTF-8"**: Define la codificación de caracteres universal. Es vital para que el navegador renderice correctamente tildes, eñes y símbolos especiales sin errores visuales.
* **viewport**: Es la etiqueta base para el diseño responsivo. Ajusta el ancho de la página al tamaño de la pantalla del dispositivo y establece la escala inicial en 1.0, evitando que el sitio se vea "miniatura" en móviles.
* **description**: Es el resumen que aparece bajo el título en los resultados de búsqueda de Google. Su función es puramente de marketing y conversión (CTR), resumiendo el valor de Grotix en una frase impactante.
* **keywords**: Lista de términos clave que ayudan a los motores de búsqueda a categorizar el sitio. Incluye los pilares del proyecto: Machine Learning, Sensors e Irrigation.
* **author**: Establece la autoría intelectual del código y el diseño, vinculando el proyecto directamente con su creador, Celevi.
* **og:site_name**: Define el nombre oficial de la plataforma (Grotix) para que los sistemas de redes sociales reconozcan la marca detrás del enlace.
* **og:title**: Es el título principal que aparecerá en negrita cuando compartas el link por WhatsApp, LinkedIn o Facebook. En este caso, posiciona la identidad de Celevi - Grotix.
* **og:description**: Cumple la misma función que la descripción SEO, pero optimizada específicamente para la vista previa de las "cards" en redes sociales.
* **og:type**: Indica a los algoritmos que el contenido es un sitio web estático (website), lo que ayuda a las plataformas a decidir qué tipo de visualización darle al enlace.

#### Web App (For Staff)

[foto]

Para la aplicación web de Grotix, se ha configurado el archivo principal (index.html) con un conjunto de etiquetas (tags) y metaetiquetas (meta tags) estructurales y de SEO. Esta configuración base tiene el doble propósito de asegurar una correcta visualización en diversos dispositivos móviles, y de establecer la identidad fundamental del portal. Además, considerando que el Dashboard gestiona datos sensibles de los agricultores y telemetría de los cultivos, se ha implementado una directiva de privacidad por defecto en los motores de búsqueda, asegurando que la información interna no quede expuesta públicamente. 

* **Viewport (<meta name="viewport">)**: Configurado con los valores width=device-width, initial-scale=1.0 para garantizar que la interfaz de usuario se escale y adapte correctamente a cualquier tamaño de pantalla, cumpliendo con los estándares de diseño responsivo.
* **Title (<title>)**: Se ha definido el valor "Grotix Portal - Farm Management Dashboard" para mostrar claramente el propósito de la plataforma en las pestañas del navegador y proveer un título por defecto antes de que el enrutador dinámico (Vue Router) actúe.
* **Description (<meta name="description">)**: Incluye un resumen descriptivo en inglés de las capacidades del sistema ("Access the Grotix management portal to monitor telemetry, control hardware, and review crop health reports"), lo cual mejora la presentación del enlace si se comparte en plataformas de mensajería o redes corporativas.
* **Keywords (<meta name="keywords">)**: Establece términos clave como "Grotix login" y "agricultural telemetry portal" para definir semánticamente el nicho de la aplicación.
* **Author (<meta name="author">)**: Identifica a "Celevi" como el autor o entidad responsable del desarrollo de este producto digital.
* **Robots (<meta name="robots">)**: Configurado como "noindex, nofollow". Esta es una medida de seguridad preventiva vital para un entorno administrativo, ya que instruye a los rastreadores web (como el bot de Google) a no indexar la página de entrada en sus resultados de búsqueda y a no seguir sus enlaces internos, protegiendo así las rutas privadas.

#### Mobile App (For Clients)

[foto]

**ASO (App Store Optimizaton) elements:**
La optimización para tiendas de aplicaciones (ASO) de la aplicación se centra en los siguientes elementos visibles:

* **Título de la Aplicación (App Title/Name):** Este está definido por el atributo android:label tanto en la etiqueta <application> como en la <activity> principal. Este es el nombre que los usuarios verán bajo el icono de la aplicación en la pantalla de inicio y en la tienda de aplicaciones.
* **Icono de la Aplicación (App Icon):** El atributo android:icon especifica el recurso @mipmap/ic_launcher y android:roundIcon especifica @mipmap/ic_launcher_round. Aunque no se muestra el diseño real, este es un elemento crucial de ASO ya que es la primera impresión visual de la aplicación.

### 5.2.4. Searching Systems
En Grotix, los Searching Systems fueron diseñados para simplificar la experiencia de búsqueda y mejorar la experiencia del usuario, ayudándolo a localizar la información que quiere consultar rápidamente y de manera eficiente. Esto nos ayudará a evitar que los clientes se sientan abrumados y ayudará al staff a supervisar correctamente el servicio que ofrecen.

#### Web App (For Staff)

[foto]

En primer lugar, está la pantalla de Búsqueda, que está diseñada para ofrecer una experiencia de descubrimiento de catálogo rápida y directa al usuario. Su diseño conciso se enfoca en la eficiencia y la relevancia de los resultados. Permite explorar entre agricultores, contratos y dispositivos.

[foto]

La pantalla de Contratos incluye un ícono de filtros (representado por barras verticales de diferentes alturas) en la esquina superior derecha. Esta funcionalidad es crucial, ya que permite al staff refinar los resultados obtenidos en la lista general de contratos, aplicando criterios adicionales.

[foto]

De manera similar, en la pantalla de Dispositivos aparece el mismo ícono que permite filtrar entre la lista general de los microcontroladores aplicando ciertos criterios.

[foto]

En la pantalla de Cultivos hay una barra de búsqueda que permite explorar entre el listado de cultivos mediante dos criterios: nombre común o el científico.

[foto]

#### Mobile App (For Clients)

[foto]

Los usuarios poseen una barra de búsqueda en cada zona (Dashboard de Cultivation Area) que creen y posean para la funcionalidad de buscar otros usuarios. Esta le permite encontrar agricultores dentro de su asociación e invitarlos a participar u observar en la zona específica, así como eliminarlos de la misma.

[foto]

En la pantalla de IA (Image Processing), el usuario puede buscar las zonas en específico que tiene para ver su estado. El sistema muestra un listado con las zonas y el estado de germinación que posee; con esta barra de búsqueda se le facilita el encuentro de algún área en particular.

[foto]

En la pantalla general de zonas (Cultivation Areas), el usuario tiene la opción de buscar entre aquellas ya existentes, así como crear una nueva o filtrarlas mediante criterios específicos. Esto le permite realizar su objetivo de manera eficiente.

### 5.2.5. Navigation Systems
El diseño de la navegación de Grotix se basa en una arquitectura de información clara, utilizando patrones probados para garantizar que tanto los agricultores como el personal administrativo puedan acceder a sus flujos de trabajo clave de manera eficiente. 

#### Web App (For Staff)

[foto]

En primer lugar, la barra lateral de navegación de la web app para el staff funciona como el eje central del sistema de navegación global, facilitando el acceso directo a los módulos críticos de Grotix.

Diseñada bajo un enfoque de navegación persistente, permite al usuario moverse de manera fluida entre el dashboard principal, el buscador, la gestión de clientes (agricultores), contratos y el monitoreo técnico de microcontroladores y zonas de cultivo. 

La jerarquía visual se apoya en una iconografía minimalista y escalable que optimiza el espacio de trabajo, asegurando que las herramientas de configuración y el acceso a la identidad de la marca permanezcan siempre al alcance del equipo operativo.

[foto]

Al momento de seleccionar un agricultor en específico en la pantalla de Agricultores (Agriculturists), la aplicación web dirige al miembro del staff a la pantalla de cliente en singular (Agriculturist). En caso de que desee regresar a ver la lista general de agricultores, puede hacerlo al hacer click en el ícono de flecha a la izquierda al costado del título (o a través del menú lateral).

[foto]

La pantalla de Cultivos (Crops) (y sus singulares) tienen la misma función de navegación que en Agricultores, permitiendo el regreso a la pantalla general de cultivos desde uno en singular.

#### Mobile App (For Clients)

[foto]

En la pantalla de una zona en específico (Dashboard de Cultivation Area) hay botones de navegación. En primer lugar está Main (Principal), que muestra los valores actuales de los criterios de la zona (humedad, luz, etc.) y la información general. En el medio se encuentra Settings (Configuración), que permite cambiar los valores de límite para cada criterio, así como el riego de la zona. Por último, está People (Personas), que permite buscar entre los agricultores de la asociación para que el administrador de la zona lo pueda agregar o eliminar.

[foto]

La parte más importante de la navegación en la aplicación móvil es la barra inferior de menú. Cuenta con 5 íconos, cada uno dando acceso a diferentes funcionalidades. El primero, el dashboard, muestra una zona en específico a elección. Le sigue la estrella de cuatro puntas que dirige a la pantalla de AI Image Processing. En el medio se encuentra la planta, que muestra el listado de zonas (Cultivation Areas). El ícono de papel lleva a la pantalla de Reportes, que le permite al usuario generar informes sobre sus zonas y cultivos. Por último, el ícono de persona es el acceso a la pantalla de perfil (Profile), en la cual se muestran los detalles de la cuenta del usuario.

[foto]

Por último, la barra superior de cada pantalla de la aplicación posee dos accesos directos. El logo de Grotix lleva a la pantalla de zonas, como un acceso directo a información general. Y el ícono de campanita abre un drawer o sidebar (pantalla modal) con las notificaciones que recibe el usuario y una opción para configurarlas.

## 5.3. Landing Page UI Design
La propuesta de diseño para la interfaz de usuario (UI) de la Landing Page de Grotix es la culminación visual de la arquitectura de información y el diseño centrado en el usuario. Desde el primer impacto, esta interfaz está diseñada para proyectar una identidad accesible, amigable y culturalmente cercana. La estructura se organiza en secciones clave que garantizan una navegación fluida e intuitiva. Estéticamente, el diseño emplea una jerarquía visual limpia, ilustraciones cálidas, tipografías legibles y un uso estratégico de la paleta de colores para despertar el interés, generar confianza e impulsar al visitante a interactuar con los llamados a la acción, asegurando que la primera impresión sea tanto funcional como emocionalmente atractiva.

### 5.3.1. Landing Page Wireframe
La sección de Landing Page Wireframes presenta la arquitectura visual y la disposición estratégica de los elementos diseñados para comunicar la propuesta de valor de Grotix de manera efectiva. A través de una narrativa digital estructurada en secciones como Hero, Services, App, y Us, estos mockups definen la jerarquía de información necesaria para guiar al usuario desde el descubrimiento de la solución de riego inteligente hasta la conversión directa. El diseño prioriza una experiencia de usuario (UX) intuitiva en modo oscuro, integrando componentes visuales modernos y puntos de contacto estratégicos que refuerzan la identidad de Celevi y su compromiso con la sostenibilidad agrícola.

A continuación, se muestra cada wireframe pensado para la Landing Page:

[foto]
[foto]
[foto]
[foto]
[foto]
[foto]

### 5.3.2. Landing Page Mock-up

[foto]

La sección General de la landing page de Grotix presenta una introducción impactante y profesional orientada a soluciones de agricultura de precisión. En el centro de una estética de modo oscuro, destaca el nombre de la plataforma acompañado de su propuesta de valor. Un botón destacado de "GET NOW!" invita a la conversión inmediata, mientras que en la base de la pantalla se despliega una galería visual que ilustra el uso de sensores en campo, monitoreo móvil y análisis de datos en tiempo real. En la parte superior, un menú de navegación claro permite acceder a las secciones de servicios, aplicación, nosotros, contacto y redes sociales, incluyendo además un selector de idioma para mayor accesibilidad.

[foto]

La sección de Services de la landing page de Grotix detalla las capacidades tecnológicas de la plataforma para la agricultura de precisión mediante un diseño de tarjetas moderno y visual. Muestra un total de 6 tarjetas mostrando las principales características de la aplicación, dando un pequeño resumen de cada una con una imagen representativa de la información brindada.

[foto]

La sección App de la landing page destaca la movilidad y el control total bajo el lema "Your crops in the palm of your hand". En esta parte, se muestra un mockup de la aplicación móvil de Grotix. La descripción enfatiza el uso de inteligencia artificial para transformar datos complejos de sensores en decisiones accionables y reportes detallados de ahorro de agua, facilitando el acceso a estos insights directamente desde el teléfono. Finalmente, se presentan los botones de descarga para las principales tiendas de aplicaciones, reforzando la accesibilidad de la plataforma para el agricultor.

[foto]

La sección Us (Sobre Nosotros) de la landing page presenta a Celevi, la startup detrás de Grotix. En esta parte se explica que el equipo proviene de la Universidad Peruana de Ciencias Aplicadas (UPC) y se enfoca en promover la agricultura inteligente mediante una plataforma IoT escalable. Su misión principal es utilizar la automatización y el análisis de datos para optimizar el riego, buscando mitigar el hambre y transformar la gestión de recursos agrícolas en un motor de bienestar social y sostenibilidad nacional. La interfaz mantiene el estilo de modo oscuro con elementos gráficos abstractos y coloridos que resaltan la identidad de la marca y utilizan los colores de la paleta designada en style guidelines.

[foto]

La sección Contact de la landing page invita a la colaboración bajo el lema "Let’s grow the future together". En el lado izquierdo, destaca un formulario de contacto sobre un fondo verde vibrante que incluye campos para el nombre, correo electrónico, asunto y mensaje, finalizando con un botón de "SEND". El texto descriptivo a la derecha motiva tanto a productores individuales como a grandes asociaciones a realizar consultas técnicas o comerciales sobre los sensores IoT y la plataforma Grotix. Esta interfaz proporciona un canal directo y sencillo para resolver dudas y fomentar la adopción de sus soluciones agrícolas.

[foto]

La sección final de la landing page, denominada Social, junto con el pie de página (footer), cierra la experiencia del usuario facilitando la conexión con la marca a través de diversos canales. Bajo el encabezado "Find us everywhere", se presentan iconos destacados de redes sociales como Instagram, Facebook, Twitter y LinkedIn, invitando a la comunidad a seguir las actualizaciones de Grotix. El footer está organizado en cuatro columnas principales:

* **Identidad:** Incluye el logotipo de Grotix, el eslogan sobre agricultura inteligente y accesos directos a redes sociales.
* **Navigation:** Réplica del menú principal con enlaces a las secciones de General, Services, App, Us, Contact y Social.
* **Legal:** Contiene enlaces a documentos normativos esenciales como Términos y Condiciones, Política de Privacidad, Política de Cookies y el Libro de Reclamaciones.
* **Support:** Ofrece recursos de ayuda, una sección de preguntas frecuentes y un acceso directo para contactar al equipo de soporte.

## 5.4. Applications UX/UI Design 
El diseño UX/UI de las aplicaciones de Livria (tanto la web para el Staff como la móvil para los Clientes) se ha abordado bajo la premisa de accesibilidad, rendimiento y optimización táctil. El objetivo principal es trasladar la experiencia de lectura y comunidad a un entorno móvil de forma fluida y nativa, respetando los patrones de diseño de cada sistema operativo. Se ha priorizado la simplicidad en la navegación y la claridad de la información, utilizando grandes zonas de toque, una tipografía legible y un contraste adecuado.

### 5.4.1. Applications Wireframes
Los wireframes de las aplicaciones móviles de Grotix (tanto para la versión web como para la móvil) representan la columna vertebral estructural del diseño, priorizando la usabilidad táctil y la eficiencia de navegación. Esta etapa se enfoca en definir la organización jerárquica del contenido y la disposición óptima de los elementos clave dentro de los patrones de diseño móvil. Al concentrarse únicamente en la estructura y el flujo de tareas sin la distracción de elementos visuales, los wireframes permiten optimizar la experiencia de usuario en movimiento y asegurar que las funcionalidades críticas del sistema sean accesibles y fluidas.

#### Web App (For Staff)

**Pantalla Principal (Main)**

[foto]

**Pantalla de Búsqueda**

[foto]

**Pantalla de Agricultores**

[foto]

**Pantalla de Agricultor Individual**

[foto]

**Pantalla de Contratos**

[foto]

**Pantalla de Listado de Dispositivos**

[foto]

**Pantalla de Bitácora en Dispositivos**

[foto]

**Pantalla Mantenimiento de Dispositivos**

[foto]

**Pantalla Dispositivo Individual**

[foto]

**Pantalla de Cultivos**

[foto]

**Pantalla Cultivo Individual**

[foto]

**Pantalla de Perfil**

[foto]


#### Mobile App (For Clients)
**Pantallas de Dashboard; Main, Settings, People**

[foto]

**Pantallas de AI, Cultivation Areas**

[foto]

**Pantallas de Reports, Profile**

[foto]

**Pantallas de Notifications**

[foto]

### 5.4.2. Applications Wireflow Diagrams

Los diagramas de wireflow de la aplicación móvil de Grotix constituyen la representación integrada de la arquitectura de pantallas y los flujos de interacción del agricultor con la plataforma. A diferencia de un wireframe estático, el wireflow combina la estructura visual de cada pantalla con las transiciones de navegación entre ellas, permitiendo verificar que cada acción del usuario desencadena una respuesta coherente del sistema. Los flujos descritos a continuación han sido diseñados tomando como eje la barra de navegación inferior (Bottom Navigation Bar) compuesta por cinco accesos directos: Dashboard, AI Advisor, Zones (botón central), Reports y Profile. De manera transversal, la cabecera superior de cada pantalla expone el logotipo de Grotix —que actúa como atajo directo hacia la pantalla de zonas— y el ícono de campanita, que despliega el panel lateral de notificaciones.

#### User Goal para Segmento 1: Agricultores Independientes 
Como agricultor usuario de Grotix, quiero visualizar en tiempo real los indicadores de humedad, temperatura e intensidad lumínica de mi zona de cultivo para tomar decisiones operativas de forma inmediata.
**Task flow:**

[foto]

**Wireflow:**

[foto]

Para poder interactuar con el monitoreo de variables de cultivo que ofrece Grotix, el agricultor accede, en primer lugar, a la pantalla principal del Dashboard al abrir la aplicación. El sistema lo sitúa automáticamente en la vista MAIN de la zona de cultivo activa, donde se despliegan en tiempo real tres métricas críticas obtenidas de los sensores IoT: el nivel de humedad del suelo representado como un indicador circular con valor porcentual y etiqueta semántica, la intensidad lumínica mediante una barra de progreso graduada con nivel descriptivo, y la temperatura ambiental en grados Celsius con indicador de estado. En caso de que alguna variable supere los umbrales configurados, el sistema resalta visualmente el indicador afectado con un cambio de color para facilitar una respuesta inmediata.

Desde esta misma pantalla, al presionar la pestaña SETTINGS ubicada en la barra de navegación superior del dashboard, el sistema presenta la vista de configuración de la zona activa. Aquí el agricultor puede activar o desactivar el riego automático mediante un toggle switch, iniciar manualmente una sesión de riego y definir el tiempo máximo de irrigación mediante un selector desplegable. Asimismo, puede establecer los niveles críticos mínimos aceptables para cada variable monitoreada —humedad, luz y temperatura— cuyos valores serán empleados por el sistema para generar alertas automáticas.

Finalmente, al seleccionar la pestaña PEOPLE, el sistema presenta el listado de colaboradores con acceso activo a la zona. El agricultor administrador puede eliminar a un colaborador existente mediante el botón REMOVE, acción que actualiza la lista de forma inmediata. Para añadir un nuevo colaborador, utiliza la barra de búsqueda superior para localizar a otro agricultor registrado en la plataforma y presiona el botón INVITE, con lo que el sistema envía una solicitud de acceso al usuario seleccionado.

#### User Goal para Segmento 2: Asociaciones Agrarias 
Como miembro de una asociación agraria, quiero consultar el análisis visual del estado de germinación y crecimiento de todas las zonas de cultivo gestionadas por la asociación, generado por la inteligencia artificial de Grotix, para conocer el progreso biológico de cada parcela sin necesidad de ser un especialista en botánica.
**Task flow:**

[foto]

**Wireflow:**

[foto]

Para poder consultar el diagnóstico fenológico que ofrece el módulo de inteligencia artificial de Grotix, el usuario accede, en primer lugar, a la pantalla de Cultivation Areas (Zones), ya sea tocando el ícono central de brote en la barra de navegación inferior o a través del logotipo de Grotix en la cabecera. En esta pantalla se presenta el listado completo de las zonas registradas por la asociación, cada una con su imagen representativa, nombre, timestamp de última sincronización y una etiqueta de estado de sensores —verde si todos están activos, roja si alguno presenta falla.

Desde cualquier pantalla de la aplicación, al presionar el ícono de destello (✦ AI Advisor) en la barra de navegación inferior, el sistema navega hacia la pantalla de AI Image Processing. En ella se muestra el indicador de confianza del modelo (AI Trust Level: 80%) y, bajo el título ZONE STATUS, el listado de todas las zonas de la asociación con sus respectivas tarjetas. Cada tarjeta presenta la imagen capturada por la cámara del microcontrolador IoT, el nombre de la zona y la etiqueta de etapa fenológica diagnosticada por el modelo (ej. Stage: SEED, Stage: GERMINATION). Si el usuario desea actualizar el diagnóstico de una zona específica, puede presionar el ícono de sincronización (↻) en la tarjeta correspondiente, tras lo cual el sistema procesa la imagen más reciente disponible y actualiza la etiqueta fenológica en pantalla.

Para acceder al detalle completo de una zona, el usuario toca directamente la tarjeta de la zona de interés. Asimismo, si gestiona una cantidad considerable de parcelas, puede utilizar la barra de búsqueda superior para filtrar las zonas por nombre y localizar rápidamente el área deseada. En ambos casos, el sistema navega hacia la pantalla dashboard_main de la zona seleccionada, donde se muestran las métricas de los sensores en tiempo real —humedad, luz y temperatura— actualizadas con los datos del dispositivo IoT asociado a esa parcela.

### 5.4.3. Applications Mock-ups
La etapa de Mockups representa la traducción fiel de la estructura definida en los wireframes a una propuesta visual de alta fidelidad. Utilizando los Style Guidelines de Grotix, esta sección ilustra el look and feel final de la plataforma. El objetivo es mostrar al detalle cómo se aplicarán los elementos visuales para generar una interfaz coherente, atractiva y funcional. Los mockups no solo respetan la jerarquía y el flujo de navegación establecidos, sino que también garantizan que la experiencia de usuario (UX) sea intuitiva y esté completamente alineada con el tono cálido y motivador de la marca.

#### Web App (For Staff)

[foto]

El Main Dashboard de la web app para el staff de Grotix presenta una interfaz intuitiva en modo oscuro organizada en tres columnas clave para la gestión operativa. La primera sección permite visualizar el estatus de los clientes activos, mientras que la columna central detalla los contratos vigentes con sus respectivas fechas de inicio. Finalmente, la sección de dispositivos monitorea en tiempo real la conectividad de los microcontroladores, diferenciando mediante etiquetas de color si se encuentran online u offline.

[foto]

La pantalla de Search de la web app para el staff ofrece una herramienta de búsqueda global integrada en una interfaz de modo oscuro, diseñada para filtrar agricultores, contratos o dispositivos de forma simultánea. Los resultados se organizan en tarjetas detalladas que muestran perfiles de usuarios con interruptores de estado, información de microcontroladores con su última fecha de mantenimiento, y el estatus de los contratos (como Active, Draft o Terminated). Esta vista unificada facilita la gestión rápida y el monitoreo del ecosistema de Grotix mediante una disposición limpia y etiquetas visuales de alta legibilidad.

[foto]

La pantalla de Agriculturists de la web app de Grotix presenta una interfaz de gestión de clientes organizada en una cuadrícula de tarjetas individuales bajo una estética de modo oscuro. Cada tarjeta muestra la fotografía del agricultor, su nombre completo y un interruptor (switch) lateral que permite activar o desactivar su estatus de forma rápida y visual. Esta disposición facilita al staff la supervisión y el control administrativo de los usuarios de la plataforma mediante un diseño limpio y funcional.

[foto]

La pantalla Single Agriculturist de la web app para el staff de Grotix ofrece una vista detallada del perfil de un usuario específico dentro de un contenedor centralizado en modo oscuro. En la parte superior del perfil, se muestra la fotografía del agricultor junto a su nombre y ocupación, acompañada de un interruptor de estado que indica claramente si el usuario está Active. El resto del formulario organiza la información de contacto y administrativa en campos de lectura, incluyendo la asociación a la que pertenece, correo electrónico, número telefónico y el rol asignado dentro de la plataforma. Esta interfaz permite al staff revisar los datos personales de manera estructurada y rápida mediante un diseño limpio y profesional.

[foto]

La pantalla de Contracts de la web app para el staff de Grotix presenta un repositorio centralizado de los acuerdos legales con clientes, organizado en una cuadrícula de tarjetas descriptivas sobre un fondo oscuro. En la parte superior, la interfaz incluye botones para alternar entre la vista de List y la opción de Add para registrar nuevos contratos, además de un icono de filtros para búsquedas avanzadas. Cada tarjeta identifica a la organización, la fecha de inicio del servicio y el estado actual del contrato mediante etiquetas de color, tales como Active, Draft, Pending, Renewed, Expired o Terminated. Esta visualización permite al equipo administrativo supervisar el ciclo de vida de cada suscripción y la vigencia de los servicios de manera eficiente.

[foto]

La pantalla de Devices de la aplicación web de Grotix permite al staff supervisar el hardware desplegado mediante una interfaz en modo oscuro organizada en una cuadrícula de tarjetas de microcontroladores. En la sección superior, el usuario puede navegar entre las funciones de List, Logbook y Maintenance, además de acceder a herramientas de filtrado. Cada tarjeta identifica un dispositivo por su código único y muestra en tiempo real si su estado es Online u Offline, junto con la fecha y hora exacta de su último mantenimiento. Esta disposición facilita un monitoreo técnico preventivo y una respuesta rápida ante cualquier desconexión en las zonas de cultivo.

[foto]

La sección Logbook dentro del módulo de Devices presenta un formulario de registro diseñado para documentar las intervenciones técnicas realizadas en el hardware de Grotix. Enmarcada en una interfaz de modo oscuro, la pantalla permite seleccionar el Device ID correspondiente, detallar la actividad realizada en un campo de texto amplio para la Action y definir el Status After mediante botones de selección rápida para marcar el dispositivo como Online u Offline. Finalmente, la vista incluye botones de acción destacados para Save o Cancel, asegurando que cada mantenimiento quede registrado correctamente en el historial del sistema.

La vista de Maintenance en el módulo de dispositivos de Grotix proporciona una interfaz de control operativo para gestionar las tareas de soporte técnico sobre el hardware. Manteniendo la estética de modo oscuro, esta pantalla organiza los microcontroladores en tarjetas que incluyen botones de acción contextuales: Start Maintenance para iniciar un proceso de revisión o End Maintenance para concluir intervenciones en curso. Cada tarjeta muestra el ID del dispositivo, su estado de conectividad actual y la marca temporal de su último mantenimiento, permitiendo al staff coordinar las tareas de campo y asegurar que todos los equipos funcionen correctamente dentro de los cronogramas establecidos.

[foto]

La pantalla de Single Device en la web app de Grotix ofrece una vista técnica integral de un microcontrolador específico, dividida en dos secciones principales sobre un fondo oscuro. En el panel izquierdo, se presentan los detalles técnicos del hardware, incluyendo el Zone ID, el modelo del dispositivo, su dirección MAC y el estatus de conexión en tiempo real (ONLINE). La sección derecha está dedicada a los Maintenance Logs, donde se listan de forma cronológica las intervenciones realizadas, detallando fechas y acciones técnicas específicas como actualizaciones de firmware o reemplazo de componentes. Esta estructura permite al staff de Grotix tener una trazabilidad completa del ciclo de vida y el estado operativo de cada unidad de hardware.

[foto]

La pantalla de Crops de la aplicación web para el staff de Grotix presenta un catálogo visual de los tipos de cultivos soportados por la plataforma, organizado en una cuadrícula de tarjetas descriptivas sobre un fondo oscuro. En la parte superior, se incluye una barra de búsqueda que permite filtrar los resultados por nombre común o científico. Cada tarjeta contiene una imagen representativa del cultivo y su nombre correspondiente (como tomate, zanahoria o albahaca), facilitando una identificación rápida y clara para la gestión agrícola. Esta interfaz mantiene la coherencia visual con el resto del sistema, ofreciendo una navegación fluida a través de la barra lateral persistente.

[foto]

La pantalla de Single Crop de la aplicación web de Grotix permite al staff gestionar los parámetros específicos de un cultivo, como el brócoli, mediante una interfaz técnica en modo oscuro. En el panel izquierdo, se muestra una imagen identificativa junto al nombre común y científico del cultivo, además de un selector para definir el Maximum Stress Time permitido. La sección derecha, bajo el encabezado Statistics, presenta controles deslizantes para configurar los rangos ideales de temperatura, humedad y luz, permitiendo ajustar los niveles óptimos de crecimiento de forma visual. Finalmente, la pantalla incluye botones prominentes para Save o Delete, asegurando un control administrativo total sobre la base de datos de cultivos.

[foto]

La pantalla de Profile en la aplicación web ofrece una vista consolidada de la información del usuario autenticado. En el panel central, se muestra la identidad del equipo o usuario, incluyendo su nombre, el registro del último acceso al sistema y una etiqueta de estado ACTIVE. Debajo de la cabecera, se organizan campos informativos sobre la cuenta. La pantalla se completa con botones de acción rápida para realizar cambios mediante la opción Edit o para finalizar la sesión de forma segura con el botón Log Out.

#### Mobile App (For Clients)

[foto]

La pantalla de Main Dashboard de la aplicación móvil de Grotix constituye el centro de control operativo para el usuario, permitiendo el monitoreo en tiempo real de zonas de cultivo específicas. Bajo una estética de modo oscuro, la interfaz presenta una tarjeta informativa del cultivo que detalla el estado de germinación y las coordenadas geográficas exactas de la plantación. El núcleo de la pantalla utiliza indicadores visuales dinámicos para reportar variables críticas: un gráfico circular para la humedad (Moisture) que indica niveles óptimos, una barra de progreso para la radiación lumínica y medidores de temperatura, todos acompañados por marcas de tiempo de la última actualización para garantizar la precisión de los datos. Asimismo, más abajo en la pantalla sale el resumen de sensores utilizados en esta zona. Esta disposición funcional se complementa con una barra de navegación inferior y pestañas superiores para ajustes y gestión de participantes, facilitando una toma de decisiones informada para mejorar la cosecha.

[foto]

La pantalla de Dashboard Settings en la aplicación móvil de Grotix permite al usuario personalizar de manera precisa el comportamiento del hardware en una zona de cultivo específica. En la sección de Irrigation, la interfaz ofrece interruptores para habilitar el riego automático o iniciar un riego manual de forma inmediata, además de un selector para establecer el Max. time of irrigation. Complementariamente, el apartado de Critical Levels permite definir los umbrales mínimos de humedad y radiación, así como el rango de temperatura ideal, asegurando que el sistema actúe según los requerimientos técnicos del cultivo. Esta configuración granular garantiza una gestión eficiente de los recursos y la protección de la salud de las plantas directamente desde el dispositivo móvil.

[foto]

La pantalla de Dashboard People en la aplicación móvil de Grotix facilita la gestión colaborativa de las zonas de cultivo al permitir la administración de los participantes asociados a cada proyecto. Bajo una interfaz de modo oscuro, esta sección presenta una lista de agricultores con sus respectivas fotografías, nombres y roles, integrando una barra de búsqueda superior para una localización rápida de usuarios. Los controles interactivos permiten invitar a nuevos colaboradores o remover a miembros existentes de la zona seleccionada, asegurando que el equipo de trabajo esté siempre actualizado y coordinado en las tareas de monitoreo agrícola.

[foto]

La pantalla de AI Image Processing en la aplicación móvil de Grotix permite al usuario visualizar el análisis avanzado de sus cultivos mediante inteligencia artificial. En la parte superior, se destaca el AI Trust Level, que indica el grado de confiabilidad del procesamiento actual (ej. 80%). Bajo la sección de Zone Status, se presenta un listado de las diferentes áreas de cultivo, mostrando para cada una la etapa de crecimiento detectada —como Seed o Germination— junto con la hora de la última actualización. Esta interfaz facilita el seguimiento automatizado del desarrollo de las plantas, permitiendo una supervisión precisa de múltiples zonas desde una sola vista centralizada.

[foto]

La pantalla de Cultivation Areas en la aplicación móvil de Grotix sirve como el inventario principal de los sectores de cultivo gestionados por el usuario. En esta interfaz de modo oscuro, se listan todas las zonas activas (como la "Zona Tomatitos" o el "Área de Zanahorias") mediante tarjetas que incluyen una imagen referencial, el nombre del área y la hora de su última sincronización. Un elemento crítico de esta pantalla es el indicador de estado de los dispositivos IoT, el cual notifica visualmente si todos los sensores operan correctamente o si existen fallas técnicas (ej. "Some sensors are failing"). Además, la parte superior integra herramientas funcionales para buscar zonas específicas, añadir nuevas áreas mediante un botón de "+" y acceder a filtros de configuración, manteniendo la coherencia con la barra de navegación inferior del sistema.

[foto]

La pantalla de Generate Report en la aplicación móvil de Grotix proporciona al usuario las herramientas necesarias para extraer y analizar datos históricos de sus cultivos de manera personalizada. Manteniendo la línea visual de modo oscuro de la plataforma, esta sección se enfoca específicamente en reportes de riego (Irrigation), permitiendo configurar rangos de tiempo exactos mediante selectores de fecha de inicio y fin, o mediante un menú desplegable para periodos predefinidos (3 meses, 6 meses, etc.). Una vez establecidos los parámetros, el botón de GENERATE procesa la información para mostrarla en el área de visualización inferior, facilitando al agricultor la revisión de tendencias y el consumo de recursos para una mejor planificación de futuras cosechas.

[foto]

La pantalla de Personal Info en la aplicación móvil de Grotix permite al agricultor gestionar su identidad digital y datos de contacto de manera centralizada. Bajo un saludo personalizado, la interfaz despliega un formulario que incluye campos para el nombre completo, correo electrónico, número telefónico y el rol del usuario, además de un espacio dedicado para la visualización y actualización de la foto de perfil. En la base de la tarjeta informativa, se ubican los botones de Edit para realizar modificaciones y Log Out para cerrar la sesión, manteniendo la coherencia visual del modo oscuro y la accesibilidad a través de la barra de navegación inferior que conecta con el resto de los módulos de la plataforma.
Abajo de esta sección podrá encontrar una línea de soporte para contactar con el staff en caso de que uno de sus sensores esté fallando.

[foto]

La sección de Notifications en la aplicación móvil de Grotix se presenta como un panel superpuesto de acceso rápido (drawer) que mantiene al usuario informado sobre eventos clave del sistema. Con un diseño limpio en modo oscuro, el panel organiza las alertas de forma cronológica, permitiendo visualizar mensajes de bienvenida, estados de los sensores o alertas de riego. Cada notificación incluye una opción de eliminación individual mediante un icono de papelera, además de un botón global de CLEAR ALL en la parte inferior para gestionar el historial de avisos de manera eficiente. Esta funcionalidad garantiza que el agricultor no pierda de vista ninguna actualización crítica sobre el rendimiento y la salud de sus cultivos.

[foto]

La vista de Configuration dentro del panel de notificaciones de la aplicación móvil permite al usuario personalizar sus preferencias de alerta de manera detallada. En esta sección, el agricultor puede gestionar los canales de recepción mediante interruptores para Push Notifications y Email Notifications. Además, ofrece un control específico sobre el tipo de contenido que genera avisos, permitiendo activar o desactivar alertas para cambios en el riego (irrigation), alcance de niveles críticos en los sensores o actualizaciones sobre el estado de germinación de los cultivos. Esta flexibilidad asegura que el usuario reciba únicamente la información más relevante.


### 5.4.4. Applications User Flow Diagrams

#### Segmento Objetivo #1: Productores Independientes

**Contexto del User Persona (Mateo Rojas):** Él busca optimizar su tiempo, reducir el trabajo manual y necesita una interfaz que no lo abrume tecnológicamente, dándole seguridad sobre su chacra de forma remota.

**User Goal:** Monitorear las variables críticas de su cultivo en tiempo real y delegar el trabajo manual habilitando el riego automático para optimizar su tiempo.

**Task flow:**

[foto]

**User flow:**

[foto]

Para interactuar con el flujo de monitoreo inteligente y automatización que ofrece Grotix, el agricultor accede inicialmente a la pantalla de Cultivation Areas al abrir la aplicación, donde visualiza un listado general de sus parcelas registradas. Al seleccionar una zona específica, como la "Zona Tomatitos", el sistema lo dirige automáticamente a la vista MAIN del Dashboard. En esta sección, se despliegan en tiempo real las métricas críticas capturadas por los sensores IoT: el nivel de humedad del suelo representado porcentualmente, la intensidad lumínica y la temperatura ambiental. Estas variables permiten al usuario supervisar la salud de su cultivo de manera inmediata, alertando visualmente si algún parámetro se encuentra fuera de los umbrales seguros establecidos.  Sin perder tiempo en navegaciones complejas, el agricultor puede desplazarse hacia la pestaña SETTINGS mediante un toque en la barra de navegación superior de la zona. En esta vista, el usuario tiene la capacidad de configurar con precisión los niveles críticos mínimos para cada variable ambiental (humedad, luz y temperatura), así como activar el interruptor de riego automático mediante un toggle switch. Esta acción garantiza que el hardware en campo responda de forma autónoma a las necesidades hídricas detectadas, optimizando el uso del recurso y permitiendo al agricultor delegar el esfuerzo físico del riego manual.  Finalmente, para validar el progreso biológico y obtener una mayor tranquilidad sobre el estado de su inversión, el usuario selecciona el icono de destello en la barra de navegación inferior para acceder al módulo de AI Image Processing. Aquí, el sistema muestra el diagnóstico generado por inteligencia artificial, identificando automáticamente la etapa fenológica actual del cultivo (como germinación o crecimiento) junto con un nivel de confianza del análisis. Este flujo integrado permite una supervisión remota completa y ágil, transformando datos sensoriales y visuales complejos en decisiones técnicas seguras para el productor.

#### Segmento Objetivo #2: Asociaciones Agrarias (Carlos Mendoza)

**Contexto del Persona (Carlos Mendoza):** Él es un gerente racional que necesita datos precisos, trazabilidad para exportación (GlobalGAP) y control sobre múltiples agricultores o zonas desde una sola plataforma.

**User Goal:** Auditar el personal asignado a una zona de cultivo específica y generar un reporte de riego trimestral para cumplir con los estándares de calidad de exportación.

**Task flow:**

[foto]

**User flow:**

[foto]

Para que el usuario logre auditar el personal asignado a una zona de cultivo específica y generar reportes de riego trimestrales que cumplan con los estándares de calidad de exportación, Grotix ofrece un flujo administrativo centralizado y eficiente. En primer lugar, si el objetivo es la auditoría de personal, el usuario accede desde la pantalla de Cultivation Areas a la zona específica de interés. Una vez dentro, se desplaza a la vista PEOPLE a través de la barra de navegación superior del dashboard. En esta sección, se visualiza la información detallada de los encargados actuales de la zona y un listado de otros agricultores de la granja disponibles para ser vinculados. El administrador tiene la facultad de gestionar estos accesos de forma dinámica: puede remover a un colaborador existente mediante el botón REMOVE, lo que actualiza la lista al instante, o añadir nuevos integrantes utilizando la barra de búsqueda y presionando el botón INVITE. Este control bidireccional asegura que siempre se tenga claridad sobre quién opera cada sector de la producción.  Por otro lado, para la generación de documentación técnica, el usuario accede a la vista de REPORTS directamente desde el menú de navegación inferior. Dentro de este módulo, el proceso de configuración está diseñado para minimizar errores de entrada: al seleccionar la fecha de inicio del reporte, el sistema utiliza una lógica de autocompletado para determinar la fecha de fin basada en el rango de tiempo seleccionado (por ejemplo, "3 months" para trazabilidad trimestral). El agricultor puede ajustar estos periodos mediante un selector desplegable, lo que actualiza automáticamente los límites temporales del informe. Una vez validados los parámetros, el usuario acciona el botón GENERATE, lo que inicia el procesamiento de la telemetría histórica y la descarga del reporte directamente en el dispositivo. Este flujo garantiza la obtención ágil de pruebas de sostenibilidad y huella hídrica, facilitando el cumplimiento de normativas internacionales.

## 5.5. Applications Prototyping 
Con el objetivo de evaluar y perfeccionar la accesibilidad y la experiencia de usuario (UX) antes del desarrollo final, se elaboró un prototipo interactivo a partir de los mockups de alta fidelidad, centrado exclusivamente en la navegación móvil.
Este modelo funcional simula de forma integral el recorrido del usuario dentro de la aplicación, permitiendo explorar directamente sus secciones, elementos y flujos de interacción tal como se verá en un dispositivo móvil.

El prototipo fue diseñado siguiendo principios de arquitectura de la información clara, jerarquía visual lógica y diseño inclusivo. Se priorizó la facilidad de uso, asegurando que cada componente respete los estándares de usabilidad y coherencia visual para una navegación fluida e intuitiva. Esta versión navegable actúa como una fiel representación de la futura interfaz de la aplicación, siendo clave para validar decisiones de diseño y garantizar una experiencia consistente y accesible.

### Web App (For Staff)

[foto]

Video explicativo:

[foto]

Link del video:
https://drive.google.com/file/d/1DgfYWx-fN4A5AzBG1_7rw40WK8VJpxDh/view?usp=sharing

Link al prototipo interactivo:
https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=40-63&p=f&t=dB36gijF28heh7zW-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A61 

### Mobile App (For Clients)

[foto]

Video explicativo:

[foto]

Link del video:
https://drive.google.com/file/d/1_v9BDa8tAwhBIG6wpW-Yj4evmoUe0aWg/view?usp=sharing

Link al prototipo interactivo:
https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=148-1047&p=f&t=JdOOShNAUIqGebVF-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A62 

## 5.6. IoT Device Design 

El diseño del dispositivo (Device Design) es la fase arquitectónica fundamental que planifica y documenta la interconexión física del hardware, asegurando una asignación lógica de pines, niveles de voltaje adecuados y aislamiento eléctrico para evitar fallos antes del ensamblaje. Bajo este enfoque técnico, la siguiente figura presenta el diagrama del nodo IoT de Grotix, ilustrando la integración del microcontrolador central ESP32-S3 con la red de sensores de percepción y los componentes de actuación e interfaz local. Este esquema sirve como la guía técnica estandarizada para la construcción del circuito, garantizando la estabilidad operativa y la correcta captura de telemetría en el entorno agrícola. 

[foto]

# CAPÍTULO VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration 

La siguiente tabla describe las herramientas y productos de software que el equipo utilizará para colaborar en el ciclo de vida de Grotix:

| Categoría | Producto | Propósito de uso | Ruta |
|---|---|---|---|
| Project Management | Jira | Seguimiento de tareas, gestión de Sprints y documentación de Historias de Usuario (US) y Técnicas (TS). | [SaaS] atlassian.com/jira |
| UX/UI Design | Figma | Diseño colaborativo y prototipado de la Mobile App, Staff Web App y la Landing Page. | [SaaS] figma.com |
| Backend Development | JetBrains Rider | Desarrollo principal de los microservicios en .NET (C#) para Telemetría, Irrigación, Perfiles, entre otros. | [Download] jetbrains.com/rider |
| Frontend Development | VS Code | Desarrollo de la aplicación web utilizando Vue.js y Landing Page con HTML, CSS y JS. | [Download] code.visualstudio.com |
| Mobile Development | Android Studio | IDE principal para el desarrollo de la aplicación móvil de Grotix utilizando el framework Flutter. | [Download] developer.android.com |
| Embedded Systems | VS Code (PlatformIO) | Desarrollo de firmware para los microcontroladores ESP32 utilizando C++. | [Download] platformio.org |
| API Documentation | Swagger | Documentación interactiva y ejecución de pruebas para los servicios web RESTful. | [Integrated] swagger.io |
| Cloud Infrastructure | Microsoft Azure | Hosting en la nube, gestión de bases de datos y orquestación del API Gateway del sistema. | [SaaS] portal.azure.com |
| Database Management | MySQL Workbench | Diseño visual y gestión de la Core DB para los datos transaccionales y maestros. | [Download] dev.mysql.com |
| Software Testing | Postman | Ejecución de pruebas manuales de los endpoints de la API y validación de peticiones HTTP. | [Download] postman.com |
| IoT Debugging | MQTT Explorer | Monitoreo y prueba de los mensajes MQTT enviados entre el ESP32 y el broker en la nube. | [Download] mqtt-explorer.com |
| Containerization | Docker Desktop | Creación y gestión de contenedores ligeros para asegurar un despliegue eficiente de los microservicios. | [Download] docker.com |

### 6.1.2. Source Code Management  
El equipo de Grotix establece GitHub como la plataforma centralizada para la gestión del código fuente y el control de versiones. Este esquema asegura la trazabilidad de las modificaciones y permite una colaboración eficiente en el desarrollo de la solución IoT. 

Cada producto digital cuenta con un repositorio independiente:

| Producto | URL del Repositorio |
|---|---|
| Landing Page | https://github.com/CeleviGrotix/Grotix_LandingPage |
| Web Services (Backend) | https://github.com/CeleviGrotix/Grotix_Web_Services |
| Frontend Web Applications | https://github.com/CeleviGrotix/Grotix_Web |
| Mobile Application (Flutter) | https://github.com/CeleviGrotix/Grotix_Mobile |

Para la gestión de versiones se implementa el modelo GitFlow, el cual organiza el desarrollo mediante el uso de ramas específicas:
* **Main:** Es la rama principal que contiene el código siempre estable y listo para producción.
* **Develop:** Rama de integración donde se fusionan todas las funcionalidades terminadas antes de ser lanzadas.
* **Feature Branches:** Ramas temporales creadas para el desarrollo de requerimientos específicos. Se originan desde develop.
* **Release Branches:** Utilizadas para preparar un nuevo lanzamiento a producción, permitiendo corregir errores menores y preparar metadatos.
* **Hotfix Branches:** Ramas urgentes para corregir errores críticos detectados directamente en la rama main.

| Tipo de Rama | Convención de Nombre | Ejemplo |
|---|---|---|
| Feature | feature/[ID_Story]-[descripción-breve] | feature/US15-organizacion-zonas |
| Release | release/v[Mayor].[Menor].[Parche] | release/v1.0.0 |
| Hotfix | hotfix/v[Mayor].[Menor].[Parche]-[desc] | hotfix/v1.0.1-error-login |

Grotix utiliza el formato MAYOR.MENOR.PARCHE para identificar sus versiones:
1. **MAYOR:** Cambios que rompen la compatibilidad con versiones anteriores.
2. **MENOR:** Nuevas funcionalidades que mantienen la compatibilidad.
3. **PARCHE:** Corrección de errores menores que no afectan la funcionalidad general.
Todos los mensajes de commit deben seguir la estructura <tipo>(<alcance>): <descripción> para estandarizar el historial:
* **feat:** Nueva funcionalidad (asociada a una US o TS).
* **fix:** Solución a un error.
* **docs:** Cambios exclusivos en la documentación.
* **test:** Adición o corrección de pruebas.
* **refactor:** Cambios en el código que no añaden funciones ni corrigen errores.
Ejemplo: feat(irrigation): implementar lógica de riego automático (US20)

### 6.1.3. Source Code Style Guide & Conventions   
Para garantizar la mantenibilidad y la legibilidad del sistema Grotix, el equipo ha adoptado un conjunto de estándares de codificación internacionales. El cumplimiento de estas normas es obligatorio para asegurar la consistencia técnica en todos los componentes de la solución. 

#### Principios Generales
* **Nomenclatura en Inglés:** Todos los nombres de variables, funciones, clases, tablas de base de datos y comentarios deben redactarse exclusivamente en inglés.
* **Significado Semántico:** Los nombres deben ser descriptivos (ej. getSoilMoistureLevel en lugar de getMoist).
* **Idioma de Programación:** Se prohíbe el uso de "Spanglish" en el código fuente.

#### Guía de Estilo por Lenguaje

| Lenguaje | Convención de Nombres | Guía de Estilo de Referencia |
|---|---|---|
| JavaScript | camelCase para variables/funciones; PascalCase para clases. | Google JavaScript Style Guide |
| C++ (ESP32) | camelCase para funciones y snake_case para variables de hardware. | Google C++ Style Guide |
| SQL | snake_case para tablas (plural) y columnas. Palabras clave en UPPERCASE. | SQL Style Guide (by Simon Holywell) |
| HTML / CSS | kebab-case para IDs y clases (ej. status-card). | Google HTML/CSS Style Guide |
| C# (.NET) | PascalCase para métodos/clases; _camelCase para campos privados. | Microsoft C# Coding Conventions |
| Python (IA) | snake_case para funciones/variables; PascalCase para clases. | PEP 8 – Style Guide for Python Code |
| Dart (Flutter) | camelCase para variables; PascalCase para tipos/clases. | Effective Dart Style Guide |

#### Convenciones para Gherkin
Para los archivos .feature, el equipo sigue las Gherkin Conventions for Readable Specifications:
* **Lenguaje de Negocio:** Uso de términos agrícolas claros en las sentencias Given, When y Then.
* **Estructura:** Un solo archivo .feature por cada Historia de Usuario, identificado con su ID respectivo (ej. US11_Moisture_Monitoring.feature).

Para automatizar el cumplimiento de estas guías, se integrarán linters en los IDEs de los desarrolladores, tales como ESLint para JavaScript, StyleCop para C# y Pylint para Python, configurados para rechazar cualquier código que no cumpla con la nomenclatura en inglés o el formato estandarizado. 

### 6.1.4. Software Deployment Configuration   
Se ha diseñado una estrategia de despliegue continuo (Continuous Deployment) e integración continua (Continuous Integration) basada en repositorios de GitHub y GitHub Actions. Esta configuración garantiza que cada producto digital llegue a su respectivo entorno de producción de manera segura, automatizada y tras haber superado las validaciones técnicas.

A continuación, se presenta el modelo de despliegue de la solución, dividido en la topología de la infraestructura y los flujos de publicación por producto.

#### Diagrama de Despliegue (C4 Model) 
El siguiente diagrama detalla la arquitectura física y de contenedores en el entorno de producción. La infraestructura se divide en tres grandes bloques: 
1. **Capa de Usuario (Dispositivos):** Comprende los smartphones donde se ejecuta la Mobile App (Flutter) y las computadoras desde las cuales se accede a la Staff Web App (Vue.js) y la Landing Page.
2. **Capa Edge/IoT (Infraestructura en Campo):** Representa el entorno rural. Incluye el Grotix Gateway (ej. Raspberry Pi) que ejecuta la Edge App (Python) apoyada en una caché local (SQLite), y los nodos físicos (ESP32) que ejecutan el firmware de control en C++.
3. **Capa Cloud (Azure):** El núcleo central de procesamiento en la región us-east-1. Utiliza Azure API Gateway como único punto de entrada, un clúster EKS (Kubernetes) para orquestar los microservicios (.NET y Python), y servicios RDS para la persistencia políglota (MySQL para la Core DB y TimescaleDB para la Telemetry DB).

[foto]

Para materializar esta arquitectura a partir de los repositorios de código fuente, se han configurado los siguientes pipelines de despliegue automatizado:
1. **Web Services (Microservicios Backend en C# y Python)**
    * **Activador:** Fusión (merge) de un Pull Request hacia la rama main.
    * **Proceso:**
        1. GitHub Actions inicializa el entorno y ejecuta automáticamente la suite de pruebas (unitarias y de integración).
        2. Si las pruebas son exitosas, se compila el código fuente y se genera una imagen de contenedor Docker.
        3. La imagen se etiqueta con el Semantic Versioning correspondiente y se empuja (push) a un registro de contenedores (Amazon ECR).
        4. Se actualizan los manifiestos de Kubernetes para desplegar la nueva versión de la imagen en los pods del clúster de Azure, garantizando Zero-Downtime.
2. **Frontend Web Applications (Staff Web App y Landing Page)**
    * **Activador:** Aprobación de cambios en la rama main.
    * **Proceso:**
        1. GitHub Actions clona el repositorio e instala las dependencias mediante el gestor de paquetes (npm install).
        2. Se ejecuta el proceso de construcción (build) para minificar y ofuscar el código de Vue.js y los recursos estáticos de la Landing Page (npm run build).
        3. Los archivos estáticos resultantes se transfieren automáticamente a un servicio de almacenamiento en la nube (Azure) distribuido mediante una red de entrega de contenido (CloudFront) para garantizar baja latencia global.
3. **Mobile Application (Flutter)**
    * **Activador:** Creación de un Release (tag) en la rama main.
    * **Proceso:**
        1. El pipeline de CI ejecuta el analizador estático de Dart y las pruebas de los widgets.
        2. Se compilan los binarios nativos para producción: formato AAB (Android App Bundle) para la Play Store y formato IPA para iOS.
        3. Los binarios generados se publican automáticamente en Firebase App Distribution para pruebas internas de la asociación agraria, o se envían a las consolas de Google Play y App Store Connect para su revisión pública.
4. **Embedded Applications (Grotix Gateway y Nodos ESP32)**
    * **Activador:** Lanzamiento de una versión de firmware estable en main.
    * **Proceso:**
        1. Para el Grotix Gateway: El script de despliegue actualiza automáticamente la imagen Docker de la Edge App en los dispositivos Raspberry Pi vinculados a través de un servicio de gestión IoT.
        2. Para los Nodos ESP32 (Firmware en C++): El código fuente compilado mediante PlatformIO genera un archivo binario .bin. Este archivo se distribuye a los microcontroladores en el campo mediante un proceso de actualización OTA (Over-The-Air) a través de la red Wi-Fi local que provee el Gateway, sin requerir intervención física en los cultivos.

## 6.2. Landing Page, Services & Applications Implementation

Este apartado describe el proceso de diseño, desarrollo e implementación de soluciones digitales orientadas a fortalecer la presencia online y optimizar la experiencia del usuario. A través de la creación de landing pages, la implementación de servicios digitales y el desarrollo de aplicaciones, se busca ofrecer soluciones funcionales, escalables y alineadas con los objetivos del negocio.

La implementación se enfoca en garantizar usabilidad, rendimiento y coherencia visual, asegurando que cada componente cumpla con estándares de calidad y responda a las necesidades específicas del cliente. Desde páginas orientadas a la conversión hasta aplicaciones que automatizan procesos, este apartado refleja un enfoque integral que combina diseño, tecnología y estrategia para generar valor real y medible.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1

| Campo | Detalle |
|---|---|
| Sprint # | Sprint 1 |
| **Sprint Planning Background** |  |
| Date | 26/04/26 |
| Time | 20:00 |
| Location | Reunión Virtual de Google Meet |
| Prepared By | Cassius Martel |
| Attendees (to planning meeting) | Binda Arbañil, Marcelo Alejandro / Castillo Garay, Ainhoa Lucía / Martel Andrade, Cassius Estefano / Nakamurakare Teruya, Alex Tomio / Rodas Sotomayor, Ernesto / |
| Review Summary | Presentación exitosa de los microservicios Profiles y Cultivation Area integrados con el API Gateway. Validación de la Landing Page y flujo de Auth con JWT. Todas las tareas (56 SP) marcadas como "Done". |
| Retrospective Summary | Se identificó la necesidad de adelantar tareas de configuración de hardware para el Sprint 2 y mejorar la estimación en tareas de infraestructura inicial. |
| **Sprint Goal & User Stories** |  |
| Sprint 1 Goal | El objetivo de este primer sprint es establecer la presencia digital inicial de Grotix y desplegar el núcleo de servicios backend (Profiles y Cultivation Area) integrados mediante un API Gateway. Se busca que la plataforma sea capaz de gestionar identidades, autenticar usuarios mediante JWT y permitir la administración básica de clientes, contratos y catálogos de cultivos para su posterior vinculación con el hardware IoT. |
| Sprint 1 Velocity | 56 |
| Sum of Story Points | 56 |

#### 6.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Frontend & UI/UX | Backend & API | QA & Testing | Infrastructure & Deployment | Project Management |
|---|---|---|---|---|---|---|
| Martel Andrade, Cassius Estefano | kcc12321 | C | C | L | C | L |
| Binda Arbañil, Marcelo Alejandro | MarceHkd | L | C | C | C | C |
| Castillo Garay, Ainhoa Lucía | noaa01100001 | L | C | C | C | C |
| Nakamurakare Teruya, Alex Tomio | kistoo | C | L | C | C | C |
| Rodas Sotomayor, Ernesto | ernesto1718 | C | C | C | L | C |

#### 6.2.1.3. Sprint Backlog 1

| Campo | Detalle |
|---|---|
| Sprint # | Sprint 1 |

| User Story Id | User Story Title | Work-Item / Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---|---:|---|---|
| US01 | Visualización de propuesta de valor y servicios | T01 | Maquetado HTML/CSS de Hero Section | Creación de la estructura base del primer bloque visible (Hero) en la landing page. | 3 | Frontend Dev | Done |
| US01 | Visualización de propuesta de valor y servicios | T02 | Inserción de Copywriting principal | Redacción y colocación del Headline impactante y la descripción de la plataforma. | 2 | Frontend Dev | Done |
| US01 | Visualización de propuesta de valor y servicios | T03 | Maquetado de Layout de Servicios | Implementación del layout para mostrar los pilares clave del servicio. | 3 | Frontend Dev | Done |
| US01 | Visualización de propuesta de valor y servicios | T04 | Integración de iconografía | Búsqueda, optimización e inserción de assets visuales para la web. | 2 | Frontend Dev | Done |
| US02 | Enlaces de acceso a la aplicación móvil | T05 | Integración de insignias de tiendas | Colocación de los logos de "App Store" y "Google Play". | 1 | Frontend Dev | Done |
| US02 | Enlaces de acceso a la aplicación móvil | T06 | Validación de redirección a App Store | Configuración de atributos href para redireccionar a la App Store. | 2 | Frontend Dev | Done |
| US02 | Enlaces de acceso a la aplicación móvil | T07 | Validación de redirección a Play Store | Configuración de atributos href para redireccionar a la Play Store. | 2 | Frontend Dev | Done |
| US03 | Implementación de CTA | T08 | Diseño del CTA primario (Hero) | Estilización del botón principal para que destaque visualmente. | 2 | Frontend Dev | Done |
| US03 | Implementación de CTA | T09 | Integración de CTA secundario | Colocación de un botón de acción permanente dentro de la barra de navegación. | 2 | Frontend Dev | Done |
| US04 | Visualización de misión, visión y equipo | T10 | Maquetado de la sección Nosotros | Construcción estructural del contenedor para la historia de la startup. | 3 | Frontend Dev | Done |
| US04 | Visualización de misión, visión y equipo | T11 | Carga de contenido de misión/visión | Formateo del texto sobre la misión y presentación del nombre "Grotix". | 2 | Frontend Dev | Done |
| US05 | Implementación de formulario y canales de contacto | T12 | Maquetado UI del formulario | Creación de los inputs para Nombre, Correo, Asunto y Mensaje. | 3 | Frontend Dev | Done |
| US05 | Implementación de formulario y canales de contacto | T13 | Validaciones de cliente (Frontend) | Lógica en JS para evitar campos vacíos y validar el formato del email. | 3 | Frontend Dev | Done |
| US05 | Implementación de formulario y canales de contacto | T14 | Configuración del transporte de correo | Enlace del formulario con un servicio de envío. | 4 | Backend Dev | Done |
| US05 | Implementación de formulario y canales de contacto | T15 | Feedback visual (Modales) | Creación de alertas de éxito o error tras el intento de envío del formulario. | 2 | Frontend Dev | Done |
| US06 | Enlaces a redes sociales | T16 | Maquetado del Footer | Creación de la estructura del pie de página. | 2 | Frontend Dev | Done |
| US06 | Enlaces a redes sociales | T17 | Inserción de iconos vectoriales | Colocación de SVG oficiales de Instagram, LinkedIn y Facebook con enlaces. | 2 | Frontend Dev | Done |
| US07 | Implementación de sistemas de navegación simplificada | T18 | Barra de navegación Desktop | Implementación del menú horizontal superior principal. | 3 | Frontend Dev | Done |
| US07 | Implementación de sistemas de navegación simplificada | T19 | Menú Hamburguesa Móvil | Lógica de colapso y despliegue del menú para pantallas pequeñas. | 4 | Frontend Dev | Done |
| US07 | Implementación de sistemas de navegación simplificada | T20 | Configuración de Scroll Suave | Aplicación de comportamiento CSS/JS para transiciones fluidas entre secciones. | 1 | Frontend Dev | Done |
| US07 | Implementación de sistemas de navegación simplificada | T21 | Resaltado dinámico (ScrollSpy) | Lógica para cambiar el estilo del elemento del menú según la sección visible. | 3 | Frontend Dev | Done |
| US08 | Implementación de Identidad y Consistencia Visual | T22 | Definición de variables de color CSS | Creación del archivo de estilos base con los colores primarios y secundarios. | 2 | Frontend Dev | Done |
| US08 | Implementación de Identidad y Consistencia Visual | T23 | Configuración de escala tipográfica | Definición de tamaños y pesos para títulos (H1-H6) y párrafos en toda la web. | 2 | Frontend Dev | Done |
| US09 | Optimización de tiempos de respuesta y carga inicial | T24 | Conversión y compresión de assets | Pasaje de imágenes a formatos modernos (WebP) y reducción de peso. | 3 | Frontend Dev | Done |
| US09 | Optimización de tiempos de respuesta y carga inicial | T25 | Implementación de carga diferida | Agregado de atributos loading="lazy" a las imágenes fuera del Hero Section. | 2 | Frontend Dev | Done |
| TS01 | Implementación de Endpoints de Monitoreo de Salud (Health Checks) | T26 | Implementación del endpoint /live | Creación del controlador REST básico que devuelva status 200 OK en el backend. | 2 | Backend Dev | Done |
| TS01 | Implementación de Endpoints de Monitoreo de Salud (Health Checks) | T27 | Test de conexión MySQL (/ready) | Implementación del ping a la base de datos central en la lógica de salud. | 3 | Backend Dev | Done |
| TS01 | Implementación de Endpoints de Monitoreo de Salud (Health Checks) | T28 | Test de conexión TimescaleDB (/ready) | Implementación de la verificación de la base de datos de telemetría. | 3 | Backend Dev | Done |
| TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | T29 | Setup del contenedor IoC | Configuración de los servicios iniciales en la clase de arranque (Program.cs). | 3 | Backend Dev | Done |
| TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | T30 | Configuración de ORM y Conexión DB | Setup del DbContext/Gestor de entidad y variables de entorno para MySQL. | 4 | Backend Dev | Done |
| TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | T31 | Creación de Migración Inicial (Users) | Generación del script SQL y tabla física de Usuarios para habilitar el login. | 2 | Backend Dev | Done |
| TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | T32 | Interfaz ITelemetryRepository | Definición de los métodos base de lectura y escritura para la telemetría. | 2 | Backend Dev | Done |
| TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | T33 | Interfaz IUserRepository | Definición de los métodos base para la gestión de entidades de usuario. | 2 | Backend Dev | Done |
| TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | T34 | Lógica de generación de JWT | Creación del servicio que emite tokens firmados con fecha de expiración. | 4 | Backend Dev | Done |
| TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | T35 | Algoritmo de Hashing (BCrypt) | Implementación de la función de cifrado de contraseñas de un solo sentido. | 3 | Backend Dev | Done |
| TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | T36 | Middleware de validación JWT | Creación del interceptor global para verificar el token en rutas protegidas. | 4 | Backend Dev | Done |
| TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | T37 | Configuración estricta de CORS | Definición de los dominios autorizados para consumir la API de Grotix. | 2 | Backend Dev | Done |
| TS06 | Implementación de Infraestructura de Pruebas Automatizadas | T38 | Instalación del framework de Testing | Setup inicial de la librería principal (xUnit/JUnit) en la solución. | 2 | QA/Dev | Done |
| TS06 | Implementación de Infraestructura de Pruebas Automatizadas | T39 | Instalación de librerías de Mocking | Integración de Moq/Mockito para la futura simulación de dependencias. | 2 | QA/Dev | Done |
| TS06 | Implementación de Infraestructura de Pruebas Automatizadas | T40 | Scaffolding de tests | Creación de la estructura de carpetas tests/unit y tests/integration. | 1 | QA/Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T41 | Inicialización del Repositorio Web App | Creación del proyecto base (Vue), instalación de Vite y Router. | 3 | Frontend Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T42 | Maquetado UI Login Web | Creación de la pantalla de inicio de sesión de uso exclusivo interno. | 3 | Frontend Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T43 | Validaciones locales del formulario | Comprobación de integridad de email y formato de contraseña en el front. | 2 | Frontend Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T44 | Integración con Auth API | Lógica de envío de peticiones POST y recepción del JWT. | 4 | Dev Team | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T45 | Almacenamiento seguro en cliente | Lógica para guardar el token en la Web App para mantener la sesión. | 2 | Frontend Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T46 | Configuración de Auth Guards (Router) | Protección de las URL del portal web para redirigir a no autenticados. | 3 | Frontend Dev | Done |
| TS14 | Autenticación y Control de Acceso para el Portal de Administración | T47 | Implementación de Cierre de Sesión | Lógica de destrucción del token almacenado y redirección a login. | 2 | Frontend Dev | Done |
| TS08 | Dashboard web con indicadores clave del sistema | T48 | Maquetado del Layout principal | Creación del contenedor lateral o superior que alberga el Dashboard. | 3 | Frontend Dev | Done |
| TS08 | Dashboard web con indicadores clave del sistema | T49 | Componentes UI de Tarjetas (Cards) | Creación de los bloques visuales para "Clientes Activos" y "Contratos". | 3 | Frontend Dev | Done |
| TS08 | Dashboard web con indicadores clave del sistema | T50 | Lógica de Mock Data inicial | Llenado temporal del dashboard con datos estáticos para visualizar el frontend. | 2 | Frontend Dev | Done |
| TS10 | Registro de contratos externos en campo | T51 | APIs de Registro de Contratos | Implementación en Backend de lógica de generación de contratos e invitaciones. | 6 | Backend Dev | Done |
| TS10 | Registro de contratos externos en campo | T52 | UI de Contratos y Asociaciones | Desarrollo de vistas en Vue para listar asociaciones y generar contratos 1-a-1. | 8 | Frontend Dev | Done |
| TS13 | Consulta rápida del catálogo de cultivos | T53 | APIs del Catálogo de Cultivos | Endpoints de CultivationArea para realizar el CRUD de plantas y sus umbrales. | 5 | Backend Dev | Done |
| TS13 | Consulta rápida del catálogo de cultivos | T54 | UI de Catálogo de Cultivos | Implementación de CropListView y vistas de edición de parámetros táctiles. | 6 | Frontend Dev | Done |
| TS09 | Gestión web de clientes agricultores | T55 | APIs de Gestión de Agricultores | Implementación de endpoints para consultar, buscar y editar perfiles de clientes. | 5 | Backend Dev | Done |
| TS09 | Gestión web de clientes agricultores | T56 | UI de Perfiles de Agricultores | Creación de ListView y DetailsView en Vue para la administración de clientes. | 6 | Frontend Dev | Done |

#### 6.2.1.4. Development Evidence for Sprint Review

Durante el presente sprint se alcanzó un avance significativo en la implementación e integración funcional del ecosistema Grotix, logrando la convergencia exitosa de sus tres pilares tecnológicos: Backend, Web App y Landing Page. Se consolidó el consumo de los Web Services REST correspondientes a los microservicios Profiles.Api y CultivationArea.Api, abarcando flujos críticos de autenticación JWT, gestión de roles, contratos comerciales y administración de áreas de cultivo, validados rigurosamente mediante Postman y documentación OpenAPI/Swagger. Paralelamente, se avanzó en la lógica interactiva y el dashboard de la aplicación Grotix_Web desarrollada en Vue.js, garantizando una experiencia de usuario fluida y conectada en tiempo real, mientras que el repositorio Grotix_LandingPage fue finalizado para proyectar la identidad visual y propuesta de valor de la plataforma. Esta alineación integral asegura una arquitectura robusta y una interfaz cohesiva, validada tanto en su estructura técnica como en su despliegue visual.

**Repository: Grotix_LandingPage**

- **Branch:** main
- **Total Commits:** 21

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 68a0001 | Initial commit | Inicialización del repositorio y configuración de entorno de desarrollo. | Apr 12, 2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 9cc00c2 | Update in README description | Actualización de la documentación técnica inicial en el archivo README. | Apr 12, 2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 7ea25b1 | Creation of directories and basic files | Configuración de la estructura de carpetas y archivos base del proyecto HTML/CSS. | Apr 12, 2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | fcd3451 | Creation of meta tags and description | Optimización SEO mediante la adición de etiquetas meta y descripciones para motores de búsqueda. | Apr 12, 2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | ca43e6a | Content of variables.css | Definición de la paleta de colores y variables globales de diseño (estilos corporativos). | Apr 12, 2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 173507d | Header and Navigation implementation | Desarrollo funcional de la barra de navegación y el menú principal. | Apr 12, 2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 3b71bf4 | Hero section implementation | Implementación de la sección principal (Hero) con el Call to Action destacado. | Apr 12, 2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 4ef8040 | Start of Services section | Estructuración base de la sección dedicada a los servicios de monitoreo. | Apr 13, 2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 2c4d114 | Services section information | Redacción e inclusión de los detalles informativos sobre los servicios ofrecidos. | Apr 13, 2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 420b6ec | App sections | Definición y estructuración de los contenedores principales de la aplicación web. | Apr 13, 2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | e6d2662 | About us section | Desarrollo del contenido informativo sobre la misión y visión de Grotix. | Apr 13, 2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | b1387a8 | Contact us start of implementation | Maquetación inicial de la sección de contacto y canales de atención. | Apr 13, 2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | d9c3fcd | Contact form initial implementation | Creación de la estructura del formulario de contacto para la captación de leads. | May 06, 2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 3b4373d | Addition of images in Services | Carga y optimización de recursos gráficos para la sección de servicios del sistema. | May 07, 2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | b2cac17 | General Section Carousel | Implementación de componente interactivo tipo carrusel para la exhibición de contenido dinámico. | May 07, 2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | cc1100e | Sections Help and FAQ | Desarrollo de la sección de soporte al usuario y preguntas frecuentes para resolución de dudas. | May 07, 2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | ced81a7 | Social Media Links | Vinculación de los canales oficiales de redes sociales en el footer de la página. | May 08, 2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | de2d5ae | Terms and Conditions, and Privacy Policy | Inclusión de las secciones legales y políticas de privacidad para el cumplimiento normativo. | May 08, 2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 9e7fb5b | complaints Book | Adición de la sección de Libro de Reclamaciones conforme a las normativas de atención al cliente. | May 08, 2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 7c894a1 | Responsive | Implementación de Media Queries para asegurar la adaptabilidad visual en dispositivos móviles y tablets. | May 08, 2026 |
| #21 | https://github.com/CeleviGrotix/Grotix_LandingPage | main | 053d8bc | Minor change in header | Refinamiento estético y ajustes menores en los componentes de navegación del encabezado. | May 09, 2026 |

**Repository: Grotix_Web**

- **Branch:** develop
- **Total Commits:** 20

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Web | develop | 39db31b | feat(frontend): initial project setup... | Inicialización del scaffolding del proyecto frontend utilizando el build tool Vite. | May 05, 2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web | develop | 6b9e820 | feat(setup): initial project structure... | Configuración base del proyecto con Vue 3, Vite, y estándares de calidad ESLint. | May 05, 2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web | develop | 6f22924 | feat(setup): add seo tags and meta tags... | Optimización de metadatos SEO y configuración de títulos dinámicos en el Router. | May 05, 2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web | develop | 0bde5d8 | feat(dashboard): set initial config... | Configuración de la estructura de archivos y carpetas para el módulo Dashboard. | May 06, 2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web | develop | 3fd50c4 | feat(dashboard): add initial side bar layout | Maquetación base de la barra lateral de navegación con soporte para rutas anidadas. | May 06, 2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web | develop | 862520b | feat(dashboard): change sidebar color... | Actualización estética del componente Sidebar utilizando efectos de gradiente radial. | May 06, 2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web | develop | a82a728 | feat(crops): CropListView and CropDetailView | Creación de componentes para visualización masiva y específica de cultivos. | May 09, 2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web | develop | fc2e913 | feat(crops): Fix index.js | Corrección en el enrutamiento de los archivos del módulo de cultivos. | May 09, 2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web | develop | 4d8765c | feat(crops): Add post, put, delete and search crops | Integración de operaciones CRUD completas para el catálogo de cultivos. | May 09, 2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web | develop | 5c26121 | feat(agriculturists): Add ListView, DetailsView | Implementación de las vistas de lista y detalle para la gestión de usuarios agrícolas. | May 09, 2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Web | develop | 081d57c | feat(contracts): Add Register, Login, AssociationListView... | Implementación del flujo completo de autenticación y gestión de asociaciones/contratos. | May 10, 2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Web | develop | 847941b | feat(shared): add gtx card structure | Desarrollo de componente reutilizable GtxCard para estandarizar el diseño de contenedores. | May 10, 2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Web | develop | 7837c48 | feat(dashboard): add members, contracts and devices columns | Adición de columnas informativas dinámicas en la tabla principal del dashboard. | May 10, 2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Web | develop | 716b56e | feat(contracts): add terminate contract logic | Implementación de la función lógica para la finalización de contratos desde la UI. | May 10, 2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Web | develop | 17e9f03 | feat(agriculturist): add agriculturists view | Creación del módulo y vista para la gestión de perfiles de agricultores. | May 10, 2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Web | develop | 24743d2 | Dashboard improvement | Mejora en la disposición de widgets y visualización de datos en el panel principal. | May 10, 2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Web | develop | c803e9b | Searchview small improvement | Optimización de la reactividad en el componente SearchView para una respuesta más fluida. | May 10, 2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_Web | develop | ad3e616 | Changes in design | Ajustes de CSS dinámico y mejora en la paleta de colores de la interfaz administrativa. | May 10, 2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_Web | develop | 6cb8be1 | Fixing small detail in search | Refactorización menor en la lógica de filtrado del componente de búsqueda global. | May 10, 2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_Web | develop | 97c89f4 | Updating local version | Sincronización de dependencias y actualización de entorno local de desarrollo. | May 10, 2026 |

**Repository: Grotix_Web_Services**

- **Branch:** develop
- **Total Commits:** 23

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 168bda4 | Initial commit | Inicialización de la solución y configuración de los proyectos base de .NET Core. | May 04, 2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 752d0da | Add user | Implementación base de la entidad User y su repositorio correspondiente. | May 04, 2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 2d49f88 | Fix registration | Resolución de conflictos en la lógica de persistencia del registro de usuarios. | May 05, 2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d56e69a | Add Cultivation Area setup | Configuración inicial y estructuración del microservicio CultivationArea. | May 05, 2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 236ae1f | Add health checks | Implementación de servicios de monitoreo de salud (Liveness/Readiness) para los microservicios. | May 05, 2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 88e6d1e | Add EF Core initial migration | Generación del esquema inicial de base de datos utilizando migraciones de Entity Framework Core. | May 05, 2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | c6ccea4 | Fix contract endpoints | Corrección de errores en las rutas de acceso a los servicios de gestión de contratos. | May 05, 2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 5fb283b | Update staff aggregate | Modificación del agregado Staff para incluir datos de acceso y roles técnicos. | May 05, 2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 137225b | Seed default roles in migration | Configuración de la semilla de datos (seeding) para roles predeterminados mediante EF Core. | May 05, 2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 4de07d8 | Migrate monolith architecture to microservices | Reestructuración de la solución para transicionar de una arquitectura monolítica a microservicios. | May 09, 2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 91e3c21 | Update roles and permissions | Actualización de la matriz de permisos y roles (RBAC) en el microservicio IAM. | May 09, 2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 946c67f | Add endpoint to get farmer users | Desarrollo de servicio de consulta de perfiles con rol de agricultor. | May 09, 2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | ca64a1e | Add credentials for registration | Adición de campos de seguridad y credenciales para el proceso de creación de identidades. | May 09, 2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 61fa9b6 | Update data types | Ajuste y normalización de tipos de datos en los esquemas de la base de datos relacional. | May 09, 2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | a1c386c | Add imageurl to crop | Extensión del modelo de dominio de cultivos para soportar URLs de recursos gráficos. | May 09, 2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d59aa07 | Add crud op to crop | Implementación de las operaciones CRUD (Crear, Leer, Actualizar, Borrar) para el catálogo de cultivos. | May 09, 2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | f74ec53 | Add user management endpoints | Implementación de servicios para la administración de cuentas y asignación de roles. | May 10, 2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 566d173 | Update user registration logic | Refactorización del flujo de registro para incluir validaciones de tokens de invitación. | May 10, 2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 857e51a | Merge branch 'feat/profile' into develop | Integración de la rama de características de perfiles en la rama principal de desarrollo. | May 10, 2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | ea18568 | Add Azure MySQL connection config... | Configuración de cadenas de conexión para bases de datos Azure MySQL en el entorno de desarrollo local. | May 10, 2026 |
| #21 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 275d401 | Point API gateway profiles cluster to Azure Profiles.Api | Reconfiguración del API Gateway (Ocelot) para enrutar el tráfico del clúster hacia la instancia de Azure. | May 10, 2026 |
| #22 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | e90714b | add endpoints | Exposición de nuevos puntos de enlace REST para la gestión de recursos institucionales. | May 10, 2026 |
| #23 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 72c8820 | add contract edit and termination logic | Implementación de la lógica de negocio para la edición y finalización de contratos de servicio en Profiles.Api. | May 10, 2026 |

#### 6.2.1.5. Testing Suite Evidence for Sprint Review

Durante este Sprint se implementó una suite de pruebas automatizadas para el backend de Grotix, organizada en tres niveles.

En primer lugar, se desarrollaron **26 unit tests** distribuidos en dos archivos: `ValueObjectsTests.cs`, que valida el comportamiento de los value objects `UserEmail` y `UserPhone` ante entradas válidas e inválidas, y `DomainTests.cs`, que verifica las reglas de negocio de los agregados `Farm`, `Zone`, `Crop`, `Contract` e `InviteTokenHasher`.

En segundo lugar, se implementaron **10 integration tests** en `IntegrationTests.cs`, los cuales prueban el flujo completo de `FarmCommandService` y `ZoneCommandService` contra una base de datos en memoria (`EF Core InMemory`), cubriendo escenarios de creación, actualización y validación de errores sin dependencia de infraestructura real.

Finalmente, se elaboraron **18 archivos `.feature`** escritos en lenguaje Gherkin bajo el enfoque BDD, uno por cada User Story y Technical Story del Sprint (`US01`–`US09`, `TS01`, `TS03`, `TS05`–`TS06`, `TS08`–`TS10`, `TS13`–`TS14`), describiendo los escenarios de aceptación que guiarán la validación funcional de la plataforma. Todos los tests unitarios e integrales se encuentran en la rama `test/sprint-testing-suite` del repositorio backend y pasan exitosamente con **0 fallos**.

**Link del repositorio de Web Services (rama de testing):**  
https://github.com/CeleviGrotix/Grotix_Web_Services/commits/test/sprint-testing-suite/

**Commits de la suite de testing**

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | 9c1067f2f6c309571482748b970245d4152b75cf | feat(setup): add initial testing suite | 10/05/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | 3aa4b17ef6258fef870c1fc4119b094a0876379a | feat(test): add value object tests | 10/05/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | ba650793507745ae5ca9aadc8037bd008d3981ed | feat(test): add unit test for domain aggregates | 10/05/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | 1fd4232bd5205144d62f1f11666a14c0edb83e31 | feat(test): add user stories bdd tests | 10/05/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | a045e00647462ad071e30cc12aff6708e50d4d89 | feat(test): add technical stories bdd tests | 10/05/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-testing-suite | test/sprint-testing-suite | 17f8fa0802f3745d56874d863dc0b8d4a179d1fa | feat(test): add 10 integration tests for FarmCommandService and ZoneCommandService with InMemory DB | 10/05/2026 |

**Control de Casos de Prueba - Pruebas Unitarias (Domain & Value Objects)**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|---|---|---|---|---|---|---|
| TC-U01 | Farm (Aggregate) | Unitaria (xUnit) | Construcción válida de un objeto de tipo Granja. | userId: 1, name: "Granja Los Andes", location: "Cusco, Perú" | Propiedades asignadas correctamente sin errores. | Pasó |
| TC-U02 | Farm (Aggregate) | Unitaria (xUnit) | Intento de instanciación con un nombre vacío o con espacios. | userId: 1, name: " ", location: "Cusco, Perú" | Excepción `ArgumentException` es lanzada. | Pasó |
| TC-U03 | Contract (Aggregate) | Unitaria (xUnit) | Intento de creación de contrato con fecha de fin anterior a la de inicio. | start: Today, end: Yesterday, status: Active, totalAmount: 1500f | Excepción `ArgumentException` es lanzada. | Pasó |
| TC-U04 | Crop (Aggregate) | Unitaria (xUnit) | Intento de registro de cultivo con tiempo de estrés negativo. | commonName: "Papa", maxStressTime: -1 | Excepción `ArgumentException` es lanzada. | Pasó |
| TC-U05 | UserEmail (Value Object) | Unitaria (xUnit) | Validación de cadena de texto que no cumple con estructura de correo electrónico. | raw: "noesuncorreo" o "@dominio.com" | Excepción `ArgumentException` es lanzada. | Pasó |
| TC-U06 | UserPhone (Value Object) | Unitaria (xUnit) | Normalización automática de espacios en blanco en el número telefónico. | raw: "+51 999 888 777" | Cadena limpia y normalizada: "+51999888777". | Pasó |

**Control de Casos de Prueba - Pruebas de Integración (Service ➔ Repository ➔ DB InMemory)**

| Test Case ID | Servicio / Flujo Evaluado | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|---|---|---|---|---|---|---|
| TC-I01 | FarmCommandService | Integración (InMemory) | Persistencia correcta de una nueva granja asociada a un usuario existente. | UserId válido, Name: "Granja Andina", Location: "Cusco" | El objeto se almacena con un ID autogenerado mayor a 0 y los datos coinciden en BD. | Pasó |
| TC-I02 | FarmCommandService | Integración (InMemory) | Intento de guardar una granja con nombre en blanco mediante comando. | UserId válido, Name: " ", Location: "Cusco" | El servicio detiene la operación y lanza un `ArgumentException`. No se guarda nada. | Pasó |
| TC-I03 | FarmCommandService | Integración (InMemory) | Actualización completa de datos de una granja previamente registrada. | FarmId existente, NewName: "Nombre Nuevo", NewLocation: "Arequipa" | Los cambios se reflejan inmediatamente en la consulta física del contexto de base de datos. | Pasó |
| TC-I04 | FarmCommandService | Integración (InMemory) | Intento de actualizar una granja usando un identificador inexistente. | FarmId: 99999, Name: "Nombre", Location: "Lugar" | El sistema lanza un `KeyNotFoundException` al no mapear el ID en los registros. | Pasó |
| TC-I05 | ZoneCommandService | Integración (InMemory) | Registro exitoso de una zona agrícola vinculando una granja y un cultivo real. | FarmId válido, CropId válido, Coords: -12.046, -77.042, Phase: "Germinación" | La zona es guardada y vinculada correctamente en el esquema relacional de la BD. | Pasó |
| TC-I06 | ZoneCommandService | Integración (InMemory) | Intento de registrar una zona asociándole un código de cultivo que no existe. | FarmId válido, CropId: 99999, Coords: -12.046, -77.042, Phase: "Germinación" | La integridad referencial simulada falla y el servicio arroja un `ArgumentException`. | Pasó |
| TC-I07 | ZoneCommandService | Integración (InMemory) | Intento de actualización de coordenadas enviando parámetros incompletos (solo latitud). | ZoneId existente, Latitude: -13.0, Longitude: null | El validador del servicio detecta la inconsistencia geográfica y lanza `ArgumentException`. | Pasó |

**Control de Casos de Prueba - Pruebas de Aceptación (User Stories & Technical Stories Coverage)**

| Test Case ID | ID Historia (US/TS) | Tipo de Prueba | Descripción del Escenario (Escenario de Gherkin) | Acción / Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|---|---|---|---|---|---|---|
| TC-A01 | US01 | Aceptación (UI) | Explicación clara de la propuesta de valor y los 3 pilares clave del servicio en la Landing Page. | Cargar la página inicial en el navegador y desplazarse a la sección de servicios. | Se visualiza el Headline y los tres bloques: "Monitoreo por sensores", "Reconocimiento de germinación con IA" y "Riego automatizado". | Pasó |
| TC-A02 | US02 | Aceptación (UI) | Redirección correcta y operativa hacia las tiendas oficiales de apps móviles sin enlaces rotos. | Hacer clic en las insignias de "App Store", "Google Play" o el botón "GET NOW!". | El navegador redirige al entorno oficial de descarga correspondiente al sistema operativo del smartphone, sin errores 404. | Pasó |
| TC-A03 | US03 | Aceptación (UI) | Visibilidad del CTA principal en Hero Section y persistencia del CTA secundario en la barra superior. | Hacer scroll vertical descendente a lo largo de toda la Landing Page. | El botón principal "Comienza ahora" destaca en el Hero y la barra de navegación se mantiene fija (sticky) arriba con su CTA visible. | Pasó |
| TC-A04 | US04 | Aceptación (UI) | Despliegue de la sección "Nosotros" (misión, visión y equipo) controlando fallos de red con placeholders. | Forzar latencia alta en imágenes de perfil de los integrantes del equipo Grotix. | La app renderiza avatares genéricos temporales que muestran el nombre y cargo del integrante; la sección mantiene su estructura limpia. | Pasó |
| TC-A05 | US05 | Aceptación (UI) | Validación de campos obligatorios y formato de correo electrónico en formulario de contacto. | Enviar formulario con campo vacío o con formato de email inválido (ej: agricultor_sin_arroba.com). | El frontend intercepta el envío, impide la petición al servidor, resalta los inputs en rojo y muestra mensajes de error descriptivos. | Pasó |
| TC-A06 | US06 | Aceptación (UI) | Operatividad de los accesos a redes sociales corporativas configurados en el pie de página. | Hacer clic en los iconos SVG de Instagram, LinkedIn y Facebook en el footer de la página. | Los perfiles oficiales de Grotix se abren en una pestaña nueva del navegador (`target="_blank"`) manteniendo la Landing Page activa en la pestaña previa. | Pasó |
| TC-A07 | US07 | Aceptación (UI) | Navegación simplificada mediante scroll suave, menú hamburguesa interactivo y resaltado dinámico (ScrollSpy). | Seleccionar una sección del menú en mobile o hacer scroll interactivo entre bloques. | Las transiciones son fluidas, el menú móvil se cierra automáticamente tras elegir un enlace y el menú activo cambia de estilo visual. | Pasó |
| TC-A08 | US08 | Aceptación (UI) | Consistencia de la identidad visual de la startup según la paleta de colores y escala tipográfica. | Renderizar la interfaz en el navegador y auditar los elementos contra variables CSS de colores y pesos (H1-H6). | La jerarquía visual se mantiene coherente en todas las vistas y los contrastes de color cumplen con los estándares de accesibilidad WCAG. | Pasó |
| TC-A09 | US09 | Aceptación (UI) | Optimización del rendimiento web mediante compresión de assets (WebP) y carga diferida (Lazy Loading). | Realizar la carga inicial del sitio bajo una conexión inestable o de datos móviles. | El tiempo de despliegue del contenido crítico en el Hero es inferior a 1.5s; las imágenes inferiores usan `loading="lazy"` y cargan al hacer scroll. | Pasó |
| TC-A10 | TS01 | Aceptación (Backend) | Monitoreo automático de salud de la API y verificación del estado de dependencias críticas de infraestructura. | Realizar peticiones HTTP GET secuenciales a los endpoints `/health/live` y `/health/ready`. | `/live` retorna 200 OK (servidor activo). `/ready` comprueba MySQL/TimescaleDB y retorna 200 OK si están arriba, o 503 si la BD está caída. | Pasó |
| TC-A11 | TS03 | Aceptación (Backend) | Desacoplamiento de la persistencia arquitectónica utilizando inyección de dependencias (IoC) y DTOs estables. | Modificar el motor de persistencia en `Program.cs` o alterar el esquema de tablas en Entity Framework Core. | El controlador sigue funcionando sin cambios al interactuar solo con la interfaz (`ITelemetryRepository`) y las respuestas usan DTOs estables. | Pasó |
| TC-A12 | TS05 | Aceptación (Backend) | Emisión de JSON Web Tokens (JWT) seguros mediante credenciales válidas y protección estricta CORS. | Consumir el endpoint POST `/api/v1/auth/sign-in` con datos válidos desde un dominio autorizado. | El backend genera un token JWT firmado con algoritmo BCrypt para contraseñas, tiempo de expiración y claims; bloquea accesos externos por CORS. | Pasó |
| TC-A13 | TS06 | Aceptación (QA) | Ejecución aislada de la suite de pruebas unitarias/integración en local y automatización en pipeline CI. | Ejecutar el comando `dotnet test` o subir un commit con errores al repositorio remoto. | Los algoritmos se validan rápidamente de forma aislada usando Mocks; si un test falla, el pipeline de Integración Continua bloquea el deploy. | Pasó |
| TC-A14 | TS14 | Aceptación (UI) | Control de acceso seguro al Portal de Administración mediante Auth Guards en las rutas del cliente. | Intentar ingresar manualmente a una URL privada del portal administrativo sin haber iniciado sesión. | El enrutador de Vue intercepta la navegación debido a la ausencia de un JWT válido y redirige inmediatamente al usuario a la vista de Login. | Pasó |
| TC-A15 | TS08 | Aceptación (UI) | Visualización centralizada de indicadores clave (KPIs) de negocio y alertas críticas en el Dashboard. | Iniciar sesión como Administrador y entrar al panel principal de control. | El panel renderiza tarjetas dinámicas con el número de clientes, contratos y dispositivos IoT, resaltando en rojo alertas críticas o contratos vencidos. | Pasó |
| TC-A16 | TS10 | Aceptación (Ecosistema) | Registro de contratos comerciales externos en campo y aprovisionamiento automático de servicios IoT. | Enviar un formulario con fechas, planes y cliente mediante Vue App hacia el backend POST `/api/v1/contracts`. | El contrato se crea con estado "Activo", se genera el Token de invitación para el administrador de la granja y se habilitan los servicios IoT. | Pasó |
| TC-A17 | TS13 | Aceptación (UI) | Consulta ágil del catálogo botánico y modificación dinámica de umbrales óptimos mediante sliders. | Buscar una especie por nombre y editar su rango óptimo de humedad usando el control deslizante de la UI. | El catálogo filtra dinámicamente, actualiza los valores biológicos en base de datos y propaga los nuevos parámetros a los dispositivos IoT asociados. | Pasó |
| TC-A18 | TS09 | Aceptación (UI) | Búsqueda, filtrado en tiempo real y gestión integral del directorio de clientes agricultores. | Digitar un criterio de búsqueda en la barra de perfiles agrícolas dentro de la interfaz administrativa en Vue. | Los registros se filtran al instante en pantalla mostrando nombres, ubicaciones y un indicador semafórico del estado contractual del usuario. | Pasó |

**Evidencia Visual de Ejecución de la Suite**

<img src="https://imgur.com/6xsktt1.png">

#### 6.2.1.6. Execution Evidence for Sprint Review
Durante el presente sprint se consolidó la exposición y consumo de los Web Services REST del backend Grotix, con especial énfasis en el flujo de identidad y perfiles (autenticación JWT, roles, asociaciones, contratos comerciales e invitaciones con correo vinculado) y en la capa de área de cultivo (fincas, zonas y catálogo de cultivos). Las pruebas de ejecución se realizaron con Postman contra los hosts locales de Profiles.Api y CultivationArea.Api, verificando códigos HTTP, cuerpos JSON y reglas de autorización alineadas con la documentación OpenAPI/Swagger.

De manera paralela, se avanzó en el desarrollo del frontend con la implementación de la vista de administrador, la cual abarca la gestión integral de perfiles de usuario, así como la creación y administración de asociaciones, contratos comerciales, invitaciones y cultivos. Esta vista constituye el punto central de control para los usuarios con rol administrador dentro de la plataforma Grotix.

**POST**

https://grotixgateway-fyevgmh2cvc4ghgv.chilecentral-01.azurewebsites.net/api/v1/auth/sign-in/ 

<img src="https://imgur.com/yFIGrWX.png">

Este endpoint permite el inicio de sesión de un usuario, devuelve el token que permite acceso a los demás endpoints.

**GET**

https://grotixgateway-fyevgmh2cvc4ghgv.chilecentral-01.azurewebsites.net/api/v1/catalog/crops

<img src="https://imgur.com/HtPKt6D.png">

Endpoint para obtener información de los diversos tipos de cultivo, con información clave sobre sus parámtros óptimos

**POST**

https://grotixgateway-fyevgmh2cvc4ghgv.chilecentral-01.azurewebsites.net/api/v1/associations/1/invites

<img src="https://imgur.com/oyua2Sz.png">

Este endpoint permite crear un token de invitación que permite a un nuevo usuario registrarse en la aplicación. Este tiene un correo como objetivo y se predefine el rol y asociación a la que pertenecerá el nuevo usuario.

**POST**

https://grotixgateway-fyevgmh2cvc4ghgv.chilecentral-01.azurewebsites.net/api/v1/contracts/Este endpoint permite la creación de un contrato con una asociación. Al crearse el contrato, se genera una invitación al representante de la granja para recibir sus permisos como administrador de la granja.

<img src="https://imgur.com/2vyhZmP.png">

Video de explicación: 

https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAX8Qlo6yS-TYuInq-CellWAQNakaunluneG2IIEWIgkZE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NXcnhZ


#### 6.2.1.7. Services Documentation Evidence for Sprint Review

Durante el presente ciclo de desarrollo (Sprint), se ha fortalecido la arquitectura del ecosistema Grotix mediante la estandarización y documentación explícita de los servicios REST utilizando el estándar OpenAPI 3.0 (Swagger). El esfuerzo técnico se concentró estratégicamente en la maduración del microservicio `Profiles.Api`, componente crítico encargado de la gobernanza de identidades, jerarquías organizacionales y gestión contractual.

En paralelo, se consolidaron las capacidades operativas del microservicio `CultivationArea.Api`, asegurando la persistencia y gestión del conocimiento agronómico.

Un hito arquitectónico relevante de este sprint ha sido la implementación e integración de un **API Gateway**. Esta capa de abstracción centraliza el tráfico, optimiza el enrutamiento de peticiones hacia los distintos microservicios y garantiza un punto único de entrada seguro, mejorando significativamente la observabilidad y el control de los servicios. La siguiente tabla detalla los endpoints desarrollados, documentados y validados durante este periodo.

**Matriz de endpoints documentados**

| Microservicio | Método | Ruta relativa | Autorización | Parámetros / cuerpo | Respuesta de éxito y notas |
|---|---|---|---|---|---|
| Profiles.Api | POST | `/api/v1/auth/register` | Anónimo | `email`, `password`, `inviteToken` | `201 Created`. Registro vía invitación. |
| Profiles.Api | POST | `/api/v1/auth/sign-in` | Anónimo | `email`, `password` | `200 OK`. Devuelve JWT y `LoginResponse`. |
| Profiles.Api | POST | `/api/v1/auth/sign-out` | Bearer JWT | — | `204 No Content`. |
| Profiles.Api | GET | `/api/v1/roles` | Anónimo | — | `200 OK`. Lista de roles: `id`, `name`, `desc`. |
| Profiles.Api | GET | `/api/v1/associations` | Admin, Staff | — | `200 OK`. Lista de asociaciones. |
| Profiles.Api | POST | `/api/v1/associations` | Admin, Staff | `name`, `email` | `201 Created`. |
| Profiles.Api | PATCH | `/api/v1/associations/{id}` | Solo Admin | Path: `id`. JSON: `name`, `email`. | `200 OK`. Actualización parcial. |
| Profiles.Api | POST | `/api/v1/admin/users` | Solo Admin | `email`, `roleId`, `assocId`, etc. | `201 Created`. Creación directa por admin. |
| Profiles.Api | PATCH | `/api/v1/admin/users/{id}` | Solo Admin | Path: `userId`. JSON administrativo. | `200 OK`. Edición parcial. |
| Profiles.Api | GET | `/api/v1/contracts` | Bearer JWT | — | `200 OK`. Lista según jerarquía. |
| Profiles.Api | GET | `/api/v1/contracts/{id}` | Bearer JWT | Path: `contractId`. | `200 OK`. Detalle de contrato. |
| Profiles.Api | POST | `/api/v1/contracts` | Admin, Staff | `associationId`, `totalAmount`, etc. | `201 Created`. Genera token `OrgAdmin`. |
| Profiles.Api | PATCH | `/api/v1/contracts/{id}` | Admin, Staff | Path: `id`. JSON: `status`, `dates`, etc. | `200 OK`. Modificación de contrato. |
| Profiles.Api | DELETE | `/api/v1/contracts/{id}` | Solo Admin | Path: `id`. | `204 No Content`. Borrado físico. |
| Profiles.Api | POST | `/api/v1/associations/{id}/invites` | Bearer JWT | Path: `id`. JSON: `email`, `roleId`. | `200 OK`. Genera token de invitación. |
| Profiles.Api | GET | `/api/v1/search` | Bearer JWT | Query: `q` (texto). | `200 OK`. Búsqueda global agregada. |
| Profiles.Api | GET | `/api/v1/users` | Bearer JWT | — | `200 OK`. Lista agricultores (Profiles). |
| Profiles.Api | GET | `/api/v1/users/{id}` | Bearer JWT | Path: `userId`. | `200 OK`. Recurso de usuario específico. |
| Profiles.Api | GET | `/api/v1/profile/me` | Bearer JWT | — | `200 OK`. Mi perfil (`UserResource`). |
| Profiles.Api | GET | `/api/v1/profile/me/staff` | Bearer JWT | — | `200 OK`. Datos técnicos si es staff. |
| Profiles.Api | PATCH | `/api/v1/profile/{id}` | Bearer JWT | Path: `id`. JSON: `name`, `phone`, etc. | `200 OK`. Actualización de perfil propio. |
| Profiles.Api | PATCH | `/api/v1/profile/{id}/preferences` | Bearer JWT | Path: `id`. JSON: `push`, `email` (bool). | `200 OK`. Ajustes de notificaciones. |
| Profiles.Api | PATCH | `/api/v1/profile/{id}/role` | Solo Admin | Path: `id`. JSON: `roleId`. | `200 OK`. Cambio de rol forzado. |
| Profiles.Api | GET | `/api/v1/staff` | Solo Admin | — | `200 OK`. Lista de staff técnico. |
| Profiles.Api | POST | `/api/v1/staff` | Solo Admin | `userId`, `technicalRole`. | `201 Created`. Promoción a staff. |
| Profiles.Api | PATCH | `/api/v1/staff/{id}` | Solo Admin | Path: `id`. `technicalRole`, `isActive`. | `200 OK`. Edición de staff. |
| Shared | GET | `/live` | Anónimo | — | `200 OK`. Liveness probe. |
| Shared | GET | `/ready/core` | Anónimo | — | `200 OK`. Health Check MySQL. |
| Shared | GET | `/ready/telemetry` | Anónimo | — | `200 OK`. Health Check TimescaleDB. |
| Cultivation.Api | GET | `/api/v1/farms` | Bearer JWT | — | `200 OK`. Granjas del agricultor. |
| Cultivation.Api | POST | `/api/v1/farms` | Bearer JWT | `name`, `location`. | `201 Created`. |
| Cultivation.Api | PATCH | `/api/v1/farms/{id}` | Bearer JWT | Path: `id`. `name`, `location`. | `200 OK`. Edición de granja. |
| Cultivation.Api | GET | `/api/v1/farms/{id}/zones` | Bearer JWT | Path: `id`. | `200 OK`. Lista de zonas de la granja. |
| Cultivation.Api | POST | `/api/v1/farms/{id}/zones` | Bearer JWT | Path: `id`. JSON: `cropId`, `coords`. | `201 Created`. Nueva zona de cultivo. |
| Cultivation.Api | GET | `/api/v1/zones/{id}` | Bearer JWT | Path: `zoneId`. | `200 OK`. Detalle de zona. |
| Cultivation.Api | PATCH | `/api/v1/zones/{id}` | Bearer JWT | Path: `id`. `cropId`, `phase`, `stats`. | `200 OK`. Edición de zona/fase. |
| Cultivation.Api | GET | `/api/v1/catalog/crops` | Bearer JWT | — | `200 OK`. Catálogo completo de cultivos. |
| Cultivation.Api | POST | `/api/v1/catalog/crops` | Admin, Staff | `commonName`, `scientificName`, `stats`. | `201 Created`. |
| Cultivation.Api | PUT | `/api/v1/catalog/crops/{id}` | Admin, Staff | Path: `id`. Update de datos de cultivo. | `200 OK`. Reemplazo completo. |
| Cultivation.Api | DELETE | `/api/v1/catalog/crops/{id}` | Admin, Staff | Path: `id`. | `204 No Content`. Borrado de catálogo. |

**Evidencias de Validación Funcional (Core Endpoints)**

Con el objetivo de verificar la integridad y el comportamiento esperado de la lógica de negocio, se han realizado pruebas de ejecución directa sobre los servicios utilizando la interfaz interactiva de Swagger. Las capturas presentadas a continuación no solo documentan la sintaxis de las llamadas, sino que constituyen una evidencia técnica de la interoperabilidad entre los componentes de software y sus respectivas capas de persistencia.

En esta sección se destacan los procesos **Core** del sistema, incluyendo la generación de seguridad mediante tokens JWT, la automatización de flujos de invitación vinculados a contratos y la validación de umbrales técnicos en el catálogo de cultivos. Cada imagen representa una transacción exitosa que confirma que los microservicios están operativos, autorizados y listos para su integración con la capa de frontend.

---

**POST `/api/v1/auth/sign-in`**

Módulo de autenticación centralizado que valida las credenciales del usuario contra el microservicio de IAM (*Identity and Access Management*). Tras una validación exitosa, el servicio emite un JSON Web Token (JWT) firmado, el cual encapsula los *claims* de identidad y el rol asignado.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Content-Type | String | Tipo de contenido del cuerpo de la petición. Debe ser `application/json`. |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| email | String | Correo electrónico registrado de la cuenta de usuario. |
| password | String | Contraseña de acceso en texto plano. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
  "email": "germinacion@grotix.pe",
  "password": "PasswordSecure123!"
}
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `200 OK`**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| identityId | Integer | Identificador único global de la identidad dentro del microservicio IAM. |
| email | String | Correo electrónico asociado a la identidad autenticada. |
| success | Boolean | Flag booleano que indica el éxito de la operación (`true`). |
| message | String | Mensaje descriptivo con el estado final del proceso. |
| token | String | JSON Web Token (JWT) firmado para la protección de recursos protegidos. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
  "identityId": 104,
  "email": "germinacion@grotix.pe",
  "success": true,
  "message": "Autenticación completada exitosamente.",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOiIxMDQiLCJyb2xlIjoiRmFybWVyIn0..."
}
```

**Error: Código `401 Unauthorized`**

```json
{
  "status": 401,
  "message": "NOT_AUTHORIZED: Las credenciales ingresadas son incorrectas o la cuenta no existe."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/nV0Ze0P.png">

---

**POST `/api/v1/associations`**

Servicio encargado de la creación de agregados de tipo **Asociación**. Este componente actúa como el nivel jerárquico superior dentro del dominio de perfiles, permitiendo agrupar agricultores, activos físicos y contratos bajo una misma entidad legal.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Content-Type | String | Tipo de contenido del cuerpo de la petición. Debe ser `application/json`. |
| Authorization | String | Token de autenticación obligatorio: `Bearer [token_jwt]`. |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| name | String | Nombre oficial o razón social de la asociación agraria. No puede ser vacío. |
| contactEmail | String | Correo electrónico de contacto principal y notificaciones de la asociación. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
  "name": "Cooperativa Agraria Valle Sagrado",
  "contactEmail": "contacto@vallesagrado.pe"
}
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `201 Created`**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| id | Integer | Identificador único asignado automáticamente por el servidor en la base de datos. |
| name | String | Nombre confirmado de la asociación agraria, limpio de espacios en los extremos. |
| contactEmail | String | Cadena con el correo electrónico de contacto persistido de forma segura. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
  "id": 8,
  "name": "Cooperativa Agraria Valle Sagrado",
  "contactEmail": "contacto@vallesagrado.pe"
}
```

**Error: Código `400 Bad Request`**

```json
{
  "status": 400,
  "message": "BAD_REQUEST: El nombre de la asociación no puede estar vacío."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/YVhWQUe.png">

---

**GET `/api/v1/contracts`**

Servicio de exposición de datos encargado de la recuperación masiva de registros contractuales persistidos en el microservicio de Profiles. Este endpoint implementa un patrón de filtrado por contexto de seguridad (*Tenant Scoping*); mientras que los roles administrativos (`Admin`, `Staff`) acceden a la totalidad de la base de datos contractual, los roles de Gestión Organizacional (`User Admin`) reciben una respuesta filtrada automáticamente por su identificador de asociación vinculado al token JWT.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Authorization | String | Token de autenticación requerido con el formato obligatorio: `Bearer [token_jwt]`. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros en la URL ni cuerpo de petición para su ejecución base.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/contracts HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `200 OK`**

Retorna un arreglo JSON con la colección de contratos autorizados para el contexto del solicitante.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| contractId | Integer | Identificador único e incremental del contrato comercial generado en la base de datos. |
| associationId | Integer | Código de la asociación agraria asignada de forma fija al acuerdo. |
| startDate | String | Fecha de inicio de vigencia de las prestaciones de la plataforma (ISO-8601). |
| endDate | String | Fecha límite de caducidad y término de vigencia contractual (ISO-8601). |
| status | String | Representación textual del estado operativo del contrato, por ejemplo: `Active` o `Pending`. |
| maxZones | Integer | Límite máximo de áreas o zonas de cultivo permitidas para configuración en la app. |
| maxMicrocontrollers | Integer | Umbral físico máximo de dispositivos y hardware IoT autorizados en los nodos. |
| totalAmount | Float | Monto comercial final total pactado por la adquisición de los servicios Grotix. |
| currency | String | Denominación de la divisa monetaria utilizada para la facturación, por ejemplo: `USD`. |
| paymentFrequency | String | Modalidad periódica de cobro grabada en las reglas de negocio, por ejemplo: `Monthly`. |
| isSuspended | Boolean | Flag de control para el congelamiento inmediato de servicios IoT ante impagos. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
  {
    "contractId": 45,
    "associationId": 12,
    "startDate": "2026-05-15T00:00:00Z",
    "endDate": "2027-05-15T00:00:00Z",
    "status": "Active",
    "maxZones": 10,
    "maxMicrocontrollers": 5,
    "totalAmount": 1500.50,
    "currency": "USD",
    "paymentFrequency": "Monthly",
    "isSuspended": false
  },
  {
    "contractId": 46,
    "associationId": 12,
    "startDate": "2026-06-01T00:00:00Z",
    "endDate": "2027-06-01T00:00:00Z",
    "status": "Pending",
    "maxZones": 20,
    "maxMicrocontrollers": 10,
    "totalAmount": 3000.00,
    "currency": "USD",
    "paymentFrequency": "Annual",
    "isSuspended": false
  }
]
```

**Error: Código `401 Unauthorized`**

```json
{
  "status": 401,
  "message": "NOT_AUTHORIZED: El token de seguridad JWT ha expirado o no cuenta con los privilegios requeridos."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/eyhVzJQ.png">

---

**POST `/api/v1/contracts`**

Componente encargado de persistir la lógica comercial del sistema. Define parámetros operativos como límites de zonas, microcontroladores permitidos y vigencia temporal. Además, dispara el proceso de invitación para el rol de Administrador Organizacional.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Content-Type | String | Tipo de contenido del cuerpo de la petición. Debe ser `application/json`. |
| Authorization | String | Token de autenticación obligatorio: `Bearer [token_jwt]`. Requiere rol Admin o Staff. |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| associationId | Integer | Identificador único de la asociación agraria vinculada al nuevo contrato. |
| startDate | String | Fecha de inicio de vigencia del contrato en formato ISO-8601. |
| endDate | String | Fecha límite de caducidad o término del contrato en formato ISO-8601. |
| status | Integer | Enumerador numérico del estado inicial del contrato, por ejemplo: `1 = Active`, `2 = Pending`. |
| maxZones | Integer | Cantidad máxima de áreas o zonas de cultivo asignadas para configuración en la app. |
| maxMicrocontrollers | Integer | Umbral físico de microcontroladores y dispositivos IoT autorizados para transmitir. |
| totalAmount | Float | Costo comercial total acordado por las prestaciones de la plataforma Grotix. |
| currency | Integer | Enumerador numérico de la divisa de facturación, por ejemplo: `1 = USD`, `2 = PEN`. |
| paymentFrequency | Integer | Enumerador numérico de la periodicidad del cobro, por ejemplo: `1 = Monthly`, `2 = Annual`. |
| isSuspended | Boolean | Flag de control para congelamiento temporal de servicios en campo. Por defecto: `false`. |
| orgAdminEmail | String | Correo electrónico institucional al que se enviará la invitación de alta para el rol `user_admin`. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
  "associationId": 5,
  "startDate": "2026-06-01T00:00:00Z",
  "endDate": "2027-06-01T00:00:00Z",
  "status": 1,
  "maxZones": 12,
  "maxMicrocontrollers": 6,
  "totalAmount": 1800.00,
  "currency": 1,
  "paymentFrequency": 1,
  "isSuspended": false,
  "orgAdminEmail": "admin_cooperativa@grotix.pe"
}
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `201 Created`**

El contrato comercial ha sido registrado de forma exitosa y se ha encolado el evento de invitación para el administrador de la organización.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| contractId | Integer | Código único autogenerado por el sistema tras la persistencia relacional en base de datos. |
| associationId | Integer | Código de la asociación agraria vinculada. |
| startDate | String | Fecha de inicio validada y confirmada por el servidor backend. |
| endDate | String | Fecha de término validada y confirmada por el servidor backend. |
| status | String | Representación textual legible del estado del contrato, por ejemplo: `Active`. |
| maxZones | Integer | Capacidad total de zonas aprovisionadas para el catálogo de parcelas. |
| maxMicrocontrollers | Integer | Límite de dispositivos autorizados para enlazarse a la pasarela IoT. |
| totalAmount | Float | Monto comercial final grabado de forma segura en el agregador. |
| currency | String | Sigla textual representativa de la moneda de pago procesada, por ejemplo: `USD`. |
| paymentFrequency | String | Modalidad textual de cobro grabada en las reglas del negocio, por ejemplo: `Monthly`. |
| isSuspended | Boolean | Flag que verifica que el contrato no se encuentra suspendido en el sistema (`false`). |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
  "contractId": 89,
  "associationId": 5,
  "startDate": "2026-06-01T00:00:00Z",
  "endDate": "2027-06-01T00:00:00Z",
  "status": "Active",
  "maxZones": 12,
  "maxMicrocontrollers": 6,
  "totalAmount": 1800.00,
  "currency": "USD",
  "paymentFrequency": "Monthly",
  "isSuspended": false
}
```

**Error: Código `400 Bad Request`**

```json
{
  "status": 400,
  "message": "BAD_REQUEST: El monto total (totalAmount) no puede ser un valor negativo."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/Ie3cH17.png">

---

**GET `/api/v1/users`**

Servicio de consulta de perfiles de usuario que implementa lógica de filtrado por ámbito (*scoping*). Dependiendo de los *claims* del token JWT, el servicio limita la respuesta a los usuarios pertenecientes exclusivamente a la asociación del solicitante.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Authorization | String | Token de autenticación obligatorio: `Bearer [token_jwt]`. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros en la URL ni cuerpo de petición para su ejecución.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/users HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `200 OK`**

Retorna un arreglo JSON con los recursos de perfil (`UserResource`) mapeados desde la capa de persistencia.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| id | Integer | Identificador único del perfil de usuario dentro del microservicio de Profiles. |
| identityId | Integer | Identificador global único de la identidad vinculada dentro del microservicio IAM. |
| name | String (nullable) | Nombre completo registrado: nombres y apellidos. |
| email | String | Dirección de correo electrónico principal del usuario. |
| taxId | String (nullable) | Documento de identidad fiscal o registro tributario del agricultor. |
| phone | String (nullable) | Número telefónico o celular de contacto. |
| roleId | Integer | Identificador del rol de negocio asignado en la plataforma. |
| associationId | Integer (nullable) | Código de la asociación agraria a la que pertenece el usuario. |
| profilePicture | String (nullable) | URL de almacenamiento u objeto con la imagen de perfil cargada. |
| isActive | Boolean | Flag de control de estado que determina si el usuario está operativo. |
| preferences | Object (nullable) | Sub-recurso con los ajustes de notificaciones del usuario. |
| createdAt | String | Marca de tiempo con la fecha y hora de registro inicial (ISO-8601). |
| updatedAt | String | Marca de tiempo con la última fecha y hora de modificación del perfil (ISO-8601). |

**Estructura del Objeto Interno `preferences` (`UserPreferencesResource`)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| push | Boolean | Flag que habilita o deshabilita las notificaciones push en dispositivos móviles. |
| email | Boolean | Flag que determina si el usuario desea recibir alertas agronómicas vía correo electrónico. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
  {
    "id": 1,
    "identityId": 101,
    "name": "Carlos Mendoza Ruiz",
    "email": "carlos.mendoza@vallesagrado.pe",
    "taxId": "10456789123",
    "phone": "+51987654321",
    "roleId": 3,
    "associationId": 8,
    "profilePicture": "https://storage.grotix.pe/avatars/user-1.jpg",
    "isActive": true,
    "preferences": {
      "push": true,
      "email": false
    },
    "createdAt": "2026-05-10T14:30:00Z",
    "updatedAt": "2026-05-28T18:22:15Z"
  }
]
```

**Error: Código `401 Unauthorized`**

```json
{
  "status": 401,
  "message": "NOT_AUTHORIZED: El token de seguridad JWT proporcionado no es válido o ya ha expirado."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/rNQmFsL.png">

---

**GET `/api/v1/catalog/crops`**

Servicio de consulta masiva para el catálogo de especies. Expone los metadatos técnicos y recursos visuales necesarios para que el frontend y otros microservicios puedan referenciar cultivos válidos.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Authorization | String | Token de autenticación requerido: `Bearer [token_jwt]`. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros en la URL ni cuerpo de petición para la consulta base del catálogo.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/catalog/crops HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `200 OK`**

Retorna un arreglo JSON con el listado detallado de todos los cultivos registrados en el sistema.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| id | Integer | Identificador único del cultivo en el catálogo. |
| commonName | String | Nombre común o comercial de la especie. |
| scientificName | String | Nombre científico o taxonómico de la especie. |
| optimalTemperature | Double | Umbral óptimo de temperatura en grados Celsius (°C) para el desarrollo. |
| optimalHumidity | Double | Umbral óptimo de humedad relativa (%) requerido. |
| optimalLight | Double | Cantidad de horas de luz solar diaria recomendadas para un desarrollo eficiente. |
| maxStressTime | Integer | Tiempo máximo de tolerancia, en horas, ante condiciones fuera de los umbrales óptimos antes de registrar una alerta crítica. |
| imageUrl | String? | URL de referencia hacia el recurso visual de la especie en el almacenamiento. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
  {
    "id": 1,
    "commonName": "Tomate",
    "scientificName": "Solanum lycopersicum",
    "optimalTemperature": 22.5,
    "optimalHumidity": 75.0,
    "optimalLight": 12.0,
    "maxStressTime": 48,
    "imageUrl": "https://storage.grotix.pe/crops/tomate.jpg"
  },
  {
    "id": 2,
    "commonName": "Papa",
    "scientificName": "Solanum tuberosum",
    "optimalTemperature": 18.0,
    "optimalHumidity": 65.0,
    "optimalLight": 10.0,
    "maxStressTime": 72,
    "imageUrl": "https://storage.grotix.pe/crops/papa.jpg"
  }
]
```

**Error: Código `401 Unauthorized`**

```json
{
  "status": 401,
  "message": "NOT_AUTHORIZED: La sesión ha expirado o no se cuenta con los privilegios de acceso."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/Vb5aJDH.png">

---

**POST `/api/v1/catalog/crops`**

Módulo de gestión del conocimiento agronómico. Permite la definición de umbrales óptimos y límites de estrés para diversas especies vegetales. Estos datos actúan como la línea base para los servicios de telemetría y alerta.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| Content-Type | String | Tipo de contenido. Debe ser `application/json`. |
| Authorization | String | Token de autenticación obligatorio: `Bearer [token_jwt]`. Requiere rol Admin o Staff. |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| commonName | String | Nombre común de la especie a registrar. |
| scientificName | String | Nombre científico o taxonómico de la especie. |
| optimalTemperature | Double | Umbral de temperatura óptima en grados Celsius (°C). |
| optimalHumidity | Double | Umbral óptimo de humedad relativa (%). |
| optimalLight | Double | Horas diarias de luz solar óptimas para el cultivo. |
| maxStressTime | Integer | Límite de tolerancia en horas ante condiciones desfavorables antes de generar una alerta. |
| imageUrl | String (optional) | URL externa hacia la imagen referencial de la especie. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
  "commonName": "Tomate",
  "scientificName": "Solanum lycopersicum",
  "optimalTemperature": 22.5,
  "optimalHumidity": 75.0,
  "optimalLight": 12.0,
  "maxStressTime": 48,
  "imageUrl": "https://storage.grotix.pe/crops/tomate.jpg"
}
```

**Respuestas del Servidor (Responses)**

**Éxito: Código `201 Created`**

Se ha persistido correctamente el nuevo cultivo en el catálogo agronómico.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| id | Integer | Identificador único autogenerado en el catálogo. |
| commonName | String | Nombre común registrado. |
| scientificName | String | Nombre científico registrado. |
| optimalTemperature | Double | Temperatura óptima configurada. |
| optimalHumidity | Double | Humedad óptima configurada. |
| optimalLight | Double | Horas de luz óptimas configuradas. |
| maxStressTime | Integer | Tiempo máximo de estrés configurado. |
| imageUrl | String? | URL de imagen asociada. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
  "id": 1,
  "commonName": "Tomate",
  "scientificName": "Solanum lycopersicum",
  "optimalTemperature": 22.5,
  "optimalHumidity": 75.0,
  "optimalLight": 12.0,
  "maxStressTime": 48,
  "imageUrl": "https://storage.grotix.pe/crops/tomate.jpg"
}
```

**Error: Código `400 Bad Request`**

```json
{
  "status": 400,
  "message": "BAD_REQUEST: Los campos 'commonName' y 'scientificName' son obligatorios."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/koxpmDX.png">

#### 6.1.2.8 Software Deployment Evidence for Sprint Review

Durante el presente sprint, se llevó a cabo el despliegue de la base de datos principal del sistema en una instancia de Azure Database for MySQL – Flexible Server, haciendo uso de la suscripción Azure for Students. Esta instancia constituye el núcleo de persistencia de datos de la aplicación y fue configurada bajo el plan de capacidad con ráfaga (Burstable B1ms), garantizando un entorno estable y escalable para las etapas de desarrollo y pruebas del proyecto. 

<img src="https://imgur.com/dCXPZwy.png">

Se configuran las credenciales de acceso (usuario y contraseña) para la base de datos principal. Respecto al tipo de carga de trabajo, se seleccionó la opción Desarrollo/Pruebas, dado que el proyecto se encuentra actualmente en fase de desarrollo y esta configuración representa el menor coste operativo, siendo la más adecuada para el entorno de trabajo del equipo en esta etapa del sprint.

<img src="https://imgur.com/j9X6LBD.png">

<img src="https://imgur.com/mCfW4yj.png">

Una vez aprovisionada la instancia, se procede a actualizar la cadena de conexión en el proyecto con los datos del servidor recién creado. La contraseña de acceso se gestiona de forma segura mediante User Secrets, evitando así exponer credenciales sensibles en el repositorio. Finalmente, se ejecuta la migración de la base de datos para aplicar el esquema definido sobre la instancia remota.

<img src="https://imgur.com/hiG4i7B.png">

Para el despliegue de la API, se utilizó un App Service con sistema operativo Linux y runtime .NET 8, bajo el plan B1 de la categoría Basic, seleccionado por representar el balance óptimo entre coste y recursos disponibles para la etapa actual de desarrollo.

<img src="https://imgur.com/JAAgXD4.png">

Agregamos variables de entorno necesarias como la cadena de conexión y el tokensettings_secret.

<img src="https://imgur.com/ifT7oOd.png">

Publicamos el microservicio para linux.

<img src="https://imgur.com/ahSmjE2.png">

Quitamos la carpeta browser del publish, ya que no es necesario

<img src="https://imgur.com/IHXqPsz.png">

Se crea comprime en un zip

<img src="https://imgur.com/IzpBYLl.png">

Y se procede a deployear.

<img src="https://imgur.com/WYp4gts.png">

Probamos que el servicio funcione correctamente con el endpoint live.

<img src="https://imgur.com/M8sWisS.png">

Se realizo el mismo proceso para CultivationAreaApi y el Gateway.

<img src="https://imgur.com/U4GJTvo.png">

Por el lado de la aplicación web, se utilizó firebase para su despliegue. Se inicio con la instalacion de las herramientas en la carpeta del proyecto.

Se selecciona el proyecto de firebase y se realiza la configuración correspondiente.

<img src="https://imgur.com/cTfyDvw.png">

Por último, se genera la versión de producción del frontend con npm run build y se publica en el alojamiento web.

#### 6.2.1.9. Team Collaboration Insights during Sprint

La implementación de la plataforma Grotix se ha desarrollado bajo un marco de trabajo ágil, priorizando la integración continua y la entrega de valor incremental. El equipo, adoptó una estrategia de GitFlow para la gestión de versiones, lo que permitió el desarrollo paralelo de la Landing Page, los Web Services (.NET) y la App Web.

**Analíticos de Colaboración y Contribuciones**

A continuación, se presentan los indicadores de actividad del repositorio oficial en GitHub, los cuales reflejan la dinámica de trabajo del equipo durante el último ciclo de desarrollo.

**Github Contributors (Landing Page)**

<img src="https://imgur.com/h8VNULy.png">

**Github Contributors (Web Services)**

<img src="https://imgur.com/jLIwWeR.png">

**Github Contributors (Web App)**

<img src="https://imgur.com/UKr0srs.png">

Como se aprecia en las capturas anteriores, la carga de trabajo fue distribuida entre todos los integrantes del equipo, evidenciando una participación activa en los distintos repositorios del proyecto. Si bien no todos los miembros trabajaron en cada repositorio, cada participante contribuyó de manera significativa en uno o dos repos específicos, según las responsabilidades asignadas y el enfoque de cada módulo. Esto permitió una organización más eficiente del desarrollo, favoreciendo la especialización de tareas y una integración coordinada del sistema Grotix. 

Frecuencia de Código y Ritmo de Desarrollo
El ritmo de implementación se mantuvo constante, con un enfoque en la robustez de los Web Services como núcleo del ecosistema. 

**Github Pulse**

<img src="https://imgur.com/Yuwty5t.png">

**Participación Transversal por Producto**

|Producto|Participantes|Naturaleza de la Colaboración|
|----|----|---|
|Landing Page|Angie Yalán, Ainhoa Castillo|Diseño responsivo, maquetado de secciones y despliegue inicial. |
|Web Services|Tomio Nakamurakare, Marcelo Binda, Cassius Martel|Definición de DTOs, implementación de controladores, lógica de persistencia y seguridad.| 
|App Web|Ainhoa Castillo, Marcelo Binda, Cassius Martel|Consumo de APIs, gestión de estados, diseño de interfaz de usuario|

**Commit History (Landing Page)**

<img src="https://imgur.com/mK7hPW3.png">

**Commit History (Web Services)**

<img src="https://imgur.com/hYT40g7.png">

**Commit History (Web App)**

<img src="https://imgur.com/XTCI0Et.png">
