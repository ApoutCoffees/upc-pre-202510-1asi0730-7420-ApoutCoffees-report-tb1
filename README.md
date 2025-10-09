![UPC Logo](img/upc-logo.png)
# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS
# FACULTAD DE INGENIERÍA
### PROGRAMA ACADÉMICO DE INGENIERÍA DE SOFTWARE

**Ciclo:** 2025-20
<br>
**NRC:** 7420
<br>
**Docente del curso:** Alex Humberto Sánchez Ponce

---
# INFORME DE TRABAJO(TB1)

**Nombre de la Startup:** ApoutCoffees

**Nombre del producto:** SmilingCups

## Integrantes
- Carlos Augusto Paredes Chavez - U202321613
- Daniel Jonatan Aquino Solorzano - U202217678
- Johnny Alexander Ojanama Abanto - U20231F412
- Juan Carlos Pastor Napa - U202217288
- Giuliano Angel Pelaez Vargas - U20221E121  

**Fecha:** Octubre, 2025

---
## Registro de versiones del informe
| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| 1.0    | 20.09.2025 | Todo el Equipo | Todo el equipo estuvo trabajando en el desarrollo de la documentación para el Sprint 1. |
---

## Project Report Collaboration Insights
[Repositorio de documentación](https://github.com/ApoutCoffees/upc-pre-202510-1asi0730-7420-ApoutCoffees-report-tb1.git)

[Repositorio del Landing Page](https://github.com/ApoutCoffees/SmilingCups-Landing-Page)

[Repositorio del Fronted](https://github.com/ApoutCoffees/SmilingCups-Fronted)

[Repositorio del Backend](https://github.com/ApoutCoffees/SmilingCups-Backend)

---

# Tabla de Contenido

[Student Outcome](student-outcome)

1. [Capítulo I: Introducción](#capítulo-i-introducción)
	- 1.1. [Startup Profile](#11-startup-profile) 
		- 1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)
		- 1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
	- 1.2. [Solution Profile](#12-solution-profile)
		- 1.2.1 [Antecedentes y problemática](#121-antecedentes-y-problemática)
		- 1.2.2 [Lean UX Process](#122-lean-ux-process)
			- 1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
			- 1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
			- 1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
			- 1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)
	- 1.3. [Segmentos objetivo](#13-segmentos-objetivo)
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
	- 2.1. [Competidores](#21-competidores)
		- 2.1.1. [Análisis competitivo](#211-análisis-competitivo)
		-  2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
	- 2.2. [Entrevistas](#22-entrevistas)
		-  2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
		- 2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)
		- 2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
	-  2.3. [Needfinding](#23-needfinding)
		- 2.3.1. [User Personas](#231-user-personas)
		- 2.3.2. [User Task Matrix](#232-user-task-matrix)
		- 2.3.3. [User Journey Mapping](#233-user-journey-mapping)
		- 2.3.4. [Empathy Mapping](#234-empathy-mapping)
	- 2.4. [Big Picture Event Storming](#24-big-picture-event-storming)
	- 2.5. [Ubiquitous Language](#25-ubiquitous-language)
3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
	- 3.1. [To-Be Scenario Mapping](#31-to-be-scenario-mapping)
	- 3.2. [User Stories](#32-user-stories)
	- 3.3. [Impact Mapping](#33-impact-mapping)
	- 3.4. [Product Backlog](#34-product-backlog)
4. [Capítulo IV: Product Design](#capitulo-iv-product-design)
	- 4.1. [Style Guidelines](#41-style-guidelines)
		- 4.1.1. [General Style Guidelines](#411-general-style-guidelines)
		- 4.1.2. [Web Style Guidelines](#412-web-style-guidelines)
	- 4.2. [Information Architecture](#42-information-architecture)
		- 4.2.1. [Organization Systems](#421-organization-systems)
		- 4.2.2. [Labeling Systems](#422-labeling-systems)
		- 4.2.3. [SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
		- 4.2.4. [Searching Systems](#424-searching-system)
		- 4.2.5. [Navigation Systems](#425-navigation-systems)
	- 4.3. [Landing Page UI Design](#43-landing-page-ui-design)
		- 4.3.1. [Landing Page Wireframe](#431-landing-page-wireframe)
		- 4.3.2. [Landing Page Mock-up](#432-landing-page-mock-up)
	- 4.4. [Web Applications UX/UI Design](#44-web-applications-uxui-design)
		- 4.4.1. [Web Applications Wireframes](#441-web-applications-wireframes)
		- 4.4.2. [Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
		- 4.4.3. [Web Applications Mock-ups](#443-web-applications-mock-ups)
		- 4.4.4. [Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
	- 4.5. [Web Applications Prototyping](#45-web-applications-prototyping)
	- 4.6. [Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
		- 4.6.1. [Design-Level EventStorming](#461-design-level-event-storming)
		- 4.6.2. [Software Architecture Context Diagram](#462-software-architecture-context-diagram)
		- 4.6.3. [Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
		- 4.6.4. [Software Architecture Components Diagram](#464-software-architecture-components-diagrams)
	-  4.7. [Software Object-Oriented Design](#47-software-object-oriented-design)
		- 4.7.1. [Class Diagrams](#471-class-diagrams)
	- 4.8. [Database Design](#48-database-design)
		-  4.8.1. [Database Diagrams](#481-database-diagrams)
5. [Capítulo V: Product Implementation, Validation & Deployment](#capitulo-v-product-implementation-validation--deployment)
	- 5.1. [Software Configuration Management](#51-software-configuration-management)
		- 5.1.1. [Software Development Environment Configuration](#511-software-development-environment-configuration)
		- 5.1.2. [Source Code Management](#512-source-code-management)
		- 5.1.3. [Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
		- 5.1.4. [Software Deployment Configuration](#514-software-deployment-configuration)
	- 5.2. [Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
		- 5.2.1. [Sprint 1](#521-sprint-1)
			- 5.2.1.1. [Sprint Planning 1](#5211-sprint-planning-1)
			- 5.2.1.2. [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
			- 5.2.1.3. [Sprint Backlog 1](#5213-sprint-backlog-1)
			- 5.2.1.4. [Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
			- 5.2.1.5. [Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
			- 5.2.1.6. [Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
			- 5.2.1.7. [Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
			- 5.2.1.8. [Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
      
	[Conclusiones](#conclusiones)

	[Bibliografía](#bibliografía)

	[Anexos](#anexos)

# Student Outcome

| Criterio específico | Giuliano Angel Pelaez Vargas | Daniel Jonatan Aquino Solorzano | Juan Carlos Pastor Napa | Johnny Alexander Ojanama Abanto | Carlos Augusto Paredes Chavez | Conclusiones |
|---------------------|------------------------------|---------------------------------|---------------------------|---------------------------------|-------------------------------|--------------|
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | Participó activamente en la definición de funcionalidades clave, contribuyendo al diseño de la arquitectura RESTful y proponiendo mejoras en la experiencia de usuario. | Apoyó en la estructuración del backlog y en la priorización de tareas, facilitando la coordinación entre frontend y backend. | Propuso ideas para la interfaz adaptable y colaboró en la integración de componentes visuales en la Landing Page. | Contribuyó en la planificación de entregables y en la validación de criterios técnicos, asegurando cumplimiento de objetivos. | Lideró la definición de segmentos, escenarios To-Be, backlog completo y modelo de datos, articulando el enfoque estratégico del proyecto. | El equipo demostró capacidad para trabajar en conjunto, definir metas claras, distribuir tareas y construir una solución coherente y funcional. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | Redactó documentación técnica sobre la arquitectura y flujos de interacción, facilitando la comprensión entre desarrolladores. | Elaboró descripciones funcionales y criterios de aceptación para las User Stories, manteniendo claridad y precisión. | Contribuyó en la redacción de fichas informativas y mensajes de interfaz, adaptados a usuarios finales. | Participó en la elaboración de escenarios y mensajes de error, comunicando con empatía y claridad. | Documentó el proyecto en formato Markdown, estructuró el User Journey Mapping, y tradujo conceptos técnicos a lenguaje accesible. | El entorno colaborativo fue efectivo en todos los niveles: técnico y funcional. Se logró transmitir el objetivo del producto entre todos los miembros del equipo |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup, Smiling Cups, es una aplicación web que conecta a amantes del café con cafeterías locales, ofreciendo un servicio de suscripciones digitales, con beneficios y promociones para los compradores, y herramientas digitales para las cafeterías para obtener métricas de consumo, llegar a más clientes y lanzar promociones. De este modo, Smiling Cups, además de dar alcance a emprendimientos cafeteros, crea una comunidad digital en torno a la experiencia cafetera, aportando valor tanto a consumidores como a los negocios.

Misión: Por un lado, ofrecemos a los amantes del café un servicio digital accesible y escalable para explorar su gusto por el café mediante beneficios exclusivos a través de un modelo de suscripciones. Por otro lado, brindamos a los negocios herramientas tecnológicas para expandir su público y fidelizar a sus clientes.

Visión: Nuestra visión es convertirnos en la plataforma líder en experiencias digitales de café, conectando a amantes del café con cafeterías a través de un ecosistema innovador que promueva la comunidad cafetera.

### 1.1.2. Perfiles de integrantes del equipo 

| Integrante                       | Código     | Carrera / Información                                                                 |
|----------------------------------|------------|----------------------------------------------------------------------------------------|
| Aquino Solorzano, Daniel Jonatan | u202217678 | Ingeniería de Software. Responsable y puntual. Conocimientos en C++ y Java.            |
| Ojanama Abanto, Johnny Alexander | u20231f412 | Ingeniería de Software. Responsable y cooperativo. Conocimientos en C++, HTML, CSS y JavaScript |
| Paredes Chavez, Carlos Augusto   | u202321613 | Ingeniería de Software. Proactivo. Conocimientos en C++ y C#.                          |
| Pastor Napa, Juan Carlos         | u202217288 | Ingenieria de Software. Creativo. Conocimientos en C++, redes, electronica y tecnico.  |
| Pelaez Vargas, Giuliano Angel    | u20221e121 | Ingeniería de Software. Solidario y enfocado. Conocimientos en C++, Python y Lua. |

## 1.2. Solution Profile 

ApoutCoffees es una plataforma en línea enfocada en la venta de cajas de misterio de café de alta calidad, que incluye cafés elegidos de pequeños proyectos peruanos.

 Su objetivo es enlazar a los consumidores con vivencias singulares de cata, proporcionando una compra digital fácil y atractiva, a la vez que otorga visibilidad y mayores beneficios a los productores locales. 

La app ofrece la opción de seleccionar entre tres clases de cajas misteriosas, cada una con un rango de precios diferente, presentadas en porciones individuales y con tarjetas informativas sobre el origen, perfiles de sabor y el proyecto detrás de cada café.

 De este modo, los consumidores encuentran nuevas opciones sin dificultades, mientras que los productores de café tienen acceso a un canal de venta en línea que aumenta su difusión del consumo local de café peruano.

### 1.2.1. Antecedentes y Problemática

Para entender mejor las necesidades de nuestros usuarios, hemos investigado sus antecedentes históricos y el problema utilizando la técnica de las 5W’s y 2H’s. Esta técnica es un método de análisis que ayuda a centrarse en las causas de un problema. Nuestro estudio se fundamenta en los antecedentes que han experimentado nuestros usuarios. A continuación, presentamos la información recopilada a través de esta técnica.  


### **What?**  
**¿Cuál es la dificultad?**  
El problema central que enfrentamos es la dificultad que tienen los consumidores para obtener cafés peruanos de pequeños agricultores de manera práctica, atractiva y contemporánea. A pesar de que Perú es conocido por la excelencia de su café, gran parte de la producción de pequeñas empresas no alcanza al consumidor final debido a la ausencia de canales de distribución innovadores. Esto restringe la visibilidad de los productores y quita a los consumidores experiencias variadas y de calidad.  

**¿Qué tipo de vínculo existe con la persona mencionada?**  
Los consumidores se ven directamente impactados al contar con escasas alternativas para encontrar cafés nuevos y diversos. Simultáneamente, los pequeños productores de café y los emprendimientos se enfrentan a dificultades en la comercialización y a la limitada accesibilidad a un mercado más extenso.  


### **When**  
**¿Cuándo ocurre el inconveniente?**  
- En el proceso de adquisición, al buscar cafés especiales, los consumidores se topan con opciones restringidas en supermercados o grandes cadenas.  
- En ocasiones de obsequio o de compra personal, cuando buscan una experiencia de alta calidad, pero no hallan opciones creativas ni asequibles.  

**¿Cuándo emplea el cliente el producto?**  
Los usuarios emplearán la aplicación web para elegir una de las 3 cajas misteriosas ofrecidas de acuerdo a su presupuesto (básica, premium o exclusiva). Emplearán el servicio tanto para uso personal como para obsequios o suscripciones mensuales.  


### **Where**  
**¿En qué lugar se encuentra el cliente al utilizar el producto?**  
El cliente ingresa desde su hogar, oficina o cualquier sitio con internet, a través de la aplicación web.  

**¿De dónde proviene el inconveniente?**  
La dificultad se presenta en la escasa participación de pequeños productores en el ámbito digital y en la carencia de plataformas que hagan de la adquisición de café una experiencia interesante y adaptada a cada cliente.  

### **Who**  
**¿Quiénes están involucrados?**  
- Pequeños productores de café peruano.  
- Consumidores interesados en experiencias premium, regalos o productos diferenciados.  
- Jóvenes profesionales y entusiastas del café.  

**¿A quiénes le sucede el problema?**  
A consumidores que buscan calidad y novedad en el café, y a productores que no logran colocar sus productos en mercados más amplios.  

**¿Quién lo utilizará?**  
El servicio será usado por consumidores nacionales e internacionales que deseen experimentar con cafés peruanos mediante un formato moderno, además de empresas que requieran regalos corporativos.  

### **Why**  
**¿Cuál es la causa principal del problema?**  
- Escasa digitalización en el sector cafetalero.  
- Dependencia de intermediarios que reducen el margen de ganancia de pequeños productores.  
- Falta de formatos innovadores de consumo (más allá de la bolsa tradicional de café).  
- Creciente demanda por experiencias de compra modernas que mezclen conveniencia digital con productos artesanales.  


### **How?**  
**¿Cómo ocurre el problema?**  
El problema ocurre porque la cadena de comercialización del café no prioriza a pequeños productores ni genera experiencias diferenciales para el consumidor final.  

**¿Cómo es percibido el problema por el usuario?**  
El consumidor percibe la compra de café como algo rutinario, poco atractivo y limitado a opciones genéricas. La falta de acceso a cafés diferenciados se siente como una barrera para explorar la riqueza del café peruano.  

**¿Cómo podemos abordar el problema?**  
**ApoutCofees** ofrece una plataforma web intuitiva que permite elegir entre tres planes de mystery boxes de café peruano. Las cajas incluyen cafés fraccionados, cartas informativas sobre el productor y notas de cata, creando una experiencia premium y educativa.  

**¿En qué condiciones los clientes usan nuestro producto?**  
- En compras digitales rápidas.  
- Al buscar un regalo premium.  
- Al desear probar nuevas variedades de café sin tener que comprar bolsas enteras.  

**¿Cómo nos conocieron los compradores?**  
- Redes sociales (Instagram, TikTok).  
- Marketing digital especializado en experiencias gourmet.  
- Recomendaciones boca a boca.  

**¿Cómo prefieren los clientes acceder al contenido?**  
A través de una aplicación web clara, con opciones simples de elección (tres cajas), información sobre cafés y posibilidad de suscripción.  

**¿Qué llevó a la persona a llegar a esta situación?**  
La necesidad de experiencias de consumo más innovadoras, la falta de acceso a cafés de pequeños emprendimientos, y el deseo de apoyar el comercio justo mientras disfrutan de un producto premium.  


### **How Much**  
- El mercado mundial de café mueve más de USD 200 mil millones anuales.  
- Perú es el noveno exportador mundial de café, con 223 mil toneladas exportadas en 2023 (SUNAT – Junta Nacional del Café).  
- Más del 90 % de los productores peruanos son pequeños caficultores, con limitadas herramientas de comercialización digital.  
- El consumo interno en Perú ha crecido un 25 % en los últimos 5 años, especialmente en el segmento de cafés especiales (Cámara Peruana del Café y Cacao).  

Esto demuestra que existe una alta demanda insatisfecha, y una oportunidad clara para **ApoutCofees** de conectar digitalmente a pequeños productores con consumidores nacionales e internacionales.  

### 1.2.2. Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements

Nuestro producto de software tiene como objetivo conectar eficazmente mediante un entorno digital a empresas cafeteras con consumidores de café. Ofreciendo funcionalidades innovadoras como entregas en forma de cajas misteriosas y contando con métricas de consumo para ayudar a las marcas con el análisis del mercado.

La problemática principalmente radica en que las marcas o empresas cafeteras peruanas (especialmente las más pequeñas) no poseen mucha visibilidad en el mercado y por consiguiente no logran llegar llegar al público objetivo. Esto genera que no consigan los ingresos esperados y sus negocios no logren conseguir el éxito empresarial.

¿Cómo podemos ayudar a las empresas cafeteras a lograr ganar visibilidad en el mercado del café para que puedan mejorar sus ingresos y sus productos puedan llegar a ser reconocidos por el consumidor objetivo?

#### 1.2.2.2. Lean UX Assumptions

- Las empresas cafeteras necesitan una herramienta digital que logre dar visibilidad a sus productos
- Estas marcas buscan que sus productos no solo se vendan bien sino que también logren transmitir y generar reconocimiento para los responsables de la producción de ese café
- Las funcionalidades creativas de la aplicación lograrán incrementar su popularidad en el mercado del café
- Los consumidores se verán atraídos por la aplicación web gracias a sus funcionalidades como las cajas misteriosas.

##### 1.2.2.2.1. Assumptions Worksheet 

**¿Quién es el usuario?**
- Empresas cafeteras peruanas que necesiten ganar visibilidad en el mercado para que sus productos lleguen mayor público
- Consumidores cotidianos de café que se vean atraídos por una aplicación que venda café de forma creativa e innovadora.
  
**¿Dónde encaja el producto en su vida?**
En la etapa de comercialización digital de café hacia el publico consumidor objetivo y al momento de realizar una búsqueda de posibles cafés para el consumo mismo del cliente de estas empresas
  
**¿Qué problemas tiene y cómo se resuelven?**
Las marcan cafeteras presentan el problema de no lograr darle la mayor visibilidad posible a sus productos debido a una falta de adaptación al mercado contemporáneo y la forma en que intentan resolver estos problemas es recurrir a mayor inversión en estrategias de Marketing y publicidad
  
**¿Cuándo y cómo se usa el producto?**
El producto se usa cuando los consumidores tienen la intención de comprar café mediante cajas misteriosas que ofrecen una experiencia atractiva para el usuario, por otro lado las marcas usarán el producto cuando necesiten saber sobre métricas y datos de consumo de sus clientes mediante las funcionalidades que ofrece la aplicación. 
  
**¿Qué características son importantes?**
  
-   Cajas misteriosas personalizables
    
-   Métodos de suscripción para funcionalidades extras y mejoradas
    
-  Catálogos de cafés y cajas misteriosas
    
-   Sección de comentarios y reseñas sobre cada café y caja misteriosa
    
-   Sección informativa sobre productores y marcas cafeteras
    
-   Métricas sobre datos de consumo de los clientes para cada empresa

**¿Cómo debe verse nuestro producto y cómo comportarse?**

La aplicación debe verse atractiva para el cliente, transmitiendo un ambiente relacionado a la razón del negocio que es el café. Debe comportarse de forma amigable e intuitiva con el usuario, demostrando que es fácil de usar y entender

##### 1.2.2.2.2. Business Outcomes 

- Incrementar los ingresos mensuales del producto mediante planes de suscripción premium a nuestros usuarios por funcionalidades agregadas y mejoradas

- Expandir las conexiones y convenios con empresas cafeteras del país para que tengamos al rededor de 50 marcas para el primer año

- Incrementar la visibilidad y reconocimiento del negocio en la mayor parte del país mediante estrategias de Marketing para seguir impulsando el crecimiento de nuestra empresa

- Incrementar el porcentaje del número de registros mensuales a la aplicación web
- Reducir el porcentaje de usuarios que dejan de usar la aplicación escuchando sus quejas y feedback que dejen en la sección de reseñas del producto 

##### 1.2.2.2.4. User Outcomes 

-   **Público Consumidor**
    
    -   Descubrir nuevos tipos de café de forma creativa y entretenida
        
    -   Disfrutar de la incertidumbre sobre los artículos que le tocarán al momento de comprar las cajas misteriosas
        
    -   Estar seguro que recibe un servicio de calidad con cafés de buena marca
        
    -   Ahorrar tiempo al poder comprar cafés de forma remota desde cualquier lugar en el que se encuentre
        
        
-   **Empresa cafetera**:
    
    -   Llegar a conectar con un mayor número de clientes sin necesidad de recurrir a grandes inversiones en Marketing.
        
    -   Obtener métricas sobre datos de consumo que le ayudan a mejorar su negocio
             
    -   Aumentar la visibilidad de su marca gracias a un entorno digital, práctico y eficaz.
        
    -   Sentirse cómodos de trabajar en torno de un ambiente digital que facilita muchas funcionalidades.

##### 1.2.2.2.5. Features

- Cajas misteriosas con artículos relacionados al café
- Catálogos de cafés con descripción de cada uno
- Sistema de compendio de cafés coleccionados 
- Sistema de logros y gamificación para el usuario consumidor
- Sección informativa sobre marcas de café y productores
- Métricas sobre datos de consumo para cada empresa cafetera 
- Sección de reseñas y comentarios para cada café y caj misteriosa
- Sección de perfil personal de usuario para ver información personal y sobre estadísticas de su cuenta
- Historial de cajas misteriosas y cafés consumidos por los usuarios consumidores

#### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.3.1. Hipótesis de Usuario

-   **Creemos que** los consumidores valorarán descubrir cafés nuevos de forma entretenida y fácil.  
    **Sabremos que es cierto cuando** veamos que al menos un 10% de las reseñas positivas de la aplicación son sobre la funcionalidad de las cajas misteriosas
    
    
-   **Creemos que** los usuarios se sentirán interesados sobre los datos del café. que reciben en las cajas misteriosas  
	**Sabremos que es cierto cuando** veamos que al menos un 15% de las reseñas positivas de la aplicación son sobre los añadidos de estos datos en las cajas misteriosas
    
    
-   **Creemos que** los clientes prefieren comprar café de forma digital y remota.  
    **Sabremos que es cierto cuando** veamos que aumentan en 60% la cantidad de ventas fuera de horario comercial presencial de las empresas
        
-   **Creemos que** los usuarios valoran la rapidez en la entrega.  
    **Sabremos que es cierto cuando** el 75% califique 4 o 5 estrellas en tiempos de entrega.
    
-   **Creemos que** los clientes quieren sentirse parte de una comunidad cafetera.  
    **Sabremos que es cierto cuando** un 30% de los usuarios publiquen en las reseñas de las aplicación que desean un entorno social y comunitario dentro de la app

##### 1.2.2.3.2. Hipótesis de Negocio

-   **Creemos que** ofrecer suscripciones en la aplicación generará buenos ingresos recurrentes.  
    **Sabremos que es cierto cuando** después de 6 hayamos aumentado los ingresos en un 60%
    
    
-   **Creemos que** incluir cafeteras conocidas atraerá más usuarios.  
    **Sabremos que es cierto cuando** veamos un crecimiento del 30% en usuarios registrados.  
   
    
-   **Creemos que** ofrecer promociones de envíos gratuitos a suscriptores aumentará la cantidad de usuarios que se registran.  
    **Sabremos que es cierto cuando** veamos un aumento del 10% en usuarios que se registran en periodos de promociones especiales
    
    
-   **Creemos que** la aplicación ganará reconocimiento gracias a las estrategias de Marketing en redes sociales
    **Sabremos que es cierto cuando** veamos un incremento del 40% de usuarios que se registran en periodos de publicación de comerciales

#### 1.2.2.4. Lean UX Canvas

![](img/lean-ux-canvas.png)

## 1.3. Segmentos Objetivo
- Segmento 1: Consumidores urbanos jóvenes y entusiastas del café
	-Perfil: Estudiantes o profesionales, edades entre 20-40 años, familiarizados con compras digitales.
	-   Necesidades:
		-   Encontrar calidad, novedad y conexión con el origen del producto.
		-   Hallar experiencias distintas con un producto familiar.
	-   Como ayuda SmilingCups:
		-   Ofrece opciones de café variadas a través de la experiencia de las "Mystery Boxes".
    
		-   Otorga visibilidad a emprendimientos de café con propuestas atractivas para un público casual.
-   Segmento 2: Marcas cafeteras peruanas de limitado acceso digital
	-   Perfil: Emprendimientos, microempresas cafeteras del Perú.
	-   Necesidades:
		-   Obtener mayor visibilidad y alcance al público cafetero.
		-   Llevar a conocer popularmente diversas propuestas con el café peruano.
	-   Como ayuda SmilingCups:
		-   Brinda los medios por los que los diversos emprendimientos cafeteros pueden darse a conocer a un público más amplio.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores 



Se identificaron hasta la fecha a 3 principales competidores para la aplicación web de nuestro startup, centrado en el mercado digital del café.

| id | nombre | descripcion general del competidor | propuesta de valor / características principales | canales de distribución / comercialización | logo_url |
|----|--------|-------------------------------------|------------------------------------------------|-------------------------------------------|----------|
| 1  | Coffee Hunters Perú | Comercializadora de cafés de especialidad dedicada a viajar a fincas de productores cafeteros peruanos para encontrar y comercializar cafés de alta calidad de manera justa | - Trazabilidad completa de los cafés<br>- Presentaciones a pequeña escala<br>- Selección directa de fincas cafeteras | - Venta directa<br>- Comercio electrónico<br>- Tiendas especializadas | ![](img/CofeeHuntersLogo.jpg) |
| 2  | Café Compadre | Marca de café de especialidad peruana con proceso de producción usando energía solar y compromiso con agricultores locales | - Café de especialidad<br>- Sostenibilidad socio-ambiental<br>- Proceso de producción con energía solar | - Venta directa<br>- Canales digitales<br>- Tiendas de productos orgánicos | ![](img/CompadreLogo.png) |
| 3  | Tunki Coffee | Cooperativa con amplia experiencia en producción de café especial, orgánico y de calidad | - Alta calidad de café<br>- Variedad de formatos de producto<br>- Café orgánico certificado | - Cooperativa de productores<br>- Comercio electrónico<br>- Distribución especializada | ![](img/TunkiLogo.jpg) |



### 2.1.1 Análisis Competitivo

<table class="tg"> <thead> <tr> <th class="tg-0pky" colspan="6">Competitive Analysis Landscape</th> </tr> </thead> <tbody> <!-- Propósito --> <tr> <td class="tg-0pky" colspan="6"><strong>Propósito del análisis:</strong> Evaluar la posición de nuestra plataforma digital de café frente a tres competidores clave del mercado peruano de café de especialidad para identificar ventajas competitivas, riesgos y tácticas prioritarias que permitan ganar cuota en el mercado.</td> </tr> <!-- Pregunta guía --> <tr> <td class="tg-0pky" colspan="6"><strong>Pregunta guía:</strong> ¿Cómo se compara nuestra plataforma digital en oferta, producto, mercado y potencial estratégico frente a Coffee Hunters Perú, Café Compadre y Tunki Coffee, y qué acciones tácticas deben priorizarse para diferenciarse y crecer?</td> </tr> <!-- Cabecera --> <tr> <td class="tg-0pky" colspan="2"></td> <td class="tg-0lax">Smiling Cups</td> <td class="tg-0pky">Coffee Hunters Perú</td> <td class="tg-0pky">Café Compadre</td> <td class="tg-0pky">Tunki Coffee</td> </tr> <!-- Perfil --> <tr> <td class="tg-0pky" rowspan="2">Perfil</td> <td class="tg-0pky">Overview</td> <td class="tg-0lax">Plataforma digital innovadora que conecta consumidores con marcas de café mediante cajas misteriosas y experiencias interactivas de descubrimiento de café.</td> <td class="tg-0pky">Comercializadora de cafés de especialidad que viaja a fincas para encontrar cafés de alta calidad.</td> <td class="tg-0pky">Marca de café de especialidad con proceso de producción sostenible usando energía solar.</td> <td class="tg-0pky">Cooperativa dedicada a la producción de café especial, orgánico y de calidad.</td> </tr> <tr> <td class="tg-0pky">Ventaja Competitiva<br>¿Qué valor ofrece a los clientes?</td> <td class="tg-0lax">- Experiencia gamificada de descubrimiento de café<br>- Cajas misteriosas personalizadas<br>- Métricas de consumo para usuarios<br>- Conectividad directa entre productores y consumidores via carta.</td> <td class="tg-0pky">- Trazabilidad completa de los cafés<br>- Selección directa de fincas<br>- Presentaciones a pequeña escala</td> <td class="tg-0pky">- Sostenibilidad socio-ambiental<br>- Proceso de producción con energía solar<br>- Compromiso con agricultores locales</td> <td class="tg-0pky">- Alta calidad de café<br>- Variedad de formatos de producto<br>- Café orgánico certificado</td> </tr> <!-- Perfil de marketing --> <tr> <td class="tg-0pky" rowspan="2">Perfil de marketing</td> <td class="tg-0pky">Mercado objetivo</td> <td class="tg-0lax">- Consumidores digitales<br>- Amantes del café<br>- Millennials y Gen Z<br>- Consumidores interesados en experiencias únicas</td> <td class="tg-0pky">- Consumidores de café de especialidad<br>- Interesados en trazabilidad<br>- Compradores conscientes</td> <td class="tg-0pky">- Consumidores ecológicos<br>- Interesados en sostenibilidad<br>- Consumidores de café premium</td> <td class="tg-0pky">- Consumidores de café gourmet<br>- Interesados en productos orgánicos<br>- Compradores de café de alta calidad</td> </tr> <tr> <td class="tg-0pky">Estrategias de marketing</td> <td class="tg-0lax">- Marketing digital<br>- Redes sociales<br>- Contenido interactivo<br>- Programa de referidos<br>- Alianzas con influencers de café</td> <td class="tg-0pky">- Storytelling de origen<br>- Marketing de contenidos<br>- Ferias de café<br>- Redes sociales especializadas</td> <td class="tg-0pky">- Marketing de sostenibilidad<br>- Eventos de concientización<br>- Redes sociales ecológicas</td> <td class="tg-0pky">- Marketing de calidad<br>- Participación en concursos de café<br>- Presentaciones en eventos especializados</td> </tr> <!-- Perfil de producto --> <tr> <td class="tg-0pky" rowspan="3">Perfil de producto</td> <td class="tg-0pky">Productos o servicios</td> <td class="tg-0lax">- Cajas misteriosas de café<br>- Plataforma digital interactiva<br>- Sistema de recomendaciones<br>- Perfil de consumo de café</td> <td class="tg-0pky">- Café de especialidad<br>- Selecciones de origen<br>- Lotes limitados</td> <td class="tg-0pky">- Café de especialidad<br>- Café con energía solar<br>- Presentaciones únicas</td> <td class="tg-0pky">- Café orgánico<br>- Diversos formatos<br>- Café de especialidad</td> </tr> <tr> <td class="tg-0pky">Precios y costos</td> <td class="tg-0lax">- Modelo de suscripción<br>- Planes flexibles<br>- Cajas con diferentes rangos de precio<br>- Opciones personalizables<br>-Opcion de entrada notablemente economica.</td> <td class="tg-0pky">- Precios premium<br>- Lotes pequeños<br>- Variabilidad de precios</td> <td class="tg-0pky">- Precios premium<br>- Enfoque en sostenibilidad<br>- Valor agregado ecológico</td> <td class="tg-0pky">- Precios altos por especialidad<br>- Diferentes rangos de precio<br>- Certificaciones orgánicas</td> </tr> <tr> <td class="tg-0pky">Canales de distribución</td> <td class="tg-0lax">- Plataforma web<br>- Aplicación móvil<br>- Entrega directa<br>- Alianzas con cafeterías</td> <td class="tg-0pky">- Comercio electrónico<br>- Tiendas especializadas<br>- Venta directa</td> <td class="tg-0pky">- Canales digitales<br>- Tiendas de productos orgánicos<br>- Venta directa</td> <td class="tg-0pky">- Comercio electrónico<br>- Distribución especializada<br>- Cooperativa</td> </tr> <!-- Análisis FODA --> <tr> <td class="tg-0pky" rowspan="4">Análisis FODA</td> <td class="tg-0pky">Fortalezas</td> <td class="tg-0lax">- Innovación tecnológica<br>- Experiencia interactiva<br>- Conexión directa productor-consumidor<br>- Métricas personalizadas</td> <td class="tg-0pky">- Conocimiento directo de origen<br>- Selección cuidadosa<br>- Relaciones con productores</td> <td class="tg-0pky">- Compromiso ambiental<br>- Proceso de producción único<br>- Imagen de marca ecológica</td> <td class="tg-0pky">- Reconocimiento de mercado<br>- Calidad consistente<br>- Experiencia en producción</td> </tr> <tr> <td class="tg-0pky">Debilidades</td> <td class="tg-0lax">- Plataforma nueva<br>- Necesidad de construir confianza<br>- Dependencia de tecnología<br>- Curva de aprendizaje para usuarios</td> <td class="tg-0pky">- Volatilidad de sabores<br>- Inconsistencia en lotes<br>- Escala limitada</td> <td class="tg-0pky">- Precios más altos<br>- Disponibilidad limitada<br>- Mercado reducido</td> <td class="tg-0pky">- Poca presencia digital<br>- Precios elevados<br>- Diversificación limitada</td> </tr> <tr> <td class="tg-0pky">Oportunidades</td> <td class="tg-0lax">- Crecimiento del mercado digital<br>- Interés en experiencias personalizadas<br>- Consumidores digitales emergentes<br>- Tendencia hacia consumo consciente</td> <td class="tg-0pky">- Interés en trazabilidad<br>- Consumidores conscientes<br>- Mercado de especialidad en crecimiento</td> <td class="tg-0pky">- Conciencia ambiental<br>- Preferencia por sostenibilidad<br>- Consumidores eco-friendly</td> <td class="tg-0pky">- Crecimiento de café de especialidad<br>- Demanda de productos orgánicos<br>- Interés en calidad</td> </tr> <tr> <td class="tg-0pky">Amenazas</td> <td class="tg-0lax">- Competencia tecnológica<br>- Cambios rápidos en preferencias digitales<br>- Barrera de entrada tecnológica<br>- Posible saturación de mercado</td> <td class="tg-0pky">- Competencia de grandes marcas<br>- Volatilidad de precios<br>- Cambio climático</td> <td class="tg-0pky">- Altos costos de producción<br>- Competencia de marcas tradicionales<br>- Precios poco competitivos</td> <td class="tg-0pky">- Entrada de nuevos competidores<br>- Presión de precios<br>- Regulaciones cambiantes</td> </tr> </tbody> </table>
	  
- 
	  
- 
### 2.1.2. Estrategias y tácticas frente a competidores

-   **Diferenciación de producto:** Mystery box interactivas, algo que los competidores no ofrecen.
    
-   **Estrategia de precio:** Planes de suscripción flexibles y promociones exclusivas para fidelizar usuarios.
    
-   **Táctica digital:** Campañas en Instagram y TikTok para atraer a un público joven urbano.
        

## 2.2. Entrevistas

---

### 2.2.1. Diseño de entrevistas

**Perfil:** Consumidores urbanos jóvenes y entusiastas del café.  
**Necesidades:** Encontrar novedad y experienias variadas en un producto conocido, el café.

**Preguntas de entrevista:**
-   ¿Qué tipo de café sueles consumir y dónde lo compras normalmente?  
-   ¿Has probado alguna vez cafés de origen peruano de pequeños productores?  
-   ¿Qué te parecería recibir una "Mystery Box" con cafés seleccionados y fichas informativas de cada uno?  
-   ¿Qué factores te motivarían a tener una suscripción a un servicio mensual de café?  
-   ¿Qué tan importante es para ti conocer la historia detrás del producto que consumes?  
-   ¿Qué elementos visuales o de diseño te llaman la atención de una aplicativo de café?  
-   ¿Usarías esta app como opción de regalo? ¿Qué te gustaría que incluya para que sea especial?

 **Perfil:** Marcas cafeteras peruanas de limitado acceso digital.  
**Necesidades:** Obtener visibilidad y aumentar su alcance al público cafetero.

**Preguntas de entrevista:**
-   ¿Qué canales usas actualmente para vender tus productos?  
-   ¿Has probado utilizar las redes sociales para vender el café? ¿Qué funcionó y qué no?  
-   ¿Qué te parecería formar parte de una plataforma que promocione tus productos a través de mystery Boxes junto a otros productores?  
-   ¿Qué información te gustaría que los consumidores conozcan sobre tu marca y tu café?  
-   ¿Qué tipo de apoyo necesitarías para participar en una plataforma digital como SmilingCups? 
-   ¿Cómo mides actualmente el impacto o éxito de tus ventas? ¿Te interesaría acceder a métricas de consumo?  
-   ¿Qué esperas de una alianza con una plataforma como esta? ¿Qué beneficios te parecerían justos?

### 2.2.2. Registro de entrevistas

___-Segmento Objetivo 1___

__Entrevista 1 (Alejandro)__

+ Nombre: Alejandro
+ Edad: 21
+ Distrito de residencia: La Molina

**Resumen de Entrevista :**
Alejandro, 21 años y residente en La Molina, consume café de forma ocasional y no suele ser quien lo compra, ya que prefiere que su hermana se encargue. Está dispuesto a probar cafés de pequeños productores y le interesa la idea de recibir una "mystery box" mensual con selecciones distintas; sin embargo, duda sobre si conocer la historia u origen del café le aportaría valor.

[![Alejandro](https://img.youtube.com/vi/0xvz6TSRT1g/hqdefault.jpg)](https://www.youtube.com/watch?v=0xvz6TSRT1g)

---

__Entrevista 2 (Franco Matías Flores)__

+ Nombre: Franco Matías Tasayko Flores
+ Edad: 20
+ Distrito de residencia: San Borja

**Resumen de Entrevista :**
Franco Matías Tasayko Flores, de 20 años, tiene una relación con el café marcada por la tradición familiar: su abuela solía tomarlo habitualmente, lo que dejó una impronta en su experiencia aunque él no sea un gran consumidor. A pesar de su bajo consumo personal, muestra disposición a explorar y probar cafés de pequeños productores, lo que sugiere interés por la autenticidad, la trazabilidad y el valor artesanal del producto. Le resulta atractiva la idea de recibir una Mystery Box de café, lo que revela curiosidad sensorial y una preferencia por experiencias de descubrimiento más que por la lealtad a una marca o perfil de sabor concreto. En conjunto, esto indica que, aunque su consumo actual es limitado, Franco es un consumidor potencialmente receptivo a estrategias de marketing basadas en la exploración, las muestras y las historias sobre origen y productores; la influencia familiar explica la familiaridad y la apertura inicial, mientras que su interés en pequeños productores y formatos sorpresa denota una motivación más experiencial y ética que puramente funcional.

[![Franco](https://img.youtube.com/vi/XfWcetDSuqM/hqdefault.jpg)](https://www.youtube.com/watch?v=XfWcetDSuqM)

---

___-Segmento Objetivo 2___

__Entrevista 3 (Jhonatan Murga Abad)__

+ Nombre: Jhonatan Murga Abad
+ Edad: 34
+ Distrito de residencia: San Miguel
+ Sector: Producción y comercialización de café

**Resumen de Entrevista :**
Jhonatan Murga Abad, ingeniero agroindustrial, comparte la experiencia de comercializar el café familiar; actualmente vende principalmente a través de distribuidores y por WhatsApp, con un volumen modesto y una fuerte dependencia de intermediarios, lo que limita su control sobre precio, posicionamiento y la relación directa con el cliente. El principal cuello de botella es la logística: sin una solución de distribución directa, llegar al consumidor final resulta difícil y frena el crecimiento. Aunque utiliza canales digitales básicos como WhatsApp, no cuenta con una estrategia digital robusta —no hay tienda en línea, presencia comercial estructurada en marketplaces ni métricas claras— y por eso carece de datos sobre preferencias de los clientes, presentaciones o sabores más aceptados y la sensibilidad al precio. Muestra interés en modelos innovadores como el Mystery Box para diversificar la oferta y captar clientes finales, pero su implementación depende de solucionar la logística y la distribución. En conjunto, la falta de métricas y canales directos dificulta la toma de decisiones informadas y la escalabilidad; las prioridades inmediatas serían resolver la cadena de distribución, construir canales digitales que permitan vender directo al consumidor y recopilar datos de clientes para optimizar presentaciones, precios y promociones.

[![Jhonatan](https://img.youtube.com/vi/_B5XOJWkT_A/hqdefault.jpg)](https://www.youtube.com/watch?v=_B5XOJWkT_A)

---

__Entrevista 4 (Toby Dextre)__

+ Nombre: Toby Dextre
+ Edad: 23
+ Distrito de residencia: Surco
+ Sector: Emprendimiento de café

**Resumen de Entrevista :**
Dextre, un estudiante que vende café por Instagram; comenzó por necesidad económica y usa la plataforma para mostrar su producto, pero aunque recibe muchas vistas le cuesta convertirlas en ventas porque su alcance se limita a su círculo cercano y los compradores dudan por falta de confianza y desconocimiento del proceso; él prepara, empaqueta y entrega el café personalmente y atiende por mensajes, lo que facilita la comunicación pero le consume tiempo y choca con sus responsabilidades universitarias, por lo que necesita mejores herramientas para pago y envío, reseñas que generen confianza y una plataforma que conecte a pequeños vendedores con consumidores interesados para aumentar visibilidad y reducir la carga operativa.

[![Toby Dextre](https://img.youtube.com/vi/DbTSV1g-nlQ/hqdefault.jpg)](https://www.youtube.com/watch?v=DbTSV1g-nlQ)

---

__Entrevista 5 (Kory Milagros)__

+ Nombre: Kory Milagros
+ Edad: 48
+ Distrito de residencia: Surquillo
+ Sector: Comercialización de café

**Resumen de Entrevista :**
Kory Milagros cuenta su experiencia vendiendo café principalmente a través del boca a boca y WhatsApp, lo que evidencia que su clientela se construye por confianza personal y redes locales; esto sugiere que una plataforma que conecte vendedores con consumidores y ofrezca pagos seguros y logística confiable podría escalar su modelo sin romper esas relaciones directas. Además, la idea de las Mystery Boxes aparece como una oportunidad para que Kory aumente la visibilidad de productos menos conocidos y fomente la prueba por parte de nuevos clientes, aunque requiere atención en la gestión de expectativas, control de calidad y trazabilidad para mantener la satisfacción y fidelidad. En resumen, su trayectoria muestra potencial para formalizar ventas informales si se le brinda soporte tecnológico y operativo que preserve la confianza que hoy logra personalmente.

[![Kory Milagros](https://img.youtube.com/vi/1e-uGAnfACk/hqdefault.jpg)](https://www.youtube.com/watch?v=1e-uGAnfACk)


### 2.2.3. Análisis de entrevistas

**Segmento Objetivo 1:**

Este segmento está compuesto por consumidores jóvenes (21 y 20 años) que tienen un consumo ocasional o limitado de café, pero muestran apertura hacia la exploración y la prueba de productos de pequeños productores. La motivación principal es experiencial y curiosa: la "Mystery Box" les atrae como formato novedoso y lúdico, más que por la necesidad de un consumo constante. La complejidad radica en que su consumo no es rutinario ni estable, lo que implica que la fidelización no puede basarse en el hábito, sino en propuestas que refuercen la experiencia, la sorpresa y la conexión emocional. Aunque son receptivos, requieren estrategias de comunicación claras y atractivas para convertir interés en compra efectiva.



**Segmento Objetivo 2:**


Este segmento está conformado por productores y microemprendedores (34, 23 y 48 años) que comercializan café de manera directa, con canales digitales básicos y alta dependencia de confianza personal o distribuidores. Su principal reto es operativo: logística, pagos seguros, confianza del cliente y escalabilidad. La complejidad aquí está en la falta de estructura digital y de métricas que permitan tomar decisiones informadas. Aunque muestran apertura a innovaciones como la Mystery Box, la prioridad es resolver la cadena de distribución, formalizar canales de venta y contar con herramientas tecnológicas que simplifiquen su operación. Son un segmento con necesidades prácticas y urgentes, lo que los hace sensibles al soporte en infraestructura más que al marketing experiencial.

## 2.3 Needfinding

### 2.3.1. User Personas
- Segmento 1 : Consumidores

![User persona - Segmento 1](img/1s.png)


-Segmento 2: Negocios

![User persona Julio - Segmento 2](img/2.png)


### 2.3.2. User Task Matrix

#### 🧍 Segmento 1: Jóvenes exploradores de café (20–21) motivados por experiencias y sorpresa

| Tarea principal                                                     | Frecuencia     | Importancia |
|---------------------------------------------------------------------|----------------|-------------|
| Descubrir y explorar “Mystery Boxes” interesantes                   | Frecuente      | Alta        |
| Leer descripciones claras y visuales sobre la experiencia           | Frecuente      | Alta        |
| Comprar una Mystery Box puntual (no suscripción)                   | Ocasional      | Alta        |
| Valorar/compartir la experiencia (reseña, redes)                    | Ocasional      | Media       |
| Guardar productos/marcas para una futura compra                     | Ocasional      | Media       |
| Gestionar métodos de pago y dirección de envío                      | Una vez / Rara | Media       |
| Resolver dudas rápidas (precio final, envíos, tiempos)              | Frecuente      | Alta        |
| Recibir recomendaciones personalizadas sin fricción                 | Frecuente      | Media       |
| Consultar estado de pedido y tracking                               | Ocasional      | Media       |

**Notas:**  
En este segmento, la motivación es la experiencia y la sorpresa, no el hábito de consumo. La claridad del valor y la narrativa pesan mucho en la conversión.

---

#### 🧑‍💼 Segmento 2: Microemprendedores/productores de café (23–48) con retos operativos y de digitalización

| Tarea principal                                                             | Frecuencia | Importancia |
|-----------------------------------------------------------------------------|------------|-------------|
| Publicar/actualizar inventario y características del café                   | Frecuente  | Alta        |
| Configurar precios, descuentos y disponibilidad                             | Frecuente  | Alta        |
| Gestionar pedidos: confirmación, preparación, despacho                      | Frecuente  | Alta        |
| Coordinar logística y seguimiento de envíos                                 | Frecuente  | Alta        |
| Cobrar y conciliar pagos (reportes, liquidaciones)                          | Frecuente  | Alta        |
| Atender mensajes/consultas de clientes                                      | Frecuente  | Media       |
| Revisar métricas básicas (ventas, conversión, stock)                        | Semanal    | Alta        |
| Mantener perfil/marca (fotos, descripciones, certificaciones)               | Ocasional  | Media       |
| Gestionar devoluciones o incidencias                                        | Ocasional  | Media       |
| Integrar herramientas externas mínimas (pagos, envíos)                      | Variable   | Alta        |

---
### 2.3.3. User Journey Mapping


**Segmento 1: Consumidor**

![](img/JourneyMap1.png)

**Segmento 2: Negocio**

![](img/JourneyMap2.png)

### 2.3.4. Empathy Mapping

Empathy Map - Segmento 1 

![](img/empathyMap1.png)

Empathy Map - Segmento 2
![](img/empathyMap2.png)

### 2.3.5. As-is Scenario Mapping

As-Is Scneario Map - Segmento 1:

![](img/1.png)

As-Is Scneario Map - Segmento 2:
![](img/2s.png)

## 2.3. Big Picture Event Storming

En esta sección nos enfocamos en modelar los flujos de actividad que pudieran darse dentro de nuestra aplicación, denotando elementos claves que no ayudarán a tener un mejor panorama del diseño a nivel generar de la esta aplicación Web. Se debe de tomar en cuenta que esta fase se puede interpretar como un bosquejo de lo que vendría a ser la siguiente fase del Event Storming, la cual se verá más adelante. Nos enfocaremos en mostrar eventos del dominio pero a una escala general, para de esa forma recién profundizar estos elementos en la siguiente fase. 

Para comenzar, se describen los elementos que serán vistos en el Big Picture Event Storming, donde se decribe a manera de leyenda cual es la función de cada uno de estos elementos y como están modelados dentro de los flujos de eventos.

-   **Evento:**  Representados mediante un post-it naranja, representan un evento de dominio y están en verbo pasado, sirven para identificar de forma precisa que evento ocurrió dentro de la aplicación. 
    
-   **Actor:**  Representados mediante un post-it amarillo, son los que modelan a aquellos actores que están involucrados en el flujo de los eventos del dominio. Tener en cuenta que contamos con dos tipos de actores, los User , para identificar a cualquier persona que interactua con la plataforma, y el System, que simboliza a la aplicación en si y se refiere a que el sistema se va a encargar de la activación de los eventos relacionados a este.
    
-   **Vista:**  Representadas mediante un post-it verde, vendrían a ser las interfaces de gráficas que conectan a nuestros usuarios con la aplicación Web.

- **Punto de quiebre:** Representadas mediante un post-it rosa, vendrían a ser las inconsistencias y dudas que quedan abiertas al momento de diseñar el event storming. Deben solventarse para las futuras versiones.

- **Sistemas Externos:** Representadas mediante un post-it rojo, representan a los sistemas que nos ayudan en procesos complejos que no convendría diseñarlos desde cero para no "reinventar la rueda". Estos sistemas son muy útiles en procesos clásicos como mensajería y métodos de pago.

A continuación se muestran las capturas del Big Picture Event Storming, donde clasificamos los flujos de eventos de acuerdo a los Bounded Context a los que podrían pertenecer.

<br>

**Bounded Context Marketplace**

![](img/bp-event-storming/marketplace/marketplace-1.png)

En este bounded context se aprecian flujos de eventos que denotan funcionalidades como el filtrado de resultados que se pueden mostrar en la marketplace, métodos de ordenamiento según el usuario o de forma automática y por último el proceso de añador una previsualización de las mistery boxes para que solo se trabaje con un concepto abstraido de estas que le sirvan al Bounded Context.

<br>

**Bounded Context Mistery Box**

![](img/bp-event-storming/mistery-box/mistery-box-1.png)

Aquí se puede ver por un lado el flujo para poder realizar la compra de una mistery box, donde se calcula el precio total teniendo en cuenta descuentos que el usuario puede tener de su suscripción. Además, se ven flujos para la visualización de contenido relacionado a mistery boxes y la creación de estas.
	
<br>

**Bounded Context Profile**

![](img/bp-event-storming/profile/profile-1.png)

En esta captura se ven flujos de eventos que denotan funcionalidades de visualización de contenido dentro del perfil del usuario, como las sugerencias, el historial de mistery boxes comprados, entre otros. Además, se puede ver un punto de quiebre, debido a que se debe aclarar bien el significado de "preference" para que no sea ambiguo.

![](img/bp-event-storming/profile/profile-2.png)

Aquí  vemos procesos para la actualización de datos del perfil del usuario la funcionalidad de mostrar métricas de consumo de su cuenta.

<br>

**Bounded Context IAM**

![](img/bp-event-storming/iam/iam-1.png)

Se pueden ver procesos genéricos para el registro y tipos de login que puede realizar el usuario, donde se contacta con sistemas externos para la autenticación del correo del usuario.

<br>

**Bounded Context Notification**

![](img/bp-event-storming/notification/notification-1.png)	

Vemos procesos generales para las notificaciones que se puedan generar dentro de la aplicación, algunas de estas también desembocan en la utilización de SendGrid como sistema externo de mensajeria.

<br>

**Bounded Context Subscription**

![](img/bp-event-storming/subscription/subscription-1.png)	

Vemos dos procesos para funcionalidades relacionadas a la suscripción del usuario, donde se utilizan métodos de un sistema externo, en este caso Stripe, para gestionar los pagos.



## 2.4. Ubiquitous Language

Para mantener consistencia en el desarrollo y comunicación del proyecto, se definieron los siguientes términos comunes dentro del equipo:

-   **Mystery Box:** Caja de suscripción con cafés seleccionados al azar de pequeños productores peruanos.
    
-   **Productores:** Cafeterías locales o microempresas proveedoras de café.
    
-   **Consumidores:** Usuarios que adquieren las mystery boxes mediante la plataforma web.
    
-   **Suscripción:** Modelo de pago recurrente mensual que da acceso a beneficios adicionales.
    
-   **Ficha de Café:** Documento digital o físico con la información de origen, notas de cata y productor.
    
-   **Dashboard de métricas:** Panel digital que muestra a los productores información sobre ventas, reseñas y comportamiento de consumidores.
    
-   **Gamificación:** Elementos lúdicos como logros, insignias y colecciones de cafés para aumentar la retención del usuario.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories

|Epic/Story ID|Título|Descripción|Criterios de Aceptación|Relacionado con (Epic ID)|
|--|--|--|--|--|
|US01|**Registro de Usuario**|**Como consumidor** **Quiero poder** registrarme en SmilingCups **para** crear un perfil dentro del aplicativo.|**Scenario 1** <br>**DADO QUE** soy un nuevo usuario, <br>**CUANDO** ingreso mis datos y confirmo el registro, <br>**ENTONCES** se crea mi cuenta y puedo acceder a la plataforma.<br><br>**Scenario 2** <br>**DADO QUE** ya tengo cuenta, <br>**CUANDO** intento registrarme con el mismo correo, <br>**ENTONCES** el sistema me sugiere iniciar sesión.|EP01|
|US02|**Inicio de sesión**|**Como usuario registrado** **Quiero poder** iniciar sesión fácilmente **para** acceder a mis cajas y suscripciones.|**Scenario 1** <br>**DADO QUE** tengo una cuenta, <br>**CUANDO** ingreso mis credenciales, <br>**ENTONCES** accedo a mi panel de usuario.|EP01|
|US03|**Explorar Mystery Boxes**|**Como consumidor** **Quiero poder** explorar las opciones de las Mystery Boxes **para** elegir la que más llame mi atención o se adapte a mi presupuesto.|**Scenario 1** <br>**DADO QUE** estoy en la sección "Mystery Boxes", <br>**CUANDO** navego entre las opciones y hago clic en la imagen de una, <br>**ENTONCES** puedo ver detalles, precios y perfiles de sabor.|EP02|
|US04|**Ver ficha informativa del café**|**Como consumidor** **Quiero poder** ver la historia y perfil de cada café incluido **para** conocer más sobre su origen y sabor.|**Scenario 1** <br>**DADO QUE** selecciono una caja, <br>**CUANDO** abro la ficha de un café, <br>**ENTONCES** veo información sobre el productor, región y notas de cata.|EP02|
|US05|**Poder suscribirse a cajas mensuales**|**Como consumidor** **Quiero poder** suscribirme a una caja mensual **para** recibir café de forma automática y sin complicaciones.|**Scenario 1** <br>**DADO QUE** estoy en la sección de suscripciones, <br>**CUANDO** elijo una caja y confirmo el pago, <br>**ENTONCES** se activa mi suscripción mensual.|EP02|
|US06|**Cancelar suscripción**|**Como consumidor** **Quiero poder** cancelar mi suscripción en cualquier momento **para** tener control sobre mis compras.|**Scenario 1** <br>**DADO QUE** tengo una suscripción activa, <br>**CUANDO** accedo a mi perfil y selecciono cancelar, <br>**ENTONCES** se detiene la renovación automática.|EP02|
|US07|**Regalar una Mystery Box**|**Como consumidor** **Quiero poder** enviar una Mystery Box como regalo **para** sorprender a alguien con una experiencia de café.|**Scenario 1** <br>**DADO QUE** quiero regalar una caja, <br>**CUANDO** ingreso los datos del destinatario y pago, <br>**ENTONCES** se envía la caja con una nota personalizada.|EP02|
|US08|**Aceptar o rechazar una Mystery Box**|**Como consumidor** **Quiero poder** aceptar o rechazar una Mystery Box como regalo **para** confirmar la posibilidad de recibirlo o no.|**Scenario 1** <br>**DADO QUE** recibo una notificación de "Propuesta de Regalo de **Usuario**", **CUANDO** le hago clic al botón "Aceptar Regalo" y relleno los datos requeridos, <br>**ENTONCES** el sistema muestra el mensaje "Regalo Aceptado". <br> <br>**Scenario 2** <br>**DADO QUE** recibo una notificación de "Propuesta de Regalo de **Usuario**", <br>**CUANDO** le hago clic al botón "Denegar Regalo", <br>**ENTONCES** el sistema muestra el mensaje "Regalo No Aceptado".|EP02|
|US09|**Definir zona de entrega**|**Como consumidor** **Quiero brindar** a la app una ubicación de entrega a través de un mapa **para** poder recibir o enviar las Mystery Boxes que ordene.|**Scenario 1** <br>**DADO QUE** estoy generando un pedido de una Mystery Box y entro al apartado "Entrega", <br>**CUANDO** en el mapa de la aplicación escribo la dirección correcta y hago clic en "Aceptar", <br>**ENTONCES** el sistema muestra el mensaje "Ubicación recibida correctamente".<br><br>**Scenario 2** <br>**DADO QUE** estoy generando un pedido de una Mystery Box y entro al apartado "Entrega", <br>**CUANDO** en el mapa de la aplicación escribo una dirección incorrecta o fuera de alcance, <br>**ENTONCES** el sistema muestra el mensaje "Pruebe otra ubicación".|EP01|
|US10|**Dejar una reseña**|**Como consumidor** **Quiero poder** dejar una reseña sobre un producto o Mystery Box que probé **para** compartir mi experiencia con otros.|**Scenario 1** <br>**DADO QUE** recibí una caja, <br>**CUANDO** accedo a la sección de reseñas, <br>**ENTONCES** puedo escribir mi opinión y calificar.|EP02|
|US10|**Filtrar Mystery Boxes por perfil de sabor**|**Como consumidor** **Quiero poder** filtrar las cajas por perfil de sabor **para** encontrar opciones que se alineen con mis preferencias.|**Scenario 1** <br>**DADO QUE** estoy en la sección de "Mystery Boxes", <br>**CUANDO** uso el filtro de sabor, <br>**ENTONCES** solo se muestran las cajas que coinciden.|EP02|
|US11|**Ver métricas de consumo**|**Como marca cafetera** **Quiero poder** ver métricas de consumo de mis cafés **para** entender mejor a mis clientes.|**Scenario 1** <br>**DADO QUE** soy productor registrado, <br>**CUANDO** accedo a mi panel, <br>**ENTONCES** veo estadísticas de ventas, reseñas y preferencias.|EP03|
|US12|**Registrar perfil de productor**|**Como productor** **Quiero poder** registrar una cuenta como productor en el aplicativo **para** tener funcionalidades distintas a las de un usuario consumidor.|**Scenario 1** <br>**DADO QUE** soy productor, <br>**CUANDO** le doy clic a "Crear cuenta como Productor" y lleno los datos necesarios, <br>**ENTONCES** el sistema muestra el mensaje "Cuenta creada exitosamente" y accedo a funcionalidades especiales para productores.|EP03|
|US13|**Generar muro propio de marca cafetera**|**Como productor** **Quiero poder** tener un muro propio sobre mi marca cafetera **para** tener un espacio específico para mis productos que ofrezca.|**Scenario 1** <br>**DADO QUE** soy productor, <br>**CUANDO** ingreso a mi perfil, <br>**ENTONCES** el sistema muestra el nombre de mi marca y la opción de realizar publicaciones o ver las ya realizadas.|EP03|
|US14|**Subir perfil de marca cafetera**|**Como productor** **Quiero poder** subir información sobre mi marca y café **para** que los consumidores conozcan mi historia.|**Scenario 1** <br>**DADO QUE** soy productor, <br>**CUANDO** ingreso mi información y la guardo, <br>**ENTONCES** se publica mi perfil en la app.|EP03|
|US15|**Recibir notificaciones de pedidos**|**Como productor** **Quiero recibir** alertas cuando se incluya mi café en un pedido realizado por un usuario **para** estar al tanto de la demanda.|**Scenario 1** <br>**DADO QUE** mi café fue seleccionado, <br>**CUANDO** se genera un pedido, <br>**ENTONCES** recibo una notificación en mi panel con los datos del pedido.|EP03|
|US16|**Crear Mystery Box**|**Como productor** **Quiero generar** una Mystery Box propio con productos propios **para** promocionar mi marca entre usuarios siguiendo la dinámica principal del aplicativo.|**Scenario 1** <br>**DADO QUE** deseo promocionar nuevas propuestas cafeteras, <br>**CUANDO** hago clic en "Generar Mystery Box" y lleno los datos de los productos que incluirá esa Mystery Box, le coloco un nombre especial y hago clic en "Aceptar", <br>**ENTONCES** el sistema muestra en mi perfil la Mystery Box nueva.|EP03|
|US17|**Ver ranking de cafés más valorados de una marca**|**Como consumidor** **Quiero poder** ver cuáles son los cafés más valorados de una marca en su perfil **para** descubrir opciones populares.|**Scenario 1** <br>**DADO QUE** estoy explorando opciones de café en un perfil de una marca, <br>**CUANDO** accedo a la sección "Populares", <br>**ENTONCES** veo los más pedidos por otros usuarios.|EP02|
|US18|**Marcar o desmarcar cafés favoritos**|**Como consumidor** **Quiero poder** guardar cafés y demás productos que me gustaron **para** tenerlos ubicados para volver a comprarlos en el futuro.|**Scenario 1** <br>**DADO QUE** probé un café que me gustó, <br>**CUANDO** hago clic en el botón con logo de estrella amarilla, <br>**ENTONCES** se guarda en la sección de "Favoritos" de mi perfil.<br><br>**Scenario 2** <br>**DADO QUE** guardé un café como favorito, <br>**CUANDO** estoy en la sección de "Favoritos" y hago clic en el botón de tacho de basura de uno de los productos, <br>**ENTONCES** se elimina de la sección de "Favoritos" de mi perfil.|EP02|
|US19|**Ver historial de Mystery Boxes o productos recibidos**|**Como usuario** **Quiero poder** ver mi historial de productos recibidas con los productos recibidos **para** recordar qué cafés probé.|**Scenario 1** <br>**DADO QUE** tengo una cuenta, <br>**CUANDO** accedo a mi perfil al apartado "Historial", <br>**ENTONCES** veo las Mystery Boxes y cafés que recibí.|EP02|
|US20|**Hacer pedidos desde el historial**|**Como usuario** **Quiero poder** ordenar Mystery Boxes u otros productos desde el historial **para** repetir pedidos rápidamente.|**Scenario 1** <br>**DADO QUE** estoy en el apartado "Historial" de mi perfil, <br>**CUANDO** hago clic en "Repetir Experiencia" en una de las opciones y sí está disponible ese producto, <br>**ENTONCES** el sistema me permite realizar el pedido tranquilamente.<br><br>**Scenario 2** <br>**DADO QUE** estoy en el apartado "Historial" de mi perfil, <br>**CUANDO** hago clic en "Repetir Experiencia" en una de las opciones, pero no está disponible ese producto, <br>**ENTONCES** el sistema no me permite realizar el pedido.|EP02|
|US21|**Tener marcadas los productos según disponibilidad**|**Como usuario** **Quiero poder** observar si un producto está disponible desde el historial **para** evitar hacer un pedido que no voy a recibir.|**Scenario 1** <br>**DADO QUE** estoy en el apartado "Historial" de mi perfil, <br>**CUANDO** un producto, sea una Mystery Box u otro, y sí está disponible, <br>**ENTONCES** el sistema muestra el producto a color y es clickeable.<br><br>**Scenario 2** <br>**DADO QUE** estoy en el apartado "Historial" de mi perfil, <br>**CUANDO** un producto, sea una Mystery Box u otro, y no está disponible, <br>**ENTONCES** el sistema muestra el producto en escala de grises y no es clickeable.|EP02|
|US23|**Establecer como disponibles o no ciertos productos realizadas**|**Como productor** **Quiero poder** establecer como disponibles o no productos de temporada, incluyendo Mystery Boxes **para** evitar pedidos de productos que no hay.|**Scenario 1** <br>**DADO QUE** tengo una cuenta "Productor" y estoy en la sección "Productos", <br>**CUANDO** un producto no está disponible y hago clic en "Habilitar Pedidos", <br>**ENTONCES** el sistema muestra los productos a color y habilita los pedidos.<br><br>**Scenario 2** <br>**DADO QUE** tengo una cuenta "Productor" y estoy en la sección "Productos", <br>**CUANDO** un producto está disponible y hago clic en "Deshabilitar Pedidos", <br>**ENTONCES** el sistema muestra los productos en gris e inhabilita los pedidos.|EP03|
|US24|**Ver historial de Mystery Boxes realizadas**|**Como productor** **Quiero poder** ver mi historial de Mystery Boxes realizadas con productos propios **para** volver a promocionarlas más adelante.|**Scenario 1** <br>**DADO QUE** tengo una cuenta "Productor", <br>**CUANDO** accedo a mi perfil al apartado "Historial de Vendidos", <br>**ENTONCES** el sistema muestra las Mystery Boxer que realicé anteriormente.|EP03|
|US25|**Acceder desde cualquier dispositivo**|**Como usuario** **Quiero poder** usar la app desde cualquier dispositivo **para** comprar café en cualquier momento.|**Scenario 1** <br>**DADO QUE** tengo cuenta, <br>**CUANDO** ingreso desde mi laptop o celular, <br>**ENTONCES** puedo acceder sin problemas.|EP01|
|US26|**Recibir recomendaciones personalizadas**|**Como consumidor** **Quiero recibir** sugerencias de cajas según mis gustos **para** descubrir nuevas opciones.|**Scenario 1** <br>**DADO QUE** tengo historial de consumo, <br>**CUANDO** accedo a la app, <br>**ENTONCES** veo recomendaciones basadas en mis preferencias.|EP02|
|US27|**Ver mapa de emprendimientos de cafés**|**Como consumidor** **Quiero ver** un mapa interactivo con la ubicación de los emprendimientos disponibles **para** conocer su procedencia.|**Scenario 1** <br>**DADO QUE** deseo tener una experiencia presencial en un emprendimiento que descubrí en el aplicativo, <br>**CUANDO** abro el mapa, <br>**ENTONCES** veo la ubicación marcada en el mapa con el texto con su título.|EP02|
|US28|**Activar o Desactivar Notificaciones de un Productor**|**Como consumidor** **Quiero poder** activar o desactivar notificaciones de la cuenta de un productor **para** notificarme de sus publicaciones. |**Scenario 1** <br>**DADO QUE** deseo saber cuanto antes las publicaciones y novedades de una cuenta de productor, <br>**CUANDO** voy a su perfil y le doy al botón "Seguir", <br>**ENTONCES** el sistema muestra el mensaje "Siguiendo Cuenta".<br><br>|**Scenario 2** <br>**DADO QUE** ya no deseo seguir la cuenta de un productor, <br>**CUANDO** voy a su perfil y le doy al botón "Dejar de seguir", <br>**ENTONCES** el sistema muestra el mensaje "Ya no sigues esta cuenta".|EP02|
|US29|**Recibir notificaciones sobre nuevos lanzamientos de una marca**|**Como usuario** **Quiero recibir** una notificación de novedades y lanzamientos de una marca en específico **para** estar al tanto de nuevas experiencias que pueda ofrecerme.|**Scenario 1** <br>**DADO QUE** activé las notificaciones de una cuenta de Productor, <br>**CUANDO** hay novedades, <br>**ENTONCES** recibo la notificación con un avance.|EP02|
|US30|**Panel de control para productores**|**Como marca cafetera**  **Quiero tener** un panel de control personalizado **para** gestionar mi perfil, cafés y métricas.|**Scenario 1** <br>**DADO QUE** soy productor registrado, <br>**CUANDO** accedo a mi panel, <br>**ENTONCES** puedo ver y editar mi información, cafés y estadísticas.|EP03| 
|US31|**Subir nuevos cafés al catálogo**|**Como productor** **Quiero poder** subir nuevos cafés al sistema **para** que sean considerados en futuras cajas.|**Scenario 1** <br>**DADO QUE** tengo nuevos lotes, <br>**CUANDO**  ingreso los datos y fotos, <br>**ENTONCES**  se agregan al catálogo de selección.|EP03|
|US32|**Agregar o borrar comentarios a creadores**|**Como cliente** **Quiero poder** agregar o borrar comentarios sobre cafés y demás productos de ciertas cuentas **para** dar feedback sobre sus productos.|**Scenario 1** <br>**DADO QUE** quiero escribir algo sobre un producto de un productor, <br>**CUANDO** accedo a la sección de "Comentarios" en su perfil y hago clic en un espacio para escribir, <br>**ENTONCES** puedo escribir una reseña.<br><br>**Scenario 2** <br>**DADO QUE** quiero borrar un comentario que realicé anteriormente, <br>**CUANDO** accedo a la sección de "Comentarios" en su perfil y hago clic en el logo de tacho de un comentario propio, <br>**ENTONCES** el sistema lo borra.|EP02|
|US33|**Ver cafés destacados del mes**|**Como consumidor**  **Quiero ver**  los cafés destacados del mes **para**  descubrir lo más recomendado por la comunidad.|**Scenario 1**  <br>**DADO QUE**  estoy en la app, <br>**CUANDO**  accedo a la sección mensual, <br>**ENTONCES**  veo los cafés más votados y comentados.|EP02| 
|US34|**Recibir alertas de nuevas cajas**|**Como consumidor**  **Quiero recibir**  notificaciones cuando se lancen nuevas cajas que correspondan a mi suscripción **para** no perderme ninguna edición especial.|**Scenario 1** <br>**DADO QUE** tengo una suscripción con Mystery Boxes mensuales, <br>**CUANDO**  hay una nueva Mystery Box, <br>**ENTONCES** recibo una notificación en mi apicativo o correo.|EP02|
|US35|**Ver perfil del productor**|**Como consumidor**  **Quiero poder**  ver el perfil completo del productor de cada café **para**  conocer su historia.|**Scenario 1** <br>**DADO QUE**  estoy revisando un café, <br>**CUANDO** hago clic en el producto, <br>**ENTONCES** el sistema me muestra una descripción que colocó el creador.|EP02| 
|US36|**Promocionar productos segun la temporada**|**Como productor**  **Quiero poder** promocionar mis productos según la temporada **para**  aprovechar el clima para atraer clientes.|**Scenario 1**  <br>**DADO QUE**  es invierno y deseo promocionar un producto, <br>**CUANDO** creo una publicación sobre mi producto, <br>**ENTONCES** el sistema me sugiere imágenes y fuentes de letra cómodos acorde a la temporada.|EP03|
|US37|**Generar promociones especiales**|**Como productor** **Quiero crear**  promociones y descuentos activos para ciertos productos **para**  promocionar mis productos.|**Scenario 1** <br>**DADO QUE** deseo promocionar un producto a través de un descuento en una Mystery Box especial, <br>**CUANDO** voy a "Sacar Promoción" y coloco los datos necesarios, <br>**ENTONCES** el sistema muestra la promoción al público.<br><br>**Scenario 2** <br>**DADO QUE** deseo crear una promoción especial, <br>**CUANDO** voy a "Sacar Promoción" y coloco los datos necesarios, pero son iguales a una promoción anterior, <br>**ENTONCES** el sistema muestra el mensaje "Esta promoción ya existe". <br><br>**Scenario 3** <br>**DADO QUE** deseo crear una promoción especial, <br>**CUANDO** voy a "Sacar Promoción" pero coloco datos incorrectos, <br>**ENTONCES** el sistema muestra el mensaje "No es posible crear esta promoción".|EP03|
|US38|**Acceder a promociones especiales**|**Como consumidor** **Quiero ver**  promociones y descuentos activos **para**  aprovechar ofertas en cajas misteriosas.|**Scenario 1** <br>**DADO QUE**  hay una campaña activa, <br>**CUANDO**  entro a la sección de promociones, <br>**ENTONCES**  veo los descuentos disponibles.<br><br>**Scenario 2** <br>**DADO QUE** deseo una promoción pero ya no está disponible, <br>**CUANDO** entro a la sección de promociones, <br>**ENTONCES** el sistema no muestra la promoción inhabilitada.|EP03|
|US39|**Recibir alertas de productos agotados**|**Como consumidor** **Quiero recibir** notificaciones cuando un producto que me gusta esté por agotarse **para** comprarlo a tiempo.|**Scenario 1** <br>**DADO QUE**  marqué un producto como favorito, <br>**CUANDO** está por agotarse, <br>**ENTONCES** el sistema envía notificaciones con el mensaje "**Producto** está por agotarse!!".|EP02| 
|US40|**Ver ofertas de cafés por tipo de grano**|**Como consumidor**  **Quiero poder**  filtrar cafés por tipo de grano (Bourbon, Typica, etc.) **para** explorar variedades específicas.|**Scenario 1**  <br>**DADO QUE**  tengo interés en un tipo de grano, <br>**CUANDO**  uso el filtro, <br>**ENTONCES**  veo cafés que lo incluyen.|EP02|
|US41|**Crear campañas colaborativas entre cafeterías**|**Como productor** **Quiero poder** lanzar campañas junto a otras marcas **para** aumentar alcance y compartir clientes.|**Scenario** <br>**DADO QUE** el usuario es productor, <br>**CUANDO** accede a la sección de colaboración, <br>**ENTONCES** puede invitar a otras marcas y lanzar una campaña conjunta.|EP03|
|US42|**Recibir recomendaciones según cafeterías seguidas**|**Como consumidor** **Quiero recibir** sugerencias de productos según las cafeterías que sigo **para** descubrir nuevas experiencias.|**Scenario** <br>**DADO QUE** sigue varias marcas, <br>**CUANDO** accede a la sección de recomendaciones, <br>**ENTONCES** ve productos relacionados.|EP02|
|US43|**Ver evolución de métricas de mi marca**|**Como productor** **Quiero ver** cómo evolucionan mis métricas de consumo y reseñas **para** tomar decisiones estratégicas.|**Scenario** <br>**DADO QUE** tiene una cuenta de productor, <br>**CUANDO** accede al panel de métricas, <br>**ENTONCES** ve gráficos comparativos por mes.|EP03|
|US44|**Recibir alertas de interacción con mi marca**|**Como productor** **Quiero recibir** notificaciones cuando alguien siga mi marca, deje reseña o compre **para** mantenerme informado.|**Scenario** <br>**DADO QUE** tiene una marca activa, <br>**CUANDO** ocurre una interacción, <br>**ENTONCES** recibe una alerta en mi panel.|EP03|

## 3.3. Impact Mapping

![](img/impact-mapping.png)

## 3.4. Product Backlog

|# Orden|User Story ID|Título|Descripción|Story Points <br>(1/2/3/5/8)|
|--|--|--|--|--|
|1|US01|Registro de Usuario|Como consumidor, quiero poder registrarme en SmilingCups para crear un perfil dentro del aplicativo.|3|
|2|US02|Inicio de sesión|Como usuario registrado, quiero poder iniciar sesión fácilmente para acceder a mis cajas y suscripciones.|2|
|3|US03|Explorar Mystery Boxes|Como consumidor, quiero poder explorar las opciones de las Mystery Boxes para elegir la que más llame mi atención o se adapte a mi presupuesto.|5|
|4|US04|Ver ficha informativa del café|Como consumidor, quiero poder ver la historia y perfil de cada café incluido para conocer más sobre su origen y sabor.|3|
|5|US05|Poder suscribirse a cajas mensuales|Como consumidor, quiero poder suscribirme a una caja mensual para recibir café de forma automática y sin complicaciones.|5|
|6|US06|Cancelar suscripción|Como consumidor, quiero poder cancelar mi suscripción en cualquier momento para tener control sobre mis compras.|3|
|7|US07|Regalar una Mystery Box|Como consumidor, quiero poder enviar una Mystery Box como regalo para sorprender a alguien con una experiencia de café.|5|
|8|US08|Aceptar o rechazar una Mystery Box|Como consumidor, quiero poder aceptar o rechazar una Mystery Box como regalo para confirmar la posibilidad de recibirlo o no.|3|
|9|US09|Definir zona de entrega|Como consumidor, quiero brindar a la app una ubicación de entrega a través de un mapa para poder recibir o enviar las Mystery Boxes que ordene.|5|
|10|US10|Dejar una reseña|Como consumidor, quiero poder dejar una reseña sobre un producto o Mystery Box que probé para compartir mi experiencia con otros.|3|
|11|US11|Filtrar Mystery Boxes por perfil de sabor|Como consumidor, quiero poder filtrar las cajas por perfil de sabor para encontrar opciones que se alineen con mis preferencias.|3|
|12|US12|Ver métricas de consumo|Como marca cafetera, quiero poder ver métricas de consumo de mis cafés para entender mejor a mis clientes.|5|
|13|US13|Registrar perfil de productor|Como productor, quiero poder registrar una cuenta como productor en el aplicativo para tener funcionalidades distintas a las de un usuario consumidor.|3|
|14|US14|Generar muro propio de marca cafetera|Como productor, quiero poder tener un muro propio sobre mi marca cafetera para tener un espacio específico para mis productos que ofrezca.|5|
|15|US15|Subir perfil de marca cafetera|Como productor, quiero poder subir información sobre mi marca y café para que los consumidores conozcan mi historia.|3|
|16|US16|Recibir notificaciones de pedidos|Como productor, quiero recibir alertas cuando se incluya mi café en un pedido realizado por un usuario para estar al tanto de la demanda.|3|
|17|US17|Crear Mystery Box|Como productor, quiero generar una Mystery Box propio con productos propios para promocionar mi marca entre usuarios siguiendo la dinámica principal del aplicativo.|5|
|18|US18|Ver ranking de cafés más valorados de una marca|Como consumidor, quiero poder ver cuáles son los cafés más valorados de una marca en su perfil para descubrir opciones populares.|3|
|19|US19|Marcar o desmarcar cafés favoritos|Como consumidor, quiero poder guardar cafés y demás productos que me gustaron para tenerlos ubicados para volver a comprarlos en el futuro.|3|
|20|US20|Ver historial de Mystery Boxes o productos recibidos|Como usuario, quiero poder ver mi historial de productos recibidas con los productos recibidos para recordar qué cafés probé.|3|
|21|US21|Hacer pedidos desde el historial|Como usuario, quiero poder ordenar Mystery Boxes u otros productos desde el historial para repetir pedidos rápidamente.|5|
|22|US22|Tener marcadas los productos según disponibilidad|Como usuario, quiero poder observar si un producto está disponible desde el historial para evitar hacer un pedido que no voy a recibir.|3|
|23|US23|Establecer como disponibles o no ciertos productos realizadas|Como productor, quiero poder establecer como disponibles o no productos de temporada, incluyendo Mystery Boxes para evitar pedidos de productos que no hay.|5|
|24|US24|Ver historial de Mystery Boxes realizadas|Como productor, quiero poder ver mi historial de Mystery Boxes realizadas con productos propios para volver a promocionarlas más adelante.|3|
|25|US25|Acceder desde cualquier dispositivo|Como usuario, quiero poder usar la app desde cualquier dispositivo para comprar café en cualquier momento.|2|
|26|US26|Recibir recomendaciones personalizadas|Como consumidor, quiero recibir sugerencias de cajas según mis gustos para descubrir nuevas opciones.|5|
|27|US27|Ver mapa de emprendimientos de cafés|Como consumidor, quiero ver un mapa interactivo con la ubicación de los emprendimientos disponibles para conocer su procedencia.|5|
|28|US28|Activar o Desactivar Notificaciones de un Productor|Como consumidor, quiero poder activar o desactivar notificaciones de la cuenta de un productor para notificarme de sus publicaciones.|3|
|29|US29|Recibir notificaciones sobre nuevos lanzamientos de una marca|Como usuario, quiero recibir una notificación de novedades y lanzamientos de una marca en específico para estar al tanto de nuevas experiencias que pueda ofrecerme.|3|
|30|US30|Panel de control para productores|Como marca cafetera, quiero tener un panel de control personalizado para gestionar mi perfil, cafés y métricas.|5|
|31|US31|Subir nuevos cafés al catálogo|Como productor, quiero poder subir nuevos cafés al sistema para que sean considerados en futuras cajas.|3|
|32|US32|Agregar o borrar comentarios a creadores|Como cliente, quiero poder agregar o borrar comentarios sobre cafés y demás productos de ciertas cuentas para dar feedback sobre sus productos.|3|
|33|US33|Ver cafés destacados del mes|Como consumidor, quiero ver los cafés destacados del mes para descubrir lo más recomendado por la comunidad.|2|
|34|US34|Recibir alertas de nuevas cajas|Como consumidor, quiero recibir notificaciones cuando se lancen nuevas cajas que correspondan a mi suscripción para no perderme ninguna edición especial.|2|
|35|US35|Ver perfil del productor|Como consumidor, quiero poder ver el perfil completo del productor de cada café para conocer su historia.|2|
|36|US36|Promocionar productos según la temporada|Como productor, quiero poder promocionar mis productos según la temporada para aprovechar el clima para atraer clientes.|3|
|37|US37|Generar promociones especiales|Como productor, quiero crear promociones y descuentos activos para ciertos productos para promocionar mis productos.|5|
|38|US38|Acceder a promociones especiales|Como consumidor, quiero ver promociones y descuentos activos para aprovechar ofertas en cajas misteriosas.|3|
|39|US39|Recibir alertas de productos agotados|Como consumidor, quiero recibir notificaciones cuando un producto que me gusta esté por agotarse para comprarlo a tiempo.|2|
|40|US40|Ver ofertas de cafés por tipo de grano|Como consumidor, quiero poder filtrar cafés por tipo de grano (Bourbon, Typica, etc.) para explorar variedades específicas.|3|
|41|US41|Crear campañas colaborativas entre cafeterías|Como productor, quiero poder lanzar campañas junto a otras marcas para aumentar alcance y compartir clientes.|5|
|42|US42|Recibir recomendaciones según cafeterías seguidas|Como consumidor, quiero recibir sugerencias de productos según las cafeterías que sigo para descubrir nuevas experiencias.|3|
|43|US43|Ver evolución de métricas de mi marca|Como productor, quiero ver cómo evolucionan mis métricas de consumo y reseñas para tomar decisiones estratégicas.|5|
|44|US44|Recibir alertas de interacción con mi marca|Como productor, quiero recibir notificaciones cuando alguien siga mi marca, deje reseña o compre para mantenerme informado.|3|

# Capitulo IV: Product Design
## 4.1. Style guidelines
Estos lineamientos se establecerán para el diseño del sistema de smiling cups, una plataforma de mysteryboxes con tematica de cafes.
### 4.1.1. General Style Guidelines

#### a. Branding
- Logotipo:El logotipo de SmilingCups utiliza una composicion circular. Se presenta en formato png para permitir su visualizacion en la mas alta calidad.
- Colores del logotipo: El logotipo emplea tonos monocromaticos para dar una vista simple y no cargada. Tiene una cara feliz en medio representando la parte de "Smiling" y la vista es de una taza desde arriba.
- Espaciado mínimo: Se establece un espaciado mínimo de 10px alrededor del logotipo para garantizar su legibilidad y presencia visual en cualquier contexto.

#### b. Tipografía

- Primera Fuente - Amaranth (56px): Utilizada para titulos principales, se usa esta fuente buscando trasmitir una vibra de tranquilidad y calma al usuario.
- Segunda Fuente - Amatic SC(32px): Utilizada para textos descriptivos e informaticos trasmitiendo una vibra segura y hogareña.
- Tercera Fuente - Lindo Figma (24px): Utilizada para los botones, es un estilo alegre y creativo para llamar la atencion del usuario
- Aplicaciones:
	- Amaranth: Utilizada para titulos principales

	- Amatic SC: Utilizada para textos descriptivos

	- Lindo Figma: Utilizada para los botones
   
### 4.1.2. Web Style Guidelines

#### a. Estructura de la página

La interfaz de usuario de la aplicación Web de Smiling Cups fue diseñada con el objetivo de ofrecer un experiencia fluida y de calidad para los usuarios, tendiendo en cuenta las adaptaciones a los distintos formatos de pantalla. Se observan a continuación tres secciones para poder entender como se organiza el contenido.


-   Header
    
    -   Ubicación: Parte superior de la pantalla
    -   Contenido:
        -   Logo: El logo de nuestra aplicación se posiciona en la esquina superior izquierda, mostrado en el formato JPG.
        -   Botones de navegación: Se disponen en la esquina superior izquierda después del logo, con opciones como "About", "Goals" y "Contact".
    -   Color del Header: Café oscuro – código #CDAC77. Este color fue elegido por debido a su relación con los contextos del negocio, transmitiendo identidad visual y profesionalismo.
-   Body
    
    -   Ubicación: La zona más amplia de la página, se encuentra en la zona central.
    -   Contenido:
        -   Imágenes: Se incluyen imágenes JPG que guardan relación con el objetivo de cada sección de la aplicación Web
    -   Color del Body: Café claro – código #FFF1D1. Este color demuestra un entorno agradable para el usuario y se muestra de forma limpia y pulida.
    

#### b. Diseño de Interfaz


-   Responsive Design: La interfaz grafica de la aplicación  esta diseñada para poder ser mostrada en diferentes tipos de dispositivos. Esto se logra mediante la utilización de diversas herramientas que ayuden con el redimensionamiento.

#### c. Tipografía Web

-   Menú Horizontal y Vertical
    -   Fuente: Scribbled
    -   Tamaño: 32 px
    -   Estilo: Negrita
-   Títulos
    -   Fuente: Amaranth
    -   Tamaño: 56 px
    -   Estilo: Regular
-   Subtítulos
    -   Fuente: Amatic SC
    -   Tamaño: 32 px
    -   Estilo: Regular
-   Cuerpo de Texto
    -   Fuente: Amatic SC
    -   Tamaño: 32 px
    -   Estilo: Regular
 

#### d. Colores


-   Paleta de colores base
    
    -   Café oscuro(#CDAC77): Color usado en el encabezado de la app.
    -   Café claro(#FFF1D1): Color usado para el fondo de la página.
 para aportar frescura y contraste.

#### e. Iconografía

-   Estilo: Íconos divertidos y atractivos, diseñados para mejorar la accesibilidad y facilitar la navegación.


## 4.2. Information Architecture
### 4.2.1. Organization Systems
SmilingCups organiza su información aplicando sistemas de organización visual y esquemas de categorización:

**A) Organización visual del contenido**

-   **Jerárquica:** Menú superior con secciones principales (Inicio,  Comunidad, Suscripciones, Mi Cuenta).
    
-   **Secuencial:** Procesos guiados paso a paso como el registro de usuarios, compra de cajas y configuración de suscripción.
    
-   **Matriz:** Sección de exploración de cafés y productores, filtrada por origen, tipo de tueste, o precio.
    
**B) Esquemas de categorización del contenido**

-   **Alfabético:** Listados de productores o cafés en catálogo.
    
-   **Cronológico:** Historial de compras y reseñas.
    
-   **Por tópicos:** Clasificación por tipo de café (espresso, filtrado, cold brew).
    
-   **Por audiencia:** División de vistas:
    
    -   Consumidores (mystery boxes, catálogo, comunidad).
        
    -   Productores (dashboard de métricas, gestión de cafés).
 
      
### 4.2.2. Labeling Systems

SmilingCups se plantea para ser claro, conciso y evitar ambigüedades:

-   **Inicio:** Página de bienvenida.
    
-   **Mystery Box:** Acceso directo a los planes de cajas misteriosas.
    
-   **Explorar:** Catálogo de cafés y productores.
    
-   **Comunidad:** Espacio de interacción, reseñas y foros.
    
-   **Mi Cuenta:** Perfil personal del usuario (historial y  configuraciones).
    
-   **Dashboard:** Herramienta exclusiva para productores con métricas de consumo.

  
### 4.2.3. SEO Tags and Meta Tags
Con el objetivo de optimizar la visibilidad de SmilingCups en motores de búsqueda y mejorar la accesibilidad de la información, se han definido los principales SEO Tags y Meta Tags que serán implementados en la Landing Page y la Web Application.

**Landing Page**

- **Title:** SmilingCups-Plataforma de Misteryboxes sobre cafe
- **Meta Description:** SmilingCups te ofrece una ruleta rusa de posibilidades si amas el cafe. Desarrollado por ApoutCoffes para los amantes del cafe y el azar.
- **Meta Keywords:** Cafe, MysteryBox, Gambling, Develop Team, Cafeina.
- **Meta Author:** ApoutCoffees Team

**Web Application**

- **Title:** SmilingCups
- **Meta Description:** Prueba tu suerte y degusta los distintos cafes que tanto te gustan, suscribete y tienta a la suerte.
- **Meta Keywords:** Cafe, MisteryBox, Gambling, Develop Team, Cafeina, Tipos de cafe, Cafe cargado.
- **Meta Author:** ApoutCoffees Team
  
### 4.2.4. Searching System

El sistema de búsqueda de SmilingCups busca facilitar el acceso rápido a cafés, productores y reseñas, evitando que los usuarios se pierdan entre el volumen de información.

-   **Barra de búsqueda principal:** Disponible en el header de la aplicación.
    
-   **Filtros de búsqueda:**
    
    -   Por tipo de café (espresso, americano, filtrado).
        
    -   Por precio (básico, premium, exclusivo).
        
    -   Por productor (nombre de la marca o región).
        
    -   Por popularidad o valoración de usuarios.
 
    
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
<br>

**Web landing page wireframe** 
<br>

- Home

<br>

![WFLandingHome.](/img/wireframes-landing/WFLandingHome.png)

<br>

- About

<br>

![WFLandingAbout.](/img/wireframes-landing/WFLandingAbout.png)

<br>

- Goals

<br>

![WFLandingGoals.](/img/wireframes-landing/WFLandingGoals.png)

<br>

- Contact

<br>

![WFLandingContact.](/img/wireframes-landing/WFLandingContact.png)

<br>

**Mobile landing page wireframe** 
<br>

- Home

<br>

![WFLandingAppHome.](/img/wireframes-landing/WFLandingAppHome.png)

<br>

- Home Tab

<br>

![WFLandingAppHomeTab.](/img/wireframes-landing/WFLandingAppHomeTab.png)

<br>

- About

<br>

![WFLandingAppAbout.](/img/wireframes-landing/WFLandingAppAbout.png)

<br>

- Goals

<br>

![WFLandingAppGoals.](/img/wireframes-landing/WFLandingAppGoals.png)

<br>

- Contact

<br>

![WFLandingAppContact.](/img/wireframes-landing/WFLandingAppContact.png)

<br>

### 4.3.2. Landing Page Moc-up
<br>

**Web landing page Moc-up** 
<br>

- Home

<br>

![MULandingHome.](/img/mockups-landing/MULandingHome.png)

<br>

- About

<br>

![MULandingAbout.](/img/mockups-landing/MULandingAbout.png)

<br>

- Goals

<br>

![MULandingGoals.](/img/mockups-landing/MULandingGoals.png)

<br>

- Contact

<br>

![MULandingContact.](/img/mockups-landing/MULandingContacts.png)

<br>

**Mobile landing page wireframe** 
<br>

- Home

<br>

![MULandingAppHome.](/img/mockups-landing/MULandingAppHome.png)

<br>

- Home Tab

<br>

![MULandingAppHomeTab.](/img/mockups-landing/MULandingAppHomeTab.png)

<br>

- About

<br>

![MULandingAppAbout.](/img/mockups-landing/MULandingAppAbout.png)

<br>

- Goals

<br>

![MULandingAppGoals.](/img/mockups-landing/MULandingAppGoals.png)

<br>

- Contact

<br>

![MULandingAppContacts.](/img/mockups-landing/MULandingAppContact.png)

<br>

## 4.4 Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5 Web Applications Prototyping
## 4.6 Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming

En esta sección nos enfocamos en pulir el diseño realizado en el Big Picture Event Storming, denotando nuevos elementos que nos ayudar a profundizar más en los flujos de eventos que se recorren dentro de la aplicación Web.

-   **Comandos:**  Representados mediante un post-it azul, son aquellos que simbolizan las acciones a realizar que serán transformadas a eventos.

   
-   **Aggregates:**  Representados mediante un post-it amarillo claro, son los que simbolizan una entidad a manera de agregados, se forman en base a los eventos del dominio, así que antes de cada evento se debe colocar un aggregate que simbolice la identidad del evento del dominio.
    
-   **Políticas:**  Representadas mediante un post-it morado, vendrían a ser las reglas del negocio que, después de haber pasado por un evento, se encargan de acción un nuevo comando, es así que normalmente se colocan entre un evento y un comando que le sigue a este. Pero también lo utilizamos como un puente entre Bounded Context, para de esta forma conectar un flujo de eventos entre diferentes contextos.
  

A continuación mostraremos las capturas del Design Level Event Storming realizado, separandolos según el Bounded Context al que pertenecen y comenzando con los Core del negocio.

  <br>
 
**Bounded Context Marketplace**

![](img/dl-event-storming/marketplace/marketplace-1.png)

![](img/dl-event-storming/marketplace/marketplace-2.png)

<br>

**Bounded Context Mistery Box**

![](img/dl-event-storming/mistery-box/mistery-box-1.png)

![](img/dl-event-storming/mistery-box/mistery-box-2.png)
	
<br>

**Bounded Context Profile**

![](img/dl-event-storming/profile/profile-1.png)

![](img/dl-event-storming/profile/profile-2.png)

![](img/dl-event-storming/profile/profile-3.png)

<br>

**Bounded Context IAM**

![](img/dl-event-storming/iam/iam-1.png)

<br>

**Bounded Context Notification**

![](img/dl-event-storming/notification/notification-1.png)

<br>

**Bounded Context Subscription**

![](img/dl-event-storming/subscription/subscription-1.png)

![](img/dl-event-storming/subscription/subscription-2.png)

### 4.6.2. Software Architecture Context Diagram

![](img/c4/context-diagram.png)

### 4.6.3. Software Architecture Container Diagrams

![](img/c4/containers-diagram.png)

### 4.6.4.Software Architecture Components Diagrams

![](img/c4/components-diagram.png)

## 4.7Software Object-Oriented Design
### 4.7.1. Class Diagrams

**Vista general:**

![](img/class-diagrams/general.png)


**Bounded Context Marketplace**

![](img/class-diagrams/marketplace.png)


**Bounded Context Mistery Box**

![](img/class-diagrams/mystery-box.png)


**Bounded Context Profile**

![](img/class-diagrams/profile.png)


**Bounded Context IAM**

![](img/class-diagrams/iam.png)


**Bounded Context Notification**

![](img/class-diagrams/notification.png)


**Bounded Context Subscription**

![](img/class-diagrams/subscription.png)

**Shared**
![](img/class-diagrams/shared.png)


## 4.8. Database Design
### 4.8.1.Database Diagrams

![](img/databse-diagram.png)

# Capitulo V Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

El entorno de desarrollo de **SmilingCups** se definió considerando las tecnologías base del proyecto:  

- **Frontend:** Vue.js 3 (con Vite) para construcción de interfaces reactivas.  
- **Backend:** Node.js con Express para la construcción de la API REST.  
- **Base de Datos:** MySQL para el almacenamiento relacional de usuarios, pedidos y suscripciones.  
- **IDE principal:**  WebStorm para frontend y JetBrains IntelliJ IDEA/Visual Studio Code para backend.  
- **Gestor de paquetes:** npm para frontend y backend.  
- **Control de versiones:** GitHub.

### 5.1.2. Source Code Management

El control del código fuente se gestiona en **GitHub**, bajo un flujo de trabajo basado en **GitFlow**, adaptado al marco ágil.  

- **Branching Strategy**  
  - **main:** Contiene el código estable y en producción.  
  - **develop:** Versión de integración para nuevas funcionalidades.  
  - **feature/:** Ramas específicas para cada User Story o Task.
    
### 5.1.3. Source Code Style Guide & Conventions

Para mantener un código consistente y legible, se adoptaron las siguientes guías de estilo y convenciones:  

- **Frontend (Vue.js):**  
  - Uso de la guía oficial de estilo de Vue.js.  
  - Componentes nombrados en PascalCase (UserProfile.vue).  
  - Variables y funciones en camelCase.  
  - Archivos .vue organizados en carpetas components/, views/, store/.  

- **Backend (Node.js ):**  
  - Estructura MVC (Model, View, Controller).  
  - Rutas en minúsculas con guiones (/api/user-profile).  
  - Variables en inglés, con nombres claros y descriptivos.  

- **General:**  
  - Commits con mensajes siguiendo convención:  
    - feat: para nuevas funcionalidades.  
    - fix: para correcciones de errores.  
    - docs: para cambios en documentación.  
    - refactor: para mejoras sin cambiar funcionalidad.  
    - test: para agregar o modificar pruebas.

### 5.1.4. Software Deployment Configuration

El despliegue de **SmilingCups** se organiza bajo un esquema de servicios distribuidos:  

- **Frontend (Vue.js):** Desplegado en **Vercel**, con actualizaciones automáticas al hacer push a **main**.  
- **Backend (Node.js/Express):** Desplegado en **Render**, con conexión directa a la base de datos.  
- **Base de Datos (MySQL):** Implementada en (MySQL en la nube) o en **MySQL Workbench** para entorno local.  
- **Landing Page:** Incluida en el mismo frontend de Vue.js.
  
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
####  5.2.1.1. Sprint Planning 1

| **Sprint #**                  | Sprint 1 |
|--------------------------------|----------|
| **Sprint Planning Background** | |
| **Date**   | 2025-09-3 |
| **Time**   | 9:00 PM |
| **Location**  | Meet via Discord  |
| **Prepared By**  | Juan Carlos Pastor Napa |
| **Attendees (to planning meeting)** | Carlos Augusto Paredes Chavez/Daniel Jonatan Aquino Solorzano/Johnny Alexander Ojanama Abanto/Juan Carlos Pastor Napa/Giuliano Angel Pelaez Vargas |
| **Sprint n – 1 Review Summary** | No hubo Sprint anterior. |
| **Sprint n – 1 Retrospective Summary** | Al ser el primer Sprint, la retrospectiva se enfocó en definir comunicación, repositorio y guías de estilo de código. |
| **Sprint Goal & User Stories** | |
| **Sprint 1 Goal**              | Configurar la base técnica del proyecto (entorno de desarrollo en WebStorm, repositorio GitHub, GitFlow, integración inicial de Vue.js + Node.js + MySQL, prototipo básico de Landing Page). |
| **Sprint 1 Velocity**          | 10 Story Points |
| **Sum of Story Points**        | 10 |


####  5.2.1.2. Aspect Leaders and Collaborators

En este Sprint se identificaron los principales aspectos: **Frontend (Vue.js), Backend (Node.js ), Base de Datos (MySQL), Landing Page, QA & Documentación**.  

| **Team Member**         | **GitHub Username** | **Frontend** | **Backend** | **Base de Datos** | **Landing Page** | **QA & Documentación** |
|--------------------------|----------------------|-----------------------|-----------------------|---------------------------|------------------|-------------------------|
| Carlos Augusto Paredes Chavez  | @CarlossUPC | C | L | C | C | L |
| Juan Carlos Pastor Napa | @ElKiwi1271  | L  | C  | L | C | C |
| Daniel Jonatan Aquino Solorzano| @DanielAquinoSolorzano | C | L | C | C | C |
| Giuliano Angel Pelaez Vargas | @SimpleGP | C  | C   | L | C | L |
| Johnny Alexander Ojanama Abanto | @JohnnyGZ41 | L | C  | C  | L | C  |

####  5.2.1.3. Sprint Backlog 1

El Sprint 1 tuvo como objetivo preparar el entorno de trabajo y asegurar la infraestructura básica.  

| **Sprint #** | **User Story** | **Work-Item / Task** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|--------------|----------------|----------------------|-----------------|-------------------------|-----------------|------------|
| Sprint 1     | US01 – Registro de Usuario | T-01: Crear tabla users en MySQL | Definir estructura de tabla con campos id, name, email, password. | 4h | Giuliano Pelaez | In process |
| Sprint 1     | US01 – Registro de Usuario | T-02: Endpoint /api/register | Implementar endpoint en Express para registrar nuevos usuarios. | 5h | Daniel Aquino | In process |
| Sprint 1     | US01 – Registro de Usuario | T-03: Formulario de registro en Vue.js | Crear vista de registro y validaciones en frontend. | 4h | Juan Pastor | In process |
| Sprint 1     | US02 – Inicio de Sesión | T-04: Endpoint /api/login | Implementar autenticación con JWT en backend. | 6h | Daniel Aquino | In process |
| Sprint 1     | US02 – Inicio de Sesión | T-05: Pantalla de Login | Crear formulario de login en Vue.js y conectar al backend. | 4h | Juan Pastor | In process |
| Sprint 1     | US03 – Explorar Mystery Boxes | T-06: Crear tabla mystery_boxes | Diseñar tabla para almacenar datos de cajas (id, nombre, precio, descripción). | 3h | Giuliano Peláez | In process |
| Sprint 1     | US03 – Explorar Mystery Boxes | T-07: Endpoint /api/boxes | Implementar endpoint para obtener listado de cajas. | 4h | Daniel Aquino | In process |
| Sprint 1     | US03 – Explorar Mystery Boxes | T-08: Vista de Exploración | Diseñar página Vue.js que muestre listado de Mystery Boxes. | 5h | Carlos Paredes | In process |
| Sprint 1     | US04 – Ver ficha informativa del café | T-09: Crear tabla coffee | Definir estructura de cafés relacionados a cada Mystery Box. | 3h | Carlos Paredes | In process |
| Sprint 1     | US04 – Ver ficha informativa del café | T-10: Endpoint /api/coffee/:id | Implementar endpoint para mostrar perfil de café. | 4h | Daniel Aquino| In process |
| Sprint 1     | US04 – Ver ficha informativa del café | T-11: Página de ficha de café en Vue.js | Desarrollar vista con historia, notas de cata y productor. | 4h | Johnny Ojanama | In process |
| Sprint 1     | US05 – Suscripción mensual | T-12: Crear tabla subscriptions | Definir modelo para almacenar suscripciones activas por usuario. | 3h | Carlos Paredes | In process |
| Sprint 1     | US05 – Suscripción mensual | T-13: Endpoint /api/subscribe | Implementar lógica para activar suscripción mensual. | 5h | Daniel Aquino | In process |
| Sprint 1     | US05 – Suscripción mensual | T-14: Vista de suscripción en Vue.js | Crear interfaz donde usuario seleccione una caja y confirme pago simulado. | 4h | Johnny Ojanama| In process |

####  5.2.1.4. Development Evidence for Sprint Review

Al ser **Sprint 1**, no se implementaron aún funcionalidades completas.  
Sin embargo, se avanzó en la configuración técnica:  

- Repositorio de GitHub creado y accesible al equipo.  
- Ramas configuradas bajo GitFlow.  
- WebStorm preparado con entornos para Vue.js y Node.js.  
- Creación de la base de datos MySQL con tabla users.  
- Primer prototipo de la Landing Page en HTML/CSS.
  
####  5.2.1.5. Execution Evidence for Sprint Review

La ejecución incluyó:  
- Reunión de arranque para definir flujo de trabajo.  
- Configuración de repositorio con **commits iniciales**.  
- Sincronización del equipo a través de reuniones virtuales y Discord.  

####  5.2.1.6. Services Documentation Evidence for Sprint Review

Se documentó lo siguiente:  
- Guía de uso del repositorio (README inicial en GitHub).  
- Modelo entidad-relación inicial para la base de datos. 


####  5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue de Sprint 1 se realizó en entornos de prueba:  
- **Frontend (Vue.js):** ejecutado en WebStorm con servidor local 
- **Backend (Node.js):** levantado en WebStorm (npm start).  
- **Base de datos:** configurada en MySQL Server o MySQl workbench.
  
####  5.2.1.8. Team Collaboration Insights during Sprint

- Se estableció Discord como canal de comunicación principal y Google Meet para reuniones semanales.  
- Se adoptaron convenciones de commits en inglés siguiendo el estándar feat:, fix:.  
- Se clarificaron los roles principales de liderazgo y colaboración para cada aspecto (Frontend, Backend, Base de Datos, Landing Page, QA & Documentación).
- Se observó una fortaleza en la rápida alineación del equipo respecto a las herramientas y lineamientos técnicos.
- Se identificó como oportunidad de mejora la estimación más precisa del esfuerzo de tareas y una documentación más detallada desde el inicio.
  
# Conclusiones

# Anexos
- [Link del Trello:] (https://trello.com/invite/b/68e01ea8517c5769321963f8/ATTId55612fc25e3b4e7bca3bdd2dc478cfdF0AFCB8B/smilingcups)
- [Script de creación de la base de datos](db-creation-script.md)

- Link de Entrevistas

# Bibliografía 



