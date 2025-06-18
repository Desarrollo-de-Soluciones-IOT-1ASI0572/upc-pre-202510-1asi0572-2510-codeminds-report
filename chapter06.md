# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.

En esta sección, el equipo establece las decisiones y convenciones que permitirán mantener la consistencia durante todo el ciclo de vida del desarrollo de software. La configuración abarca la gestión del código fuente, la configuración del entorno de desarrollo y el despliegue de las aplicaciones. Estas decisiones garantizan una colaboración eficiente, asegurando que todos los miembros del equipo trabajen de manera coherente y organizada.

### 6.1.1. Software Development Environment Configuration.

En esta sección se especifican y describen las herramientas y productos de software que los miembros del equipo deben utilizar durante el ciclo de vida del desarrollo, para garantizar la colaboración eficiente y la consistencia en el proyecto. Estas herramientas cubren todas las áreas clave, incluyendo la gestión del proyecto, el diseño UX/UI, el desarrollo, las pruebas y el despliegue.

#### Project Management

- Trello:
  Trello es una herramienta web para la gestión de proyectos que funciona en la mayoría de los navegadores. Se utilizó para organizar y registrar las tareas pendientes, en proceso y completadas, lo que permitió mantener un control claro del progreso del proyecto y las responsabilidades de cada miembro del equipo.

#### Product UX/UI Design

- Miro:
  Miro fue empleado para el desarrollo de mapas de escenarios y planificación visual, facilitando la comprensión y comunicación entre los distintos segmentos objetivo.

- Figma:
  Figma jugó un papel fundamental en la creación colaborativa de wireframes, maquetas y prototipos para el landing page, aplicaciones web y moviles. Su acceso es gratuito mediante una cuenta registrada, lo que facilita la colaboración remota entre los miembros del equipo.

#### Software Developement

**Landing Page:** <br>
El desarrollo de la Landing Page se realizó utilizando las tecnologías fundamentales para el diseño web moderno:
<br>

- HTML5: Para la estructura semántica del contenido. <br>
- CSS3: Para el diseño visual, uso de media queries y animaciones básicas. <br>
- JavaScript: Para la interactividad, validaciones de formularios y manipulación del DOM.
  <br>
  Estas tecnologías permiten una página ligera, responsive y optimizada para dispositivos móviles, garantizando una experiencia de usuario accesible y clara.

<br>
<br>

**Frontend Web:** <br>
Para el desarrollo de la aplicación web se emplearon tecnologías del entorno frontend moderno:

- **HTML5**, **CSS3** y **JavaScript** como fundamentos esenciales.
- **Angular** como framework principal, permitiendo una arquitectura basada en componentes, enrutamiento interno, servicios reutilizables y vinculación bidireccional de datos.

Angular facilitó la creación de una interfaz dinámica y escalable, especialmente útil para usuarios como padres y administradores, quienes requieren acceso en tiempo real a información del transporte escolar.

<br>

**Aplicacion Movil** :<br>
La aplicación móvil fue desarrollada de forma **nativa para Android** utilizando:

- **Android Studio** como entorno de desarrollo integrado (IDE).
- **Kotlin** como lenguaje principal, por su interoperabilidad con Java, su sintaxis moderna y su orientación a la seguridad.
  <br>
  Esta aplicación móvil complementa la experiencia web y ofrece a los padres una herramienta confiable para el seguimiento diario de sus hijos en el transporte escolar, directamente desde su smartphone.

#### IDE's de desarrollo

- WebStorm :
  Utilizado para la creación del **Landing Page** y la **aplicación web**. Este IDE, desarrollado por JetBrains, está optimizado para tecnologías web como **HTML5**, **CSS3**, **JavaScript** y frameworks modernos como **Angular**, lo que permite una codificación más eficiente, estructurada y mantenible.
- Android Studio :
  Fue la herramienta principal para el desarrollo de la **aplicación móvil**. Esta se implementó en **Kotlin**, siguiendo las prácticas recomendadas para el desarrollo nativo en Android. Esto garantiza una experiencia de usuario fluida y una compatibilidad robusta con las versiones más recientes del sistema operativo.
- IntelliJ IDEA :
  Se empleó para el desarrollo del **backend** del sistema. Este potente IDE también desarrollado por JetBrains, permite integrar múltiples tecnologías y facilita la implementación de servicios, controladores y lógica de negocio. Además, ofrece herramientas avanzadas como **depuración**, integración con **bases de datos**, y compatibilidad con herramientas de construcción como **Gradle** o **Maven**.

#### Software Testing

- Para verificar el correcto funcionamiento del sistema en cada una de sus partes, se realizaron diversas pruebas utilizando herramientas específicas según el entorno. En el caso de la landing page y la aplicación web, se utilizaron navegadores modernos como Google Chrome, Microsoft Edge y Mozilla Firefox, tanto en sus versiones de escritorio como móviles, lo cual permitió inspeccionar el comportamiento visual, la interacción del usuario y la correcta adaptación del diseño responsivo. Para el backend, se empleó Postman, una herramienta que permitió validar el funcionamiento de cada API desarrollada, comprobando los métodos HTTP, las respuestas recibidas, los códigos de estado y el formato de los datos enviados y recibidos. Finalmente, para la aplicación móvil, se utilizó el emulador integrado en Android Studio, que permitió simular dispositivos con distintas resoluciones y versiones de Android, lo cual facilitó la detección de errores y la comprobación de la experiencia del usuario en diferentes escenarios sin necesidad de usar un dispositivo físico.

#### Software Deployment

- **Firebase** :
  Plataforma en la nube que proporciona un conjunto completo de herramientas para el desarrollo, despliegue y alojamiento de aplicaciones web. Facilita a los desarrolladores la creación y publicación eficiente y escalable de sitios estáticos o dinámicos.

#### Software Documentation

- Markdown :
  Lenguaje de marcado ligero que permite dar formato al texto de forma sencilla utilizando texto plano. Se utiliza para documentar información relevante sobre el contexto, organización, producción y creación del proyecto.
- Structurizr:
  Herramienta para la creación rápida de diagramas C4 mediante una sintaxis similar a un lenguaje de programación. Requiere una cuenta registrada para su uso en la aplicación web.

- Vertabelo:
  Es una aplicación web colaborativa que facilita el diseño e implementación de bases de datos en una amplia variedad de motores.

### 6.1.2. Source Code Management.

En esta sección se detalla cómo el equipo gestionará el código fuente utilizando GitHub como plataforma y sistema de control de versiones. A continuación, se describen los medios y el esquema de organización que se implementarán para el seguimiento de modificaciones. El equipo aplicará el workflow GitFlow para organizar las ramas de desarrollo y mantendrá un seguimiento estricto del versionado y los commits.

## Organización y Gestión del Trabajo

El trabajo colaborativo fue gestionado a través de la plataforma GitHub, utilizando una organización dedicada:

- **Organización:** [Desarrollo-de-Soluciones-IOT-1ASI0572](https://github.com/Desarrollo-de-Soluciones-IOT-1ASI0572)
- **Repositorio de la Landing Page:** [EduGo-landing-page](https://github.com/Desarrollo-de-Soluciones-IOT-1ASI0572/CodeMinds-LandingPage)
- **Repositorio del FrontEnd:** [EduGo-FrontEnd](https://github.com/Desarrollo-de-Soluciones-IOT-1ASI0572/edugo-web-application)

---

### Flujo de Trabajo con GitFlow

Para garantizar un desarrollo ordenado, se adoptó la estrategia de ramas **GitFlow**, que permite un control riguroso del ciclo de vida del software.

#### Ramas Principales

- **`main`**

  - Contiene versiones estables listas para producción.
  - Solo recibe cambios desde ramas `release` o `hotfix`.

- **`development`**
  - Rama de integración para las funcionalidades en desarrollo.
  - Se parte de esta rama para crear nuevas funcionalidades (`feature`).

#### Ramas Secundarias

- **`feature/<nombre_funcionalidad>`**
  - Usadas para implementar nuevas características.
  - Se crean desde `development`.
  - Una vez completadas, se fusionan nuevamente con `development`.
  - Ejemplo: `feature/add-analytics-dashboard`

### 6.1.3. Source Code Style Guide & Conventions.

Para el desarrollo de futuros sprints se utilizarán las siguientes convenciones en el código:

**Idioma:**

- La documentación y elaboración de informes se realizarán en español.
- Los nombres de archivos, variables, clases, funciones y constantes en HTML, CSS, JavaScript, TypeScript y Java estarán en inglés.

**Clases y funciones:**

- Los identificadores para clases y funciones se escribirán en inglés.

**Comentarios y documentación del código:**

- Se promoverá el uso de comentarios claros y breves en español, para explicar el propósito y funcionamiento de las partes relevantes del código, facilitando así la comprensión para todo el equipo de desarrollo.

### 6.1.4. Software Deployment Configuration.

La configuración de despliegue de software para la solución propuesta depende del componente específico que se esté desplegando. A continuación, se detallan las configuraciones de despliegue para cada uno de los componentes principales del proyecto.

#### Landing Page
La landing page fue desplegada utilizando **GitHub Pages**, un servicio gratuito que permite alojar sitios web estáticos directamente desde un repositorio de GitHub. Este servicio es ideal para proyectos de código abierto y proporciona una forma sencilla de compartir el trabajo con el público.
<br><br> ![edugo-landing-page-github](assets/chapter4/edugo-landing-page-github-pages.jpg)
#### Aplicación Web
La aplicación web fue desplegada utilizando **Firebase Hosting**, un servicio de Google que permite alojar aplicaciones web de forma rápida y segura. Firebase Hosting es ideal para aplicaciones de una sola página (SPA) y proporciona características como SSL automático, integración con otras herramientas de Firebase y un CDN global para mejorar la velocidad de carga.
<br><br> ![edugo-web-app-firebase](assets/chapter4/edugo-web-app-firebase.jpg)

## 6.2. Landing Page, Services & Applications Implementation.

En esta sección, detallamos el proceso completo de implementación, pruebas, documentación y despliegue de los distintos componentes que conforman la solución. Esto incluye el desarrollo de nuestra Landing Page, que sirve como punto de entrada y presentación de nuestro producto al público general, así como la implementación de los Servicios Web, Aplicaciones Web, Aplicaciones Móviles y Aplicaciones Embebidas que constituyen el núcleo funcional de nuestra propuesta.

A lo largo de esta sección, explicamos cómo hemos abordado cada fase del ciclo de vida del desarrollo de software para estos componentes, desde la planificación inicial y el diseño, hasta la ejecución de pruebas y el despliegue en entornos de producción. Detallamos las tecnologías utilizadas, los desafíos enfrentados y las soluciones implementadas para asegurar que cada componente cumpla con los requisitos establecidos y proporcione una experiencia de usuario óptima.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1.

| Sprint #                                 | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**           |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Date                                     | 2025-05-02                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Time                                     | 20:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Location                                 | Virtual meeting via Discord                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Prepared By                              | Angel Antonio Cancho Corilla / Juan Diego Cueto Dominguez / Scott Jacobo Huachaca Advincula / Marcelo Sebastian Ramirez Ramirez / Paolo Del Carmen Martinez Villanueva / Xiao Lian Li Zegarra                                                                                                                                                                                                                                                      |
| Attendees (to planning meeting)          | Angel Antonio Cancho Corilla / Juan Diego Cueto Dominguez / Scott Jacobo Huachaca Advincula / Marcelo Sebastian Ramirez Ramirez / Paolo Del Carmen Martinez Villanueva / Xiao Lian Li Zegarra                                                                                                                                                                                                                                                      |
| **Pre-Sprint Review Summary**            | During the preparation phase, the sprint bases were defined, focusing on the development of the Landing Page and the business logic applied to the Front-End design of the web application.                                                                                                                                                                                                                                                        |
| **Initial Sprint Retrospective Summary** | The objectives set in Sprint 1 were met, however, opportunities for improvement in time and task management were identified.                                                                                                                                                                                                                                                                                                                       |
| **Sprint Goal & User Stories**           |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Sprint 1 Goal                            | Our focus is on delivering a clear and simple landing page that communicates the main value of our service. Also an interface, that allows administrators, to visualize business related information and analytics.We believe the mentioned functionalities development will increase the value in the experience for our users.This will be confirmed when new visitors learn more about our service and users are using the implemented features |
| Sprint 1 Velocity                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Sum of Story Points                      | 16 Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                    |

#### 6.2.1.2. Aspect Leaders and Collaborators.

# Leadership and Collaboration Matrix (LACX)

| **Team Member (Last Name, First Name)**   | **GitHub Username** | **Landing Page Development (L/C)** | **Business Logic for Front-End (L/C)** | **Administration Interface (L/C)** | **Data Visualization (L/C)** | **Analytics (L/C)** |
|-------------------------------------------|---------------------|------------------------------------|----------------------------------------|------------------------------------|------------------------------|---------------------|
| **Cancho Corilla, Angel Antonio**         | `angerlessdev`      | **L**                              | **C**                                  | **C**                              | **C**                        | **L**               |
| **Cueto Dominguez, Juan Diego**           | `JDu202012207`      | **C**                              | **L**                                  | **C**                              | **L**                        | **C**               |
| **Huachaca Advincula, Scott Jacobo**      | `Scott-Huachaca`    | **C**                              | **C**                                  | **L**                              | **C**                        | **C**               |
| **Ramirez Ramirez, Marcelo Sebastian**    | `MRamirez202210582` | **C**                              | **C**                                  | **C**                              | **C**                        | **L**               |
| **Del Carmen Martinez Villanueva, Paolo** | `paolomv02`         | **C**                              | **L**                                  | **C**                              | **C**                        | **C**               |
| **Li Zegarra, Xiao Lian**                 | `XLianLZ`           | **C**                              | **C**                                  | **L**                              | **C**                        | **C**               |

#### 6.2.1.3. Sprint Backlog 1.

# Sprint 1

| User Story |                                                      | Work-Item / Task |                                       |                                                                                       |                    |                              |                                                |
|------------|------------------------------------------------------|------------------|---------------------------------------|---------------------------------------------------------------------------------------|--------------------|------------------------------|------------------------------------------------|
| Id         | Title                                                | Id               | Title                                 | Description                                                                           | Estimation (Hours) | Assigned To                  | Status (To-do / In-Process / To-Review / Done) |
| HU10       | Generación de reportes automáticos                   | TA01             | Lógica para la generacion de reportes | Programacion de la logica vinculada a la generacion de reportes                       | 5 horas            | Angel Cancho- Paolo Martinez | Done                                           |
| HU45       | Visualización del historial de incidentes            | TA02             | Desarrollo del listado de incidentes  | Listado de incidentes recibidos de un endpoint                                        | 2.5 horas          | Juan Diego Cueto             | Done                                           |
|            |                                                      | TA03             | Vista de Incidentes                   | Desarrollo de la vista de que muestra informacion detallada de la lista de incidentes | 2.5 horas          | Scott Huachaca               | Done                                           |
| HU52       | Visualizacion de proposito y beneficios del servicio | TA04             | Navegacion                            | Implementacion de una barra de navegacion                                             | 1 hora             | Xiao Li                      | Done                                           |
|            |                                                      | TA05             | Contenido Principal                   | Insercion de informacion en la landing page                                           | 2 horas            | Xiao Li                      | Done                                           |
| HU53       | Formulario de Contacto                               | TA06             | Formulario                            | Desarrollo de formulario con campos de contacto(nombre, correo, mensaje, etc.)        | 2 horas            | Marcelo Ramirez              | Done                                           |

#### 6.2.1.4. Development Evidence for Sprint Review.

Para este primer sprint se decidió trbajar en una rama diferente para después unirlo todo en develop. Cada miembro ha realizado un commit para luego hacer merge.

| Repository            | Branch                          | Commit ID                                | Commit Message                                                        | Committed on(date)    |
|-----------------------|---------------------------------|------------------------------------------|-----------------------------------------------------------------------|-----------------------|
| CodeMinds-LandingPage | main                            | de87e5cb957edb9c71d78843c64ff5b761060c2b | fix(landing-page): set english as default language                    | 13/05/2025            |
| CodeMinds-LandingPage | main                            | 3bfbb3898b963e1e82bd4551dfaae948e3b1504f | feat(landing-page): add language configuration file                   | 13/05/2025            |
| CodeMinds-LandingPage | main                            | 3b1c3c3320f227ac5f1ab5d909b52c19414b1fcd | feat(landing-page): style sheet initial commit                        | 13/05/2025            |
| CodeMinds-LandingPage | main                            | 0093fdb53adc93987efdc078f1d54d1d49024dd3 | feat(landing-page): script file initial commit                        | 13/05/2025            |
| CodeMinds-LandingPage | main                            | 4cf928b3881c5245f13d654fb9b879f57f2c830c | feat(landing-page): html file initial commit                          | 13/05/2025            |
| CodeMinds-LandingPage | main                            | 67d79de6195f29a88e98b6614db9878c3b22bbd7 | feat(Landing-Page): Add team description in portugues                 | 15/05/2025            |
| CodeMinds-LandingPage | main                            | e4592aab9c36bcfd1e116e55597a408ad2ea5e08 | feat(Landing-Page): add team description translation                  | 15/05/2025            |
| CodeMinds-LandingPage | main                            | 790ce5d99a62f0be973d0fffb3ef3e9738df9553 | feat(Landing-Page): add Team photo                                    | 15/05/2025            |
| CodeMinds-LandingPage | main                            | 8d945be380998242fd8dafe0e6d25f0abe678bb5 | feat(Landing-Page): add team profile images                           | 15/05/2025            |
| CodeMinds-LandingPage | main                            | b93812f67ca125711b99050460703265f26fc929 | chore(landing-page): manage contact and team translations             | 15/05/2025            |
| CodeMinds-LandingPage | main                            | dfc49155d29e9517508dfa4516f63524cc51a9b2 | chore(landing-page): contact and team styles                          | 15/05/2025            |
| CodeMinds-LandingPage | main                            | eb128daedcdf4758eb5710c8751e7770a11aa2cf | chore(landing-page): add contact and team references to the home      | 15/05/2025            |
| CodeMinds-LandingPage | main                            | 2b6750085efaf5a521b69be888e9d8eacf4581f6 | feat(landing-page): add team html file                                | 15/05/2025            |
| CodeMinds-LandingPage | main                            | cfe4749e33cbd6eebd0e3b76ffaf629ee433f2aa | feat(landing-page): add contact html file                             | 15/05/2025            |
| CodeMinds-LandingPage | main                            | 22ef41e8c68294a78d49acae7b62fbd6b90f7bdc | chore(landing-page): set english as default language                  | 15/05/2025            |
| edugo-web-application | develop                         | b8307949e7b3234859c51b4ccf784a6959713c58 | feat(dashboard): add view dashboard                                   | 15/05/25              |
| edugo-web-application | develop                         | 35dd827d518592fdab57c292c46249fa541d1411 | feat(develop): add header component                                   | 15/05/25              |
| edugo-web-application | main                            | 2c4ecee3371b8c08c8944ad06a791beb948494ba | docs: update readme with installation instructions                    | 15/05/25              |
| edugo-web-application | main                            | 117a7e4348fd934cbfac10a7766f4f80cca3ee04 | chore: initial commit                                                 | 15/05/25              |
| edugo-web-application | develop                         | 87a4baf387429c8bd1e8309b153ababfe861d8c3 | refactor: update navigation routes with semantic rules                | 16/05/25              |
| edugo-web-application | develop                         | 025e6e36dd321a23530898339d6ba9ecdca36a82 | feat(profiles): add component for profile                             | 16/05/25              |
| edugo-web-application | develop                         | 2b2888b8dacc6ad889d6e8c6395a66c15187602a | fix(develop): fix merge errors                                        | 16/05/25              |
| edugo-web-application | feature/add-reports-table       | fe48c3d8be5a2120fb85b1ff60610cced0431a57 | feat(add-reports-table): merged in develop branch                     | 16/05/25              |
| edugo-web-application | feature/add-analytics-dashboard | efcd0c7f72f4eddb0aa078419bdeccc544543940 | refactor(analytics): update models and services for new fake API data | 16/05/25              |
| edugo-web-application | develop                         | 79e054aa940d0e0b7cb05354505a92699aa3cde1 | refactor(iam): add logo icon to sign-in and route login to dashboard  | 16/05/25              |
| edugo-web-application | develop                         | f2237a290593f733df798f66e851da39b04dd133 | feat(iam): add sign-in page and set login as principal route          | 16/05/25              |
| edugo-web-application | develop                         | fef1688972539792753109a14dca2df9206c4ee3 | chore(update): update api url                                         | 16/05/25              |
| edugo-web-application | feature/add-reports-table       | 4f3143818ddce8c519eb2ae4c9d625fd11b86fa5 | feat(add-reports-table): add table filter                             | 16/05/25              |
| edugo-web-application | feature/add-reports-table       | ce0fe99ebbdd4f3c38081342f6bcfcce57be3c6d | feat(add-reports-table): add incidents model                          | 16/05/25              |
| edugo-web-application | feature/add-reports-table       | 43f8f6d6c076908c8f2bccd7541ab074417ce025 | feat(add-reports-table): add reports table                            | 16/05/25              |

#### 6.2.1.5. Testing Suite Evidence for Sprint Review.

| Repository            | Branch | Commit ID                                | Commit Message                                         | Committed on(date) |
|-----------------------|--------|------------------------------------------|--------------------------------------------------------|--------------------|
| CodeMinds-LandingPage | main   | 67d79de6195f29a88e98b6614db9878c3b22bbd7 | feat(Landing-Page):Add team description in portugues   | 16/05/25           |
| edugo-web-application | main   | 87a4baf387429c8bd1e8309b153ababfe861d8c3 | refactor: update navigation routes with semantic rules | 16/05/25           |

#### 6.2.1.6. Execution Evidence for Sprint Review.

Para el logro de este proyecto, se realizó el despliegue tanto de la Landing Page, como la primera versión de la aplicación web, las cuales se encuentran en los siguientes enlaces a continuación:

**Para el landing page**
<img src="/assets/chapter4/Execution-LandingPage.PNG" alt="Contact" style="width:100%;">
Enlace a la Landing Page: https://shorturl.at/gUWFP

**Para la aplicación web**
<img src="/assets/chapter4/frontend-execution.PNG" alt="Contact" style="width:100%;">
Enlace al FrontEnd: https://edugo-web-app.web.app/sign-in

**Enlace del video de evidencia:** https://shorturl.at/ca4qS

#### 6.2.1.7. Services Documentation Evidence for Sprint Review.

A continuación se presenta la documentación de los servicios de la aplicación web, incluyendo la descripción de los
endpoints disponibles.

| Endpoint                                                          | Http Verb | Accion               | Descripcion                                                                                                                                                                              |
|-------------------------------------------------------------------|-----------|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| https://jdu202012207.github.io/pruebas-api/drivers.json           | GET       | Obtener conductores  | Devuelve información de los conductores registrados, incluyendo datos personales, número de licencia, vehículo asignado y estudiantes a su cargo.                                        |
| https://jdu202012207.github.io/pruebas-api/parents.json           | GET       | Obtener apoderados   | Devuelve información de los padres de familia registrados, incluyendo nombre, DNI, número telefónico, foto y los estudiantes a su cargo                                                  |
| https://jdu202012207.github.io/pruebas-api/students.json          | GET       | Obtener estudiantes	 | Devuelve información de los estudiantes registrados, incluyendo su nombre, colegio, grado, código RFID, foto y relación con su apoderado y conductor asignado.                           |
| https://jdu202012207.github.io/pruebas-api/analytics-drivers.json | GET       | Obtener analíticas	  | Devuelve analíticas de rendimiento de los conductores, incluyendo resumen de incidentes (desvíos, tardanzas, excesos de velocidad), tiempos de llegada y distancias recorridas por día.  |

#### 6.2.1.8. Software Deployment Evidence for Sprint Review.

Para el sprint presentado de la landing page y FrontEnd se optó por varias herramientas para su desarrollo.

- _Git_: Se utilizó para el control de versiones del código fuente.
- _GitFlow_: Se utilizó para ver el avance de los integrantes del equipo.
- _GitHub_: Se utilizó para crear el repositorio de la landing page, donde se subió el código fuente.
- _Angular_: Se utilizó para crear el web app funcional con la ayuda de un fakeapi
- _GitHub Pages_: Es la plataforma donde se desplegó la landing page. Se eligió por ser una solución gratuita, rápida y sencilla que permite publicar directamente desde el repositorio de GitHub.

**Deployamiento del landing**
Para el despliegue de la landing page, se configuró el servicio de GitHub Pages siguiendo los siguientes pasos:

1. Se accedió al repositorio en la plataforma de GitHub.
2. En la parte superior del repositorio, se hizo clic en la pestaña **"Settings"**.
3. En el menú lateral izquierdo, se seleccionó la opción **"Pages"**.
4. En la sección **"Source"**, se eligió la rama `main` como origen y la carpeta raíz (`/`) como directorio de publicación.
5. Finalmente, se hizo clic en **"Save"** para guardar los cambios y activar el despliegue.
   <img src="/assets/chapter4/DeployLanding.PNG" alt="Contact" style="width:100%;">

#### 6.2.1.9. Team Collaboration Insights during Sprint.

Para esta sección del documentos, añadimos los insights realizados durante el sprint, tanto de la realización de la aplicación web, como el landing page:

Insights del LandingPage, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamLanding.PNG" alt="Contact" style="width:100%;">
<br>

Insights del FrontEnd, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamFrontend.PNG" alt="Contact" style="width:100%;">

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning 2.

| Sprint #                                 | Sprint 2                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**           |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Date                                     | 2025-05-26                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Time                                     | 20:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Location                                 | Virtual meeting via Discord                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Prepared By                              | Angel Antonio Cancho Corilla / Juan Diego Cueto Dominguez / Scott Jacobo Huachaca Advincula / Marcelo Sebastian Ramirez Ramirez / Paolo Del Carmen Martinez Villanueva / Xiao Lian Li Zegarra                                                                                                                                                                                                                                                      |
| Attendees (to planning meeting)          | Angel Antonio Cancho Corilla / Juan Diego Cueto Dominguez / Scott Jacobo Huachaca Advincula / Marcelo Sebastian Ramirez Ramirez / Paolo Del Carmen Martinez Villanueva / Xiao Lian Li Zegarra                                                                                                                                                                                                                                                      |
| **Pre-Sprint Review Summary**            | During the preparation phase, the sprint bases were defined, focusing on the development of the Landing Page and the business logic applied to the Front-End design of the web application.                                                                                                                                                                                                                                                        |
| **Initial Sprint Retrospective Summary** | The objectives set in Sprint 1 were met, however, opportunities for improvement in time and task management were identified.                                                                                                                                                                                                                                                                                                                       |
| **Sprint Goal & User Stories**           |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Sprint 2 Goal                            | Our focus is on delivering _____. Also an interface, that allows administrators, to visualize business related information and analytics.We believe the mentioned functionalities development will increase the value in the experience for our users.This will be confirmed when ______ |
| Sprint 2 Velocity                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Sum of Story Points                      |  Story Points                                                                                                                                                                                                                                                                                                                                                                                                                                    |

#### 6.2.2.2. Aspect Leaders and Collaborators.

# Leadership and Collaboration Matrix (LACX)

| **Team Member (Last Name, First Name)**   | **GitHub Username** | **Landing Page Development (L/C)** | **Business Logic for Front-End (L/C)** | **Administration Interface (L/C)** | **Data Visualization (L/C)** | **Analytics (L/C)** |
|-------------------------------------------|---------------------|------------------------------------|----------------------------------------|------------------------------------|------------------------------|---------------------|
| **Cancho Corilla, Angel Antonio**         | `angerlessdev`      | **L**                              | **C**                                  | **C**                              | **C**                        | **L**               |
| **Cueto Dominguez, Juan Diego**           | `JDu202012207`      | **C**                              | **L**                                  | **C**                              | **L**                        | **C**               |
| **Huachaca Advincula, Scott Jacobo**      | `Scott-Huachaca`    | **C**                              | **C**                                  | **L**                              | **C**                        | **C**               |
| **Ramirez Ramirez, Marcelo Sebastian**    | `MRamirez202210582` | **C**                              | **C**                                  | **C**                              | **C**                        | **L**               |
| **Del Carmen Martinez Villanueva, Paolo** | `paolomv02`         | **C**                              | **L**                                  | **C**                              | **C**                        | **C**               |
| **Li Zegarra, Xiao Lian**                 | `XLianLZ`           | **C**                              | **C**                                  | **L**                              | **C**                        | **C**               |

#### 6.2.2.3. Sprint Backlog 2.

# Sprint 2

| User Story |                                                      | Work-Item / Task |                                       |                                                                                       |                    |                              |                                                |
|------------|------------------------------------------------------|------------------|---------------------------------------|---------------------------------------------------------------------------------------|--------------------|------------------------------|------------------------------------------------|
| Id         | Title                                                | Id               | Title                                 | Description                                                                           | Estimation (Hours) | Assigned To                  | Status (To-do / In-Process / To-Review / Done) |
| HU10       | Generación de reportes automáticos                   | TA01             | Lógica para la generacion de reportes | Programacion de la logica vinculada a la generacion de reportes                       | 5 horas            | Angel Cancho- Paolo Martinez | Done                                           |
| HU45       | Visualización del historial de incidentes            | TA02             | Desarrollo del listado de incidentes  | Listado de incidentes recibidos de un endpoint                                        | 2.5 horas          | Juan Diego Cueto             | Done                                           |
|            |                                                      | TA03             | Vista de Incidentes                   | Desarrollo de la vista de que muestra informacion detallada de la lista de incidentes | 2.5 horas          | Scott Huachaca               | Done                                           |
| HU52       | Visualizacion de proposito y beneficios del servicio | TA04             | Navegacion                            | Implementacion de una barra de navegacion                                             | 1 hora             | Xiao Li                      | Done                                           |
|            |                                                      | TA05             | Contenido Principal                   | Insercion de informacion en la landing page                                           | 2 horas            | Xiao Li                      | Done                                           |
| HU53       | Formulario de Contacto                               | TA06             | Formulario                            | Desarrollo de formulario con campos de contacto(nombre, correo, mensaje, etc.)        | 2 horas            | Marcelo Ramirez              | Done                                           |

#### 6.2.2.4. Development Evidence for Sprint Review.

Para este segunfo sprint se decidió trbajar en ramas diferente para después unirlo todo en develop. Cada miembro ha realizado un commit para luego hacer merge.

**CodeMinds-Backend**:

| Repository            | Branch                          | Commit ID                                | Commit Message                                                        | Committed on(date)    |
|-----------------------|---------------------------------|------------------------------------------|-----------------------------------------------------------------------|-----------------------|
| CodeMinds-Backend     | feature/analytics      | d5d79ac6f6d8e069abde9e471c8a08099a055823 | feat(analytics): add analytics                                        | 05/06/2025            |
| CodeMinds-Backend     | feature/iam            | 47bd4e33395c449f916244bf43093054df48c3fa | feat(iam): add user and role management with exception handling       | 12/06/2025            |
| CodeMinds-Backend     | feature/iam   | 786b2c3891934e37b08a5af573b2d892ee40d6f3 | feat(iam): implement query and command services for user and role management | 12/06/2025              |
| CodeMinds-Backend     | feature/iam   | 4fd0fe2181ddba12a324cc1bea4151e580025e9d | feat(iam): add implementation of JWT and BCrypt token services with security filters  | 12/06/2025    |
| CodeMinds-Backend     | feature/iam   | dbf7f23a418d68b8632232b9d0be97e52db6c143 | feat(iam): add authentication and user management endpoints with role seeding   | 12/06/2025        |
| CodeMinds-Backend     | feature/iam   | 9ca324d6f49b15bcc57b8db00f74f1e38a153129 | feat(iam): add auditing support with abstract models and open-api configuration  | 13/05/2025      |
| CodeMinds-Backend     | feature/iam   | a2c8dc5a5e11b6261869bf13811c5ae08d8f4ed4 | feat(iam): add message resource record for standardized message handling     | 13/06/2025            |
| CodeMinds-Backend  | feature/profiles                | 0da3d186af2de80578618004fa6a817326077edc | feat(profiles): add profiles bc                 | 09/06/2025            |
| CodeMinds-Backend  | feature/profiles                | ce7666060d2838f51baa725a018b14c6d1493410 | fix(profiles): fix profiles services         | 12/06/2025            |
| CodeMinds-Backend  | feature/profiles                | 033f78099cb9e70cf3c30d8b17c519db29086f5a | feat(profiles): add acl with IAM             | 12/06/2025            |
| CodeMinds-Backend | feature/real-time-notification | 8316928 | feat: add RealTimeNotificationQueryService interface | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 6142322 | feat: add RealTimeNotificationCommandService interface | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 1065866 | feat: add CreateRealTimeNotificationCommand record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 6663388 | feat: add CorsConfig | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 7642576 | feat: add AuditableAbstractAggregateRoot | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 3674709 | feat: add AuditableModel | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 536317c | feat: add RealTimeNotification | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 23edb52 | feat: add RealTimeNotificationController with CRUD endpoints | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 4042965 | feat: add CreateRealTimeNotificationCommandFromResourceAssembler class | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 2e0440c | feat: add NotificationStatus enum | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 089956a | feat: add RealTimeNotificationCommandServiceImpl implementation | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 405f783 | feat: add OpenApiConfiguration for API documentation | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 5ac09fa | feat: add NotificationEvent value object | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 3cf4ada | feat: add GetRealNotificationsForUserType record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 21cf693 | feat: add GetRealNotificationsForUserId record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | ddb0999 | feat: add GetAllRealTimeNotificationsQuery record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | ea7685b | feat: add CreateRealTimeNotificationResource record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 7fefc11 | feat: add SnakeCaseWithPluralizedTablePhysicalNamingStrategy class | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 9d5248e | feat: add RealTimeNotificationResource record | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 795387a | feat: add RealTimeNotificationRepository interface | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 895347 | feat: add RealTimeNotificationQueryServiceImpl implementation | 06/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 8ds288s | feat: update CreateRealTimeNotificationCommandFromResourceAssembler to include tripid and studentId | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | [7s2s64c | feat: extend CreateRealTimeNotificationResource to include tripid and studentId | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification |  | feat: add GetRealNotificationsForStudentId record for student notification queries | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | e5b1ec2 | feat: add GetRealNotificationsForTripid record for trip notification queries | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 9f189d7 | feat: add GetRealNotificationsForUserAndTrip record for user and trip notification queries | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 9aa6713 | feat: update RealTimeNotificationCommandServiceImpl to include tripid and studentId in notification creation | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 39e918c | feat: add query methods in RealTimeNotificationQueryService for studentId, tripid, and userId with tripid | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 937c5bd | feat: add query methods in RealTimeNotificationQueryServiceImpl for studentId, tripid, and userId with tripid | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 7128a5f | feat: add methods to RealTimeNotificationRepository for querying by studentId, tripid, and userId with tripid | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 353356e | feat: expand RealTimeNotificationResource to include eventType, description, timestamp, tripid, and studentId | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 29f1eb6 | feat: enhance RealTimeNotificationResourceFromEntityAssembler to include additional fields | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 311488a | feat: add StudentBoardedEventListener to handle student boarding events | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 6b0b068 | feat: add getters for eventType and description in NotificationEvent class | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | bea106d | feat: add tripid and studentId fields to RealTimeNotification class | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | ba574fe | feat: add TripStartedEventListener to handle trip start events and create notifications | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 6145883 | feat: add SpeedExceededEventListener to handle speed exceeded events and create notifications | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 5374288 | feat: add TripStartedEventListener to handle trip start events and create notifications | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | a283796 | feat: add TriplEndedEventListener to handle trip end events and create notifications | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 211cfba | feat: add StudentExitedEventListener to handle student exit events and create notifications | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | eSDtec2 | feat: add endpoints to retrieve notifications by tripid, studentId, and userId with tripid | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 9f18947 | feat: extend CreateRealTimeNotificationCommand to include tripid and studentId | 12/06/2025 |
| CodeMinds-Backend | feature/real-time-notification | 9aa6713 | feat: update CreateRealTimeNotificationCommandFromResourceAssembler to include tripid and studentId | 12/06/2025 | 
| CodeMinds-Backend | feature/vehicule-tracking | b7fdbf5 | feat: add vehicule repositories | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 64aae9e | feat: add vehicule services | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | a97f58b | feat: add vehicule value object | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 7d5fd31 | feat: add vehicule queries | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 69bbde9 | feat: add vehicule entitle | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 19sbs88 | feat: add vehicule commands | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 82d3sa5 | feat: add vehicule aggregate | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 88aefi9 | feat: add vehicule queryservices | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 3274e8b | feat: add vehicule commandservices | 06/06/2025 |
| CodeMinds-Backend | feature/vehicule-tracking | 4dcd271 | feat: disable Spring Security | 06/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 617d5db | feat(vehicle-tracking): add EndRouteCommand and associated resource assembler for ending trips | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 4d16ae2 | feat(vehicle-tracking): add query classes for active trip, current location, past trips by driver, and trip students | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 8184920 | feat(vehicle-tracking): add command classes and assemblers for trip student and vehicle creation | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 776ef96 | feat(vehicle-tracking): add resource and command classes for trip and vehicle creation | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 53fc5cb | feat(vehicle-tracking): update database password for local development | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | ad1690c | feat(vehicle-tracking): [commit message missing] | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 5c08541 | feat(vehicle-tracking): add TripRepository for managing trip data | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 19c2580 | feat(vehicle-tracking): update Location entity to use Long for vehicleId and id, and add speed limit check | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 24476eb | feat(vehicle-tracking): add vehiclestatus enum for tracking vehicle states | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | cb8411b | feat(vehicle-tracking): add VehicleStatus enum for tracking vehicle states | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 43a971e | feat(vehicle-tracking): enhance Vehicle entity with status and trips management | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 8263151 | feat(vehicle-tracking): add Trip entity | 12/06/2025 |
| Repository | Branch | Commit Hash | Message | Date |
|------------|--------|-------------|---------|------|
| CodeMinds-Backend | feature/vehicle-tracking | dagc443e | feat(vehicle-tracking): update updateLocation method and add getCurrentLocation and getLocationsByTripId endpoints | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | 9781852 | feat(vehicle-tracking): add handle method for GetLocationsByTripIdQuery to retrieve locations by trip ID | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc521 | feat(vehicle-tracking): add handle method for GetLocationsByTripIdQuery to retrieve locations by trip ID | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc555a9b | feat(vehicle-tracking): refactor handle method to use CreateLocationCommand and add getCurrentLocation method | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc527a9b | feat(vehicle-tracking): update handle method to use CreateLocationCommand and add getCurrentLocation method | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc546a | feat(vehicle-tracking): add GetLocationsByTripIdQuery for querying locations by trip ID | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc153a8 | feat(vehicle-tracking): add CreateLocationResource for location creation data transfer | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc354a | feat(vehicle-tracking): add CreateLocationCommandFromResourceAssembler for command transformation | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc759a6e | feat(vehicle-tracking): add methods to find locations by tripId for enhanced querying | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc227a | feat(vehicle-tracking): add trip association to Location entity for improved tracking | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | dagc910a | feat(vehicle-tracking): rename UpdateLocationCommand to CreateLocationCommand and add tripId for location creation | 15/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | a1b2c3d | feat(vehicle-tracking): add RegisterStudentBoardingCommandFromResourceAssembler and RegisterStudentExitCommandFromResourceAssembler | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | e4f5g6h | feat(vehicle-tracking): add RegisterStudentBoardingCommand and RegisterStudentBoardingResource | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | i7j8k9l | feat(vehicle-tracking): add RegisterStudentExitCommand | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | m1n2o3p | feat(vehicle-tracking): add RegisterStudentExitResource | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | q4r5s6t | feat(vehicle-tracking): implement SpringDomainEventPublisher | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | u7v8w9x | feat(vehicle-tracking): add TripStudentResourceFromEntityAssembler | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | y1z2a3b | feat(vehicle-tracking): add TripStudentResource | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | c4d5e6f | feat(vehicle-tracking): add TripStudentRepository | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | g7h8i9j | feat(vehicle-tracking): add TripResourceFromEntityAssembler | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | k1l2m3n | feat(vehicle-tracking): add TripResource | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | o4p5q6r | feat(vehicle-tracking): add event records for route deviations, speed exceedance, etc | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | s7t8u9v | feat(vehicle-tracking): add DomainEventPublisher interface | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | w1x2y3z | feat(vehicle-tracking): enhance TrackingQueryServiceImpl | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | a4b5c6d | feat(vehicle-tracking): refactor VehicleResource and VehicleTrackingController | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | e7f8g9h | feat(vehicle-tracking): add timestamp to UpdatedLocationCommand/Resource | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | i1j2k3l | feat(vehicle-tracking): implement trip management in TrackingCommandService | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | m4n5o6p | feat(vehicle-tracking): enhance TrackingQueryService with trip handlers | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | q7r8s9t | feat(vehicle-tracking): extend TrackingCommandService | 12/06/2025 |
| CodeMinds-Backend | feature/vehicle-tracking | u1v2w3x | feat(vehicle-tracking): add tripId to StartRouteResource | 12/06/2025 |

#### 6.2.2.5. Testing Suite Evidence for Sprint Review.

| Repository            | Branch | Commit ID                                | Commit Message                                         | Committed on(date) |
|-----------------------|--------|------------------------------------------|--------------------------------------------------------|--------------------|
| CodeMinds-LandingPage | main   | 67d79de6195f29a88e98b6614db9878c3b22bbd7 | feat(Landing-Page):Add team description in portugues   | 16/05/25           |

#### 6.2.2.6. Execution Evidence for Sprint Review.


#### 6.2.2.7. Services Documentation Evidence for Sprint Review.

A continuación se presenta la documentación de los servicios de la aplicación web, incluyendo la descripción de los
endpoints disponibles.

| Endpoint                                                          | Http Verb | Accion               | Descripcion                                                                                                                                                                              |
|-------------------------------------------------------------------|-----------|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| https://jdu202012207.github.io/pruebas-api/drivers.json           | GET       | Obtener conductores  | Devuelve información de los conductores registrados, incluyendo datos personales, número de licencia, vehículo asignado y estudiantes a su cargo.                                        |
| https://jdu202012207.github.io/pruebas-api/parents.json           | GET       | Obtener apoderados   | Devuelve información de los padres de familia registrados, incluyendo nombre, DNI, número telefónico, foto y los estudiantes a su cargo                                                  |
| https://jdu202012207.github.io/pruebas-api/students.json          | GET       | Obtener estudiantes	 | Devuelve información de los estudiantes registrados, incluyendo su nombre, colegio, grado, código RFID, foto y relación con su apoderado y conductor asignado.                           |
| https://jdu202012207.github.io/pruebas-api/analytics-drivers.json | GET       | Obtener analíticas	  | Devuelve analíticas de rendimiento de los conductores, incluyendo resumen de incidentes (desvíos, tardanzas, excesos de velocidad), tiempos de llegada y distancias recorridas por día.  |

#### 6.2.2.8. Software Deployment Evidence for Sprint Review.

Para el sprint presentado de la landing page y FrontEnd se optó por varias herramientas para su desarrollo.

- _Git_: Se utilizó para el control de versiones del código fuente.
- _GitFlow_: Se utilizó para ver el avance de los integrantes del equipo.
- _GitHub_: Se utilizó para crear el repositorio de la landing page, donde se subió el código fuente.
- _Angular_: Se utilizó para crear el web app funcional con la ayuda de un fakeapi
- _GitHub Pages_: Es la plataforma donde se desplegó la landing page. Se eligió por ser una solución gratuita, rápida y sencilla que permite publicar directamente desde el repositorio de GitHub.

**Deployamiento del Backend**
Para el despliegue de la landing page, se configuró el servicio de GitHub Pages siguiendo los siguientes pasos:

1. Se accedió al repositorio en la plataforma de GitHub.
2. En la parte superior del repositorio, se hizo clic en la pestaña **"Settings"**.
3. En el menú lateral izquierdo, se seleccionó la opción **"Pages"**.
4. En la sección **"Source"**, se eligió la rama `main` como origen y la carpeta raíz (`/`) como directorio de publicación.
5. Finalmente, se hizo clic en **"Save"** para guardar los cambios y activar el despliegue.
   <img src="/assets/chapter4/DeployLanding.PNG" alt="Contact" style="width:100%;">


**Deployamiento del AppMobile**

**Deployamiento del EdgeServer**

**Deployamiento del Embedded**

#### 6.2.2.9. Team Collaboration Insights during Sprint.

Para esta sección del documentos, añadimos los insights realizados durante el sprint, tanto de la realización de la aplicación web, como el landing page:

Insights del AppMovil, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamLanding.PNG" alt="Contact" style="width:100%;">
<br>

Insights del Backend, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamFrontend.PNG" alt="Contact" style="width:100%;">
<br>

Insights del EdgeServer, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamFrontend.PNG" alt="Contact" style="width:100%;">
<br>

Insights del Embedded, donde se muestran los commits realizados al repositorio en el ultimo mes
<img src="/assets/chapter4/TeamFrontend.PNG" alt="Contact" style="width:100%;">

## 6.3. Validation Interviews.
### 6.3.1. Diseño de Entrevistas.
### 6.3.2. Registro de Entrevistas.
### 6.3.3. Evaluaciones según heurísticas.
## 6.4. Video About-the-Product.

