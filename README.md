
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

**Fecha:** Agosto, 2025

---
## Registro de versiones del informe
| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| 1.0    |  |  |  |
| 1.1 |

---

## Project Report Collaboration Insights
[Repositorio en GitHub](https://github.com/ApoutCoffees/upc-pre-202510-1asi0730-7420-ApoutCoffees-report-tb1.git)

---

# Tabla de Contenido

1. [Capítulo I: Introducción](#capítulo-i-introducción)
	- 1.1. [Startup Profile](#startup-profile) 
		- 1.1.1. [Descripción de la Startup](#descripción-de-la-startup)
		- 1.1.2. [Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
	- 1.2. [Solution Profile](#solution-profile)
		- 1.2.1 [Antecedentes y problemática](#antecedentes-y-problemática)
		- 1.2.2 [Lean UX Process](#lean-ux-process)
			- 1.2.2.1. [Lean UX Problem Statements](#lean-ux-problem-statements)
			- 1.2.2.2. [Lean UX Assumptions](#lean-ux-assumptions)
			- 1.2.2.3. [Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
			- 1.2.2.4. [Lean UX Canvas](#lean-ux-canvas)
	- 1.3. [Segmentos objetivo](#segmentos-objetivo)
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
	- 2.1. [Competidores](#competidores)
		- 2.1.1. [Análisis competitivo](#análisis-competitivo)
		-  2.1.2. [Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
	- 2.2. [Entrevistas](#entrevistas)
		-  2.2.1. [Diseño de entrevistas](#diseño-de-entrevistas)
		- 2.2.2. [Registro de entrevistas](#registro-de-entrevistas)
		- 2.2.3. [Análisis de entrevistas](análisis-de-entrevistas)
	-  2.3. [Needfinding](#needfinding)
		- 2.3.1. [User Personas](#user-personas)
		- 2.3.2. [User Task Matrix](#user-task-matrix)
		- 2.3.3. [User Journey Mapping](#user-journey-mapping)
		- 2.3.4. [Empathy Mapping](#empathy-mapping)
	- 2.4. [Big Picture Event Storming](#big-picture-event-storming)
	- 2.5. [Ubiquitous Language](#ubiquitous-language)
3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
	- 3.1. [To-Be Scenario Mapping](#to-be-scenario-mapping)
	- 3.2. [User Stories](#user-stories)
	- 3.3. [Impact Mapping](#impact-mapping)
	- 3.4. [Product Backlog](#product-backlog)
4. [Capítulo IV: Product Design](#capitulo-iv-product-design)
	- 4.1. [Style Guidelines](#style-guideline)
		- 4.1.1. [General Style Guidelines](#general-style-guidelines)
		- 4.1.2. [Web Style Guidelines](#web-style-guidelines)
	- 4.2. [Information Architecture](#information-architecture)
		- 4.2.1. [Organization Systems](#organization-systems)
		- 4.2.2. [Labeling Systems](#labeling-systems)
		- 4.2.3. [SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
		- 4.2.4. [Searching Systems](#searching-systems)
		- 4.2.5. [Navigation Systems](#navigation-systems)
	- 4.3. [Landing Page UI Design](#landing-page-ui-design)
		- 4.3.1. [Landing Page Wireframe](#landing-page-wireframe)
		- 4.3.2. [Landing Page Mock-up](#landing-page-mock-up)
	- 4.4. [Web Applications UX/UI Design](#web-applications-uxui-design)
		- 4.4.1. [Web Applications Wireframes](#web-applications-wireframes)
		- 4.4.2. [Web Applications Wireflow Diagrams](#web-applications-wireflow-diagrams)
		- 4.4.3. [Web Applications Mock-ups](#web-applications-mock-ups)
		- 4.4.4. [Web Applications User Flow Diagrams](#web-applications-user-flow-diagrams)
	- 4.5. [Web Applications Prototyping](#web-applications-prototyping)
	- 4.6. [Domain-Driven Software Architecture](#domain-driven-software-architecture)
		- 4.6.1. [Design-Level EventStorming](#design-level-eventstorming)
		- 4.6.2. [Software Architecture Context Diagram](#software-architecture-context-diagram)
		- 4.6.3. [Software Architecture Container Diagrams](#software-architecture-container-diagrams)
		- 4.6.4. [Software Architecture Components Diagram](#software-architecture-components-diagram)
	-  4.7. [Software Object-Oriented Design](#software-object-oriented-design)
		- 4.7.1. [Class Diagrams](#class-diagrams)
	- 4.8. [Database Design](#database-design)
		-  4.8.1. [Database Diagrams](#database-diagrams)
5. [Capítulo V: Product Implementation, Validation & Deployment](#capitulo-v-product-implementation-validation--deployment)
	- 5.1. [Software Configuration Management](#software-configuration-management)
		- 5.1.1. [Software Development Environment Configuration](#software-development-environment-configuration)
		- 5.1.2. [Source Code Management](#source-code-management)
		- 5.1.3. [Source Code Style Guide & Conventions](#source-code-style-guide--conventions)
		- 5.1.4. [Software Deployment Configuration](#software-deployment-configuration)
	- 5.2. [Landing Page, Services & Applications Implementation](#landing-page-services--applications-implementation)
		- 5.2.1. [Sprint 1](#sprint-1)
			- 5.2.1.1. [Sprint Planning 1](#sprint-planning-1)
			- 5.2.1.2. [Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators)
			- 5.2.1.3. [Sprint Backlog 1](#sprint-backlog-1)
			- 5.2.1.4. [Development Evidence for Sprint Review](#development-evidence-for-sprint-review)
			- 5.2.1.5. [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
			- 5.2.1.6. [Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
			- 5.2.1.7. [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
			- 5.2.1.8. [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
		
	[Conclusiones](#conclusiones)
	[Bibliografía](#bibliografía)
	[Anexos](#anexos)

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
|

# Student Outcome

| Criterio específico | Giuliano Angel Pelaez Vargas | Daniel Jonatan Aquino Solorzano | Juan Carlos Pastor Napa | Johnny Alexander Ojanama Abanto | Carlos Augusto Paredes Chavez | Conclusiones |
|---------------------|------------------------------|---------------------------------|---------------------------|---------------------------------|-------------------------------|--------------|
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | asd | asd | asd | asd | asd | asd |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | asd | asd | asd | asd | asd | asd |

---

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup 
### 1.1.2. Perfiles de integrantes del equipo 
## 1.2. Solution Profile 
### 1.2.1. Antecedentes y Problemática
### 1.2.2. Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.2.1. Assumptions Worksheet 
##### 1.2.2.2.2. Business Outcomes 
##### 1.2.2.2.3. User 
##### 1.2.2.2.4. User Outcomes 
##### 1.2.2.2.5. Features
#### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.3.1. Hipótesis de Usuario
##### 1.2.2.3.2. Hipótesis de Negocio
#### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos Objetivo
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores 
### 2.1.1 Análisis Competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3 Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
## 2.3. Big Picture Event Storming
## 2.4. Ubiquitous Language
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog
# Capitulo IV: Product Design
## 4.1. Style guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching System
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Moc-up
## 4.4 Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5 Web Applications Prototyping
## 4.6 Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4.Software Architecture Components Diagrams
## 4.7Software Object-Oriented Design
### 4.7.1. Class Diagrams
## 4.8. Database Design
### 4.8.1.Database Diagrams
# Capitulo V Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
####  5.2.1.1. Sprint Planning 1
####  5.2.1.2. Aspect Leaders and Collaborators
####  5.2.1.3. Sprint Backlog 1
####  5.2.1.4. Development Evidence for Sprint Review
####  5.2.1.5. Execution Evidence for Sprint Review
####  5.2.1.6. Services Documentation Evidence for Sprint Review
####  5.2.1.7. Software Deployment Evidence for Sprint Review
####  5.2.1.8. Team Collaboration Insights during Sprint
# Conclusiones
# Bibliografía 
# Anexos




