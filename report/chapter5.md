# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
En esta sección, se incluirá los productos de software que se usaron en el proyecto.

Se clasificará en el siguiente orden:
- Producto UX/UI Design.
- Software Development.
- Software Deployment.

**Producto UX/UI Design:**<br>
- [Figma](https://www.figma.com/) - Herramienta de diseño colaborativo para crear prototipos y maquetas de interfaces de usuario.
- [Lucidchart](https://lucid.app/) - Herramienta de diagramación para crear diagramas de flujo, wireframes y otros elementos visuales.
- [Uxpressia](https://uxpressia.com/) - Herramienta de diseño centrada en el usuario para crear mapas de empatía y customer journey maps.
- [Structurizr](https://structurizr.com/) - Herramienta de modelado de software para crear diagramas de arquitectura y diseño orientado a dominios.
- [Miro](https://miro.com/) - Plataforma de pizarra colaborativa en línea que permite a equipos trabajar juntos en tiempo real para crear mapas mentales, flujos de usuarios y planificaciones de producto.
- [Vertabelo](https://vertabelo.com/) - Herramienta de modelado de bases de datos que permite diseñar esquemas visuales, generar scripts SQL y colaborar en tiempo real con tu equipo.
- [Trello](https://trello.com/) - Herramienta visual de gestión de proyectos basada en tableros y tarjetas que facilita la organización, seguimiento y colaboración en tareas dentro de equipos de trabajo.

**Software Development:**<br>
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Entorno de desarrollo integrado (IDE) para Java y otros lenguajes de programación.
- [Github](https://www.github.com/) - Plataforma de control de versiones y colaboración para el desarrollo de software.
- [Visual Studio Code](https://code.visualstudio.com/) - Editor de código fuente ligero y potente para varios lenguajes de programación.
- [HTML](https://www.w3.org/TR/html52/) - Lenguaje de marcado para la creación de páginas web.
- [CSS](https://www.w3.org/Style/CSS/) - Lenguaje de estilo para la presentación de documentos HTML.
- [CodeSandBox](https://codesandbox.io/) = Entorno de desarrollo en línea que permite crear, editar y desplegar rápidamente proyectos web, ideal para construir y probar landing pages de forma colaborativa y sin necesidad de configuración local.

**Software Deployment:**<br>
- GitHub Pages - Servicio de alojamiento web para proyectos estáticos.

### 5.1.2. Source Code Management

Para la gestión del código fuente, se utilizará GitHub como plataforma central de control de versiones y colaboración entre los miembros del equipo. Se han creado repositorios separados para los distintos productos del proyecto.
Los enlaces también están disponibles en la sección de anexos.

- **Organización en GitHub:** [https://github.com/wasd25](https://github.com/wasd25)
- **Repositorio del informe:** [https://github.com/wasd25/final-report](https://github.com/wasd25/final-report)
- **Repositorio de la Landing Page:** [https://github.com/wasd25/landing-page](https://github.com/wasd25/landing-page)

#### Modelo de ramificación: GitFlow

Para el modelo de desarrollo, se decidió usar GitFlow como modelo de ramificación. Este modelo permite una gestión eficiente de las ramas y facilita la colaboración entre los desarrolladores.

Para el repositorio del informe se crearon las siguientes ramas:
- **main:** Rama principal de desarrollo, donde se integrarán todas las características y correcciones de errores.
- **chapter-1:** Rama para el desarrollo del capítulo 1 del informe.
- **chapter-2:** Rama para el desarrollo del capítulo 2 del informe.
- **chapter-3:** Rama para el desarrollo del capítulo 3 del informe.
- **chapter-4:** Rama para el desarrollo del capítulo 4 del informe.
- **chapter-5:** Rama para el desarrollo del capítulo 5 del informe.

Para el repositorio de Landing Page se crearon las siguientes ramas:

- Features
1. header
2. hero
3. about-us
4. solutions
5. subscriptions
6. contact-sales
7. faq
8. footer

#### Estilo de commits: Conventional Commits
Para asegurar mensajes de commits claros y estandarizados, se seguirá la convención [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). Algunos ejemplos:

- feat: add search by name functionality
- fix: correct form validation error
- docs: update installation instructions
- refactor: simplify calculation logic

El prefijo de categorías se define de la siguiente forma:
- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (formatting, missing semicolons, etc.)
- refactor: A code change that neither fixes a bug nor adds a feature
- test: Adding missing tests or correcting existing ones
- chore: Changes to the build process or auxiliary tools

### 5.1.3. Source Code Style Guide & Conventions

En esta sección se definen las convenciones de nombres y codificación adoptadas por el equipo para los lenguajes utilizados en el proyecto: HTML, CSS, JavaScript, TypeScript y Java. El idioma estándar para todo el código (nombres de variables, funciones, clases, archivos, etc.) es el **inglés**.

#### Principios generales

- **Idioma estándar:** Todo el código fuente está escrito en inglés, incluyendo nombres de archivos, clases, variables y funciones.
- **Legibilidad ante todo:** Se prioriza el uso de nombres descriptivos y claros por encima de abreviaciones o tecnicismos innecesarios.
- **Formato consistente:** Se aplica un estilo uniforme en todo el equipo y en todos los lenguajes, reforzado por herramientas automáticas.
- **Nombres semánticos:** Se usan **sustantivos** para clases, componentes y archivos, y **verbos** para funciones o métodos.
- **Indentación:** 2 espacios para HTML, CSS, JS y TS. 4 espacios para Java.

#### HTML y CSS

**HTML**
- Archivos terminan en `.html`.
- Se utilizan etiquetas semánticas como `<header>`, `<section>`, `<nav>`, `<footer>`, etc.
- Se incluye `alt` en imágenes y atributos `aria-*` para accesibilidad.
- Atributos con comillas dobles (`"`).
- Se usa `camelCase` para ID's y `kebab-case` para clases.
- Indentación: 2 espacios.

**CSS**
- Archivos terminan en `.css`.
- Se usa `kebab-case` para nombres de clases y archivos: `main-header`, `product-card`, `login-form`.
- Se agrupan estilos relacionados y se separan con comentarios.

#### JavaScript y TypeScript

- Archivos terminan en `.js` o `.ts`.
- Se usa `camelCase` para variables y funciones: `userName`, `getUserData()`.
- Se usa `PascalCase` para clases y componentes: `UserProfile`, `LoginForm`.
- Se prefiere `const` y `let` en lugar de `var`.
- Se prefieren funciones flecha (`=>`) y nombres explícitos.
- Cada archivo debe tener una única responsabilidad o componente.

Basado en:
- [Guía de estilo TypeScript de Google](https://google.github.io/styleguide/tsguide.html)
- [Guía de estilo JavaScript de Airbnb](https://github.com/airbnb/javascript)


#### Java

- Archivos terminan en `.java`.
- Clases con `PascalCase`: `UserService`, `OrderController`.
- Métodos y variables con `camelCase`: `getUserById()`, `userEmail`.
- Constantes con `UPPER_SNAKE_CASE`: `MAX_ATTEMPTS`.
- Una clase pública por archivo.
- Se documentan métodos y clases públicas con JavaDoc.

Basado en:
- [Guía de estilo Java de Google](https://google.github.io/styleguide/javaguide.html)
- [Buenas prácticas de Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)

### 5.1.4. Software Deployment Configuration

En esta sección se describe la configuración necesaria para desplegar cada uno de los componentes del proyecto: Landing Page, Web Services y Frontend Web Application. El objetivo es garantizar que, a partir del código fuente almacenado en los repositorios, se pueda lograr una publicación funcional y accesible para los usuarios.

#### Despliegue de Landing Page

La **Landing Page** fue desarrollada usando HTML y CSS, y fue desplegada mediante **GitHub Pages**, un servicio gratuito de hosting para sitios estáticos.

**Pasos de despliegue:**
1. Se creó el repositorio `landing-page` en GitHub.
2. Se subió el código fuente HTML, CSS y recursos estáticos.
3. Desde la configuración del repositorio, se activó **GitHub Pages** seleccionando la rama `main` y la carpeta raíz (`/`).
4. Automáticamente, GitHub publicó el sitio web en una URL pública.

**Repositorio:** [https://github.com/wasd25/landing-page](https://github.com/wasd25/landing-page)<br>
**URL desplegada:** []()

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

A continuación, se presentará el sprint planning 1 donde se mostrarán las evidencias de planificación e implementación del landing page.

| Campo                    | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint #                 | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Date                     | 28/08/2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Time                     | 6:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Location                 | Google Meet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Prepared by              | Pedro Andre Guia Carrasco                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Attendees (to meeting)   | - Ayrton Briceno <br> - Mateo Loechle  <br> - Anyelo Alejos <br> - Jafeth Ynga                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Sprint 1 Review Summary  | Este fue el primer sprint realizado por el equipo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Sprint 1 Retrospective Summary                         | Se acordó implementar una primera versión funcional de la Landing Page del sistema Qlic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Sprint 1 Goal                         | Nos enfocamos en implementar la Landing Page de Qlic con una arquitectura sólida basada en HTML, CSS y JavaScript, priorizando la adaptabilidad a distintos dispositivos y una navegación consistente. Creemos que esto permitirá comunicar efectivamente el propósito del sistema, facilitar el acceso a la información clave y sentar las bases técnicas para evoluciones posteriores del proyecto. Creemos que esto permitirá comunicar efectivamente el propósito del sistema, facilitar el acceso a la información clave y sentar las bases técnicas para evoluciones posteriores del proyecto. |
| Sprint 1 Velocity                         | 8                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Sum of Story Points                        | 8                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

#### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Landing Page (L/C) | Documentation (L/C) | Epics (L/C) |
|-------------------------------------|-----------------|--------------------|---------------------|-------------|
| Guia Carrasco, Pedro Andre          | Pedrivizz       | C                  | C                   | L           |
| Briceño Llanos, Ayrton Omar         | AyrtonBriceno   | C                  | L                   | C           |
| Loechle Arias, Mateo Ítalo          | LowMathzzz                | C                  | C                   | C           |
| Ynga Amado, Jafeth Worren           | Jafeth-MV                | L                  | C                   | C           |
| Alejos Jesus, Anyelo Bill                      | Everkoe                | C                  | C                   | C           |


#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones
Durante el proceso de creación y desarrollo de este trabajo pudimos llegar a las siguientes conclusiones:

### 1. Trabajo en equipo y colaboración
El éxito de este proyecto demuestra la importancia del trabajo en equipo y la colaboración efectiva entre los miembros del grupo.
La sinergia, comunicación constante y distribución de roles permitieron integrar diferentes perspectivas y habilidades, 
logrando un desarrollo más robusto y eficiente.

### 2. Planificación y organización en el desarrollo de software
Una adecuada planificación y organización fueron clave para el cumplimiento de los objetivos del proyecto. 
La metodología empleada (como Agile o SCRUM) facilitó la gestión de tareas, la priorización de funcionalidades y la entrega 
de resultados en los tiempos establecidos, asegurando un producto de calidad.

### 3. Tecnología y herramientas aplicadas a las realidad
El uso de tecnologías modernas y herramientas innovadoras permitió desarrollar una solución alineada con las necesidades 
reales del sector. La integración de frameworks ágiles, bases de datos eficientes y sistemas en la nube garantizó un producto
escalable, seguro y adaptable al contexto peruano.

### 4. Solución rentable y sostenible contra el desperdicio alimentario
Este proyecto se consolida como una solución rentable y sostenible para reducir el desperdicio de alimentos en Perú, 
especialmente en el sector restaurantero. Al conectar a establecimientos con consumidores, se optimiza el uso de excedentes, 
generando un impacto económico, social y ambiental positivo.


# Bibliografía


- Conne, M(2024). _The Markdown Guide_. MarkdownGuide. Recuperado de: https://www.markdownguide.org/

- Conventional Commits. (n.d.). *Conventional commits v1.0.0.* Retrieved from https://www.conventionalcommits.org/en/v1.0.0/

- BrowserStack. (n.d.). Responsive Web Design: A Complete Guide. Recuperado de https://www.browserstack.com/guide/responsive-web-design

- Spring Boot. (n.d.). Spring Boot Documentation. Retrieved from https://docs.spring.io/spring-boot/documentation.html#documentation.web

- Modyo. (n.d.). Domain-Driven Design (DDD) - Patrones de arquitectura. Retrieved from https://docs.modyo.com/es/architecture/patterns/ddd.html

- Pivotal Software (2024). Spring Boot Reference Documentation (v3.2.4). https://docs.spring.io/spring-boot/docs/current/reference/html/

- Evans, E. (2004). Domain-Driven Design: Tackling Complexity in the Heart of Software. Addison-Wesley. https://www.domainlanguage.com/ddd/

- Eser, A. (2025, 30 de mayo). *Marketing in the Water Industry Statistics*. ZipDo Education Reports. Recuperado de https://zipdo.co/marketing-in-the-water-industry-statistics/

- América Noticias. (2025). *Sunass: cierre de brechas en agua y saneamiento requiere cerca de 95 mil millones inversión*. América TV. Recuperado de https://www.americatv.com.pe/noticias/actualidad/sunass-cierre-brechas-agua-y-saneamiento-requiere-cerca-s-95-mil-millones-inversion-n468439

- Ministerio de Vivienda, Construcción y Saneamiento. (2024, 9 de agosto). *Más de 500 mil peruanos accederán a servicios de agua potable y saneamiento con obras que el Ministerio de Vivienda concluirá al 2025*. Gobierno del Perú. Recuperado de https://www.gob.pe/institucion/vivienda/noticias/1000795-mas-de-500-mil-peruanos-accederan-a-servicios-de-agua-potable-y-saneamiento-con-obras-que-el-ministerio-de-vivienda-concluira-al-2025

# Anexos

### VIDEOS:

| Título                  | Descripción                                        | Enlace |
|-------------------------|----------------------------------------------------|--------|
| Video de exposición TB1 | Video explicativo de los avances de la entrega TB1 |        |
| Video de entrevistas    | Video recopilatorio de todas las entrevistas       |        |



### UX/UI
| Título | Descripción                                                                                                | Enlace                       |
|--------|------------------------------------------------------------------------------------------------------------|------------------------------|
| Figma  | Enlace hacia el documento de Figma con todos los diseños planteados para tanto Frontend como Landing Page. | https://acortar.link/4gd758  | 

### GITHUB

| Título       | Descripción                            | Enlace                                 |
|--------------|----------------------------------------|----------------------------------------|
| Reporte      | Enlace al repositorio del reporte      | https://github.com/wasd25/final-report |
| Landing Page | Enlace al repositorio del Landing Page | https://github.com/wasd25/landing-page |