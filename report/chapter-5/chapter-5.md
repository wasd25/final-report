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
- **Repositorio del informe:** [https://github.com/wasd25/final-report-2](https://github.com/wasd25/final-report-2)
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
9. product

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
- **Indentación:** 2 espacios para HTML, CSS, JS.

#### HTML y CSS

**HTML**
- Archivos terminan en `.html`.
- Se utilizan etiquetas semánticas como `<header>`, `<section>`, `<nav>`, `<footer>`, etc.
- Se incluye `alt` en imágenes y atributos `aria-*` para accesibilidad.
- Atributos con comillas dobles (`"`).
- Indentación: 2 espacios.

**CSS**
- Archivos terminan en `.css`.
- Los selectores y clases se nombran en minúsculas y guiones medios `.form-container`, `.btn-enviar`.
- Se agrupan estilos relacionados y se separan con comentarios.
- Se define una paleta de colores base en variables CSS para mantener consistencia.

#### JavaScript

**JS**
- Archivos terminan en `.js`.
- Las variables se escriben en minúsculas con guiones bajos: `datos_usuario`, `correo_valido`.
- Se evita el uso de var y let, priorizando const para mayor seguridad.
- Se emplea indentación de 4 espacios para bloques de código.
- Se prefiere la declaración explícita de funciones en lugar de funciones flecha para mayor legibilidad

Basado en:
- [Guía de estilo JavaScript de Airbnb](https://github.com/airbnb/javascript)

### 5.1.4. Software Deployment Configuration

En esta sección se describe la configuración necesaria para desplegar cada uno de los componentes del proyecto: Landing Page, Web Services y Frontend Web Application. El objetivo es garantizar que, a partir del código fuente almacenado en los repositorios, se pueda lograr una publicación funcional y accesible para los usuarios.

#### Despliegue de Landing Page

La **Landing Page** fue desarrollada usando HTML, CSS y JS, y fue desplegada mediante **GitHub Pages**, un servicio gratuito de hosting para sitios estáticos.

**Pasos de despliegue:**
1. Se creó el repositorio `landing-page` en GitHub.
2. Se subió el código fuente HTML, CSS y recursos estáticos.
3. Desde la configuración del repositorio, se activó **GitHub Pages** seleccionando la rama `main` y la carpeta raíz (`/`).
4. Automáticamente, GitHub publicó el sitio web en una URL pública.

**Repositorio:** [https://github.com/wasd25/landing-page](https://github.com/wasd25/landing-page)<br>
**URL desplegada:** [https://wasd25.github.io/landing-page/](https://wasd25.github.io/landing-page/)<br>

## 5.2. Landing Page, Services & Applications Implementation

En esta sección se detalla y evidencia la implementación de cada entregable de Qlic.

**Landing page:** La landing page fue realizada de manera grupal y desplegada debidamente con la herramienta GitHub Pages.
A continuación las siguientes imágenes sirven de referencia para evidenciar la implementación de la Landing Page.

![landing1.jpg](../../assets/chapter-5/landing1.jpg)
![landing2.jpg](../../assets/chapter-5/landing2.jpg)
![landing3.jpg](../../assets/chapter-5/landing3.jpg)
![landing4.jpg](../../assets/chapter-5/landing4.jpg)
![landing5.jpg](../../assets/chapter-5/landing5.jpg)
![landing6.jpg](../../assets/chapter-5/landing6.jpg)
![landing7.jpg](../../assets/chapter-5/landing7.jpg)
![landing8.jpg](../../assets/chapter-5/landing8.jpg)
![landing9.jpg](../../assets/chapter-5/landing9.jpg)

### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

A continuación, se presentará el sprint planning 1 donde se mostrarán las evidencias de planificación e implementación del landing page.

<table>
<tr>
    <th colspan="5">Sprint 1</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-09-18</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">12:08 PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Zoom</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Guía Carrasco Pedro Andre</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Ayrton Omar Briceño Llanos, Loechle Arias Mateo Ítalo, Guia Carrasco Pedro Andre, Jafeth Worren, Ynga Amado, Anyelo Bill, Alejos Jesus.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Review Summary</td>
    <td colspan="8">En este primer sprint se asignaron responsabilidades a cada integrante y se planteó los requerimientos para el desarrollo de la Landing Page.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">En esta sección todos los integrantes mencionaron tener aciertos en partes del código y en otras partes poder mejorar sus habilidades realizando la Landing Page</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Goal</td>
    <td colspan="8">
Nos centramos en desarrollar y desplegar una landing page que presente información a los usuarios a través de imágenes y datos. Creemos que la página debe ser completamente adaptable a cualquier tipo de dispositivo que utilicen los usuarios. El éxito de este sprint se confirmará cuando garanticemos una experiencia de usuario fluida y responsiva.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Velocity</td>
    <td colspan="8">
8</td>
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">
8</td>
</tr>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | GitHub Username | Landing Page (L/C) | Documentation (L/C) | Epics (L/C) |
|-------------------------------------|-----------------|--------------------|---------------------|-------------|
| Guia Carrasco, Pedro Andre          | Pedrivizz       | C                  | C                   | L           |
| Briceño Llanos, Ayrton Omar         | AyrtonBriceno   | C                  | L                   | C           |
| Loechle Arias, Mateo Ítalo          | LowMathzzz                | C                  | C                   | C           |
| Ynga Amado, Jafeth Worren           | Jafeth-MV                | L                  | C                   | C           |
| Alejos Jesus, Anyelo Bill                      | Everkoe                | C                  | C                   | C           |


#### 5.2.1.3. Sprint Backlog 1

En esta sección se muestra las tareas que se realizaron en el sprint 1, se adjunta la captura del tablero y el link. Link del tablero:

https://trello.com/invite/b/68b32abbe82181450f7bac82/ATTI10b281445d67389941f4f6ffbdd6e4385B21C1B4/sprint-1

![trello.jpg](../../assets/chapter-5/trello.jpg)

| Id   | Title                         | Id   | Title                        | Description                                                                 | Estimation (Hours) | Assigned To | Status (To-do/In-Process/To-Review/Done) |
|------|-------------------------------|------|------------------------------|-----------------------------------------------------------------------------|--------------------|-------------|------------------------------------------|
| US01 | Descripción clara del producto | T01  | Crear sección "¿Qué es Qlic?" | Diseñar e implementar la sección que describe el producto en la landing page | 5                  | Mateo       | Done                                     |
| US01 | Descripción clara del producto | T02  | Redactar contenido            | Redactar texto claro y conciso sobre Qlic y su propuesta de valor           | 5                  | Mateo       | Done                                     |
| US02 | Soluciones por segmento       | T03  | Diseñar sección de soluciones | Diseñar UI para mostrar soluciones para residenciales y PYMES                | 3                  | Jafeth      | Done                                     |
| US02 | Soluciones por segmento       | T04  | Implementar lógica por segmento| Implementar lógica para filtrar soluciones según el segmento seleccionado   | 4                  | Jafeth      | Done                                     |
| US03 | Monitoreo en Tiempo Real      | T05  | Diseñar panel de monitoreo    | Crear diseño inicial para visualizar datos IoT en tiempo real                | 5                  | Mateo       | Done                                  |
| US03 | Monitoreo en Tiempo Real      | T06  | Integración de datos IoT      | Conectar datos simulados para mostrar información en el panel                | 5                  | Mateo       | Done                                   |
| US04 | Seguimiento de presión        | T07  | Crear módulo de presión       | Desarrollar componente para visualizar y registrar datos de presión          | 5                  | Mateo       | Done                                    |
| US05 | Control de temperatura        | T08  | Crear módulo de temperatura   | Desarrollar componente para mostrar la temperatura en tiempo real            | 5                  | Mateo       | Done                                    |
| US06 | Gestión de volumen            | T09  | Crear módulo de volumen       | Desarrollar componente para visualizar niveles de volumen                    | 5                  | Mateo       | Done                                    |
| US07 | Ver y selección de planes     | T10  | Diseñar página de planes      | Crear diseño visual para la sección de planes de suscripción                 | 6                  | Jafeth       | Done                                    |
| US07 | Ver y selección de planes     | T11  | Implementar lógica de selección| Permitir la selección de un plan desde la interfaz                          | 8                  | Jafeth       | Done                                    |
| US08 | Ver preguntas frecuentes (FAQ)| T12  | Crear sección FAQ             | Desarrollar sección de preguntas frecuentes con contenido inicial            | 4                  | Jafeth       | Done                                    |
| US09 | Contactar ventas              | T13  | Implementar formulario contacto| Crear formulario funcional para contacto directo con el equipo de ventas    | 6                  | Jafeth       | Done                                    |
| US10 | Visualizar información del equipo | T14 | Crear sección "Nuestro equipo" | Diseñar y desarrollar sección con información e imágenes del equipo           | 4                  | Pedro       | Done                                    |

#### 5.2.1.4. Development Evidence for Sprint Review

| Repository        | Branch                | Commit Id                                | Commit Message | Commit Message Body            | Commit on (Date) |
|-------------------|-----------------------|------------------------------------------|----------------|--------------------------------|------------------|
| wasd-landing-page | main                  | ad74632a88b42b0b219e8becb6d75586b9745870 | update: landing page finished               | update: landing page finished  | 15/09/2025       |
| wasd-landing-page | feature/header        | 9bb9fd2bfc10eb985c96349ced1d74977554629f | update(js): header section               | update(js): header section                               | 15/09/2025       |
| wasd-landing-page | feature/hero          | edd2d9d143b4d9523d778d37ba36b7ee3ece7dd1           | feat: added hero section               | feat: added hero section                               | 15/09/2025       |
| wasd-landing-page | feature/about-us      | 5ff4976080591571fd12c5eab510965063d5e7bc           | feat(about-us): add structure and styles for the about-us section.               |  feat(about-us): add structure and styles for the about-us section.                              | 15/09/2025       |
| wasd-landing-page | feature/product       | a9b7aee8c76cc4917b1689770f34c2632a768b2b                   | add: added home section + css for items. on designed branch , waiting for main merge               | add: added home section + css for items. on designed branch , waiting for main merge                               | 15/09/2025       |
| wasd-landing-page | feature/solutions     | 0f9324142f3145abcbef05385641a39de8a51d2a                | feat: added solutions section               |  feat: added solutions section                              | 15/09/2025       |
| wasd-landing-page | feature/subscriptions | e88936be85bd1c5b3e00d735e4d1723069d368e7                 | update(js): subscriptions section               | update(js): subscriptions section                               | 15/09/2025       |
| wasd-landing-page | feature/faq           | 5a34dfccb18eaa743287f794b72e0675096542d2                | feat: added faq section               | feat: added faq section                               | 15/09/2025       |
| wasd-landing-page | feature/contact-sales | 183a8625ac1eef1bcd085cf5f70945d9e9f9f06a                | update(js): contact-sales section               | update(js): contact-sales section                               | 15/09/2025       |
| wasd-landing-page | feature/footer        | 757e65a3a7b035b793a2e6b6f1b657fbda341836                                         | update(js): footer section and internationalization               | update(js): footer section and internationalization                               | 15/09/2025       |

#### 5.2.1.5. Execution Evidence for Sprint Review

Después de finalizar el Sprint 1, hemos logrado implementar todas las secciones de nuestra Landing Page, aunque con algunos desperfectos en cuanto a diseño. A continuación, te invitamos a explorar nuestros avances a través de imágenes que muestran el resultado obtenido.

1. Seccion header: Aqui mostramos la barra de navegacion de nuestro sitio web.

![header.png](../../assets/chapter-5/header.png)

2. Seccion de monitoreo: Demostramos el monitoreo inteligente de liquidos en hogares y empresas.

![hero.png](../../assets/chapter-5/hero.png)

3. Seccion de visibilidad de liquidos: Monitorea tanques y tuberías de líquidos, midiendo volumen, presión y temperatura con paneles claros y alertas configurables.

![production.png](../../assets/chapter-5/production.png)

4. Seccion de Nosotros y Equipo de trabajo: Se visualiza el proposito del producto y presenta a los desarrolladores del grupo.

![about-us.png](../../assets/chapter-5/about-us.png)

5. Seccion de soluciones: Mostramos las soluciones por cada segmento, en este caso residencias y negocios.

![solutions.png](../../assets/chapter-5/solutions.png)

6. Seccion de funcionalidades: Descubre las interesantes funcionalidades de esta empresa.

![features.png](../../assets/chapter-5/features.png)

7. Seccion de comentarios de clientes: Historias reales de equipos que usan Qlic para líquidos.

![questions.png](../../assets/chapter-5/questions.png)

8. Seccion de subscripcion: Presentamos los planes de subscripcion del producto.

![plans.png](../../assets/chapter-5/plans.png)

9. Seccion de preguntas frecuentes: Detallamos algunas dudas antes de que optes en utilizar el producto.

![faq.png](../../assets/chapter-5/faq.png)

10. Seccion de contactar: Si necesitas ayuda, no dudes en dejar un mensaje.

![contact-sales.png](../../assets/chapter-5/contact-sales.png)

11. Seccion footer: La parte final del sitio web.

![footer.png](../../assets/chapter-5/footer.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

**Esta sección no aplica para esta entrega.**

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Se desplegó la landing page usando el servicio de GitHub Pages. Se configuró para utilizar la rama main como base del proyecto a desplegar.

![deploy.png](../../assets/chapter-5/deploy.png)

URL de Landing Page Desplegada: https://wasd25.github.io/landing-page/

#### 5.2.1.8. Team Collaboration Insights during Sprint

La meta de este sprint fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, HTML, CSS y JavaScript. Como evidencias del trabajo realizado tenemos los diagramas de flujo que representan los commits realizados por cada miembro del equipo WASD.

![insigths.png](../../assets/chapter-5/insigths.png)

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

### 3. Tecnología y herramientas aplicadas a la realidad
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

| Título                  | Descripción                                        | Enlace                      |
|-------------------------|----------------------------------------------------|-----------------------------|
| Video de exposición TB1 | Video explicativo de los avances de la entrega TB1 | https://acortar.link/fW34Bs |
| Video de entrevistas    | Video recopilatorio de todas las entrevistas       | https://acortar.link/CHjPcJ |



### UX/UI
| Título | Descripción                                                                                                | Enlace                       |
|--------|------------------------------------------------------------------------------------------------------------|------------------------------|
| Figma  | Enlace hacia el documento de Figma con todos los diseños planteados para tanto Frontend como Landing Page. | https://acortar.link/aGZMSk  | 

### GITHUB

| Título                  | Descripción                            | Enlace                                   |
|-------------------------|----------------------------------------|------------------------------------------|
| Reporte                 | Enlace al repositorio del reporte      | https://github.com/wasd25/final-report-2 |
| Landing Page            | Enlace al repositorio del Landing Page | https://github.com/wasd25/landing-page   |
| Landing Page Desplegada | Enlace de Landing Page Desplegada      | https://wasd25.github.io/landing-page/   |