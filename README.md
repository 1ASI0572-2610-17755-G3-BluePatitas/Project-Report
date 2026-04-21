# <center>Project Report</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="200"><br>
    <strong>Ingeniería de Software - 2026-10</strong><br>
    <strong>Desarrollo de Soluciones IOT - 17755</strong><br>
    <strong>Profesor: Marco Antonio Leon Baca</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

<p align="center">
    <strong>Startup: </strong><br>
    <strong>Producto: </strong>
</p>

<div style="text-align:center;">
    <h3 align="center">Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Giancarlo Santiago Castañeda Guimas</td>
            <td>U202310601</td>
        </tr>
        <tr>
            <td>Luciana Carolina Choquehuanca Nuñez</td>
            <td>U202319431</td>
        </tr>
        <tr>
            <td>Carlos Matthew Gonzales Valverde</td>
            <td>U202314130</td>
        </tr>
        <tr>
            <td>María Patricia Hernández Uchuya</td>
            <td>U202311258</td>
        </tr>
        <tr>
            <td>Ronald Joel Peralta Chipa</td>
            <td>U202224619</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Abril, 2026</strong>
</p>

<br>

# Registro de versiones del Informe

<table align="center">
    <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de modificaciones</th>
    </tr>
    <tr>
        <td>0</td>
        <td>11/04/2026</td>
        <td>María Hernández</td>
        <td>Creación del reporte</td>
    </tr>
</table>

<br>

# Project Report Collaboration Insights
Link del repositorio del reporte: 

<br>

# Contenido
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
        - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
            - [4.1.1.1 Candidate Context Discovery](#4111-candidate-context-discovery)
            - [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
            - [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
        - [4.1.2. Context Mapping](#412-context-mapping)
        - [4.1.3. Software Architecture](#413-software-architecture)
            - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
            - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
            - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
            - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
        - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
            - [4.2.X.1. Domain Layer](#42x1-domain-layer)
            - [4.2.X.2. Interface Layer](#42x2-interface-layer)
            - [4.2.X.3. Application Layer](#42x3-application-layer)
            - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
            - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
            - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
                - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
                - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
    - [5.1. Style Guidelines](#51-style-guidelines)
        - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
        - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
    - [5.2. Information Architecture](#52-information-architecture)
        - [5.2.1. Organization Systems](#521-organization-systems)
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
    - [5.5. Applications Prototyping](#55-applications-prototyping)
    - [5.6. IoT Device Design](#56-iot-device-design)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
    - [6.1. Software Configuration Management](#61-software-configuration-management)
        - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
        - [6.1.2. Source Code Management](#612-source-code-management)
        - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
        - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
    - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
        - [6.2.X. Sprint n](#62x-sprint-n)
            - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
            - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
            - [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
            - [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
            - [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
            - [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
            - [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
            - [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
            - [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)
    - [6.3. Validation Interviews](#63-validation-interviews)
        - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
        - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
        - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
    - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<br>

# Student Outcome

<br>

# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>Giancarlo Santiago Castañeda Guimas - U202310601</strong></p>
      <p align="justify">
        ...
      </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 250px; text-align: center;">
      <img src="img/lluciana_img.png" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>Luciana Carolina Choquehuanca Nuñez - U202319431</strong></p>
      <p align="justify">
        Mi nombre es Luciana Carolina, soy estudiante de la carrera de Ingeniería de Software, actualmente cursando el séptimo ciclo, y tengo 20 años. Me considero una persona proactiva, con gran interés en participar en proyectos que impliquen adquirir nuevos conocimientos y seguir aprendiendo constantemente. Me gusta mantener el orden en mi trabajo, por lo que siempre busco entregar resultados que cumplan con los estándares requeridos. Además, disfruto aprender tanto de mis profesores como de mis compañeros, ya que considero que el aprendizaje colaborativo es clave para mi desarrollo profesional.
      </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>Carlos Matthew Gonzales Valverde - U202314130</strong></p>
      <p align="justify">
        ...
      </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>María Patricia Hernández Uchuya - U202311258</strong></p>
      <p align="justify">
        Estudio la carrera de Ingeniería de Software, tengo 20 años y actualmente me encuentro cursando el septimo ciclo de dicha carrera. Me considero una persona con responsabilidad, optimismo y honestidad, cualidades que considero fundamentales para una colaboración efectiva en equipo y un buen desarrollo en este proyecto.
      </p>
    </td>
  </tr>
</table>

<table align="center" border="1" cellspacing="0" cellpadding="8" style="width: 90%; border-collapse: collapse;">
  <tr>
    <td style="width: 150px; text-align: center;">
      <img src="" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>Ronald Joel Peralta Chipa - U202224619</strong></p>
      <p align="justify">
         ...
      </p>
    </td>
  </tr>
</table>

## 1.2. Solution Profile

Nuestra startup tiene como propósito mejorar la calidad de vida de los animales callejeros mediante una solución tecnológica que integra una aplicación web con dispositivos IoT implementados en refugios, permitiendo una gestión más eficiente, segura y monitoreada. Fundada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas en Perú, busca desarrollar herramientas innovadoras que respondan a las necesidades más urgentes del bienestar animal.

En colaboración con refugios, implementamos sensores de movimiento que detectan intentos de escape, así como sensores de temperatura y humedad que garantizan condiciones ambientales adecuadas. Asimismo, utilizamos sistemas de identificación para el seguimiento del estado de vacunación y cámaras térmicas para el monitoreo de la salud de los animales. La solución también incorpora bebederos inteligentes y sistemas de alimentación con sensores de peso, los cuales permiten supervisar el consumo y generar alertas ante posibles irregularidades.

Además, a través de nuestra plataforma web, los usuarios pueden involucrarse activamente mediante donaciones económicas dirigidas a los refugios, contribuyendo de manera directa a su sostenibilidad y a la mejora de las condiciones de vida de los animales en situación de calle.

| **Misión** | **Visión** | **Valores** |
|------------|------------|-------------|
| Nuestra misión es contribuir al bienestar de los animales callejeros mediante la integración de tecnologías IoT en refugios, optimizando su gestión y garantizando condiciones adecuadas. Brindamos una solución integral que conecta a los usuarios con refugios y clínicas veterinarias, promoviendo la adopción responsable y fomentando una comunidad comprometida contra el abandono animal. | Aspiramos a posicionarnos como líderes en Perú en soluciones tecnológicas para el bienestar animal. Visualizamos un futuro donde los refugios utilicen tecnologías IoT para asegurar el cuidado de los animales sin hogar, fortaleciendo la colaboración entre comunidades, refugios y profesionales, e inspirando a más personas a involucrarse en su protección. | ➤ Responsabilidad<br>➤ Colaboración<br>➤ Innovación |

### 1.2.1. Antecedentes y problemática

El bienestar de los animales callejeros en el Perú representa un desafío social y de salud pública crítico que ha sobrepasado la capacidad operativa de los refugios locales. A nivel de gestión, estudios de la Pontificia Universidad Católica del Perú (PUCP, 2025) revelan que el enfoque actual de bienestar animal se limita a la respuesta reactiva ante el sufrimiento, careciendo de herramientas técnicas que aseguren las "cinco libertades" del animal de forma constante. En Lima, donde se concentran 2 millones de perros en abandono, los refugios operan bajo un modelo de "acogida temporal" con recursos limitados, donde la supervisión de la salud y el comportamiento es puramente observacional y manual.

####  What? 

La problemática principal radica en la ineficiencia de los modelos de gestión tradicionales en los refugios de animales, los cuales dependen de procesos manuales para el monitoreo de salud, alimentación y seguridad. Según investigaciones en el ámbito de bienestar animal, la carencia de herramientas tecnológicas integradas (IoT) impide una supervisión constante y técnica, lo que incrementa los riesgos de mortalidad y dificulta la detección temprana de anomalías fisiológicas. Esta brecha tecnológica también obstaculiza la coordinación efectiva entre los albergues y las clínicas veterinarias, limitando la capacidad de respuesta ante emergencias.

####  When? 

El problema se manifiesta de forma continua durante la estancia del animal, pero se vuelve crítico cuando los refugios enfrentan una alta densidad de población. En situaciones de emergencia, como brotes de enfermedades contagiosas o intentos de escape, la falta de sistemas de alerta automatizados en tiempo real ralentiza las respuestas operativas, comprometiendo la integridad física y el bienestar de los animales.

####  Where? 

El problema se localiza físicamente en los refugios y albergues temporales, donde la supervisión se ve limitada por la infraestructura. Sin embargo, la problemática se extiende al entorno digital, donde los gestores, veterinarios y adoptantes carecen de una plataforma centralizada para monitorear sensores de movimiento, temperatura y alimentación, o para acceder a datos de cámaras térmicas e identificadores biométricos de forma remota.

#### Who? 
Esta situación afecta directamente a dos grupos principales:

1.  **Rescatistas y voluntarios:** Quienes asumen una carga operativa excesiva y enfrentan dificultades para garantizar la seguridad y salud de los animales bajo métodos empíricos.
    
2.  **Organizaciones de bienestar animal:** Entidades que buscan escalar su impacto mediante la implementación de tecnologías avanzadas para optimizar el control ambiental y la gestión de recursos.
    

####  Why? 

De acuerdo con Pinto (2021), la gestión deficiente de los refugios en el Perú es consecuencia de la escasez de recursos económicos y la ausencia de políticas públicas eficaces. A esto se suma una baja concienciación social sobre la adopción responsable. Desde una perspectiva técnica, la problemática persiste debido a la nula integración de tecnologías de seguimiento y control automatizado, lo que perpetúa modelos de cuidado reactivos en lugar de preventivos.

#### How?

Los distintos actores enfrentan este escenario interactuando a través de un ecosistema de productos digitales que transforma variables físicas en información procesable y visual. En las instalaciones, la recolección continua de parámetros ambientales y biométricos alimenta paneles de control interactivos e interfaces adaptables a cualquier dispositivo móvil o web.

Esta interacción permite a los albergues anticipar emergencias y automatizar sus recursos diarios, a las clínicas veterinarias priorizar sus intervenciones basándose en cálculos y tendencias estadísticas del estado de los animales, y a los donantes explorar reportes cuantitativos que les muestran el impacto directo de su apoyo. De esta manera, el monitoreo físico evoluciona hacia una red colaborativa e inclusiva que mantiene a todas las partes sincronizadas en tiempo real

####  How Much? 

El impacto es severo y cuantificable. En el contexto regional, se estima que de los más de 286,000 perros y gatos recogidos anualmente por diversas entidades, un 15.6% no sobrevive debido a la precariedad en los cuidados y la falta de atención médica oportuna (Fundación Affinity, s.f.). Estas cifras subrayan la necesidad urgente de implementar soluciones tecnológicas que reduzcan la tasa de mortalidad y aseguren estándares de bienestar animal dignos.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3 Segmentos Objetivo

| Segmento | Descripción | Características |
|----------|-------------|-----------------|
| **Segmento 1: Administradores de refugios** | Este segmento de usuarios es clave, ya que son los encargados de gestionar el cuidado y la adopción de animales callejeros. Necesitan herramientas para contabilizar los animales que tienen bajo su cuidado y aquellos que están listos para ser adoptados, además de la posibilidad de recibir apoyo financiero a través de donaciones. | - **Edades:** 20 a 50 años <br> - **Ubicación:** Perú <br> - **Motivaciones:** Alta preocupación por el bienestar animal y deseo de facilitar la adopción. <br> - **Intereses:** Protección y derechos de los animales, gestión de recursos y networking. <br> - **Comportamiento:** Proactivos en la búsqueda de apoyo; buscan plataformas que faciliten la visibilidad y recaudación. |
| **Segmento 2: Veterinarios** | Este segmento incluye a las clínicas veterinarias que colaboran con los refugios para proporcionar atención médica a los animales. Las clínicas buscan optimizar su coordinación con los refugios y aprovechar el sistema de alertas y financiamiento que ofrece la plataforma para atender a los animales de manera más eficiente. | - **Edades:** 20 a 60 años <br> - **Ubicación:** Perú <br> - **Motivaciones:** Proporcionar atención de calidad y mejorar la coordinación con refugios. <br> - **Intereses:** Innovación en servicios, responsabilidad social empresarial y eficiencia operativa. <br> - **Comportamiento:** Buscan herramientas tecnológicas para optimizar su gestión, valorando los sistemas de alertas y financiamiento. |
<br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming
## 2.5. Ubiquitous Language

<br>

# Capítulo III: Requirements Specification

## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

<br>

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. Design-Level EventStorming
#### 4.1.1.1 Candidate Context Discovery
#### 4.1.1.2 Domain Message Flows Modeling
#### 4.1.1.3 Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture System Landscape Diagram
#### 4.1.3.2. Software Architecture Context Level Diagrams
#### 4.1.3.3. Software Architecture Container Level Diagrams
#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram

<br>

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines
### 5.1.1. General Style Guidelines
### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture
### 5.2.1. Organization Systems
### 5.2.2. Labeling Systems
### 5.2.3. SEO Tags and Meta Tags
### 5.2.4. Searching Systems
### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design
### 5.3.1. Landing Page Wireframe
### 5.3.2. Landing Page Mock-up

## 5.4. Applications UX/UI Design
### 5.4.1. Applications Wireframes
### 5.4.2. Applications Wireflow Diagrams
### 5.4.3. Applications Mock-ups
### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping
## 5.6. IoT Device Design

<br>

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management
### 6.1.1. Software Development Environment Configuration
### 6.1.2. Source Code Management
### 6.1.3. Source Code Style Guide & Conventions
### 6.1.4. Software Deployment Configuration

## 6.2. Landing Page, Services & Applications Implementation
### 6.2.X. Sprint n
#### 6.2.X.1. Sprint Planning n
#### 6.2.X.2. Aspect Leaders and Collaborators
#### 6.2.X.3. Sprint Backlog n
#### 6.2.X.4. Development Evidence for Sprint Review
#### 6.2.X.5. Testing Suite Evidence for Sprint Review
#### 6.2.X.6. Execution Evidence for Sprint Review
#### 6.2.X.7. Services Documentation Evidence for Sprint Review
#### 6.2.X.8. Software Deployment Evidence for Sprint Review
#### 6.2.X.9. Team Collaboration Insights during Sprint

## 6.3. Validation Interviews
### 6.3.1. Diseño de Entrevistas
### 6.3.2. Registro de Entrevistas
### 6.3.3. Evaluaciones según heurísticas

## 6.4. Video About-the-Product

<br>

# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team

<br>

# Bibliografía

<br>

# Anexos
Link del Repositorio del Informe: 
Link del Repositorio del Backend: 
Link del Repositorio del Frontend Aplicación Web: 
Link del Repositorio del Frontend Aplicación Móvil: 
