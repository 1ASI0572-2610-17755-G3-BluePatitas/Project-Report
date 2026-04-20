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
    <td style="width: 150px; text-align: center;">
      <img src="" width="150"></img>
    </td>
    <td>
      <p align="center"><strong>Luciana Carolina Choquehuanca Nuñez - U202319431</strong></p>
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
### 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

<br>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores 

Para esta sección analizaremos y compararemos a diversos competidores que pudimos llegar a encontrar para así transferir conocimiento detectando las mejores opciones y prácticas que aplicar para nuestra aplicación.

Los competidores se pueden dividir en varios tipos, como los que hacen exactamente lo mismo que nosotros, los que no hacen lo mismo pero pueden llegar a solucionarlo, los de mayor rango que serían los que consideramos que estamos muy lejos de alcanzarlos, etc. 

Al terminar el análisis competitivo y teniendo en mente las ventajas y desventajas de nuestros competidores podremos emplear mejores estrategias contra ellos.

Como competidores tenemos:
* WUF
* DogHero
* Petfinder

A continuación se presenta una tabla evaluando a estos competidores para la solución propuesta:

| Nombre | Descripción | Características | Distribución |
| :--- | :--- | :--- | :--- |
| **WUF** | Organización sin fines de lucro en Perú dedicada a reducir el número de perros callejeros mediante campañas de esterilización, educación y promoción de la adopción. | Cuenta con una fuerte presencia local y una red establecida de voluntarios y aliados. Sin embargo, su enfoque se limita principalmente a los perros y tiene alta dependencia de donaciones externas. | Plataforma web y fuerte presencia en redes sociales (Facebook, Instagram) para campañas locales, recaudación de fondos y promoción de adopciones. |
| **DogHero** | Plataforma en América Latina enfocada en servicios de cuidado de mascotas (como paseos y alojamiento) que también ofrece opciones para promover la adopción. | Posee una amplia red de usuarios en LATAM debido a la diversificación de sus servicios, aunque su enfoque principal no es la adopción, lo que enfrenta a la plataforma con un alto nivel de competencia. | Aplicación y plataforma digital disponible a nivel regional (Brasil y otros países de América Latina). |
| **Petfinder** | Plataforma internacional para la adopción de mascotas que funciona como intermediario para conectar refugios y rescates con personas que buscan adoptar. | Tiene un alcance global y una base tecnológica muy fuerte que incluye funciones avanzadas de búsqueda y filtros, aunque su enfoque global dificulta la adaptación a necesidades locales. | Plataforma web a nivel global y distribución digital a gran escala. |

### 2.1.1. Análisis competitivo 

| **Competitive Analysis Landscape** | **Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.** |
| :---- | :---- |
| ¿Por qué llevar a cabo este análisis?  | Deseamos analizar a nuestros competidores para buscar en qué puntos podemos mejorar, contra que nos estamos enfrentando en el mercado y como nos distinguimos de estos |

| Categoría | Factores | **BluePatitas** | **WUF** | **DogHero** | **Petfinder** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | Startup peruana  que integra software y hardware IoT para automatizar el monitoreo de salud, seguridad y ambiente en refugios de animales. | ONG peruana dedicada a la promoción de la adopción responsable y la gestión de una plataforma de marketplace para financiar refugios. | Plataforma digital que conecta a dueños de mascotas con una red de anfitriones certificados para hospedaje, paseos y guardería. | El directorio de adopción de animales más grande a nivel global, facilitando la conexión entre miles de refugios y potenciales adoptantes. |
| | **Ventaja competitiva** | • Monitoreo técnico en tiempo real mediante IoT.<br>• Alertas preventivas de salud y seguridad.<br>• Transparencia en donaciones vinculada al estado real del animal. | • Marca líder y reconocida en el mercado peruano.<br>• Alianzas estratégicas con empresas de retail y consumo masivo.<br>• Comunidad digital sólida y activa ("Wulovers"). | • Confianza basada en un sistema riguroso de reseñas y evaluaciones.<br>• Incluye "Garantía Veterinaria" en cada reserva.<br>• App móvil con UX optimizada para reservas rápidas. | • Base de datos masiva con integración de miles de organizaciones internacionales.<br>• Herramientas avanzadas de filtrado.<br>• Respaldo corporativo de Nestlé Purina. |
| **Perfil de Marketing** | **Mercado objetivo** | Refugios de animales, organizaciones de bienestar animal y donantes que buscan trazabilidad tecnológica. | Personas en Perú interesadas en la adopción responsable y consumidores de productos con impacto social. | Dueños de mascotas de áreas urbanas que requieren cuidado personalizado por viajes o trabajo. | Público global interesado en la adopción y organizaciones de rescate que buscan visibilidad. |
| | **Estrategias de marketing** | Demostración de eficiencia operativa en refugios, alianzas académicas y marketing de transparencia basado en datos. | Colaboraciones B2B, campañas de sensibilización emocional y eventos presenciales de adopción. | Marketing de influencers, sistemas de referidos y publicidad segmentada en redes sociales. | Optimización masiva en buscadores (SEO) para términos de adopción y patrocinios de marcas de alimentos. |
| **Perfil de Producto** | **Productos & Servicios** | Aplicación web de gestión, sensores IoT (movimiento, temp/hum), cámaras térmicas, bebederos inteligentes y pasarela de donaciones. | Marketplace de accesorios, plataforma de adopción y programas de padrinazgo para albergues. | Servicios de hospedaje en casas particulares, paseos diarios, guardería y visitas a domicilio. | Directorio de búsqueda de mascotas, recursos educativos sobre cuidado animal y gestión de voluntarios. |
| | **Precios & Costos** | Modelo de suscripción para refugios por implementación técnica y porcentaje por gestión de donaciones. | Productos con precios competitivos; las adopciones pueden incluir un costo administrativo o donación sugerida. | Tarifas flexibles establecidas por cada anfitrión (promedio S/ 30 - S/ 70 por noche). | Gratuito para adoptantes; ingresos vía publicidad y financiamiento corporativo. |
| | **Canales de distribución** | Aplicación web (SaaS) e instalación física de dispositivos IoT en refugios aliados. | Plataforma web (e-commerce) y redes sociales. | App móvil nativa (iOS/Android) y sitio web interactivo. | Portal web global y aplicación móvil. |
| **Análisis SWOT** | **Fortalezas** | • Única solución con monitoreo automatizado IoT.<br>• Capacidad de detección temprana de enfermedades mediante telemetría. | • Alta reputación y confianza en el mercado local.<br>• Red consolidada de albergues afiliados en todo el país. | • Modelo de negocio escalable con baja inversión en infraestructura física.<br>• Excelente sistema de atención al cliente y seguros. | • Dominio absoluto del tráfico de búsqueda internacional.<br>• Capacidad tecnológica avanzada para manejo de Big Data. |
| | **Debilidades** | • Costos iniciales de hardware e implementación en refugios con pocos recursos.<br>• Etapa temprana de desarrollo (Startup). | • Dependencia directa de ventas de terceros y donaciones.<br>• Limitación geográfica al mercado nacional (Perú). | • Riesgos operativos inherentes al cuidado en hogares externos.<br>• Percepción de precios altos por las comisiones. | • Dificultad para verificar la actualización en tiempo real de refugios pequeños.<br>• Interfaz web saturada. |
| | **Oportunidades** | • Expansión a clínicas veterinarias para hospitalización.<br>• Venta de data analítica sobre comportamiento animal. | • Implementación de servicios veterinarios digitales o telemedicina.<br>• Desarrollo de una línea de productos propia. | • Expansión hacia servicios de entrenamiento y salud preventiva.<br>• Alianzas con aerolíneas y hoteles. | • Integración de IA para el "match" perfecto de adopción.<br>• Expansión en mercados emergentes de Latam. |
| | **Amenazas** | • Rápida evolución de componentes de hardware.<br>• Resistencia al cambio tecnológico por parte de refugios tradicionales. | • Volatilidad económica que afecte el consumo.<br>• Surgimiento de nuevas ONGs con modelos similares. | • Competencia directa de hoteles caninos y veterinarias.<br>• Cambios en regulaciones de hospedaje animal. | • Aparición de apps locales con enfoques más personalizados.<br>• Cambios en los algoritmos de búsqueda. |

### 2.1.2. Estrategias y tácticas frente a competidores 

#### **Estrategia 1: Diferenciación a través del monitoreo inteligente y transparencia de datos**

 **Táctica 1.1: Implementación de un Dashboard IoT de monitoreo en tiempo real**

-   Desarrollar una interfaz dentro de la plataforma web que permita a los administradores de refugios visualizar indicadores biométricos (temperatura, peso) y ambientales (humedad, calor) capturados por los sensores, facilitando una gestión basada en datos técnicos.
    
-   Configurar un sistema de alertas críticas automáticas que notifique instantáneamente vía web o móvil ante intentos de escape (sensores de movimiento) o irregularidades en la alimentación (sensores de peso en bebederos).
    

 **Táctica 1.2: Historial clínico digital e inteligente**

-   Crear una base de datos centralizada que registre automáticamente la información recolectada por los identificadores y cámaras térmicas, proporcionando a los veterinarios un historial detallado del estado de salud del animal desde su ingreso.
    
-   Ofrecer a los donantes y futuros adoptantes un reporte de bienestar generado por el sistema, garantizando que el animal ha vivido en condiciones óptimas de temperatura y nutrición, lo que eleva el valor de confianza frente a la competencia.
    

----------

#### **Estrategia 2: Fortalecimiento de la comunidad mediante el "Padrinazgo Tecnológico"**

 **Táctica 2.1: Campañas de educación sobre Bienestar Animal 4.0**

-   Lanzar campañas digitales para concienciar sobre cómo la tecnología IoT reduce las tasas de mortalidad en refugios, educando a la comunidad sobre la importancia de pasar de un cuidado manual a uno automatizado y preventivo.
    
-   Colaborar con estudiantes y facultades de ingeniería para promover el desarrollo de soluciones tecnológicas en favor de los animales, posicionando a BluePatitas como un referente de innovación social en el Perú.
    

**Táctica 2.2: Programa de transparencia para donantes**

-   Implementar un sistema donde cada donación económica se vea reflejada en el sostenimiento de los sensores y dispositivos IoT del refugio, permitiendo al usuario sentir que su aporte tiene un impacto directo y medible en la seguridad del animal.
    
-   Organizar "Open Days" tecnológicos en los refugios aliados para que la comunidad vea en funcionamiento los bebederos inteligentes y sistemas de control ambiental, fortaleciendo el vínculo emocional y la credibilidad de la startup.
    

----------

####  **Estrategia 3: Alianzas estratégicas para la sostenibilidad operativa**

 **Táctica 3.1: Acuerdos exclusivos de soporte técnico con refugios y clínicas**

-   Establecer convenios con refugios estratégicos en zonas críticas de Lima (como Lima Norte o Este) para ser su proveedor exclusivo de tecnología de monitoreo, asegurando una red de albergues "Smart" que superen la oferta de gestión básica de otras plataformas.
    
-   Integrar el acceso de las cámaras térmicas y datos de salud con clínicas veterinarias aliadas para permitir una telemetría básica antes de que el animal sea trasladado para atención presencial, optimizando tiempos y recursos.
    

 **Táctica 3.2: Escalabilidad y expansión basada en datos de impacto**

-   Iniciar la fase piloto en los refugios con mayor índice de hacinamiento en Lima Metropolitana, recolectar métricas de éxito (reducción de escapes, mejora en tiempos de respuesta médica) y utilizar estos datos para atraer inversión y expandirse a provincias.
    
-   Evaluar la adaptación del hardware IoT para su implementación en hogares de acogida temporal, permitiendo que la red de voluntarios de BluePatitas tenga el mismo nivel de control y seguridad que un refugio profesional.


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
