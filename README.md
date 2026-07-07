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

---


## Project Report Collaboration Insights

Para la elaboración del presente informe, el equipo trabajó de manera colaborativa y centralizada en el repositorio Grotix_IoT_Report, alojado en la organización oficial de GitHub del equipo. Durante este proceso, cada integrante contribuyó activamente en la redacción, estructuración y revisión de los capítulos correspondientes, asegurando que el documento refleje con precisión el progreso técnico, arquitectónico y estratégico del proyecto. La gestión mediante este repositorio permitió mantener un control de versiones riguroso y una integración fluida de los aportes de todos los miembros, cuyas evidencias de participación se detallan en las métricas y analíticos de colaboración presentados a continuación.

URL del repositorio del Project Report en GitHub: https://github.com/CeleviGrotix/Grotix_IoT_Report

**AV1**

Insights:

<p align="center">
  <img src="https://imgur.com/VmVOI6K.jpg" alt="Insights Report">
</p>

Commits

<p align="center">
  <img src="https://imgur.com/3pNjury.jpg" alt="Commits Report">
</p>

**TB1**

Insights:

<p align="center">
  <img src="https://imgur.com/afcOgZW.png" alt="Commits Report">
</p>


Commits

<p align="center">
  <img src="https://imgur.com/jjjDfWc.png" alt="Commits Report">
</p>

**AV2**

Insights:

<p align="center">
  <img src="https://imgur.com/l1U0JV6.png" alt="Commits Report">
</p>


Commits

<p align="center">
  <img src="https://imgur.com/SLGwhdf.png" alt="Commits Report">
</p>

**TB2**

Insights:

<p align="center">
  <img src="https://imgur.com/E072LUs.png" alt="Commits Report">
</p>


Commits

<p align="center">
  <img src="https://imgur.com/TaWS29a.png" alt="Commits Report">
</p>

---

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
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño de entrevistas](#631-diseño-de-entrevistas)
    - [6.3.2. Registro de entrevistas](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  - [6.4. Video About-the-Product](#64-video-about-the-product)
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
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Binda Arbañil, Marcelo Alejandro**<br>**AV1**<br>Desempeñó un rol de liderazgo técnico compartido, sincronizando los requerimientos de hardware con los modelos C4 y la topología IoT estructural.<br>**TP**<br>Articuló el trabajo de integración entre las áreas de hardware y software, mitigando fricciones técnicas en mesas de discusión colectivas.<br>**AV2**<br>Lideró el desarrollo frontend de la aplicación web e integró las reglas de inferencia visual en el Bounded Context de Crop Analysis.<br>**TF**<br>Desempeñó un rol de liderazgo técnico integrador a lo largo del proyecto, logrando sincronizar las restricciones del hardware IoT con los modelos arquitectónicos C4. Su dirección en el desarrollo frontend de la aplicación web y la integración del Bounded Context de Crop Analysis evidencian su capacidad para articular el trabajo entre distintas capas del software, mitigando fricciones técnicas mediante mesas de discusión colectivas que fortalecieron la cohesión del equipo.<br><br>**Castillo Garay, Ainhoa Lucía**<br>**AV1**<br>Dirigió de manera conjunta la delimitación estratégica de los Bounded Contexts aplicando principios de Domain-Driven Design (DDD).<br>**TP**<br>Guió la transición práctica de los modelos estructurales hacia el código fuente de los microservicios core (Profiles y Cultivation Area).<br>**AV2**<br>Lideró el desarrollo móvil en Flutter, implementando la lógica de autenticación JWT, flujo de pantallas y consumo de servicios cloud.<br>**TF**<br>Dirigió de manera conjunta la estrategia arquitectónica aplicando principios de Domain-Driven Design (DDD) para delimitar los Bounded Contexts. Su liderazgo fue fundamental durante la transición de los modelos estructurales hacia la implementación física, asumiendo la dirección del desarrollo móvil multiplataforma en Flutter, donde coordinó exitosamente la integración de flujos de autenticación y el consumo reactivo de servicios cloud junto al equipo de backend.<br><br>**Martel Andrade, Cassius Estefano**<br>**AV1**<br>Fomentó canales de comunicación equitativa durante el modelado inicial del dominio en las sesiones grupales de EventStorming.<br>**TP**<br>Facilitó las dinámicas de sincronización del equipo, distribuyendo de forma eficiente responsabilidades según áreas de especialidad.<br>**AV2**<br>Coordinó la evolución de la arquitectura del sistema a través de la ejecución y documentación de las iteraciones de desarrollo.<br>**TF**<br>Ejerció un liderazgo clave al fomentar canales de comunicación equitativa desde las sesiones iniciales de EventStorming hasta las iteraciones arquitectónicas desarrollo. Su capacidad para distribuir responsabilidades según especialidad y coordinar la documentación técnica rigurosa garantizó una evolución ordenada del sistema, facilitando la sincronización técnica necesaria para orquestar microservicios y hardware físico.<br><br>**Nakamurakare Teruya, Alex Tomio**<br>**AV1**<br>Asumió la dirección del diseño y normalización del modelo de datos relacional para los contextos lógicos iniciales.<br>**TP**<br>Resolvió cuellos de botella críticos relacionados con la persistencia relacional durante la integración del API Gateway.<br>**AV2**<br>Dirigió la orquestación de APIs y esquemas distribuidos para asegurar la persistencia políglota entre MySQL y TimescaleDB.<br>**TF**<br>Asumió la dirección arquitectónica del ecosistema backend, liderando el diseño y normalización de los modelos de datos relacionales y distribuidos. Su capacidad para resolver colaborativamente cuellos de botella críticos, como la configuración de persistencia políglota (MySQL y TimescaleDB) y la integración del API Gateway, demostró un liderazgo técnico sólido enfocado en asegurar la escalabilidad y disponibilidad de los servicios cloud.<br><br>**Rodas Sotomayor, Ernesto**<br>**AV1**<br>Condujo la estructuración del Ubiquitous Language y la especificación de las Technical Stories como directrices de calidad.<br>**TP**<br>Coordinó sesiones de pair programming y revisión conjunta para resguardar la uniformidad.<br>**AV2**<br>Lideró la optimización del stack en la nube de Azure.<br>**TF**<br>Lideró la estructuración del Ubiquitous Language (Lenguaje Ubicuo) y la especificación de Technical Stories, estableciendo directrices de calidad claras para todo el equipo. Su coordinación de sesiones de pair programming y revisión conjunta garantizó la uniformidad del código, culminando con la dirección y optimización exitosa del stack tecnológico desplegado en la infraestructura de Azure. | **AV1**<br>El equipo consolidó un modelo de liderazgo técnico colaborativo al unificar las diversas competencias individuales. Esto permitió definir de manera colectiva la topología IoT y las fronteras de los contextos acotados del sistema.<br>**TP**<br>Se descentralizó la toma de decisiones técnicas mediante un esquema de supervisión cruzada. Los retos de mensajería asíncrona e integración en la nube se resolvieron mediante sesiones de diseño unificado y no como aportes aislados.<br>**AV3**<br>La sinergia del equipo permitió rotar orgánicamente el liderazgo según las necesidades del Sprint 2. El dominio compartido sobre microservicios, desarrollo móvil y visión artificial consolidó una solución resiliente y alineada a los estándares de producción de la industria.<br>**TF**<br>Como equipo, consolidamos un modelo de liderazgo técnico verdaderamente descentralizado y colaborativo, maximizando nuestras diversas competencias individuales. Desde la concepción de la topología IoT hasta el despliegue final del ecosistema (Edge-to-Cloud), las decisiones arquitectónicas y la orquestación de microservicios se resolvieron mediante esquemas de supervisión cruzada y sesiones de diseño unificado. La rotación orgánica del liderazgo según los retos del Sprint (desarrollo móvil, backend, firmware y visión artificial) nos permitió mitigar fricciones y construir una solución tecnológica resiliente, alineada con los estándares de producción de la industria. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Binda Arbañil, Marcelo Alejandro**<br>**AV1**<br>Planificó los hitos de entrega inicial empleando tableros visuales, garantizando un flujo estructurado de trabajo colaborativo.<br>**TP**<br>Monitoreó los plazos de desarrollo e integración mediante reuniones periódicas de seguimiento y sincronización técnica.<br>**AV2**<br>Adoptó de forma proactiva requerimientos de diseño responsivo y adaptabilidad de vistas basándose en el feedback del equipo.<br>**TF**<br>Garantizó un flujo de trabajo estructurado y transparente planificando los hitos de entrega. Su gestión proactiva al monitorear plazos de desarrollo e incorporar feedback continuo para adaptar vistas web responsivas, aseguró que las metas técnicas se cumplieran en los tiempos establecidos, fomentando un entorno de comunicación abierta y sincronización constante.<br><br>**Castillo Garay, Ainhoa Lucía**<br>**AV1**<br>Modeló la interacción de hardware y software a través de Context Maps, facilitando un entorno inclusivo de comprensión global.<br>**TP**<br>Estructuró los diagramas de componentes y clases del sistema definiendo metas a corto plazo para evitar retrasos.<br>**AV2**<br>Investigó e implementó de manera ágil componentes móviles reutilizables durante el Sprint, robusteciendo la consistencia de la interfaz.<br>**TF**<br>Fomentó un entorno inclusivo de comprensión global al modelar la interacción entre hardware y software mediante Context Maps. Estructuró eficazmente los diagramas de componentes definiendo metas a corto plazo, y mantuvo un enfoque ágil al investigar e implementar componentes móviles reutilizables. Esto previno retrasos y aseguró que el desarrollo de la aplicación móvil cumpliera con los objetivos de usabilidad y rendimiento del proyecto.<br><br>**Martel Andrade, Cassius Estefano**<br>**AV1**<br>Analizó con precisión las competencias individuales del equipo para estructurar una división de tareas equilibrada y eficiente.<br>**TP**<br>Replanteó la planificación del Sprint Backlog adaptándolo de forma dinámica a las restricciones reales de conectividad rural.<br>**AV2**<br>Incorporó buenas prácticas de arquitectura de software para asegurar la mantenibilidad a largo plazo de la plataforma de cara al usuario.<br>**TF**<br>Estructuró una división de tareas equilibrada y eficiente tras analizar con precisión las competencias individuales del equipo. Su flexibilidad para replantear la planificación del Sprint Backlog adaptándolo a restricciones físicas reales (como la conectividad intermitente IoT) y su enfoque en integrar buenas prácticas de ingeniería, aseguraron el cumplimiento de los objetivos garantizando la mantenibilidad a largo plazo de la plataforma de cara al usuario.<br><br>**Nakamurakare Teruya, Alex Tomio**<br>**AV1**<br>Integró las sugerencias técnicas de todos los integrantes dentro del Diagrama Global de Base de Datos para asegurar inclusividad.<br>**TP**<br>Mantuvo canales de comunicación abiertos y transparentes durante la fase crítica de despliegue de bases de datos relacionales.<br>**AV2**<br>Ajustó los esquemas distribuidos de telemetría y series de tiempo en Azure para satisfacer nuevas métricas analíticas del negocio.<br>**TF**<br>Aseguró la inclusividad técnica integrando las sugerencias de todos los miembros en el diseño global de la infraestructura de datos. Su habilidad para mantener canales de comunicación transparentes durante los despliegues críticos en Azure y su proactividad para ajustar esquemas de telemetría a nuevas métricas analíticas, fueron determinantes para cumplir los objetivos operativos del negocio sin sacrificar la estabilidad del entorno colaborativo.<br><br>**Rodas Sotomayor, Ernesto**<br>**AV1**<br>Facilitar el codiseño de los lienzos estratégicos de negocio (Lean UX Canvas) para alinear las metas académicas con las técnicas.<br>**TP**<br>Promovió talleres internos de revisión de código para asegurar la adaptabilidad del equipo frente a nuevas herramientas lógicas.<br>**AV2**<br>Optimizó los entornos de integración continua (CI/CD) en GitHub Actions, garantizando entregas de software estables y sin fallos.<br>**TF**<br>Promovió un entorno altamente adaptativo codiseñando los lienzos estratégicos de negocio (Lean UX Canvas) para alinear metas académicas y técnicas. Su iniciativa al facilitar talleres internos de revisión de código y su gestión para optimizar los flujos de Integración/Despliegue Continuo (CI/CD) en GitHub Actions, garantizaron entregas de software ágiles, estables y fieles a la planificación del equipo. | **AV1**<br>El grupo propició un espacio inclusivo unificado mediante herramientas visuales estratégicas (Lean UX, Context Maps). Esto facilitó que cada meta establecida contribuyera directamente a cimentar una solución IoT escalable.<br>**TP**<br>Se logró un cumplimiento del 100% de los objetivos trazados para el hito parcial mediante la estructuración del Sprint Backlog 1 con metas de corto plazo y revisiones semanales, integrando con éxito el flujo de maquetado con el despliegue cloud.<br>**AV3**<br>El equipo demostró una alta adaptabilidad y compromiso con el aprendizaje continuo frente a los desafíos del Sprint 2. La investigación conjunta, la resolución de cuellos de botella en la persistencia políglota y la automatización de despliegues en Azure validaron la madurez del equipo para cumplir con calidad de exportación los requerimientos del proyecto.<br>**TF**<br>Logramos un cumplimiento integral y exitoso de los objetivos del proyecto mediante una planificación táctica adaptativa. Fomentamos un entorno inclusivo al utilizar herramientas visuales estratégicas (EventStorming, Context Maps, Kanban) que garantizaron la participación de todos. Frente a desafíos complejos como la integración asíncrona, la persistencia políglota y los despliegues automatizados en Azure, nuestra capacidad para replantear el Sprint Backlog, establecer metas a corto plazo y mantener la comunicación constante demostró nuestra madurez para planificar, ejecutar y entregar un producto software-hardware con calidad de exportación. |

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
| 8 | US31 | Compartir accesos de lectura a otros usuarios | 3 |
| 9 | US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | 13 |
| 10 | US10 | Vinculación del Microcontrolador con la Aplicación | 5 |
| 11 | US22 | Gestión de registro fotográfico de cultivos. | 5 |
| 12 | TS01 | Implementación de Endpoints de Monitoreo de Salud (Health Checks) | 3 |
| 13 | US21 | Generación y descarga de reportes históricos | 1 |
| 14 | US30 | Protección y privacidad de los datos | 5 |
| 15 | TS07 | Estandarización de la Experiencia del Desarrollador y Documentación | 3 |
| 16 | TS05 | Implementación de Protocolos de Autenticación y Protección de Recursos | 5 |
| 17 | US17 | Persistencia de datos ante pérdida de conectividad | 3 |
| 18 | US18 | Notificaciones automáticas por condiciones críticas y cambios de estado | 1 |
| 19 | US15 | Organización de dispositivos por zonas y especies | 3 |
| 20 | US16 | Configuración de parámetros y umbrales de control | 1 |
| 21 | TS08 | Dashboard web con indicadores clave del sistema | 5 |
| 22 | TS12 | Gestión de mantenimiento de dispositivos IoT | 5 |
| 23 | TS13 | Consulta rápida del catálogo de cultivos | 3 |
| 24 | TS09 | Gestión móvil de clientes agricultores | 5 |
| 25 | TS10 | Registro de contratos externos en campo | 5 |
| 26 | TS11 | Gestión de suspensión de servicios | 3 |
| 27 | US27 | Visualización de estado de servicios | 3 |
| 28 | US26 | Configuración y gestión de alertas de usuario | 1 |
| 29 | US25 | Modificación de datos personales y de contacto | 1 |
| 30 | US24 | Registro, inicio y cierre de sesión de usuario | 1 |
| 31 | US29 | Acceso garantizado y fluidez en la consulta de datos | 3 |
| 32 | US28 | Diseño consistente y adaptabilidad multiplataforma | 3 |
| 33 | TS03 | Desacoplamiento de Lógica de Negocio mediante Inyección de Dependencias | 5 |
| 34 | TS04 | Optimización de Latencia y Eficiencia en el Procesamiento | 3 |
| 35 | TS06 | Implementación de Infraestructura de Pruebas Automatizadas | 5 |
| 36 | US01 | Visualización de propuesta de valor y servicios | 1 |
| 37 | US02 | Enlaces de acceso a la aplicación móvil | 1 |
| 38 | US03 | Implementación de CTA | 1 |
| 39 | US04 | Visualización de misión, visión y equipo | 1 |
| 40 | US05 | Implementación de formulario y canales de contacto | 1 |
| 41 | US06 | Enlaces a redes sociales | 1 |
| 42 | US07 | Implementación de sistemas de navegación simplificada | 1 |
| 43 | US08 | Implementación de Identidad y Consistencia Visual | 1 |
| 44 | US09 | Optimización de tiempos de respuesta y carga inicial | 3 |
| 45 | TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) | 3 |
| 46 | TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | 5 |
| 47 | TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | 5 |
| 48 | TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python) | 8 |
| 49 | TS19 | Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET) | 5 |
| 50 | TS20 | Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos | 3 |
| 51 | TS14 | Autenticación y Control de Acceso para el Portal de Administración | 2 |

### Product Backlog Funcional

| Prioridad | ID | Título | Story Points |
|----|----|----|----|
| 2 | US11 | Monitoreo fiel de las condiciones del entorno | 5 |
| 3 | US12 | Actualización periódica y automática de telemetría | 5 |
| 5 | US14 | Dashboard de Monitoreo Integral y Resumen de Estado | 3 |
| 6 | US19 | Activación manual del sistema de irrigación | 3 |
| 7 | US20 | Automatización del riego mediante modelos de aprendizaje automático | 8 |
| 8 | US31 | Compartir accesos de lectura a otros usuarios | 3 |
| 9 | US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | 13 |
| 10 | US10 | Vinculación del Microcontrolador con la Aplicación | 5 |
| 11 | US22 | Gestión de registro fotográfico de cultivos. | 5 |
| 13 | US21 | Generación y descarga de reportes históricos | 1 |
| 18 | US18 | Notificaciones automáticas por condiciones críticas y cambios de estado | 1 |
| 19 | US15 | Organización de dispositivos por zonas y especies | 3 |
| 20 | US16 | Configuración de parámetros y umbrales de control | 1 |
| 21 | TS08 | Dashboard web con indicadores clave del sistema | 5 |
| 22 | TS12 | Gestión de mantenimiento de dispositivos IoT | 5 |
| 23 | TS13 | Consulta rápida del catálogo de cultivos | 3 |
| 24 | TS09 | Gestión web de clientes agricultores | 5 |
| 25 | TS10 | Registro de contratos externos en campo | 5 |
| 26 | TS11 | Gestión de suspensión de servicios | 3 |
| 27 | US27 | Visualización de estado de servicios | 3 |
| 28 | US26 | Configuración y gestión de alertas de usuario | 1 |
| 29 | US25 | Modificación de datos personales y de contacto | 1 |
| 30 | US24 | Registro, inicio y cierre de sesión de usuario | 1 |
| 36 | US01 | Visualización de propuesta de valor y servicios | 1 |
| 37 | US02 | Enlaces de acceso a la aplicación móvil | 1 |
| 38 | US03 | Implementación de CTA (Botones de acción) | 1 |
| 39 | US04 | Visualización de misión, visión y equipo | 1 |
| 40 | US05 | Implementación de formulario y canales de contacto | 1 |
| 41 | US06 | Enlaces a redes sociales | 1 |
| 8 | US31 | Compartir accesos de lectura a otros usuarios | 3 |
| 9 | US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | 13 |
| 10 | US10 | Vinculación del Microcontrolador con la Aplicación | 5 |
| 11 | US22 | Gestión de registro fotográfico de cultivos. | 5 |
| 13 | US21 | Generación y descarga de reportes históricos | 1 |
| 18 | US18 | Notificaciones automáticas por condiciones críticas y cambios de estado | 1 |
| 19 | US15 | Organización de dispositivos por zonas y especies | 3 |
| 20 | US16 | Configuración de parámetros y umbrales de control | 1 |
| 21 | TS08 | Dashboard web con indicadores clave del sistema | 5 |
| 22 | TS12 | Gestión de mantenimiento de dispositivos IoT | 5 |
| 23 | TS13 | Consulta rápida del catálogo de cultivos | 3 |
| 24 | TS09 | Gestión web de clientes agricultores | 5 |
| 25 | TS10 | Registro de contratos externos en campo | 5 |
| 26 | TS11 | Gestión de suspensión de servicios | 3 |
| 27 | US27 | Visualización de estado de servicios | 3 |
| 28 | US26 | Configuración y gestión de alertas de usuario | 1 |
| 29 | US25 | Modificación de datos personales y de contacto | 1 |
| 30 | US24 | Registro, inicio y cierre de sesión de usuario | 1 |
| 36 | US01 | Visualización de propuesta de valor y servicios | 1 |
| 37 | US02 | Enlaces de acceso a la aplicación móvil | 1 |
| 38 | US03 | Implementación de CTA (Botones de acción) | 1 |
| 39 | US04 | Visualización de misión, visión y equipo | 1 |
| 40 | US05 | Implementación de formulario y canales de contacto | 1 |
| 41 | US06 | Enlaces a redes sociales | 1 |

### Product Backlog No Funcional

| Prioridad | ID | Título | Story Points |
|----|----|----|----|
| 1 | TS02 | Estandarización de Contratos de Interoperabilidad IoT | 3 |
| 4 | US13 | Garantía de exactitud en la medición de datos | 3 |
| 12 | TS01 | Implementación de Endpoints de Monitoreo de Salud | 3 |
| 15 | US30 | Protección y privacidad de los datos | 5 |
| 16 | TS07 | Estandarización de la Exp. del Desarrollador y Documentación | 3 |
| 17 | TS05 | Implementación de Protocolos de Autenticación | 5 |
| 18 | US17 | Persistencia de datos ante pérdida de conectividad | 3 |
| 32 | US29 | Acceso garantizado y fluidez en la consulta de datos | 3 |
| 33 | US28 | Diseño consistente y adaptabilidad multiplataforma | 3 |
| 34 | TS03 | Desacoplamiento de Lógica mediante DI/Repository | 5 |
| 35 | TS04 | Optimización de Latencia y Eficiencia (Async) | 3 |
| 36 | TS06 | Infraestructura de Pruebas Automatizadas | 5 |
| 43 | US07 | Implementación de sistemas de navegación simplificada | 1 |
| 44 | US08 | Implementación de Identidad y Consistencia Visual | 1 |
| 45 | US09 | Optimización de tiempos de respuesta y carga inicial | 3 |
| 46 | TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) | 3 |
| 47 | TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | 5 |
| 48 | TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | 5 |
| 49 | TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (.NET) | 8 |
| 50 | TS19 | Integración de Hardware IoT y Configuración del Microcontrolador (ESP32) | 5 |
| 12 | TS01 | Implementación de Endpoints de Monitoreo de Salud | 3 |
| 15 | US30 | Protección y privacidad de los datos | 5 |
| 16 | TS07 | Estandarización de la Exp. del Desarrollador y Documentación | 3 |
| 17 | TS05 | Implementación de Protocolos de Autenticación | 5 |
| 18 | US17 | Persistencia de datos ante pérdida de conectividad | 3 |
| 32 | US29 | Acceso garantizado y fluidez en la consulta de datos | 3 |
| 33 | US28 | Diseño consistente y adaptabilidad multiplataforma | 3 |
| 34 | TS03 | Desacoplamiento de Lógica mediante DI/Repository | 5 |
| 35 | TS04 | Optimización de Latencia y Eficiencia (Async) | 3 |
| 36 | TS06 | Infraestructura de Pruebas Automatizadas | 5 |
| 43 | US07 | Implementación de sistemas de navegación simplificada | 1 |
| 44 | US08 | Implementación de Identidad y Consistencia Visual | 1 |
| 45 | US09 | Optimización de tiempos de respuesta y carga inicial | 3 |
| 46 | TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil (Flutter) | 3 |
| 47 | TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | 5 |
| 48 | TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | 5 |
| 49 | TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (.NET) | 8 |
| 50 | TS19 | Integración de Hardware IoT y Configuración del Microcontrolador (ESP32) | 5 |
| 50 | TS20 | Configuración de Persistencia de Datos para Telemetría Masiva | 3 |
| 51 | TS14 | Autenticación y Control de Acceso para el Portal de Administración | 2 |
| 51 | TS14 | Autenticación y Control de Acceso para el Portal de Administración | 2 |

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

<img src="https://imgur.com/8URn58p.png">

Este flujo describe la orquestación técnica que ocurre cuando un usuario registra una nueva zona de cultivo en Grotix, iniciando con el comando Crear Zona de Cultivo que, tras superar una política de validación de campos, activa el Bounded Context de Cultivation Area para generar tanto una notificación de éxito como la actualización visual en la interfaz. Simultáneamente, el sistema escala la operación hacia el contexto de Hardware Device mediante el comando Asignar microcontrolador, donde el sistema de sensores valida la vinculación física del dispositivo y ejecuta finalmente el comando de vinculación técnica entre el microcontrolador y la zona lógica, asegurando que los datos de telemetría queden correctamente mapeados desde el primer momento.

* **Escenario 2: Riego Automático por Identificación de IA**

<img src="https://imgur.com/D4yuIYs.png">

Este flujo describe la orquestación técnica que comienza en el Bounded Context de Crop Analysis (IA) con el procesamiento de imágenes y la identificación del tipo de cultivo, generando eventos clave que activan la lógica de decisión del sistema. Tras superar una política de validación de umbrales basada en la especie detectada, el contexto de Irrigation cycle colabora con Cultivation area para obtener los parámetros hídricos óptimos, escalando la operación hacia el Bounded Context de Hardware Device mediante el comando de inicio de riego automático. Finalmente, el sistema interactúa con el actuador físico para ejecutar el comando de activación de la bomba de agua, culminando el proceso con la emisión del evento Riego Iniciado, lo que garantiza que la ejecución hídrica esté perfectamente alineada con las necesidades biológicas detectadas por la inteligencia artificial en tiempo real. 

* **Escenario 3: Respuesta a Umbral Crítico de Telemetría (Alerta)**

<img src="https://imgur.com/ym3UFly.png">

Este flujo detalla la respuesta reactiva del sistema ante condiciones críticas en el campo, comenzando cuando el Sensor emite el evento Lectura de sensor de nivel de humedad, el cual es captado por el contexto de Hardware Device y validado mediante una política que confirma la relación entre el microcontrolador y la zona de cultivo. Una vez verificada la identidad del dispositivo, el flujo se traslada al contexto de Cultivation Area para emitir el evento Nivel de humedad leído, que sirve como entrada para el contexto de Telemetry; allí, una Política de validación de umbral analiza el dato y, al detectar niveles fuera de rango, dispara el evento Umbral crítico de humedad alcanzado. Finalmente, este evento activa el comando Generar alerta de umbral excedido dentro del contexto de Profile, culminando en una Notificación (Toast) enviada directamente al usuario para informarle sobre la anomalía y permitir una toma de decisiones inmediata basada en los datos de telemetría.

* **Escenario 4: Intervención manual remota**

<img src="https://imgur.com/No8NAKr.png">

Este flujo describe la orquestación técnica que ocurre cuando el Usuario de Grotix decide actuar sobre el campo mediante el comando Iniciar riego manual, especificando el ID del área y la duración requerida. Esta instrucción es procesada por el Bounded Context de Irrigation Cycle, que escala la operación hacia el contexto de Hardware Device a través del envío de un mensaje de control manual para la zona afectada. Finalmente, el sistema interactúa con la infraestructura física ejecutando el comando Activar bomba de agua sobre el actuador correspondiente (Bomba/Válvula), culminando el proceso con la emisión del evento Riego iniciado manualmente, lo que asegura la trazabilidad del inicio de la operación y la sincronización del estado hídrico en todo el ecosistema.

#### 4.1.1.3. Bounded Context Canvases

Esta sección presenta el diseño estratégico de los Bounded Contexts de Grotix, la plataforma de agricultura inteligente desarrollada por la startup Celevi. Cada canvas modela uno de los seis contextos identificados en el dominio, describiendo sus responsabilidades, el lenguaje ubicuo que lo rige, las comunicaciones de entrada y salida con otros contextos, y las decisiones de negocio que encapsula.Gratix integra sensores IoT, automatización de riego y visión artificial por IA para democratizar la agricultura de precisión en el Perú. Su arquitectura de dominio responde a esta complejidad técnica distribuyendo las responsabilidades en seis contextos diferenciados

**Profile Bounded Context**

<img src="https://imgur.com/R49hDPK.png">

**Cultivation Area Bounded Context:**

<img src="https://imgur.com/tHl2M45.png">

**Hardware Device Bounded Context:**

<img src="https://imgur.com/BeCv22v.png">

**Irrigation cycle Bounded Context:**

<img src="https://imgur.com/ZywttgL.png">

**Crop Analysis (AI) Bounded Context:**

<img src="https://imgur.com/LsowVYQ.png">

**Telemetry Bounded Context:**

<img src="https://imgur.com/iIqigse.png">

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

<img src="https://imgur.com/lO55NLZ.png">

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

<img src="https://imgur.com/25l3vsO.png">

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

<img src="https://imgur.com/eEpKrh4.png">

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

<img src="https://imgur.com/AqLYiOt.png">

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

<img src="https://imgur.com/hd5TnA4.png">

El diagrama de clases de la capa de dominio de Hardware Device modela la estación física como el Agregado Raíz HardwareDevice, encargado de orquestar el ciclo de vida de los componentes electrónicos en el campo. El sistema distingue entre Sensors, que producen objetos de valor del tipo RawData mediante lecturas ambientales, y Actuators, que ejecutan acciones físicas como la activación de bombas o válvulas. La integridad operativa se mantiene a través del objeto de valor BatteryLevel y el estado enumerado DeviceStatus, mientras que el servicio de dominio DeviceHeartbeatService asegura que la sincronización con la nube sea constante. Finalmente, la interfaz IHardwareInterface actúa como una capa de abstracción (HAL), permitiendo que la lógica de negocio interactúe con los pines físicos del microcontrolador sin quedar acoplada a un modelo de hardware específico (ej. ESP32 vs Raspberry Pi).

##### 4.2.3.6.2. Bounded Context Database Design Diagram

<img src="https://imgur.com/IpCJO5z.png">

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

<img src="https://imgur.com/ESNWI43.png">

El diagrama de clases de la capa de dominio de Irrigation Cycle establece a IrrigationCycle como el Agregado Raíz encargado de gestionar el ciclo de vida de un evento de riego, desde su inicio hasta su culminación o aborto, manteniendo la integridad del volumen de agua consumido mediante el objeto de valor WaterQuantity. La planificación se desacopla a través del agregado IrrigationSchedule, que permite definir frecuencias y duraciones personalizadas para cada zona de cultivo. El motor inteligente del contexto reside en el IrrigationCalculator, un servicio de dominio que evalúa si un riego debe ejecutarse o posponerse comparando la telemetría actual con los umbrales biológicos, mientras que las interfaces de repositorio aseguran que tanto el historial de ejecuciones (registrado en IrrigationLog) como los calendarios activos se persistan correctamente en la infraestructura de datos de Grotix.

##### 4.2.4.6.2. Bounded Context Database Design Diagram

<img src="https://imgur.com/g28c861.png">

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

<img src="https://imgur.com/399dqq5.png">

El diagrama de clases de la capa de dominio estructura el núcleo analítico de Grotix, estableciendo a AnalysisReport como el Agregado Raíz responsable de unificar los hallazgos de un ciclo de evaluación para una zona de cultivo específica. Este agregado mantiene la integridad de los resultados utilizando objetos de valor inmutables como HealthScore (que determina el estado general mediante el enumerador HealthStatus) y GrowthMetric (que compara el rendimiento real contra el esperado), mientras que las anomalías específicas se modelan mediante entidades AgriculturalInsight para permitir un seguimiento individualizado de alertas agronómicas. La complejidad heurística y predictiva reside en el servicio de dominio DiagnosisEngine, encargado de procesar la telemetría cruda y los umbrales biológicos para instanciar reportes coherentes, los cuales son finalmente abstraídos para su persistencia a través del contrato definido en IAnalysisRepository.

##### 4.2.5.6.2. Bounded Context Database Design Diagram

<img src="https://imgur.com/Yz57VdF.png">

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

<img src="https://imgur.com/1HblRho.png">

El diseño de persistencia para el Bounded Context de Telemetry ha sido optimizado para el manejo de flujos masivos de datos y la integridad de series temporales, centrando su arquitectura en el ciclo de vida del TelemetryReadingAggregate. La estructura se divide en dos capas de persistencia que garantizan la disponibilidad del sistema bajo cualquier condición de red. En la capa de borde, la tabla pending_telemetry actúa como una cola de persistencia efímera que asegura que ninguna lectura capturada por el IoTDataConsumer se pierda ante fallos de conectividad, permitiendo que el objeto de valor CaptureTimestamp mantenga la precisión cronológica del dato original antes de su sincronización definitiva con la nube.

Una vez que los datos son procesados por el RegisterMeasurementHandler, la persistencia definitiva se realiza en la tabla sensor_reading dentro de la base de datos maestra. Esta tabla ha sido diseñada siguiendo principios de bases de datos de series de tiempo, utilizando tipos de datos de alta capacidad como BigInt para el ReadingID y Float para el MeasurementValue, lo que permite almacenar millones de registros sin degradación del rendimiento. La vinculación con la entidad SensorSource se resuelve mediante una clave foránea hacia el SensorID, permitiendo que el TimeSeriesTelemetryRepository realice agregaciones y consultas históricas eficientes por zona o tipo de sensor. Además, el servicio de dominio ThresholdValidator utiliza esta estructura de persistencia para comparar en tiempo real la lectura entrante con los registros históricos, asegurando que solo los datos validados y consistentes alimenten los gráficos y motores de análisis del agricultor.

# CAPÍTULO V: Solution UI/UX Design

## 5.1. Style Guidelines
Para asegurar la integridad visual y funcional del ecosistema Grotix, se define este marco de Style Guidelines como el eje central de diseño y estandarización para el equipo de desarrollo. Esta sección establece las normas fundamentales para el uso de activos, tipografías y elementos gráficos, garantizando una transición fluida y profesional entre la landing page, la aplicación móvil y las interfaces de gestión IoT. Al centralizar estas directrices, no solo se refuerza la identidad de marca orientada a la innovación agrícola y tecnológica, sino que se optimiza la eficiencia operativa del equipo al proporcionar un lenguaje visual común que responde estrictamente a los criterios de usabilidad, accesibilidad y consistencia multiplataforma definidos en los requerimientos del sistema.

### 5.1.1. General Style Guidelines
Las General Style Guidelines de Grotix se fundamentan en la creación de una identidad visual que equilibre la innovación tecnológica con la confiabilidad agrícola. Basándonos en principios de diseño centrados en el usuario, hemos seleccionado una paleta de colores y una jerarquía tipográfica que garantizan la legibilidad y accesibilidad (WCAG), facilitando la interacción de los agricultores con datos complejos de telemetría e IA. En cuanto al tono de comunicación, Grotix adopta una dimensión entusiasta, respetuosa y profesional, eliminando tecnicismos innecesarios para asegurar que el lenguaje sea sereno y comprensible, transformando así la experiencia técnica en una herramienta de gestión cotidiana cercana y efectiva.

#### Branding y Logo

<img src="https://imgur.com/mBeabdf.png">

El branding de Grotix se ha diseñado para proyectar una identidad que fusiona la naturaleza con la precisión tecnológica. El logotipo utiliza una tipografía moderna y de alta legibilidad, donde el isotipo destaca por la integración de hojas verdes que simbolizan la vida y el crecimiento agrícola. La incorporación de un elemento circular y una letra "i" en tonos celestes refuerza el concepto de inteligencia y fluidez hídrica, comunicando visualmente que Grotix no es solo una herramienta de monitoreo, sino una solución inteligente enfocada en la sostenibilidad y el éxito de la germinación. Esta composición visual garantiza que la marca sea fácilmente reconocible tanto en interfaces digitales como en dispositivos físicos, manteniendo una estética profesional y vanguardista.

#### Paleta de Colores (Colors)

<img src="https://imgur.com/e5Q3Lve.png">

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

```html
<title>Grotix</title>
```

En este meta tag, se define el título que tendrá el sitio web del proyecto. El equipo decidió usar el nombre de la startup seguido del nombre del producto para resaltar nuestra autoría sobre la idea, optando por una mayor simplicidad que facilite la lectura por parte del usuario.

**Meta Tags**

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- META TAGS -->
<meta name="description" content="AI-Driven Precision Irrigation for Smarter, Water-Efficient Farming.">
<meta name="keywords" content="Grotix, farming, water, irrigation, sensors, machine learning, agriculture">
<meta name="author" content="Celevi">

<!-- Open Graph -->
<meta property="og:site_name" content="Grotix">
<meta property="og:title" content="Celevi - Grotix">
<meta property="og:description" content="AI-Driven Precision Irrigation for Smarter, Water-Efficient Farming.">
<meta property="og:type" content="website">
```

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

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/vite.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Grotix Default Meta Tags -->
    <title>Grotix Portal - Farm Management Dashboard</title>
    <meta name="description" content="Access the Grotix management portal to monitor telemetry, control hardware, and review crop health reports." />
    <meta name="keywords" content="Grotix login, farm management dashboard, agricultural telemetry portal" />
    <meta name="author" content="Celevi" />

    <!-- Evitar indexación de rutas privadas por defecto -->
    <meta name="robots" content="noindex, nofollow" />
  </head>
  <body>
    <div id="app"></div>
    <script type="module" src="/src/main.js"></script>
  </body>
</html>
```

Para la aplicación web de Grotix, se ha configurado el archivo principal (index.html) con un conjunto de etiquetas (tags) y metaetiquetas (meta tags) estructurales y de SEO. Esta configuración base tiene el doble propósito de asegurar una correcta visualización en diversos dispositivos móviles, y de establecer la identidad fundamental del portal. Además, considerando que el Dashboard gestiona datos sensibles de los agricultores y telemetría de los cultivos, se ha implementado una directiva de privacidad por defecto en los motores de búsqueda, asegurando que la información interna no quede expuesta públicamente. 

* **Viewport (<meta name="viewport">)**: Configurado con los valores width=device-width, initial-scale=1.0 para garantizar que la interfaz de usuario se escale y adapte correctamente a cualquier tamaño de pantalla, cumpliendo con los estándares de diseño responsivo.
* **Title (<title>)**: Se ha definido el valor "Grotix Portal - Farm Management Dashboard" para mostrar claramente el propósito de la plataforma en las pestañas del navegador y proveer un título por defecto antes de que el enrutador dinámico (Vue Router) actúe.
* **Description (<meta name="description">)**: Incluye un resumen descriptivo en inglés de las capacidades del sistema ("Access the Grotix management portal to monitor telemetry, control hardware, and review crop health reports"), lo cual mejora la presentación del enlace si se comparte en plataformas de mensajería o redes corporativas.
* **Keywords (<meta name="keywords">)**: Establece términos clave como "Grotix login" y "agricultural telemetry portal" para definir semánticamente el nicho de la aplicación.
* **Author (<meta name="author">)**: Identifica a "Celevi" como el autor o entidad responsable del desarrollo de este producto digital.
* **Robots (<meta name="robots">)**: Configurado como "noindex, nofollow". Esta es una medida de seguridad preventiva vital para un entorno administrativo, ya que instruye a los rastreadores web (como el bot de Google) a no indexar la página de entrada en sus resultados de búsqueda y a no seguir sus enlaces internos, protegiendo así las rutas privadas.

#### Mobile App (For Clients)

```xml
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <uses-permission android:name="android.permission.INTERNET" />

    <application
        android:allowBackup="true"
        android:usesCleartextTraffic="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@mipmap/ic_launcher"
        android:label="AdminLivria"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.AdminLivria">
        <activity
            android:name=".MainActivity"
            android:exported="true"
            android:label="AdminLivria"
            android:theme="@style/Theme.AdminLivria">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>
```

**ASO (App Store Optimizaton) elements:**
La optimización para tiendas de aplicaciones (ASO) de la aplicación se centra en los siguientes elementos visibles:

* **Título de la Aplicación (App Title/Name):** Este está definido por el atributo android:label tanto en la etiqueta <application> como en la <activity> principal. Este es el nombre que los usuarios verán bajo el icono de la aplicación en la pantalla de inicio y en la tienda de aplicaciones.
* **Icono de la Aplicación (App Icon):** El atributo android:icon especifica el recurso @mipmap/ic_launcher y android:roundIcon especifica @mipmap/ic_launcher_round. Aunque no se muestra el diseño real, este es un elemento crucial de ASO ya que es la primera impresión visual de la aplicación.

### 5.2.4. Searching Systems
En Grotix, los Searching Systems fueron diseñados para simplificar la experiencia de búsqueda y mejorar la experiencia del usuario, ayudándolo a localizar la información que quiere consultar rápidamente y de manera eficiente. Esto nos ayudará a evitar que los clientes se sientan abrumados y ayudará al staff a supervisar correctamente el servicio que ofrecen.

#### Web App (For Staff)

<img src="https://imgur.com/kkxKF5L.png">

En primer lugar, está la pantalla de Búsqueda, que está diseñada para ofrecer una experiencia de descubrimiento de catálogo rápida y directa al usuario. Su diseño conciso se enfoca en la eficiencia y la relevancia de los resultados. Permite explorar entre agricultores, contratos y dispositivos.

<img src="https://imgur.com/87OABjk.png">

La pantalla de Contratos incluye un ícono de filtros (representado por barras verticales de diferentes alturas) en la esquina superior derecha. Esta funcionalidad es crucial, ya que permite al staff refinar los resultados obtenidos en la lista general de contratos, aplicando criterios adicionales.

<img src="https://imgur.com/CGwaMsP.png">

De manera similar, en la pantalla de Dispositivos aparece el mismo ícono que permite filtrar entre la lista general de los microcontroladores aplicando ciertos criterios.

<img src="https://imgur.com/eoFwZUU.png">

En la pantalla de Cultivos hay una barra de búsqueda que permite explorar entre el listado de cultivos mediante dos criterios: nombre común o el científico.

#### Mobile App (For Clients)

<img src="https://imgur.com/LU1MnpG.png">

Los usuarios poseen una barra de búsqueda en cada zona (Dashboard de Cultivation Area) que creen y posean para la funcionalidad de buscar otros usuarios. Esta le permite encontrar agricultores dentro de su asociación e invitarlos a participar u observar en la zona específica, así como eliminarlos de la misma.

<img src="https://imgur.com/JTUC8lz.png">

En la pantalla de IA (Image Processing), el usuario puede buscar las zonas en específico que tiene para ver su estado. El sistema muestra un listado con las zonas y el estado de germinación que posee; con esta barra de búsqueda se le facilita el encuentro de algún área en particular.

<img src="https://imgur.com/ieZdMxX.png">

En la pantalla general de zonas (Cultivation Areas), el usuario tiene la opción de buscar entre aquellas ya existentes, así como crear una nueva o filtrarlas mediante criterios específicos. Esto le permite realizar su objetivo de manera eficiente.

### 5.2.5. Navigation Systems
El diseño de la navegación de Grotix se basa en una arquitectura de información clara, utilizando patrones probados para garantizar que tanto los agricultores como el personal administrativo puedan acceder a sus flujos de trabajo clave de manera eficiente. 

#### Web App (For Staff)

<img src="https://imgur.com/MqIX1wY.png">

En primer lugar, la barra lateral de navegación de la web app para el staff funciona como el eje central del sistema de navegación global, facilitando el acceso directo a los módulos críticos de Grotix.

Diseñada bajo un enfoque de navegación persistente, permite al usuario moverse de manera fluida entre el dashboard principal, el buscador, la gestión de clientes (agricultores), contratos y el monitoreo técnico de microcontroladores y zonas de cultivo. 

La jerarquía visual se apoya en una iconografía minimalista y escalable que optimiza el espacio de trabajo, asegurando que las herramientas de configuración y el acceso a la identidad de la marca permanezcan siempre al alcance del equipo operativo.

<img src="https://imgur.com/I7LZMd3.png">

Al momento de seleccionar un agricultor en específico en la pantalla de Agricultores (Agriculturists), la aplicación web dirige al miembro del staff a la pantalla de cliente en singular (Agriculturist). En caso de que desee regresar a ver la lista general de agricultores, puede hacerlo al hacer click en el ícono de flecha a la izquierda al costado del título (o a través del menú lateral).

<img src="https://imgur.com/bOtcPCb.png">

La pantalla de Cultivos (Crops) (y sus singulares) tienen la misma función de navegación que en Agricultores, permitiendo el regreso a la pantalla general de cultivos desde uno en singular.

#### Mobile App (For Clients)

<img src="https://imgur.com/CEDXXNb.png">

En la pantalla de una zona en específico (Dashboard de Cultivation Area) hay botones de navegación. En primer lugar está Main (Principal), que muestra los valores actuales de los criterios de la zona (humedad, luz, etc.) y la información general. En el medio se encuentra Settings (Configuración), que permite cambiar los valores de límite para cada criterio, así como el riego de la zona. Por último, está People (Personas), que permite buscar entre los agricultores de la asociación para que el administrador de la zona lo pueda agregar o eliminar.

<img src="https://imgur.com/FADDyBf.png">

La parte más importante de la navegación en la aplicación móvil es la barra inferior de menú. Cuenta con 5 íconos, cada uno dando acceso a diferentes funcionalidades. El primero, el dashboard, muestra una zona en específico a elección. Le sigue la estrella de cuatro puntas que dirige a la pantalla de AI Image Processing. En el medio se encuentra la planta, que muestra el listado de zonas (Cultivation Areas). El ícono de papel lleva a la pantalla de Reportes, que le permite al usuario generar informes sobre sus zonas y cultivos. Por último, el ícono de persona es el acceso a la pantalla de perfil (Profile), en la cual se muestran los detalles de la cuenta del usuario.

<img src="https://imgur.com/OuwPGvc.png">

Por último, la barra superior de cada pantalla de la aplicación posee dos accesos directos. El logo de Grotix lleva a la pantalla de zonas, como un acceso directo a información general. Y el ícono de campanita abre un drawer o sidebar (pantalla modal) con las notificaciones que recibe el usuario y una opción para configurarlas.

## 5.3. Landing Page UI Design
La propuesta de diseño para la interfaz de usuario (UI) de la Landing Page de Grotix es la culminación visual de la arquitectura de información y el diseño centrado en el usuario. Desde el primer impacto, esta interfaz está diseñada para proyectar una identidad accesible, amigable y culturalmente cercana. La estructura se organiza en secciones clave que garantizan una navegación fluida e intuitiva. Estéticamente, el diseño emplea una jerarquía visual limpia, ilustraciones cálidas, tipografías legibles y un uso estratégico de la paleta de colores para despertar el interés, generar confianza e impulsar al visitante a interactuar con los llamados a la acción, asegurando que la primera impresión sea tanto funcional como emocionalmente atractiva.

### 5.3.1. Landing Page Wireframe
La sección de Landing Page Wireframes presenta la arquitectura visual y la disposición estratégica de los elementos diseñados para comunicar la propuesta de valor de Grotix de manera efectiva. A través de una narrativa digital estructurada en secciones como Hero, Services, App, y Us, estos mockups definen la jerarquía de información necesaria para guiar al usuario desde el descubrimiento de la solución de riego inteligente hasta la conversión directa. El diseño prioriza una experiencia de usuario (UX) intuitiva en modo oscuro, integrando componentes visuales modernos y puntos de contacto estratégicos que refuerzan la identidad de Celevi y su compromiso con la sostenibilidad agrícola.

A continuación, se muestra cada wireframe pensado para la Landing Page:

<img src="https://imgur.com/pQD3owL.png">
<img src="https://imgur.com/6he5Glm.png">
<img src="https://imgur.com/YuDJW1q.png">
<img src="https://imgur.com/qWxR5xP.png">
<img src="https://imgur.com/opbin0H.png">
<img src="https://imgur.com/ugtDL6g.png">

### 5.3.2. Landing Page Mock-up

<img src="https://imgur.com/UxsADgt.png">

La sección General de la landing page de Grotix presenta una introducción impactante y profesional orientada a soluciones de agricultura de precisión. En el centro de una estética de modo oscuro, destaca el nombre de la plataforma acompañado de su propuesta de valor. Un botón destacado de "GET NOW!" invita a la conversión inmediata, mientras que en la base de la pantalla se despliega una galería visual que ilustra el uso de sensores en campo, monitoreo móvil y análisis de datos en tiempo real. En la parte superior, un menú de navegación claro permite acceder a las secciones de servicios, aplicación, nosotros, contacto y redes sociales, incluyendo además un selector de idioma para mayor accesibilidad.

<img src="https://imgur.com/MhjNeVJ.png">

La sección de Services de la landing page de Grotix detalla las capacidades tecnológicas de la plataforma para la agricultura de precisión mediante un diseño de tarjetas moderno y visual. Muestra un total de 6 tarjetas mostrando las principales características de la aplicación, dando un pequeño resumen de cada una con una imagen representativa de la información brindada.

<img src="https://imgur.com/NmS0uRz.png">

La sección App de la landing page destaca la movilidad y el control total bajo el lema "Your crops in the palm of your hand". En esta parte, se muestra un mockup de la aplicación móvil de Grotix. La descripción enfatiza el uso de inteligencia artificial para transformar datos complejos de sensores en decisiones accionables y reportes detallados de ahorro de agua, facilitando el acceso a estos insights directamente desde el teléfono. Finalmente, se presentan los botones de descarga para las principales tiendas de aplicaciones, reforzando la accesibilidad de la plataforma para el agricultor.

<img src="https://imgur.com/zSPcF0F.png">

La sección Us (Sobre Nosotros) de la landing page presenta a Celevi, la startup detrás de Grotix. En esta parte se explica que el equipo proviene de la Universidad Peruana de Ciencias Aplicadas (UPC) y se enfoca en promover la agricultura inteligente mediante una plataforma IoT escalable. Su misión principal es utilizar la automatización y el análisis de datos para optimizar el riego, buscando mitigar el hambre y transformar la gestión de recursos agrícolas en un motor de bienestar social y sostenibilidad nacional. La interfaz mantiene el estilo de modo oscuro con elementos gráficos abstractos y coloridos que resaltan la identidad de la marca y utilizan los colores de la paleta designada en style guidelines.

<img src="https://imgur.com/UPsWCrT.png">

La sección Contact de la landing page invita a la colaboración bajo el lema "Let’s grow the future together". En el lado izquierdo, destaca un formulario de contacto sobre un fondo verde vibrante que incluye campos para el nombre, correo electrónico, asunto y mensaje, finalizando con un botón de "SEND". El texto descriptivo a la derecha motiva tanto a productores individuales como a grandes asociaciones a realizar consultas técnicas o comerciales sobre los sensores IoT y la plataforma Grotix. Esta interfaz proporciona un canal directo y sencillo para resolver dudas y fomentar la adopción de sus soluciones agrícolas.

<img src="https://imgur.com/P12lNyg.png">

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

<img src="https://imgur.com/pldtjdL.png">

**Pantalla de Búsqueda**

<img src="https://imgur.com/Zp1UPUy.png">

**Pantalla de Agricultores**

<img src="https://imgur.com/0MmdCsc.png">

**Pantalla de Agricultor Individual**

<img src="https://imgur.com/X1033Zf.png">

**Pantalla de Contratos**

<img src="https://imgur.com/1XhzEZZ.png">

**Pantalla de Listado de Dispositivos**

<img src="https://imgur.com/YdJbEmm.png">

**Pantalla de Bitácora en Dispositivos**

<img src="https://imgur.com/pATPsVY.png">

**Pantalla Mantenimiento de Dispositivos**

<img src="https://imgur.com/8C3qgqs.png">

**Pantalla Dispositivo Individual**

<img src="https://imgur.com/2gWrpJf.png">

**Pantalla de Cultivos**

<img src="https://imgur.com/vCLT9De.png">

**Pantalla Cultivo Individual**

<img src="https://imgur.com/1Ub3gT5.png">

**Pantalla de Perfil**

<img src="https://imgur.com/u23z4bI.png">


#### Mobile App (For Clients)
**Pantallas de Dashboard; Main, Settings, People**

<img src="https://imgur.com/0dHHFmV.png">
<img src="https://imgur.com/ehI9Mou.png">
<img src="https://imgur.com/PEO6a83.png">

**Pantallas de AI, Cultivation Areas**

<img src="https://imgur.com/DnalwBR.png">
<img src="https://imgur.com/FI6bD1e.png">

**Pantallas de Reports, Profile**

<img src="https://imgur.com/T6DfXXP.png">
<img src="https://imgur.com/WfOrJYn.png">

**Pantallas de Notifications**

<img src="https://imgur.com/mLVXaj5.png">
<img src="https://imgur.com/PwxydnJ.png">

### 5.4.2. Applications Wireflow Diagrams

Los diagramas de wireflow de la aplicación móvil de Grotix constituyen la representación integrada de la arquitectura de pantallas y los flujos de interacción del agricultor con la plataforma. A diferencia de un wireframe estático, el wireflow combina la estructura visual de cada pantalla con las transiciones de navegación entre ellas, permitiendo verificar que cada acción del usuario desencadena una respuesta coherente del sistema. Los flujos descritos a continuación han sido diseñados tomando como eje la barra de navegación inferior (Bottom Navigation Bar) compuesta por cinco accesos directos: Dashboard, AI Advisor, Zones (botón central), Reports y Profile. De manera transversal, la cabecera superior de cada pantalla expone el logotipo de Grotix —que actúa como atajo directo hacia la pantalla de zonas— y el ícono de campanita, que despliega el panel lateral de notificaciones.

#### User Goal para Segmento 1: Agricultores Independientes 
Como agricultor usuario de Grotix, quiero visualizar en tiempo real los indicadores de humedad, temperatura e intensidad lumínica de mi zona de cultivo para tomar decisiones operativas de forma inmediata.
**Task flow:**

<img src="https://imgur.com/WVBV2xJ.png">

**Wireflow:**

<img src="https://imgur.com/76NwFMp.png">

Para poder interactuar con el monitoreo de variables de cultivo que ofrece Grotix, el agricultor accede, en primer lugar, a la pantalla principal del Dashboard al abrir la aplicación. El sistema lo sitúa automáticamente en la vista MAIN de la zona de cultivo activa, donde se despliegan en tiempo real tres métricas críticas obtenidas de los sensores IoT: el nivel de humedad del suelo representado como un indicador circular con valor porcentual y etiqueta semántica, la intensidad lumínica mediante una barra de progreso graduada con nivel descriptivo, y la temperatura ambiental en grados Celsius con indicador de estado. En caso de que alguna variable supere los umbrales configurados, el sistema resalta visualmente el indicador afectado con un cambio de color para facilitar una respuesta inmediata.

Desde esta misma pantalla, al presionar la pestaña SETTINGS ubicada en la barra de navegación superior del dashboard, el sistema presenta la vista de configuración de la zona activa. Aquí el agricultor puede activar o desactivar el riego automático mediante un toggle switch, iniciar manualmente una sesión de riego y definir el tiempo máximo de irrigación mediante un selector desplegable. Asimismo, puede establecer los niveles críticos mínimos aceptables para cada variable monitoreada —humedad, luz y temperatura— cuyos valores serán empleados por el sistema para generar alertas automáticas.

Finalmente, al seleccionar la pestaña PEOPLE, el sistema presenta el listado de colaboradores con acceso activo a la zona. El agricultor administrador puede eliminar a un colaborador existente mediante el botón REMOVE, acción que actualiza la lista de forma inmediata. Para añadir un nuevo colaborador, utiliza la barra de búsqueda superior para localizar a otro agricultor registrado en la plataforma y presiona el botón INVITE, con lo que el sistema envía una solicitud de acceso al usuario seleccionado.

#### User Goal para Segmento 2: Asociaciones Agrarias 
Como miembro de una asociación agraria, quiero consultar el análisis visual del estado de germinación y crecimiento de todas las zonas de cultivo gestionadas por la asociación, generado por la inteligencia artificial de Grotix, para conocer el progreso biológico de cada parcela sin necesidad de ser un especialista en botánica.

**Task flow:**

<img src="https://imgur.com/IZu6svL.png">

**Wireflow:**

<img src="https://imgur.com/LsYElfX.png">

Para poder consultar el diagnóstico fenológico que ofrece el módulo de inteligencia artificial de Grotix, el usuario accede, en primer lugar, a la pantalla de Cultivation Areas (Zones), ya sea tocando el ícono central de brote en la barra de navegación inferior o a través del logotipo de Grotix en la cabecera. En esta pantalla se presenta el listado completo de las zonas registradas por la asociación, cada una con su imagen representativa, nombre, timestamp de última sincronización y una etiqueta de estado de sensores —verde si todos están activos, roja si alguno presenta falla.

Desde cualquier pantalla de la aplicación, al presionar el ícono de destello (✦ AI Advisor) en la barra de navegación inferior, el sistema navega hacia la pantalla de AI Image Processing. En ella se muestra el indicador de confianza del modelo (AI Trust Level: 80%) y, bajo el título ZONE STATUS, el listado de todas las zonas de la asociación con sus respectivas tarjetas. Cada tarjeta presenta la imagen capturada por la cámara del microcontrolador IoT, el nombre de la zona y la etiqueta de etapa fenológica diagnosticada por el modelo (ej. Stage: SEED, Stage: GERMINATION). Si el usuario desea actualizar el diagnóstico de una zona específica, puede presionar el ícono de sincronización (↻) en la tarjeta correspondiente, tras lo cual el sistema procesa la imagen más reciente disponible y actualiza la etiqueta fenológica en pantalla.

Para acceder al detalle completo de una zona, el usuario toca directamente la tarjeta de la zona de interés. Asimismo, si gestiona una cantidad considerable de parcelas, puede utilizar la barra de búsqueda superior para filtrar las zonas por nombre y localizar rápidamente el área deseada. En ambos casos, el sistema navega hacia la pantalla dashboard_main de la zona seleccionada, donde se muestran las métricas de los sensores en tiempo real —humedad, luz y temperatura— actualizadas con los datos del dispositivo IoT asociado a esa parcela.

### 5.4.3. Applications Mock-ups
La etapa de Mockups representa la traducción fiel de la estructura definida en los wireframes a una propuesta visual de alta fidelidad. Utilizando los Style Guidelines de Grotix, esta sección ilustra el look and feel final de la plataforma. El objetivo es mostrar al detalle cómo se aplicarán los elementos visuales para generar una interfaz coherente, atractiva y funcional. Los mockups no solo respetan la jerarquía y el flujo de navegación establecidos, sino que también garantizan que la experiencia de usuario (UX) sea intuitiva y esté completamente alineada con el tono cálido y motivador de la marca.

#### Web App (For Staff)

<img src="https://imgur.com/8tqpyef.png">

El Main Dashboard de la web app para el staff de Grotix presenta una interfaz intuitiva en modo oscuro organizada en tres columnas clave para la gestión operativa. La primera sección permite visualizar el estatus de los clientes activos, mientras que la columna central detalla los contratos vigentes con sus respectivas fechas de inicio. Finalmente, la sección de dispositivos monitorea en tiempo real la conectividad de los microcontroladores, diferenciando mediante etiquetas de color si se encuentran online u offline.

<img src="https://imgur.com/8uaoX4H.png">

La pantalla de Search de la web app para el staff ofrece una herramienta de búsqueda global integrada en una interfaz de modo oscuro, diseñada para filtrar agricultores, contratos o dispositivos de forma simultánea. Los resultados se organizan en tarjetas detalladas que muestran perfiles de usuarios con interruptores de estado, información de microcontroladores con su última fecha de mantenimiento, y el estatus de los contratos (como Active, Draft o Terminated). Esta vista unificada facilita la gestión rápida y el monitoreo del ecosistema de Grotix mediante una disposición limpia y etiquetas visuales de alta legibilidad.

<img src="https://imgur.com/dy6NkWC.png">

La pantalla de Agriculturists de la web app de Grotix presenta una interfaz de gestión de clientes organizada en una cuadrícula de tarjetas individuales bajo una estética de modo oscuro. Cada tarjeta muestra la fotografía del agricultor, su nombre completo y un interruptor (switch) lateral que permite activar o desactivar su estatus de forma rápida y visual. Esta disposición facilita al staff la supervisión y el control administrativo de los usuarios de la plataforma mediante un diseño limpio y funcional.

<img src="https://imgur.com/DRh4k2q.png">

La pantalla Single Agriculturist de la web app para el staff de Grotix ofrece una vista detallada del perfil de un usuario específico dentro de un contenedor centralizado en modo oscuro. En la parte superior del perfil, se muestra la fotografía del agricultor junto a su nombre y ocupación, acompañada de un interruptor de estado que indica claramente si el usuario está Active. El resto del formulario organiza la información de contacto y administrativa en campos de lectura, incluyendo la asociación a la que pertenece, correo electrónico, número telefónico y el rol asignado dentro de la plataforma. Esta interfaz permite al staff revisar los datos personales de manera estructurada y rápida mediante un diseño limpio y profesional.

<img src="https://imgur.com/oa5NYdM.png">

La pantalla de Contracts de la web app para el staff de Grotix presenta un repositorio centralizado de los acuerdos legales con clientes, organizado en una cuadrícula de tarjetas descriptivas sobre un fondo oscuro. En la parte superior, la interfaz incluye botones para alternar entre la vista de List y la opción de Add para registrar nuevos contratos, además de un icono de filtros para búsquedas avanzadas. Cada tarjeta identifica a la organización, la fecha de inicio del servicio y el estado actual del contrato mediante etiquetas de color, tales como Active, Draft, Pending, Renewed, Expired o Terminated. Esta visualización permite al equipo administrativo supervisar el ciclo de vida de cada suscripción y la vigencia de los servicios de manera eficiente.

<img src="https://imgur.com/4m3Fa2r.png">

La pantalla de Devices de la aplicación web de Grotix permite al staff supervisar el hardware desplegado mediante una interfaz en modo oscuro organizada en una cuadrícula de tarjetas de microcontroladores. En la sección superior, el usuario puede navegar entre las funciones de List, Logbook y Maintenance, además de acceder a herramientas de filtrado. Cada tarjeta identifica un dispositivo por su código único y muestra en tiempo real si su estado es Online u Offline, junto con la fecha y hora exacta de su último mantenimiento. Esta disposición facilita un monitoreo técnico preventivo y una respuesta rápida ante cualquier desconexión en las zonas de cultivo.

<img src="https://imgur.com/IW67762.png">

La sección Logbook dentro del módulo de Devices presenta un formulario de registro diseñado para documentar las intervenciones técnicas realizadas en el hardware de Grotix. Enmarcada en una interfaz de modo oscuro, la pantalla permite seleccionar el Device ID correspondiente, detallar la actividad realizada en un campo de texto amplio para la Action y definir el Status After mediante botones de selección rápida para marcar el dispositivo como Online u Offline. Finalmente, la vista incluye botones de acción destacados para Save o Cancel, asegurando que cada mantenimiento quede registrado correctamente en el historial del sistema.

La vista de Maintenance en el módulo de dispositivos de Grotix proporciona una interfaz de control operativo para gestionar las tareas de soporte técnico sobre el hardware. Manteniendo la estética de modo oscuro, esta pantalla organiza los microcontroladores en tarjetas que incluyen botones de acción contextuales: Start Maintenance para iniciar un proceso de revisión o End Maintenance para concluir intervenciones en curso. Cada tarjeta muestra el ID del dispositivo, su estado de conectividad actual y la marca temporal de su último mantenimiento, permitiendo al staff coordinar las tareas de campo y asegurar que todos los equipos funcionen correctamente dentro de los cronogramas establecidos.

<img src="https://imgur.com/o2dVBKk.png">

La pantalla de Single Device en la web app de Grotix ofrece una vista técnica integral de un microcontrolador específico, dividida en dos secciones principales sobre un fondo oscuro. En el panel izquierdo, se presentan los detalles técnicos del hardware, incluyendo el Zone ID, el modelo del dispositivo, su dirección MAC y el estatus de conexión en tiempo real (ONLINE). La sección derecha está dedicada a los Maintenance Logs, donde se listan de forma cronológica las intervenciones realizadas, detallando fechas y acciones técnicas específicas como actualizaciones de firmware o reemplazo de componentes. Esta estructura permite al staff de Grotix tener una trazabilidad completa del ciclo de vida y el estado operativo de cada unidad de hardware.

<img src="https://imgur.com/MOUuNl9.png">

La pantalla de Crops de la aplicación web para el staff de Grotix presenta un catálogo visual de los tipos de cultivos soportados por la plataforma, organizado en una cuadrícula de tarjetas descriptivas sobre un fondo oscuro. En la parte superior, se incluye una barra de búsqueda que permite filtrar los resultados por nombre común o científico. Cada tarjeta contiene una imagen representativa del cultivo y su nombre correspondiente (como tomate, zanahoria o albahaca), facilitando una identificación rápida y clara para la gestión agrícola. Esta interfaz mantiene la coherencia visual con el resto del sistema, ofreciendo una navegación fluida a través de la barra lateral persistente.

<img src="https://imgur.com/lOffVna.png">

La pantalla de Single Crop de la aplicación web de Grotix permite al staff gestionar los parámetros específicos de un cultivo, como el brócoli, mediante una interfaz técnica en modo oscuro. En el panel izquierdo, se muestra una imagen identificativa junto al nombre común y científico del cultivo, además de un selector para definir el Maximum Stress Time permitido. La sección derecha, bajo el encabezado Statistics, presenta controles deslizantes para configurar los rangos ideales de temperatura, humedad y luz, permitiendo ajustar los niveles óptimos de crecimiento de forma visual. Finalmente, la pantalla incluye botones prominentes para Save o Delete, asegurando un control administrativo total sobre la base de datos de cultivos.

<img src="https://imgur.com/Lg2kWvK.png">

La pantalla de Profile en la aplicación web ofrece una vista consolidada de la información del usuario autenticado. En el panel central, se muestra la identidad del equipo o usuario, incluyendo su nombre, el registro del último acceso al sistema y una etiqueta de estado ACTIVE. Debajo de la cabecera, se organizan campos informativos sobre la cuenta. La pantalla se completa con botones de acción rápida para realizar cambios mediante la opción Edit o para finalizar la sesión de forma segura con el botón Log Out.

#### Mobile App (For Clients)

<img src="https://imgur.com/8jlsiLb.png">

La pantalla de Main Dashboard de la aplicación móvil de Grotix constituye el centro de control operativo para el usuario, permitiendo el monitoreo en tiempo real de zonas de cultivo específicas. Bajo una estética de modo oscuro, la interfaz presenta una tarjeta informativa del cultivo que detalla el estado de germinación y las coordenadas geográficas exactas de la plantación. El núcleo de la pantalla utiliza indicadores visuales dinámicos para reportar variables críticas: un gráfico circular para la humedad (Moisture) que indica niveles óptimos, una barra de progreso para la radiación lumínica y medidores de temperatura, todos acompañados por marcas de tiempo de la última actualización para garantizar la precisión de los datos. Asimismo, más abajo en la pantalla sale el resumen de sensores utilizados en esta zona. Esta disposición funcional se complementa con una barra de navegación inferior y pestañas superiores para ajustes y gestión de participantes, facilitando una toma de decisiones informada para mejorar la cosecha.

<img src="https://imgur.com/r2mHG6M.png">

La pantalla de Dashboard Settings en la aplicación móvil de Grotix permite al usuario personalizar de manera precisa el comportamiento del hardware en una zona de cultivo específica. En la sección de Irrigation, la interfaz ofrece interruptores para habilitar el riego automático o iniciar un riego manual de forma inmediata, además de un selector para establecer el Max. time of irrigation. Complementariamente, el apartado de Critical Levels permite definir los umbrales mínimos de humedad y radiación, así como el rango de temperatura ideal, asegurando que el sistema actúe según los requerimientos técnicos del cultivo. Esta configuración granular garantiza una gestión eficiente de los recursos y la protección de la salud de las plantas directamente desde el dispositivo móvil.

<img src="https://imgur.com/yXIWl2L.png">

La pantalla de Dashboard People en la aplicación móvil de Grotix facilita la gestión colaborativa de las zonas de cultivo al permitir la administración de los participantes asociados a cada proyecto. Bajo una interfaz de modo oscuro, esta sección presenta una lista de agricultores con sus respectivas fotografías, nombres y roles, integrando una barra de búsqueda superior para una localización rápida de usuarios. Los controles interactivos permiten invitar a nuevos colaboradores o remover a miembros existentes de la zona seleccionada, asegurando que el equipo de trabajo esté siempre actualizado y coordinado en las tareas de monitoreo agrícola.

<img src="https://imgur.com/k3dk9H8.png">

La pantalla de AI Image Processing en la aplicación móvil de Grotix permite al usuario visualizar el análisis avanzado de sus cultivos mediante inteligencia artificial. En la parte superior, se destaca el AI Trust Level, que indica el grado de confiabilidad del procesamiento actual (ej. 80%). Bajo la sección de Zone Status, se presenta un listado de las diferentes áreas de cultivo, mostrando para cada una la etapa de crecimiento detectada —como Seed o Germination— junto con la hora de la última actualización. Esta interfaz facilita el seguimiento automatizado del desarrollo de las plantas, permitiendo una supervisión precisa de múltiples zonas desde una sola vista centralizada.

<img src="https://imgur.com/YzqYCzn.png">

La pantalla de Cultivation Areas en la aplicación móvil de Grotix sirve como el inventario principal de los sectores de cultivo gestionados por el usuario. En esta interfaz de modo oscuro, se listan todas las zonas activas (como la "Zona Tomatitos" o el "Área de Zanahorias") mediante tarjetas que incluyen una imagen referencial, el nombre del área y la hora de su última sincronización. Un elemento crítico de esta pantalla es el indicador de estado de los dispositivos IoT, el cual notifica visualmente si todos los sensores operan correctamente o si existen fallas técnicas (ej. "Some sensors are failing"). Además, la parte superior integra herramientas funcionales para buscar zonas específicas, añadir nuevas áreas mediante un botón de "+" y acceder a filtros de configuración, manteniendo la coherencia con la barra de navegación inferior del sistema.

<img src="https://imgur.com/mvf3xxY.png">

La pantalla de Generate Report en la aplicación móvil de Grotix proporciona al usuario las herramientas necesarias para extraer y analizar datos históricos de sus cultivos de manera personalizada. Manteniendo la línea visual de modo oscuro de la plataforma, esta sección se enfoca específicamente en reportes de riego (Irrigation), permitiendo configurar rangos de tiempo exactos mediante selectores de fecha de inicio y fin, o mediante un menú desplegable para periodos predefinidos (3 meses, 6 meses, etc.). Una vez establecidos los parámetros, el botón de GENERATE procesa la información para mostrarla en el área de visualización inferior, facilitando al agricultor la revisión de tendencias y el consumo de recursos para una mejor planificación de futuras cosechas.

<img src="https://imgur.com/8zwQ6ze.png">

La pantalla de Personal Info en la aplicación móvil de Grotix permite al agricultor gestionar su identidad digital y datos de contacto de manera centralizada. Bajo un saludo personalizado, la interfaz despliega un formulario que incluye campos para el nombre completo, correo electrónico, número telefónico y el rol del usuario, además de un espacio dedicado para la visualización y actualización de la foto de perfil. En la base de la tarjeta informativa, se ubican los botones de Edit para realizar modificaciones y Log Out para cerrar la sesión, manteniendo la coherencia visual del modo oscuro y la accesibilidad a través de la barra de navegación inferior que conecta con el resto de los módulos de la plataforma.
Abajo de esta sección podrá encontrar una línea de soporte para contactar con el staff en caso de que uno de sus sensores esté fallando.

<img src="https://imgur.com/YkT2kZR.png">

La sección de Notifications en la aplicación móvil de Grotix se presenta como un panel superpuesto de acceso rápido (drawer) que mantiene al usuario informado sobre eventos clave del sistema. Con un diseño limpio en modo oscuro, el panel organiza las alertas de forma cronológica, permitiendo visualizar mensajes de bienvenida, estados de los sensores o alertas de riego. Cada notificación incluye una opción de eliminación individual mediante un icono de papelera, además de un botón global de CLEAR ALL en la parte inferior para gestionar el historial de avisos de manera eficiente. Esta funcionalidad garantiza que el agricultor no pierda de vista ninguna actualización crítica sobre el rendimiento y la salud de sus cultivos.

<img src="https://imgur.com/DG7GyWX.png">

La vista de Configuration dentro del panel de notificaciones de la aplicación móvil permite al usuario personalizar sus preferencias de alerta de manera detallada. En esta sección, el agricultor puede gestionar los canales de recepción mediante interruptores para Push Notifications y Email Notifications. Además, ofrece un control específico sobre el tipo de contenido que genera avisos, permitiendo activar o desactivar alertas para cambios en el riego (irrigation), alcance de niveles críticos en los sensores o actualizaciones sobre el estado de germinación de los cultivos. Esta flexibilidad asegura que el usuario reciba únicamente la información más relevante.


### 5.4.4. Applications User Flow Diagrams

#### Segmento Objetivo #1: Productores Independientes

**Contexto del User Persona (Mateo Rojas):** Él busca optimizar su tiempo, reducir el trabajo manual y necesita una interfaz que no lo abrume tecnológicamente, dándole seguridad sobre su chacra de forma remota.

**User Goal:** Monitorear las variables críticas de su cultivo en tiempo real y delegar el trabajo manual habilitando el riego automático para optimizar su tiempo.

**Task flow:**

<img src="https://imgur.com/tzrXAuM.png">

**User flow:**

<img src="https://imgur.com/D9lPlXx.png">

Para interactuar con el flujo de monitoreo inteligente y automatización que ofrece Grotix, el agricultor accede inicialmente a la pantalla de Cultivation Areas al abrir la aplicación, donde visualiza un listado general de sus parcelas registradas. Al seleccionar una zona específica, como la "Zona Tomatitos", el sistema lo dirige automáticamente a la vista MAIN del Dashboard. En esta sección, se despliegan en tiempo real las métricas críticas capturadas por los sensores IoT: el nivel de humedad del suelo representado porcentualmente, la intensidad lumínica y la temperatura ambiental. Estas variables permiten al usuario supervisar la salud de su cultivo de manera inmediata, alertando visualmente si algún parámetro se encuentra fuera de los umbrales seguros establecidos.  Sin perder tiempo en navegaciones complejas, el agricultor puede desplazarse hacia la pestaña SETTINGS mediante un toque en la barra de navegación superior de la zona. En esta vista, el usuario tiene la capacidad de configurar con precisión los niveles críticos mínimos para cada variable ambiental (humedad, luz y temperatura), así como activar el interruptor de riego automático mediante un toggle switch. Esta acción garantiza que el hardware en campo responda de forma autónoma a las necesidades hídricas detectadas, optimizando el uso del recurso y permitiendo al agricultor delegar el esfuerzo físico del riego manual.  Finalmente, para validar el progreso biológico y obtener una mayor tranquilidad sobre el estado de su inversión, el usuario selecciona el icono de destello en la barra de navegación inferior para acceder al módulo de AI Image Processing. Aquí, el sistema muestra el diagnóstico generado por inteligencia artificial, identificando automáticamente la etapa fenológica actual del cultivo (como germinación o crecimiento) junto con un nivel de confianza del análisis. Este flujo integrado permite una supervisión remota completa y ágil, transformando datos sensoriales y visuales complejos en decisiones técnicas seguras para el productor.

#### Segmento Objetivo #2: Asociaciones Agrarias (Carlos Mendoza)

**Contexto del Persona (Carlos Mendoza):** Él es un gerente racional que necesita datos precisos, trazabilidad para exportación (GlobalGAP) y control sobre múltiples agricultores o zonas desde una sola plataforma.

**User Goal:** Auditar el personal asignado a una zona de cultivo específica y generar un reporte de riego trimestral para cumplir con los estándares de calidad de exportación.

**Task flow:**

<img src="https://imgur.com/AVhJZ1G.png">

**User flow:**

<img src="https://imgur.com/R7bOnKO.png">

Para que el usuario logre auditar el personal asignado a una zona de cultivo específica y generar reportes de riego trimestrales que cumplan con los estándares de calidad de exportación, Grotix ofrece un flujo administrativo centralizado y eficiente. En primer lugar, si el objetivo es la auditoría de personal, el usuario accede desde la pantalla de Cultivation Areas a la zona específica de interés. Una vez dentro, se desplaza a la vista PEOPLE a través de la barra de navegación superior del dashboard. En esta sección, se visualiza la información detallada de los encargados actuales de la zona y un listado de otros agricultores de la granja disponibles para ser vinculados. El administrador tiene la facultad de gestionar estos accesos de forma dinámica: puede remover a un colaborador existente mediante el botón REMOVE, lo que actualiza la lista al instante, o añadir nuevos integrantes utilizando la barra de búsqueda y presionando el botón INVITE. Este control bidireccional asegura que siempre se tenga claridad sobre quién opera cada sector de la producción.  Por otro lado, para la generación de documentación técnica, el usuario accede a la vista de REPORTS directamente desde el menú de navegación inferior. Dentro de este módulo, el proceso de configuración está diseñado para minimizar errores de entrada: al seleccionar la fecha de inicio del reporte, el sistema utiliza una lógica de autocompletado para determinar la fecha de fin basada en el rango de tiempo seleccionado (por ejemplo, "3 months" para trazabilidad trimestral). El agricultor puede ajustar estos periodos mediante un selector desplegable, lo que actualiza automáticamente los límites temporales del informe. Una vez validados los parámetros, el usuario acciona el botón GENERATE, lo que inicia el procesamiento de la telemetría histórica y la descarga del reporte directamente en el dispositivo. Este flujo garantiza la obtención ágil de pruebas de sostenibilidad y huella hídrica, facilitando el cumplimiento de normativas internacionales.

## 5.5. Applications Prototyping 
Con el objetivo de evaluar y perfeccionar la accesibilidad y la experiencia de usuario (UX) antes del desarrollo final, se elaboró un prototipo interactivo a partir de los mockups de alta fidelidad, centrado exclusivamente en la navegación móvil.
Este modelo funcional simula de forma integral el recorrido del usuario dentro de la aplicación, permitiendo explorar directamente sus secciones, elementos y flujos de interacción tal como se verá en un dispositivo móvil.

El prototipo fue diseñado siguiendo principios de arquitectura de la información clara, jerarquía visual lógica y diseño inclusivo. Se priorizó la facilidad de uso, asegurando que cada componente respete los estándares de usabilidad y coherencia visual para una navegación fluida e intuitiva. Esta versión navegable actúa como una fiel representación de la futura interfaz de la aplicación, siendo clave para validar decisiones de diseño y garantizar una experiencia consistente y accesible.

### Web App (For Staff)

<img src="https://imgur.com/71rEM5m.png">

Video explicativo:

<img src="https://imgur.com/eeRCEYj.png">

Link del video:
[https://drive.google.com/file/d/1DgfYWx-fN4A5AzBG1_7rw40WK8VJpxDh/view?usp=sharing](https://drive.google.com/file/d/1DgfYWx-fN4A5AzBG1_7rw40WK8VJpxDh/view?usp=sharing)

Link al prototipo interactivo:
[https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=40-63&p=f&t=dB36gijF28heh7zW-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A61](https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=40-63&p=f&t=dB36gijF28heh7zW-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A61) 

### Mobile App (For Clients)

<img src="https://imgur.com/pEFL1p9.png">

Video explicativo:

<img src="https://imgur.com/tcKYIvn.png">

Link del video:
[https://drive.google.com/file/d/1_v9BDa8tAwhBIG6wpW-Yj4evmoUe0aWg/view?usp=sharing](https://drive.google.com/file/d/1_v9BDa8tAwhBIG6wpW-Yj4evmoUe0aWg/view?usp=sharing)

Link al prototipo interactivo:
[https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=148-1047&p=f&t=JdOOShNAUIqGebVF-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A62](https://www.figma.com/proto/oG0SittF4VvPKSelZNuj6J/Grotix?node-id=148-1047&p=f&t=JdOOShNAUIqGebVF-1&scaling=scale-down&content-scaling=fixed&page-id=40%3A62) 

## 5.6. IoT Device Design 

El diseño del dispositivo (Device Design) es la fase arquitectónica fundamental que planifica y documenta la interconexión física del hardware, asegurando una asignación lógica de pines, niveles de voltaje adecuados y aislamiento eléctrico para evitar fallos antes del ensamblaje. Bajo este enfoque técnico, la siguiente figura presenta el diagrama del nodo IoT de Grotix, ilustrando la integración del microcontrolador central ESP32-S3 con la red de sensores de percepción y los componentes de actuación e interfaz local. Este esquema sirve como la guía técnica estandarizada para la construcción del circuito, garantizando la estabilidad operativa y la correcta captura de telemetría en el entorno agrícola. 

<img src="https://imgur.com/rQnpDQ8.png">

# CAPÍTULO VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration 

La siguiente tabla describe las herramientas y productos de software que el equipo utilizará para colaborar en el ciclo de vida de Grotix:

| Categoría | Producto | Propósito de uso | Ruta |
|---|---|---|---|
| Project Management | Jira | Seguimiento de tareas, gestión de Sprints y documentación de Historias de Usuario (US) y Técnicas (TS). | [SaaS] [atlassian.com/jira](https://www.atlassian.com/software/jira) |
| UX/UI Design | Figma | Diseño colaborativo y prototipado de la Mobile App, Staff Web App y la Landing Page. | [SaaS] [figma.com](https://www.figma.com) |
| Backend Development | JetBrains Rider | Desarrollo principal de los microservicios en .NET (C#) para Telemetría, Irrigación, Perfiles, entre otros. | [Download] [jetbrains.com/rider](https://www.jetbrains.com/rider) |
| Frontend Development | VS Code | Desarrollo de la aplicación web utilizando Vue.js y Landing Page con HTML, CSS y JS. | [Download] [code.visualstudio.com](https://code.visualstudio.com) |
| Mobile Development | Android Studio | IDE principal para el desarrollo de la aplicación móvil de Grotix utilizando el framework Flutter. | [Download] [developer.android.com](https://developer.android.com/studio) |
| Embedded Systems | VS Code (PlatformIO) | Desarrollo de firmware para los microcontroladores ESP32 utilizando C++. | [Download] [platformio.org](https://platformio.org) |
| API Documentation | Swagger | Documentación interactiva y ejecución de pruebas para los servicios web RESTful. | [Integrated] [swagger.io](https://swagger.io) |
| Cloud Infrastructure | Microsoft Azure | Hosting en la nube, gestión de bases de datos y orquestación del API Gateway del sistema. | [SaaS] [portal.azure.com](https://portal.azure.com) |
| Database Management | MySQL Workbench | Diseño visual y gestión de la Core DB para los datos transaccionales y maestros. | [Download] [dev.mysql.com](https://dev.mysql.com) |
| Software Testing | Postman | Ejecución de pruebas manuales de los endpoints de la API y validación de peticiones HTTP. | [Download] [postman.com](https://postman.com) |
| IoT Debugging | MQTT Explorer | Monitoreo y prueba de los mensajes MQTT enviados entre el ESP32 y el broker en la nube. | [Download] [mqtt-explorer.com](http://mqtt-explorer.com) |
| Containerization | Docker Desktop | Creación y gestión de contenedores ligeros para asegurar un despliegue eficiente de los microservicios. | [Download] [docker.com](https://docker.com) |

### 6.1.2. Source Code Management  
El equipo de Grotix establece GitHub como la plataforma centralizada para la gestión del código fuente y el control de versiones. Este esquema asegura la trazabilidad de las modificaciones y permite una colaboración eficiente en el desarrollo de la solución IoT. 

Cada producto digital cuenta con un repositorio independiente:

| Producto | URL del Repositorio |
|---|---|
| Landing Page | [https://github.com/CeleviGrotix/Grotix_LandingPage](https://github.com/CeleviGrotix/Grotix_LandingPage) |
| Web Services (Backend) | [https://github.com/CeleviGrotix/Grotix_Web_Services](https://github.com/CeleviGrotix/Grotix_Web_Services) |
| Frontend Web Applications | [https://github.com/CeleviGrotix/Grotix_Web](https://github.com/CeleviGrotix/Grotix_Web) |
| Mobile Application (Flutter) | [https://github.com/CeleviGrotix/Grotix_Mobile](https://github.com/CeleviGrotix/Grotix_Mobile) |

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

| User Story Id | User Story Title | Work-Item / Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status (To-do / In-Process / To-Review / Done) |
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

#### 6.2.1.8 Software Deployment Evidence for Sprint Review

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

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning 2

| Campo | Detalle |
|---|---|
| Sprint # | Sprint 2 |
| **Sprint Planning Background** |  |
| Date | 15/05/26 |
| Time | 20:00 |
| Location | Reunión Virtual de Google Meet |
| Prepared By | Cassius Martel |
| Attendees (to planning meeting) | Binda Arbañil, Marcelo Alejandro / Castillo Garay, Ainhoa Lucía / Martel Andrade, Cassius Estefano / Nakamurakare Teruya, Alex Tomio / Rodas Sotomayor, Ernesto / |
| Review Summary | Presentación exitosa de los nuevos microservicios core del sistema IoT (Telemetría, Hardware e Irrigación en .NET) y el microservicio de Análisis de Cultivos con Inteligencia Artificial (Python/FastAPI). Despliegue inicial de la aplicación móvil en Flutter con integración de autenticación, dashboard táctil y gestión de zonas. Optimización exitosa de latencia mediante DTOs y refinamiento de la aplicación Web para la gestión técnica de dispositivos. Todas las tareas (53 SP/Horas) marcadas como "Done". |
| Review Summary | Presentación exitosa de los nuevos microservicios core del sistema IoT (Telemetría, Hardware e Irrigación en .NET) y el microservicio de Análisis de Cultivos con Inteligencia Artificial (Python/FastAPI). Despliegue inicial de la aplicación móvil en Flutter con integración de autenticación, dashboard táctil y gestión de zonas. Optimización exitosa de latencia mediante DTOs y refinamiento de la aplicación Web para la gestión técnica de dispositivos. Todas las tareas (53 SP/Horas) marcadas como "Done". |
| Retrospective Summary | El equipo logró una gran sinergia al paralelizar el desarrollo móvil en Flutter con la expansión masiva de los microservicios backend. Se identificó que la integración del motor de IA en Python requiere un ruteo estricto en el API Gateway. |
| **Sprint Goal & User Stories** |  |
| Sprint 2 Goal | El objetivo de este segundo sprint es expandir la arquitectura de microservicios para soportar la lógica core del ecosistema IoT (Ingesta de Telemetría, Control de Irrigación, Gestión de Hardware) y la inferencia de Inteligencia Artificial mediante FastAPI. Paralelamente, se busca establecer la aplicación móvil multiplataforma (Flutter), brindando a los agricultores acceso a dashboards de monitoreo táctil, gestión de zonas, invitaciones de colaboración y análisis fenológico en tiempo real directamente desde sus smartphones. |
| Sprint 2 Velocity | 56 |
| Sum of Story Points | 53 |
| Sum of Story Points | 53 |

#### 6.2.2.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Frontend & UI/UX | Backend & API | QA & Testing | Infrastructure & Deployment | Project Management |
|---|---|---|---|---|---|---|
| Martel Andrade, Cassius Estefano | kcc12321 | C | C | L | C | L |
| Binda Arbañil, Marcelo Alejandro | MarceHkd | L | C | C | C | C |
| Castillo Garay, Ainhoa Lucía | noaa01100001 | L | C | C | C | C |
| Nakamurakare Teruya, Alex Tomio | kistoo | C | L | C | C | C |
| Rodas Sotomayor, Ernesto | ernesto1718 | C | C | C | L | C |

#### 6.2.2.3. Sprint Backlog 2

| User Story Id | User Story Title | Work-Item / Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status (To-do / In-Process / To-Review / Done) |
|---|---|---|---|---|---:|---|---|
| TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | T57 | Estructura base en Telemetry API | Creación del proyecto base en .NET (C#) y configuración de las rutas del controlador para la ingesta asíncrona. | 3 | Backend Dev | Done |
| TS16 | Implementación del Microservicio de Telemetría e Ingesta IoT (.NET) | T58 | Modelado de contratos lógicos | Definición y validación del esquema de datos JSON estructurados para la recepción de paquetes de telemetría de campo. | 3 | Backend Dev | Done |
| TS20 | Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos | T59 | Poblado de simulación vía Swagger | Diseño y ejecución de endpoints de simulación en Telemetry.Api desde Swagger para popular la base de datos PostgreSQL con lecturas lógicas de sensores. | 3 | Backend Dev | Done |
| TS20 | Configuración de Estrategia de Simulación y Mocking de Telemetría e Ingesta de Datos | T60 | Adaptación de controladores para contingencias | Configuración de controladores para manejar respuestas estáticas controladas y flujos alternos si la base de datos de telemetría no detecta tramas activas. | 2 | Backend Dev | Done |
| TS19 | Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET) | T61 | APIs CRUD de Inventario de Equipos | Desarrollo de endpoints transaccionales en Hardware.Api para registrar, modificar y listar dispositivos de forma virtual. | 4 | Backend Dev | Done |
| TS19 | Implementación del Microservicio de Gestión de Hardware y Dispositivos (.NET) | T62 | Control de estado operacional de activos | Lógica en .NET para actualizar la bandera de estado (Online/Offline/Maintenance) inyectando la propiedad temporal lastSeen bajo validación de casing. | 2 | Backend Dev | Done |
| TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | T63 | Motor de Reglas Hídricas Autónomas | Desarrollo de la lógica de negocio en Irrigation.Api para evaluar las variables y disparar ciclos automáticos lógicos. | 5 | Backend Dev | Done |
| TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | T64 | Controlador de comandos de actuadores | Creación de endpoints técnicos para recibir acciones de encendido/apagado y simular logs en el historial de irrigación. | 3 | Backend Dev | Done |
| TS17 | Implementación del Microservicio de Control y Orquestación de Riego (.NET) | T65 | Pruebas Unitarias integrales con xUnit | Escritura y ejecución de cobertura de pruebas automatizadas con xUnit en las capas de negocio de cada microservicio para validar el comportamiento del dominio. | 5 | Backend Dev | Done |
| TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python) | T66 | Servidor base y API en FastAPI | Configuración del entorno de desarrollo en Python con FastAPI y endpoints HTTP destinados a la recepción de recursos visuales de parcelas. | 4 | Backend Dev | Done |
| TS18 | Desarrollo del Microservicio de Análisis de Cultivos e Integración de IA (Python) | T67 | Integración de pipeline de inferencia IA | Programación del script en Python para conectarse mediante API Key a los servicios lógicos de IA y retornar la clasificación fenológica sin enlace de hardware ESP32. | 6 | Backend Dev | Done |
| US25 | Modificación de datos personales y de contacto | T68 | Refactorización de endpoints de perfil | Correcciones y mejoras técnicas en el microservicio de identidades para el guardado consistente de datos de contacto de agricultores. | 5 | Backend Dev | Done |
| US25 | Modificación de datos personales y de contacto | T69 | Rediseño de Layout de Profile Web | Ajuste visual, unificación de estados reactivos y limpieza de conflictos de fusión en el componente MyProfileView.vue dentro de Vue 3. | 4 | Frontend Dev | Done |
| US25 | Modificación de datos personales y de contacto | T70 | Maquetación UI móvil de sección Perfil | Construcción responsiva de la pantalla de gestión de perfil dentro de la aplicación móvil basándose en los wireframes. | 4 | Frontend Dev | Done |
| US15 | Organización de dispositivos por zonas y especies | T71 | Optimización de consultas estructurales | Corrección de bases de datos y asignación jerárquica de granjas/lotes dentro del microservicio Cultivation.Api. | 5 | Backend Dev | Done |
| US15 | Organización de dispositivos por zonas y especies | T72 | UI móvil de formularios de creación | Implementación en Flutter de las vistas de ingreso de parcelas y asociación a variedades del catálogo botánico. | 6 | Frontend Dev | Done |
| TS12 | Gestión de mantenimiento de dispositivos IoT | T73 | UI Web de Inventario con Filtros Dinámicos | Construcción de DevicesListView incorporando propiedades computadas para el filtrado reactivo en tiempo real por ID, texto y estado. | 6 | Frontend Dev | Done |
| TS12 | Gestión de mantenimiento de dispositivos IoT | T74 | UI Web de Bitácora Técnica Depurada | Ajuste de DeviceLogbookView.vue aislando el guardado atómico hacia estados ONLINE/OFFLINE, excluyendo la bandera manual de mantenimiento. | 6 | Frontend Dev | Done |
| TS12 | Gestión de mantenimiento de dispositivos IoT | T75 | Integración de colecciones de dispositivos | Inyección de colecciones controladas y mapeo del campo de fecha corregido a lastSeen para poblar adecuadamente la UI del frontend. | 4 | Frontend Dev | Done |
| TS11 | Gestión de Capas de Datos Mock de la Aplicación Móvil | T76 | UI Móvil de Vista de Detalle de Zona Individual | Construcción y maquetación de la pantalla móvil de detalle por zona en Flutter conectando variables directas reales desde Cultivation.Api. | 5 | Frontend Dev | Done |
| TS11 | Gestión de Capas de Datos Mock de la Aplicación Móvil | T77 | Estructuras Mock para Reportes, Notis y Sensores | Desarrollo de clases estáticas y repositorios temporales en Flutter para renderizar la UI de reportes históricos, notificaciones y gráficas de sensores. | 4 | Frontend Dev | Done |
| TS15 | Configuración de Arquitectura Base y Scaffolding para la App Móvil | T78 | Inicialización, Capas y Clientes Flutter | Setup estructural bajo arquitectura limpia, empaquetado de cliente HTTP base apuntando al API Gateway, ruteo básico e instalación de paquetes de estado. | 6 | Frontend Dev | Done |
| US24 | Registro, inicio y cierre de sesión de usuario | T79 | UI móvil de formulario de accesos Login | Maquetación estricta de la pantalla de Login adaptada a la guía gráfica y almacenamiento de tokens JWT. Flujos de envío de correo/registro omitidos. | 5 | Frontend Dev | Done |
| US31 | Compartir acceso de lectura y monitoreo a otros usuarios | T80 | UI móvil de campos de invitación | Desarrollo del formulario visual en Flutter para ingresar colaboradores secundarios. | 5 | Frontend Dev | Done |
| US14 | Dashboard de Monitoreo Integral y Resumen de Estado | T81 | UI de Dashboard táctil principal | Maquetación responsiva en Flutter de la pantalla principal de telemetría respetando los indicadores y el diseño circular del wireframe. | 7 | Frontend Dev | Done |
| US14 | Dashboard de Monitoreo Integral y Resumen de Estado | T82 | Interpolación de Sensores Mock | Consumo del repositorio mock móvil para inyectar datos reactivos de humedad de suelo, luz y temperatura ambiente en los medidores gráficos. | 4 | Frontend Dev | Done |
| US22 | Clasificación del estado fenológico mediante Inteligencia Artificial | T83 | UI móvil de análisis visual de cultivo | Creación del submódulo móvil en Flutter para desplegar la pantalla de análisis de salud vegetal renderizando las imágenes procesadas por el API de Python. | 6 | Frontend Dev | Done |
| US21 | Generación y descarga de reportes históricos | T84 | UI móvil de sección de reportes | Maquetación estética en Flutter de la pantalla de reportes proyectando los tres datos clave en UI. | 5 | Frontend Dev | Done |
| TS04 | Optimización de Latencia y Eficiencia en el Procesamiento | T85 | Afinamiento de DTOs en capas backend | Ajuste fino de objetos de transferencia de datos en .NET para truncar nulos, acelerando drásticamente el peso de las tramas enviadas a las apps móviles. | 4 | Backend Dev | Done |

**Total de tareas:** 29

**Sum of Estimation Hours:** 131

#### 6.2.2.4. Development Evidence for Sprint Review

Durante este Sprint se realizaron avances en la implementación de la solución, tanto en los Web Services como en las aplicaciones web y móvil. Se desarrollaron nuevos endpoints, integraciones con dispositivos y sensores, funcionalidades de búsqueda y filtrado, mejoras en la gestión de perfiles y visualización de datos, así como configuraciones necesarias para el despliegue de la plataforma.

Asimismo, se ejecutaron actividades de corrección de incidencias, optimización de componentes, integración de módulos y actualización de configuraciones de infraestructura. Los commits presentados a continuación evidencian el progreso realizado y las funcionalidades implementadas para cumplir con los objetivos definidos para el Sprint.

**Repository: Grotix_Web**

- **Branch:** develop
- **Total Commits:** 17

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Web | develop | 59797d2 | Merge branch 'develop' of https://github.com/CeleviGrotix/Grotix_Web into develop | Sincronización de cambios entre ramas. | 14/05/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web | develop | 4b4e221 | Fix crops data source | Corrección de fuente de datos de cultivos. | 14/05/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web | develop | dce5652 | feat: make web app fully responsive | Adaptación de la interfaz a todos los dispositivos. | 14/05/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web | develop | 268500e | Add secret | Incorporación de configuración segura. | 14/05/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web | develop | cf4109f | Add DeviceDetailView | Creación de vista de detalle de dispositivos. | 1/06/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web | develop | d171564 | fix: resolve profile page merge conflicts | Resolución de conflictos en perfil. | 1/06/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web | develop | 064a227 | Fix: conflictos resueltos | Corrección de conflictos de integración. | 1/06/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web | develop | 6445d1d | Fix profile view | Ajustes en la vista de perfil. | 1/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web | develop | 7732c44 | Deploy configuration | Configuración para despliegue. | 6/06/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web | develop | ef72c40 | feat: integrate real device data into search results and dashboard views | Integración de datos reales de dispositivos. | 6/06/2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Web | develop | 32d3808 | fix: Add TaxId to Profile | Adición del campo TaxId al perfil. | 6/06/2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Web | develop | 609560b | feat: rediseño premium UI de dispositivos | Mejora visual de la interfaz de dispositivos. | 6/06/2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Web | develop | 50b5095 | feat: implementacion de filtros | Implementación de filtros de búsqueda. | 6/06/2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Web | develop | 3d62ec7 | Update useDeviceStore.js | Actualización de gestión de dispositivos. | 7/06/2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Web | develop | 29d6c7f | Update DeviceApi.js | Actualización de servicios de dispositivos. | 7/06/2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Web | develop | 6a80a81 | Update useSearchStore.js | Actualización de lógica de búsqueda. | 7/06/2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Web | develop | 4f8ed60 | Update .firebaserc | Actualización de configuración Firebase. | 7/06/2026 |

**Repository: Grotix_Mobile**

- **Branch:** develop
- **Total Commits:** 35

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 20ba582 | first commit | Inicialización del proyecto. | 30/05/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 4d4572b | Profile implementation | Implementación de perfil. | 31/05/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 2fe4db3 | Login implementation | Implementación de inicio de sesión. | 31/05/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c79eda2 | Authentication initial implementation | Implementación inicial de autenticación. | 31/05/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 2872f02 | smol changes | Ajustes menores. | 31/05/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | d2f8fdf | Dashboard implementation | Implementación de dashboard. | 31/05/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 10653ce | Reports implementation | Implementación de reportes. | 31/05/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | ec558f2 | i18n and Profile implementation | Soporte multilenguaje y perfil. | 31/05/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 905deff | Initial design of fundamental views | Diseño inicial de vistas. | 31/05/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 9cd2a02 | Updates in navigation | Actualización de navegación. | 31/05/2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | f5b5784 | Main shell - Navigation initial implementation | Actualización de funcionalidades. | 31/05/2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 7420fdf | Fixing zone detail view | Actualización de funcionalidades. | 1/06/2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 2f257c5 | Creating zone detail view | Actualización de funcionalidades. | 1/06/2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 16854d8 | Fixing some zone issues | Actualización de funcionalidades. | 1/06/2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 91e07bb | Improvement in data from auth user | Actualización de funcionalidades. | 1/06/2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 1d121c9 | Zones view improvement | Actualización de funcionalidades. | 1/06/2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | f94957b | Zones application | Actualización de funcionalidades. | 1/06/2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 38fae52 | Supervision application | Actualización de funcionalidades. | 1/06/2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 2b7e571 | creating new entities | Actualización de funcionalidades. | 1/06/2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 9bd5a17 | Updating list of zones in AI Image Processing | Actualización de funcionalidades. | 2/06/2026 |
| #21 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 0b007b9 | Main View in Dashboard updates | Actualización de funcionalidades. | 2/06/2026 |
| #22 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 64aaf40 | Dashbard updating | Actualización de funcionalidades. | 2/06/2026 |
| #23 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 47f966c | mocking notifications | Actualización de funcionalidades. | 5/06/2026 |
| #24 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 186315f | Improving People tab in dashboard | Actualización de funcionalidades. | 5/06/2026 |
| #25 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 9b7b188 | Fixing Settings tab | Actualización de funcionalidades. | 5/06/2026 |
| #26 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | df97d4a | Publish APK to GitHub Releases | Actualización de funcionalidades. | 6/06/2026 |
| #27 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 44d3ed9 | Fix Flutter version in CI | Actualización de funcionalidades. | 6/06/2026 |
| #28 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 647fdae | Add APK build workflow | Actualización de funcionalidades. | 6/06/2026 |
| #29 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c710f2f | Some updates in Register and Profile | Actualización de funcionalidades. | 6/06/2026 |
| #30 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 0b19316 | Update AndroidManifest.xml | Actualización de funcionalidades. | 7/06/2026 |
| #31 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 33e11f1 | Update build-apk.yml | Actualización de funcionalidades. | 7/06/2026 |
| #32 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 63fe4d4 | Trigger v1.0.0 release | Actualización de funcionalidades. | 7/06/2026 |
| #33 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 62bed46 | Trigger release build | Actualización de funcionalidades. | 7/06/2026 |
| #34 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | dd28a14 | Release v1.0.0 | Actualización de funcionalidades. | 7/06/2026 |
| #35 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | b4f20c7 | Add INTERNET permission for release build | Actualización de funcionalidades. | 7/06/2026 |

**Repository: Grotix_Crop_Analysis**

- **Branch:** HttpCrop
- **Total Commits:** 3

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Crop_Analysis | HttpCrop | daa4c79 | esp-http-IA | Implementación de integración HTTP para servicios de inteligencia artificial. | 4/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Crop_Analysis | HttpCrop | 37c9348 | IA-HTTP | Configuración de comunicación entre módulos de IA y servicios HTTP. | 4/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Crop_Analysis | HttpCrop | 4bd9b98 | Initial commit | Inicialización del proyecto y estructura base del repositorio. | 4/06/2026 |

**Repository: Grotix_Web_Services**

- **Branch:** develop
- **Total Commits:** 61

| Secuencia | Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|---|
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | c8acb77 | Add irrigation cycle bounded context | Implementación de hardware. | 26/05/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | f021636 | Add hardware device bounded context | Implementación de telemetría. | 26/05/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 2ebc912 | Add telemetry bc | Mejoras en perfiles. | 26/05/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 105c569 | refactor: formalize Profiles persistence in dedicated DbContext | Refactorización del sistema. | 26/05/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | fc1c5aa | refactor: split cultivation area persistence into dedicated DbContext | Refactorización del sistema. | 26/05/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 7a7dfb4 | refactor split IAM persistence into dedicated DbContext | Corrección de incidencias. | 26/05/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 8d1d4b9 | chore fix nullability warnings | Refactorización del sistema. | 26/05/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 49138af | refactor decouple IAM and modularize service wiring | Actualización de migraciones. | 26/05/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | e05ef29 | fix migration snapshot drift in Grotix.Persistence | Refactorización del sistema. | 26/05/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 4a3a4a7 | refactor: split backend into class libraries and extract shared persistence | Refactorización del sistema. | 26/05/2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 5a31c3f | refactor: isolate shared service contracts | Refactorización del sistema. | 26/05/2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 87136bb | refactor: extract auth | Actualización de funcionalidades. | 26/05/2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | c0bec30 | feat(backend): cloud diagram tables and maintenance/analysis APIs | Implementación de alertas. | 27/05/2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 31386c7 | Implement alerts | Incorporación de endpoint. | 27/05/2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | c8be4e0 | Add endpoints for sensors and actuators | Corrección de incidencias. | 27/05/2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | a91cb86 | fix | Corrección de incidencias. | 27/05/2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 87e3750 | Fix | Ajustes en endpoint. | 27/05/2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 0c57a46 | Delete duplicate endpoint | Actualización de funcionalidades. | 27/05/2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | bcfef1c | Add data persistence rules | Incorporación de endpoint. | 27/05/2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 9dd0ec6 | Add get members per association endpoint | Corrección de incidencias. | 27/05/2026 |
| #21 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 8f920b8 | Fix zone member management | Actualización de funcionalidades. | 27/05/2026 |
| #22 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | ec7114c | Link farm to association | Corrección de incidencias. | 27/05/2026 |
| #23 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | a7bd5da | Fix contract creation | Actualización de funcionalidades. | 27/05/2026 |
| #24 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 2d3c4a3 | Implement search handler | Actualización de migraciones. | 27/05/2026 |
| #25 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 26cbbda | fix(migrations): enable EF tooling for hardware/irrigation APIs and sync telemetry/hardware/irrigation database models | Implementación de hardware. | 27/05/2026 |
| #26 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | b820126 | feat(hardware) | Integración de clima. | 27/05/2026 |
| #27 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 4801361 | feat(irrigation): add weather forecast adapter | Integración con RabbitMQ. | 27/05/2026 |
| #28 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d13d420 | feat(iot): publish and consume actuator commands via RabbitMQ for irrigation control | Mejoras en perfiles. | 27/05/2026 |
| #29 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | e9647d8 | feat(profile): add persisted user notifications inbox and APIs | Implementación de riego. | 27/05/2026 |
| #30 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 91f23e9 | Add post for irrigation schedule | Integración de cambios. | 27/05/2026 |
| #31 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 4fa3259 | Merge branch 'feat/cultivation_area' into develop | Integración de cambios. | 27/05/2026 |
| #32 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 7069ec3 | Merge branch 'feat/profile' into develop | Actualización de configuración. | 27/05/2026 |
| #33 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 600fa01 | chore(config): load env vars from .env at startup and fix nullable warnings | Actualización de configuración. | 27/05/2026 |
| #34 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 44f481b | Add .env configuration | Actualización de funcionalidades. | 27/05/2026 |
| #35 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 64ec682 | Add parameters to users patch for admins | Incorporación de endpoint. | 27/05/2026 |
| #36 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | f297711 | feat(cultivation): add zone member management endpoints | Corrección de incidencias. | 27/05/2026 |
| #37 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d934e39 | unify prefix for controllers | Actualización de configuración. | 27/05/2026 |
| #38 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d527f2f | normalize local env-based configuration across services and gateway | Actualización de migraciones. | 27/05/2026 |
| #39 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 2496748 | Fix migrations | Actualización de migraciones. | 30/05/2026 |
| #40 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d2ef387 | Fix migrations | Actualización de funcionalidades. | 30/05/2026 |
| #41 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 0d33cf5 | Small changes in appsettings for gateway | Incorporación de endpoint. | 31/05/2026 |
| #42 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 8bb49be | Add endpoint | Corrección de incidencias. | 31/05/2026 |
| #43 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 507b84d | Fix gateway | Actualización de configuración. | 31/05/2026 |
| #44 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | e13d4a9 | Add configuration scripts | Actualización de migraciones. | 31/05/2026 |
| #45 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 02e18c5 | Fix migration | Actualización de funcionalidades. | 31/05/2026 |
| #46 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | e037003 | Remove api restrictions | Corrección de incidencias. | 31/05/2026 |
| #47 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 1a805ee | Fix | Actualización de funcionalidades. | 31/05/2026 |
| #48 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | bb4bba7 | Adjust sensor reading parameters | Actualización de migraciones. | 31/05/2026 |
| #49 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 9b0096f | Fix migrations | Ajustes en endpoint. | 31/05/2026 |
| #50 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | a30b7ff | Fix endpoint | Actualización de funcionalidades. | 1/06/2026 |
| #51 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | b14ceb1 | Add health check for zone | Integración de cambios. | 1/06/2026 |
| #52 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 774a972 | Merge branch 'develop' of https://github.com/CeleviGrotix/Grotix_Web_Services into develop | Incorporación de endpoint. | 1/06/2026 |
| #53 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | fa78824 | Add endpoints | Actualización de funcionalidades. | 1/06/2026 |
| #54 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | bd92bde | Updating migrate.ps1 | Actualización de funcionalidades. | 1/06/2026 |
| #55 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 520163f | Connection String changes | Actualización de funcionalidades. | 1/06/2026 |
| #56 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 724261e | Adding connection string in migration command file | Ajustes en endpoint. | 1/06/2026 |
| #57 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | ab2dcc1 | Update permissions for endpoint | Ajustes en endpoint. | 2/06/2026 |
| #58 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 1b7a553 | Change response for endpoint | Configuración de despliegue. | 5/06/2026 |
| #59 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 086273c | Add deployment | Configuración de despliegue. | 5/06/2026 |
| #60 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | efc8978 | Add compressed file for deploy | Corrección de incidencias. | 5/06/2026 |
| #61 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | d6c95b1 | Fix business logic |  | 5/06/2026 |


#### 6.2.2.5. Testing Suite Evidence for Sprint Review

Durante el Sprint 2, se consolidó la estrategia de calidad de Grotix mediante la implementación de una suite de pruebas exhaustiva para los seis Bounded Contexts desarrollados: **Telemetry**, **Irrigation Cycle**, **Cultivation Area**, **Hardware Device**, **Profiles** y **Crop Analysis**.

En el nivel unitario, se desarrollaron un total de **50 pruebas automatizadas** enfocadas en la integridad de los dominios y la lógica de negocio. Estas pruebas validan los invariantes de los agregados, como `IrrigationCycleRecord` o `Microcontroller`, la correcta normalización de los Value Objects y el comportamiento esperado de los servicios de aplicación y motores de diagnóstico bajo diversos escenarios, asegurando una lógica robusta mediante el uso intensivo de mocks.

En el nivel de integración, se implementaron **14 tests** que validan la interacción entre los controladores REST, las capas de servicio y la persistencia. Mediante el uso de bases de datos en memoria (`EF Core InMemory`) y `TestClients` de FastAPI, se verificó el flujo completo de los endpoints, asegurando que las reglas de autorización (`RBAC`) y las validaciones de entrada funcionen correctamente antes de interactuar con la infraestructura real.

Finalmente, en el nivel de aceptación (`BDD`), se redactaron **18 escenarios Gherkin** que cubren los criterios de aceptación críticos de las User Stories del Sprint. Estos tests, implementados mediante SpecFlow (.NET) y Pytest-bdd (Python), garantizan que la funcionalidad desarrollada esté alineada con las necesidades de negocio, cubriendo escenarios clave como la detección de anomalías en telemetría, el control hídrico automatizado, la gestión de mantenimiento técnico y la inferencia de salud vegetal.

**Repositorios de testing**

- **Grotix Web Services (Telemetry, Irrigation Cycle, Profile, Cultivation Area, Hardware Device – rama de testing):** https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite
- **Crop Analysis (rama de testing):** https://github.com/CeleviGrotix/Crop-analysis/tree/test/spring_2_testing_suite

**Commits de la suite de testing**

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite | test/sprint-2-testing-suite | 24e36ac66f3ef941906e48f0b7eff9f009baad5e | testing-suite: Add Unit, Integration and BDD Tests for Telemetry Bounded Context | 03/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite | test/sprint-2-testing-suite | 2784830113cd0e0476c73eab5010f9e4931d1350 | testing-suite: Add Unit, Integration and BDD Tests for Irrigation Cycle Bounded Context | 03/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite | test/sprint-2-testing-suite | b3d058020be2d5aacd996fa303ad1acc3d76f8a4 | testing-suite: Add Unit, Integration and BDD Tests for Cultivation Area Bounded Context | 03/06/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite | test/sprint-2-testing-suite | 6aeca44f84b5f5a7a43952f548987bfe0d900b5f | testing-suite: Add Unit, Integration and BDD Tests for Hardware Device Bounded Context | 03/06/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-2-testing-suite | test/sprint-2-testing-suite | 377c1febed88dfea305d8a173d04a06f05abdf60 | testing-suite: Add Unit, Integration and BDD Tests for Profile Bounded Context | 03/06/2026 |
| #06 | https://github.com/CeleviGrotix/Crop-analysis/tree/test/spring_2_testing_suite | test/sprint_2_testing_suite | 3ce6ae366ffdce7942c0d4960ce18dffec08f734 | Test: Add Unit, Integration and BDD tests for Crop Analysis Service | 06/06/2026 |

**Control de Casos de Prueba - Telemetry Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U01 | ReadingRangeValidator | Unitaria (xUnit) | Lectura física válida | [0-100], Valor 50 | True | Pasó |
| TC-U02 | ReadingRangeValidator | Unitaria (xUnit) | Lectura física menor al mínimo | [0-100], Valor -10 | False | Pasó |
| TC-U03 | ReadingRangeValidator | Unitaria (xUnit) | Lectura física mayor al máximo | [0-100], Valor 150 | False | Pasó |
| TC-U04 | ThresholdEvaluator | Unitaria (xUnit) | Lectura dentro de umbral | 50, Min 20, Max 80 | False (No fuera de rango) | Pasó |
| TC-U05 | ThresholdEvaluator | Unitaria (xUnit) | Lectura menor al umbral mínimo | 10, Min 20, Max 80 | True (Fuera de rango) | Pasó |
| TC-U06 | ThresholdEvaluator | Unitaria (xUnit) | Detectar brecha mínima | 10, Min 20, Max 80 | Retorna 20 | Pasó |
| TC-U07 | ThresholdEvaluator | Unitaria (xUnit) | Detectar brecha máxima | 90, Min 20, Max 80 | Retorna 80 | Pasó |
| TC-U08 | MovingAverageFilter | Unitaria (xUnit) | Suavizado inicial | Lista vacía, Valor 25.5 | Retorna 25.5 | Pasó |
| TC-U09 | MovingAverageFilter | Unitaria (xUnit) | Suavizado con historial | Historial [10, 20], Valor 30 | Retorna 20 | Pasó |
| TC-U10 | TelemetryIngestService | Unitaria (xUnit) | Ingesta de lectura y alerta | Evento de telemetría (25.5 temp) | Se llama a AddAsync 1 vez | Pasó |

**Control de Casos de Prueba - Telemetry Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I01 | TelemetryIngestController | Integración (xUnit) | Ingesta válida como admin | Request con datos, Rol Admin | 202 Accepted | Pasó |
| TC-I02 | TelemetryIngestController | Integración (xUnit) | Validación de dispositivo | DeviceId 0 | 400 Bad Request | Pasó |
| TC-I03 | TelemetryIngestController | Integración (xUnit) | Validación de permisos | Rol "guest" | 403 Forbidden | Pasó |

**Control de Casos de Prueba - Telemetry Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A01 | US11 | Aceptación (BDD) | Detección de lectura anómala | Sensor [0-100], valor 150 | Marcado como inválida | Pasó |
| TC-A02 | US13 | Aceptación (BDD) | Suavizado de señal | Historial [40, 42], nuevo 44 | Promedio 42 | Pasó |
| TC-A03 | US18 | Aceptación (BDD) | Evaluación de umbrales críticos | Umbrales [20, 80], valor 10 | Fuera de rango (BELOW_MIN) | Pasó |

<img src="https://imgur.com/U1um0WH.png">

**Control de Casos de Prueba - Irrigation Cycle Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U11 | IrrigationCalculator | Unitaria (xUnit) | Cálculo con entradas nulas | currentHumidity=null, target=60.0 | Retorna 25 (Default) | Pasó |
| TC-U12 | IrrigationCalculator | Unitaria (xUnit) | Humedad actual >= objetivo | current=65.0, target=60.0 | Retorna 25 (Default) | Pasó |
| TC-U13 | IrrigationCalculator | Unitaria (xUnit) | Cálculo con déficit válido | current=40.0, target=60.0 | Retorna 50 | Pasó |
| TC-U14 | IrrigationCalculator | Unitaria (xUnit) | Estimación de duración | 12 Litros / 5L/min | Retorna 3 minutos | Pasó |
| TC-U15 | IrrigationCalculator | Unitaria (xUnit) | Resolución de duración | 50 Litros, Req 15 min | Retorna 15 | Pasó |
| TC-U16 | IrrigationCycleRecord | Unitaria (xUnit) | Constructor válido | zoneId=1, vol=50, dur=10 | Status = IN_PROGRESS | Pasó |
| TC-U17 | IrrigationCycleRecord | Unitaria (xUnit) | Volumen negativo | vol = -10 | Lanza ArgumentException | Pasó |
| TC-U18 | IrrigationCycleRecord | Unitaria (xUnit) | Completado de ciclo | actualVolume = 45.0 | Status = COMPLETED, EndTime presente | Pasó |
| TC-U19 | IrrigationCycleRecord | Unitaria (xUnit) | Aborto de ciclo | Razón = "MANUAL_CANCEL" | Status = ABORTED, Razón guardada | Pasó |
| TC-U20 | IrrigationCommandSvc | Unitaria (xUnit) | Zona inexistente | zoneId = 99 | Lanza ArgumentException | Pasó |

**Control de Casos de Prueba - Irrigation Cycle Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I04 | IrrigationController | Integración (xUnit) | Inicio de riego manual | zoneId=1, Payload válido | 200 OK con cycleId | Pasó |
| TC-I05 | IrrigationController | Integración (xUnit) | Acceso a zona no autorizada | zoneId=1, isAuthenticated=false | 403 Forbidden | Pasó |
| TC-I06 | IrrigationController | Integración (xUnit) | Ciclo activo en zona existe | zoneId=1, Ciclo ya existe | 409 Conflict | Pasó |

**Control de Casos de Prueba - Irrigation Cycle Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A04 | US20 (Sc2) | Aceptación (BDD) | Cálculo automático de volumen | Objetivo 60%, Actual 40% | Necesidad 50L, duración 10min | Pasó |
| TC-A05 | US19 (Sc1) | Aceptación (BDD) | Registro de ciclo manual | Vol 30L, Dur 6min | Status = IN_PROGRESS | Pasó |
| TC-A06 | US19 (Sc2) | Aceptación (BDD) | Aborto de riego | Razón "Lluvia detectada" | Status = ABORTED, Razón guardada | Pasó |

<img src="https://imgur.com/t0VUo3A.png">

**Control de Casos de Prueba - Cultivation Area Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U21 | DiagnosisEngine | Unitaria (pytest) | Formateo correcto del reporte | Diccionario con respuesta JSON de la IA: health_score, detected_phase, etc. | Reporte formateado correctamente | Pasó |
| TC-U22 | DiagnosisEngine | Unitaria (pytest) | Detección de estado crítico | health_score = 69.9 | Retorna True | Pasó |
| TC-U23 | DiagnosisEngine | Unitaria (pytest) | Detección de estado saludable | health_score = 85.0 | Retorna False | Pasó |
| TC-U24 | Handler | Unitaria (pytest) | Ejecución exitosa y guardado | zone_id=10, path="/img/crop.jpg" | Repositorio llama a save con nombre limpio | Pasó |
| TC-U25 | Handler | Unitaria (pytest) | Extracción correcta de nombre archivo | image_path path="C:/.../plant.png" | guardado es "plant.png" | Pasó |
| TC-U26 | Handler | Unitaria (pytest) | Propagación de errores de IA | Exception("AI Error") | Lanza Exception | Pasó |
| TC-U27 | AIAdapter | Unitaria (pytest) | Petición exitosa a servicio IA | Archivo de imagen válido | Retorna JSON de predicción | Pasó |
| TC-U28 | AIAdapter | Unitaria (pytest) | Servidor caído | Error 500 del servicio IA | Lanza Exception personalizada | Pasó |
| TC-U29 | AIAdapter | Unitaria (pytest) | Timeout de red | Timeout en petición IA | Lanza Exception personalizada | Pasó |
| TC-U30 | DiagnosisEngine | Unitaria (pytest) | Borde de salud (70.0) | health_score = 70.0 | Retorna False | Pasó |

**Control de Casos de Prueba - Cultivation Area Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I07 | AnalysisController | Integración (FastAPI) | Procesamiento completo de zona | Imagen multipart/form-data | Status 200 OK y JSON de análisis | Pasó |

**Control de Casos de Prueba - Cultivation Area Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A07 | US24 (Sc1) | Aceptación (BDD) | Categorización de crecimiento | Imagen pre-procesada | Clasificación de fase y salud | Pasó |
| TC-A08 | US24 (Sc2) | Aceptación (BDD) | Umbral de confianza < 75% | Confianza = 0.60 | Estado marcado como "Indeterminado" | Pasó |
| TC-A09 | US24 (Sc3) | Aceptación (BDD) | Actualización automática BD | Diagnóstico "Floración" | Repositorio save llamado con "Floración" | Pasó |

<img src="https://imgur.com/LDBR2Qd.png">

**Control de Casos de Prueba - Hardware Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U31 | Microcontroller | Unitaria (xUnit) | Creación válida de dispositivo | Model, MAC, ZoneId | Instancia creada, Status: OFFLINE | Pasó |
| TC-U32 | Microcontroller | Unitaria (xUnit) | Validación de modelo vacío | Model="" | Lanza ArgumentException | Pasó |
| TC-U33 | Microcontroller | Unitaria (xUnit) | Validación de MAC vacía | MacAddress="" | Lanza ArgumentException | Pasó |
| TC-U34 | Microcontroller | Unitaria (xUnit) | Vincular a zona | ZoneId=5 | ZoneId asignado correctamente | Pasó |
| TC-U35 | Microcontroller | Unitaria (xUnit) | Zona inválida | ZoneId=0 | Lanza ArgumentException | Pasó |
| TC-U36 | TechnicalMaintenance | Unitaria (xUnit) | Registro de mantenimiento | StaffId, DeviceId, Tipo | Instancia creada | Pasó |
| TC-U37 | TechnicalMaintenance | Unitaria (xUnit) | StaffId inválido | StaffId=0 | Lanza ArgumentException | Pasó |
| TC-U38 | MaintenanceService | Unitaria (xUnit) | Log sin dispositivo | DeviceId=1, no existe en DB | Lanza KeyNotFoundException | Pasó |
| TC-U39 | MaintenanceService | Unitaria (xUnit) | Registro técnico válido | Staff, Device, Datos | Retorna entidad creada | Pasó |
| TC-U40 | MaintenanceService | Unitaria (xUnit) | Listado de logs | DeviceId=1, Límite 10 | Llama al repositorio una vez | Pasó |

**Control de Casos de Prueba - Hardware Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I08 | MaintenanceController | Integración (xUnit) | Registro bitácora mantenimiento | Action="Reinicio", Status="OK" | 201 Created | Pasó |
| TC-I09 | MaintenanceController | Integración (xUnit) | Fallo por dispositivo inexistente | DeviceId=99 | 404 Not Found | Pasó |
| TC-I10 | MaintenanceController | Integración (xUnit) | Consulta de logs | DeviceId=1, Límite=50 | 200 OK | Pasó |

**Control de Casos de Prueba - Hardware Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A10 | US12 | Aceptación (BDD) | Mantenimiento de dispositivos | Estado="EN_MANTENIMIENTO" | Estado actualizado | Pasó |
| TC-A11 | US12 | Aceptación (BDD) | Bitácora técnica | Descrip: "Limpieza sensor" | Registro con fecha actual | Pasó |
| TC-A12 | US15 | Aceptación (BDD) | Reubicación/Desvinculación | ZoneId = Null | Acción: Desvinculación | Pasó |

<img src="https://imgur.com/0RJfMjZ.png">

**Control de Casos de Prueba - Profile Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U41 | User (Aggregate) | Unitaria (xUnit) | Construcción de usuario válido | ID=100, Nombre="Juan Perez" | Instancia creada, Activo=True | Pasó |
| TC-U42 | User (Aggregate) | Unitaria (xUnit) | Asignación de rol inválido | RoleId=0 | Lanza ArgumentException | Pasó |
| TC-U43 | User (Aggregate) | Unitaria (xUnit) | Actualización de perfil | Nombre nuevo, TaxId nuevo | Propiedades actualizadas | Pasó |
| TC-U44 | Contract (Aggregate) | Unitaria (xUnit) | Validación de fechas | Fecha fin < Fecha inicio | Lanza ArgumentException | Pasó |
| TC-U45 | Contract (Aggregate) | Unitaria (xUnit) | Validación de límites negativos | MaxZones = -1 | Lanza ArgumentException | Pasó |
| TC-U46 | Contract (Aggregate) | Unitaria (xUnit) | Actualización de límites | Nuevos límites, Suspended=true | Propiedades actualizadas | Pasó |
| TC-U47 | UserCommandSvc | Unitaria (xUnit) | Registro con rol inexistente | RoleId=99 | Lanza ArgumentException | Pasó |
| TC-U48 | UserCommandSvc | Unitaria (xUnit) | Identidad duplicada | IdentityId ya existe en BD | Lanza ArgumentException | Pasó |
| TC-U49 | UserCommandSvc | Unitaria (xUnit) | Edición de perfil inexistente | UserId=1 (no existe) | Lanza KeyNotFoundException | Pasó |
| TC-U50 | UserCommandSvc | Unitaria (xUnit) | Asignación de rol válida | UserId=1, RoleId=2 | Rol actualizado a 2 | Pasó |

**Control de Casos de Prueba - Profile Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I11 | UserProfileController | Integración (xUnit) | Obtención de perfil propio | IdentityId=100 (Token) | 200 OK con datos de perfil | Pasó |
| TC-I12 | UserProfileController | Integración (xUnit) | Patch exitoso de perfil propio | UserId=1 (Dueño) | 200 OK | Pasó |
| TC-I13 | UserProfileController | Integración (xUnit) | Acceso no autorizado a perfil ajeno | Request a UserId=2, Caller=1 | 403 Forbidden | Pasó |

**Control de Casos de Prueba - Profile Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A13 | US26 | Aceptación (BDD) | Modificación de perfil | Cambiar nombre y teléfono | Nombre reflejado correctamente | Pasó |
| TC-A14 | US11 | Aceptación (BDD) | Ajuste de límites contrato | MaxZones 10 -> 25 | Contrato permite 25 zonas | Pasó |
| TC-A15 | US11 | Aceptación (BDD) | Suspensión de contrato | Ejecutar suspensión | Bandera IsSuspended = True | Pasó |

<img src="https://imgur.com/1cVGZcR.png">

**Control de Casos de Prueba - Crop Analysis Unit Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-U51 | DiagnosisEngine | Unitaria (pytest) | Formateo correcto del reporte | Diccionario con respuesta JSON de la IA: health_score, detected_phase, etc. | Reporte formateado correctamente | Pasó |
| TC-U52 | DiagnosisEngine | Unitaria (pytest) | Detección de estado crítico | health_score = 69.9 | Retorna True | Pasó |
| TC-U53 | DiagnosisEngine | Unitaria (pytest) | Detección de estado saludable | health_score = 85.0 | Retorna False | Pasó |
| TC-U54 | Handler | Unitaria (pytest) | Ejecución exitosa y guardado | zone_id=10, path="/img/crop.jpg" | Repositorio llama a save con nombre limpio | Pasó |
| TC-U55 | Handler | Unitaria (pytest) | Extracción correcta de nombre archivo | image_path path="C:/.../plant.png" | guardado es "plant.png" | Pasó |
| TC-U56 | Handler | Unitaria (pytest) | Propagación de errores de IA | Exception("AI Error") | Lanza Exception | Pasó |
| TC-U57 | AIAdapter | Unitaria (pytest) | Petición exitosa a servicio IA | Archivo de imagen válido | Retorna JSON de predicción | Pasó |
| TC-U58 | AIAdapter | Unitaria (pytest) | Servidor caído | Error 500 del servicio IA | Lanza Exception personalizada | Pasó |
| TC-U59 | AIAdapter | Unitaria (pytest) | Timeout de red | Timeout en petición IA | Lanza Exception personalizada | Pasó |
| TC-U60 | DiagnosisEngine | Unitaria (pytest) | Borde de salud (70.0) | health_score = 70.0 | Retorna False | Pasó |

**Control de Casos de Prueba - Crop Analysis Integration Testing**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-I14 | AnalysisController | Integración (FastAPI) | Procesamiento completo de zona | Imagen multipart/form-data | Status 200 OK y JSON de análisis | Pasó |

**Control de Casos de Prueba - Crop Analysis Acceptance Testing**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
| --- | --- | --- | --- | --- | --- | --- |
| TC-A16 | US24 (Sc1) | Aceptación (BDD) | Categorización de crecimiento | Imagen pre-procesada | Clasificación de fase y salud | Pasó |
| TC-A17 | US24 (Sc2) | Aceptación (BDD) | Umbral de confianza < 75% | Confianza = 0.60 | Estado marcado como "Indeterminado" | Pasó |
| TC-A18 | US24 (Sc3) | Aceptación (BDD) | Actualización automática BD | Diagnóstico "Floración" | Repositorio save es llamado con "Floración" | Pasó |

<img src="https://imgur.com/wyE3OHG.png">

#### 6.2.2.6. Execution Evidence for Sprint Review

**Aplicación Web:**

Durante el presente sprint, se consolidó la integración del frontend con la arquitectura de microservicios desplegada en la nube de Azure, estableciendo la comunicación y el consumo de servicios a través del API Gateway. Se completó el desarrollo del módulo de gestión de dispositivos (Hardware), implementando interfaces dinámicas para el monitoreo de estado, consulta de bitácoras y la orquestación de acciones de mantenimiento, garantizando una sincronización bidireccional con el backend. 

De manera paralela, se optimizaron las funcionalidades de gestión de perfil, habilitando la persistencia de datos personales y fiscales con validación en tiempo real. Finalmente, se ejecutó una mejora integral en la experiencia de usuario (UX) y la visualización de datos dinámicos en el Dashboard y el buscador, reemplazando componentes estáticos por datos reales provenientes de la API y estandarizando la normalización de zonas horarias para la correcta localización del usuario, lo que resulta en una plataforma robusta, profesional y alineada con los requerimientos operativos.

Pantalla de Perfil:

<img src="https://imgur.com/nFwxwjl.png">

Pantalla de la lista de devices:

<img src="https://imgur.com/HP2dC6d.png">

Pantalla de LogBook:

<img src="https://imgur.com/HS9wSHt.png">

Pantalla del mantenimiento:

<img src="https://imgur.com/6NGEcys.png">

Pantalla del device detail:

<img src="https://imgur.com/BrL7ODo.png">

Video de la explicación:
[ExecutionEvidenceAppWebSP2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/IQBTTmNEZmqyRr4wUZ9MbBihAQxXDZ0ogwVLT4vqC23it44?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=oCqQpZ) 

**Aplicación Móvil:**

Durante este sprint, se completó la implementación integral de la arquitectura de vistas para la aplicación Grotix, logrando la consolidación del ecosistema visual y su total integración con el ecosistema de servicios en el backend.

Se priorizó el desarrollo y despliegue de la interfaz de usuario en su totalidad, estableciendo una comunicación eficiente mediante la conexión a múltiples endpoints. Esta integración permite ahora la gestión y visualización dinámica de la información en la mayoría de las tablas del sistema, garantizando un flujo de datos coherente y en tiempo real.

Paralelamente, se optimizó la arquitectura de consumo de servicios para asegurar una alta disponibilidad y respuesta en la carga de datos, permitiendo que la aplicación procese de manera precisa las operaciones de lectura y escritura necesarias para el funcionamiento operativo. Con estas actualizaciones, Grotix ha alcanzado una madurez funcional que facilita la interacción fluida del usuario final con la lógica de negocio del backend, sentando una base sólida para las próximas fases de escalamiento.

<img src="https://imgur.com/bJlenag.png">
<img src="https://imgur.com/UP12RcX.png">
<img src="https://imgur.com/gPvi2mV.png">
<img src="https://imgur.com/OCCSaA4.png">
<img src="https://imgur.com/iQ6eDDr.png">
<img src="https://imgur.com/64JJpFm.png">
<img src="https://imgur.com/rowta89.png">
<img src="https://imgur.com/Z9q0go7.png">
<img src="https://imgur.com/Nki3G39.png">
<img src="https://imgur.com/hGFzKkI.png">

Video explicativo:
[Sprint2_ExecutionEvidence_Mobile.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311701_upc_edu_pe/IQAVPXFkgzoFTrKKlMwhjUhKAYqMHu7je5t5Q7fLNWfeHlA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=rYAKff) 

#### 6.2.2.7. Services Documentation Evidence for Sprint Review

Durante el Sprint 2 se amplió de forma significativa la cobertura funcional del ecosistema Grotix: se incorporaron los microservicios de Telemetría (Telemetry.Api), Riego (Irrigation.Api) y Gestión de Hardware (HardwareDevice.Api), se completó la integración del servicio de análisis de cultivos (CropAnalysis.Api/FastAPI), y se enriqueció el microservicio de Perfiles con endpoints de notificaciones y un endpoint de consulta de asociación propia. Adicionalmente, se modificaron los endpoints GET /api/v1/associations/{id}/members (ahora devuelve profilePicture) y POST /api/v1/auth/register (manejo de errores 400 mejorado). La siguiente tabla resume los 56 endpoints nuevos y modificados del sprint.

| Microservicio | Método | Ruta relativa al host | Autorización | Parámetros / cuerpo | Respuesta de éxito y notas |
|---|---|---|---|---|---|
| Profiles.Api | GET | /api/v1/associations/mine | Bearer JWT | - | 200 OK. Asociación del usuario. 404 si sin asociación. |
| Profiles.Api | GET | /api/v1/associations/{id}/members | Bearer JWT | Path: associationId | 200 OK. Lista con profilePicture. [Modificado] |
| Profiles.Api | POST | /api/v1/profile/{userId}/notifications | admin JWT | JSON: title, message, type | 200 OK. Objeto notificación creado. |
| Profiles.Api | GET | /api/v1/profile/me/notifications | Bearer JWT | Query: unreadOnly, limit | 200 OK. Array de notificaciones. |
| Profiles.Api | GET | /api/v1/profile/me/notifications/unread-count | Bearer JWT | - | 200 OK. { unreadCount }. |
| Profiles.Api | PATCH | /api/v1/profile/me/notifications/{id}/read | Bearer JWT | Path: notificationId | 200 OK. { success: true }. |
| Profiles.Api | PATCH | /api/v1/profile/me/notifications/read-all | Bearer JWT | - | 200 OK. { success, updated }. |
| Telemetry.Api | GET | /api/v1/telemetry/zones/{zoneId} | TELEMETRY_VIEW / admin | Query: startTime, endTime, sensorTypes, limit | 200 OK. Lecturas de sensores por zona. |
| Telemetry.Api | GET | /api/v1/telemetry/zones/{zoneId}/alerts | TELEMETRY_VIEW / admin | Query: limit | 200 OK. Historial de alertas de umbral. |
| Telemetry.Api | GET | /api/v1/telemetry/zones/{zoneId}/thresholds | Bearer JWT | Path: zoneId | 200 OK. Umbrales activos por sensor. |
| Telemetry.Api | PATCH | /api/v1/telemetry/zones/{zoneId}/thresholds | THRESHOLD_WRITE / admin | JSON array: { sensorType, minValue, maxValue } | 200 OK. { success: true }. |
| Telemetry.Api | POST | /api/v1/telemetry/ingest | DEVICE_CONFIG / admin | JSON: deviceId, zoneId, temperature, humidityAir, humiditySoil, lightIntensity | 202 Accepted. { deviceId, zoneId, ingested }. |
| Telemetry.Api | GET | /api/v1/telemetry/actuators/{actuatorId}/logs | TELEMETRY_VIEW / admin | Query: limit | 200 OK. Historial de acciones del actuador. |
| Telemetry.Api | GET | /api/v1/telemetry/health/live | Anónimo | - | 200 OK. { status, timestamp, messageBroker }. |
| Telemetry.Api | GET | /api/v1/telemetry/health/ready | Anónimo | - | 200/503. { status, checks }. |
| Irrigation.Api | POST | /api/v1/irrigation/start/{zoneId} | MANUAL_CONTROL_EXECUTE / admin | JSON: volumeLiters?, durationMinutes? | 200 OK. { cycleId }. 409 si ciclo activo. |
| Irrigation.Api | POST | /api/v1/irrigation/stop/{zoneId} | MANUAL_CONTROL_EXECUTE / admin | JSON: reason? | 200 OK. Ciclo finalizado con status ABORTED. |
| Irrigation.Api | GET | /api/v1/irrigation/schedules | Bearer JWT | Query: zoneId? | 200 OK. Array de programas. |
| Irrigation.Api | POST | /api/v1/irrigation/schedules | MANUAL_CONTROL_EXECUTE / admin | JSON: zoneId, daysOfTheWeek, startTime, durationMinutes | 200 OK. { scheduleId }. |
| Irrigation.Api | PATCH | /api/v1/irrigation/schedules/{id} | MANUAL_CONTROL_EXECUTE / admin | JSON parcial de programa | 200 OK. { success: true }. |
| Irrigation.Api | DELETE | /api/v1/irrigation/schedules/{id} | MANUAL_CONTROL_EXECUTE / admin | Path: id | 200 OK. { success: true }. |
| Irrigation.Api | GET | /api/v1/irrigation/history | TELEMETRY_VIEW / admin | Query: zoneId?, startTime?, endTime?, limit? | 200 OK. Historial de ciclos. |
| Irrigation.Api | GET | /api/v1/irrigation/history/{zoneId} | TELEMETRY_VIEW / admin | Path: zoneId. Query: startTime?, endTime?, limit? | 200 OK. Historial de la zona. |
| Irrigation.Api | GET | /api/v1/irrigation/active | Bearer JWT | Query: zoneId? | 200 OK. Ciclos activos. |
| Irrigation.Api | GET | /api/v1/irrigation/active/{zoneId} | Bearer JWT | Path: zoneId | 200 OK. Ciclos activos de la zona. |
| Irrigation.Api | GET | /api/v1/irrigation/health/live | Anónimo | - | 200 OK. { status, timestamp }. |
| Irrigation.Api | GET | /api/v1/irrigation/health/ready | Anónimo | - | 200/503. { status, checks }. |
| Hardware.Api | GET | /api/v1/hardware/devices | DEVICE_CONFIG / admin | Query: status?, zoneId? | 200 OK. Array de dispositivos. |
| Hardware.Api | POST | /api/v1/hardware/devices | DEVICE_CONFIG / admin | JSON: model, macAddress, zoneId?, sensors[], actuators[] | 201 Created. { deviceId }. |
| Hardware.Api | GET | /api/v1/hardware/devices/{id} | DEVICE_CONFIG / admin | Path: id | 200 OK. Detalle con sensores y actuadores. |
| Hardware.Api | PATCH | /api/v1/hardware/devices/{id} | DEVICE_CONFIG / admin | JSON parcial: zoneId?, model?, macAddress? | 200 OK. { success: true }. |
| Hardware.Api | DELETE | /api/v1/hardware/devices/{id} | DEVICE_CONFIG / admin | Path: id | 200 OK. { success: true }. |
| Hardware.Api | PATCH | /api/v1/hardware/devices/{id}/status | DEVICE_CONFIG / admin | JSON: status, lastSeen? | 200 OK. Estado actualizado. |
| Hardware.Api | GET | /api/v1/hardware/devices/{id}/status | DEVICE_CONFIG / admin | Path: id | 200 OK. { deviceId, status, lastSeen, uptimeSeconds }. |
| Hardware.Api | GET | /api/v1/hardware/devices/{id}/telemetry | DEVICE_CONFIG / admin | Query: sensorTypes[]? | 200 OK. Snapshot de telemetría del dispositivo. |
| Hardware.Api | GET | /api/v1/hardware/devices/{id}/diagnostic | HARDWARE_DIAGNOSTIC / admin | Query: includeSensors, includeActuators | 200 OK. { overallStatus, checks }. |
| Hardware.Api | POST | /api/v1/hardware/devices/{id}/sensors | DEVICE_CONFIG / admin | JSON: type, unit, pin, minPhysical?, maxPhysical? | 201 Created. { sensorId, type, unit, pin, zoneId }. |
| Hardware.Api | DELETE | /api/v1/hardware/devices/{id}/sensors/{sensorId} | DEVICE_CONFIG / admin | Path: id, sensorId | 200 OK. { success: true }. |
| Hardware.Api | POST | /api/v1/hardware/devices/{id}/actuators | DEVICE_CONFIG / admin | JSON: type, pin | 201 Created. { actuatorId, type, pin, status }. |
| Hardware.Api | DELETE | /api/v1/hardware/devices/{id}/actuators/{actuatorId} | DEVICE_CONFIG / admin | Path: id, actuatorId | 200 OK. { success: true }. |
| Hardware.Api | POST | /api/v1/hardware/devices/{id}/link-to-zone/{zoneId} | DEVICE_CONFIG / admin | Path: id, zoneId | 200 OK. { success: true }. |
| Hardware.Api | DELETE | /api/v1/hardware/devices/{id}/unlink-from-zone/{zoneId} | DEVICE_CONFIG / admin | Path: id, zoneId | 200 OK. { success: true }. |
| Hardware.Api | GET | /api/v1/hardware/devices/{id}/zone | DEVICE_CONFIG / admin | Path: id | 200 OK. { zoneId, zoneName, cropName }. |
| Hardware.Api | GET | /api/v1/hardware/zones/{zoneId}/devices | DEVICE_CONFIG / admin | Path: zoneId | 200 OK. Array resumen de dispositivos de la zona. |
| Hardware.Api | GET | /api/v1/hardware/zones/{zoneId}/health | Bearer JWT | Path: zoneId | 200 OK. { zoneId, allActive, totalDevices, devices[] }. |
| Hardware.Api | POST | /api/v1/hardware/devices/{deviceId}/maintenance-logs | DEVICE_CONFIG / admin | JSON: action, statusAfter | 201 Created. Log de mantenimiento. |
| Hardware.Api | GET | /api/v1/hardware/devices/{deviceId}/maintenance-logs | DEVICE_CONFIG / admin | Query: limit | 200 OK. Historial de mantenimiento. |
| Hardware.Api | POST | /api/v1/hardware/devices/{deviceId}/technical-maintenance | DEVICE_CONFIG / admin | JSON: staffId, type, description, results? | 201 Created. Mantenimiento técnico registrado. |
| Hardware.Api | GET | /api/v1/hardware/devices/{deviceId}/technical-maintenance | DEVICE_CONFIG / admin | Query: limit | 200 OK. Historial de mantenimientos técnicos. |
| Hardware.Api | GET | /api/v1/hardware/actuators/{actuatorId}/action-queue | DEVICE_CONFIG / admin | Query: limit | 200 OK. Cola de comandos del actuador. |
| Hardware.Api | GET | /api/v1/hardware/health/live | Anónimo | - | 200 OK. { status, timestamp }. |
| Hardware.Api | GET | /api/v1/hardware/health/ready | Anónimo | - | 200/503. { status, checks }. |
| CropAnalysis.Api | POST | /api/v1/analysis/zones/{zoneId}/analyze | Bearer JWT | Form-data: image (file) | 201 Created. { analysisId, imageUrl, healthScore, phase }. |
| CropAnalysis.Api | GET | /api/v1/analysis/zones/{zoneId}/health | Bearer JWT | Path: zoneId | 200 OK. Último reporte de salud. 404 si sin reportes. |
| CropAnalysis.Api | GET | /api/v1/analysis/zones/{zoneId}/reports | Bearer JWT | Query: limit, offset | 200 OK. Historial de reportes paginado. |
| CropAnalysis.Api | GET | /api/v1/analysis/reports/{reportId} | Bearer JWT | Path: reportId | 200 OK. Detalle completo con analysisDetails. |

**Evidencias de Validación Funcional (Sprint 2 Endpoints)**

A continuación se detallan los parámetros, cuerpos de petición y respuestas esperadas de cada endpoint nuevo o modificado, validados mediante Swagger UI y clientes HTTP.

**GET /api/v1/associations/mine**

Permite a cualquier usuario autenticado consultar los datos de la asociación a la que pertenece sin necesidad de privilegios de administrador. El microservicio Profiles.Api resuelve la asociación vinculada al claim de identidad contenido en el token JWT.

**A. Cabeceras (Headers)** 

|Campo (Field)|Tipo (Type)|Descripción|
|---|---|---|
|Authorization|String|Token de autenticación. Formato: Bearer {jwt_token}|

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros adicionales. 

**C. Ejemplo de Petición (Request-Example)** 

```http
GET /api/v1/associations/mine HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9... 
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Retorna el objeto asociación del usuario autenticado.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| id | Integer | Identificador único de la asociación. |
| name | String | Nombre oficial de la asociación. |
| contactEmail | String | Correo de contacto. |

**Ejemplo de Respuesta Exitosa (Success-Example)** 

```json
{ 
    "id": 3, 
    "name": "Cooperativa Agraria Los Andes", "contactEmail": "contacto@losandes.pe" 
}
```

**Error: Código 404 Not Found**
**Ejemplo de Respuesta de Error (Error-Response)** 

```json
{ 
    "status": 404, 
    "message": "NOT_FOUND: El usuario no pertenece a ninguna asociación registrada." 
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/associations/{associationId}/members [Modificado Sprint 2]**

Lista todos los miembros de una asociación. En Sprint 2 se incorporó el campo profilePicture en cada objeto miembro, permitiendo al frontend mostrar avatares en listados de equipo y paneles de gestión.

**A. Cabeceras (Headers)** 

|Campo (Field)|Tipo (Type)|Descripción|
|--|---|--|
|Authorization|String|Token de autenticación. Formato: Bearer {jwt_token}|

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere cuerpo. 

**C. Ejemplo de Petición (Request-Example)** 

```http
GET /api/v1/associations/3/members HTTP/1.1 
Host: api.grotix.pe 
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Retorna la lista de miembros con foto de perfil incluida.

| Campo (Field) | Tipo (Type) | Descripción |
|---|---|---|
| userId | Integer | Identificador del usuario miembro. |
| name | String | Nombre completo. |
| email | String | Correo electrónico. |
| roleId | Integer | ID del rol asignado. |
| roleName | String | Nombre del rol (ej. user_basic). |
| profilePicture | String? | URL de la foto de perfil. null si no tiene. [Nuevo] |
| assignedAt | DateTime | Fecha de incorporación. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{ 
    "userId": 23, 
    "name": "Carlos Mamani Quispe", 
    "email": "c.mamani@grotix.pe", 
    "roleId": 4, 
    "roleName": "user_basic", 
    "profilePicture": "https://storage.grotix.pe/avatars/cmamani.jpg", 
    "assignedAt": "2026-05-01T08:00:00Z" 
}
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/profile/{userId}/notifications**

Permite a un administrador enviar una notificación directa a un usuario específico. La notificación queda almacenada y el usuario puede consultarla mediante GET /profile/me/notifications. El campo type es libre (ej. alert, info, warning).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Token de autenticación admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| userId | Integer (path) | Destinatario de la notificación. |
| title | String | Título corto de la notificación. |
| message | String | Cuerpo del mensaje. |
| type | String? | Tipo libre: alert, info, warning. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "title": "Alerta de Humedad",
    "message": "La zona 5 ha superado el umbral máximo de humedad de suelo.",
    "type": "alert"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Notificación creada y almacenada.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer | Identificador único de la notificación. |
| userId | Integer | Usuario destinatario. |
| title | String | Título de la notificación. |
| message | String | Contenido del mensaje. |
| type | String? | Tipo de notificación. |
| isRead | Boolean | Estado de lectura. Siempre false al crear. |
| createdAt | DateTime | Fecha y hora de creación. |
| readAt | DateTime? | Fecha de lectura. null hasta que se marque como leída. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "id": 101,
    "userId": 23,
    "title": "Alerta de Humedad",
    "message": "La zona 5 ha superado el umbral máximo...",
    "type": "alert",
    "isRead": false,
    "createdAt": "2026-06-07T14:00:00Z",
    "readAt": null
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "FORBIDDEN: Solo administradores pueden enviar notificaciones."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/profile/me/notifications**

Obtiene las notificaciones del usuario autenticado. Soporta filtro por estado de lectura y paginación mediante limit. Las notificaciones se retornan ordenadas de más reciente a más antigua.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| unreadOnly | Boolean (query) | Si true, devuelve solo notificaciones no leídas. Default: false. |
| limit | Integer (query) | Número máximo de notificaciones a retornar. Default: 50. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/profile/me/notifications?unreadOnly=true&limit=20 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de notificaciones del usuario. Vacío [] si no hay.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| id                | Integer         | Identificador de la notificación. |
| title             | String          | Título.                           |
| message           | String          | Cuerpo del mensaje.               |
| type              | String?         | Tipo de notificación.             |
| isRead            | Boolean         | Estado de lectura.                |
| createdAt         | DateTime        | Fecha de creación.                |
| readAt            | DateTime?       | Fecha de lectura o null.          |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
    {
        "id": 101,
        "title": "Alerta de Humedad",
        "message": "La zona 5 ha superado el umbral máximo...",
        "type": "alert",
        "isRead": false,
        "createdAt": "2026-06-07T14:00:00Z",
        "readAt": null
    }
]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/profile/me/notifications/unread-count**

Retorna el conteo de notificaciones no leídas del usuario autenticado. Endpoint ligero, ideal para actualizar el badge de notificaciones en la barra de navegación sin necesidad de cargar el listado completo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros adicionales.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/profile/me/notifications/unread-count HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Conteo de notificaciones no leídas.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| unreadCount       | Integer         | Número de notificaciones no leídas. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "unreadCount": 3
}
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**PATCH /api/v1/profile/me/notifications/{notificationId}/read**

Marca una notificación específica como leída, actualizando los campos isRead=true y readAt con la fecha y hora actual. Solo el propietario de la notificación puede marcarla como leída.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| notificationId | Integer (path) | Identificador de la notificación a marcar. |

**C. Ejemplo de Petición (Request-Example)**

```http
PATCH /api/v1/profile/me/notifications/101/read HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Notificación marcada como leída.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| success           | Boolean         | true si la operación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Notificación no encontrada."
}
```

**D. Evidencia en Swagger**

<img src="">

**PATCH /api/v1/profile/me/notifications/read-all**

Marca todas las notificaciones no leídas del usuario autenticado como leídas en una sola operación. Devuelve el número de notificaciones actualizadas.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere cuerpo de petición.

**C. Ejemplo de Petición (Request-Example)**

```http
PATCH /api/v1/profile/me/notifications/read-all HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Todas las notificaciones pendientes marcadas como leídas.

| Campo (Field) | Tipo (Type) | Descripción                          |
|-------------------|-----------------|------------------------------------------|
| success           | Boolean         | true si la operación fue exitosa.        |
| updated           | Integer         | Cantidad de notificaciones actualizadas. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true,
    "updated": 5
}
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```


**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/telemetry/zones/{zoneId}**

Obtiene las lecturas de telemetría de todos los sensores de una zona de cultivo dentro de una ventana temporal. Soporta filtrado por tipo de sensor y paginación mediante limit. Los datos provienen de la base de datos TimescaleDB y están optimizados para consultas de series temporales.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso TELEMETRY_VIEW o rol admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| zoneId | Integer (path) | Identificador de la zona. |
| startTime | DateTime? (query) | Inicio de la ventana temporal (ISO 8601 UTC). |
| endTime | DateTime? (query) | Fin de la ventana temporal. Por defecto: ahora. |
| sensorTypes | String[]? (query) | Filtro por tipo de sensor. Ej: SOIL_MOISTURE, AIR_TEMPERATURE. |
| limit | Integer (query) | Máximo de lecturas a retornar. Rango: 1-10000. Default: 1000. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/zones/5?sensorTypes=SOIL_MOISTURE&limit=100 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Objeto de telemetría con lecturas agrupadas por sensor.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| zoneId | Integer | Zona consultada. |
| period.start | DateTime | Inicio del periodo devuelto. |
| period.end | DateTime | Fin del periodo devuelto. |
| sensors | Array | Lista de sensores con sus lecturas. |
| sensors[].sensorId | Integer | ID del sensor. |
| sensors[].type | String | Tipo: SOIL_MOISTURE, AIR_TEMPERATURE, AIR_HUMIDITY, LIGHT_INTENSITY. |
| sensors[].unit | String | Unidad de medida (%, °C, lux). |
| sensors[].readings | Array | Lecturas: [{ value, timestamp }]. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "zoneId": 5,
    "period": { "start": "2026-06-06T00:00:00Z", "end": "2026-06-07T00:00:00Z" },
    "sensors": [{
            "sensorId": 1, "type": "SOIL_MOISTURE", "unit": "%",
            "readings": [{ "value": 34.5, "timestamp": "2026-06-07T08:00:00Z" }]
        }]
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: La zona no tiene sensores registrados."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/telemetry/zones/{zoneId}/alerts**

Lista las alertas de umbral disparadas para una zona de cultivo. Una alerta se genera automáticamente cuando una lectura de sensor supera (breach direction ABOVE_MAX) o cae por debajo (BELOW_MIN) de los umbrales configurados. Soporta paginación.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso TELEMETRY_VIEW o rol admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                 |
|-------------------|-----------------|---------------------------------|
| zoneId            | Integer (path)  | Identificador de la zona.       |
| limit             | Integer (query) | Máximo de alertas. Default: 50. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/zones/5/alerts?limit=20 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de alertas de umbral para la zona.

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| id                | Integer         | ID de la alerta.                        |
| zoneId            | Integer         | Zona afectada.                          |
| sensorId          | Integer         | Sensor que disparó la alerta.           |
| sensorType        | String          | Tipo de sensor.                         |
| value             | Float           | Valor registrado que excedió el umbral. |
| minThreshold      | Float           | Umbral mínimo configurado.              |
| maxThreshold      | Float           | Umbral máximo configurado.              |
| breachDirection   | String          | ABOVE_MAX o BELOW_MIN.                  |
| triggeredAt       | DateTime        | Fecha y hora de la alerta.              |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 15, "zoneId": 5, "sensorId": 1, "sensorType": "SOIL_MOISTURE",
        "value": 15.2, "minThreshold": 20.0, "maxThreshold": 80.0,
        "breachDirection": "BELOW_MIN",
        "triggeredAt": "2026-06-07T06:30:00Z"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/telemetry/zones/{zoneId}/thresholds**

Obtiene los umbrales de alerta activos para cada tipo de sensor de una zona. Los umbrales pueden provenir de los defaults del cultivo asignado (source=crop) o de configuraciones personalizadas (source=custom) creadas mediante PATCH.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere cuerpo de petición.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/zones/5/thresholds HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de umbrales por tipo de sensor.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| sensorType | String | Tipo de sensor: SOIL_MOISTURE, AIR_TEMPERATURE, etc. |
| minValue | Float? | Umbral mínimo. null si no definido. |
| maxValue | Float? | Umbral máximo. null si no definido. |
| source | String | crop = default del cultivo; custom = personalizado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
    { "sensorType": "SOIL_MOISTURE", "minValue": 20.0, "maxValue": 80.0, "source": "custom" },
    { "sensorType": "AIR_TEMPERATURE", "minValue": 15.0, "maxValue": 35.0, "source": "crop" }
]
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: La zona no tiene umbrales configurados."
}
```

**D. Evidencia en Swagger**

<img src="">

**PATCH /api/v1/telemetry/zones/{zoneId}/thresholds**

Actualiza o crea umbrales personalizados para los sensores de una zona de cultivo. El cuerpo debe ser un array JSON (no un objeto). Enviar null en minValue o maxValue para eliminar ese límite individual. Requiere permiso THRESHOLD_WRITE.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso THRESHOLD_WRITE o rol admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| [] (array) | Array | El body ES el array de umbrales a actualizar. |
| [].sensorType | String | Tipo de sensor a configurar. |
| [].minValue | Float? | Umbral mínimo. null para quitar el límite inferior. |
| [].maxValue | Float? | Umbral máximo. null para quitar el límite superior. |

**C. Ejemplo de Petición (Request-Example)**

```json
[
    { "sensorType": "SOIL_MOISTURE", "minValue": 18.0, "maxValue": 75.0 },
    { "sensorType": "AIR_TEMPERATURE", "minValue": null, "maxValue": null }
]
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Umbrales actualizados exitosamente.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| success           | Boolean         | true si la operación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "FORBIDDEN: Permiso THRESHOLD_WRITE requerido."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**POST /api/v1/telemetry/ingest**

Endpoint de ingesta de telemetría. Recibe una lectura de sensor desde un microcontrolador (ESP32) o desde el Edge Service. La lectura se persiste en TimescaleDB y dispara evaluación de umbrales. Requiere permiso DEVICE_CONFIG.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o rol admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| sensorId | Integer | Identificador del sensor que generó la lectura. |
| value | Float | Valor medido. |
| deviceId | Integer? | ID del microcontrolador. Default: 0. |
| timestamp | DateTime? | Fecha y hora de la medición. Default: UTC ahora. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "sensorId": 1,
    "value": 34.5,
    "deviceId": 3,
    "timestamp": "2026-06-07T08:00:00Z"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 202 Accepted

Lectura aceptada para procesamiento asíncrono.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| sensorId          | Integer         | Sensor que recibió la lectura.    |
| ingested          | Boolean         | true si la lectura fue procesada. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "sensorId": 1,
    "ingested": true
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "FORBIDDEN: Permiso DEVICE_CONFIG requerido."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**POST /api/v1/irrigation/start/{zoneId}**

Inicia un ciclo de riego manual para una zona de cultivo. Los parámetros volumeLiters y durationMinutes son opcionales; el backend calcula valores predeterminados basados en la zona. Si ya existe un ciclo IN_PROGRESS en la zona, la petición falla con 409.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso MANUAL_CONTROL_EXECUTE o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                        |
|-------------------|-----------------|----------------------------------------|
| zoneId            | Integer (path)  | Zona de cultivo a regar.               |
| volumeLiters      | Float?          | Volumen deseado en litros. Opcional.   |
| durationMinutes   | Integer?        | Duración deseada en minutos. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "volumeLiters": 10.5,
    "durationMinutes": 30
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Ciclo de riego iniciado exitosamente.

| Campo (Field) | Tipo (Type) | Descripción                          |
|-------------------|-----------------|------------------------------------------|
| cycleId           | Integer         | Identificador del ciclo de riego creado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "cycleId": 42
}
```

**Error: Código 409 Conflict**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 409,
    "message": "CONFLICT: Ya existe un ciclo de riego en progreso para esta zona."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**POST /api/v1/irrigation/stop/{zoneId}**

Detiene el ciclo de riego activo de una zona de cultivo. El ciclo pasa a estado ABORTED con la razón indicada en el campo reason. Devuelve el objeto ciclo completo con la información de inicio y fin del riego.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso MANUAL_CONTROL_EXECUTE o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| zoneId            | Integer (path)  | Zona de cultivo a detener.              |
| reason            | String?         | Razón de la detención manual. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "reason": "Lluvia detectada manualmente"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Ciclo de riego detenido. Devuelve el ciclo finalizado.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| id                | Integer         | ID del ciclo.                     |
| zoneId            | Integer         | Zona regada.                      |
| startTime         | DateTime        | Inicio del ciclo.                 |
| endTime           | DateTime        | Fin del ciclo (momento del stop). |
| volumeLiters      | Float           | Volumen estimado utilizado.       |
| status            | String          | ABORTED (detenido manualmente).   |
| abortReason       | String?         | Razón del abort.                  |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "id": 42,
    "zoneId": 5,
    "startTime": "2026-06-07T08:00:00Z",
    "endTime": "2026-06-07T08:22:00Z",
    "volumeLiters": 7.7,
    "status": "ABORTED",
    "abortReason": "Lluvia detectada manualmente"
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: No hay ciclo activo en la zona."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/irrigation/schedules**

Lista los programas de riego automático configurados. Puede filtrarse por zona mediante el parámetro de consulta zoneId. Retorna tanto programas activos como inactivos.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type)  | Descripción              |
|-------------------|------------------|------------------------------|
| zoneId            | Integer? (query) | Filtrar por zona específica. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/schedules?zoneId=5 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de programas de riego.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer | ID del programa. |
| zoneId | Integer | Zona asignada. |
| daysOfTheWeek | String | Días en formato CSV: MON,WED,FRI. |
| startTime | String | Hora de inicio en formato HH:mm (ej. 06:30). |
| durationMinutes | Integer | Duración en minutos. |
| isActive | Boolean | true si el programa está habilitado. |
| createdAt | DateTime | Fecha de creación. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 1, "zoneId": 5, "daysOfTheWeek": "MON,WED,FRI",
        "startTime": "06:30", "durationMinutes": 45,
        "isActive": true, "createdAt": "2026-05-15T00:00:00Z"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/irrigation/schedules**

Crea un nuevo programa de riego automático para una zona. El programa se ejecuta automáticamente en los días y hora especificados. Los días se especifican como string CSV en formato abreviado inglés (MON, TUE, WED, THU, FRI, SAT, SUN).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso MANUAL_CONTROL_EXECUTE o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                  |
|-------------------|-----------------|----------------------------------|
| zoneId            | Integer         | Zona a programar.                |
| daysOfTheWeek     | String          | Días en CSV. Ej: MON,WED,FRI.    |
| startTime         | String          | Hora de inicio HH:mm. Ej: 06:30. |
| durationMinutes   | Integer         | Duración del riego en minutos.   |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "zoneId": 5,
    "daysOfTheWeek": "MON,WED,FRI",
    "startTime": "06:30",
    "durationMinutes": 45
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Programa de riego creado.

| Campo (Field) | Tipo (Type) | Descripción         |
|-------------------|-----------------|-------------------------|
| scheduleId        | Integer         | ID del programa creado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "scheduleId": 1
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 400,
    "message": "BAD_REQUEST: El formato de startTime debe ser HH:mm."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/irrigation/history**

Obtiene el historial de ciclos de riego completados y abortados. Soporta filtrado por zona, rango temporal y paginación. Útil para reportes de consumo hídrico y auditoría de operaciones de riego.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso TELEMETRY_VIEW o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type)   | Descripción              |
|-------------------|-------------------|------------------------------|
| zoneId            | Integer? (query)  | Filtrar por zona.            |
| startTime         | DateTime? (query) | Inicio del rango temporal.   |
| endTime           | DateTime? (query) | Fin del rango temporal.      |
| limit             | Integer? (query)  | Máximo de ciclos a retornar. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/history?zoneId=5&limit=10 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de ciclos de riego históricos.

| Campo (Field) | Tipo (Type) | Descripción           |
|-------------------|-----------------|---------------------------|
| id                | Integer         | ID del ciclo.             |
| zoneId            | Integer         | Zona regada.              |
| startTime         | DateTime        | Inicio.                   |
| endTime           | DateTime        | Fin.                      |
| volumeLiters      | Float           | Volumen utilizado.        |
| status            | String          | COMPLETED o ABORTED.      |
| abortReason       | String?         | Razón de abort si aplica. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 42, "zoneId": 5,
        "startTime": "2026-06-07T06:30:00Z",
        "endTime": "2026-06-07T07:15:00Z",
        "volumeLiters": 33.75, "status": "COMPLETED", "abortReason": null
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/hardware/devices**

Lista todos los microcontroladores (ESP32) registrados en el sistema. Permite filtrar por estado de conexión (status) y por zona asignada (zoneId). Requiere permiso DEVICE_CONFIG o rol admin.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| status | String? (query) | Filtrar por estado: ONLINE, OFFLINE, MAINTENANCE, ERROR. |
| zoneId | Integer? (query) | Filtrar por zona asignada. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices?status=ONLINE&zoneId=5 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de microcontroladores.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer | ID del dispositivo. |
| zoneId | Integer? | Zona asignada. null si no tiene zona. |
| model | String | Modelo del hardware (ej. ESP32-WROOM). |
| macAddress | String | Dirección MAC única del dispositivo. |
| status | String | Estado actual: ONLINE, OFFLINE, MAINTENANCE, ERROR. |
| lastSeen | DateTime? | Último timestamp de actividad. |
| createdAt | DateTime | Fecha de registro. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 3, "zoneId": 5, "model": "ESP32-WROOM",
        "macAddress": "AA:BB:CC:DD:EE:FF", "status": "ONLINE",
        "lastSeen": "2026-06-07T08:30:00Z",
        "createdAt": "2026-04-15T00:00:00Z"
    }]
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "FORBIDDEN: Permiso DEVICE_CONFIG requerido."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/hardware/devices**

Registra un nuevo microcontrolador en el sistema. Permite configurar sensores y actuadores en el momento del registro. El campo zoneId es opcional y puede asignarse después mediante el endpoint link-to-zone.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| model | String | Modelo del microcontrolador. Requerido. |
| macAddress | String | Dirección MAC única. Requerido. |
| zoneId | Integer? | Zona a asignar. Opcional. |
| sensors | Array? | Lista de sensores a agregar: [{ type, unit, pin, minPhysical, maxPhysical }]. |
| actuators | Array? | Lista de actuadores: [{ type, pin }]. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "model": "ESP32-WROOM",
    "macAddress": "AA:BB:CC:DD:EE:01",
    "zoneId": 5,
    "sensors": [{ "type": "SOIL_MOISTURE", "unit": "%", "pin": 34, "minPhysical": 0, "maxPhysical": 100 }],
    "actuators": [{ "type": "IRRIGATION_VALVE", "pin": 12 }]
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 201 Created

Dispositivo registrado exitosamente.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| deviceId          | Integer         | ID del microcontrolador registrado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 3
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 400,
    "message": "BAD_REQUEST: La dirección MAC ya está registrada."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**PATCH /api/v1/hardware/devices/{id}/status**

Actualiza el estado de conexión de un microcontrolador. Los valores válidos son: ONLINE, OFFLINE, MAINTENANCE, ERROR. El campo lastSeen puede enviarse para registrar el último timestamp de actividad del dispositivo. Requiere permiso DEVICE_CONFIG.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer (path) | ID del microcontrolador. |
| status | String | Nuevo estado: ONLINE, OFFLINE, MAINTENANCE o ERROR. |
| lastSeen | DateTime? | Timestamp de la última actividad. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "status": "MAINTENANCE",
    "lastSeen": "2026-06-07T09:00:00Z"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Estado del dispositivo actualizado.

| Campo (Field) | Tipo (Type) | Descripción                |
|-------------------|-----------------|--------------------------------|
| deviceId          | Integer         | ID del dispositivo.            |
| status            | String          | Nuevo estado registrado.       |
| lastSeen          | DateTime?       | Último timestamp actualizado.  |
| uptimeSeconds     | Integer?        | Segundos en línea (si aplica). |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 3,
    "status": "MAINTENANCE",
    "lastSeen": "2026-06-07T09:00:00Z",
    "uptimeSeconds": null
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 400,
    "message": "BAD_REQUEST: Valor de status no válido. Use: ONLINE, OFFLINE, MAINTENANCE, ERROR."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/hardware/zones/{zoneId}/health**

Verifica el estado de salud de todos los microcontroladores asignados a una zona. Devuelve allActive=true únicamente si hay al menos un dispositivo y todos tienen estado ONLINE. Permite detectar sensores caídos de forma rápida.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere cuerpo de petición.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/zones/5/health HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Estado de salud consolidado de todos los dispositivos de la zona.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| zoneId | Integer | Zona consultada. |
| allActive | Boolean | true si todos los dispositivos están ONLINE. |
| totalDevices | Integer | Total de dispositivos en la zona. |
| devices | Array | Detalle por dispositivo. |
| devices[].id | Integer | ID del microcontrolador. |
| devices[].model | String | Modelo del dispositivo. |
| devices[].status | String | Estado: ONLINE, OFFLINE, MAINTENANCE, ERROR. |
| devices[].lastSeen | DateTime | Último timestamp de actividad. |
| devices[].isActive | Boolean | true si status es ONLINE. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "zoneId": 5,
    "allActive": false,
    "totalDevices": 2,
    "devices": [
        { "id": 3, "model": "ESP32-WROOM", "status": "ONLINE", "lastSeen": "2026-06-07T08:30:00Z", "isActive": true },
        { "id": 4, "model": "ESP32-S3", "status": "OFFLINE","lastSeen": "2026-06-06T18:00:00Z", "isActive": false }
    ]
}
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**PATCH /api/v1/irrigation/schedules/{id}**

Actualización parcial de un programa de riego existente. Solo se actualizan los campos enviados.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso MANUAL_CONTROL_EXECUTE o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| id                | Integer (path)  | ID del programa a actualizar.     |
| daysOfTheWeek     | String?         | Nuevos días en CSV. Ej: MON,FRI.  |
| startTime         | String?         | Nueva hora HH:mm.                 |
| durationMinutes   | Integer?        | Nueva duración en minutos.        |
| isActive          | Boolean?        | Activar o desactivar el programa. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "daysOfTheWeek": "MON,FRI",
    "isActive": false
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Programa actualizado.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| success           | Boolean         | true si la operación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Programa no encontrado."
}
```

**D. Evidencia en Swagger**

**DELETE /api/v1/irrigation/schedules/{id}**

Elimina un programa de riego automático. La eliminación es permanente.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso MANUAL_CONTROL_EXECUTE o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción             |
|-------------------|-----------------|-----------------------------|
| id                | Integer (path)  | ID del programa a eliminar. |

**C. Ejemplo de Petición (Request-Example)**

```http
DELETE /api/v1/irrigation/schedules/1 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Programa eliminado.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| success           | Boolean         | true si la eliminación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Programa no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/irrigation/history/{zoneId}**

Variante del historial de riego con zoneId directamente en el path. Equivalente a GET /irrigation/history?zoneId={zoneId}.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso TELEMETRY_VIEW o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type)   | Descripción                  |
|-------------------|-------------------|----------------------------------|
| zoneId            | Integer (path)    | Zona cuyo historial se consulta. |
| startTime         | DateTime? (query) | Inicio del rango temporal.       |
| endTime           | DateTime? (query) | Fin del rango temporal.          |
| limit             | Integer? (query)  | Máximo de ciclos.                |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/history/5?limit=10 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Historial de ciclos de la zona.

| Campo (Field) | Tipo (Type) | Descripción           |
|-------------------|-----------------|---------------------------|
| id                | Integer         | ID del ciclo.             |
| zoneId            | Integer         | Zona regada.              |
| startTime         | DateTime        | Inicio del ciclo.         |
| endTime           | DateTime        | Fin del ciclo.            |
| volumeLiters      | Float           | Volumen utilizado.        |
| status            | String          | COMPLETED o ABORTED.      |
| abortReason       | String?         | Razón de abort si aplica. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 42, "zoneId": 5, "status": "COMPLETED", "volumeLiters": 33.75
        ...
        "}]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/irrigation/active**

Lista todos los ciclos de riego actualmente en progreso. Puede filtrarse por zona con el query param zoneId.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type)  | Descripción   |
|-------------------|------------------|-------------------|
| zoneId            | Integer? (query) | Filtrar por zona. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/active HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de ciclos activos. Vacío [] si no hay ninguno en progreso.

| Campo (Field) | Tipo (Type) | Descripción      |
|-------------------|-----------------|----------------------|
| id                | Integer         | ID del ciclo activo. |
| zoneId            | Integer         | Zona en riego.       |
| startTime         | DateTime        | Inicio del ciclo.    |
| status            | String          | IN_PROGRESS.         |
| volumeLiters      | Float?          | Volumen estimado.    |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 43, "zoneId": 5, "startTime": "2026-06-08T06:30:00Z", "status": "IN_PROGRESS"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/irrigation/active/{zoneId}**

Lista los ciclos de riego activos de una zona específica con el zoneId en el path.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Token de autenticación. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción   |
|-------------------|-----------------|-------------------|
| zoneId            | Integer (path)  | Zona a consultar. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/active/5 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Ciclos activos de la zona. Vacío [] si no hay riego en curso.

| Campo (Field) | Tipo (Type) | Descripción |
|-------------------|-----------------|-----------------|
| id                | Integer         | ID del ciclo.   |
| zoneId            | Integer         | Zona en riego.  |
| startTime         | DateTime        | Inicio.         |
| status            | String          | IN_PROGRESS.    |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "id": 43, "zoneId": 5, "startTime": "2026-06-08T06:30:00Z", "status": "IN_PROGRESS"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/irrigation/health/live**

Probe de liveness del microservicio Irrigation.Api. No requiere autenticación. Confirma que el proceso HTTP está activo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| —                 | —               | No requiere cabeceras de autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/health/live HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio activo.

| Campo (Field) | Tipo (Type) | Descripción         |
|-------------------|-----------------|-------------------------|
| status            | String          | OK.                     |
| timestamp         | DateTime        | Fecha y hora del check. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "OK",
    "timestamp": "2026-06-08T00:00:00Z"
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy"
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/irrigation/health/ready**

Probe de readiness del microservicio Irrigation.Api. Verifica la conectividad con MySQL antes de recibir tráfico.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| —                 | —               | No requiere cabeceras de autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/irrigation/health/ready HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio listo para recibir tráfico.

| Campo (Field) | Tipo (Type) | Descripción              |
|-------------------|-----------------|------------------------------|
| status            | String          | Healthy.                     |
| checks            | Object          | { coreDatabase: "Healthy" }. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "Healthy",
    "checks": { "coreDatabase": "Healthy" }
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy",
    "checks": { "coreDatabase": "Unhealthy" }
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/devices/{id}**

Obtiene el detalle completo de un microcontrolador incluyendo sus sensores y actuadores registrados.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción     |
|-------------------|-----------------|---------------------|
| id                | Integer (path)  | ID del dispositivo. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Detalle del dispositivo con sensores y actuadores.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| deviceId | Integer | ID del dispositivo. |
| zoneId | Integer? | Zona asignada. |
| model | String | Modelo del hardware. |
| macAddress | String | Dirección MAC. |
| status | String | ONLINE, OFFLINE, MAINTENANCE, ERROR. |
| lastSeen | DateTime? | Último timestamp. |
| sensors | Array | [{ sensorId, type, unit, pin, status, lastSeen }]. |
| actuators | Array | [{ actuatorId, type, pin, status, lastSeen }]. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 1, "zoneId": 1, "model": "ESP32-WROOM",
    "macAddress": "AA:BB:CC:DD:EE:FF", "status": "ONLINE",
    "sensors": [{ "sensorId": 2, "type": "AIR_TEMPERATURE", "unit": "°C", "pin": 4, "status": "NORMAL" }],
    "actuators": [{ "actuatorId": 1, "type": "IRRIGATION_VALVE", "pin": 12, "status": "CLOSED" }]
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**PATCH /api/v1/hardware/devices/{id}**

Actualización parcial de los datos de un microcontrolador. Permite cambiar zoneId, model o macAddress.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción      |
|-------------------|-----------------|----------------------|
| id                | Integer (path)  | ID del dispositivo.  |
| zoneId            | Integer?        | Nueva zona asignada. |
| model             | String?         | Nuevo modelo.        |
| macAddress        | String?         | Nueva dirección MAC. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "zoneId": 2,
    "model": "ESP32-S3"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Dispositivo actualizado.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| success           | Boolean         | true si la operación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**DELETE /api/v1/hardware/devices/{id}**

Elimina un microcontrolador del sistema junto con sus sensores y actuadores asociados.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                |
|-------------------|-----------------|--------------------------------|
| id                | Integer (path)  | ID del dispositivo a eliminar. |

**C. Ejemplo de Petición (Request-Example)**

```http
DELETE /api/v1/hardware/devices/3 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Dispositivo eliminado.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| success           | Boolean         | true si la eliminación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/hardware/devices/{id}/sensors**

Agrega un nuevo sensor a un microcontrolador existente. El tipo debe ser uno de los valores reconocidos por el sistema.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer (path) | ID del dispositivo. |
| type | String | Tipo de sensor: AIR_TEMPERATURE, AIR_HUMIDITY, SOIL_MOISTURE, LIGHT_INTENSITY. |
| unit | String | Unidad de medida: °C, %, lux. |
| pin | Integer | Pin GPIO del ESP32. |
| minPhysical | Float? | Valor físico mínimo del sensor. Opcional. |
| maxPhysical | Float? | Valor físico máximo del sensor. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "type": "AIR_TEMPERATURE",
    "unit": "°C",
    "pin": 4,
    "minPhysical": 0,
    "maxPhysical": 100
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 201 Created

Sensor agregado al dispositivo.

| Campo (Field) | Tipo (Type) | Descripción               |
|-------------------|-----------------|-------------------------------|
| sensorId          | Integer         | ID del sensor creado.         |
| type              | String          | Tipo de sensor.               |
| unit              | String          | Unidad de medida.             |
| pin               | Integer         | Pin GPIO.                     |
| zoneId            | Integer?        | Zona asociada al dispositivo. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "sensorId": 2,
    "type": "AIR_TEMPERATURE",
    "unit": "°C",
    "pin": 4,
    "zoneId": 1
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 400,
    "message": "BAD_REQUEST: Tipo de sensor no válido."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**DELETE /api/v1/hardware/devices/{id}/sensors/{sensorId}**

Elimina un sensor de un dispositivo. Las lecturas históricas asociadas se conservan en TimescaleDB.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción           |
|-------------------|-----------------|---------------------------|
| id                | Integer (path)  | ID del dispositivo.       |
| sensorId          | Integer (path)  | ID del sensor a eliminar. |

**C. Ejemplo de Petición (Request-Example)**

```http
DELETE /api/v1/hardware/devices/1/sensors/2 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Sensor eliminado.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| success           | Boolean         | true si la eliminación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Sensor no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/hardware/devices/{id}/actuators**

Agrega un actuador (ej. válvula de riego) a un microcontrolador existente.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| id                | Integer (path)  | ID del dispositivo.                     |
| type              | String          | Tipo de actuador. Ej: IRRIGATION_VALVE. |
| pin               | Integer         | Pin GPIO del ESP32.                     |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "type": "IRRIGATION_VALVE",
    "pin": 12
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 201 Created

Actuador agregado.

| Campo (Field) | Tipo (Type) | Descripción         |
|-------------------|-----------------|-------------------------|
| actuatorId        | Integer         | ID del actuador creado. |
| type              | String          | Tipo de actuador.       |
| pin               | Integer         | Pin GPIO.               |
| status            | String          | Estado inicial: CLOSED. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "actuatorId": 2,
    "type": "IRRIGATION_VALVE",
    "pin": 12,
    "status": "CLOSED"
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 400,
    "message": "BAD_REQUEST: Tipo de actuador no válido."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**DELETE /api/v1/hardware/devices/{id}/actuators/{actuatorId}**

Elimina un actuador de un dispositivo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción             |
|-------------------|-----------------|-----------------------------|
| id                | Integer (path)  | ID del dispositivo.         |
| actuatorId        | Integer (path)  | ID del actuador a eliminar. |

**C. Ejemplo de Petición (Request-Example)**

```http
DELETE /api/v1/hardware/devices/1/actuators/2 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Actuador eliminado.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| success           | Boolean         | true si la eliminación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Actuador no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/hardware/devices/{id}/link-to-zone/{zoneId}**

Vincula un microcontrolador a una zona de cultivo. No requiere cuerpo. El dispositivo pasa a estar asociado a la zona especificada.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción           |
|-------------------|-----------------|---------------------------|
| id                | Integer (path)  | ID del dispositivo.       |
| zoneId            | Integer (path)  | ID de la zona a vincular. |

**C. Ejemplo de Petición (Request-Example)**

```http
POST /api/v1/hardware/devices/1/link-to-zone/5 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Dispositivo vinculado a la zona.

| Campo (Field) | Tipo (Type) | Descripción                     |
|-------------------|-----------------|-------------------------------------|
| success           | Boolean         | true si la vinculación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo o zona no encontrados."
}
```

**D. Evidencia en Swagger**

<img src="">

**DELETE /api/v1/hardware/devices/{id}/unlink-from-zone/{zoneId}**

Desvincula un microcontrolador de su zona de cultivo actual.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción              |
|-------------------|-----------------|------------------------------|
| id                | Integer (path)  | ID del dispositivo.          |
| zoneId            | Integer (path)  | ID de la zona a desvincular. |

**C. Ejemplo de Petición (Request-Example)**

```http
DELETE /api/v1/hardware/devices/1/unlink-from-zone/5 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Dispositivo desvinculado de la zona.

| Campo (Field) | Tipo (Type) | Descripción                        |
|-------------------|-----------------|----------------------------------------|
| success           | Boolean         | true si la desvinculación fue exitosa. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo o zona no encontrados."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/devices/{id}/zone**

Obtiene la zona de cultivo a la que está vinculado un dispositivo, incluyendo el nombre del cultivo asignado.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción     |
|-------------------|-----------------|---------------------|
| id                | Integer (path)  | ID del dispositivo. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/zone HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Información de la zona vinculada.

| Campo (Field) | Tipo (Type) | Descripción              |
|-------------------|-----------------|------------------------------|
| zoneId            | Integer         | ID de la zona.               |
| zoneName          | String          | Nombre de la zona.           |
| cropName          | String          | Nombre del cultivo asignado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "zoneId": 5,
    "zoneName": "Sector Norte",
    "cropName": "Tomate"
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: El dispositivo no está vinculado a ninguna zona."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/zones/{zoneId}/devices**

Lista todos los microcontroladores asignados a una zona de cultivo con un resumen de sus sensores y actuadores.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|-------------------|-----------------|-----------------|
| zoneId            | Integer (path)  | ID de la zona.  |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/zones/5/devices HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Array de dispositivos de la zona.

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| deviceId          | Integer         | ID del dispositivo.               |
| model             | String          | Modelo del hardware.              |
| macAddress        | String          | Dirección MAC.                    |
| status            | String          | Estado actual.                    |
| lastSeen          | DateTime?       | Último timestamp.                 |
| sensorCount       | Integer         | Número de sensores registrados.   |
| actuatorCount     | Integer         | Número de actuadores registrados. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "deviceId": 1, "model": "ESP32-WROOM", "status": "ONLINE",
        "sensorCount": 2, "actuatorCount": 1
        ...
        "}]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/devices/{id}/telemetry**

Obtiene el snapshot más reciente de telemetría de un dispositivo: todas las lecturas actuales de sus sensores, nivel de batería y señal.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type)     | Descripción             |
|-------------------|---------------------|-----------------------------|
| id                | Integer (path)      | ID del dispositivo.         |
| sensorTypes       | String[]? (query) | Filtrar por tipo de sensor. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/telemetry HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Snapshot de telemetría del dispositivo.

| Campo (Field) | Tipo (Type) | Descripción                      |
|-------------------|-----------------|--------------------------------------|
| deviceId          | Integer         | ID del dispositivo.                  |
| timestamp         | DateTime        | Fecha del snapshot.                  |
| readings          | Array           | [{ sensorId, type, value, unit }]. |
| batteryLevel      | Integer?        | Nivel de batería en %.               |
| signalStrength    | Integer?        | Intensidad de señal WiFi en dBm.     |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 1,
    "timestamp": "2026-06-08T00:04:00Z",
    "readings": [{ "sensorId": 2, "type": "AIR_TEMPERATURE", "value": 38.0, "unit": "°C" }],
    "batteryLevel": 85,
    "signalStrength": -65
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/devices/{id}/status**

Consulta el estado de conexión actual de un microcontrolador junto con el tiempo en línea.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción     |
|-------------------|-----------------|---------------------|
| id                | Integer (path)  | ID del dispositivo. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/status HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Estado actual del dispositivo.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| deviceId | Integer | ID del dispositivo. |
| status | String | ONLINE, OFFLINE, MAINTENANCE o ERROR. |
| lastSeen | DateTime? | Último timestamp de actividad. |
| uptimeSeconds | Integer? | Segundos en línea desde el último arranque. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 1,
    "status": "ONLINE",
    "lastSeen": "2026-06-08T00:04:00Z",
    "uptimeSeconds": 3600
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/devices/{id}/diagnostic**

Ejecuta un diagnóstico completo del dispositivo verificando conectividad, estado de sensores y actuadores. Requiere permiso HARDWARE_DIAGNOSTIC.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso HARDWARE_DIAGNOSTIC o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer (path) | ID del dispositivo. |
| includeSensors | Boolean (query) | Incluir diagnóstico de sensores. Default: true. |
| includeActuators | Boolean (query) | Incluir diagnóstico de actuadores. Default: true. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/diagnostic?includeSensors=true HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Resultado del diagnóstico del dispositivo.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| deviceId | Integer | ID del dispositivo. |
| timestamp | DateTime | Fecha del diagnóstico. |
| overallStatus | String | HEALTHY, DEGRADED o CRITICAL. |
| checks | Object | { connectivity, sensors[], actuators[] }. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 1,
    "timestamp": "2026-06-08T00:05:00Z",
    "overallStatus": "HEALTHY",
    "checks": { "connectivity": "OK", "sensors": [], "actuators": [] }
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "FORBIDDEN: Permiso HARDWARE_DIAGNOSTIC requerido."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**POST /api/v1/hardware/devices/{deviceId}/maintenance-logs**

Registra un log de mantenimiento para un dispositivo. El userId se toma automáticamente del token JWT.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| deviceId | Integer (path) | ID del dispositivo. |
| action | String | Acción realizada. Ej: CALIBRACION_SENSOR, LIMPIEZA, REEMPLAZO. |
| statusAfter | String | Estado del dispositivo tras el mantenimiento. Ej: ONLINE. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "action": "CALIBRACION_SENSOR",
    "statusAfter": "ONLINE"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 201 Created

Log de mantenimiento registrado.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| logId | Integer | ID del log creado. |
| deviceId | Integer | Dispositivo mantenido. |
| userId | Integer | Usuario que realizó el mantenimiento (del JWT). |
| action | String | Acción registrada. |
| statusAfter | String | Estado post-mantenimiento. |
| timestamp | DateTime | Fecha del mantenimiento. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "logId": 5,
    "deviceId": 1,
    "userId": 3,
    "action": "CALIBRACION_SENSOR",
    "statusAfter": "ONLINE",
    "timestamp": "2026-06-08T00:10:00Z"
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/hardware/devices/{deviceId}/maintenance-logs**

Lista el historial de logs de mantenimiento de un dispositivo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                        |
|-------------------|-----------------|----------------------------------------|
| deviceId          | Integer (path)  | ID del dispositivo.                    |
| limit             | Integer (query) | Máximo de logs. Default: 50, max: 200. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/maintenance-logs?limit=10 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Historial de mantenimiento del dispositivo.

| Campo (Field) | Tipo (Type) | Descripción                       |
|-------------------|-----------------|---------------------------------------|
| logId             | Integer         | ID del log.                           |
| deviceId          | Integer         | ID del dispositivo.                   |
| userId            | Integer         | Usuario que realizó el mantenimiento. |
| action            | String          | Acción realizada.                     |
| statusAfter       | String          | Estado post-mantenimiento.            |
| timestamp         | DateTime        | Fecha.                                |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "logId": 5, "deviceId": 1, "userId": 3,
        "action": "CALIBRACION_SENSOR", "statusAfter": "ONLINE",
        "timestamp": "2026-06-08T00:10:00Z"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**POST /api/v1/hardware/devices/{deviceId}/technical-maintenance**

Registra una revisión técnica formal realizada por personal de staff sobre un dispositivo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros del Cuerpo (Request Body Parameters)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| deviceId | Integer (path) | ID del dispositivo. |
| staffId | Integer | ID del miembro de staff que realizó el mantenimiento. |
| type | String | Tipo: PREVENTIVO, CORRECTIVO. |
| description | String | Descripción de las tareas realizadas. |
| results | String? | Resultados o hallazgos. Opcional. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "staffId": 1,
    "type": "PREVENTIVO",
    "description": "Revisión mensual completa",
    "results": "Todos los sensores calibrados correctamente"
}
```

**Respuestas del servidor (Responses)**

Éxito: Código 201 Created

Mantenimiento técnico registrado.

| Campo (Field) | Tipo (Type) | Descripción          |
|-------------------|-----------------|--------------------------|
| maintenanceId     | Integer         | ID del registro.         |
| staffId           | Integer         | ID del staff.            |
| deviceId          | Integer         | ID del dispositivo.      |
| type              | String          | Tipo de mantenimiento.   |
| description       | String          | Descripción.             |
| date              | DateTime        | Fecha del mantenimiento. |
| results           | String?         | Resultados.              |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "maintenanceId": 3,
    "staffId": 1,
    "deviceId": 1,
    "type": "PREVENTIVO",
    "date": "2026-06-08T00:15:00Z"
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 404,
    "message": "NOT_FOUND: Dispositivo no encontrado."
}
```

**D. Evidencia en Swagger**

<img src="">

<img src="">

**GET /api/v1/hardware/devices/{deviceId}/technical-maintenance**

Lista el historial de mantenimientos técnicos formales de un dispositivo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                   |
|-------------------|-----------------|-----------------------------------|
| deviceId          | Integer (path)  | ID del dispositivo.               |
| limit             | Integer (query) | Máximo de registros. Default: 50. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/devices/1/technical-maintenance HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Historial de mantenimientos técnicos.

| Campo (Field) | Tipo (Type) | Descripción                |
|-------------------|-----------------|--------------------------------|
| maintenanceId     | Integer         | ID del registro.               |
| staffId           | Integer         | Staff responsable.             |
| type              | String          | Tipo: PREVENTIVO o CORRECTIVO. |
| description       | String          | Descripción.                   |
| date              | DateTime        | Fecha.                         |
| results           | String?         | Resultados.                    |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "maintenanceId": 3, "staffId": 1, "type": "PREVENTIVO",
        "description": "Revisión mensual", "date": "2026-06-08T00:15:00Z"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/actuators/{actuatorId}/action-queue**

Lista la cola de comandos pendientes, enviados y completados para un actuador específico (ej. válvula de riego).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso DEVICE_CONFIG o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                  |
|-------------------|-----------------|----------------------------------|
| actuatorId        | Integer (path)  | ID del actuador.                 |
| limit             | Integer (query) | Máximo de entradas. Default: 50. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/actuators/1/action-queue?limit=20 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Cola de acciones del actuador.

| Campo (Field) | Tipo (Type) | Descripción                    |
|-------------------|-----------------|------------------------------------|
| actionId          | Integer         | ID de la acción.                   |
| actuatorId        | Integer         | ID del actuador.                   |
| command           | String          | Comando: OPEN o CLOSE.             |
| status            | String          | PENDING, SENT, COMPLETED o FAILED. |
| createdAt         | DateTime        | Fecha de creación del comando.     |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "actionId": 10, "actuatorId": 1,
        "command": "OPEN", "status": "COMPLETED",
        "createdAt": "2026-06-08T06:30:00Z"
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/health/live**

Probe de liveness del microservicio HardwareDevice.Api. Confirma que el proceso HTTP está activo.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción            |
|-------------------|-----------------|----------------------------|
| —                 | —               | No requiere autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/health/live HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio activo.

| Campo (Field) | Tipo (Type) | Descripción  |
|-------------------|-----------------|------------------|
| status            | String          | OK.              |
| timestamp         | DateTime        | Fecha del check. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "OK",
    "timestamp": "2026-06-08T00:00:00Z"
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy"
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/hardware/health/ready**

Probe de readiness del microservicio HardwareDevice.Api. Verifica conectividad con MySQL.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción            |
|-------------------|-----------------|----------------------------|
| —                 | —               | No requiere autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/hardware/health/ready HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio listo.

| Campo (Field) | Tipo (Type) | Descripción              |
|-------------------|-----------------|------------------------------|
| status            | String          | Healthy.                     |
| checks            | Object          | { coreDatabase: "Healthy" }. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "Healthy",
    "checks": { "coreDatabase": "Healthy" }
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy"
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/telemetry/actuators/{actuatorId}/logs**

Lista el historial de acciones ejecutadas por un actuador (apertura/cierre de válvula). Útil para auditoría de ciclos de riego y diagnóstico.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Permiso TELEMETRY_VIEW o admin. Formato: Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

| Campo (Field) | Tipo (Type) | Descripción                         |
|-------------------|-----------------|-----------------------------------------|
| actuatorId        | Integer (path)  | ID del actuador.                        |
| limit             | Integer (query) | Máximo de logs. Default: 100, max: 500. |

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/actuators/1/logs?limit=50 HTTP/1.1
Host: api.grotix.pe
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Historial de acciones del actuador.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| logId | Integer | ID del log. |
| actuatorId | Integer | ID del actuador. |
| action | String | Acción ejecutada: OPEN o CLOSE. |
| duration | Integer? | Duración de la acción en segundos. |
| timestamp | DateTime | Fecha y hora de la acción. |
| flowRate | Float? | Caudal registrado durante la acción (si aplica). |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[{
        "logId": 25, "actuatorId": 1, "action": "OPEN",
        "duration": 2700, "timestamp": "2026-06-08T06:30:00Z", "flowRate": 1.25
    }]
```

**Error: Código 401 Unauthorized**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 401,
    "message": "NOT_AUTHORIZED: Token inválido o expirado."
}
```

**D. Evidencia en Swagger**

<img src="">

Está vacío porque solo muestra las órdenes pendientes, una vez enviadas pasarán a estar enviadas o completada.

**GET /api/v1/telemetry/health/live**

Probe de liveness del microservicio Telemetry.Api. También reporta el estado de conectividad con RabbitMQ.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción            |
|-------------------|-----------------|----------------------------|
| —                 | —               | No requiere autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/health/live HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio activo.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| status | String | OK. |
| timestamp | DateTime | Fecha del check. |
| messageBroker | String | Estado de RabbitMQ: Connected o Disconnected. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "OK",
    "timestamp": "2026-06-08T00:00:00Z",
    "messageBroker": "Connected"
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy"
}
```

**D. Evidencia en Swagger**

<img src="">

**GET /api/v1/telemetry/health/ready**

Probe de readiness del microservicio Telemetry.Api. Verifica TimescaleDB, MySQL y RabbitMQ antes de recibir tráfico.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción            |
|-------------------|-----------------|----------------------------|
| —                 | —               | No requiere autenticación. |

**B. Parámetros de Búsqueda (Query Parameters)**

No requiere parámetros.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/telemetry/health/ready HTTP/1.1
Host: api.grotix.pe
```

**Respuestas del servidor (Responses)**

Éxito: Código 200 OK

Servicio listo para recibir tráfico.

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| status | String | Healthy. |
| checks | Object | { database, coreDatabase, messageBroker }. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "status": "Healthy",
    "checks": { "database": "Healthy", "coreDatabase": "Healthy", "messageBroker": "Healthy" }
}
```

**Error: Código 503 Service Unavailable**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": "Unhealthy",
    "checks": { "database": "Unhealthy" }
}
```

**D. Evidencia en Swagger**

<img src="">

#### 6.2.2.8. Software Deployment Evidence for Sprint Review

<img src="https://imgur.com/WPXtAzQ.png">

Configuración inicial de un servidor flexible de PostgreSQL en Microsoft Azure. En esta etapa se definieron los parámetros principales del servicio, incluyendo la suscripción, grupo de recursos, nombre del servidor, región de despliegue y versión de PostgreSQL, preparando la infraestructura de base de datos para soportar los servicios backend de la aplicación.

<img src="https://imgur.com/MNKUmhP.png">

Visualización del servidor PostgreSQL grotixtelemetry una vez completado el aprovisionamiento en Microsoft Azure. En la captura se muestra el estado Ready, confirmando que la instancia de base de datos fue desplegada correctamente y quedó disponible para su integración con los servicios backend de la solución durante el Sprint.

<img src="https://imgur.com/dapVAfY.png">

Configuración de los parámetros avanzados del servidor PostgreSQL en Azure, donde se habilitó la extensión TimescaleDB mediante el parámetro azure.extensions. Esta extensión permite optimizar el almacenamiento y procesamiento de datos de series temporales, facilitando la gestión eficiente de información telemétrica generada por los dispositivos IoT de la solución.

<img src="https://imgur.com/bikIOrd.png">

Configuración del parámetro shared_preload_libraries para precargar la librería TimescaleDB durante el inicio del servidor PostgreSQL. Esta acción es necesaria para habilitar completamente las funcionalidades de la extensión y garantizar su correcto funcionamiento en el procesamiento de datos de series temporales. Posteriormente, se reinició el servidor para aplicar los cambios realizados.

<img src="https://imgur.com/I2sYQBJ.png">

Conexión exitosa al servidor PostgreSQL desplegado en Azure mediante el cliente psql. Durante este paso se creó la base de datos grotix_telemetry y se estableció la conexión a ella, dejando preparado el entorno para el almacenamiento y gestión de los datos telemétricos generados por la aplicación.

<img src="https://imgur.com/I4sfynP.png">

Creación y validación de la extensión TimescaleDB dentro de la base de datos grotix_telemetry mediante comandos SQL ejecutados desde psql. Esta configuración habilita capacidades avanzadas para el almacenamiento y análisis eficiente de datos de series temporales, requisito fundamental para el procesamiento de información telemétrica en la solución IoT.

<img src="https://imgur.com/791cdqE.png">

Verificación de las extensiones instaladas en la base de datos grotix_telemetry mediante el comando \dx. La captura confirma que la extensión TimescaleDB fue instalada correctamente y se encuentra activa, permitiendo el manejo optimizado de datos de series temporales requeridos por el sistema de telemetría.

<img src="https://imgur.com/BP1tzbb.png">

Configuración y actualización de las variables de entorno de la aplicación web desplegada en Azure App Service. En esta etapa se definieron parámetros esenciales como las cadenas de conexión a la base de datos, configuraciones de RabbitMQ, variables de autenticación, entorno de ejecución y opciones de monitoreo, permitiendo que los servicios funcionen correctamente en el entorno productivo de la nube.

<img src="https://imgur.com/yqIysJX.png">

Desarrollo de un script automatizado de despliegue utilizando PowerShell y Azure CLI para simplificar la publicación de servicios en Azure App Service. El script automatiza tareas como la compilación del proyecto .NET, la generación del paquete de despliegue y la publicación de la aplicación en la nube, reduciendo el esfuerzo manual y garantizando un proceso de deployment más rápido, consistente y reproducible.

<img src="https://imgur.com/Uu2Gmyq.png">

<img src="https://imgur.com/QiMsrQX.png">

Ejecución del script automatizado de despliegue para el servicio Profiles.Api. Durante el proceso se realizó la compilación del proyecto, la generación del paquete comprimido de publicación y su despliegue en Azure App Service. La salida de la consola confirma que la compilación, transferencia y puesta en marcha del servicio se completaron exitosamente, validando el correcto funcionamiento del proceso automatizado de deployment para cada microservicio de la solución.

<img src="https://imgur.com/vuVAuv9.png">

Validación del despliegue mediante la ejecución del endpoint de salud (/live) desde la documentación Swagger publicada en Azure. La respuesta exitosa con código 200 OK confirma que el servicio se encuentra operativo, accesible desde Internet y funcionando correctamente después del proceso de deployment realizado durante el Sprint.

<img src="https://imgur.com/bYACcnQ.png">

Creación de una instancia de CloudAMQP como servicio administrado de RabbitMQ en la nube. Esta configuración permitió disponer de un broker de mensajería accesible desde Internet para soportar la comunicación asíncrona entre los microservicios de la solución, facilitando el intercambio de eventos y datos telemétricos de manera escalable y desacoplada.

<img src="https://imgur.com/AHD3fKG.png">

<img src="https://imgur.com/3hRZski.png">

<img src="https://imgur.com/rmcTrxv.png">

<img src="https://imgur.com/iXodZWQ.png">

Configuración de una instancia de RabbitMQ en CloudAMQP y parametrización de los servicios desplegados mediante variables de entorno. Durante este proceso se seleccionó el plan y la región de despliegue del broker, obteniendo posteriormente los datos de conexión (host, puerto, usuario, contraseña y virtual host), los cuales fueron registrados en Azure App Service para permitir la comunicación asíncrona entre los microservicios de la solución.

<img src="https://imgur.com/ACP52js.png">

Procedemos a crear la carpeta dist para el redespliegue de la aplicación web.

<img src="https://imgur.com/Q3l9fcF.png">

Y desplegamos la aplicación web.

<img src="https://imgur.com/djbEy9B.png">

Configuramos GithubActions para que automatice la generación del apk cada vez que se realizan cambios en la rama main y que se desplieguen el release.

<img src="https://imgur.com/0AYHwMj.png">

Una vez subido este cambio, se genera el archivo apk listo para descargar en cualquier dispositivo android.

#### 6.2.2.9. Team Collaboration Insights during Sprint

La implementación de la plataforma Grotix se ha desarrollado bajo un marco de trabajo ágil, priorizando la integración continua y la entrega de valor incremental. El equipo consolidó una estrategia basada en GitFlow para la gestión de versiones, lo que permitió el co-desarrollo y despliegue paralelo de los cuatro ecosistemas clave del proyecto: el módulo de procesamiento de datos e inteligencia agrícola (Grotix_Crop_Analysis), la aplicación para dispositivos móviles (Grotix_Mobile), la arquitectura de microservicios del backend (Web Services) y la aplicación web adaptativa (Web).

**Analíticos de Colaboración y Contribuciones**

A continuación, se presentan los indicadores de actividad de los repositorios oficiales en GitHub, los cuales reflejan la dinámica de trabajo, la frecuencia de integraciones y el flujo de colaboración del equipo durante el presente ciclo de desarrollo.

### 6.2.3. Sprint 3

#### 6.2.3.1. Sprint Planning 3

| Campo | Detalle |
|---|---|
| Sprint # | Sprint 3 |
| **Sprint Planning Background** |  |
| Date | 28/06/26 |
| Time | 20:00 |
| Location | Reunión Virtual de Google Meet |
| Prepared By | Cassius Martel |
| Attendees (to planning meeting) | Binda Arbañil, Marcelo Alejandro / Castillo Garay, Ainhoa Lucía / Martel Andrade, Cassius Estefano / Nakamurakare Teruya, Alex Tomio |
| Review Summary | Presentación exitosa de la integración end-to-end entre el hardware IoT (ESP32) y la plataforma Grotix, logrando la captura de telemetría fiel en tiempo real y el control bidireccional del riego (automático y manual). Se logró un hito arquitectónico al desplegar persistencia local (SQLite) en la capa Edge, garantizando el funcionamiento offline del sistema. Asimismo, se integró exitosamente la API de Gemini para diagnósticos fenológicos con visión artificial. La arquitectura ahora soporta reportería histórica, alertas push y vinculación segura de microcontroladores mediante la Web App. Todas las tareas de las historias asignadas fueron integradas y pasaron a estado "Done". |
| Retrospective Summary | El equipo demostró una excelente capacidad de coordinación técnica al trabajar simultáneamente en firmware (C++), backend (.NET/Python) y frontend (Flutter/Vue.js). La implementación del Edge Computing (Store-and-Forward y SQLite) representó un desafío de bajo nivel que se superó con éxito, aumentando drásticamente la resiliencia de la plataforma ante fallos de red. Se identificó que la generación delegada de links de invitación mejoró la seguridad del *onboarding* de nuevos agricultores. |
| **Sprint Goal & User Stories** |  |
| Sprint 3 Goal | Consolidar la capacidad operativa y autónoma del ecosistema Grotix mediante la integración definitiva del hardware IoT en campo. El objetivo es habilitar el monitoreo preciso, la automatización del riego con tolerancia a fallos de conectividad (Edge Computing), proveer análisis avanzado de cultivos mediante Inteligencia Artificial (Gemini), e implementar un robusto sistema de notificaciones y reportes para una toma de decisiones eficiente por parte del agricultor. |
| Sprint 3 Velocity | 56 |
| Sum of Story Points | 60 |

#### 6.2.3.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Frontend & UI/UX | Backend & API | QA & Testing | Infrastructure & Deployment | Project Management |
|----|----|----|----|----|----|----|
| Martel Andrade, Cassius Estefano | kcc12321 | C | C | C | C | L |
| Binda Arbañil, Marcelo Alejandro | MarceHkd | L | C | C | C | C |
| Castillo Garay, Ainhoa Lucía | noaa01100001 | C | C | L | C | C |
| Nakamurakare Teruya, Alex Tomio | kistoo | C | L | C | L | C |

#### 6.2.3.3. Sprint Backlog 3

| User Story Id | User Story Title | Work-Item / Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status (To-do / In-Process / To-Review / Done) |
|---|---|---|---|---|---|---|---|
| US10 | Vinculación del Microcontrolador con la Aplicación | T86 | Interfaz UI de vinculación en Web App | Desarrollo del formulario en Vue.js para que el staff asigne microcontroladores a zonas específicas. | 3 | Web Dev | Done |
| US10 | Vinculación del Microcontrolador con la Aplicación | T87 | Lógica Frontend de asignación | Implementación de validaciones en la web para asociar la MAC Address del ESP32 a la cuenta del agricultor. | 2 | Web Dev | Done |
| US11 | Monitoreo fiel de las condiciones del entorno | T88 | Lectura analógica/digital en C++ | Configuración de pines GPIO en el ESP32 para capturar humedad de suelo, temperatura y luz. | 3 | Embedded Dev | Done |
| US11 | Monitoreo fiel de las condiciones del entorno | T89 | Integración del flujo Edge a Frontend | Conexión de la App Móvil para consumir directamente los datos crudos desde la capa Edge y renderizarlos. | 3 | Mobile Dev | Done |
| US11 | Monitoreo fiel de las condiciones del entorno | T90 | Lógica de estado Online/Offline de dispositivos | Lógica en Backend (.NET) para actualizar el estado del dispositivo basándose en la marca de tiempo lastSeen de su última lectura. | 2 | Backend Dev | Done |
| US12 | Actualización periódica y automática de telemetría | T91 | Ciclo de lectura cada 15 min | Programación de timers en el firmware del microcontrolador para enviar ráfagas de datos dependiendo de la cantidad de tiempo asignada en frontend. | 2 | Embedded Dev | Done |
| US12 | Actualización periódica y automática de telemetría | T92 | Renderizado reactivo en Dashboard | Configuración en Flutter/Dart para actualizar visualmente las métricas cada que ingresa una nueva trama de datos. | 3 | Mobile Dev | Done |
| US12 | Actualización periódica y automática de telemetría | T93 | Notificaciones In-App de actualización | Implementación de alertas (snackbars) en la interfaz móvil avisando al usuario que hay nuevas lecturas disponibles. | 2 | Mobile Dev | Done |
| US13 | Garantía de exactitud en la medición de datos | T94 | Mapeo matemático en firmware | Ajuste en el código del ESP32 para convertir los voltajes analógicos en porcentajes exactos de humedad/temperatura. | 3 | Embedded Dev | Done |
| US13 | Garantía de exactitud en la medición de datos | T95 | Calibración de precisión de sensores | Pruebas físicas y ajustes de sensibilidad en el código de la Embedded App para asegurar el margen de error < 2%. | 2 | Embedded Dev | Done |
| US15 | Organización de dispositivos por zonas y especies | T96 | Módulo Web de Creación de Zonas | Desarrollo de las vistas para que el staff de Grotix cree, liste y asigne características a las zonas de cultivo. | 4 | Web Dev | Done |
| US15 | Organización de dispositivos por zonas y especies | T97 | Renderizado de Zonas en UI | Lógica en el frontend para organizar gráficamente las tarjetas de dispositivos agrupados por zona. | 2 | Web/Mobile Dev | Done |
| US19 | Activación manual del sistema de irrigación | T98 | Control UI para riego manual | Diseño e integración del botón interactivo en la app móvil para encender o apagar el riego a voluntad. | 2 | Mobile Dev | Done |
| US19 | Activación manual del sistema de irrigación | T99 | Parámetro IrrigationMode en Zonas | Modificación en la entidad Zone del Backend (.NET) para incluir la bandera IrrigationMode (Auto/Manual). | 1 | Backend Dev | Done |
| US19 | Activación manual del sistema de irrigación | T100 | Ejecución de actuador | Código en el ESP32 para escuchar la orden manual proveniente de la app y encender físicamente la bomba de agua. | 3 | Embedded Dev | Done |
| US20 | Automatización del riego mediante aprendizaje automático | T101 | Motor de evaluación autónoma en ESP32 | Lógica embebida en C++ para que el microcontrolador accione el riego por sí solo de forma autónoma. | 4 | Embedded Dev | Done |
| US20 | Automatización del riego mediante aprendizaje automático | T102 | Reglas de seguridad en Hardware | Programación de un "Auto-Stop" del actuador en el firmware para evitar inundaciones. | 2 | Embedded Dev | Done |
| US24 | Registro, inicio y cierre de sesión de usuario | T103 | Panel Web de Enlaces de Invitación | Creación de interfaz en la Web App para que el staff genere y copie los links de registro para los agricultores. | 3 | Web Dev | Done |
| US24 | Registro, inicio y cierre de sesión de usuario | T104 | Pantalla de Registro de Agricultor | Maquetado de la vista de registro accesible vía link para capturar los datos básicos del usuario. | 3 | Web Dev | Done |
| US24 | Registro, inicio y cierre de sesión de usuario | T105 | Interfaz de Login Móvil | Diseño de la pantalla de autenticación en la app móvil con validación simple de campos y credenciales. | 3 | Mobile Dev | Done |
| US24 | Registro, inicio y cierre de sesión de usuario | T106 | Almacenamiento local de Sesión | Uso de Secure Storage/SharedPreferences en la App Móvil para mantener la sesión abierta o cerrarla (Logout). | 2 | Mobile Dev | Done |
| US22 | Gestión de registro fotográfico de cultivos | T107 | Despliegue de Crop Analysis Service | Configuración del contenedor y despliegue del microservicio dedicado al análisis de imágenes en Azure. | 3 | Backend Dev | Done |
| US22 | Gestión de registro fotográfico de cultivos | T108 | Endpoint POST de ingesta de imágenes | Desarrollo del servicio REST para recibir la imagen desde el cliente, procesarla temporalmente y prepararla para la IA. | 2 | Backend Dev | Done |
| US22 | Gestión de registro fotográfico de cultivos | T109 | Integración con API de Gemini | Implementación del cliente HTTP en el backend para enviar la imagen al modelo de IA y extraer el diagnóstico fenológico en JSON. | 4 | Backend Dev |  |
| US22 | Gestión de registro fotográfico de cultivos | T110 | Módulo de cámara y galería Móvil | Implementación de permisos nativos y lógica en la App Móvil para tomar fotos o elegirlas de la galería. | 3 | Mobile Dev |  |
| US23 | Clasificación del estado fenológico mediante Inteligencia Artificial | T111 | Interfaz de resultados y diagnóstico | Renderizado dinámico en la app móvil de la puntuación de salud y el resumen devuelto por Gemini. | 3 | Mobile Dev |  |
| US27 | Visualización del estado de servicios | T112 | Endpoint de Contratos y Suscripciones | Creación del endpoint para devolver el estado lógico del servicio del cliente. | 2 | Backend Dev | Done |
| US27 | Visualización del estado de servicios | T113 | Provider/Service de Contratos en Flutter | Lógica de consumo HTTP y manejo de estado en la aplicación móvil para retener los datos de la suscripción. . | 2 | Mobile Dev | Done |
| US27 | Visualización del estado de servicios | T114 | Panel "Mi Suscripción" en App Móvil | en App MóvilMaquetado de la tarjeta visual que muestra el plan vigente, fechas de corte y estado de conectividad al usuario. | 2 | Mobile Dev | Done |
| US17 | Persistencia de datos ante pérdida de conectividad | T115 | Sistema de archivos en Edge | Configuración de la partición de memoria en el ESP32 para permitir almacenamiento no volátil. | 2 | Embedded Dev | Done |
| US17 | Persistencia de datos ante pérdida de conectividad | T116 | Inicialización de SQLite en firmware | Inserción de la librería SQLite y creación de la tabla local ZoneThresholds dentro del microcontrolador. | 4 | Embedded Dev | Done |
| US17 | Persistencia de datos ante pérdida de conectividad | T117 | Sincronización de umbrales (Nube -> Edge) | Lógica para descargar y guardar los umbrales de humedad en SQLite cada vez que el ESP32 tiene conexión a Internet. | 3 | Embedded Dev | Done |
| US17 | Persistencia de datos ante pérdida de conectividad | T118 | Motor de evaluación offline | Algoritmo que lee SQLite localmente para activar el relé de la bomba de agua cuando el internet se cae (Offline mode). | 4 | Embedded Dev | Done |
| US21 | Generación y descarga de reportes históricos | T119 | Endpoint de agregación estadística | Lógica en BD PostgreSQL/Backend para calcular promedios de humedad, temperatura y luz por rangos de fecha. | 4 | Backend Dev | Done |
| US21 | Generación y descarga de reportes históricos | T120 | Endpoint de ciclos de riego | Creación de servicio para devolver la cantidad de ciclos de riego en una zona específica. | 2 | Backend Dev | Done |
| US21 | Generación y descarga de reportes históricos | T121 | Selectores de Fecha (Date Picker) UI | Selectores de Fecha (Date Picker) UI | 2 | Mobile Dev | Done |
| US21 | Generación y descarga de reportes históricos | T122 | Endpoint GET de Hardware | Creación de servicio para devolver el hardware específico de una zona | 4 | Backend Dev | Done |
| US21 | Generación y descarga de reportes históricos | T123 | Exportación de reporte a PDF | Implementación del motor de renderizado de documentos en el cliente para descargar la información estructurada. | 3 | Mobile Dev | Done |
| US26 y U18 | Configuración y gestión de alertas de usuario / Notificaciones automáticas por riego y disponibilidad de dispositivos | T124 | Configuración de servicio | Setup del gestor de notificaciones en el backend con los tokens de dispositivo. | 3 | Backend Dev | Done |
| US26 y U18 | Configuración y gestión de alertas de usuario / Notificaciones automáticas por riego y disponibilidad de dispositivos | T125 | Emisión de alertas de ciclo de riego | Lógica de disparador al guardar un *ActuatorLog* para notificar al agricultor que el riego empezó o terminó. | 2 | Backend Dev | Done |
| US26 y U18 | Configuración y gestión de alertas de usuario / Notificaciones automáticas por riego y disponibilidad de dispositivos | T126 | Worker de detección Offline | Tarea en segundo plano que revisa periódicamente el lastSeen y emite una alerta crítica si un microcontrolador se desconecta. | 3 | Backend Dev | Done |
| US26 y U18 | Configuración y gestión de alertas de usuario / Notificaciones automáticas por riego y disponibilidad de dispositivos | T127 | Listener de notificaciones | Configuración de los servicios nativos en Android/iOS para despertar la app y recibir la notificación Push. | 3 | Mobile Dev | Done |
| US26 y U18 | Configuración y gestión de alertas de usuario / Notificaciones automáticas por riego y disponibilidad de dispositivos | T128 | Bandeja In-App de Historial de Alertas | Creación de una vista estilo "Campanita" donde el usuario puede leer sus notificaciones pasadas. | 2 | Mobile Dev | Done |

#### 6.2.3.4. Development Evidence for Sprint Review

**Repository: Grotix_Web**

- **Branch:** develop

- **Total Commits:** 15

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Web | develop | 1da132448804b81e666a230b5a6720fb72d7127b | feat: add registration for agriculturist | 14/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web | develop | 394e7a29d121009c8c16b9461c36bf2979d3d1a2 | Add | 18/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web | develop | 50227ba5671095cfff092b230274ec76f79797bd | Fix display | 18/06/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web | develop | 02d263cb9b2ab787910f25c1067102a967ae81b0 | add registration invalidation for non staff user | 21/06/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web | develop | 52f5d1eee2ab6db09383155e9ad0a86c6184e08d | add comments | 21/06/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web | develop | 2655a006f91733c32227191f3fda75b2c6ea2ccd | feat: setup module scaffolding for device binding | 21/06/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web | develop | de33f8c8031080d40422d4d6d42a9b58058a9c40 | feat: implement form and validation for microcontroller linkage | 21/06/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web | develop | 552aa9e31987d869958ad477b3620f6b5bb4bd9f | feat: add zone creation dashboard for staff admin | 21/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web | develop | 90fa81126ec4234715e97d659d473c9c000e837f | feat: integrate zone service to display cultivation zones | 21/06/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web | develop | cb5126d34094a85ee81f40d3a1e62814e4e9a329 | feat: implement association invite generation UI | 21/06/2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Web | develop | ca25b4deb90525e0c0fc2a1aeb9be6f4de21f073 | feat: add route protection for registration invites | 21/06/2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Web | develop | fe57e46b944df01a96946bc334fa61c18403c7d6 | feat: develop farmer registration form with token validation | 21/06/2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Web | develop | c1cc4add35c0810203f65e4ff212e146a6b6ae7b | fix: resolve form state management in registration flow | 21/06/2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Web | develop | d4d4a0c50cb54c1f5b0a482723ff84197b057a23 | refactor: optimize reactive rendering for device status cards | 21/06/2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Web | develop | 9cc7ccb078822b5bdfce065dcf000a3e668030d3 | chore: prepare production build and environment configuration | 21/06/2026 |

**Repository: Grotix_Mobile**

- **Branch:** develop

- **Total Commits:** 39

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 4b3d8dfc290fcc90574317ce2a473b15d025b5a2 | Add telemetry | 18/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 90fbdf399d7c61ab990fa470ae918e2cb662cd85 | fix | 18/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c861c51de33dfb4ccb6762b0a09e9a0c91183241 | feat: modal de soporte para zonas y selección de cámara/galería en IA. fix: carga de telemetría y renderizado seguro de imágenes | 18/06/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 474e2749481b021ccd6ea72764c15dde4397bd21 | Merge branch 'features/zones' into develop - Conflictos resueltos | 18/06/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 504707b52a7850084827659c1d6a07cfe98b9586 | fix | 19/06/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c1714036f21c2dc96239c54eab82793dc0b5e1c7 | Fix | 19/06/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 03c750fa0ec1e2e39fc9acb4b00213d0319a8889 | fix manual irrigation logic | 21/06/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 43b31515cfaee7466164c244da2a12142b5d0f4c | fix auto irrigation logic | 21/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c03a13fb9064a91b6529e1bdf66658e8c6fec41c | add irrigation timer for UX | 21/06/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | ac8af9b87a5d71161957f6e6552f51ef3c5e120f | feat: integrate telemetry data fetching from edge services | 21/06/2026 |
| #11 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | fe9f3efc75e1bfb91a6bbe4fe0fef172352d12c8 | feat: add periodic polling for telemetry synchronization | 21/06/2026 |
| #12 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 2bb476e23244e781528d0b2b8316964654148638 | feat: implement snackbar notifications for new readings | 21/06/2026 |
| #13 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | ea18de0ad4e27b94713985e42481b6655da6fcb0 | feat: build irrigation control toggle UI for zones | 21/06/2026 |
| #14 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 387d615445eef23fe1a4fe95d8c125cffb159499 | feat: add API service calls for manual irrigation control | 21/06/2026 |
| #15 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | b91c416309e5fd27a90568214252c73ec9ed826a | refactor: optimize provider state management for sensor data | 21/06/2026 |
| #16 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 433589c103324c8773636986412b0303f2836d7a | fix: resolve responsive issues in device status cards | 21/06/2026 |
| #17 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 6a5b51d1668a4df382cdaf8b6b6d141b8597f479 | chore(setup): initialize sprint 3 dependencies and config files | 28/06/2026 |
| #18 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 52f219089248c48ce195955c2e666c4d8cbc7b1b | feat(domain): add Contract model entity | 28/06/2026 |
| #19 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 379d58e313b3954d9de45a4abb10cd55ea1ac3dd | feat(domain): add Notification model and data structures | 28/06/2026 |
| #20 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | a71e9f196c2cb078fbb50523dd49ee876078894d | feat(data): implement notification datasource | 28/06/2026 |
| #21 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | e0fa00da63c540e33587e64a5a592f9a7f4662f9 | feat(repository): add notification repository methods | 28/06/2026 |
| #22 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 4006a338d158508451234a52fb16d24af509d6e1 | feat(state): integrate notification logic in ProfileProvider | 28/06/2026 |
| #23 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 36fe12fb31f40e269ac88133f2bb70564d12a9cd | feat(ui): build notification history list screen | 28/06/2026 |
| #24 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | ca8cf5f441238b0170ba25d68e5d7d04bc463471 | feat(ui): add notification indicator to profile view | 28/06/2026 |
| #25 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 45c9acffc7b6bf62ffaf6296fd3416f6af4141ef | feat(data): extend AssociationRepository with contract fetch methods | 28/06/2026 |
| #26 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 6f89f180fde4c8ad0ef78e2913f2496b941d88f5 | feat(state): add subscription data binding to ProfileProvider | 28/06/2026 |
| #27 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 12a19a51d4f8f2e3cb632d987ce056219000342a | feat(ui): create subscription status card in profile | 28/06/2026 |
| #28 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 837b6751a0842396241bb73c736ad4f1e47b1824 | fix(contracts): implement null safety and empty state for subscriptions | 28/06/2026 |
| #29 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 3cc6b6f6f2a30f7adf99cdfb80379f51db2f589b | feat(data): add irrigation history datasource | 28/06/2026 |
| #30 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | b7324a8021019fc9e45e1eb33516311be7eea554 | feat(repository): implement telemetry query repository | 28/06/2026 |
| #31 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 7aa8b6d0aa0e91beb9421e96d80ba3bbc523fee7 | feat(ui): design irrigation report summary screen | 28/06/2026 |
| #32 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | ee0babdd6f8bbfedc551f9f793176bb8dc750fc8 | feat(ui): integrate data visualization for irrigation cycles | 28/06/2026 |
| #33 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | abdf7652cc7483f136e09dd11676d758f8ecf32d | feat(data): create image upload datasource with file picker | 28/06/2026 |
| #34 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 3ff62f0b436d4b94db565522436d6524909e7185 | feat(ui): implement image selection and upload preview flow | 28/06/2026 |
| #35 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 1ad7228dbff327a5e1e068844cdca88717de690b | feat(state): add IA diagnostic provider for state classification | 28/06/2026 |
| #36 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 05bc251176ab2ea8d3f4001036ca9632deb92282 | feat(ui): build plant health score and summary dashboard | 28/06/2026 |
| #37 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | 42be67bc47a43f7ec7bbfc919b14879597e7e227 | fix(dashboard): correct telemetry synchronization and local state cache | 28/06/2026 |
| #38 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | defcf6ac3f1310d0eefdc24b185d98b5339d4cea | refactor(profile): optimize profile data loading and network logic | 28/06/2026 |
| #39 | https://github.com/CeleviGrotix/Grotix_Mobile | develop | c19dc4435dddc4b8a5579de1c1c44d2b7b5c1d5b | fix(ui): polish styles, loading states, and error handling for new modules | 28/06/2026 |

**Repository: Grotix_Web_Services**

- **Branch:** develop

- **Total Commits:** 12

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 9e6d0e6576657aeb62f67ea859405b6c74ec09f3 | Update endpoint | 18/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 78451ade9b7a2104f6386dfbd6e2903edb12b60f | Add endpoint | 19/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | b6de5d3727380eed055bf5cf0e499d7110907ae7 | feat(hardware): implement background worker for device offline detection | 28/06/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 75fc8b3711b92e840f06c1cf3af9cc5f712294c9 | feat(hardware): create service to retrieve hardware inventory by zone | 28/06/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 959e0b51098b5a114c8dddc6d94a9d9248aa3cc0 | feat(irrigation): implement actuator log trigger for irrigation lifecycle notifications | 28/06/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 9b7f287af09f27d380e9eacea7a235c73d01c874 | feat(irrigation): implement service to track irrigation cycles by zone | 28/06/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 7b582737cbb33c900acf1ada7ff41782e52bb39a | feat(notifications): add device token management system for user push notifications | 28/06/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 11f3b5d905734fb3a09afea0fed0e56e829c640e | feat(telemetry): implement aggregation logic for sensor statistics | 28/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 541836e07db0118c2c8fec60e1eee3c1cfbaa612 | feat(contracts): create endpoint for client service status reporting | 28/06/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 9f865ef60332ea9f232df732422d56ce1a0cf59b | feat(vision): implement rest endpoint for image upload and processing | 28/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | fe371f95e2c93f7497b671996160c6c4ba31f927 | feat(vision): implement http client for ia diagnostic model integration | 28/06/2026 |
| #10 | https://github.com/CeleviGrotix/Grotix_Web_Services | develop | 29e7b6f7c11144b50239d70dc96fc2a7cad1e3c6 | chore(infra): setup azure container deployment for vision microservice | 28/06/2026 |

**Repository: Grotix_Embedded**

- **Branch:** main

- **Total Commits:** 1

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Embedded | main | 8f6a65a275754a5442314e781a62abb6e80af78b | Add embedded app code | 01/07/2026 |

**Repository: Grotix_Edge**

- **Branch:** main

- **Total Commits:** 1

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Edge | main | 832fdc9fc1fdc796512809a7faa727eb6c55adce | Add edge app code | 01/07/2026 |

#### 6.2.3.5. Testing Suite Evidence for Sprint Review

Durante el ciclo de desarrollo actual, el equipo de Grotix consolidó una suite de pruebas automatizadas masiva para cubrir todo el ecosistema de microservicios. Nuestro enfoque de calidad garantiza la integridad de los *Bounded Contexts* mediante una estrategia de pruebas multinivel.

Si bien todas las funcionalidades del sistema fueron validadas bajo estándares de calidad, se aplicó una rigurosidad de prueba extendida sobre las User Stories US22, US23, US27, US21 y US26. Esta priorización responde a la alta complejidad técnica y criticidad de negocio que poseen estas funcionalidades

En el nivel unitario, se desarrollaron más de 70 pruebas automatizadas enfocadas en la integridad de los agregados de dominio y lógica de negocio pura, validando invariantes mediante mocks (Moq). En el nivel de integración, se implementaron más de 30 tests utilizando bases de datos en memoria (EF Core InMemory) para verificar la orquestación de servicios y reglas de autorización sin alterar la infraestructura real. Finalmente, en el nivel de aceptación (BDD), se ejecutaron más de 20 escenarios Gherkin mediante SpecFlow (.NET), asegurando que los flujos críticos cumplan estrictamente con las necesidades de negocio.

Enlaces a las ramas de testing:

- Testing de bounded context: [test/sprint-3-testing-suite](https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-3-testing-suite)

- Testing específicos de historias de usuario: [test/sprint-4-testing-suite](https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite)

| Secuencia | Repository | Branch | Commit Id | Commit Message | Committed on (Date) |
|----|----|----|----|----|----|
| #01 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-3-testing-suite | test/sprint-3-testing-suite | b8eba5abea5ce53bcef200e7a04b2427a7fad413 | test(sprint-3): implement comprehensive unit testing suite across all bounded contexts | 21/06/2026 |
| #02 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-3-testing-suite | test/sprint-3-testing-suite | 6f6a1018ee4b848612b6fd9b9469c9f8d0f39810 | test(sprint-3): implement integration testing suite via EF Core InMemory | 21/06/2026 |
| #03 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-3-testing-suite | test/sprint-3-testing-suite |  | test(sprint-3): introduce SpecFlow BDD step definitions for acceptance testing | 21/06/2026 |
| #04 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | e64a239dc0398b66ebbf0b2f6d6ae430c1496054 | testing-suite: Add Unit, Integration and BDD Tests for US22 | 28/06/2026 |
| #05 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | 71222781864373629179af635493aa6af38ef607 | testing-suite: Add Unit, Integration and BDD Tests for US23 | 28/06/2026 |
| #06 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | 383e9ac74fe497292427c701cfc60deb155fada9 | testing-suite: Add Unit, Integration and BDD Tests for US27 | 28/06/2026 |
| #07 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | 7283cba8165c4a49e51e9415cfbc7a8f593a1827 | testing-suite: Add Unit, Integration and BDD Tests for US21 | 28/06/2026 |
| #08 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | fca8c52f3bbc709f9769ce0ccc77d7fb1570383a | testing-suite: Add Unit, Integration and BDD Tests for US26 | 28/06/2026 |
| #09 | https://github.com/CeleviGrotix/Grotix_Web_Services/tree/test/sprint-4-testing-suite | test/sprint-4-testing-suite | cb1e074bf9f5bb354a4c90526706cf3613ff0410 | testing-suite: Testing and minor fixes | 28/06/2026 |

**Pruebas Unitarias (Unit Tests)**

**Control de Casos de Prueba - Profiles Unit Testing (US25)**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U61 | Identity (Aggregate) | Unitaria (xUnit) | Construcción válida de identidad | Email="juan@grotix.pe", PasswordHash válido | Instancia creada correctamente | Pasó |
| TC-U62 | Identity (Aggregate) | Unitaria (xUnit) | Email con formato inválido | Email="juan@@grotix" | Lanza ArgumentException | Pasó |
| TC-U63 | InviteTokenHasher | Unitaria (xUnit) | Verificación de token válido | Token plano + hash almacenado coinciden | Retorna true | Pasó |
| TC-U64 | InviteTokenHasher | Unitaria (xUnit) | Verificación de token expirado | Invite.ExpiresAt < DateTime.UtcNow | Retorna false | Pasó |
| TC-U65 | CreateAccountHandler | Unitaria (xUnit) | Email no coincide con invitación | InviteEmail≠RequestEmail | Lanza ArgumentException | Pasó |
| TC-U66 | CreateAccountHandler | Unitaria (xUnit) | Registro exitoso con invitación válida | Token válido, datos completos | Persiste Identity y User, publica UserRegistered | Pasó |

**Control de Casos de Prueba - Hardware Device Unit Testing (US10)**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U67 | Microcontroller (Aggregate) | Unitaria (xUnit) | Vinculación válida a zona | MacAddress válida, ZoneId=3 | ZoneId asignado, Status=OFFLINE | Pasó |
| TC-U68 | Microcontroller (Aggregate) | Unitaria (xUnit) | MAC Address con formato inválido | MacAddress="00:1A:ZZ" | Lanza ArgumentException | Pasó |
| TC-U69 | Microcontroller (Aggregate) | Unitaria (xUnit) | Vinculación a zona inexistente | ZoneId=0 | Lanza ArgumentException | Pasó |
| TC-U70 | Microcontroller (Aggregate) | Unitaria (xUnit) | Reasignación de zona sin desvincular | ZoneId 3 -> 7 | ZoneId actualizado a 7 | Pasó |
| TC-U71 | MicrocontrollerCommandService | Unitaria (xUnit) | MAC ya vinculada a otra cuenta | MacAddress existente en BD | Lanza ArgumentException ("Dispositivo ya vinculado") | Pasó |
| TC-U72 | MicrocontrollerCommandService | Unitaria (xUnit) | Marca de dispositivo offline por heartbeat vencido | LastSeen hace 16 minutos | Status actualizado a OFFLINE | Pasó |

**Control de Casos de Prueba - Telemetry Unit Testing (US11, US12, US13)**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U78 | ReadingRangeValidator | Unitaria (xUnit) | Lectura físicamente imposible (alta) | Sensor humedad, Valor 150% | Retorna false (inválida) | Pasó |
| TC-U79 | ReadingRangeValidator | Unitaria (xUnit) | Lectura físicamente imposible (baja) | Sensor temperatura, Valor -20°C | Retorna false (inválida) | Pasó |
| TC-U80 | MovingAverageFilter | Unitaria (xUnit) | Suavizado con historial corto | Historial=[40,42], Nuevo=44 | Retorna 42 (promedio) | Pasó |
| TC-U81 | RegisterMeasurementHandler | Unitaria (xUnit) | Registro de lectura válida en ciclo de 15 min | Humedad=55%, Temp=22°C, Luz=12000 lux | Llama a AddAsync una vez, actualiza LastSeen | Pasó |
| TC-U82 | RegisterMeasurementHandler | Unitaria (xUnit) | Descarte de lectura anómala | Salto de 40% a 95% en 1 ciclo sin riego | Lectura marcada como "pendiente de validación" | Pasó |
| TC-U83 | SensorReading (Aggregate) | Unitaria (xUnit) | Cálculo de margen de error ADC | Voltaje crudo 2.45V, rango calibrado [0-3.3V] | Error de cuantización < 2% | Pasó |

**Control de Casos de Prueba - Irrigation Unit Testing (US19, US20)**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U84 | IrrigationCycle (Aggregate) | Unitaria (xUnit) | Activación manual válida | ZoneId=3, Mode=Manual | Status=InProgress, fuente=Manual | Pasó |
| TC-U85 | IrrigationCycle (Aggregate) | Unitaria (xUnit) | Vencimiento del Safety Timer | Riego manual activo > MaxManualDuration | Status=Aborted, válvula cerrada | Pasó |
| TC-U86 | IrrigationCycle (Aggregate) | Unitaria (xUnit) | Prioridad del modo manual sobre automático | Modo activo=Auto, llega orden Manual | Pausa lógica automática, ejecuta orden manual | Pasó |
| TC-U87 | IrrigationCalculator | Unitaria (xUnit) | Cálculo de volumen en modo autónomo | HumedadActual=40%, Objetivo=60% | Retorna WaterQuantity > 0 | Pasó |
| TC-U88 | IrrigationCalculator | Unitaria (xUnit) | Sin necesidad hídrica | HumedadActual=65%, Objetivo=60% | Retorna WaterQuantity = 0 | Pasó |
| TC-U89 | IrrigationCommandService | Unitaria (xUnit) | Desactivación manual del riego | Riego en curso, comando Stop | Status=Completed, válvula cerrada | Pasó |

<img src="https://imgur.com/Ti5Voe3.png">

**Control de Casos de Prueba - US22 - Gestión de registro fotográfico de cultivos**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U90 | Zone (Aggregate) | Unitaria (xUnit) | Actualización válida de URL HTTPS | imageUrl="https://..." | zone.ImageUrl == url | Pasó |
| TC-U91 | Zone (Aggregate) | Unitaria (xUnit) | Actualización válida de URL HTTP | imageUrl="http://..." | zone.ImageUrl == url | Pasó |
| TC-U92 | Zone (Aggregate) | Unitaria (xUnit) | Validación de string vacío | imageUrl="" | zone.ImageUrl == null | Pasó |
| TC-U93 | Zone (Aggregate) | Unitaria (xUnit) | Validación de espacios en blanco | imageUrl=" " | zone.ImageUrl == null | Pasó |
| TC-U94 | Zone (Aggregate) | Unitaria (xUnit) | Limpieza de espacios (Trim) | imageUrl=" https://... " | zone.ImageUrl == "https://..." | Pasó |
| TC-U95 | Zone (Aggregate) | Unitaria (xUnit) | Eliminación de imagen (null) | imageUrl=null | zone.ImageUrl == null | Pasó |

<img src="https://imgur.com/YmAmxwD.png">

**Control de Casos de Prueba - US23 - Clasificación del estado fenológico mediante Inteligencia Artificial**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U96 | AnalysisReport | Unitaria (xUnit) | Construcción válida con datos correctos | Id=1, Fase="Germinacion", Score=85 | Objeto creado con valores correctos | Pasó |
| TC-U97 | AnalysisReport | Unitaria (xUnit) | Validación de fases permitidas | Fase in ["Semilla", "Vegetativo", etc] | Fase asignada correctamente | Pasó |
| TC-U98 | AnalysisReport | Unitaria (xUnit) | Categoría cuando confianza es baja | Fase="Indeterminado", Score=50 | Asigna fase "Indeterminado" | Pasó |
| TC-U99 | AnalysisReport | Unitaria (xUnit) | Validación límite inferior score (75%) | Score=75 | Score 75 aceptado | Pasó |
| TC-U100 | AnalysisReport | Unitaria (xUnit) | Validación ZoneId inválido | ZoneId=0 | Lanza ArgumentException | Pasó |
| TC-U101 | AnalysisReport | Unitaria (xUnit) | Validación fase vacía | Fase="" | Lanza ArgumentException | Pasó |
| TC-U102 | AnalysisReport | Unitaria (xUnit) | Validación score > 100 | Score=101 | Lanza ArgumentException | Pasó |
| TC-U103 | AnalysisReport | Unitaria (xUnit) | Validación score negativo | Score=-1 | Lanza ArgumentException | Pasó |
| TC-U104 | AnalysisReport | Unitaria (xUnit) | Limpieza de espacios (Trim) | Fase=" Germinacion " | Fase asignada como "Germinacion" | Pasó |

<img src="https://imgur.com/9749IPY.png">

**Control de Casos de Prueba - US27 - Visualización del estado de servicios**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U105 | Contract | Unitaria (xUnit) | Estado inicial activo y no suspendido | Status=Active, isSuspended=false | IsSuspended=false, Status=Active | Pasó |
| TC-U106 | Contract | Unitaria (xUnit) | Suspensión de servicio por flag | isSuspended=true | IsSuspended=true | Pasó |
| TC-U107 | Contract | Unitaria (xUnit) | Cambio a estado cancelado | Status=Cancelled | Status=Cancelled | Pasó |
| TC-U108 | Contract | Unitaria (xUnit) | Verificación de fecha de inicio | Fecha creación -10 días | StartDate es correcta | Pasó |
| TC-U109 | Contract | Unitaria (xUnit) | Verificación de fecha de expiración | Fecha creación +30 días | EndDate es correcta | Pasó |
| TC-U110 | Contract | Unitaria (xUnit) | Validación de coherencia temporal | Instancia Contract | EndDate > StartDate | Pasó |
| TC-U111 | Contract | Unitaria (xUnit) | Actualización: Suspensión de servicio | Update(isSuspended=true) | IsSuspended=true | Pasó |
| TC-U112 | Contract | Unitaria (xUnit) | Actualización: Reactivación de servicio | Update(isSuspended=false) | IsSuspended=false | Pasó |
| TC-U113 | Contract | Unitaria (xUnit) | Validación: Fecha fin anterior a inicio | StartDate, EndDate (start-1) | Lanza ArgumentException | Pasó |
| TC-U114 | Contract | Unitaria (xUnit) | Verificación de límites contratados | Creación por defecto | MaxZones=5, MaxMicro=3 | Pasó |

<img src="https://imgur.com/lBYLCeV.png">

**Control de Casos de Prueba - US21 - Generación y descarga de reportes históricos**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U115 | ZoneReportData | Unitaria (xUnit) | Rango de tiempo: 7 días | Start=-7d, End=Now | PeriodStart < PeriodEnd | Pasó |
| TC-U116 | ZoneReportData | Unitaria (xUnit) | Rango de tiempo: 30 días | Start=-30d, End=Now | PeriodStart < PeriodEnd | Pasó |
| TC-U117 | ZoneReportData | Unitaria (xUnit) | Rango de tiempo: 90 días | Start=-90d, End=Now | PeriodStart < PeriodEnd | Pasó |
| TC-U118 | ZoneReportData | Unitaria (xUnit) | Rango de tiempo: 180 días | Start=-180d, End=Now | PeriodStart < PeriodEnd | Pasó |
| TC-U119 | ZoneReportData | Unitaria (xUnit) | Rango de tiempo: 365 días | Start=-365d, End=Now | PeriodStart < PeriodEnd | Pasó |
| TC-U120 | ZoneReportData | Unitaria (xUnit) | Timestamper de generación | Creación de reporte | GeneratedAtUtc cercano a Now | Pasó |
| TC-U121 | ZoneReportData | Unitaria (xUnit) | Validación conteo de lecturas | ReadingsCount=150 | Telemetry.ReadingsCount == 150 | Pasó |
| TC-U122 | ZoneReportData | Unitaria (xUnit) | Precisión de promedios | Datos estándar | Valores promedio coinciden | Pasó |
| TC-U123 | ZoneReportData | Unitaria (xUnit) | Validación conteo ciclos riego | CyclesCount=10 | Irrigation.CyclesCount == 10 | Pasó |
| TC-U124 | ZoneReportData | Unitaria (xUnit) | Validación volumen total riego | Datos estándar | Volume == 120.5 | Pasó |
| TC-U125 | ZoneReportData | Unitaria (xUnit) | Integridad de metadatos de Zona | Objeto Zone | Fields (Name, Crop, Mode) correctos | Pasó |
| TC-U126 | ZoneReportData | Unitaria (xUnit) | Integridad de metadatos de Granja | Objeto Farm | Fields (Name, Location) correctos | Pasó |
| TC-U127 | ZoneReportData | Unitaria (xUnit) | Cálculo de duración de periodo | 30 días exactos | Duration == 30 días | Pasó |

<img src="https://imgur.com/0DcCEcx.png">

**Control de Casos de Prueba - US26 - Configuración y gestión de alertas de usuario**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-U128 | User | Unitaria (xUnit) | Obtener preferencias por defecto | Usuario nuevo sin config | Retorna preferencias base | Pasó |
| TC-U129 | User | Unitaria (xUnit) | Persistir habilitación de Push | push=true, email=false | Push=true guardado | Pasó |
| TC-U130 | User | Unitaria (xUnit) | Persistir habilitación de Email | push=false, email=true | Email=true guardado | Pasó |
| TC-U131 | User | Unitaria (xUnit) | Deshabilitar todos los canales | push=false, email=false | Ambos canales false | Pasó |
| TC-U132 | User | Unitaria (xUnit) | Habilitar todos los canales | push=true, email=true | Ambos canales true | Pasó |
| TC-U133 | UserNotification | Unitaria (xUnit) | Construcción válida de notificación | Título, Mensaje, Tipo="alert" | Instancia creada, IsRead=false | Pasó |
| TC-U134 | UserNotification | Unitaria (xUnit) | Marcar como leída | Notificación nueva | IsRead=true, ReadAt fecha set | Pasó |
| TC-U135 | UserNotification | Unitaria (xUnit) | Idempotencia de marcar como leída | Llamar MarkAsRead 2 veces | ReadAt mantiene valor inicial | Pasó |
| TC-U136 | UserNotification | Unitaria (xUnit) | Validación de título requerido | Título="" | Lanza ArgumentException | Pasó |
| TC-U137 | UserNotification | Unitaria (xUnit) | Validación de ID usuario | UserId=0 | Lanza ArgumentException | Pasó |
| TC-U138 | UserNotification | Unitaria (xUnit) | Normalización de tipo (default) | Tipo=null o desconocido | Asigna tipo "info" por defecto | Pasó |

<img src="https://imgur.com/zzskkhC.png">

**Pruebas de Integración (Integration Tests)**

**Control de Casos de Prueba - General Integration Testing (Profiles, Hardware Device, Cultivation Area, Telemetry, Irrigation)**

| Test Case ID | Servicio / Flujo | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-I14 | AuthController | Integración (xUnit) | Registro exitoso con token de invitación | Body válido + InviteToken vigente | 201 Created con userId | Pasó |
| TC-I15 | AuthController | Integración (xUnit) | Registro con token expirado | InviteToken vencido | 400 Bad Request | Pasó |
| TC-I16 | MicrocontrollerController | Integración (xUnit) | Vinculación de dispositivo a zona como staff | Rol="staff", ZoneId válido | 200 OK con Microcontroller actualizado | Pasó |
| TC-I17 | MicrocontrollerController | Integración (xUnit) | Intento de vinculación por rol no autorizado | Rol="user_basic" | 403 Forbidden | Pasó |
| TC-I18 | ZoneController | Integración (xUnit) | Creación de zona dentro del límite del contrato | MaxZones=10, ZonasActuales=4 | 201 Created con Zone | Pasó |
| TC-I19 | ZoneController | Integración (xUnit) | Creación de zona excediendo el límite del contrato | MaxZones=10, ZonasActuales=10 | 409 Conflict | Pasó |
| TC-I20 | TelemetryController | Integración (xUnit) | Consulta de historial de zona | ZoneId=3, Rango últimas 24h | 200 OK con lista de SensorReading | Pasó |
| TC-I21 | IrrigationController | Integración (xUnit) | Inicio de riego manual autorizado | ZoneId=3, Rol="user_advanced" | 200 OK con cycleId | Pasó |
| TC-I22 | IrrigationController | Integración (xUnit) | Inicio de riego manual sobre zona ajena | ZoneId de otra asociación | 403 Forbidden | Pasó |

<img src="https://imgur.com/ktav5pD.png">

**Control de Casos de Prueba - US22 - Gestión de registro fotográfico de cultivos**

| Test Case ID | Componente / Clase | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-I23 | ZonesController | Integración (xUnit) | Actualización de imagen exitosa | ZoneId=1, Body con URL válida | 200 OK | Pasó |
| TC-I24 | ZonesController | Integración (xUnit) | Intento de actualizar zona inexistente | ZoneId=99999, Body válido | 404 NotFound | Pasó |
| TC-I25 | ZonesController | Integración (xUnit) | Eliminación de imagen (envío de null) | ZoneId=1, Body con ImageUrl=null | 200 OK, Comando recibe ImageUrl=null | Pasó |
| TC-I26 | ZonesController | Integración (xUnit) | Verificación de parámetros enviados al servicio | ZoneId=1, Body con URL válida | 200 OK, Comando recibe ZoneId y URL correctos | Pasó |

<img src="https://imgur.com/Ketr2yz.png">

**Control de Casos de Prueba - US23 - Clasificación del estado fenológico mediante Inteligencia Artificial**

| Test Case ID | Servicio / Flujo | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-I27 | AnalysisReportsController | Integración (xUnit) | Creación exitosa de reporte (Happy Path) | ZoneId=1, Body {Phase, Score} | 201 Created | Pasó |
| TC-I28 | AnalysisReportsController | Integración (xUnit) | Validación de cuerpo de respuesta en creación | ZoneId=1, Body válido | 201 Created con objeto AnalysisReport no nulo | Pasó |
| TC-I29 | AnalysisReportsController | Integración (xUnit) | Procesamiento de reporte con baja confianza | ZoneId=1, Body {"Indeterminado", 50f} | 201 Created | Pasó |
| TC-I30 | AnalysisReportsController | Integración (xUnit) | Fallo por zona inexistente | ZoneId=99999, Body válido | 404 Not Found | Pasó |
| TC-I31 | AnalysisReportsController | Integración (xUnit) | Verificación de delegación correcta al servicio | ZoneId=1, Body {"Floracion", 90f} | Servicio recibe los parámetros exactos | Pasó |

<img src="https://imgur.com/SiF2l6T.png">

**Control de Casos de Prueba - US27 - Visualización del estado de servicios**

| Test Case ID | Servicio / Flujo | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-I32 | ContractsController | Integración (xUnit) | Obtención exitosa (UserAdmin) | role="user_admin", asociación válida | 200 OK con contratos filtrados | Pasó |
| TC-I33 | ContractsController | Integración (xUnit) | Visualización estado activo | Contrato isSuspended=false | 200 OK, objeto con estado activo | Pasó |
| TC-I34 | ContractsController | Integración (xUnit) | Visualización estado suspendido | Contrato isSuspended=true | 200 OK, objeto con estado suspendido | Pasó |
| TC-I35 | ContractsController | Integración (xUnit) | Consulta con asociación sin contratos | List devuelve lista vacía | 200 OK, lista vacía | Pasó |
| TC-I36 | ContractsController | Integración (xUnit) | Consulta con rol Admin global | role="admin" | 200 OK, todos los contratos existentes | Pasó |
| TC-I37 | ContractsController | Integración (xUnit) | Validación de seguridad (sin Auth) | ClaimsPrincipal vacío | 401 Unauthorized | Pasó |

<img src="https://imgur.com/vQf62jY.png">

**Control de Casos de Prueba - US21 - Generación y descarga de reportes históricos**

| Test Case ID | Servicio / Flujo | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-I38 | ZoneReportsController | Integración (xUnit) | Resumen de métricas exitoso | ZoneId=1, Rango 30 días | 200 OK | Pasó |
| TC-I39 | ZoneReportsController | Integración (xUnit) | Rango de 7 días | ZoneId=1, Rango 7 días | 200 OK | Pasó |
| TC-I40 | ZoneReportsController | Integración (xUnit) | Rango de 90 días | ZoneId=1, Rango 90 días | 200 OK | Pasó |
| TC-I41 | ZoneReportsController | Integración (xUnit) | Rango de 365 días | ZoneId=1, Rango 365 días | 200 OK | Pasó |
| TC-I42 | ZoneReportsController | Integración (xUnit) | Zona inexistente en resumen | ZoneId=99999, Rango=30 | 404 Not Found | Pasó |
| TC-I43 | ZoneReportsController | Integración (xUnit) | Reporte nulo/indisponible | ZoneId=1, Configuración vacía | 404 Not Found | Pasó |
| TC-I44 | ZoneReportsController | Integración (xUnit) | Exportación PDF exitosa | ZoneId=1, Rango=30 | 200 OK, FileContentResult | Pasó |
| TC-I45 | ZoneReportsController | Integración (xUnit) | Validación de tipo MIME (PDF) | ZoneId=1, Rango=30 | ContentType = "application/pdf" | Pasó |
| TC-I46 | ZoneReportsController | Integración (xUnit) | Exportación en zona inexistente | ZoneId=99999 | 404 Not Found | Pasó |

<img src="https://imgur.com/psSgxCM.png">

**Control de Casos de Prueba - US26 - Configuración y gestión de alertas de usuario**

| Test Case ID | Servicio / Flujo | Tipo de Prueba | Descripción del Escenario | Datos de Entrada (Input) | Resultado Esperado (Output) | Estado |
|----|----|----|----|----|----|----|
| TC-I47 | UserProfileController | Integración (xUnit) | Habilitación exitosa de notif. Push | Body {Push: true, Email: false} | 200 OK | Pasó |
| TC-I48 | UserProfileController | Integración (xUnit) | Habilitación exitosa de Email | Body {Push: false, Email: true} | 200 OK | Pasó |
| TC-I49 | UserProfileController | Integración (xUnit) | Deshabilitación total de alertas | Body {Push: false, Email: false} | 200 OK | Pasó |
| TC-I50 | UserProfileController | Integración (xUnit) | Validación de integridad de datos enviados | Body {Push: true, Email: true} | Comando UpdateUserPreferences con data correcta | Pasó |
| TC-I51 | UserProfileController | Integración (xUnit) | Manejo de usuario no encontrado | UserId=1 (inexistente) | 404 Not Found | Pasó |
| TC-I52 | UserProfileController | Integración (xUnit) | Listado exitoso de notificaciones | Contexto de usuario autenticado | 200 OK con lista de UserNotification | Pasó |

<img src="https://imgur.com/A8c52uX.png">

**Pruebas de Aceptación bajo enfoque BDD (Acceptance Tests)**

**Control de Casos de Prueba - General Acceptance Testing / BDD (Profiles, Hardware Device, Cultivation Area, Telemetry, Irrigation)**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario (Gherkin) | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A19 | US25 (Sc1) | Aceptación (BDD) | Registro exitoso mediante enlace de invitación | Token vigente, datos completos | Cuenta creada y UserRegistered publicado | Pasó |
| TC-A21 | US10 (Sc1) | Aceptación (BDD) | Vinculación exitosa de microcontrolador | ID único de dispositivo válido | Dispositivo mostrado como "Activo" en el perfil | Pasó |
| TC-A22 | US10 (Sc4) | Aceptación (BDD) | Vinculación con ID inexistente | DeviceId no registrado en manufactura | Mensaje de error, sin vinculación | Pasó |
| TC-A23 | US15 (Sc1) | Aceptación (BDD) | Creación de zona | Nombre="Invernadero 1" | Zona creada y visible en el panel | Pasó |
| TC-A24 | US15 (Sc2) | Aceptación (BDD) | Asignación de hardware a zona y cultivo | Microcontrolador + CropId="Zanahoria" | Hardware asociado a la zona y cultivo | Pasó |
| TC-A25 | US11 (Sc1) | Aceptación (BDD) | Reflejo inmediato de cambio físico | Cambio de humedad real detectado | Dashboard actualiza el valor en pantalla | Pasó |
| TC-A26 | US12 (Sc1) | Aceptación (BDD) | Ejecución del ciclo de lectura cada 15 min | Timer interno alcanza 15 min | Sensores capturan y envían datos a la nube | Pasó |
| TC-A27 | US13 (Sc4) | Aceptación (BDD) | Detección de inconsistencia física | Salto de 40% a 90% sin riego activo | Lectura marcada "pendiente de validación" | Pasó |
| TC-A28 | US19 (Sc1) | Aceptación (BDD) | Activación remota del riego manual | Usuario activa riego desde la app | Válvula abierta, estado "en curso" | Pasó |
| TC-A29 | US20 (Sc1) | Aceptación (BDD) | Activación autónoma por necesidad hídrica | Sensores indican déficit de humedad | Válvula abierta sin intervención del usuario | Pasó |

<img src="https://imgur.com/ZSWPKTm.png">

**Control de Casos de Prueba - US22 - Gestión de registro fotográfico de cultivos**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A30 | US22 (Sc1) | Aceptación (BDD) | Registrar URL en zona nueva | Zona ID=1, URL válida | 200 OK, imagen persiste | Pasó |
| TC-A31 | US22 (Sc2) | Aceptación (BDD) | Actualizar URL de imagen existente | Zona ID=1, Nueva URL válida | 200 OK, URL actualizada | Pasó |
| TC-A32 | US22 (Sc3) | Aceptación (BDD) | Manejo de URL vacía (Remoción) | Zona ID=1, URL vacía ("") | 200 OK, imagen registrada como null | Pasó |
| TC-A33 | US22 (Sc4) | Aceptación (BDD) | Error al actualizar zona inexistente | Zona ID=99999, URL válida | 404 Not Found | Pasó |

<img src="https://imgur.com/XpaMoKy.png">

**Control de Casos de Prueba - US23 - Clasificación del estado fenológico mediante Inteligencia Artificial**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A34 | US23 (Sc1) | Aceptación (BDD) | Categorización exitosa de estado | Fase="Germinacion", Score=85 | 201 Created, fase detectada correcta | Pasó |
| TC-A35 | US23 (Sc2) | Aceptación (BDD) | Resultado con baja confianza | Fase="Indeterminado", Score=50 | 201 Created, fase "Indeterminado" persistida | Pasó |
| TC-A36 | US23 (Sc3) | Aceptación (BDD) | Validación de zona inexistente | ZoneId=99999, Fase="Germinacion" | 404 Not Found | Pasó |

<img src="https://imgur.com/HZiHpd8.png">

**Control de Casos de Prueba - US27 - Visualización del estado de servicios**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A37 | US28 (Sc1) | Aceptación (BDD) | Servicio activo y habilitado | Contrato activo (no suspendido), usuario admin | 200 OK, estado 'Active' | Pasó |
| TC-A38 | US28 (Sc3) | Aceptación (BDD) | Servicio con contrato suspendido | Contrato suspendido, usuario admin | 200 OK, estado 'Suspended' | Pasó |
| TC-A39 | US28 (Sc2) | Aceptación (BDD) | Asociación sin contrato activo | Lista de contratos vacía | 200 OK, lista de contratos vacía | Pasó |

<img src="https://imgur.com/ICs7qwt.png">

**Control de Casos de Prueba - US21 - Generación y descarga de reportes históricos**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A40 | US21 (Sc1) | Aceptación (BDD) | Generación reporte semanal | ZoneId=1, Rango=7 días | 200 OK, datos del periodo | Pasó |
| TC-A41 | US21 (Sc1) | Aceptación (BDD) | Generación reporte mensual | ZoneId=1, Rango=30 días | 200 OK, datos del periodo | Pasó |
| TC-A42 | US21 (Sc1) | Aceptación (BDD) | Generación reporte trimestral | ZoneId=1, Rango=90 días | 200 OK, datos del periodo | Pasó |
| TC-A43 | US21 (Sc2) | Aceptación (BDD) | Vista previa de métricas | ZoneId=1, Rango=30 días | 200 OK, telemetría e irrigación | Pasó |
| TC-A44 | US21 (Sc3) | Aceptación (BDD) | Exportación a archivo PDF | ZoneId=1, Rango=30 días | 200 OK, retorno archivo PDF | Pasó |
| TC-A45 | US21 (Err) | Aceptación (BDD) | Zona inexistente en reporte | ZoneId=99999 | 404 Not Found | Pasó |

<img src="https://imgur.com/VTSnbfr.png">

**Control de Casos de Prueba - US26 - Configuración y gestión de alertas de usuario**

| Test Case ID | ID Historia | Tipo de Prueba | Descripción del Escenario | Acción / Input | Resultado Esperado | Estado |
|----|----|----|----|----|----|----|
| TC-A45 | US26 (Sc1) | Aceptación (BDD) | Activar push y desactivar email | Push: true, Email: false | 200 OK | Pasó |
| TC-A46 | US26 (Sc2) | Aceptación (BDD) | Desactivar todos los canales | Push: false, Email: false | 200 OK | Pasó |
| TC-A47 | US26 (Sc3) | Aceptación (BDD) | Activar todos los canales | Push: true, Email: true | 200 OK | Pasó |
| TC-A48 | US26 (Sc4) | Aceptación (BDD) | Persistencia y validación de comando | Push: true, Email: true | 200 OK, Comando enviado con valores correctos | Pasó |

<img src="https://imgur.com/Suqu1II.png">

#### 6.2.3.6. Execution Evidence for Sprint Review

**Aplicación Web:**

Durante este sprint, se priorizó el fortalecimiento de la capa de identidad y la administración centralizada de la plataforma. Se implementó un módulo robusto de gestión de identidades, integrando un flujo de registro controlado mediante enlaces de invitación generados exclusivamente por el personal administrativo de la asociación, lo cual garantiza un *onboarding* seguro, validado y bajo supervisión. Complementariamente, se desarrolló la infraestructura funcional para que el personal de la plataforma pueda crear, configurar y organizar las zonas de cultivo directamente desde la aplicación web, centralizando la configuración del entorno agrícola y fortaleciendo la gobernanza sobre los datos del usuario.

En paralelo, se habilitó la funcionalidad de vinculación lógica entre los dispositivos físicos (microcontroladores) y las zonas geográficas definidas, permitiendo una configuración ágil de la red de sensores desde la interfaz web. Esta nueva capa de administración facilita significativamente la escalabilidad de la solución, al permitir al equipo configurar diversos tipos de plantas y entornos de manera simultánea y ordenada. Con estas implementaciones, Grotix consolida un ecosistema de gestión integral que articula eficazmente la identidad del usuario, la organización del terreno y la conectividad del hardware, resultando en una plataforma más operativa, profesional y preparada para la automatización agrícola.

Pantalla de Devices:

<img src="https://imgur.com/mBd624T.png">

Datos del Device:

<img src="https://imgur.com/1Pv10RJ.png">

Datos de Sensores y Actuadores:

<img src="https://imgur.com/fJQs1EF.png">

Datos de Cultivation Zone para cada Asociación:

<img src="https://imgur.com/V2WI1vL.png">

Generación de Link de Registro:

<img src="https://imgur.com/9ZVaL7d.png">

Registro de Agricultor:

<img src="https://imgur.com/zvUHups.png">

**Aplicación Móvil**

Se concretó la implementación integral de la aplicación, alcanzando un estado de madurez funcional. En este ciclo se integró la visualización dinámica de zonas de cultivo y la monitorización de umbrales tras el procesamiento de datos de los sensores. Asimismo, se habilitaron los flujos completos de riego manual y automático, se perfeccionó la configuración personalizada de umbrales por parte del usuario, y se integró el módulo de diagnóstico fenológico mediante IA. Finalmente, se optimizó la sección de perfil con la visualización de contratos y se implementó el motor de generación de reportes históricos, permitiendo al usuario auditar lecturas y ciclos de riego sobre periodos específicos.

Dashboard por zona:

<img src="https://imgur.com/zxShuL9.png">

Sección de análisis con IA:

<img src="https://imgur.com/97E9ejN.png">

Score de una planta:

<img src="https://imgur.com/MEsmHfK.png">

Detalle de zona:

<img src="https://imgur.com/oFkKrqP.png">

Edición de zona:

<img src="https://imgur.com/2iHW90o.png">

Generación de Reportes:

<img src="https://imgur.com/oDnZNDn.png">

Reporte de Zona:

<img src="https://imgur.com/0TwiPaF.png">

Perfil de usuario:

<img src="https://imgur.com/lDh9cBs.png">

Plan del usuario:

<img src="https://imgur.com/WQlcgcD.png">

Ventana de notificaciones:

<img src="https://imgur.com/UBaQ4kh.png">

**Edge App**

Se desarrolló e integró la Edge App, la cual ha sido optimizada para actuar como un puente de alta disponibilidad entre la infraestructura física y la nube. En este sprint, se implementó y validó exitosamente un motor de persistencia local basado en SQLite, permitiendo que la lógica de negocio, la gestión de umbrales y la activación de riego autónomo se ejecuten de manera independiente, garantizando la continuidad operativa ante escenarios de conectividad intermitente.

<img src="https://imgur.com/k5xttNA.png">

**Implementación de Hardware**

Se completó el despliegue del nodo IoT central basado en ESP32 (38 pines), integrando y calibrando exitosamente el conjunto de sensores (DHT22 para ambiente, sensor de luz analógico y sensor capacitivo de humedad de suelo). En este periodo, se finalizó la integración física del actuador de riego, implementando el relé de 5V y la bomba de agua con su módulo de alimentación dedicado, verificando que la lógica embebida gestione correctamente las señales de potencia y asegure la estabilidad eléctrica del nodo ante los disparos de riego.

<img src="https://imgur.com/S59QP3V.png">

Repositorio con el código Embebido: https://github.com/CeleviGrotix/Grotix_Embedded

<img src="https://imgur.com/nWPV0bs.png">

Video explicativo:

[Execution EvidenceIoT.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQBqqDaRVN_WTI7RI66FiEDMAVw31SzkDuJa26C5sPOLgR0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=xeDbE9)

#### 6.2.3.7. Services Documentation Evidence for Sprint Review

La documentación de microservicios presenta la evolución técnica de Grotix a lo largo del Sprint 3 consolidando la integración operativa entre dispositivos IoT y la plataforma en la nube mediante un ecosistema de servicios RESTful documentados íntegramente bajo el estándar OpenAPI/Swagger. Este conjunto de evidencias detalla la implementación de endpoints robustos que habilitan desde la gestión crítica de hardware, telemetría en tiempo real y orquestación de riego autónomo, hasta funcionalidades avanzadas como el diagnóstico fenológico asistido por inteligencia artificial, la persistencia offline en la capa edge, la generación de reportes históricos y la gestión de alertas y contratos de usuario; un despliegue coordinado entre los microservicios CultivationArea.Api, Telemetry.Api, IrrigationCycle.Api, Profiles.Api y el servidor de procesamiento de IA que, a través de estos contratos de interfaz, garantiza la trazabilidad, desacoplamiento y consistencia operativa requerida para la arquitectura de Grotix.

| Microservicio | Método | Ruta (relativa al host) | Autorización | Parámetros / cuerpo | Respuesta (éxito y notas) |
|----|----|----|----|----|----|
| Cultivation.Api | PATCH | /api/v1/zones/{id} | Bearer JWT | JSON parcial: name, cropId, irrigationMode, etc. | 200 OK. Zona actualizada. [Modificado: irrigationMode] |
| Cultivation.Api | POST | /api/v1/farms/{farmId}/zones | Bearer JWT | JSON: name, cropId, coords, irrigationMode? | 201 Created. Nueva zona con modo de riego. [Modificado] |
| Cultivation.Api | GET | /api/v1/zones/{zoneId}/members | Bearer JWT | Path: zoneId. | 200 OK. Personal asignado a la zona. [Nuevo] |
| Cultivation.Api | POST | /api/v1/zones/{zoneId}/members | user_admin / admin / staff | JSON: { userId }. | 200 OK. { success: true }. [Nuevo] |
| Cultivation.Api | DELETE | /api/v1/zones/{zoneId}/members/{userId} | user_admin / admin / staff | Path: zoneId, userId. | 200 OK. Quita asignación a la zona. [Nuevo] |
| CultivationArea.Api | PATCH | /api/v1/zones/{zoneId} | Bearer JWT | JSON parcial: imageUrl | 200 OK. Zona con imageUrl actualizada. [US22] |
| CultivationArea.Api | POST | /api/v1/zones/{zoneId}/analysis-reports | Bearer JWT / user_admin+ | JSON: detectedPhase, healthScore | 201 Created. Reporte de diagnóstico IA. [US23, Nuevo] |
| CultivationArea.Api | GET | /api/v1/zones/{zoneId}/analysis-reports | Bearer JWT | Path: zoneId. Query: limit? | 200 OK. Lista de diagnósticos IA. [US23, Nuevo] |
| CultivationArea.Api | GET | /api/v1/zones/{zoneId}/reports/summary | Bearer JWT | Path: zoneId. Query: from?, to? | 200 OK. Resumen JSON del reporte. [US21, Nuevo] |
| CultivationArea.Api | GET | /api/v1/zones/{zoneId}/reports/export | Bearer JWT | Path: zoneId. Query: from?, to? | 200 OK. Archivo PDF binario. [US21, Nuevo] |
| Hardware.Api | GET | /api/v1/hardware/sensors/catalog | DEVICE_CONFIG / admin | — | 200 OK. Catálogo de modelos y tipos de sensor. [Nuevo] |
| Hardware.Api | POST | /api/v1/hardware/devices/{id}/link-to-zone/{zoneId} | DEVICE_CONFIG / admin | Path: id, zoneId. | 200 OK. Vincula ESP32 a zona. [Validado Sprint 3] |
| Hardware.Api | GET | /api/v1/hardware/zones/{zoneId}/health | Bearer JWT | Path: zoneId. | 200 OK. Salud de dispositivos con isActive por lastSeen. [Modificado] |
| Hardware.Api | PATCH | /api/v1/hardware/devices/{id}/status | DEVICE_CONFIG / admin | JSON: status, lastSeen?. | 200 OK. Actualiza estado operacional. [Modificado] |
| Telemetry.Api | POST | /api/v1/telemetry/ingest | DEVICE_CONFIG / admin | JSON: deviceId, zoneId, lecturas. | 202 Accepted. Persiste telemetría y refresca lastSeen. [Modificado] |
| Telemetry.Api | GET | /api/v1/telemetry/zones/{zoneId}/thresholds | Bearer JWT | Path: zoneId | 200 OK. Umbrales efectivos por sensor. [US17, Usado por Edge] |
| Irrigation.Api | POST | /api/v1/irrigation/start/{zoneId} | MANUAL_CONTROL_EXECUTE / admin | JSON: volumeLiters?, durationMinutes?. | 200 OK. { cycleId }. Riego manual (US19). [Integrado Sprint 3] |
| Irrigation.Api | POST | /api/v1/irrigation/stop/{zoneId} | MANUAL_CONTROL_EXECUTE / admin | JSON: reason?. | 200 OK. Ciclo ABORTED. [Integrado Sprint 3] |
| Irrigation.Api | GET | /api/v1/irrigation/active | Bearer JWT | Query: zoneId? | 200 OK. Ciclos activos de riego. [US17, Usado por Edge] |
| Profiles.Api | GET | /api/v1/contracts | Bearer JWT / user_admin+ | — | 200 OK. Contratos de la asociación. [US27] |
| Profiles.Api | PATCH | /api/v1/profile/{userId}/preferences | Bearer JWT | JSON: push, email | 200 OK. Preferencias actualizadas. [US26, Nuevo] |
| Profiles.Api | GET | /api/v1/profile/me/notifications | Bearer JWT | Query: unreadOnly?, limit? | 200 OK. Lista de notificaciones. [US26, Nuevo] |
| Profiles.Api | PATCH | /api/v1/profile/me/notifications/{id}/read | Bearer JWT | Path: notificationId | 200 OK. { success: true }. [US26, Nuevo] |
| Profiles.Api | PATCH | /api/v1/profile/me/notifications/read-all | Bearer JWT | — | 200 OK. { success: true, updated }. [US26, Nuevo] |

**Evidencias de Validación Funcional**

**PATCH /api/v1/zones/{zoneId}**

Actualiza datos de una zona de cultivo. En Sprint 3 se incorporó el campo irrigationMode (MANUAL \| AUTOMATIC) para controlar si la zona permite riego manual desde la app y si los automatismos (programación y alertas) deben ejecutarse. Valores inválidos devuelven 400.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción    |
|-------------------|-----------------|--------------------|
| Content-Type      | String          | application/json   |
| Authorization     | String          | Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId (integer).

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "name": "Parcela Norte",
    "irrigationMode": "MANUAL"
}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| id | Integer | Identificador de la zona. |
| farmId | Integer | Granja contenedora. |
| cropId | Integer | Cultivo asociado. |
| name | String | Nombre visible de la zona. |
| irrigationMode | String | MANUAL o AUTOMATIC. [Nuevo en respuesta editable] |
| currentPhase | String? | Fase fenológica actual. |
| latitude / longitude | Double | Coordenadas geográficas. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "id": 12,
    "farmId": 3,
    "cropId": 1,
    "name": "Parcela Norte",
    "irrigationMode": "MANUAL",
    "currentPhase": "Floración",
    "phaseStartDate": "2026-06-01T00:00:00Z",
    "imageUrl": null,
    "latitude": -13.52,
    "longitude": -71.97
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "message": "Modo de riego inválido. Valores: AUTOMATIC, MANUAL."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/ST1azh0.png">

**POST /api/v1/farms/{farmId}/zones**

Crea una zona dentro de una granja. Sprint 3 permite definir irrigationMode al crear la parcela (por defecto AUTOMATIC si se omite). Usado por el módulo web de creación de zonas (US15).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción    |
|-------------------|-----------------|--------------------|
| Content-Type      | String          | application/json   |
| Authorization     | String          | Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: farmId (integer).

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "name": "Lote B",
    "cropId": 2,
    "latitude": -13.51,
    "longitude": -71.96,
    "currentPhase": "Germinación",
    "irrigationMode": "AUTOMATIC"
}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 201 Created**

| Campo (Field) | Tipo (Type) | Descripción             |
|-------------------|-----------------|-----------------------------|
| id                | Integer         | ID autogenerado de la zona. |
| irrigationMode    | String          | Modo de riego persistido.   |
| name              | String          | Nombre de la zona.          |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "id": 18,
    "farmId": 3,
    "cropId": 2,
    "name": "Lote B",
    "irrigationMode": "AUTOMATIC",
    "currentPhase": "Germinación",
    "phaseStartDate": null,
    "imageUrl": null,
    "latitude": -13.51,
    "longitude": -71.96
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "No tienes acceso a esta granja."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/z7Oisc7.png">

**GET /api/v1/zones/{zoneId}/members**

Lista el personal asignado a una zona. Cualquier miembro con acceso a la zona puede consultar la lista. Soporta la organización de equipos por parcela (US15).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción    |
|-------------------|-----------------|--------------------|
| Authorization     | String          | Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId. Sin cuerpo.

**C. Ejemplo de Petición (Request-Example)**

```http
GET /api/v1/zones/12/members HTTP/1.1
Host: localhost:5102
Authorization: Bearer {token}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción                    |
|-------------------|-----------------|------------------------------------|
| userId            | Integer         | ID del perfil de usuario.          |
| name              | String?         | Nombre completo.                   |
| email             | String          | Correo del miembro.                |
| roleId            | Integer         | Rol de negocio.                    |
| roleName          | String          | Nombre del rol (ej. user_basic).   |
| assignedAt        | DateTime        | Fecha de asignación a la zona.     |
| assignedByUserId  | Integer?        | Usuario que realizó la asignación. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
[
    {
        "userId": 23,
        "name": "Carlos Mamani",
        "email": "c.mamani@grotix.pe",
        "roleId": 4,
        "roleName": "user_basic",
        "assignedAt": "2026-06-15T10:00:00Z",
        "assignedByUserId": 5
    }
]
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "message": "No tienes acceso a esta zona."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/ZCoqFmk.png">

**POST /api/v1/zones/{zoneId}/analysis-reports**

Persiste el resultado del diagnóstico fenológico generado por la Inteligencia Artificial para una zona de cultivo. Es invocado por la app móvil inmediatamente después de recibir la respuesta del servidor Python de IA, guardando la fase detectada y la puntuación de salud en la base de datos (US23).

**A. Cabeceras (Headers)**

| Campo | Tipo | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Bearer {jwt_token}. Requiere user_admin, admin o staff. |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId (integer).

**C. Ejemplo de Petición (Request-Example)**

{

"detectedPhase": "Germinacion",

"healthScore": 85.0

}

**RESPUESTAS DEL SERVIDOR (RESPONSES)**


**Éxito: Código 201 Created**

| Campo     | Tipo | Descripción                     |
|---------------|----------|-------------------------------------|
| reportId      | Integer  | ID del reporte generado             |
| zoneId        | Integer  | Zona analizada                      |
| detectedPhase | String   | Fase fenológica detectada por la IA |
| healthScore   | Float    | Puntuación de salud (0–100)         |
| createdAt     | DateTime | Fecha y hora del diagnóstico        |

**Ejemplo de Respuesta Exitosa (Success-Example)**

{

"reportId": 45,

"zoneId": 12,

"detectedPhase": "Germinacion",

"healthScore": 85.0,

"createdAt": "2026-06-28T14:30:00Z"

}

**Error: Código 400 Bad Request**

{

"message": "HealthScore debe estar entre 0 y 100."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/yGi05T8.png">
<img src="https://imgur.com/SgWt6Oe.png">

**GET /api/v1/zones/{zoneId}/analysis-reports**

Devuelve el historial de diagnósticos IA para una zona, ordenados del más reciente al más antiguo. Permite al usuario revisar la evolución fenológica del cultivo a lo largo del tiempo (US23).

**A. Cabeceras (Headers)**

| Campo     | Tipo | Descripción    |
|---------------|----------|--------------------|
| Authorization | String   | Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId (integer). Query: limit (integer, default 50, máx 200).

**C. Ejemplo de Petición (Request-Example)**

GET /api/v1/zones/12/analysis-reports?limit=10 HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK — array de reportes.**

| Campo     | Tipo | Descripción       |
|---------------|----------|-----------------------|
| reportId      | Integer  | ID del reporte        |
| detectedPhase | String   | Fase detectada        |
| healthScore   | Float    | Puntuación de salud   |
| createdAt     | DateTime | Fecha del diagnóstico |

**Ejemplo de Respuesta Exitosa**

[

{

"reportId": 45,

"zoneId": 12,

"detectedPhase": "Germinacion",

"healthScore": 85.0,

"createdAt": "2026-06-28T14:30:00Z"

},

{

"reportId": 44,

"zoneId": 12,

"detectedPhase": "Indeterminado",

"healthScore": 50.0,

"createdAt": "2026-06-27T09:15:00Z"

}

]

**Error: Código 404 Not Found**

{

"message": "Zone not found."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/b2agV2q.png">

<img src="https://imgur.com/UZGyQP4.png">

**GET /api/v1/telemetry/zones/{zoneId}/thresholds**

Devuelve los umbrales efectivos de todos los sensores para una zona, resolviendo la prioridad entre umbrales personalizados (custom) y defaults del cultivo (crop). Es consumido por la capa edge al arrancar y periódicamente para mantener los umbrales sincronizados en SQLite local, garantizando el riego offline cuando se pierde la conexión (US17).

**A. Cabeceras**

| Campo     | Tipo | Descripción    |
|---------------|----------|--------------------|
| Authorization | String   | Bearer {jwt_token} |

**B. Parámetros de Búsqueda**

Path: zoneId (integer).

**C. Ejemplo de Petición**

GET /api/v1/telemetry/zones/5/thresholds HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK — array de umbrales por tipo de sensor.**

| Campo  | Tipo | Descripción                                       |
|------------|----------|-------------------------------------------------------|
| sensorType | String   | Tipo de sensor (SOIL_MOISTURE, AIR_TEMPERATURE, etc.) |
| minValue   | Double   | Umbral mínimo efectivo                                |
| maxValue   | Double   | Umbral máximo efectivo                                |
| source     | String   | Origen del umbral: "custom" o "crop"                  |

**Ejemplo de Respuesta Exitosa**

[

{

"sensorType": "SOIL_MOISTURE",

"minValue": 32,

"maxValue": 52,

"source": "custom"

},

{

"sensorType": "AIR_TEMPERATURE",

"minValue": 22,

"maxValue": 23,

"source": "custom"

}

]

**Error: Código 404 Not Found**

{

"status": 403,

"message": "Forbidden."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/bV6KABz.png">

<img src="https://imgur.com/uTZWGU5.png">

**POST /api/v1/hardware/devices/{id}/link-to-zone/{zoneId}**

Vincula un microcontrolador (ESP32) registrado por MAC Address a una zona específica. Endpoint central del flujo de vinculación implementado en la Web App por el staff (T86–T87).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Bearer {jwt_token}. Requiere DEVICE_CONFIG o admin. |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: id (deviceId), zoneId.

**C. Ejemplo de Petición (Request-Example)**

```http
POST /api/v1/hardware/devices/7/link-to-zone/12 HTTP/1.1
Authorization: Bearer {token}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| success | Boolean | true si la vinculación se aplicó correctamente. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "success": true
}
```

**Error: Código 404 Not Found**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "message": "Dispositivo o zona no encontrados."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/j90191j.png">

<img src="https://imgur.com/xFIO4Tv.png">

**GET /api/v1/hardware/zones/{zoneId}/health**

Consulta la salud agregada de los dispositivos de una zona. Sprint 3 incorpora isActive calculado a partir de lastSeen y un job en background que marca OFFLINE dispositivos sin telemetría reciente (umbral configurable, por defecto 60 min).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción    |
|-------------------|-----------------|--------------------|
| Authorization     | String          | Bearer {jwt_token} |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId.

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| zoneId | Integer | Zona consultada. |
| allActive | Boolean | true si todos los dispositivos están activos. |
| totalDevices | Integer | Cantidad de dispositivos en la zona. |
| devices[].deviceId | Integer | ID del microcontrolador. |
| devices[].status | String | ONLINE \| OFFLINE \| MAINTENANCE. |
| devices[].lastSeen | DateTime? | Última trama recibida. [Clave Sprint 3] |
| devices[].isActive | Boolean | Derivado de lastSeen vs umbral. [Nuevo] |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "zoneId": 12,
    "allActive": false,
    "totalDevices": 2,
    "devices": [
        {
            "deviceId": 7,
            "model": "ESP32-WROOM",
            "status": "ONLINE",
            "lastSeen": "2026-06-19T18:45:00Z",
            "isActive": true
        },
    {
        "deviceId": 8,
        "model": "ESP32-WROOM",
        "status": "OFFLINE",
        "lastSeen": "2026-06-19T16:00:00Z",
        "isActive": false
    }
]
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "NOT_AUTHORIZED: Sin acceso a la zona solicitada."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/BUsv2Rw.png">

<img src="https://imgur.com/qR9oJs7.png">

**POST /api/v1/telemetry/ingest**

Ingesta un paquete de telemetría desde el ESP32 (temperatura, humedad aire/suelo, luz). Además de persistir lecturas en TimescaleDB, actualiza lastSeen del dispositivo y lo marca ONLINE, alimentando el monitoreo periódico de la app móvil (US12).

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Bearer {jwt_token}. DEVICE_CONFIG o admin. |

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "deviceId": 7,
    "zoneId": 12,
    "temperature": 24.5,
    "humidityAir": 62.0,
    "humiditySoil": 41.0,
    "lightIntensity": 850.0,
    "timestamp": "2026-06-19T18:45:00Z"
}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 202 Accepted**

| Campo (Field) | Tipo (Type) | Descripción                |
|-------------------|-----------------|--------------------------------|
| deviceId          | Integer         | Dispositivo origen.            |
| zoneId            | Integer         | Zona destino.                  |
| ingested          | Boolean         | Confirmación de procesamiento. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "deviceId": 7,
    "zoneId": 12,
    "ingested": true
}
```

**Error: Código 400 Bad Request**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "message": "DeviceId inválido."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/hGEMVe8.png">

<img src="https://imgur.com/iLOEKxj.png">

**POST /api/v1/irrigation/start/{zoneId}**

Inicia un ciclo de riego manual para la zona indicada. Consumido por la app móvil para encender la bomba bajo demanda. Si ya existe un ciclo IN_PROGRESS en la zona, responde 409.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Bearer {jwt_token}. Permiso MANUAL_CONTROL_EXECUTE. |

**B. Parámetros de Búsqueda (Query Parameters)**

Path: zoneId. Body opcional.

**C. Ejemplo de Petición (Request-Example)**

```json
{
    "volumeLiters": 30.0,
    "durationMinutes": 10
}
```

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción                          |
|-------------------|-----------------|------------------------------------------|
| cycleId           | Integer         | Identificador del ciclo de riego creado. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "cycleId": 104
}
```

**Error: Código 409 Conflict**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "message": "Ya existe un ciclo de riego activo en esta zona."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/Cy516AG.png">

<img src="https://imgur.com/XYGMsbV.png">

**GET /api/v1/hardware/sensors/catalog**

Expone el catálogo de modelos de sensores soportados (p. ej. DHT22, capacitive soil) con los tipos de lectura permitidos por pin. Usado al registrar sensores en el inventario de hardware.

**A. Cabeceras (Headers)**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| Authorization | String | Bearer {jwt_token}. DEVICE_CONFIG o admin. |

**B. Parámetros de Búsqueda (Query Parameters)**

Sin parámetros.

**RESPUESTAS DEL SERVIDOR (RESPONSES)**

**Éxito: Código 200 OK**

| Campo (Field) | Tipo (Type) | Descripción |
|----|----|----|
| models[].model | String | Código del modelo de sensor. |
| models[].types | String[] | Tipos de lectura soportados. |
| models[].allowsMultipleTypesOnSamePin | Boolean | Si admite múltiples tipos en un pin. |

**Ejemplo de Respuesta Exitosa (Success-Example)**

```json
{
    "models": [
        {
            "model": "DHT22",
            "types": ["TEMPERATURE", "HUMIDITY_AIR"],
            "allowsMultipleTypesOnSamePin": true
        },
    {
        "model": "CAP_SOIL_V1",
        "types": ["HUMIDITY_SOIL"],
        "allowsMultipleTypesOnSamePin": false
    }
]
}
```

**Error: Código 403 Forbidden**

**Ejemplo de Respuesta de Error (Error-Response)**

```json
{
    "status": 403,
    "message": "NOT_AUTHORIZED: Permiso DEVICE_CONFIG requerido."
}
```

**D. Evidencia en Swagger**

<img src="https://imgur.com/tpJipV2.png">

<img src="https://imgur.com/7BNXfjN.png">

**GET /api/v1/contracts**

Devuelve la lista de contratos comerciales de la asociación del usuario autenticado. La app móvil consume este endpoint para mostrar el estado del servicio (activo o suspendido), las fechas de vigencia de la campaña y los límites contratados de zonas y microcontroladores (US27).

**A. Cabeceras**

| Campo | Tipo | Descripción |
|----|----|----|
| Authorization | String | Bearer {jwt_token}. Requiere user_admin, admin o staff. |

**B. Parámetros de Búsqueda**

Sin parámetros. Filtra automáticamente por la asociación del caller.

**C. Ejemplo de Petición**

GET /api/v1/contracts HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK**

| Campo           | Tipo | Descripción                     |
|---------------------|----------|-------------------------------------|
| id                  | Integer  | ID del contrato                     |
| associationId       | Integer  | Asociación propietaria              |
| startDate / endDate | DateTime | Fechas de la campaña                |
| status              | String   | Active, Cancelled, etc.             |
| isSuspended         | Boolean  | true si el servicio está suspendido |
| maxZones            | Integer  | Límite de zonas contratadas         |
| maxMicrocontrollers | Integer  | Límite de microcontroladores        |

**Ejemplo de Respuesta Exitosa**

[

{

"id": 3,

"associationId": 1,

"startDate": "2026-01-01T00:00:00Z",

"endDate": "2026-12-31T00:00:00Z",

"status": "Active",

"maxZones": 5,

"maxMicrocontrollers": 3,

"totalAmount": 299.99,

"currency": "USD",

"paymentFrequency": "Monthly",

"isSuspended": false

}

]

**Error: Código 403 Forbidden**

{

"status": 403,

"message": "Forbidden."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/vO2UKMv.png">

<img src="https://imgur.com/KGQ0S5Z.png">

**PATCH /api/v1/profile/{userId}/preferences**

Actualiza las preferencias de notificación del usuario: canales habilitados. El motor de notificaciones aplica la nueva configuración de forma inmediata para los siguientes envíos (US26).

**A. Cabeceras**

| Campo | Tipo | Descripción |
|----|----|----|
| Content-Type | String | application/json |
| Authorization | String | Bearer {jwt_token}. El usuario solo puede modificar sus propias preferencias. |

**B. Parámetros de Búsqueda**

Path: userId (integer).

**C. Ejemplo de Petición**

{

"push": true,

"email": false

}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK — perfil del usuario con preferencias actualizadas.**

| Campo   | Tipo | Descripción                           |
|-------------|----------|-------------------------------------------|
| id          | Integer  | ID del usuario                            |
| name        | String?  | Nombre del usuario                        |
| preferences | Object   | Preferencias de notificación actualizadas |

**Ejemplo de Respuesta Exitosa**

{

"id": 1,

"name": "Juan Perez",

"email": "juan@grotix.pe",

"preferences": {

"push": true,

"email": false

}

}

**Error: Código 404 Not Found**

{

"message": "Usuario 1 no encontrado."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/9Rn7Ezq.png">

<img src="https://imgur.com/cDwUhOC.png">

**GET /api/v1/profile/me/notifications**

Devuelve el historial de notificaciones del usuario autenticado. Soporta filtrado por estado de lectura y paginación por límite (US26).

**A. Cabeceras**

| Campo     | Tipo | Descripción    |
|---------------|----------|--------------------|
| Authorization | String   | Bearer {jwt_token} |

**B. Parámetros de Búsqueda**

Query: unreadOnly (boolean, default false), limit (integer, default 50).

**C. Ejemplo de Petición**

GET /api/v1/profile/me/notifications?unreadOnly=true&limit=20 HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK — array de notificaciones.**

| Campo | Tipo  | Descripción               |
|-----------|-----------|-------------------------------|
| id        | Integer   | ID de la notificación         |
| title     | String    | Título                        |
| message   | String    | Cuerpo del mensaje            |
| type      | String    | info, warning, alert, success |
| isRead    | Boolean   | Estado de lectura             |
| createdAt | DateTime  | Fecha de creación             |
| readAt    | DateTime? | Fecha de lectura              |

**Ejemplo de Respuesta Exitosa**

[

{

"id": 12,

"userId": 1,

"title": "Alerta Crítica de Humedad",

"message": "La humedad del suelo en Parcela Norte ha caído por debajo del umbral mínimo.",

"type": "alert",

"isRead": false,

"createdAt": "2026-06-28T14:00:00Z",

"readAt": null

}

]

**Error: Código 401 Unauthorized**

{

"status": 401

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/Mum0MB3.png">

<img src="https://imgur.com/fBrMl5H.png">

**PATCH /api/v1/profile/me/notifications/{notificationId}/read**

Marca una notificación específica del usuario como leída. Actualiza el campo readAt con el timestamp actual (US26).

**A. Cabeceras**

| Campo     | Tipo | Descripción    |
|---------------|----------|--------------------|
| Authorization | String   | Bearer {jwt_token} |

**B. Parámetros de Búsqueda**

Path: notificationId (integer).

**C. Ejemplo de Petición**

PATCH /api/v1/profile/me/notifications/12/read HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK**

{

"success": true

}

**Error: Código 404 Not Found**

{

"message": "Notification not found."

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/QmJTIeU.png">

<img src="https://imgur.com/pg7Gr7s.png">

**PATCH /api/v1/profile/me/notifications/read-all**

Marca todas las notificaciones no leídas del usuario como leídas en una sola operación. Usado por el botón "Marcar todo como leído" de la bandeja de notificaciones (US26).

**A. Cabeceras**

| Campo     | Tipo | Descripción    |
|---------------|----------|--------------------|
| Authorization | String   | Bearer {jwt_token} |

**B. Parámetros de Búsqueda**

Sin parámetros ni cuerpo.

**C. Ejemplo de Petición**

PATCH /api/v1/profile/me/notifications/read-all HTTP/1.1

Authorization: Bearer {token}

**RESPUESTAS DEL SERVIDOR**

**Éxito: Código 200 OK**

| Campo | Tipo | Descripción                                 |
|-----------|----------|-------------------------------------------------|
| success   | Boolean  | true si la operación fue exitosa                |
| updated   | Integer  | Cantidad de notificaciones marcadas como leídas |

**Ejemplo de Respuesta Exitosa**

{

"success": true,

"updated": 5

}

**Error: Código 401 Unauthorized**

{

"status": 401

}

**D. Evidencia en Swagger**

<img src="https://imgur.com/i4sPfsw.png">

<img src="https://imgur.com/7cUfcUc.png">

#### 6.2.3.8. Software Deployment Evidence for Sprint Review

#### 6.2.3.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews

En esta sección, el equipo registra y explica las actividades de entrevistas de validación durante el proyecto. Se debe realizar entrevistas de validación en las que usuarios de los segmentos objetivo interactúen con el landing page y con las aplicaciones de Grotix. El objetivo es comprobar la usabilidad y la correcta resolución de los problemas identificados durante la fase de Needfinding.

### 6.3.1. Diseño de entrevistas

En esta sección el equipo establece, por cada segmento objetivo, los elementos a incluir en la sesión de validación, abarcando la presentación de la Landing Page para validar la propuesta de valor y la demostración de la aplicación móvil conectada a los servicios backend. Aquí se especifican los flujos de usuario (User Flows) que formarán parte principal del proceso de validación y las preguntas guía de la sesión.

**User Flows utilizados:**

- **Segmento Objetivo #1: Productores Independientes**
  - *User Flow:* Como agricultor independiente, quiero monitorear las variables críticas de mi cultivo en tiempo real (humedad, temperatura, luz) y delegar el trabajo manual habilitando el riego automático mediante umbrales personalizables, para optimizar mi tiempo físico en campo.
  - *User Flow:* Como agricultor independiente, quiero utilizar el procesamiento de imágenes por Inteligencia Artificial para diagnosticar el estado fenológico de mis cultivos y tener seguridad sobre el progreso de mi siembra.

- **Segmento Objetivo #2: Asociaciones Agrarias**
  - *User Flow:* Como administrador de una asociación, quiero auditar y gestionar el personal asignado a una zona de cultivo específica (añadir/remover colaboradores) para mantener el control de acceso a los datos de la granja.
  - *User Flow:* Como administrador de una asociación, quiero generar y descargar reportes históricos de riego y telemetría de forma automatizada y segmentada por periodos de tiempo, para cumplir con los estándares de trazabilidad y calidad requeridos para la exportación.

**Cuestionario de Entrevistas**

**Segmento Objetivo #1: Productores Independientes**

**1. Perfil y Contexto Actual:**

- ¿Cuál es tu nombre, dónde está ubicada tu parcela y qué tipo de cultivos manejas?
- ¿Cómo supervisas actualmente el riego y la salud de tus plantas cuando no estás físicamente en la chacra?
- ¿Cuál es tu mayor preocupación o riesgo (plagas, sequía, heladas) cuando dejas tu cultivo sin supervisión presencial?
- ¿Qué tan familiarizado estás con el uso de aplicaciones móviles para gestionar tu trabajo agrícola?

**2. Interacción con la Landing Page:**

- A primera vista, sin hacer mucho scroll, ¿qué entiendes que ofrece la plataforma Grotix para tu trabajo diario?
- ¿El lenguaje y las palabras utilizadas en la página te resultan familiares o sientes que son demasiado técnicas?
- Considerando los pilares de sensores IoT e Inteligencia Artificial, ¿crees que esta tecnología resolvería los problemas que mencionaste al inicio?
- Al llegar a la sección de Contacto/Formulario, ¿te genera la confianza suficiente para dejar tus datos y solicitar el servicio? ¿Qué información extra te gustaría ver antes de dar ese paso?

**3. Usabilidad de la App Móvil (Dashboard y Settings):**

- Al ingresar a la pantalla principal del Dashboard de tu zona de cultivo, ¿te resulta clara la información sobre la humedad, temperatura y luz? ¿Los colores o medidores te ayudan a entender si todo está bien?
- Te pido que vayas a la pestaña de Configuración e intentes ajustar el tiempo máximo de riego a 3 minutos. ¿Te resultó fácil e intuitivo usar estos controles? Finalmente, basado en tu experiencia, ¿tienes alguna idea o sugerencia para mejorar el diseño visual de este apartado?
- Al activar el interruptor (toggle) del riego automático, ¿sientes que la aplicación te deja claro que el sistema ahora tiene el control del agua? ¿Te daría temor dejarlo activado?

**4. Confianza en la Inteligencia Artificial (AI Image Processing):**

- Al probar la función de Inteligencia Artificial para el análisis de tu planta, ¿sientes que el diagnóstico de la etapa de crecimiento (ej. germinación) es útil para ti?
- Si la aplicación te da un "nivel de confianza del 80%" sobre el estado de tu cultivo, ¿confiarías ciegamente en ese dato o preferirías ir a comprobarlo tú mismo? ¿Por qué?

**5. Cierre y Valor Percibido:**

- ¿Hubo algún botón, ícono o pantalla que no entendiste para qué servía durante la prueba?
- De las 3 funciones principales (monitoreo en vivo, riego automático o IA), ¿cuál sientes que te ahorraría más tiempo físico, dinero o estrés en tu día a día?
- Si este sistema estuviera disponible hoy, ¿estarías dispuesto a instalar estos sensores en tu terreno? ¿Cuál sería tu principal duda antes de comprarlo?

**Segmento Objetivo #2: Asociaciones Agrarias / Administradores de Grotix**

**1. Perfil y Operativa Actual (Contexto)**

- ¿Cuál es tu nombre y cuál es tu rol administrativo o técnico dentro de la organización?
- ¿Cuántas parcelas, asociaciones agrícolas o clientes manejas actualmente y cómo centralizas la información de todos ellos?
- ¿Qué tan complicado te resulta hoy en día llevar el control de los contratos vigentes y saber qué equipos (hardware) están instalados o fallando en el campo?

**2. Navegación en el Dashboard Principal y Búsqueda**

- Tras revisar el "Main Dashboard" con sus tres columnas (clientes activos, contratos y estado de dispositivos), ¿te resultó claro conocer de un solo vistazo la salud general del negocio y qué equipos estaban fuera de línea ("Offline")?
- Sobre la función de búsqueda global ("Search") que te mostramos, ¿te pareció más intuitivo usar esta barra para encontrar una cooperativa específica de forma directa, en lugar de tener que buscarla navegando por las diferentes pestañas?

**3. Gestión de Asociaciones y Contratos**

- Cuando revisamos la sección para editar contratos ("Edit Contract") y viste cómo se modifican los límites de zonas o microcontroladores ("Max Zones", "Max Microcontrollers"), ¿te parecieron claros los campos y el funcionamiento del botón para actualizar los términos?
- Al observar los datos que incluye el contrato (monto total, frecuencia de pago y el botón de terminar contrato), ¿sientes que cubre lo necesario para gestionar un acuerdo de servicio con un cliente agrícola, o crees que haría falta agregar algún otro campo legal o financiero?

**4. Gestión de Personal y Accesos**

- Respecto a la sección de miembros activos ("Active Members"), donde vimos que se genera un enlace de invitación ("Generate Invite Link") para un nuevo usuario con un rol específico, ¿te pareció un proceso rápido y seguro para delegar accesos a tu equipo?

**5. Control de Dispositivos y Bitácora de Mantenimiento**

- Al revisar la vista de dispositivos ("Grotix Devices"), donde cada tarjeta muestra el modelo del microcontrolador, la asociación, la zona asignada y su estado de conexión, ¿consideras que esta es información suficiente para saber rápidamente a dónde debes enviar a un técnico en caso de fallas?
- Sobre el formulario de mantenimiento ("New Maintenance Log") que vimos para registrar acciones técnicas en los equipos, ¿te parece útil y completo para mantener un historial del hardware directamente desde la plataforma?

**6. Cierre y Valor Empresarial**

- Tras ver la navegación de la plataforma web, que utiliza un diseño en modo oscuro (Dark Mode), ¿los colores, el contraste y la distribución de los menús te parecieron cómodos para un uso administrativo diario, o crees que podrían cansarte la vista?
- ¿Aproximadamente cuántas horas de trabajo administrativo estimas que Grotix le ahorraría a tu equipo al centralizar usuarios, contratos y el mantenimiento del hardware IoT en un solo portal?
- Si pudieras pedir una función extra exclusivamente para tu rol de administrador dentro de esta plataforma, ¿cuál sería y por qué?

### 6.3.2. Registro de entrevistas

**Segmento Objetivo #1: Productores Independientes de Pequeña y Mediana Escala**

**Entrevistado N.º 1: Carolina Choquehuanca**

- Edad: 27
- Departamento: Huaral
- Estado civil: Soltera
- Ocupación:

<img src="https://imgur.com/KScRs8R.png">

**Acerca de la entrevista:**

- Link: [https://1drv.ms/v/c/63ce8f5541876735/IQBJg4aIkSfVQJRhyRwiuYDIARsHnRY7MwYtMqVUe7aTx18?e=01MyLw](https://1drv.ms/v/c/63ce8f5541876735/IQBJg4aIkSfVQJRhyRwiuYDIARsHnRY7MwYtMqVUe7aTx18?e=01MyLw)
- Instante en el que inicia: 0:00
- Duración: 11:05

Carolina validó de manera muy positiva el ecosistema de Grotix, señalando que tanto la landing page como la aplicación móvil le encantaron y le resultarían de gran utilidad para optimizar su día a día. Explicó que actualmente posee un huerto donde la activación presencial y manual del sistema de riego le consume una cantidad excesiva de tiempo y dinero, por lo que la automatización remota resuelve directamente su principal dolor operativo. Como única observación de usabilidad para prevenir errores de manipulación en el sistema, sugirió incorporar una ventana de confirmación obligatoria cada vez que se vaya a accionar el riego, independientemente de si este se ejecuta de forma automática o manual.

**Entrevistado N.º 2: Leandro Machaca**

- Edad: 26
- Departamento: Oxapampa, Pasco
- Estado civil: Soltero
- Ocupación: Productor de agricultura familiar (5 años de trayectoria)

<img src="https://imgur.com/hGXcd8s.png">

**Acerca de la entrevista:**

- Link: [https://1drv.ms/v/c/63ce8f5541876735/IQCBrfQUMFa8TJTqt0ky7oUAAZzWVMqnEV7dk9zOl310F40?e=AAo6V8](https://1drv.ms/v/c/63ce8f5541876735/IQCBrfQUMFa8TJTqt0ky7oUAAZzWVMqnEV7dk9zOl310F40?e=AAo6V8)
- Instante en el que inicia: 0:00
- Duración: 21:31

Leandro, enfocado en el cultivo de paltas, calificó a Grotix como una herramienta perfecta para mitigar su necesidad de trasladarse físicamente hasta su huerto ante cualquier anomalía, permitiéndole monitorear la estabilidad de su producción de forma remota. Tras revisar la interfaz, aportó comentarios clave para refinar la arquitectura de la información y la usabilidad: recomendó reubicar el apartado de niveles críticos del dispositivo junto al módulo de riego automático por su estrecha relación lógica, desplazando el riego manual a la parte inferior e implementar una alerta preventiva que le pregunte al usuario si está seguro de salir de la aplicación cuando el riego automático esté desactivado. Además, sugirió optimizar el diseño del dashboard de cada zona para que todas las métricas ambientales sean legibles de un solo vistazo en la pantalla, eliminando por completo la necesidad de hacer scroll.

**Entrevistado N.º 3: Claudio Astocondor**

- Edad: 25
- Departamento: Huaral, Lima
- Estado civil: Soltero
- Ocupación: Administrador agrícola de campo

<img src="https://imgur.com/9orG6se.png">

**Acerca de la entrevista:**


- Link: [Entrevista de Validación - Claudio Astocondor](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAOm2MB01IbRLuWlgKTunP5AfV0J-4KVq6Im47ajxRcWYY?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=IEXfc1)
- Instante en el que inicia: 0:00
- Duración: 23:15

Claudio validó a Grotix como una solución viable y estratégica para optimizar el tiempo operativo y asegurar los rigurosos estándares de calidad exigidos en sus cultivos de fresa y mandarina destinados a la agroexportación. Destacó que el monitoreo remoto es clave para mantener el control del campo durante sus ausencias; sin embargo, manifestó cierta cautela respecto a la infalibilidad del sistema, dado que cualquier margen de error técnico podría traducirse en pérdidas financieras significativas. Tras evaluar la interfaz, consideró atractivas las funcionalidades, pero enfatizó que sus principales condicionantes para adoptar la tecnología radican en el costo de implementación, la autonomía y resistencia del hardware bajo condiciones climáticas reales, y la precisión de la inteligencia artificial antes de delegarle el control total del riego.

**Segmento Objetivo #2: Asociaciones Agrarias y Cooperativas**

**Entrevistado N.º 4: Diego Ahane Barrios**

- Edad: 26
- Departamento: Lima
- Estado civil: Soltero
- Ocupación: Administrador de Operaciones Agrícolas

<img src="https://imgur.com/INEMFK9.png">

**Acerca de la entrevista:**

- Link: [Grotix 202610 - Entrevista de Validación 1 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312443_upc_edu_pe/IQA3yLDKJ0aEQbOAPci2aMvWARh0WKr_GNLx497u29ZDwCM?e=vvaHJT)
- Instante en el que inicia: 0:00
- Duración: 13:45

Diego Ahane se desempeña como administrador de operaciones en una empresa del sector agroexportador, donde supervisa contratos con asociaciones agrícolas, coordina el soporte técnico y realiza el seguimiento de los equipos instalados en campo. Actualmente gestiona alrededor de veinte clientes, cuya información se encuentra distribuida entre hojas de cálculo, correos electrónicos y otros registros, lo que dificulta obtener una visión clara y centralizada de las operaciones.

Durante la validación de Grotix, Diego destacó que uno de los principales retos de su trabajo es identificar rápidamente qué contratos requieren atención y qué dispositivos presentan fallas. En ese sentido, valoró positivamente el Main Dashboard, ya que le permitió visualizar de manera inmediata el estado general del negocio y detectar equipos fuera de línea. Asimismo, consideró que la búsqueda global agiliza la localización de asociaciones específicas y que la edición de contratos resulta intuitiva y fácil de comprender, aunque sugirió incorporar opciones como renovaciones automáticas y documentos adjuntos.

También señaló que la gestión de usuarios mediante enlaces de invitación facilita la delegación de accesos de forma segura. Respecto al módulo de dispositivos y mantenimiento, consideró que la información mostrada es suficiente para coordinar intervenciones técnicas y mantener un historial ordenado de las acciones realizadas. Finalmente, estimó que una plataforma como Grotix podría ahorrar entre ocho y doce horas semanales a su equipo administrativo y sugirió incorporar alertas predictivas y reportes automáticos para anticipar fallas y optimizar la toma de decisiones.

**Entrevistado N.º 5: Santiago Cárdenas**

- Edad: 25
- Departamento: Huancayo
- Estado civil: Soltero
- Ocupación: Gerente de operaciones en empresa agroexportadora

<img src="https://imgur.com/tgZ8RjA.png">

**Acerca de la entrevista:**

- Link: [Grotix 202610 - Entrevista de Validación 2 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312443_upc_edu_pe/IQDlfNnfcV-CTLGJqtewwUbMAcmuuEit8Lndp2R6lKEoohE?e=VtsfpE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Instante en el que inicia: 0:00
- Duración: 9:00

Santiago Cárdenas se desempeña como gerente de operaciones en una empresa del sector agroexportador y es responsable de supervisar contratos, coordinar al equipo técnico y dar seguimiento a los dispositivos instalados en distintas asociaciones agrícolas. Actualmente gestiona alrededor de doce asociaciones, cuya información se encuentra distribuida entre hojas de cálculo, correos electrónicos y reportes internos, lo que dificulta la centralización de datos.

Durante la validación de Grotix, Santiago indicó que uno de los principales problemas es la actualización oportuna de la información operativa. En ese sentido, valoró el Main Dashboard porque permite visualizar rápidamente el estado general del sistema e identificar incidencias. También destacó que la búsqueda global facilita encontrar asociaciones específicas sin necesidad de navegar por todo el sistema.

Asimismo, señaló que la sección de contratos es clara y fácil de usar, aunque sugirió agregar alertas de vencimiento e historial de cambios. Respecto a la gestión de usuarios, consideró útil la generación de enlaces de invitación, pero recomendó incluir fechas de expiración por seguridad.

En cuanto a los dispositivos, mencionó que la información mostrada es suficiente para coordinar soporte técnico rápidamente, y que el registro de mantenimiento ayuda a mantener un historial ordenado. Finalmente, estimó que la plataforma podría ahorrar entre cuatro y seis horas semanales y sugirió incorporar reportes ejecutivos exportables para mejorar la toma de decisiones.

**Entrevistado N.º 6: Alyssa Ortega**

- Edad: 24
- Departamento: Lima
- Estado civil: Soltera
- Ocupación: Coordinadora de soporte operativo empresa exportadora

<img src="https://imgur.com/Ene5fzJ.png">

**Acerca de la entrevista:**

- Link: [Grotix 202610 - Entrevista de Validación 3 Segmento 2.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312443_upc_edu_pe/IQDrvmcf_dk7RLI5vWh2yLxlAcFsmsLHsq7i8f9afnxibLA?e=vfBm3m&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
- Instante en el que inicia: 0:00
- Duración: 21:31

Alyssa Ortega se desempeña como coordinadora de soporte operativo en una empresa del sector agroexportador y es responsable de supervisar incidencias en campo, coordinar al equipo técnico y dar seguimiento al estado de los dispositivos instalados en distintas asociaciones agrícolas. Actualmente gestiona alrededor de diez a doce asociaciones, cuya información se encuentra distribuida entre reportes en Excel, mensajes de WhatsApp y registros compartidos, lo que dificulta mantener una actualización centralizada y oportuna de los datos.

Durante la validación de Grotix, Alyssa indicó que uno de los principales problemas es la falta de información en tiempo real, lo que puede retrasar la atención de incidencias. En ese sentido, valoró el Main Dashboard porque permite identificar rápidamente el estado general de los dispositivos y priorizar los casos urgentes. También destacó que la búsqueda global facilita encontrar asociaciones específicas de forma rápida sin navegar por todo el sistema.

Asimismo, señaló que la sección de contratos es clara y fácil de usar, aunque sugirió incluir alertas de renovación y notas internas para mejorar la coordinación. Respecto a los dispositivos, mencionó que la información mostrada es suficiente para ubicar fallas y coordinar soporte técnico. Finalmente, estimó que la plataforma podría generar un ahorro de entre cinco y siete horas semanales, principalmente en la gestión de incidencias y búsqueda de información, y propuso incorporar alertas en tiempo real para mejorar la respuesta operativa.

#### 6.3.3. Evaluaciones según heurísticas

**UX Heuristics & Principles Evaluation**

Usability – Inclusive Design – Information Architecture

CARRERA: Ingeniería de Software

CURSO: Desarrollo de Soluciones IoT

SECCIÓN: 6772

PROFESOR: Marco Antonio Leon Baca

AUDITOR: Grotix Staff

CLIENTE(S): Carolina Choquehuanca, Leandro Machaca, Claudio Astocondor, Diego Ahane, Santiago Cárdenas, Alyssa Ortega.

**SITE o APP A EVALUAR:**

*Grotix – Landing Page, Web App y App Móvil*

**TAREAS EVALUADAS:**

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

- Navegación informativa del landing (servicios, app, equipo, contacto, redes, páginas legales y centro de ayuda).
- Inicio de sesión y registro de cuenta (Web App y App Móvil).
- Gestión de asociaciones, contratos y zonas de cultivo desde la Web App.
- Gestión de dispositivos IoT: listado, detalle, sensores/actuadores, bitácora y mantenimiento.
- Gestión de cultivos (crops) y sus parámetros óptimos.
- Edición de perfil de usuario (Web App y App Móvil).
- Monitoreo de zona de cultivo, configuración de riego automático/manual y gestión de personas (App Móvil).
- Generación de reportes y revisión de notificaciones (App Móvil).

**ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad.

| Nivel | Descripción |
|---|---|
| 1 | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2 | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4 | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN:**

| # | Problema | Escala de severidad | Heurística/Principio violado |
|---|---|---|---|
| 1 | Botón "Terminate Contract" sin confirmación, ubicado junto a "Update Contract" | 4 | Usability: Prevención de errores |
| 2 | Inconsistencia de idioma en toda la plataforma | 3 | Usability: Consistencia y estándares |
| 3 | Sidebar de navegación de la Web App sin etiquetas de texto | 2 | Usability: Reconocimiento antes que memoria |
| 4 | El botón "+" de "Cultivation Areas" no crea una zona, sino que muestra un número de teléfono | 2 | Usability: Coincidencia entre el sistema y el mundo real |
| 5 | Campos de fecha sin formato indicado en "Generate Report" | 1 | Usability: Prevención de errores |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1: Botón "Terminate Contract" sin confirmación, ubicado junto a "Update Contract"**

Severidad: 4

Heurística violada: Usability: Prevención de errores

Pantalla / Ubicación: *Web App – Detalle de Asociación*

Problema:

En la pantalla de detalle de una asociación ("Association Details"), el botón rojo "TERMINATE CONTRACT" aparece inmediatamente debajo del botón "UPDATE CONTRACT", con un tamaño y jerarquía visual similares. Terminar un contrato es una acción destructiva y probablemente irreversible (afecta el servicio activo de una asociación completa, sus zonas y dispositivos), por lo que un clic accidental ‒especialmente al intentar pulsar "Update Contract"‒ puede tener consecuencias graves para el negocio del cliente.

<img src="">

Recomendación:

Separar visualmente el botón destructivo del resto de acciones (ubicación distinta o un área secundaria de "acciones peligrosas"). Modificar el modal de confirmación para que obligue al usuario a escribir el nombre de la asociación o confirmar explícitamente la acción, e indicar las consecuencias (qué pasa con las zonas, dispositivos y usuarios asociados al contrato).

**PROBLEMA #2: Inconsistencia de idioma en toda la plataforma**

Severidad: 3

Heurística violada: Usability: Consistencia y estándares

Pantalla / Ubicación: *Web App*

Problema:

La interfaz combina inglés y español de forma impredecible. La página "Mi Perfil" de la Web App está enteramente en español ("Información Personal", "Correo Electrónico", "Nombre Completo", "Identificación (Tax ID)") mientras el resto del dashboard (Main Dashboard, Devices, Crops, Associations) está en inglés. No existe un selector de idioma visible que justifique este comportamiento ni una razón aparente para la mezcla.

<img src="">

<img src="">

Recomendación:

Definir un idioma consistente por sesión de usuario (ya existe un selector EN/ES en el landing; debería propagarse a Web App). Auditar todas las cadenas de texto hardcodeadas (placeholders, modales, mensajes de sistema) y centralizarlas en un sistema de internacionalización (i18n) único.

**PROBLEMA #3: Sidebar de navegación de la Web App sin etiquetas de texto**

Severidad: 2

Heurística violada: Usability: Reconocimiento antes que memoria

Pantalla / Ubicación: *Web App – Navegación global*

Problema:

El menú lateral persistente muestra siete íconos (inicio, búsqueda, perfil/agricultores, documento, dispositivo, hoja/cultivos, engranaje) sin ningún texto que los acompañe ni tooltips visibles en las capturas analizadas. Íconos como el de "documento" o "dispositivo" (engranaje circular) no tienen un significado universalmente reconocible, por lo que un usuario nuevo debe recurrir a la prueba y error o memorizar la posición de cada función en lugar de reconocerla directamente.

<img src="">

Recomendación:

Añadir etiquetas de texto junto a cada ícono (al menos en estado expandido del sidebar, o mediante tooltips accesibles al pasar el cursor/foco). Evaluar si conviene un sidebar expandible con texto visible por defecto, dado que el espacio horizontal en escritorio no es una restricción crítica.

**PROBLEMA #4: El botón "+" de "Cultivation Areas" no crea una zona, sino que muestra un número de teléfono**

Severidad: 2

Heurística violada: Usability: Coincidencia entre el sistema y el mundo real

Pantalla / Ubicación: *App Móvil – Cultivation Areas*

Problema:

El ícono "+" en la pantalla "Cultivation Areas" es el patrón universal para "crear/agregar un nuevo elemento". Al presionarlo, sin embargo, se abre un modal ("Añadir nueva zona") que explica que la creación de zonas está gestionada exclusivamente por el equipo de soporte, y ofrece únicamente un número de teléfono y un botón "Entendido". El usuario no puede completar la acción que el ícono prometía dentro de la misma app, lo que genera una expectativa incumplida.

<img src="">

Recomendación:

Sustituir el ícono "+" por un botón con etiqueta explícita como "Solicitar nueva zona" o "Contactar soporte", evitando el ícono estándar de creación si la acción real es una derivación a un canal externo.

**PROBLEMA #5: Campos de fecha sin formato indicado en "Generate Report"**

Severidad: 1

Heurística violada: Usability: Prevención de errores

Pantalla / Ubicación: *App Móvil – Generate Report*

Problema:

Los campos "Start" y "Finish" del formulario de generación de reportes muestran el placeholder genérico "--/--/--", sin indicar si el formato esperado es DD/MM/AAAA (convención peruana) o MM/DD/AAAA. Aunque es probable que un selector de calendario evite el problema en la mayoría de los casos, el placeholder por sí solo no comunica el formato si el usuario llegara a escribir la fecha manualmente.

<img src="">

Recomendación:

Mostrar el formato esperado explícitamente en el placeholder (p. ej. "DD/MM/AAAA") o apoyarse exclusivamente en un selector de calendario nativo que elimine la ambigüedad de entrada manual.

## 6.4. Video About-the-Product

El presente video ha sido diseñado como una herramienta de comunicación estratégica para presentar nuestra solución integral frente a los retos de la agricultura moderna. El contenido está dirigido a visitantes de nuestra Landing Page y usuarios finales, ofreciendo una visión clara de cómo Grotix optimiza la gestión hídrica mediante hardware IoT resiliente y procesamiento en el borde. A través de una demostración del funcionamiento real de los componentes electrónicos (ESP32), el flujo de la aplicación móvil y la capacidad diagnóstica de nuestra Inteligencia Artificial, el video articula el valor de negocio de Grotix: la capacidad de operar de forma autónoma en entornos de conectividad limitada, transformando la intuición del agricultor en decisiones basadas en datos precisos. La pieza se complementa con un testimonio de validación real que ratifica la reducción de costos operativos y la tranquilidad que nuestra solución aporta a las operaciones agrícolas.

<img src="https://imgur.com/pSdk7pA.png">

Link del video en Microsoft Streams: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQB_rO1R__CXRrOb6dEIM27bASKboXi3LUS6jOZnjuvsrRo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1btASA](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQB_rO1R__CXRrOb6dEIM27bASKboXi3LUS6jOZnjuvsrRo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1btASA)

Link del video en YT:

# Conclusiones

* Validación del Modelo de Negocio y Enfoque Lean UX: La consolidación de Grotix como una solución de negocio tecnológicamente viable y financieramente escalable se fundamenta en la ejecución rigurosa del Lean UX Process. Se validó empíricamente que la severa ineficiencia hídrica en el agro peruano —donde el 80% del agua se pierde y el 97.4% de las tierras irrigadas depende del riego por gravedad— puede mitigarse críticamente mediante un ecosistema IoT combinado con Inteligencia Artificial. Este enfoque transforma las prácticas empíricas tradicionales de riego en decisiones técnicas basadas en la precisión de datos en tiempo real, maximizando el valor operativo bajo el modelo Hardware as a Service (HaaS).

* Trazabilidad de Requerimientos centrado en el Usuario: La transición metodológica desde la fase de Needfinding (análisis de competidores, mapas de empatía y User Personas desarrollado en el Capítulo II) hacia la especificación técnica de requerimientos en el Capítulo III y el diseño del software en el Capítulo IV asegura una trazabilidad impecable. Cada User Story y Technical Story (TS) responde de forma directa a un dolor real del pequeño agricultor y de las asociaciones agrarias, garantizando que el software resuelva problemas críticos como la ausencia de históricos climáticos, el monitoreo remoto desarticulado y la falta de control preciso sobre el suelo.

- Rigurosidad Técnica mediante Atributos de Calidad: La inclusión de Atributos de Calidad específicos y sus respectivas Technical Stories eleva la propuesta de Grotix de un prototipo académico a un nivel industrial de producción. Al diseñar el backend de microservicios y las interfaces frontend (Web/Mobile) bajo métricas estrictas de disponibilidad, modificabilidad, seguridad y performance, se garantiza una plataforma resiliente capaz de soportar las exigencias de un entorno agrícola real, controlando ráfagas masivas de ingesta de datos sin degradar el rendimiento del ecosistema cloud.

- Resiliencia en la Última Milla mediante Edge Computing y Store-and-Forward: Se concluye que la arquitectura de hardware implementada sobre el microcontrolador ESP32 (WROOM/S3) es capaz de mitigar la inestabilidad de conectividad (Wi-Fi/4G) inherente a las zonas rurales peruanas gracias a la implementación de una Edge App con persistencia local (Edge DB). El diseño e integración del patrón Store-and-Forward demostró ser el mecanismo crítico para garantizar la integridad de las lecturas, sincronizando la información acumulada de manera asíncrona una vez restablecido el enlace con el Message Broker, eliminando así vacíos analíticos en el historial del cultivo.

- Desacoplamiento Operativo y Escalabilidad con DDD Estratégico: La separación física de los seis Bounded Contexts definidos (Profile, Cultivation Area, Hardware Device, Irrigation Cycle, Crop Analysis y Telemetry) en microservicios independientes programados en C# / .NET y coordinados a través de un API Gateway centralizado en Azure garantiza la resiliencia operativa de la solución. Esta disposición estratégica impide el acoplamiento sistémico, asegurando que fallos aislados en servicios adyacentes no comprometan las actividades críticas de telemetría y ejecución de ciclos de riego, permitiendo además la asignación eficiente de recursos en la nube.

* Desacoplamiento Operativo y Escalabilidad con DDD Estratégico: La separación física de los seis Bounded Contexts definidos (Profile, Cultivation Area, Hardware Device, Irrigation Cycle, Crop Analysis y Telemetry) en microservicios independientes programados en C# / .NET y coordinados a través de un API Gateway centralizado en Azure garantiza la resiliencia operativa de la solución. Esta disposición estratégica impide el acoplamiento sistémico, asegurando que fallos aislados en servicios adyacentes no comprometan las actividades críticas de telemetría y ejecución de ciclos de riego, permitiendo además la asignación eficiente de recursos en la nube.

* Persistencia Políglota Optimizada para IoT: El diseño de la capa de datos bajo un esquema de persistencia políglota resuelve de forma eficiente las necesidades transaccionales y analíticas de la plataforma. La segregación física entre bases de datos relacionales (Core DB en MySQL para entidades y configuraciones de microservicios) y bases de datos optimizadas para series temporales (Telemetry DB implementada en TimescaleDB sobre Azure) evita cuellos de botella durante la ingesta masiva de lecturas concurrentes provenientes de los sensores de suelo y ambiente, optimizando los tiempos de respuesta de las consultas históricas.

* Sinergia de Patrones Arquitectónicos (Repository y Pub-Sub): La combinación de los patrones de diseño Repository y Publisher-Subscriber dota a la plataforma de una flexibilidad de nivel industrial. Mientras que el patrón Repository independiza la lógica de negocio del dominio frente a los motores físicos de persistencia (facilitando pruebas unitarias y la mantenibilidad de la librería compartida BuildingBlocks), el patrón Pub-Sub operado mediante MQTT en el borde y RabbitMQ (CloudAMQP) en la nube actúa como el sistema circulatorio asíncrono de Grotix, distribuyendo eventos y comandos (OPEN/CLOSE) de forma eficiente y no bloqueante.

* Inclusión Tecnológica mediante Visión Artificial (Crop Analysis): La integración del microservicio de análisis fenológico basado en visión artificial (Crop Analysis) actúa como un catalizador indispensable para la adopción digital en comunidades agrícolas con baja alfabetización tecnológica. Al automatizar la identificación de fases de crecimiento y fitopatologías visuales en las plantas, y comunicar estos datos procesados hacia el contexto de irrigación a través de una Capa Anticorrupción (Anti-Corruption Layer - ACL), se reduce significativamente la carga cognitiva del usuario, democratizando el acceso a la agricultura de precisión.

* Validación Integral del Deployment en Sprints 1 y 2: Las actividades de despliegue continuo (CI/CD) orquestadas mediante GitHub Actions y scripts automatizados en la nube de Azure (Región Chile Central) validaron la viabilidad técnica y operativa de la solución al cierre del Sprint 2. La disponibilidad activa de los endpoints para servicios esenciales, la correcta configuración de variables de entorno y secretos de infraestructura, y el despliegue funcional de la aplicación Web (Firebase) y la aplicación Móvil (APK compilado automáticamente), reducen drásticamente la incertidumbre técnica y demuestran la viabilidad de puesta en producción real del ecosistema Grotix.

* La implementación física de los nodos IoT demostró que la estabilidad del software depende críticamente de la topología eléctrica. Durante el desarrollo con el microcontrolador ESP32-C3, módulos de relé y bombas de agua, se validó empíricamente la necesidad de aislar lógicamente el "Cerebro" (microcontrolador) de los "Músculos" (actuadores mecánicos). La segregación de fuentes de alimentación (aislando las corrientes de 5V) evitó reinicios súbitos provocados por caídas de tensión (Brownouts) y ruido electromagnético (EMI) generados por los motores de las bombas, garantizando una ingesta de telemetría continua y sin interrupciones. 

* Se concluye que en sistemas IoT aplicados a la agricultura, la dependencia exclusiva de la nube para el control de actuadores representa un riesgo crítico de negocio. El desarrollo del firmware validó la importancia de programar reglas de seguridad a nivel de hardware (como temporizadores Watchdog y funciones Auto-Stop en los pines GPIO). Estos mecanismos de defensa descentralizados aseguran que, ante una pérdida de conectividad Wi-Fi o caída del servidor durante un ciclo de riego activo, el microcontrolador cierre de forma autónoma el flujo de agua, previniendo daños irreparables en el cultivo por inundación 

* El hito más representativo del trabajo final es la orquestación bidireccional exitosa. Grotix dejó de ser un sistema puramente de monitoreo (lectura de datos) para convertirse en un sistema de control activo. La capacidad de leer sensores físicos (DHT22, capacitivos de humedad), enviar payloads empaquetados en JSON mediante clientes HTTP/MQTT hacia la nube, y recibir comandos asíncronos en milisegundos para accionar los relés del ESP32, valida la madurez de la plataforma para operar el ciclo completo del Internet de las Cosas en tiempo real. 

# Recomendaciones

Con la finalidad de garantizar la sostenibilidad técnica, la escalabilidad y la futura evolución del ecosistema *Grotix* hacia un entorno de producción industrial bajo el modelo *Hardware as a Service* (HaaS), se formulan las siguientes recomendaciones estratégicas y operativas agrupadas por ejes de ingeniería:

**1. Arquitectura de Software y Diseño Orientado a Dominios**

* Consolidación del Desacoplamiento en la Arquitectura Inicial (.NET): Se recomienda priorizar la estructuración del *Minimum Viable Product* (MVP) asegurando que el esqueleto arquitectónico en .NET refleje estrictamente el desacoplamiento estipulado en las Historias Técnicas de Interoperabilidad (TS02) y Modificabilidad (TS03). La lógica de negocio detallada no debe ser programada antes de validar que los límites lógicos de las capas (*Domain, Application, Infrastructure, Interface*) estén blindados contra dependencias circulares.

* Aislamiento del Core Domain mediante una Capa Anticorrupción (ACL): Es mandatorio implementar un componente ACL riguroso entre el microservicio *Crop Analysis* (IA) y el *Irrigation Cycle Service*. Esto evitará que la complejidad inherente a los modelos de visión artificial e inferencia fenológica contamine el motor transaccional de riego. El contexto de irrigación debe consumir únicamente contratos de datos estables e interfaces limpias, garantizando que futuras actualizaciones, recalibraciones o migraciones de los modelos de IA no fuercen refactorizaciones en la lógica central de negocio.

* Gobernanza Arquitectónica y Revisiones Periódicas: Se sugiere establecer juntas de revisión arquitectónica regulares en las siguientes iteraciones. El objetivo es contrastar la implementación física con los diagramas de contenedores, componentes y el mapa de contextos (*Context Mapping*) definidos en los ciclos ADD 3, 4 y 5, mitigando proactivamente la erosión arquitectónica o el acoplamiento accidental entre microservicios adyacentes.

**2. Ingeniería de Hardware y Resiliencia en el Borde (Edge Computing)**

* Validación de Contratos de Datos mediante PoC Temprana: Se aconseja ejecutar una Prueba de Concepto (PoC) aislada y temprana enfocada de forma exclusiva en validar el intercambio de payloads entre los microcontroladores ESP32 (WROOM/S3) y el backend en C#. Se debe asegurar que las serializaciones y deserializaciones en formato JSON se procesen correctamente bajo condiciones variables de red, mitigando problemas de latencia o desalineación de esquemas antes de la fabricación en serie de los nodos sensores.

* Implementación Prioritaria de Autonomía en el Borde (Edge Autonomy): Ante la latencia e intermitencia crítica de las redes 4G/Wi-Fi en el agro rural peruano, se debe priorizar el desarrollo de la lógica *Store-and-Forward* y el modo de operación degradado en la *Edge App*. El firmware del ESP32 debe ser capaz de ejecutar ciclos de riego programados localmente consultando la base de datos local (*Edge DB*), operando de manera 100% autónoma y encolando la telemetría histórica hasta que el canal de comunicación con el *Message Broker* sea seguro y estable.

**3. Estrategia de Datos y Persistencia Políglota**

* Alineación de la Infraestructura Dual de Persistencia: Es sumamente crítico realizar el setup y la segregación física del almacenamiento transaccional (*Core DB* en MySQL) y el almacenamiento analítico (*Telemetry DB* en TimescaleDB). Se debe asegurar por diseño que no existan consultas cruzadas distribuidas (*cross-context queries*) entre bases de datos de microservicios distintos. Adicionalmente, el *Telemetry Service* debe configurarse para aislar las ráfagas masivas de ingesta de datos concurrentes, evitando la degradación del rendimiento general en recursos compartidos o en planes escalables de infraestructura (como las instancias Azure MySQL Burstable B1ms).

**4. Aseguramiento de la Calidad y Automatización del Pipeline (DevOps)**

* Automatización de la Pirámide de Pruebas en el Ciclo CI/CD: Habiendo establecido suites de pruebas unitarias y de integración (con xUnit para .NET, y frameworks afines), es indispensable automatizar su ejecución mediante *GitHub Actions*. Se recomienda configurar políticas de rama (*Branch Protections*) que bloqueen de forma automática cualquier *Pull Request* o *Merge* hacia la rama develop o main si la cobertura de código cae por debajo del umbral del 80%, o si fallan las pruebas de contrato de la API, impidiendo que el API Gateway exponga contratos rotos.

* Gobernanza Estricta de la Librería Compartida (BuildingBlocks): Dado que se han centralizado las capacidades transversales de infraestructura (autenticación JWT, *Health Checks* de preparación/vida, y abstracciones de Entity Framework) en la librería compartida *BuildingBlocks*, esta debe tratarse internamente como un producto independiente. Cualquier modificación de código en este componente común debe estar sujeta a un proceso riguroso de *Code Review* multipar, previniendo regresiones o fallos en cascada dentro de los microservicios core como *Profiles* y *Cultivation Area*.

* Automatización Estática mediante Linters y Git Hooks: Con el propósito de homogeneizar el código fuente dentro de los cuatro repositorios activos (Landing, Web, Backend, Mobile), se sugiere integrar herramientas de análisis estático (*linters* como StyleCop, ESLint y Pylint) acopladas a *Git Hooks* (mediante herramientas como Husky). Esto obligará a que cada confirmación (*commit*) respete de manera nativa la nomenclatura técnica estrictamente en inglés, las buenas prácticas semánticas y las convenciones de formateo acordadas por la startup *Celevi*.

**5. Infraestructura Cloud y Observabilidad Avanzada**

* Evolución hacia Infraestructura como Código (IaC): Se recomienda migrar la provisión manual realizada en el portal de Azure hacia plantillas declarativas usando *Bicep* o *Terraform*. El almacenamiento de configuraciones de red, contenedores, Azure App Services y las bases de datos en código permitirá replicar el entorno de producción de manera exacta en ambientes de *Staging* o *QA*, reduciendo a cero los errores humanos en el seteo de variables de entorno, cadenas de conexión y *User Secrets*.

* Monitoreo y Observabilidad Post-Despliegue: Aprovechando que los microservicios ya integran endpoints de diagnóstico /api/v1/irrigation/health/live y /ready, el siguiente paso crítico consiste en centralizar estas métricas en *Azure Application Insights*. Se aconseja parametrizar alertas proactivas que notifiquen al equipo de desarrollo ante anomalías en la tasa de transferencia del broker RabbitMQ, incrementos atípicos en la latencia del API Gateway o saturación de memoria por el procesamiento de imágenes, optimizando la tolerancia a fallos del sistema en producción.

**6. Experiencia de Usuario (UI/UX) y Roadmap del Producto**

* Modularización mediante una Librería de Componentes UI: Para resguardar la consistencia visual y la velocidad de desarrollo en las aplicaciones Frontend (Web en Firebase y la App Móvil Android), es altamente recomendable estructurar una librería interna de componentes UI reutilizables basada en las guías de estilo formuladas en el Capítulo V. Esto optimizará los flujos de navegación unificados para productores y cooperativas de exportación.

* Evolución del Roadmap Analítico y del Motor de IA: De cara al futuro comercial de *Grotix*, se sugiere robustecer el microservicio de *Crop Analysis*. El plan de evolución técnica debe priorizar la ingesta de nuevas fuentes de información (imágenes multiespectrales, datos meteorológicos satelitales externos) y ampliar el entrenamiento de los algoritmos para diversificar el catálogo de cultivos compatibles, incrementando con ello la precisión predictiva de las alertas fitosanitarias enviadas a los usuarios de la plataforma.

**7. Gestión del Ciclo de Vida del Hardware IoT y Firmware**

* Implementación de Actualizaciones Remotas (Over-The-Air - OTA): Dado que el modelo HaaS (Hardware as a Service) de Grotix contempla el despliegue de microcontroladores ESP32 en zonas agrícolas rurales y de difícil acceso físico, es mandatorio integrar capacidades de despliegue OTA en el firmware. Esto permitirá a los administradores de la plataforma inyectar parches de seguridad, actualizar credenciales Wi-Fi, o modificar la lógica de calibración de los sensores masivamente desde el backend, reduciendo drásticamente los costos operativos asociados al envío de técnicos al terreno.

* Optimización Energética mediante Estados de Suspensión (Deep Sleep): Para escalar la solución a cultivos extensivos donde no hay acceso a la red eléctrica continua, se recomienda evolucionar el código de los microcontroladores hacia un enfoque de Ultra-Bajo Consumo. Se debe programar el uso del modo Deep Sleep del ESP32, permitiendo que el hardware "despierte" únicamente cada 15 o 30 minutos, encienda el módulo Wi-Fi, envíe la ráfaga de telemetría y vuelva a dormir. Esto, acoplado a paneles solares de bajo amperaje y baterías de litio (ej. 18650), otorgará a los nodos de Grotix una autonomía energética real de meses o años.

* Procesamiento Analítico en el Borde (Edge Analytics) y Filtrado de Ruido: Actualmente, los sensores envían la lectura cruda al backend. Para futuras iteraciones, se recomienda trasladar algoritmos ligeros de procesamiento de señales directamente al firmware del ESP32. Implementar filtros matemáticos (como Promedios Móviles o un Filtro de Kalman básico) en C++ mitigará los falsos positivos derivados de lecturas anómalas (picos de humedad erróneos o fallos del sensor DHT22), asegurando que los *payloads* de telemetría que viajan a la nube sean altamente precisos, ahorrando ancho de banda y minimizando el procesamiento en el servidor.

# Bibliografía

Agencia Andina. (2011, 11 de abril). ANA: 80% del agua destinada a uso agrícola se pierde por deficiencias en riego. [https://andina.pe/agencia/noticia-ana-80-del-agua-destinada-a-uso-agricola-se-pierde-deficiencias-riego-343493.aspx](https://andina.pe/agencia/noticia-ana-80-del-agua-destinada-a-uso-agricola-se-pierde-deficiencias-riego-343493.aspx)

AgroPerú. (2024, noviembre 8). Déficit hídrico amenaza la campaña agrícola 2024–2025. [AgroPerú](https://www.agroperu.pe/deficit-hidrico-amenaza-la-campana-agricola-2024-2025/?utm_source=chatgpt.com)

Alvarez, A. (2020, 5 de agosto). 5W2H: Qué significa, para qué sirve, cómo aplicarla y algunos ejemplos. LeanConstructionMexico. [https://www.leanconstructionmexico.com.mx/post/5w2h-qué-significa-para-qué-sirve-cómo-aplicarla-y-algunos-ejemplos](https://www.leanconstructionmexico.com.mx/post/5w2h-qué-significa-para-qué-sirve-cómo-aplicarla-y-algunos-ejemplos)

Centro Nacional de Planeamiento Estratégico. (s. f.). Ficha R10: Agricultura (Observatorio Nacional de Prospectiva). [CEPLAN](https://observatorio.ceplan.gob.pe/ficha/r10_an?utm_source=chatgpt.com)

Centro Peruano de Estudios Sociales (CEPES). (2024). Índice Global del Hambre (IGH) 2024: Informe Perú. [https://cepes.org.pe/](https://cepes.org.pe/)

Garay Canales, O. B. (2009). Manual de uso consuntivo del agua para los principales cultivos de los Andes centrales peruanos. [Instituto Geofísico del Perú](http://met.igp.gob.pe/proyectos/incagro/datos/ManualConsuntivo.pdf?utm_source=chatgpt.com)

Escobal, J., Trivelli, C., & Revesz, B. (2006). Pequeña agricultura comercial: dinámica y retos en el Perú. Consorcio de Investigación Económica y Social (CIES), Centro de Investigación y Promoción del Campesinado (CIPCA), Instituto de Estudios Peruanos (IEP) y Grupo de Análisis para el Desarrollo (GRADE). [https://www.grade.org.pe/upload/publicaciones/archivo/download/pubs/LIBROGRADE_PEQUENAAGRICULTURACOMERCIAL.pdf](https://www.grade.org.pe/upload/publicaciones/archivo/download/pubs/LIBROGRADE_PEQUENAAGRICULTURACOMERCIAL.pdf)

Excélsior Digital. (2022, 6 de abril). Sector agrícola ocupa hasta 76% de agua del país; es también en el que más se desperdicia. [https://www.excelsior.com.mx/nacional/sector-agricola-ocupa-hasta-76-de-agua-del-pais-es-tambien-es-el-que-mas-la-desperdicia](https://www.excelsior.com.mx/nacional/sector-agricola-ocupa-hasta-76-de-agua-del-pais-es-tambien-es-el-que-mas-la-desperdicia)

Iberico, J. (2016). Abastecimiento de agua para la agricultura en la costa. En Revista Moneda, (N.º 168). [Banco Central de Reserva del Perú](https://www.bcrp.gob.pe/docs/Publicaciones/Revista-Moneda/moneda-168/moneda-168-07.pdf?utm_source=chatgpt.com)

Instituto Nacional de Estadística e Informática. (2023). Encuesta Nacional Agropecuaria 2022: Principales Resultados. Lima: Instituto Nacional de Estadística e Informática. Recuperado de [https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1912/libro.pdf](https://www.inei.gob.pe/media/MenuRecursivo/publicaciones_digitales/Est/Lib1912/libro.pdf)

Instituto Nacional de Estadística e Informática. (2023). Sistema de monitoreo y seguimiento de los indicadores de los Objetivos de Desarrollo Sostenible. [https://ods.inei.gob.pe/ods/](https://ods.inei.gob.pe/ods/)

Instituto Nacional de Estadística e Informática. (2024). La agricultura familiar en el Perú: Retos y posibilidades para su transformación en el contexto de los Objetivos de Desarrollo Sostenible (ODS). [INEI](https://www.inei.gob.pe/media/MenuRecursivo/investigaciones/agricultura-familiar-en-el-peru.pdf?utm_source=chatgpt.com)

Linares Nima, L. M. (2025, mayo 6). Crisis hídrica y cambio climático en Perú: el impacto de la agroexportación. Programa de Investigación en Cambio Climático, Universidad Nacional Autónoma de México (PINCC-UNAM).

Ministerio de Transportes y Comunicaciones. (2025, diciembre 31). Más de 194 mil ciudadanos en 924 localidades rurales accedieron por primera vez a servicios móviles 4G en 2025. [Gob.pe](https://www.gob.pe/institucion/mtc/noticias/1324575-mtc-mas-de-194-mil-ciudadanos-en-924-localidades-rurales-accedieron-por-primera-vez-a-servicios-moviles-4g-en-2025?utm_source=chatgpt.com)

Montaño, F. (2023, noviembre 5). La crisis histórica del agro impacta y amenaza la agricultura familiar. [Ojo Público](https://ojo-publico.com/derechos-humanos/la-crisis-historica-del-agro-impacta-y-amenaza-la-agricultura-familiar?utm_source=chatgpt.com)

Nagel, J. (2012). Principales barreras para la adopción de las TIC en la agricultura y en las áreas rurales. Comisión Económica para América Latina y el Caribe (CEPAL). [CEPAL](https://www.cepal.org/es/publicaciones/4011-principales-barreras-la-adopcion-tic-la-agricultura-areas-rurales?utm_source=chatgpt.com)

Organización de las Naciones Unidas para la Alimentación y la Agricultura (FAO). (2024). El estado de la seguridad alimentaria y la nutrición en el mundo (SOFI) 2024. [https://www.fao.org/publications/sofi/es/](https://www.fao.org/publications/sofi/es/) 

Pintado, M. (2022, agosto 22). Calendario agrícola, fertilizantes y seguridad alimentaria. [Centro Peruano de Estudios Sociales](https://cepes.org.pe/2022/08/22/calendario-agricola-fertilizantes-y-seguridad-alimentaria/?utm_source=chatgpt.com)

Pontificia Universidad Católica del Perú. (2024, abril 11). Los impactos de las sequías en el Perú. [Clima de Cambios PUCP](https://www.pucp.edu.pe/climadecambios/noticias/los-impactos-de-las-sequias-en-el-peru/?utm_source=chatgpt.com)

Programa Subsectorial de Irrigaciones (PSI). (2009, abril). El Programa Subsectorial de Irrigaciones y la tecnificación del riego en el Perú. Ministerio de Agricultura. [https://repositorio.midagri.gob.pe/bitstream/20.500.13036/418/1/Riego%20tecnificado.pdf](https://repositorio.midagri.gob.pe/bitstream/20.500.13036/418/1/Riego%20tecnificado.pdf)

Ramos, E. (2025, septiembre 3). Tecnologías IoT buscan transformar la agricultura peruana. [Agraria.pe](http://Agraria.pe)

Rivadeneira, A. A. (2024). Avances y desafíos del ODS 2: Hambre cero [Presentación]. Foro de los Países de América Latina y el Caribe sobre el Desarrollo Sostenible 2024, CEPAL. [https://foroalc2030.cepal.org/2024/sites/foro2024/files/presentations/mesa_2-peru-rivadeneira-_ods_2_hambre_cero.pdf](https://foroalc2030.cepal.org/2024/sites/foro2024/files/presentations/mesa_2-peru-rivadeneira-_ods_2_hambre_cero.pdf)

Sociedad de Comercio Exterior del Perú. (2024, agosto 16). 1 de cada 5 peruanos padece de inseguridad alimentaria grave. [ComexPerú](https://www.comexperu.org.pe/articulo/1-de-cada-5-peruanos-padece-de-inseguridad-alimentaria-grave?utm_source=chatgpt.com)

United Nations University Institute for Water, Environment and Health. (s. f.). Expandir el riego podría mejorar la nutrición infantil, pero conlleva riesgos. [UNU-INWEH](https://unu.edu/inweh/collection/expandir-el-riego-podria-mejorar-la-nutricion-infantil-pero-conlleva-el-riesgo-de?utm_source=chatgpt.com)

# Anexos

**Anexo 1**

_Eficiencia y Costos de Métodos de Riego en el Perú_

|Método de Riego|Eficiencia de Aplicación|Costo de Inversión (US$/ha)|Predominancia en el Agro|
|:-:|:-:|:-:|:-:|
|Gravedad / Surcos|35%|400|~85% en la costa|
|Aspersión|75%|2,600 - 4,115|2%|
|Goteo (Presurizado)|90%|2,775|13%|

_Nota. Adaptado de Abastecimiento de agua para la agricultura en la costa, por J. Iberico (2016), Revista Moneda, (168), Banco Central de Reserva del Perú, [BCRP](https://www.bcrp.gob.pe/docs/Publicaciones/Revista-Moneda/moneda-168/moneda-168-07.pdf?utm_source=chatgpt.com)_

**Anexo 2**

_Indicadores de Salud y Seguridad Alimentaria (ODS 2 y 3)_

|Indicador|Valor (2022-2023)|Tendencia / Estado|
|:-:|:-:|:-:|
|Prevalencia de Anemia (niños < 3 años)|42.4%|Al alza (Incremento vs 2021)|
|Desnutrición Crónica Infantil|11.7%|Estancamiento|
|Incidencia de Déficit Calórico|36.2%|Al alza (era 23.9% en 2015)|
|Población Rural con Alta Inseguridad Alimentaria|> 70%|Crítica|

_Nota. Adaptado de Perú: Indicadores de Resultados de los Programas Presupuestales. Encuesta Demográfica y de Salud Familiar (ENDES) 2023, por el Instituto Nacional de Estadística e Informática (2024), [INEI](https://www.inei.gob.pe/?utm_source=chatgpt.com); de Sistema de monitoreo y seguimiento de los indicadores de los Objetivos de Desarrollo Sostenible, por el Instituto Nacional de Estadística e Informática (2023), [INEI ODS](https://ods.inei.gob.pe/ods/?utm_source=chatgpt.com); de El estado de la seguridad alimentaria y la nutrición en el mundo (SOFI) 2024, por la Organización de las Naciones Unidas para la Alimentación y la Agricultura (2024), [FAO SOFI](https://www.fao.org/publications/sofi/es/?utm_source=chatgpt.com); y de Índice Global del Hambre (IGH) 2024: Informe Perú, por el Centro Peruano de Estudios Sociales (2024), [CEPES](https://cepes.org.pe/?utm_source=chatgpt.com)._


# Links

Celevi. 2026. Github Repository for Crop Analysis Service. [https://github.com/CeleviGrotix/Grotix_Crop_Analysis](https://github.com/CeleviGrotix/Grotix_Crop_Analysis)

Celevi. 2026. Github Repository for Edge App. [https://github.com/CeleviGrotix/Grotix_Edge](https://github.com/CeleviGrotix/Grotix_Edge)

Celevi. 2026. Github Repository for Embedded App. [https://github.com/CeleviGrotix/Grotix_Embedded](https://github.com/CeleviGrotix/Grotix_Embedded)

Celevi. 2026. Github Repository for Grotix Landing Page. [https://github.com/CeleviGrotix/Grotix_LandingPage](https://github.com/CeleviGrotix/Grotix_LandingPage)

Celevi. 2026. Github Repository for Grotix Mobile Application. [https://github.com/CeleviGrotix/Grotix_Mobile](https://github.com/CeleviGrotix/Grotix_Mobile)

Celevi. 2026. Github Repository for Grotix Report. [https://github.com/CeleviGrotix/Grotix_IoT_Report](https://github.com/CeleviGrotix/Grotix_IoT_Report)

Celevi. 2026. Github Repository for Grotix Web Application. [https://github.com/CeleviGrotix/Grotix_Web](https://github.com/CeleviGrotix/Grotix_Web)

Celevi. 2026. Github Repository for Grotix Web Services. [https://github.com/CeleviGrotix/Grotix_Web_Services](https://github.com/CeleviGrotix/Grotix_Web_Services)

Celevi. 2026. Diagrama de Actividades y estados. [https://lucid.app/lucidchart/c8bcf184-0676-40f7-8347-263e3babf686/edit?view_items=SgYRUQgH.nII&page=0_0&invitationId=inv_3a2bf95b-b22a-4add-b99f-02d0ed853fee](https://lucid.app/lucidchart/c8bcf184-0676-40f7-8347-263e3babf686/edit?view_items=SgYRUQgH.nII&page=0_0&invitationId=inv_3a2bf95b-b22a-4add-b99f-02d0ed853fee)

Celevi. 2026. Diagrama de clase. [https://lucid.app/lucidchart/c28cc6bf-8486-4dbb-ba7f-a3210df48a5c/edit?viewport_loc=-3394%2C-1465%2C6925%2C3224%2C0_0&invitationId=inv_67cd59c7-5703-4cb1-8122-5312a9ed8259](https://lucid.app/lucidchart/c28cc6bf-8486-4dbb-ba7f-a3210df48a5c/edit?viewport_loc=-3394%2C-1465%2C6925%2C3224%2C0_0&invitationId=inv_67cd59c7-5703-4cb1-8122-5312a9ed8259)

Celevi. 2026. Diagrama de base de datos. [https://lucid.app/lucidchart/ecbadf35-cf2e-4657-9e6e-2cc36ad54304/edit?viewport_loc=-1240%2C-788%2C3271%2C1482%2C0_0&invitationId=inv_a764d72e-3f6f-41cc-9bb1-5cd2f9f05490](https://lucid.app/lucidchart/ecbadf35-cf2e-4657-9e6e-2cc36ad54304/edit?viewport_loc=-1240%2C-788%2C3271%2C1482%2C0_0&invitationId=inv_a764d72e-3f6f-41cc-9bb1-5cd2f9f05490)

Celevi. 2026. Esquemas realizados con UXPRESIA. [https://drive.google.com/drive/folders/1AcRLc0XIIurTc_4bcvQW3vW6aLwbFvW2?usp=sharing](https://drive.google.com/drive/folders/1AcRLc0XIIurTc_4bcvQW3vW6aLwbFvW2?usp=sharing)

Celevi. 2026. Grotix Diagrams. [https://upcedupe-my.sharepoint.com/:b:/g/personal/u202312287_upc_edu_pe/IQAn8hVFx5EfTb4P72xVU794AZD90knyfQ6wPBYvp6LSBL4?e=7EV2FV](https://upcedupe-my.sharepoint.com/:b:/g/personal/u202312287_upc_edu_pe/IQAn8hVFx5EfTb4P72xVU794AZD90knyfQ6wPBYvp6LSBL4?e=7EV2FV)

Celevi. 2026. Grotix EventStorming. [https://miro.com/welcomeonboard/RHE0Z0ZHYlYxSVU3Y0ozTjEya3JETTc1NzIyVmsyYy9UMHBEN0ovRUF2RDdEbjRQZFBpUEZ3a3lubXRFc0d1NzhHdkNvZUZHeElDWDFRc0lsZEVWUy9GYTVRRWtwZVF5enJyVlpZUzdXQmtYVUp1a2FIVXdESDJDVllXSEZYaXh3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=31489203478](https://miro.com/welcomeonboard/RHE0Z0ZHYlYxSVU3Y0ozTjEya3JETTc1NzIyVmsyYy9UMHBEN0ovRUF2RDdEbjRQZFBpUEZ3a3lubXRFc0d1NzhHdkNvZUZHeElDWDFRc0lsZEVWUy9GYTVRRWtwZVF5enJyVlpZUzdXQmtYVUp1a2FIVXdESDJDVllXSEZYaXh3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=31489203478)

Celevi. 2026. *Lean UX Canvas*. [https://docs.google.com/document/d/1v9oqi4oCp-7cLg5QIZMB1egRKy5mVaJw/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true](https://docs.google.com/document/d/1v9oqi4oCp-7cLg5QIZMB1egRKy5mVaJw/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true)

Celevi. 2026. Proyecto en Jira. [https://sacsayhuamanlover.atlassian.net/jira/software/projects/GTX/boards/2?atlOrigin=eyJpIjoiODViNjFlOWI0MjA5NDY1NzgyZWMyNDFjYzc1N2ZlNmIiLCJwIjoiaiJ9](https://sacsayhuamanlover.atlassian.net/jira/software/projects/GTX/boards/2?atlOrigin=eyJpIjoiODViNjFlOWI0MjA5NDY1NzgyZWMyNDFjYzc1N2ZlNmIiLCJwIjoiaiJ9)

Celevi. 2026. Segmento_1_As-Is/To-Be. [https://miro.com/app/board/uXjVGjm4oO4=/?share_link_id=832410871375](https://miro.com/app/board/uXjVGjm4oO4=/?share_link_id=832410871375)

Celevi. 2026. Segmento_2_As-Is/To-Be. [https://miro.com/app/board/uXjVJHVbkR8=/](https://miro.com/app/board/uXjVJHVbkR8=/)

Celevi. 2026. Sprint Backlog 2 en Jira. [https://cassiusmartel21042006-1776311272559.atlassian.net/jira/software/projects/GSB2/list?jql=project%20%3D%20GSB2%20ORDER%20BY%20cf%5B10019%5D%20ASC](https://cassiusmartel21042006-1776311272559.atlassian.net/jira/software/projects/GSB2/list?jql=project%20%3D%20GSB2%20ORDER%20BY%20cf%5B10019%5D%20ASC)

Celevi. 2026. Api gateway service. [https://grotixgateway1-hrftg6a4gqf0fqhd.chilecentral-01.azurewebsites.net/](https://grotixgateway1-hrftg6a4gqf0fqhd.chilecentral-01.azurewebsites.net/)

Celevi. 2026. Profile service. [http://grotixprofile-byc3drb9gqe9epev.chilecentral-01.azurewebsites.net/swagger/](http://grotixprofile-byc3drb9gqe9epev.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Cultivation area service. [http://grotixcultivationarea-c5d8hhd3c2defwda.chilecentral-01.azurewebsites.net/swagger/](http://grotixcultivationarea-c5d8hhd3c2defwda.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Hardware device service. [http://grotixhardware-dsfucydsavcyhffw.chilecentral-01.azurewebsites.net/swagger/](http://grotixhardware-dsfucydsavcyhffw.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Irrigation cycle service. [http://grotixirrigationcycle-enbkhfe7a4cye2cm.chilecentral-01.azurewebsites.net/swagger/](http://grotixirrigationcycle-enbkhfe7a4cye2cm.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Telemetry service. [http://grotixtelemetry-amakfshkb4ahbsbm.chilecentral-01.azurewebsites.net/swagger/](http://grotixtelemetry-amakfshkb4ahbsbm.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Web Application. [https://grotixweb.web.app/](https://grotixweb.web.app/)

Celevi. 2026. Execution evidence for sprint review 1. [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAX8Qlo6yS-TYuInq-CellWAQNakaunluneG2IIEWIgkZE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NXcnhZ](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAX8Qlo6yS-TYuInq-CellWAQNakaunluneG2IIEWIgkZE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NXcnhZ)

Celevi. 2026. Execution evidence for sprint review 2. [https://upcedupe-my.sharepoint.com/personal/u202311157_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202311157%5Fupc%5Fedu%5Fpe%2FDocuments%2FExecutionEvidenceAppWebSP2%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E7e736a7c%2D5e8a%2D4772%2Db375%2Dcddccb03b13d](https://upcedupe-my.sharepoint.com/personal/u202311157_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202311157%5Fupc%5Fedu%5Fpe%2FDocuments%2FExecutionEvidenceAppWebSP2%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E7e736a7c%2D5e8a%2D4772%2Db375%2Dcddccb03b13d)

Celevi. 2026. Diagrama de clase. [https://lucid.app/lucidchart/c28cc6bf-8486-4dbb-ba7f-a3210df48a5c/edit?viewport_loc=-3394%2C-1465%2C6925%2C3224%2C0_0&invitationId=inv_67cd59c7-5703-4cb1-8122-5312a9ed8259](https://lucid.app/lucidchart/c28cc6bf-8486-4dbb-ba7f-a3210df48a5c/edit?viewport_loc=-3394%2C-1465%2C6925%2C3224%2C0_0&invitationId=inv_67cd59c7-5703-4cb1-8122-5312a9ed8259)

Celevi. 2026. Diagrama de base de datos. [https://lucid.app/lucidchart/ecbadf35-cf2e-4657-9e6e-2cc36ad54304/edit?viewport_loc=-1240%2C-788%2C3271%2C1482%2C0_0&invitationId=inv_a764d72e-3f6f-41cc-9bb1-5cd2f9f05490](https://lucid.app/lucidchart/ecbadf35-cf2e-4657-9e6e-2cc36ad54304/edit?viewport_loc=-1240%2C-788%2C3271%2C1482%2C0_0&invitationId=inv_a764d72e-3f6f-41cc-9bb1-5cd2f9f05490)

Celevi. 2026. Esquemas realizados con UXPRESIA. [https://drive.google.com/drive/folders/1AcRLc0XIIurTc_4bcvQW3vW6aLwbFvW2?usp=sharing](https://drive.google.com/drive/folders/1AcRLc0XIIurTc_4bcvQW3vW6aLwbFvW2?usp=sharing)

Celevi. 2026. Grotix Diagrams. [https://upcedupe-my.sharepoint.com/:b:/g/personal/u202312287_upc_edu_pe/IQAn8hVFx5EfTb4P72xVU794AZD90knyfQ6wPBYvp6LSBL4?e=7EV2FV](https://upcedupe-my.sharepoint.com/:b:/g/personal/u202312287_upc_edu_pe/IQAn8hVFx5EfTb4P72xVU794AZD90knyfQ6wPBYvp6LSBL4?e=7EV2FV)

Celevi. 2026. Grotix EventStorming. [https://miro.com/welcomeonboard/RHE0Z0ZHYlYxSVU3Y0ozTjEya3JETTc1NzIyVmsyYy9UMHBEN0ovRUF2RDdEbjRQZFBpUEZ3a3lubXRFc0d1NzhHdkNvZUZHeElDWDFRc0lsZEVWUy9GYTVRRWtwZVF5enJyVlpZUzdXQmtYVUp1a2FIVXdESDJDVllXSEZYaXh3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=31489203478](https://miro.com/welcomeonboard/RHE0Z0ZHYlYxSVU3Y0ozTjEya3JETTc1NzIyVmsyYy9UMHBEN0ovRUF2RDdEbjRQZFBpUEZ3a3lubXRFc0d1NzhHdkNvZUZHeElDWDFRc0lsZEVWUy9GYTVRRWtwZVF5enJyVlpZUzdXQmtYVUp1a2FIVXdESDJDVllXSEZYaXh3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=31489203478)

Celevi. 2026. Lean UX Canvas. [https://docs.google.com/document/d/1v9oqi4oCp-7cLg5QIZMB1egRKy5mVaJw/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true](https://docs.google.com/document/d/1v9oqi4oCp-7cLg5QIZMB1egRKy5mVaJw/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true)

Celevi. 2026. Proyecto en Jira. [https://sacsayhuamanlover.atlassian.net/jira/software/projects/GTX/boards/2?atlOrigin=eyJpIjoiODViNjFlOWI0MjA5NDY1NzgyZWMyNDFjYzc1N2ZlNmIiLCJwIjoiaiJ9](https://sacsayhuamanlover.atlassian.net/jira/software/projects/GTX/boards/2?atlOrigin=eyJpIjoiODViNjFlOWI0MjA5NDY1NzgyZWMyNDFjYzc1N2ZlNmIiLCJwIjoiaiJ9)

Celevi. 2026. Segmento_1_As-Is/To-Be. [https://miro.com/app/board/uXjVGjm4oO4=/?share_link_id=832410871375](https://miro.com/app/board/uXjVGjm4oO4=/?share_link_id=832410871375)

Celevi. 2026. Segmento_2_As-Is/To-Be. [https://miro.com/app/board/uXjVJHVbkR8=/](https://miro.com/app/board/uXjVJHVbkR8=/)

Celevi. 2026. Sprint Backlog 2 en Jira. [https://cassiusmartel21042006-1776311272559.atlassian.net/jira/software/projects/GSB2/list?jql=project%20%3D%20GSB2%20ORDER%20BY%20cf%5B10019%5D%20ASC](https://cassiusmartel21042006-1776311272559.atlassian.net/jira/software/projects/GSB2/list?jql=project%20%3D%20GSB2%20ORDER%20BY%20cf%5B10019%5D%20ASC)

Celevi. 2026. Api gateway service. [https://grotixgateway1-hrftg6a4gqf0fqhd.chilecentral-01.azurewebsites.net/](https://grotixgateway1-hrftg6a4gqf0fqhd.chilecentral-01.azurewebsites.net/)

Celevi. 2026. Profile service. [grotixprofile-byc3drb9gqe9epev.chilecentral-01.azurewebsites.net/swagger/](http://grotixprofile-byc3drb9gqe9epev.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Cultivation area service. [grotixcultivationarea-c5d8hhd3c2defwda.chilecentral-01.azurewebsites.net/swagger/](http://grotixcultivationarea-c5d8hhd3c2defwda.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Hardware device service. [grotixhardware-dsfucydsavcyhffw.chilecentral-01.azurewebsites.net/swagger/](http://grotixhardware-dsfucydsavcyhffw.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Irrigation cycle service. [grotixirrigationcycle-enbkhfe7a4cye2cm.chilecentral-01.azurewebsites.net/swagger/](http://grotixirrigationcycle-enbkhfe7a4cye2cm.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. [Telemetry service. grotixtelemetry-amakfshkb4ahbsbm.chilecentral-01.azurewebsites.net/swagger/](http://grotixirrigationcycle-enbkhfe7a4cye2cm.chilecentral-01.azurewebsites.net/swagger/)

Celevi. 2026. Web Application. [https://grotixweb.web.app/](https://grotixweb.web.app/)

Celevi. 2026. Execution evidence for sprint review 1. [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAX8Qlo6yS-TYuInq-CellWAQNakaunluneG2IIEWIgkZE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NXcnhZ](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/IQAX8Qlo6yS-TYuInq-CellWAQNakaunluneG2IIEWIgkZE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NXcnhZ)



Celevi. 2026. Execution evidence for sprint review 2. [https://upcedupe-my.sharepoint.com/personal/u202311157_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202311157%5Fupc%5Fedu%5Fpe%2FDocuments%2FExecutionEvidenceAppWebSP2%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E7e736a7c%2D5e8a%2D4772%2Db375%2Dcddccb03b13d](https://upcedupe-my.sharepoint.com/personal/u202311157_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202311157%5Fupc%5Fedu%5Fpe%2FDocuments%2FExecutionEvidenceAppWebSP2%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E7e736a7c%2D5e8a%2D4772%2Db375%2Dcddccb03b13d)

Celevi. 2026. Execution evidence for sprint review 3. [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQBqqDaRVN_WTI7RI66FiEDMAVw31SzkDuJa26C5sPOLgR0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=xeDbE9](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQBqqDaRVN_WTI7RI66FiEDMAVw31SzkDuJa26C5sPOLgR0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=xeDbE9)

Celevi. 2026. About-the-product. [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQB_rO1R__CXRrOb6dEIM27bASKboXi3LUS6jOZnjuvsrRo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1btASA](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202312287_upc_edu_pe/IQB_rO1R__CXRrOb6dEIM27bASKboXi3LUS6jOZnjuvsrRo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1btASA)
