![upc logo .png](../../assets/chapter1/upc%20logo%20.png)

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## Carrera: Ingeniería de Software
## Aplicaciones Web - Presencial
## PROFESOR: Rafael Castro
## NRC: 7470
## INFORME TB1
## START UP: WASD
## PRODUCTO: Qlic

### INTEGRANTES:

<table>
  <thead>
    <tr>
      <th style="background-color: #333; color: #fff;">Apellidos y Nombres</th>
      <th style="background-color: #333; color: #fff;">Código de Alumno</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jafeth Worren, Ynga Amado</td>
      <td>u202314715</td>
    </tr>
    <tr>
      <td>Loechle Arias, Mateo Ítalo</td>
      <td>u202215004</td>
    </tr>
    <tr>
      <td>Guia Carrasco, Pedro Andre</td>
      <td>u202212010</td>
    </tr>
    <tr>
      <td>Briceño Llanos, Ayrton Omar</td>
      <td>u202311077</td>
    </tr>
    <tr>
      <td>Anyelo Bill, Alejos Jesus</td>
      <td>u20231d149</td>
    </tr>
  </tbody>
</table>

--- 

Ciclo 2025-20

# Registro de versiones del informe

| Versión | Fecha      | Autor                       | Descripción de modificación                                                                            |
|---------|------------|-----------------------------|--------------------------------------------------------------------------------------------------------|
| 1.1     | 28/08/2025 | Briceño Llanos, Ayrton Omar | Creación del documento de trabajo en formato markdown.                                                 |
| 1.2     | 29/08/2025 | Briceño Llanos, Ayrton Omar | Redacción del startup profile y solution profile, delimitación de segmentos objetivo.                  |
| 1.3     | 2/09/2025  | Anyelo Bill, Alejos Jesus   | Elaboración y registro de entrevistas a segmentos objetivo, análisis de entrevistas.                   |
| 1.4     | 4/09/2025  | Briceño Llanos, Ayrton Omar | Elaboración de user personas, impact mapping, to-be, redacción de conclusiones, bibliografía y anexos. |
| 1.5     | 5/09/2025  | Anyelo Bill, Alejos Jesus   | Elaboración de user stories y epics.                                                                   |
| 1.6     | 8/09/2025  | Guia Carrasco, Pedro Andre  | Elaboración de diagramas de contenedores, diagramas de contexto, diagramas de componentes.             |
| 1.7     | 11/09/2025 | Guia Carrasco, Pedro Andre  | Registro de evidencias del Sprint 1.                                                                   |
| 1.8     | 12/09/2025 | Jafeth Worren, Ynga Amado   | Diseño de mockups, elaboración de wire-flows y user-flows para la landing page.                        |
| 1.9     | 13/09/2025 | Guia Carrasco, Pedro Andre  | Elaboración de diagrama de base de datos,diagrama de clases, diccionario de clases.                    |
| 1.10    | 15/09/2025 | Jafeth Worren, Ynga Amado   | Despliegue de la landing page.                                                                         |
| 1.11    | 15/09/2025 | Loechle Arias, Mateo Ítalo  | Diseño de wireframes y mockups de la aplicacion web.                                                   |

# Project Report Collaboration Insights

#### Repositorio del informe del proyecto
El informe del proyecto se encuentra alojado en el siguiente repositorio de la organización de GitHub del equipo:

🔗 Enlace del repositorio: https://github.com/wasd25/final-report

A continuación, se detallan las actividades realizadas en cada entrega, la participación de los miembros del equipo, y las evidencias correspondientes.

#### Desarrollo del informe
Para la primera entrega (TB1) se trabajó en la estructura inicial del informe, definiendo el índice y distribuyendo las secciones entre los miembros.

##### Evidencia de colaboración
(IMAGEN CON INSIGHTS)

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-Ubiquitous-language)
### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
        - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
        - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
        - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
        - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)


# Student Outcome

ABET – EAC - Student Outcome 3

Se refiere a la capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

| Criterio específico                                                   | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.  | **TB1:** <br><br/> **Ayrton Briceño:** Durante el trabajo parcial, participé activamente en la elaboración del informe y en la coordinación general del equipo. Me aseguré de comunicar por escrito de manera clara las ideas, hallazgos y descripciones requeridas en el informe, adaptando el lenguaje para que fuera comprensible tanto para los miembros del equipo como para lectores externos. Además, durante las reuniones virtuales por Discord, compartí observaciones clave sobre las necesidades de los usuarios entrevistados y propuse ajustes en las tareas asignadas, fomentando el consenso mediante una comunicación oral directa y efectiva. Esta experiencia fortaleció mi capacidad para transmitir ideas con claridad y adaptar el mensaje a distintos públicos, tanto en contextos escritos como orales. <br><br> **TB1: Mateo Loeche:** Complementé la comunicación del equipo al participar en las reuniones virtuales, aportando sugerencias para optimizar la presentación de ideas y colaborando en la clarificación de conceptos técnicos durante las discusiones. <br/> <br>**Pedro Guía:** Participé activamente en las reuniones virtuales del equipo, compartiendo ideas y proponiendo mejoras en la estructura de nuestras presentaciones. Además, apoyé en la explicación de temas técnicos para asegurar que todos comprendieran los conceptos clave y se mantuviera una comunicación efectiva. <br><br/> **Anyelo Alejos:** Durante el desarrollo del proyecto, me encargué de organizar y redactar varias secciones clave como los antecedentes, el análisis de entrevistas y los escenarios de usuario. Me enfoqué en que todo estuviera claro y bien estructurado, usando un lenguaje sencillo pero preciso para que cualquier persona pudiera entenderlo. También participé en reuniones virtuales donde compartí ideas sobre cómo mejorar los mapas de usuario y cómo presentar los resultados de forma más visual. Propuse ajustes en el estilo del informe y ayudé a definir cómo explicar los conceptos técnicos sin que suenen complicados. Esta experiencia me ayudó a mejorar mi forma de comunicarme, tanto al hablar como al escribir, adaptando el mensaje según el público y el objetivo de cada parte del trabajo. <br><br/>| Adaptamos nuestra forma de comunicarnos según el perfil de la audiencia, utilizando códigos y recursos adecuados para asegurar la correcta transmisión del mensaje. Empleamos medios audiovisuales pertinentes al contenido presentado, y verificamos constantemente que la comunicación haya sido clara y efectiva. Durante la presentación de resultados, orientamos nuestro discurso hacia los objetivos específicos, garantizando la comprensión del mensaje. Además, practicamos la escucha activa y objetiva antes de emitir juicios, promoviendo siempre el diálogo y la conciliación.                                   |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | **TB1:** <br><br/> **Ayrton Briceño:** En esta entrega, puse en práctica mis habilidades de comunicación escrita al coordinar eficazmente con mis compañeros mediante plataformas como WhatsApp. Asimismo, contribuí activamente en la elaboración de los documentos compartidos, asegurando una redacción clara y coherente. Estas acciones me ayudaron a mantener una comunicación constante con el equipo y a reforzar la organización general del trabajo. <br><br> **Mateo Loeche:** Aporté en la redacción y revisión de los documentos finales, cuidando la claridad, cohesión y ortografía, además de verificar que la información transmitida se ajustara al público objetivo. </br> <br> **Pedro Guía:** En este trabajo, me enfoqué en mantener una comunicación fluida con el equipo, facilitando la resolución de dudas y organizando la información necesaria para cumplir con los objetivos planteados. <br><br/> **Anyelo Alejos:** En esta entrega, participé en la redacción de secciones como el análisis de entrevistas, escenarios de usuario y guías de estilo. Me aseguré de que el contenido fuera claro y fácil de entender, evitando tecnicismos innecesarios. También colaboré en la revisión del informe completo para mantener una estructura coherente y un lenguaje uniforme. Usamos herramientas como Google Docs y WhatsApp para coordinar los aportes, lo que permitió mantener una comunicación constante y una buena organización del trabajo. <br><br/>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Elaboramos informes técnicos siguiendo los estándares establecidos para el desarrollo de proyectos de ingeniería, asegurando la calidad del contenido antes de su entrega. Nos esforzamos por transmitir ideas y conceptos clave de forma clara y empática, adaptando el nivel de detalle y el lenguaje escrito a las características del público, independientemente de su especialidad o jerarquía. Seleccionamos de manera cuidadosa los medios y formatos más adecuados para facilitar la comprensión del mensaje, y verificamos sistemáticamente que todos los atributos de calidad estén presentes antes de la presentación final.  |
