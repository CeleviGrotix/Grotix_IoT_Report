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
