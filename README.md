
<div align="center">
<img src="images/logo-upc.png" width="150" alt="Logo de la UPC"><br><br>

**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**<br>
**FACULTAD DE INGENIERÍA**<br>
**CARRERAS: INGENIERÍA DE SOFTWARE / INGENIERÍA DE SISTEMAS DE INFORMACIÓN**<br>
**Desarrollo de Aplicaciones Open Source - 7800**<br><br>

**DOCENTE**<br>
Iván Robles Fernandez<br><br>

**Informe AV1 Sprint Review**<br><br>

**Nombre Start up:** SafeZone<br>
**Nombre Producto:** NodeSecure<br><br>

**2026-02**<br><br>

**INTEGRANTES**<br><br>

<table>
  <thead>
    <tr>
      <th>Apellidos y Nombres</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Anahua Ancachi, Liz Maribel</td>
      <td>U202421123</td>
    </tr>
    <tr>
      <td>Sandoval Aiquipa, Kelber Yamir</td>
      <td>U202418645</td>
    </tr>
    <tr>
      <td>Pérez Bellido, Fernando Sebastián</td>
      <td>U202410420</td>
    </tr>
    <tr>
      <td>Ravello Cárdenas, Luciana Angielina</td>
      <td>U20221F887</td>
    </tr>
  </tbody>
</table>
<br>

**Lima, 16 de Setiembre del 2026**

</div>
<br><br><br><br><br><br>

## Registro de versiones del informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><b>AV1</b></td>
      <td valign="top">16/09/2026</td>
      <td valign="top">
        Anahua Ancachi, Liz Maribel<br>
        Sandoval Aiquipa, Kelber Yamir<br>
        Pérez Bellido, Fernando Sebastián<br>
        Ravello Cárdenas, Luciana Angielina
      </td>
      <td valign="top">Se realizó todo lo detallado en la primera entrega de AV1 – Sprint Review, que consiste desde el capítulo 1 hasta el punto 5.2.1.8. Team Collaboration Insights during Sprint. A esto se le agregó la primera versión de las conclusiones, la bibliografía y los anexos.</td>
    </tr>
    <tr>
      <td><b>TB1</b></td>
      <td>-</td>
      <td>-</td>
      <td>En proceso</td>
    </tr>
    <tr>
      <td><b>AV2</b></td>
      <td>-</td>
      <td>-</td>
      <td>En proceso</td>
    </tr>
    <tr>
      <td><b>TF1</b></td>
      <td>-</td>
      <td>-</td>
      <td>En proceso</td>
    </tr>
  </tbody>
</table>

<br><br><br><br>

# Contenido
[**Capítulo I: Introducción**](#capítulo-i-introducción)<br>
&nbsp;&nbsp;&nbsp;&nbsp;*[1.1. Startup Profile](#11-startup-profile)*<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.1.2. Perfiles de integrantes del equipo](#112-integrantes-del-equipo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;*[1.2. Solution Profile](#12-solution-profile)*<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2 Lean UX Process](#122-lean-ux-process)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statement)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statement)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[1.3. Segmentos objetivo](#13-segmentos-objetivo)<br><br>
[**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[2.1. Competidores](#21-competidores)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1.1. Análisis competitivo](#211-análisis-competitivo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[2.2. Entrevistas](#221-diseño-de-entrevistas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2.2. Registro de entrevistas](#segmento-01-dueños-y-administradores-de-almacén)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[2.3. Needfinding](#23-needfinding)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.1. User Personas](#231-user-personas)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.2. User Task Matrix](#232-user-task-matrix)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.3. User Journey Mapping](#233-user-journey-mapping)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3.4. Empathy Mapping](#234-empathy-mapping)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[2.4. Big Picture Event Storming](#24-big-picture-event-storming)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[2.5. Ubiquitous Language](#25-ubiquitous-language)<br><br>
[**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.1. User Stories](#31-user-stories)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.2. Impact Mapping](#32-impact-mapping)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[3.3. Product Backlog](#33-product-backlog)<br><br>
[**Capítulo IV: Product Design**](#capítulo-iv-product-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.1. Style Guidelines](#41-style-guidelines)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.1.1. General Style Guidelines](#411-general-style-guidelines)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.1.2. Web Style Guidelines](#412-web-style-guidelines)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.2. Information Architecture](#42-information-architecture)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2.1. Organization Systems](#421-organization-systems)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2.2. Labeling Systems](#422-labeling-systems)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2.4. Searching Systems](#424-searching-systems)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2.5. Navigation Systems](#425-navigation-systems)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.3. Landing Page UI Design](#43-landing-page-ui-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.5. Web Applications Prototyping](#45-web-applications-prototyping)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.6.1. Design-Level Event Storming](#461-design-level-event-storming)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.7.1. Class Diagrams](#471-class-diagrams)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[4.8. Database Design](#48-database-design)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.8.1. Database Diagrams](#481-database-diagrams)<br><br>
[**Capítulo V: Product Implementation, Validation & Deployment**](#5-product-implementation-validation--deployment)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[5.1. Software Configuration Management](#51-software-configuration-management)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.1.2. Source Code Management](#512-source-code-management)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)<br>
&nbsp;&nbsp;&nbsp;&nbsp;[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1. Sprint 1](#521-sprint-1)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)<br><br>
[Conclusiones](#conclusiones)<br>
[Bibliografía](#bibliografía)<br>
[Anexos](#anexos)<br><br><br>


# Student Outcome
En esta sección se detalla la contribución de cada integrante del equipo para explicar cómo las actividades y entregables del trabajo final han ayudado a desarrollar las dimensiones del Student Outcome correspondiente a la competencia de Comunicación. En esta sección se describe la relación entre el outcome, sus criterios y el trabajo colaborativo e individual realizado a lo largo del proyecto. Esto se complementa con lo reflejado en los testimonios expuestos que forman parte del video acerca del equipo.

<table>
<thead>
  <tr>
    <th width="30%">Criterio específico</th>
    <th width="40%">Acciones realizadas</th>
    <th width="30%">Conclusiones</th>
  </tr>
</thead>
<tbody>
  <!-- Criterio 3.c1 -->
  <tr>
    <td rowspan="4" valign="top"><b>3.c1. Comunica oralmente con efectividad a diferentes rangos de audiencia</b></td>
    <td valign="top">
      <b>AV1</b><br><br>
      <b>Anahua Ancachi, Liz Maribel:</b> Condujo y moderó oralmente las entrevistas semiestructuradas con los usuarios del segmento operativo (Segmento 2), transmitiendo las preguntas de manera clara y adaptando el lenguaje técnico a situaciones cotidianas de almacén. Asimismo, expuso y sustentó en las reuniones de equipo los hallazgos del Needfinding y los perfiles de User Personas desarrollados para el Capítulo II.<br><br>
      <b>Sandoval Aiquipa, Kelber Yamir:</b> Expuso de manera fluida y persuasiva la lógica de interacción y los diseños de UX/UI durante las sesiones de revisión. Justificó las decisiones de diseño (uso de Dark Mode, diagramas de flujos y mockups) ante el equipo y en el video de exposición, empleando un tono adecuado y profesional para alinear la visión técnica con los objetivos del negocio.<br><br>
      <b>Pérez Bellido, Fernando Sebastián:</b><br><br>
      <b>Ravello Cárdenas, Luciana Angielina:</b> Sustentó verbalmente las bases del modelo de negocio, segmentos objetivo e hipótesis del Lean UX para el Capítulo I. Realizó aportes en un lenguaje claro y fácil de entender durante las reuniones de coordinación. También contribuyó con las entrevistas, expresándose de manera clara.
    </td>
    <td valign="top">
      <b>AV1</b><br><br>
      En esta primera entrega, como equipo concluimos que ha sido muy importante mantener una comunicación oral activa mediante debates y reuniones de coordinación para alinear la visión del proyecto. Hemos podido compartir nuestras ideas individuales de forma efectiva para definir la problemática y la solución adaptándonos para asegurarnos de que todos estemos en sintonía respecto a los objetivos del producto.
    </td>
  </tr>
  <tr>
    <td><b>TB1</b></td>
    <td><b>TB1</b></td>
  </tr>
  <tr>
    <td><b>AV2</b></td>
    <td></td>
  </tr>
  <tr>
    <td><b>VF1</b></td>
    <td><b>VF1</b></td>
  </tr>

  <!-- Criterio 3.c2 -->
  <tr>
    <td rowspan="4" valign="top"><b>3.c2. Comunica por escrito con efectividad a diferentes rangos de audiencia</b></td>
    <td valign="top">
      <b>AV1</b><br><br>
      <b>Anahua Ancachi, Liz Maribel:</b> Redactó las secciones principales del Capítulo II (Requirements Elicitation & Analysis), documentando el análisis competitivo, el diseño y registro de entrevistas, y el análisis de variables. Estructuró por escrito el Needfinding (necesidades identificadas), los artefactos UX (User Personas, User Task Matrix, User Journey Mapping y Empathy Mapping) de forma clara, técnica y profesional para la evaluación del informe.<br><br>
      <b>Sandoval Aiquipa, Kelber Yamir:</b> Redactó exhaustivamente la sección de Product Design (Capítulo 4.4), documentando los User Flows, Wireflows y Mockups. Empleó un enfoque de redacción técnica orientada al dominio de negocio (Domain-Driven Design), utilizando términos logísticos y operativos precisos para describir correctamente la funcionalidad de cada interfaz.<br><br>
      <b>Pérez Bellido, Fernando Sebastián:</b><br><br>
      <b>Ravello Cárdenas, Luciana Angielina:</b> Redactó las secciones principales del Capítulo I (Startup Profile, proceso Lean UX y Segmentos Objetivo). Utilizó un lenguaje escrito adecuado y estructurado para documentar la información, asegurando su comprensión tanto para la evaluación académica como para un público logístico-comercial.
    </td>
    <td valign="top">
      <b>AV1</b><br><br>
      Llegamos a la conclusión de que la colaboración en esta etapa nos permitió determinar un estándar de redacción sólido y profesional para el informe. Se consiguió levantar el contexto del sistema IoT de manera estructurada y presentar el valor de nuestra propuesta tecnológica de forma clara y entendible.
    </td>
  </tr>
  <tr>
    <td><b>TB1</b></td>
    <td><b>TB1</b></td>
  </tr>
  <tr>
    <td><b>AV2</b></td>
    <td><b>AV2</b></td>
  </tr>
  <tr>
    <td><b>VF1</b></td>
    <td><b>VF1</b></td>
  </tr>
</tbody>
</table>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

En el entorno logístico y empresarial actual, el control de inventarios y la seguridad de los almacenes enfrentan grandes desafíos, especialmente debido a las pérdidas por el "robo hormiga", accesos no autorizados y a un monitoreo deficiente en tiempo real. Los sistemas de seguridad tradicionales suelen ser puramente reactivos, limitándose a grabar incidentes sin ofrecer herramientas analíticas para prevenirlos de forma inmediata. Frente a este escenario, SafeZone emerge como una startup tecnológica enfocada en transformar la gestión de la seguridad industrial y comercial. Nuestra misión es ofrecer un ecosistema inteligente que permita a los negocios dejar atrás la vigilancia pasiva, otorgándoles un control activo y preventivo sobre sus activos más valiosos.

Para dar solución a esta problemática, SafeZone ha desarrollado NodeSecure, una plataforma inteligente de control de inventario potenciada por la trazabilidad de la tecnología IoT. NodeSecure va mucho más allá de ser un simple registro digital de productos o un hardware que controla puertas físicas; es un sistema web integral que relaciona directamente los movimientos operativos del inventario con los eventos físicos que suceden dentro de las instalaciones. La idea central que hace único a nuestro producto es que el software registra detalladamente lo que digitalmente debería ocurrir, mientras que los dispositivos IoT actúan como evidencia física para informar lo que realmente sucedió en el espacio.

El ecosistema de NodeSecure funciona utilizando dispositivos físicos simples, como sensores magnéticos, que reportan constantemente la actividad del entorno. Cuando la plataforma detecta un evento físico, como la apertura de un almacén, lo compara de forma automática con el historial de entradas y salidas registradas. Si se produce una acción física que no cuenta con un movimiento de inventario asociado que la justifique, el sistema identifica la discrepancia y genera una alerta inmediata. Gracias a un dashboard unificado, los administradores pueden supervisar múltiples áreas, auditar quién realizó cada operación y mantener una trazabilidad temporal exacta, facilitando respuestas rápidas ante cualquier irregularidad o desconexión.

La propuesta de valor de SafeZone está diseñada bajo un modelo altamente escalable, adaptándose tanto a dueños de PYMES que buscan soluciones accesibles para evitar mermas diarias, como a jefes de operaciones que requieren controlar redes complejas y auditar incidentes de forma rigurosa. El verdadero diferencial comercial de NodeSecure radica en brindar una visibilidad operativa total: permite a los usuarios saber con precisión qué mercancía salió, quién fue el responsable de registrarla, en qué momento exacto ocurrió y, lo más importante, advertir al instante si hubo alguna actividad física anómala que no cuadre con el registro oficial.


### 1.1.2 Integrantes del equipo

<table>
  <tr>
    <td align="center">
      <img src="images/liz-foto.png" width="600" alt="Foto de Liz">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Anahua Ancachi Liz Maribel<br>
      <strong>Código:</strong> U202421123<br>
      <strong>Carrera:</strong> Ingeniería de Software<br><br>
      Estudiante de Ingeniería de Software en la UPC de quinto ciclo de la carrera. Tengo conocimientos básicos en C++, SQL. Me considero una persona responsable y empática a la hora de colaborar en equipo. Además, me encanta el diseño y plantear soluciones creativas a los problemas para entregar el mejor resultado posible.
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/sebastian-foto.png" width="600" alt="Foto de Fernando">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Fernando Sebastián Pérez Bellido<br>
      <strong>Código:</strong> U202410420<br>
      <strong>Carrera:</strong> Ingeniería de Software<br><br>
      Estudiante de Ingeniería de Software en la UPC con un enfoque en la creación de soluciones tecnológicas que generen impacto real. Cuento con bases sólidas en C++, Python y un poco de conocimiento en React, complementadas con conocimientos en SQL y entornos cloud. Me apasiona aplicar la lógica algorítmica para resolver problemas complejos.
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/luciana-foto.png" width="600" alt="Foto de Luciana">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Ravello Cárdenas Luciana Angielina<br>
      <strong>Código:</strong> U20221F887<br>
      <strong>Carrera:</strong> Ingeniería de Software<br><br>
      Estudiante de Ingeniería de Software en la UPC cursando el quinto ciclo de la carrera. Tengo conocimientos en C++, SQL y Figma. Se me considera una persona amable y responsable, lo que ayuda a crear un buen ambiente en equipo. Siempre estoy dispuesta a escuchar opiniones y sugerencias para mejorar la calidad de los trabajos entregados.
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/kelber-foto.png" width="600" alt="Foto de Kelber">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Sandoval Aiquipa Kelber Yamir<br>
      <strong>Código:</strong> U202418645<br>
      <strong>Carrera:</strong> Ingeniería de Software<br><br>
      Estudiante de Ingeniería de Software en la UPC, cursando el quinto ciclo. Soy un apasionado por el diseño de experiencia de usuario (UX/UI) y la creación de interfaces limpias, accesibles e intuitivas. Gracias a mi experiencia liderando equipos y gestionando la atención directa con el público, he desarrollado una gran empatía para entender las necesidades de los usuarios y traducirlas en soluciones tecnológicas efectivas. Me gusta aportar creatividad, orden y una excelente comunicación para asegurar que el producto final no solo funcione bien, sino que se vea increíble.
    </td>
  </tr>
</table>


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

Hoy en día, la gestión logística y el sector retail enfrentan un desafío crítico que compromete directamente su rentabilidad: la pérdida sistemática de inventario. En Perú, estudios revelan que las mermas en el sector comercial peruano generan pérdidas de entre S/ 700 y S/ 1,000 millones anuales. Lo más preocupante es que cerca del 52% de estas pérdidas corresponde a la llamada "merma desconocida", una categoría conformada en su gran mayoría por hurtos, fraudes y el persistente "robo hormiga". Este último fenómeno, caracterizado por la sustracción de pequeñas cantidades de mercadería a lo largo del tiempo, resulta sumamente complejo de detectar mediante auditorías convencionales, acumulando daños financieros severos para las empresas (Conexión ESAN, 2026).

**<ins>5W + 2H de la problemática</ins>**

- **What? (¿Cuál es el problema?):** Pérdidas económicas significativas en los sectores de logística y retail debido a la "merma desconocida", específicamente por robos hormiga, hurtos y fraudes.

- **Who? (¿Quién lo sufre?):** Dueños de PYMES, gerentes de operaciones y jefes de seguridad en el sector retail, distribución y logística. 

- **Where? (¿Dónde ocurre?):** En almacenes, depósitos, bodegas y centros de distribución de empresas comerciales en Perú y en toda Latinoamérica.

- **When? (¿Cuándo ocurre?):** Durante la gestión diaria de inventarios, especialmente cuando los procesos de vigilancia son pasivos o reactivos y no permiten una detección inmediata de irregularidades.

- **Why? (¿Por qué ocurre?):** Por la desconexión operativa entre los registros digitales y la realidad física del almacén, sumado a que las empresas perciben la tecnología IoT preventiva comos costosa o compleja de implementar.

- **How? (¿Cómo se manifiesta?):** Mediante descuadres de inventario recurrentes, accesos físicos no detectados a tiempo (robo hormiga), revisiones manuales tardías y una pérdida total de trazabilidad operativa por la ausencia de sensores IoT que validen los registros digitales en tiempo real. 

- **How much? (¿Cuánto afecta?):**  Provoca continuas mermas económicas por falta de control físico, pérdida de inventario por "robos hormiga" y un elevado costo de oportunidad debido a la excesiva carga de tareas manuales al tener que auditar cámaras e incidentes de forma tardía.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statement

**El estado actual de** la gestión de inventario y seguridad operativa en almacenes **se ha enfocado principalmente en** el uso de sistemas de vigilancia estrictamente reactivos (como cámaras CCTV o candados) y en registros digitales aislados, obligando a las empresas a realizar auditorías manuales lentas y a depender de sistemas desconectados para investigar las mermas.

**Lo que los productos y servicios existentes no logran abordar es** la profunda desconexión entre los movimientos teóricos del sistema y los eventos físicos que realmente ocurren, sumado a la fuerte barrera económica que hace que las empresas rechacen tecnologías avanzadas al percibirlas como excesivamente costosas y complejas de implementar.

**Nuestro producto** (NodeSecure) **abordará esta brecha mediante** una plataforma web centralizada de control de inventario inteligente que permite monitorear los espacios, controlar accesos y gestionar la información en tiempo real, ya que utiliza tecnología IoT como fuente de evidencia física. El sistema valida y contrasta de forma automática las actividades registradas con cada apertura física realizada, identificando inconsistencias inmediatamente, optimizando la trazabilidad del inventario y enviando alertas en tiempo real.

**Nuestro enfoque inicial será** los dueños y administradores de PYMES, así como también los jefes de seguridad y operaciones del sector logístico.

**Sabremos que tenemos éxito cuando veamos** una alta tasa de retención en nuestros planes de suscripción, una adopción rápida de la plataforma sin necesidad de capacitaciones complejas, y una reducción comprobable en los tiempos de respuesta ante intrusiones y en las pérdidas originadas por robos internos en los almacenes de los clientes.


#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions (Supuestos de Negocio)**
- Creemos que ofrecer un modelo SaaS por suscripción mensual escalable en tres niveles  (Básico, Premium y Corporativo) será financieramente viable y atractivo para distintos tamaños de empresa, permitiendo que las PYMES adopten nuestra solución sin barreras de entrada.
- Asumimos que NodeSecure logrará posicionarse y diferenciarse de la competencia no como un sistema de alarmas tradicional, sino como una plataforma inteligente que cruza en tiempo real los eventos físicos del almacén con los registros digitales de inventario. 
- Creemos que delegar la detección física a dispositivos de hardware y accesibles (como ESP32 y sensores magnéticos de puerta) nos permitirá enfocar todos nuestros recursos en perfeccionar el desarrollo de la plataforma de software, sin tener que asumir altos costos de mantenimiento de hardware.
- Asumimos que lograremos captar la retención de nuestro mercado objetivo de manera satisfactoria destacando la accesibilidad económica de la solución y su facilidad de despliegue, frente a los sistemas tradicionales que las empresas perciben como altamente costosos o complejos.


**Business Outcome Assumptions (Supuestos de Resultados de Negocio)**
- Creemos que el éxito de SafeZone se reflejará en un incremento sostenido de empresas suscritas a la plataforma NodeSecure a través de sus distintos planes.
- Asumimos que garantizaremos una alta tasa de retención, particularmente de clientes corporativos, siempre que la plataforma web sea estable, confiable y precisa en la emisión de notificaciones en tiempo real.
- Creemos que las empresas que implementen nuestro producto lograrán reducir de forma significativa sus mermas económicas y pérdidas provocadas por el "robo hormiga" y los accesos no autorizados.
- Asumimos que el uso de nuestro sistema impulsará un cambio en la forma en que las empresas y comercios gestionan su seguridad, logrando que las empresas migren de un modelo de vigilancia reactiva a una gestión de seguridad preventiva.


**User Assumptions (Supuestos del Usuario)**
- Creemos que nuestros usuarios para los planes básicos son dueños o administradores de PYMES que gestionan pequeños almacenes y que actualmente dependen de controles manuales o en hojas de cálculo.
- Asumimos que nuestros usuarios para los planes superiores son jefes de seguridad o de operaciones a cargo de supervisar redes complejas de múltiples zonas logísticas.
- Creemos que ambos perfiles de usuario valoran profundamente las interfaces limpias, directas y accesibles desde cualquier lugar, buscando evitar el uso de configuraciones tecnológicas complejas.
- Consideramos que el principal problema de estos públicos radica en la molestia que genera rastrear mermas a través de plataformas fragmentadas, dificultando determinar con claridad qué pasó y en qué instante exacto.


**User Outcome and Benefit Assumptions (Supuestos de Resultados y Beneficios para el Usuario)**
- Creemos que los dueños de PYMES podrán tener mayor tranquilidad operativa al mantener el control de sus negocios y supervisar las aperturas de forma remota, sin necesidad de estar físicamente en el local.
- Asumimos que los jefes de operaciones podrán actuar rápidamente ante cualquier irregularidad gracias a las alertas automáticas que recibirán a través de un panel centralizado.
- Creemos que el personal de auditoría podrá reducir considerablemente las tareas manuales al utilizar las marcas de tiempo exactas de los eventos registrados para ubicar rápidamente las grabaciones de CCTV, evitando revisar horas de video sin una referencia clara .
- Asumimos que las empresas con múltiples sucursales lograrán estandarizar y centralizar la toma de decisiones al visualizar el estado de toda su infraestructura logística desde un único punto de acceso.


**Feature Assumptions (Supuestos de Funcionalidades)**
- Creemos que nuestra propuesta de valor residirá en un Dashboard Unificado que consolide el inventario disponible, el historial de movimientos, las alertas críticas y el estado de conexión de los sensores IoT en un solo lugar.
- Asumimos que el motor de detección de discrepancias, el cual comparará los eventos físicos del IoT con los movimientos de inventario registrados, será la herramienta funcional clave para descubrir sustracciones no reportadas.
- Creemos que establecer roles y permisos para cada tipo de usuario (Administrador, Almacenero, Auditor) permitirá proteger el acceso y la manipulación al stock controlando qué acciones puede realizar cada usuario según sus funciones.
- Asumimos que el desarrollo de una API RESTful estructurada para recibir los eventos (POST) emitidos por los microcontroladores permitirá procesar los registros de forma asíncrona, garantizando que el sistema sea capaz de registrar eventos críticos en tiempo real.

<br>

#### 1.2.2.3. Lean UX Hypothesis Statement

**Hypothesis Statement 1:**<br>
Creemos que lograremos incrementar la cantidad de empresas suscritas y mejorar la retención de nuestros clientes

Si los dueños de PYMES y jefes de seguridad

Obtienen el beneficio de centralizar la supervisión de todas sus sedes y mantener un control claro sin necesidad de estar físicamente presentes

Con un Dashboard Unificado que consolide el inventario disponible, el historial de movimientos, las alertas críticas y el estado de conexión de los sensores IoT en una sola pantalla.


**Hypothesis Statement 2:**<br>
Creemos que lograremos reducir drásticamente las pérdidas económicas causadas por robos internos y accesos no autorizados en los almacenes

Si los jefes de operaciones y dueños de negocios

Obtienen la capacidad de descubrir sustracciones no reportadas y reaccionar rápidamente ante cualquier incidente

Con un motor de detección de discrepancias que compare de forma automática los eventos físicos reportados por el IoT con los movimientos de inventario registrados en el sistema.


**Hypothesis Statement 3:**<br>
Creemos que lograremos brindar un servicio estable y confiable que asegure la retención de clientes del sector corporativo

Si los administradores, almaceneros y auditores

Logran interactuar con la plataforma de forma segura, garantizando que la manipulación del stock y la información estén protegidas de acuerdo a su jerarquía

Con la implementación de un modelo estricto de roles y permisos que delimite exactamente qué funciones y zonas puede consultar cada usuario.


**Hypothesis Statement 4:**<br>
Creemos que lograremos que las empresas modernicen su seguridad y pasen de un enfoque reactivo a uno puramente preventivo

Si el personal de seguridad y auditoría
Obtiene notificaciones críticas exactas y una marca de tiempo confiable para buscar evidencias precisas en sus cámaras CCTV

Con el desarrollo de una API RESTful estructurada (mediante peticiones POST) que reciba, asocie y procese en tiempo real los eventos físicos emitidos por los microcontroladores (ESP32).

<br>

#### 1.2.2.4. Lean UX Canvas



<table>
  <tbody>
    <tr>
      <td valign="top">
        <b>1. Business</b><br><br>
        Las mermas desconocidas y el "robo hormiga" generan pérdidas millonarias en el sector comercial peruano. Existe una desconexión operativa entre el registro digital en software y los eventos físicos reales en almacenes. Las PYMES perciben la tecnología IoT como compleja y costosa.
      </td>
      <td valign="top">
        <b>5. Solutions</b><br>
        <ul>
          <li>Plataforma Web SPA (Vue.js + ASP.NET Core) para gestión de inventario, movimientos y stock.</li>
          <li>Integración IoT pasiva (ESP32 con sensores magnéticos en puertas) para registrar aperturas físicas.</li>
          <li>Motor de detección automática de discrepancias entre aperturas físicas y registros.</li>
          <li>Registro histórico con timestamps para servir de índice en auditorías con CCTV.</li>
        </ul>
      </td>
      <td valign="top">
        <b>2. Business Outcomes</b><br>
        <ul>
          <li>Reducción del 30% en tiempo dedicado a investigar pérdidas en cámaras CCTV.</li>
          <li>Disminución de un 25% en incidencias por descuadres de stock no justificados.</li>
          <li>Adopción del modelo SaaS en PYMES mediante el plan Básico.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td valign="top">
        <b>3. Users</b><br>
        <ul>
          <li><b>Segmento 1:</b> Dueños de PYMES, Gerentes de Operaciones y Jefes de Seguridad.</li>
          <li><b>Segmento 2:</b> Encargados de Logística, Almaceneros y Personal Operativo.</li>
        </ul>
      </td>
      <td valign="top">
        <b>4. User Benefits</b><br>
        <ul>
          <li>Visibilidad operativa total en tiempo real de lo que ocurre en sus almacenes.</li>
          <li>Respaldo laboral para el personal operativo al registrar quién y cuándo se realizó cada movimiento.</li>
          <li>Solución escalable y de bajo costo sin inversiones pesadas en hardware.</li>
        </ul>
      </td>
      <td valign="top"></td>
    </tr>
    <tr>
      <td valign="top">
        <b>6. Hypothesis</b><br><br>
        Creemos que al cruzar eventos físicos (IoT) con movimientos digitales de inventario en tiempo real, lograremos reducir las mermas desconocidas en almacenes de PYMES, sabremos que tuvimos éxito cuando las alertas de discrepancia reduzcan el tiempo de auditoría en un 30%.
      </td>
      <td valign="top">
        <b>7. What’s the most important thing we need to learn first?</b><br><br>
        Validar si los dueños de almacenes valoran tener una marca de tiempo exacta (timestamp) para cruzar con sus cámaras CCTV en lugar de requerir una integración directa de video en el software.
      </td>
      <td valign="top">
        <b>8. What’s the least amount of work we need to do to learn the next most important thing?</b><br><br>
        Desarrollar un MVP funcional compuesto por un backend en ASP.NET Core, una SPA en Vue.js y un dispositivo ESP32 con sensor magnético de puerta para simular el flujo completo de detección de discrepancias.
      </td>
    </tr>
  </tbody>
</table>

<br>

## 1.3. Segmentos objetivo.
El modelo de negocio de SafeZone opera en el ámbito B2B (Business-to-Business) y busca reducir riesgos mientras digitaliza el control diario en almacenes e inventarios. Mediante nuestra plataforma NodeSecure, hemos identificado dos perfiles principales de clientes, cuyas necesidades cambian según el tamaño de su infraestructura y el nivel de control que requieren:

**Segmento 1: Dueños y Administradores de PYMES (Retail, Tiendas y Pequeños Almacenes)**<br>
Este segmento representa a los emprendedores, gerentes y dueños de pequeñas y medianas empresas. Constituyen el cliente ideal para los planes de entrada de la plataforma, ya que no suelen contar con el capital para mantener equipos de vigilancia física las 24 horas, pero tienen la necesidad crítica de proteger su inventario.

Aspectos demográficos:
- Edad: Entre 25 y 55 años.
- Ocupación: Dueños de negocio, gerentes generales o administradores comerciales.
- Nivel de digitalización: Medio-Alto en herramientas de uso cotidiano. Gestionan gran parte de la operación de su negocio desde dispositivos móviles y buscan interfaces intuitivas (dashboards limpios) que no requieran una curva de aprendizaje técnica.

<br>


Aspectos psicográficos y de comportamiento:
- Motivaciones: Obtener tranquilidad operativa y mantener el control de su patrimonio a distancia, evitando gastos asfixiantes en infraestructuras de seguridad tradicionales.
- Comportamiento y Dolores (Pain points): Viven con la preocupación constante de la merma por "robo hormiga". Su mayor frustración es depender de revisiones manuales y enterarse de los incidentes mucho tiempo después de que ocurrieron.
- Necesidades: Buscan herramientas digitales intuitivas y rápidas de poner en marcha, priorizando soluciones que envíen alertas inmediatas al móvil para reaccionar al instante ante cualquier anomalía o acceso no autorizado.

**Dato estadístico:** Las micro y pequeñas empresas representan el 99.2% del tejido empresarial peruano, siendo vitales para la economía nacional (Gobierno del Perú, 2024). Sin embargo, el 73% (de MYPES y de PYMES) carece de sistemas automatizados, lo que dificulta su transformación digital (Redacción EC, 2025). Esta carencia, agravada por una gestión de inventarios deficiente y el "robo hormiga", provoca pérdidas de hasta el 10% en sus ingresos, poniendo en riesgo su estabilidad financiera y subrayando la necesidad urgente de soluciones tecnológicas para un control eficaz (Loarte y Temple, 2024).

<br>

**Segmento 2: Jefes de Seguridad y Operaciones (Medianas y Grandes Corporaciones)**<br>
Este segmento agrupa a profesionales responsables de la integridad, seguridad industrial y eficiencia logística en grandes empresas (como centros de distribución, cadenas de retail y fábricas). Son el público objetivo de los planes corporativos,  pues operan bajo estrictas normativas y necesitan escalar el control a múltiples ubicaciones.
 
Aspectos demográficos:
- Edad: Entre 35 y 60 años.
- Ocupación: Jefes de Seguridad Industrial, Supervisores Logísticos, Supply Chain Managers o Jefes de Planta.
- Nivel de digitalización: Avanzado. Están habituados a la lectura de métricas de rendimiento, uso de sistemas de planificación (ERP) y software de gestión de almacenes (WMS).

<br>

Aspectos psicográficos y de comportamiento:
- Motivaciones: Buscan escalabilidad, reducción sistemática de riesgos operativos y lograr una visibilidad ininterrumpida de todas las sucursales a su cargo simultáneamente.
- Comportamiento y Dolores (Pain points): Sufren por la alta carga manual que implica cruzar información fragmentada (por ejemplo, buscar horas en grabaciones de cámaras para justificar una pérdida en el registro de Excel).
- Necesidades: Exigen trazabilidad absoluta (quién, qué, cuándo y dónde). Requieren configurar roles de usuario, permisos granulares por zonas de riesgo y contar con un sistema automatizado que funcione como un índice exacto para auditorías.<br>

**Dato estadístico:** La modernización logística es clave para la rentabilidad corporativa. Mientras un 30% de empresas aún opera con procesos convencionales y riesgos elevados (Aguilar y Chingay, 2025), la automatización mediante sensores IoT ha demostrado elevar la exactitud del inventario del 33% al 94% y la eficiencia operativa hasta en un 90% (Cespedes y Ponce, 2025). Esta integración minimiza pérdidas y optimiza la seguridad, reduciendo drásticamente los errores de supervisión.<br><br><br><br>



# Capítulo II: Requirements Elicitation & Analysis 
## 2.1. Competidores
### 2.1.1. Análisis competitivo
Para evaluar la posición estratégica de NodeSecure en el mercado de gestión de inventarios y trazabilidad con evidencia IoT, se seleccionaron tres competidores directos e indirectos clave:
Verkada: Plataforma empresarial de seguridad física basada en la nube que integra videovigilancia, sensores ambientales y control de accesos.
Quaker Software: Firma de desarrollo tecnológico especializada en la arquitectura e implementación personalizada de sistemas ERP, CRM y control de inventarios a medida para grandes industrias.
Samsara: Plataforma SaaS de operaciones conectadas con sensores IoT para el seguimiento de activos, logística y gestión operativa en almacenes.

<table>
  <thead>
    <tr>
      <th colspan="5" align="center"><h3>Competitive Analysis Landscape</h3></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="20%"><b>¿Por qué llevar a cabo este análisis?</b></td>
      <td colspan="4">Identificar fortalezas, debilidades, oportunidades y amenazas de nuestra startup frente a soluciones existentes, para definir la propuesta de valor y las estrategias competitivas que nos permitan diferenciarnos.</td>
    </tr>
    <tr>
      <td><b>En la cabecera colocar por cada competidor nombre y logo</b></td>
      <td align="center" width="20%">
        <b>Su Startup:</b><br><b>NodeSecure</b><br><br>
        <img src="./images/image1.png" width="70" alt="NodeSecure">
      </td>
      <td align="center" width="20%">
        <b>Competidor 1:</b><br><b>Verkada</b><br><br>
        <img src="./images/image2.png" width="70" alt="Verkada">
      </td>
      <td align="center" width="20%">
        <b>Competidor 2:</b><br><b>Quaker Software</b><br><br>
        <img src="./images/image3.png" width="70" alt="Quaker Software">
      </td>
      <td align="center" width="20%">
        <b>Competidor 3:</b><br><b>Samsara</b><br><br>
        <img src="./images/image4.png" width="70" alt="Samsara">
      </td>
    </tr>
    <!-- PERFIL OVERVIEW -->
    <tr>
      <td rowspan="2"><b>Perfil</b></td>
      <td colspan="4"><b>Overview</b></td>
    </tr>
    <tr>
      <td>Plataforma web de gestión de inventario que registra los movimientos digitales de productos y utiliza IoT como evidencia física para detectar discrepancias y facilitar auditorías.</td>
      <td>Sistema de seguridad física basado en hardware propietario conectado a la nube para videovigilancia y control de accesos corporativos.</td>
      <td>Firma de desarrollo a medida que implementa soluciones ERP, CRM y módulos de control de inventario según requerimientos del cliente.</td>
      <td>Plataforma SaaS de operaciones conectadas que utiliza sensores IoT en almacenes y flotas para visibilidad en tiempo real.</td>
    </tr>
    <!-- VENTAJA COMPETITIVA -->
    <tr>
      <td colspan="1"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
      <td>Correlación entre los movimientos de inventario digitales y eventos físicos (sensores) para servir como un índice de trazabilidad que facilita las auditorías sin requerir cámaras costosas integradas.</td>
      <td>Ecosistema de hardware moderno con analítica avanzada de video e Inteligencia Artificial centralizada en la nube.</td>
      <td>Alta capacidad de personalización e integración profunda con flujos de trabajo empresariales a gran escala.</td>
      <td>Plataforma IoT industrial consolidada con trazabilidad logística de activos y analítica avanzada.</td>
    </tr>
    <!-- PERFIL DE MARKETING -->
    <tr>
      <td rowspan="2"><b>Perfil de Marketing</b></td>
      <td colspan="4"><b>Mercado objetivo</b></td>
    </tr>
    <tr>
      <td>Dueños de PYMES, administradores y jefes de operaciones/seguridad en almacenes, depósitos y centros de distribución.</td>
      <td>Grandes corporaciones, sector educativo e industrias de gran escala con presupuesto elevado.</td>
      <td>Empresas de manufactura, firmas financieras y grandes corporaciones con procesos de software personalizados.</td>
      <td>Empresas medianas y grandes de logística, transporte, distribución y almacenamiento.</td>
    </tr>
    <tr>
      <td><b>Estrategias de marketing</b></td>
      <td>Marketing B2B digital, demostraciones operativas del flujo web/IoT y alianzas con consultoras logísticas y de retail.</td>
      <td>Venta directa mediante canal corporativo (Enterprise Sales), presencia en ferias globales y marketing técnico.</td>
      <td>Venta consultiva B2B, desarrollo de proyectos por contrato y redes de partners tecnológicos.</td>
      <td>Venta directa B2B, pruebas piloto gratuitas para almacenes/flotas y presencia en ferias del sector.</td>
    </tr>
    <!-- PERFIL DE PRODUCTO -->
    <tr>
      <td rowspan="2"><b>Perfil de Producto</b></td>
      <td colspan="4"><b>Productos & Servicios</b></td>
    </tr>
    <tr>
      <td>Aplicación Web (Vue.js + ASP.NET Core), registro de entradas/salidas, alertas de discrepancia, índice de auditoría temporal y conexión IoT (ESP32).</td>
      <td>Cámaras IP, controladores de acceso, sensores ambientales, intercomunicadores y consola Command.</td>
      <td>Desarrollo de ERP/CRM a medida, módulos de inventario, auditoría de operaciones y servicios de consultoría IT.</td>
      <td>Sensores IoT de entorno y puertas, rastreadores de activos, cámaras con IA y software de gestión operativa.</td>
    </tr>
    <tr>
      <td><b>Precios & Costos</b></td>
      <td>Esquema SaaS con Plan Básico (solo software), Plan Premium (inventario + IoT) y Plan Corporativo adaptado a PYMES.</td>
      <td>Elevado costo inicial en hardware propietario e licencias de software anuales por dispositivo.</td>
      <td>Elevados costos iniciales de desarrollo a medida y licencias corporativas según el alcance del proyecto.</td>
      <td>Suscripción SaaS por activo/dispositivo orientada a presupuestos corporativos medianos y altos.</td>
    </tr>
    <tr>
      <td><b>Canales de distribución (Web y/o Móvil)</b></td>
      <td>Aplicación Web Responsive (SPA) y Landing Page corporativa.</td>
      <td>Plataforma Cloud propietaria, distribuidores autorizados e integradores de sistemas.</td>
      <td>Venta directa mediante consultoría tecnológica y despliegues web/cloud corporativos.</td>
      <td>Venta directa a través de su plataforma SaaS y red global de socios tecnológicos.</td>
    </tr>
    <!-- ANÁLISIS SWOT / FODA -->
    <tr>
      <td colspan="5" align="center"><b>Análisis SWOT / FODA</b><br><i>Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</i></td>
    </tr>
    <tr>
      <td><b>Fortalezas</b></td>
      <td>Correlación en tiempo real entre eventos físicos del sensor magnético/IoT y el software de inventario.</td>
      <td>Menor costo de implementación comparado con infraestructuras pesadas de videovigilancia corporativa.</td>
      <td>Plataforma web nativa, ligera y de fácil adopción para personal operativo.</td>
      <td>Solución tecnológica consolidada en el mercado.</td>
    </tr>
    <tr>
      <td><b>Debilidades</b></td>
      <td>Marca en etapa inicial sin posicionamiento previo en el mercado local.</td>
      <td>Dependencia de la conectividad de red local para el reporte en tiempo real de los nodos IoT.</td>
      <td>Largo tiempo de desarrollo y costo elevado.</td>
      <td>Curva de aprendizaje inicial requerida para configuración.</td>
    </tr>
    <tr>
      <td><b>Oportunidades</b></td>
      <td>Elevada pérdida económica en Perú por "merma desconocida" (S/ 700 a S/ 1,000 millones anuales).</td>
      <td>Baja penetración de sistemas de auditoría automatizada en PYMES logísticas locales debido a los altos costos de la competencia.</td>
      <td>Adopción creciente de transformación digital en empresas medianas.</td>
      <td>Crecimiento del mercado de logística e IoT en la región.</td>
    </tr>
    <tr>
      <td><b>Amenazas</b></td>
      <td>Entrada de competidores de seguridad tradicional incorporando sensores de bajo costo.</td>
      <td>Resistencia al cambio tecnológico por parte del personal de almacén acostumbrado a procesos manuales.</td>
      <td>Llegada de soluciones estándar a menor precio.</td>
      <td>Competencia agresiva de precios por parte de proveedores globales consolidados.</td>
    </tr>
  </tbody>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

Estrategia de diferenciación mediante trazabilidad físico-digital:
Posicionar a NodeSecure como una solución que integra la gestión de inventario con la evidencia generada por dispositivos IoT. A diferencia de las plataformas enfocadas únicamente en videovigilancia, control de accesos o gestión logística, NodeSecure busca relacionar los movimientos registrados digitalmente con los eventos físicos detectados en el almacén.
Táctica: comunicar esta propuesta mediante demostraciones del flujo completo, mostrando cómo una apertura física puede contrastarse con los movimientos registrados y generar una alerta cuando exista una discrepancia.
Estrategia de adopción progresiva para PYMES:
Reducir la barrera de entrada tecnológica y económica mediante un modelo SaaS escalable. El cliente puede comenzar utilizando las funcionalidades de gestión de inventario y posteriormente incorporar sensores IoT según sus necesidades y presupuesto.
Táctica: ofrecer planes diferenciados Básico, Premium y Corporativo que permitan incrementar progresivamente el nivel de monitoreo sin requerir una implementación completa desde el inicio. 

Estrategia de facilidad de uso para reducir la resistencia al cambio:
Considerando que una de las amenazas identificadas es la resistencia del personal de almacén acostumbrado a procesos manuales, NodeSecure debe priorizar una experiencia de uso sencilla y rápida.
Táctica: diseñar una interfaz web con procesos de registro de entradas y salidas que requieran pocos pasos, además de mantener la detección de eventos IoT funcionando en segundo plano para no interrumpir las actividades operativas. 
Estrategia de confianza basada en evidencia y trazabilidad:
Construir la propuesta de valor alrededor de la generación de evidencia verificable sobre las operaciones realizadas. La plataforma debe permitir identificar quién realizó una operación, qué movimiento efectuó y cuándo ocurrió, complementando esta información con los eventos físicos registrados por los sensores.
Táctica: utilizar dashboards, alertas, historial de eventos y marcas de tiempo para facilitar la supervisión y las posteriores auditorías. 

## 2.2.1. Diseño de entrevistas
Para comprender a fondo los dolores y validar las necesidades de nuestro público y  levantar los requerimientos del sistema SafeZone (NodeSecure), se diseñaron dos guiones de entrevistas semiestructuradas enfocados en nuestros dos segmentos de usuario objetivo.

Entrevista - Segmento 1: Dueños de PYMES y Jefes de Operaciones / Almacén 

¿Cuáles son los principales problemas o pérdidas que ha detectado en el control diario de su almacén o negocio?
¿Ha tenido problemas con robos, pérdidas o faltantes de mercadería? ¿Qué suele ocurrir cuando se presenta alguno de estos casos?
¿Cómo realizan actualmente el registro y control de las entradas, salidas y del stock disponible de mercadería?
¿Con qué mecanismos cuentan actualmente para supervisar quién entra o sale de las zonas de almacenamiento?
Por ejemplo, cámaras y registros
¿Con qué frecuencia encuentran diferencias entre el stock que tienen registrado y la mercadería que realmente tienen físicamente?
Cuando detectan un faltante, ¿qué tan difícil les resulta determinar qué ocurrió y quiénes estuvieron presentes en ese momento?
¿Qué tan útil sería para usted recibir una alerta en su celular cuando ocurra algo fuera de lo normal, como una apertura de puerta fuera de horario o una posible discrepancia de inventario?
Si pudiera consultar la fecha y hora exacta en que ocurrió un incidente, ¿consideraría útil esa información para revisar directamente ese momento en sus cámaras o registros? ¿Por qué?
Pensando en una herramienta que ayude a controlar el inventario y detectar este tipo de situaciones, ¿qué características considera más importantes para que realmente le resulte útil en su negocio?
¿Estaría dispuesto a utilizar una solución de este tipo en su negocio? ¿Qué factores tendría en cuenta para decidir adoptarla?


Entrevista - Segmento 2: Encargados de Logística y Personal Operativo 

¿Cómo es normalmente el proceso cuando realizas una entrada o salida de productos en el almacén?
¿Qué herramientas utilizas habitualmente para registrar los movimientos de productos?
 Por ejemplo: computadora, celular, tablet, Excel u otro sistema.
¿Cuánto tiempo aproximadamente te toma registrar una entrada o salida de productos?
¿Qué dificultades encuentras actualmente al registrar y controlar el inventario?
¿Qué ocurre cuando necesitas registrar una salida rápidamente y el sistema resulta lento o complicado de utilizar?
¿Con qué frecuencia se presentan descuadres entre el stock registrado y la cantidad de productos que realmente tienen?
Cuando ocurre un descuadre de stock, ¿qué tan fácil o difícil es identificar quién realizó el movimiento y cuándo ocurrió?
¿Qué características consideras indispensables en una aplicación para registrar los movimientos de productos de forma rápida y sencilla?
¿Qué tan útil sería para ti que la plataforma genere automáticamente un registro de la fecha y hora del evento?
¿Crees que contar con este tipo de registros te ayudaría a identificar mejor qué ocurrió cuando se presenta un descuadre de inventario?
¿Te gustaría controlar toda la información importante de manera remota?

<h3>Segmento 01: Dueños y Administradores de Almacén</h3>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>Sandoval Aiquipa, Kelber Yamir</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Jose Miguel</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>28 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>Ate, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
    <tr>
    <td><strong>Inicio</strong></td>
    <td> </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Administra un almacén de suministros eléctricos. Menciona que las mermas no explicadas al mes representan una pérdida de hasta el 8% al trimestre. Registra inventarios en Excel e inspeccionan con cámaras analógicas fijas. Expresa que revisar horas de video para hallar un faltante es ineficiente. Considera de enorme utilidad recibir alertas en el celular ante eventos anómalos y contar con la fecha y hora (<em>timestamp</em>) exacta para auditar las grabaciones directamente.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>Sandoval Aiquipa, Kelber Yamir</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Diego Campoblanco</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>25 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Juan de Miraflores, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
  <tr>
    <td><strong>Inicio</strong></td>
    <td> </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Dueña de una distribuidora de abarrotes al por mayor. Presenta problemas con el "robo hormiga" y desbalances de productos no anotados a tiempo. Actualmente utiliza un cuaderno físico y control visual. Destaca que recibir alertas remotas en el celular le daría un control absoluto para supervisar su negocio a distancia y cruzar la hora de apertura de puertas con las ventas realizadas.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>[Nombre del Entrevistador]</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Patricia Sofía Ramos Vílchez</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>45 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Juan de Miraflores, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
  <tr>
    <td><strong>Inicio</strong></td>
    <td> </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Dueña de una distribuidora de abarrotes al por mayor. Presenta problemas con el "robo hormiga" y desbalances de productos no anotados a tiempo. Actualmente utiliza un cuaderno físico y control visual. Destaca que recibir alertas remotas en el celular le daría un control absoluto para supervisar su negocio a distancia y cruzar la hora de apertura de puertas con las ventas realizadas.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>[Nombre del Entrevistador]</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Roberto Alonzo Gutiérrez Farfán</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>48 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>San Luis, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
    <tr>
    <td><strong>Inicio</strong></td>
    <td> </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Jefe de Operaciones de 3 sedes ferreteras. Sufre por el desfase de información entre tiendas y el tiempo invertido en auditorías por faltantes de herramientas. Ve indispensable un Dashboard centralizado para monitorear las sedes de manera simultánea, junto con la gestión de permisos por roles de usuario e historial de registros inalterables para agilizar las investigaciones.</td>
  </tr>
</table>

<br>

<!-- ========================================== -->
<!-- REGISTRO DE ENTREVISTAS - SEGMENTO 02      -->
<!-- ========================================== -->
<h3>Segmento 02: Personal Operativo y Almaceneros</h3>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>Luciana Angielina Ravello Cárdenas</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Jorge Luis Huamán Quispe</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>27 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>Santiago de Surco, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
    <tr>
    <td><strong>Inicio</strong></td>
    <td> 30 s </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Encargado de recepción e inventario. Registra movimientos combinando libretas de papel con una computadora fija, lo que le toma entre 15 y 20 minutos por lote. Solicita una aplicación móvil rápida que se pueda usar desde celular o tablet con botones grandes. Valora el registro automático de fecha y hora para respaldar formalmente la recepción de carga en su turno.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>Liz Maribel Anahua Ancachi</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Valeria Isabel Morales Castro</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>23 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>Villa El Salvador, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
  </tr>
    <tr>
    <td><strong>Inicio</strong></td>
    <td> 4:30 </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Auxiliar de almacén. Llenan formatos impresos en papel que demoran horas en procesarse administrativamente, generando confusión sobre el stock real. Considera que un sistema web amigable asociado a registros personales automáticos protegerá a los trabajadores honestos, aclarando la hora exacta en que ocurrió cualquier inconsistencia.</td>
  </tr>
</table>

<br>

<table>
  <tr>
    <td width="20%"><strong>Entrevistador</strong></td>
    <td>Luciana Angielina Ravello Cárdenas</td>
  </tr>
  <tr>
    <td><strong>Entrevistado</strong></td>
    <td>Carla Paredes Benítez</td>
  </tr>
  <tr>
    <td><strong>Edad</strong></td>
    <td>26 años</td>
  </tr>
  <tr>
    <td><strong>Distrito</strong></td>
    <td>Ate, Lima</td>
  </tr>
  <tr>
    <td><strong>Evidencia</strong></td>
    <td><a href="https://canva.link/9w4klnpwqeadxqt" target="_blank">Ver Evidencia</a></td>
  </tr>
  <tr>
    <td><strong>Inicio</strong></td>
    <td> 7:40 </td>
  </tr>
  <tr>
    <td><strong>Resumen</strong></td>
    <td>Encargada de operaciones de despacho. Experimenta cuellos de botella al usar una única computadora compartida con hojas de Excel. Requiere una aplicación ágil que le permita registrar salidas en menos de 30 segundos de forma remota. Resalta que los registros automáticos con marcas de tiempo (timestamps) garantizarían total transparencia en el historial de movimientos de inventario.</td>
  </tr>
</table>

<br>

### 2.2.3. Análisis de entrevistas
Segmento 01 (Administrativo / Toma de decisiones):
La principal molestia de la gerencia es la pérdida de tiempo al investigar faltantes. La integración del sensor IoT con la plataforma web soluciona este problema al generar marcas de tiempo (timestamps) exactas que dirigen la revisión del video CCTV al minuto preciso del evento. 

Segmento 02 (Operativo / Campo):  
El personal de campo rechaza los sistemas complejos que entorpecen el despacho. Valoran la automatización de la fecha y hora porque agiliza el flujo de trabajo y sirve como prueba objetiva para deslindar responsabilidades en descuadres de stock. 

Variables de análisis identificadas:

<h3>Análisis Comparativo entre Segmentos</h3>

<table>
  <thead>
    <tr>
      <th>Variable</th>
      <th>Segmento 1 (Dueños / Administradores)</th>
      <th>Segmento 2 (Operativo / Almaceneros)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Problemas y pérdidas recurrentes</strong></td>
      <td>Mermas no explicadas (hasta un 8% trimestral) y "robo hormiga" de productos de alto valor. Dificultad para supervisar múltiples sedes sin desfase de información.</td>
      <td>Descuadres semanales de inventario por olvido de registro manual en horas pico. Archivos de Excel bloqueados por uso concurrente y hojas de papel que se pierden.</td>
    </tr>
    <tr>
      <td><strong>Herramientas e infraestructura actual</strong></td>
      <td>Uso de hojas de cálculo en Excel o cuadernos físicos en recepción. Cámaras CCTV analógicas/IP que graban continuamente sin sensores asociados.</td>
      <td>Libretas de apunte, vales impresos en papel y uso de una única computadora de escritorio compartida.</td>
    </tr>
    <tr>
      <td><strong>Monitoreo y control de accesos</strong></td>
      <td>Control visual directo del encargado o cerraduras tradicionales. Las cámaras no permiten identificar el momento exacto de un incidente sin revisar horas de video.</td>
      <td>Responsabilidad diluida entre todo el personal del turno al no haber un control individualizado de quién ingresa al almacén o modifica el stock.</td>
    </tr>
    <tr>
      <td><strong>Impacto de las alertas y trazabilidad (timestamps)</strong></td>
      <td>Consideran crucial recibir alertas en el celular ante cierres/aperturas fuera de horario. Usar el timestamp exacto permite auditar las cámaras directamente en minutos.</td>
      <td>Exigen que el sistema registre la fecha, hora y usuario automáticamente como respaldo laboral de transparencia ante la gerencia por faltantes injustificados.</td>
    </tr>
    <tr>
      <td><strong>Requerimientos de la plataforma web/IoT</strong></td>
      <td>Dashboard centralizado para ver el estado del inventario y seguridad en tiempo real. Gestión estricta de permisos por roles de usuario y bajo costo de implementación.</td>
      <td>Aplicación web móvil/responsive para tablets y celular con interfaz sencilla, botones grandes y registros que tomen menos de 30 segundos.</td>
    </tr>
  </tbody>
</table>

<br>

## 2.3. Needfinding
A partir del análisis se identificaron necesidades recurrentes en ambos segmentos. Estas necesidades permiten orientar los siguientes artefactos de diseño.

Necesidades identificadas
Registrar las entradas y salidas de productos de manera rápida.
Mantener actualizado el stock disponible.
Identificar quién realizó cada movimiento.
Registrar automáticamente la fecha y hora de las operaciones.
Detectar diferencias entre movimientos digitales y eventos físicos.
Recibir alertas ante situaciones anómalas.
Consultar un historial de eventos.
Reducir el tiempo necesario para investigar incidentes.
Facilitar la consulta remota de información.
Mantener una interfaz sencilla para el personal operativo.


### 2.3.1. User Personas
Segmento 01: 
![User Persona Segmento 01](./images/2.3.1.1.png)

Segmento 02: 
![User Persona Segmento 02](./images/2.3.1.2.png)

#### 2.3.2. User Task Matrix
<h3>Priorización de Tareas por Segmento</h3>

<table>
  <thead>
    <tr>
      <th>Tareas</th>
      <th>(Segmento 1) Francisco Robles</th>
      <th>(Segmento 2) Carla Paredes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Inicio de Sesión y Autenticación</strong></td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><strong>Gestión de Permisos y Roles</strong></td>
      <td>Alta</td>
      <td>Baja</td>
    </tr>
    <tr>
      <td><strong>Registro de Entradas y Salidas</strong></td>
      <td>Baja</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><strong>Generación Automática de Timestamps</strong></td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td><strong>Monitoreo IoT y Sensores de Puertas</strong></td>
      <td>Alta</td>
      <td>Media</td>
    </tr>
    <tr>
      <td><strong>Alertas e Incidencias en Tiempo Real</strong></td>
      <td>Alta</td>
      <td>Baja</td>
    </tr>
    <tr>
      <td><strong>Dashboard Centralizado y Reportes</strong></td>
      <td>Alta</td>
      <td>Baja</td>
    </tr>
    <tr>
      <td><strong>Consulta Rápida de Inventario</strong></td>
      <td>Baja</td>
      <td>Baja</td>
    </tr>
  </tbody>
</table>

##### 2.3.3. User Journey Mapping

Segmento 01: 
![User Journey Map Segmento 01](./images/2.3.3.1.png)

Segmento 02:
![User Journey Map Segmento 02](./images/2.3.3.2.png)


###### 2.3.4. Empathy Mapping

Segmento 01:
![Empathy Map Segmento 01](./images/2.3.4.1.png)

Segmento 02: 
![Empathy Map Segmento 01](./images/2.3.4.2.png)

## 2.4. Big Picture Event Storming

![Big Picture Event Storming](./images/2.4.png)

## 2.5. Ubiquitous Language

![Ubiquitous Language](./images/2.5.png)


## 4.4. Web Applications UX/UI Design.

El diseño de la experiencia de usuario (UX) y de la interfaz (UI) de la plataforma NodeSecure se ha centrado en la operatividad bajo presión. Entendemos que un jefe de seguridad o un dueño de negocio entra a la aplicación web buscando respuestas rápidas: "¿Coincide mi inventario digital con la mercadería física?", "¿Hubo alguna salida de stock no registrada?". Por ello, la UX prioriza la conciliación del inventario en tiempo real, la gestión de entradas/salidas y la visualización de discrepancias detectadas por los sensores IoT. La UI, basada en Material Design, utiliza una estética limpia y profesional que reduce la carga cognitiva, permitiendo que el usuario identifique anomalías de stock o accesos mediante el uso estratégico de colores semánticos (rojo para discrepancias, verde para stock conciliado).

### 4.4.1. Web Applications Wireframes.

En esta sección se presentan los wireframes diseñados para las versiones desktop y mobile de la plataforma. Estos modelos estructurales establecen la arquitectura de la información, la jerarquía visual y los flujos de interacción principales sin la distracción de elementos gráficos complejos. Los wireframes detallan la experiencia del usuario administrador a través de los módulos críticos del sistema, como lo es el dashboard de discrepancias, la gestión de inventario (entradas y salidas), el historial de trazabilidad y el ecosistema de facturación. El objetivo de esta etapa es validar la usabilidad y la eficiencia de las tareas operativas antes de transicionar al diseño de alta fidelidad.

#### 1. User Goal: Acceso al sistema

Permitir a los dueños de PYMES y administradores registrar su empresa, ingresar a la plataforma NodeSecure de forma segura y recuperar sus credenciales en caso de olvido.

En el diseño del flujo de acceso, la arquitectura de información sigue un modelo de navegación lineal que guía al usuario paso a paso, evitando distracciones innecesarias. Se emplean campos de texto amplios y una tipografía sans-serif de alto contraste, lo que mejora la legibilidad y refuerza principios como la alineación y la simplicidad visual.

**Pantallas de flujo:**
* Formulario inicial donde el usuario registra sus datos personales, los de su empresa y crea una contraseña para iniciar su prueba gratuita.
* Pantalla de login estándar para usuarios que ya tienen una cuenta.
* Interfaz sencilla donde el usuario ingresa su correo electrónico para recibir un enlace de restablecimiento de acceso.

**Desktop**
![Desktop Wireframes - User Goal 1](images/ug1-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 1](images/ug1-wireframe-mobile.png)

#### 2. User Goal: Registro y Monitoreo de Almacenes e Inventario

Proveer un panel de control para visualizar el estado de conciliación de stock de todas las sucursales en tiempo real y permitir la configuración de nuevos locales operativos.

Para el panel principal de almacenes, la arquitectura de información sigue un modelo jerárquico basado en cards, lo que permite visualizar y entender rápidamente el volumen de operaciones de múltiples sucursales. Se aplica el principio de contraste para resaltar claramente los estados de "Discrepancia Detectada" frente a los estados de "Stock Conciliado", facilitando una lectura rápida y priorizada de la información de auditoría en lugar de un simple monitoreo físico.

Otro aspecto de la información crítica no depende únicamente del color, ya que se complementa con etiquetas en texto que indican el tipo de evento físico no registrado o el desfase de inventario. Los botones de acción también cuentan con áreas táctiles amplias, lo que mejora la accesibilidad para usuarios con dificultades motrices.

**Pantallas de flujo:**
* Lista principal que muestra el estado en tiempo real de conciliación de inventario de cada sucursal registrada.
* Formulario para registrar una nueva sucursal y establecer sus parámetros de auditoría y horarios de operación de turnos.
* Estado del formulario que resalta visualmente en rojo los campos obligatorios faltantes o con formato incorrecto.
* Ventana emergente que confirma que el nuevo almacén ha sido guardado y está listo para vincularse al registro de movimientos de stock.

**Desktop**
![Desktop Wireframes - User Goal 2](images/ug2-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 2](images/ug2-wireframe-mobile.png)

#### 3. User Goal: Administración de dispositivos IoT

Facilitar la vinculación de nuevos sensores IoT a zonas específicas del almacén para la recolección de evidencia física, visualizar su estado de conexión y controlar los límites de uso según la suscripción.

La vinculación y gestión de dispositivos se diseña con el objetivo de reducir la carga cognitiva, agrupando el hardware por categorías (ej. Sensores Magnéticos, Lectores RFID) para facilitar su identificación y acceso. Se aplica el principio de proximidad de Gestalt para organizar de forma clara la información de cada dispositivo junto a su estado de conexión, mientras que el uso de modales superpuestos permite realizar acciones sin perder el contexto de la pantalla principal. Desde un enfoque inclusivo, los formularios y acciones críticas, como la desvinculación de un sensor, presentan alto contraste y botones con descripciones claras y directas (“Sí, desvincular” y “Cancelar”), evitando ambigüedades y mejorando la comprensión para todo tipo de usuarios.

**Pantallas de flujo:**
* Inventario visual del hardware conectado que reporta evidencia física, indicando si están Online/Offline y mostrando el uso actual de la cuota del plan.
* Formulario para ingresar el número de serie de un equipo nuevo y asignarlo a una zona específica del almacén para cruzar su data con los movimientos digitales.
* Ventana emergente de éxito que confirma la correcta sincronización del nuevo sensor con el sistema.
* Ventana emergente de advertencia que bloquea la vinculación cuando el usuario ha alcanzado el límite de hardware permitido por su plan.

**Desktop**
![Desktop Wireframes - User Goal 3](images/ug3-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 3](images/ug3-wireframe-mobile.png)

#### 4. User Goal: Auditoría de Eventos y Discrepancias

Permitir al usuario revisar la bitácora de trazabilidad del inventario, buscar movimientos o discrepancias mediante filtros y acceder al detalle de las alertas físicas no registradas.

Dado que el historial maneja grandes volúmenes de datos operativos, su arquitectura de información se organiza de forma secuencial y con opciones de filtrado claras para facilitar la búsqueda. Se aplica una jerarquía visual donde la hora y la gravedad de la discrepancia destacan en el primer nivel de lectura, permitiendo identificar rápidamente eventos donde el stock digital no coincide con la evidencia física del IoT.

**Pantallas de flujo:**
* Lista cronológica detallada de todas las actividades del almacén, diferenciando movimientos de stock validados de alertas por discrepancia física.
* Menús desplegables que permiten filtrar el historial por "Tipo de evento" (Entrada, Salida, Discrepancia) o "Rango de fechas".
* Ventana emergente y vista de detalle que muestra el resumen inmediato de una discrepancia sin perder el contexto de la auditoría.

**Desktop**
![Desktop Wireframes - User Goal 4](images/ug4-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 4](images/ug4-wireframe-mobile.png)

#### 5. User Goal: Gestión de personal y accesos

Controlar de forma segura qué empleados tienen acceso a la plataforma, invitar nuevos miembros y delimitar qué zonas de inventario pueden auditar o gestionar.

Este módulo utiliza una arquitectura de información facetada que separa claramente los roles de administrador y personal operativo (almaceneros/auditores), reduciendo el riesgo de errores en la asignación de permisos. Se aplica el principio de repetición en las tarjetas de usuario para mantener un orden visual consistente y fácil de seguir, mientras que elementos como los badges de roles emplean variaciones tonales sutiles para diferenciarlos sin sobrecargar la interfaz. Desde un enfoque inclusivo, la edición de permisos se apoya en interruptores visuales grandes acompañados de texto claro y confirmatorio, además de un diseño tolerante a errores que evita cambios accidentales, especialmente en usuarios con dificultades motoras.

**Pantallas de flujo:**
* Panel central que lista al equipo de trabajo, separando claramente a los Administradores del personal operativo asignado a los almacenes.
* Formulario para enviar una invitación por correo asignando un rol de sistema específico (Administrador, Almacenero o Auditor) a un nuevo miembro.
* Panel de configuración con opciones para habilitar o deshabilitar el acceso de un empleado a zonas de inventario específicas.
* Ventana emergente de advertencia destructiva para revocar definitivamente el acceso de un empleado a la plataforma.

**Desktop**
![Desktop Wireframes - User Goal 5](images/ug5-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 5](images/ug5-wireframe-mobile.png)

#### 6. User Goal: Administración de suscripción y facturación

Permitir a la empresa escalar sus operaciones mejorando su plan, personalizar límites a medida o gestionar la cancelación del servicio para adecuar la plataforma a su volumen de inventario.

El flujo de facturación guía al usuario desde la comparación de planes hasta el pago mediante una arquitectura de información progresiva. Además, se incorporan elementos interactivos como sliders y resúmenes de pago claros que facilitan la comprensión del proceso. Desde el enfoque inclusivo, se prioriza la legibilidad financiera mediante tipografías grandes para los montos y textos simples, evitando jerga técnica. Esto permite que usuarios con distintos niveles de conocimiento o limitaciones visuales comprendan fácilmente la información y tomen decisiones con mayor confianza al escalar su capacidad de auditoría.

**Pantallas de flujo:**
* Panel de resumen con el plan actual, fecha de próximo cobro y barras de progreso que muestran los límites consumidos de almacenes y nodos IoT.
* Pantalla comparativa de beneficios y precios entre los diferentes planes ofrecidos para la gestión de inventario.
* Interfaz de cotizador interactivo con controles deslizables para elegir la cantidad exacta de almacenes y sensores de evidencia necesarios.
* Pantalla de checkout que detalla el costo total, prorrateos y permite confirmar el método de pago con tarjeta.
* Ventana emergente de retención que advierte al usuario sobre las funcionalidades clave de trazabilidad que perderá si decide cancelar.
* Ventana emergente de confirmación de transacción aprobada y notificación de actualización de los límites del plan.
* Vista del dashboard en estado "sin plan" cuando la cuenta no posee una suscripción activa, bloqueando nuevas auditorías.

**Desktop**
![Desktop Wireframes - User Goal 6](images/ug6-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 6](images/ug6-wireframe-mobile.png)

#### 7. User Goal: Configuración de cuenta y notificaciones

Dar control al usuario sobre sus credenciales de acceso y los canales por los cuales desea recibir alertas sobre discrepancias de inventario.

La sección de configuración organiza las preferencias operativas mediante una arquitectura categórica, aplicando el principio de agrupamiento para mantener juntas las opciones relacionadas y facilitar su comprensión. Se utilizan controles estándar y líneas divisorias sutiles que ordenan la interfaz sin recargarla, manteniendo una experiencia limpia y clara.

**Pantallas de flujo:**
* Menú de ajustes con interruptores para activar o desactivar notificaciones Push, Email y SMS enfocadas en reportes de auditoría y descuadres físicos.
* Ventana emergente que advierte al usuario sobre el riesgo operativo (pérdida de trazabilidad en tiempo real) si intenta silenciar por completo las notificaciones del sistema.
* Ventana emergente de confirmación que avisa sobre la pausa de recepción de alertas Push de inventario en el dispositivo actual al salir de la cuenta.

**Desktop**
![Desktop Wireframes - User Goal 7](images/ug7-wireframe-desktop.png)

**Mobile**
![Mobile Wireframes - User Goal 7](images/ug7-wireframe-mobile.png)

### 4.4.2. Web Applications Wireflow Diagrams

El Wireflow es un artefacto que combina la estructura de los wireframes con la lógica de un diagrama de flujo. Su importancia radica en que permite visualizar no solo qué elementos hay en cada pantalla, sino cómo el usuario se desplaza entre ellas para completar un proceso. Para **NodeSecure**, esto es vital porque el sistema debe ser capaz de guiar al usuario de forma intuitiva desde la detección de una discrepancia de stock hasta la conciliación del inventario en el menor número de pasos posible. En esta sección se detalla la arquitectura de navegación, mostrando los caminos que conectan el panel de control con los módulos de configuración de sensores IoT y revisión de historiales de auditoría.

#### 1. User Goal: Acceso al sistema

El flujo visual comienza con un nodo de inicio que lleva a la pantalla de presentación. Luego se presenta un rombo de decisión que evalúa si el usuario posee credenciales. De esa decisión se desprenden dos ramas: una que va hacia el registro de una nueva empresa y otra hacia el inicio de sesión tradicional. Ambas terminan en la validación y finalizan con el acceso al dashboard.

**El happy path:**
* **Inicio de la aplicación:** El administrador abre la plataforma web o móvil.
* **Pantalla principal:** Se muestra directamente la vista de inicio de sesión.
* **Decisión:** "¿El usuario tiene una cuenta?". En el *happy path* suponemos que el usuario ya es un cliente registrado.
* **Ingreso de datos:** El usuario completa los campos de correo electrónico y contraseña en el formulario.
* **Autenticación:** El usuario hace clic en el botón "Ingresar" y el sistema valida las credenciales correctamente en la base de datos.
* **Fin del flujo de acceso:** El usuario entra de manera exitosa a la aplicación y aterriza directamente en el dashboard de "Mis Almacenes" para comenzar a auditar su inventario.

**Diagrama Lógico:**
![Logical Flow - User Goal 1](images/ug1-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 1](images/ug1-wireflow-visual.png)

#### 2. User Goal: Registro y monitoreo de almacenes

Este flujo ilustra cómo un administrador registra un nuevo nodo logístico o sucursal desde el panel principal. El usuario completa un formulario con datos y horarios operativos; en caso de que la información sea incorrecta o falten campos obligatorios, el sistema bloquea el avance y muestra alertas preventivas en rojo. Al validar correctamente los datos, se confirma el registro mediante una ventana emergente de éxito y se redirige al usuario de vuelta al dashboard, donde el nuevo almacén ya aparece activo y listo para la conciliación de inventario.

**El happy path:**
* **Inicio:** El usuario se encuentra en el dashboard principal de "Mis Almacenes".
* **Acción:** Hace clic en el botón "+ Registrar nuevo almacén".
* **Ingreso de datos:** Llena el formulario de información general y horarios sin cometer errores.
* **Guardar:** Hace clic en el botón "Guardar Almacén".
* **Validación interna:** El sistema verifica que la dirección es válida y los campos obligatorios están completos.
* **Confirmación:** Aparece la ventana emergente con el mensaje "Almacén Guardado".
* **Fin del flujo:** El usuario regresa automáticamente al dashboard y visualiza la nueva sucursal en la lista, lista para auditar.

**Diagrama Lógico:**
![Logical Flow - User Goal 2](images/ug2-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 2](images/ug2-wireflow-visual.png)

#### 3. User Goal: Administración de dispositivos IoT

Este flujo describe el proceso de gestión de hardware IoT de auditoría en el sistema. Desde el panel principal de dispositivos, el usuario puede intentar agregar un sensor o nodo nuevo. El sistema realiza una validación preventiva de la cuota del plan; si se alcanzó el límite, bloquea la acción con una ventana informativa. Si existe cupo disponible, el usuario accede al formulario donde ingresa el número de serie y la zona para registrar y sincronizar el equipo logístico. De igual manera, el módulo permite desvincular hardware obsoleto, acción protegida por una ventana de advertencia para evitar eliminaciones accidentales de evidencia física.

**El happy path:**
* **Inicio:** El usuario se encuentra en la vista principal de "Dispositivos IoT".
* **Acción de registro:** Hace clic en el botón oscuro "+ Vincular nuevo dispositivo".
* **Validación interna:** El sistema verifica que el usuario tiene cupo disponible en su plan SaaS.
* **Ingreso de datos:** El sistema despliega el formulario y el usuario ingresa el Número de Serie, Nombre y asigna una Zona del almacén.
* **Guardar:** Hace clic en el botón "Vincular Dispositivo".
* **Fin del flujo:** El sistema sincroniza el equipo y devuelve al usuario al dashboard, donde el nuevo sensor ya figura en la lista con el estado "Online".

**Diagrama Lógico:**
![Logical Flow - User Goal 3](images/ug3-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 3](images/ug3-wireflow-visual.png)

#### 4. User Goal: Auditoría de Eventos y Discrepancias

Este flujo ilustra cómo un administrador audita la trazabilidad del inventario mediante la bitácora del sistema. Desde la vista principal, el usuario puede utilizar filtros inferiores para acotar la lista cronológica por tipo de movimiento (ej. discrepancias físicas) o rango de fechas, facilitando la búsqueda de mermas. Al localizar una anomalía de stock específica, el usuario puede seleccionarla para desplegar una ventana emergente que brinda evidencia detallada del sensor IoT sin perder su contexto en la lista de auditoría principal.

**El happy path:**
* **Inicio:** El usuario ingresa a la vista de "Auditoría y Trazabilidad".
* **Interacción:** El usuario hace clic en el botón superior "Tipo de evento".
* **Filtrado:** Se despliega el menú inferior correspondiente; el usuario selecciona "Discrepancias Físicas" y presiona "Aplicar Filtros".
* **Actualización:** El menú se cierra y la lista principal se actualiza mostrando solo las salidas de stock no registradas.
* **Selección:** El usuario hace clic sobre una tarjeta específica de la lista.
* **Fin del flujo:** El sistema despliega la ventana central (modal) mostrando el resumen de la discrepancia, la causa y el botón para justificar el descuadre.

**Diagrama Lógico:**
![Logical Flow - User Goal 4](images/ug4-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 4](images/ug4-wireflow-visual.png)git checkout -b feature/ux-wireflow-ug5-update

#### 5. User Goal: Gestión de personal y accesos

Este flujo ilustra el proceso de administración de usuarios operativos en la plataforma. Desde el panel "Equipo y Accesos", el administrador puede añadir nuevos miembros abriendo un formulario donde ingresa el correo y asigna el nivel de permisos (Ej. Almacenero o Auditor). Además, el administrador puede gestionar al personal existente seleccionando el menú de opciones en la tarjeta de un empleado. Desde allí, puede abrir un menú inferior para eliminarlo, acción que requiere confirmación mediante una ventana emergente de advertencia para evitar la revocación accidental de accesos, garantizando así un control seguro sobre quién puede auditar el inventario.

**El happy path:**
* **Inicio:** El usuario administrador ingresa a la vista "Equipo y Accesos".
* **Acción:** Hace clic en el botón superior "+ Invitar nuevo usuario".
* **Ingreso de datos:** El sistema muestra el formulario; el administrador escribe el correo electrónico y selecciona el "Rol en el sistema".
* **Asignación:** Se despliega el selector para asignar las zonas del almacén que el nuevo usuario podrá auditar.
* **Confirmación:** Hace clic en el botón oscuro "Enviar Invitación".
* **Fin del flujo:** El sistema procesa la solicitud, envía el correo al invitado y devuelve al administrador a la lista actualizada del equipo.

**Diagrama Lógico:**
![Logical Flow - User Goal 5](images/ug5-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 5](images/ug5-wireflow-visual.png)

#### 6. User Goal: Administración de suscripción y facturación

Este flujo describe cómo un usuario administra la facturación y escalabilidad de su cuenta SaaS. Desde el panel principal de suscripción, el administrador puede optar por cancelar su servicio o mejorar su plan actual. Si decide actualizar, navega por un catálogo comparativo y accede a un cotizador interactivo para el plan Enterprise, donde ajusta sus límites de almacenes y nodos IoT de evidencia de forma dinámica. Por último, el usuario revisa el resumen de pago con los montos prorrateados y confirma la transacción, logrando que el sistema actualice inmediatamente la capacidad operativa de su cuenta.

**El happy path:**
* **Inicio:** El administrador ingresa a la vista "Mi Suscripción".
* **Acción:** Hace clic en el botón oscuro "Cambiar Plan".
* **Selección:** En el catálogo de "Mejorar Plan", revisa las opciones y hace clic en "Actualizar a Enterprise".
* **Configuración:** Utiliza los controles deslizantes para establecer la cantidad exacta de Almacenes y Dispositivos IoT que necesita su operación, y presiona "Continuar al Pago".
* **Pago:** Revisa el detalle del "Resumen de Pago", valida su tarjeta y hace clic en el botón oscuro "Confirmar y Pagar".
* **Fin del flujo:** La plataforma procesa el cobro y redirige al usuario de vuelta al panel "Mi Suscripción", donde ahora se visualiza el plan Enterprise activo junto con las nuevas barras de límites extendidos para auditoría.

**Diagrama Lógico:**
![Logical Flow - User Goal 6](images/ug6-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 6](images/ug6-wireflow-visual.png)

#### 7. User Goal: Configuración de cuenta y notificaciones

Este flujo ilustra la gestión de preferencias y seguridad de la cuenta del usuario. Desde el panel principal de configuración, el administrador interactúa con los canales de notificaciones o selecciona la opción para salir de la plataforma. El sistema integra validaciones preventivas antes de ejecutar acciones definitivas; por ejemplo, si el usuario intenta silenciar las alertas, se le advierte del riesgo operativo (pérdida de trazabilidad de stock) mediante una ventana emergente. De manera similar, al intentar finalizar su sesión, se exige una confirmación explícita para evitar cierres accidentales y garantizar que el usuario comprenda que dejará de recibir alertas de inventario inmediatas en ese dispositivo.

**El happy path (Cierre de sesión):**
* **Inicio:** El usuario ingresa a la vista principal de Configuración.
* **Acción:** Hace clic en el botón inferior con el texto "Cerrar Sesión".
* **Advertencia:** El sistema detecta el intento de salida y despliega el modal de confirmación para evitar un cierre por error táctil.
* **Confirmación:** El usuario hace clic en el botón oscuro "Cerrar Sesión" dentro de la ventana.
* **Fin del flujo:** La plataforma cierra la sesión de forma segura y redirige automáticamente al usuario a la pantalla inicial de inicio de sesión.

**Diagrama Lógico:**
![Logical Flow - User Goal 7](images/ug7-wireflow-logical.png)

**Diagrama Visual (Wireflow):**
![Visual Wireflow - User Goal 7](images/ug7-wireflow-visual.png)

### 4.4.3. Web Applications Mock-ups

**Desktop**

Los mockups de la versión de escritorio presentan un sistema de diseño moderno y coherente, con una paleta de colores oscuros que ayuda a reducir la fatiga visual durante largos periodos de monitoreo. La arquitectura de información se organiza a través de una barra lateral persistente que facilita la navegación entre módulos clave como el panel de almacenes, el historial de eventos y la configuración. Además, el uso consistente de tipografías legibles y componentes estandarizados, como tarjetas y botones en tonos azules, permite mantener una jerarquía visual clara y fácil de seguir.

Con respecto a usabilidad e inclusión, la interfaz prioriza la prevención de errores y la retroalimentación constante. Las acciones críticas están protegidas mediante ventanas emergentes con alertas de alto contraste que advierten sobre sus consecuencias, mientras que los estados del sistema combinan iconos y texto para asegurar una comprensión clara. Esto permite que la información sea accesible para distintos tipos de usuarios y garantiza que tanto los flujos principales como los de error sean intuitivos.

#### Módulo de Autenticación y Acceso
![Login y Recuperación](images/desktop-mockup-01.png)

#### Módulo de Suscripción (Onboarding)
![Selección de Plan y Pago](images/desktop-mockup-02.png)

#### Módulo de Monitoreo y Auditoría en Tiempo Real
![Dashboard y Monitoreo](images/desktop-mockup-03.png)
![Filtros de Trazabilidad](images/desktop-mockup-04.png)
![Detalle de Merma](images/desktop-mockup-05.png)

#### Módulo de Gestión de Dispositivos IoT
![Nodos y Sensores](images/desktop-mockup-06.png)
![Vinculación de Dispositivos](images/desktop-mockup-07.png)

#### Módulo de Equipo y Accesos Logísticos
![Lista de Personal](images/desktop-mockup-08.png)
![Gestión de Permisos](images/desktop-mockup-09.png)

#### Escalabilidad Enterprise y Configuración
![Cotizador Enterprise](images/desktop-mockup-10.png)
![Preferencias y Cierre de Sesión](images/desktop-mockup-11.png)
![Salida Segura](images/desktop-mockup-12.png)

---

**Mobile**

La versión móvil mantiene coherencia con el diseño de escritorio, conservando el modo oscuro para asegurar comodidad visual y una experiencia profesional en cualquier contexto. La arquitectura de información se adapta a pantallas pequeñas mediante una barra de navegación inferior persistente, facilitando el acceso con el pulgar a módulos clave como Almacenes, Dispositivos IoT e Historial. Además, los tamaños de texto, tarjetas y áreas táctiles han sido optimizados para cumplir con estándares de accesibilidad, permitiendo una interacción fluida incluso en movimiento o con una sola mano.

A nivel interactivo, se priorizan patrones propios del entorno móvil, como el uso de bottom sheets para opciones secundarias y modales para confirmaciones críticas, evitando menús complejos. También, se incorporan indicadores visuales claros para estados del sistema, lo que permite identificar alertas de forma inmediata. Este enfoque no solo responde a las limitaciones del dispositivo, sino que mejora la experiencia general al ofrecer navegación intuitiva, retroalimentación constante y un diseño accesible para distintos tipos de usuarios.

#### Módulo de Autenticación y Onboarding (Mobile)
![Login y Suscripción Inicial](images/mobile-mockup-01.png)

#### Módulo de Monitoreo de Almacenes (Mobile)
![Gestión de Sucursales](images/mobile-mockup-02.png)

#### Módulo de Dispositivos IoT (Mobile)
![Hardware y Conectividad](images/mobile-mockup-03.png)

#### Módulo de Auditoría y Trazabilidad (Mobile)
![Historial y Mermas](images/mobile-mockup-04.png)

#### Módulo de Equipo y Accesos Logísticos (Mobile)
![Gestión de Personal](images/mobile-mockup-05.png)

#### Escalabilidad Enterprise y Facturación (Mobile)
![Renovación y Pagos](images/mobile-mockup-06.png)

#### Configuración, Alertas y Salida (Mobile)
![Preferencias de Cuenta](images/mobile-mockup-07.png)
![Cierre de Sesión Seguro](images/mobile-mockup-08.png)

### 4.4.4. Web Applications User Flow Diagrams

Mientras que el wireflow se enfoca en la estructura visual de las pantallas, el User Flow o Diagrama de Flujo de Usuario se centra en el proceso de toma de decisiones de la persona que opera NodeSecure. Este diagrama ayuda a comprender el camino lógico que sigue un Administrador Logístico o Jefe de Operaciones para alcanzar un objetivo específico, como puede ser la auditoría de una discrepancia de stock o una salida sin registro. Al desglosar cada acción y punto de decisión, podemos identificar posibles fricciones en la experiencia y asegurar que el sistema responda de manera coherente a las necesidades operativas de la empresa, garantizando que el flujo de información para prevenir mermas sea siempre claro y directo.

#### User Goal 1: Acceso e Inicio en el Sistema
Francisco, dueño de PYME, interactúa con la aplicación para registrarse o acceder a su cuenta mediante un flujo claro y sin fricciones. Si es su primera vez, sigue la ruta de registro completando sus datos comerciales. Si ya cuenta con credenciales, ingresa directamente con su correo y contraseña para acceder al panel principal. El sistema cuenta con un proceso de recuperación que le permite restablecer su acceso de forma segura a través de un enlace enviado a su correo electrónico, garantizando continuidad operativa sin bloqueos.

**El happy path: Inicio de sesión exitoso**
* **Inicio** ➔ Francisco abre la aplicación móvil y visualiza la pantalla de Acceso.
* **Decisión** ➔ El sistema le presenta las opciones y Francisco determina que ya tiene una cuenta activa.
* **Ingreso de datos** ➔ Francisco escribe su correo electrónico y su contraseña.
* **Acción** ➔ Presiona el botón azul "Ingresar".
* **Fin del flujo** ➔ El sistema valida las credenciales y Francisco entra exitosamente al panel de auditoría de sus almacenes.

**El unhappy path: Recuperación de Contraseña**
* **Inicio** ➔ Francisco abre la aplicación, pero no recuerda su contraseña.
* **Acción** ➔ Presiona el enlace "¿Olvidaste tu contraseña?".
* **Navegación** ➔ El sistema lo redirige a la vista de "Recuperar Contraseña".
* **Ingreso de datos** ➔ Francisco escribe el correo electrónico asociado a su empresa.
* **Confirmación** ➔ Presiona el botón "Enviar Enlace".
* **Fin del flujo** ➔ El sistema envía las instrucciones de restablecimiento al correo para que pueda recuperar su acceso de forma segura.

![User Flow - User Goal 1](images/ug1-userflow.png)

#### User Goal 2: Registro y Monitoreo de Almacenes
Como Jefe de Operaciones, Roberto quiere registrar nuevas sucursales y ver el estado de conciliación de todos los almacenes de la empresa en una sola plataforma para detectar rápidamente cualquier incidente.
En este escenario, Roberto agrega una nueva sucursal desde el panel principal. El flujo le solicita datos básicos y horarios de operación, incorporando validaciones en tiempo real (campos obligatorios en rojo) para evitar errores. Además, el sistema controla los límites del plan, mostrando una alerta restrictiva si ya alcanzó la cantidad máxima de almacenes permitidos.

**El happy path: Registro de almacén exitoso**
* **Inicio** ➔ Roberto se encuentra en la vista principal de "Mis Almacenes".
* **Acción** ➔ Presiona el botón azul "+ Registrar nuevo almacén".
* **Navegación** ➔ El sistema despliega el formulario "Nuevo Almacén".
* **Ingreso de datos** ➔ Roberto completa los campos y configura los Horarios de Operación mediante los interruptores interactivos.
* **Confirmación** ➔ Hace clic en "Guardar Almacén".
* **Fin del flujo** ➔ El sistema valida la información, muestra la ventana de "Registro Exitoso" y Roberto vuelve al dashboard donde la nueva sucursal ya figura en estado "Auditando".

**El unhappy path: Límite de Plan Alcanzado**
* **Inicio** ➔ Roberto presiona "+ Registrar nuevo almacén".
* **Intercepción** ➔ El sistema verifica la suscripción y detecta que la empresa ya alcanzó el límite máximo de almacenes.
* **Notificación** ➔ En lugar de abrir el formulario, se despliega la ventana "Límite de Almacenes", bloqueando el registro.
* **Fin del flujo** ➔ Roberto debe decidir: presionar "Mejorar a Plan Premium" para escalar la cuenta, o "Quizás más tarde" para regresar al dashboard sin cambios.

![User Flow - User Goal 2](images/ug2-userflow.png)

#### User Goal 3: Gestión de Dispositivos IoT
Roberto necesita registrar, vincular y administrar los sensores magnéticos y lectores RFID de cada almacén para cruzar la evidencia física con los registros de inventario.
Desde el panel de IoT, Roberto visualiza el estado de conexión (Online/Offline) de cada nodo. Puede vincular nuevos equipos si su plan lo permite; de lo contrario, el sistema bloquea la acción. También puede desvincular sensores obsoletos, acción que está protegida con una confirmación destructiva para evitar la pérdida accidental de trazabilidad.

**El happy path: Vinculación de dispositivo exitosa**
* **Inicio** ➔ Roberto ingresa a "Dispositivos IoT" y visualiza la lista de sensores.
* **Acción** ➔ Presiona el botón "+ Vincular nuevo dispositivo".
* **Navegación** ➔ Al tener cupo, el sistema lo dirige al formulario.
* **Ingreso de datos** ➔ Roberto ingresa el Número de Serie (S/N) y asigna la Zona (ej. Zona de Carga).
* **Procesamiento** ➔ Presiona "Vincular Dispositivo". Se muestra un modal de espera "Activando Dispositivo...".
* **Fin del flujo** ➔ Se confirma con "Dispositivo en línea" y Roberto regresa al panel donde el nuevo sensor aparece "Online".

![User Flow - User Goal 3](images/ug3-userflow.png)

#### User Goal 4: Auditoría de Eventos y Discrepancias
Roberto quiere ver un registro cronológico detallado de las actividades del almacén y filtrar la información para auditar cualquier salida sin registro o merma detectada.
El flujo permite aplicar filtros precisos. Al ubicar una alerta crítica, el usuario revisa la evidencia del sensor IoT. Tras evaluarla, decide si justificar la discrepancia (falsa alarma) o si reportar la merma directamente a la supervisión.

**El happy path: Auditoría y Escalamiento de Incidente**
* **Inicio** ➔ Roberto ingresa a "Auditoría y Trazabilidad" y observa la lista cronológica.
* **Acción** ➔ Hace clic en la tarjeta roja "Salida física sin registro".
* **Vista Rápida** ➔ El sistema despliega un modal de resumen. Roberto presiona "Ver Detalles y Evidencia".
* **Análisis** ➔ En "Detalle del Evento", revisa la hora exacta (timestamp) y la causa de activación.
* **Decisión** ➔ Al confirmar la merma, presiona el botón "Reportar Merma".
* **Fin del flujo** ➔ El sistema muestra el modal "Contactar a Supervisor". Roberto presiona "Sí, Llamar" para escalar el incidente de inventario.

![User Flow - User Goal 4](images/ug4-userflow.png)

#### User Goal 5: Gestión de Equipo y Accesos
Francisco, como dueño del negocio, quiere invitar a su personal operativo al sistema y asignar permisos por zonas logísticas para delegar auditorías sin perder el control de la seguridad.
El flujo abarca la invitación de nuevos miembros (asignando roles como Almacenero o Auditor) y la edición o revocación de accesos existentes, procesos siempre respaldados por modales de confirmación.

**El happy path: Invitación de usuario exitosa**
* **Inicio** ➔ Francisco ingresa a "Equipo y Accesos" para ver a su personal activo.
* **Acción** ➔ Presiona el botón "+ Invitar nuevo usuario".
* **Ingreso de datos** ➔ Escribe el correo del empleado, selecciona el rol (Almacenero) y las zonas asignadas.
* **Confirmación** ➔ Presiona "Enviar Invitación".
* **Fin del flujo** ➔ El sistema despliega "Invitación Enviada" y Francisco regresa a la lista donde el correo figura como "Pendiente".

![User Flow - User Goal 5](images/ug5-userflow.png)

#### User Goal 6: Suscripción y Facturación
Francisco necesita ampliar los límites operativos de su cuenta SaaS para registrar más almacenes y vincular más nodos IoT a medida que su negocio crece.
El flujo guía al usuario desde la selección del plan hasta un cotizador interactivo, calculando prorrateos y culminando en el checkout de pago para habilitar inmediatamente los nuevos límites.

**El happy path: Actualización a Plan Enterprise**
* **Inicio** ➔ Francisco ingresa a "Mi Suscripción" y nota que sus límites están al tope.
* **Acción** ➔ Presiona "Cambiar Plan".
* **Selección** ➔ Revisa el catálogo y elige "Actualizar a Enterprise".
* **Configuración** ➔ En el cotizador, ajusta los *sliders* a 5 almacenes y 25 dispositivos IoT. Presiona "Continuar al Pago".
* **Pago** ➔ En el Resumen de Pago, valida su método de pago y presiona "Confirmar y Pagar".
* **Fin del flujo** ➔ Aparece "¡Actualización Exitosa!". Al presionar "Ir a mi suscripción", visualiza sus límites operativos ampliados.

![User Flow - User Goal 6](images/ug6-userflow.png)

#### User Goal 7: Configuración de cuenta y notificaciones
Francisco gestiona sus preferencias de notificaciones para asegurar que recibe alertas de mermas sin interrupciones. 
El flujo incluye validaciones preventivas: si intenta apagar todas las alertas o cancelar su suscripción, se le advierte sobre la pérdida de trazabilidad. El cierre de sesión también exige confirmación para evitar la desconexión accidental del auditor en campo.

**El happy path: Cierre de sesión seguro**
* **Inicio** ➔ Francisco ingresa a la vista de "Configuración".
* **Acción** ➔ Toca el botón rojo "Cerrar Sesión".
* **Advertencia** ➔ El sistema despliega el modal "¿Cerrar sesión?" advirtiendo que dejará de recibir alertas en el dispositivo.
* **Confirmación** ➔ Francisco presiona "Sí, salir".
* **Fin del flujo** ➔ La plataforma finaliza la sesión y lo redirige a la pantalla inicial de acceso.

![User Flow - User Goal 7](images/ug7-userflow.png)

## 4.6. Domain-Driven Software Architecture

En esta sección se presenta la arquitectura de software de **NextPath** desde el enfoque de Domain-Driven Design (DDD), mostrando la organización del sistema, sus principales dominios, componentes y las relaciones entre los diferentes elementos que participan en la solución.

### 4.6.1. Software Architecture Context Diagram

El Software Architecture Context Diagram presenta una visión general del sistema NextPath y su interacción con los principales actores y sistemas externos. El diagrama permite identificar a los usuarios que utilizan la plataforma y los servicios externos con los que el sistema se comunica, como el servicio de pagos, el servicio de correo electrónico y la API de inteligencia artificial.


<div align="center">
  <img src="images/context.png.png" alt="repositorio">
</div>


### 4.6.3. Software Architecture Container Diagrams

Los Software Architecture Container Diagrams muestran la estructura interna de la plataforma NextPath a nivel de contenedores. Se representan la aplicación web, el API Gateway y los diferentes servicios que conforman la solución, además de las bases de datos y los sistemas externos con los que interactúan.

Los contenedores se organizan de acuerdo con las principales capacidades funcionales de la plataforma, incluyendo autenticación, evaluaciones, planificación de carrera, facturación, comunidad, servicios de asesoría y Analytics & AI.


<div align="center">
  <img src="images/container.png.png" alt="repositorio">
</div>

### 4.6.4. Software Architecture Components Diagrams

Los Software Architecture Components Diagrams presentan con mayor nivel de detalle la estructura interna de los principales servicios de NextPath. Cada diagrama descompone un contenedor en sus componentes principales y muestra las relaciones existentes entre ellos, así como las interacciones con bases de datos y sistemas externos.

Se detallan los componentes correspondientes a los diferentes servicios de la plataforma, permitiendo identificar las responsabilidades específicas dentro de cada contenedor y comprender cómo se procesan las funcionalidades del sistema.


<div align="center">
  <img src="images/AUTH.png.png" alt="repositorio">
</div>



# 5. Product Implementation, Validation & Deployment


## 5.1. Software Configuration Management
La gestión de configuración del software de NodeSecure permite organizar y controlar los artefactos generados durante el desarrollo, mantener trazabilidad de los cambios y facilitar el trabajo colaborativo. Para AV1, esta sección documenta las herramientas empleadas, la administración del código fuente, las convenciones adoptadas y la configuración de despliegue de la primera versión de la Landing Page.


### 5.1.1. Software Development Environment Configuration


#### Project Management


<table>
<tr>
<th>Producto</th>
<th>Propósito</th>
<th>Ruta</th>
</tr>
<tr>
<td>GitHub Projects</td>
<td>Planificación y seguimiento de issues, user stories y tareas del equipo.</td>
<td>https://github.com</td>
</tr>
</table>


#### Requirements Management


<table>
<tr>
<th>Producto</th>
<th>Propósito</th>
<th>Ruta</th>
</tr>
<tr>
<td>GitHub</td>
<td>Gestión de requerimientos mediante Issues y documentación versionada del proyecto.</td>
<td>https://github.com</td>
</tr>
<tr>
<td>Markdown</td>
<td>Documentación estructurada de requerimientos y del informe dentro del repositorio.</td>
<td>Integrado en GitHub</td>
</tr>
</table>


#### Product UX/UI Design


<table>
<tr>
<th>Producto</th>
<th>Propósito</th>
<th>Ruta</th>
</tr>
<tr>
<td>Figma</td>
<td>Diseño de wireframes, mockups y prototipos de la interfaz de usuario.</td>
<td>https://figma.com</td>
</tr>
<tr>
<td>UXPressia</td>
<td>Mapeo de la experiencia del cliente, incluyendo User Personas, mapas de empatía y Customer Journey Maps.</td>
<td>https://uxpressia.com/</td>
</tr>
<tr>
<td>Miro</td>
<td>Lienzo virtual colaborativo para investigación, brainstorming y organización de ideas.</td>
<td>https://miro.com/</td>
</tr>
<tr>
<td>PlantUML</td>
<td>Herramienta para crear diagramas UML a partir de texto y documentar estructuras técnicas.</td>
<td>https://plantuml.com/</td>
</tr>
</table>


#### Software Development


Se refiere al marco de trabajo y a las herramientas empleadas para la creación del producto digital. Durante AV1, el alcance de implementación se concentra en la Landing Page de NodeSecure.


<table>
<tr>
<th>Producto</th>
<th>Descripción</th>
<th>Ruta</th>
</tr>
<tr>
<td>GitHub</td>
<td>Plataforma de alojamiento y colaboración que permite gestionar el control de versiones y el trabajo en equipo.</td>
<td>https://github.com</td>
</tr>
<tr>
<td>Visual Studio Code</td>
<td>Editor de código fuente ligero y extensible utilizado para el desarrollo de la Landing Page.</td>
<td>https://code.visualstudio.com/</td>
</tr>
<tr>
<td>HTML5</td>
<td>Lenguaje de marcado utilizado para estructurar semánticamente el contenido de la Landing Page.</td>
<td>https://developer.mozilla.org/es/docs/Web/HTML</td>
</tr>
<tr>
<td>CSS3</td>
<td>Lenguaje de estilos utilizado para definir la presentación visual y la adaptación responsive.</td>
<td>https://developer.mozilla.org/es/docs/Web/CSS</td>
</tr>
<tr>
<td>JavaScript</td>
<td>Lenguaje utilizado para la interacción y comportamiento dinámico de la Landing Page.</td>
<td>https://developer.mozilla.org/es/docs/Web/JavaScript</td>
</tr>
</table>


#### Software Testing


El testing se considera como el proceso de evaluación del producto para verificar que la Landing Page cumpla los requerimientos definidos y funcione correctamente en los escenarios previstos.


<table>
<tr>
<th>Herramienta</th>
<th>Descripción</th>
<th>Ruta</th>
</tr>
<tr>
<td>Gherkin</td>
<td>Lenguaje DSL para definir comportamientos mediante escenarios Given, When, Then.</td>
<td>https://cucumber.io/docs/gherkin/</td>
</tr>
<tr>
<td>GitHub Pages</td>
<td>Servicio utilizado para publicar la Landing Page y validar su funcionamiento en un entorno accesible.</td>
<td>https://pages.github.com/</td>
</tr>
</table>


### 5.1.2. Source Code Management


En esta sección se describe la gestión del código fuente (SCM, por sus siglas en inglés: Source Code Management), la cual permite registrar, organizar y controlar los cambios realizados durante el desarrollo de NodeSecure. GitHub se utiliza como plataforma central para la administración de repositorios y colaboración entre los integrantes.


<table>
<tr>
<th>Componente</th>
<th>Repositorio</th>
</tr>
<tr>
<td>Project Report</td>
<td>https://github.com/SecureZoneTeam/NodeSecure-Report</td>
</tr>
<tr>
<td>Landing Page</td>
<td>https://github.com/SecureZoneTeam/NodeSecure-Landing-Page</td>
</tr>
</table>


#### GitFlow


NodeSecure adopta GitFlow como modelo de trabajo basado en ramas. La rama <code>main</code> contiene las versiones estables del producto; <code>develop</code> funciona como rama de integración; y las ramas <code>feature/&lt;nombre-de-seccion&gt;</code> se utilizan para desarrollar funcionalidades específicas antes de integrarlas mediante Pull Requests.


<table>
<tr>
<th>Rama</th>
<th>Propósito</th>
</tr>
<tr>
<td><code>main</code></td>
<td>Contiene versiones finales y estables listas para despliegue.</td>
</tr>
<tr>
<td><code>develop</code></td>
<td>Integra las funcionalidades desarrolladas antes de una liberación.</td>
</tr>
<tr>
<td><code>feature/&lt;nombre-de-seccion&gt;</code></td>
<td>Permite desarrollar una funcionalidad o sección de manera aislada y luego integrarla a <code>develop</code>.</td>
</tr>
</table>


#### Conventional Commits


Los mensajes de commit se estructuran mediante Conventional Commits para mantener un historial claro y facilitar la identificación del tipo de cambio realizado.


<table>
<tr>
<th>Tipo</th>
<th>Uso</th>
</tr>
<tr>
<td><code>feat</code></td>
<td>Incorporación de nuevas funcionalidades.</td>
</tr>
<tr>
<td><code>fix</code></td>
<td>Corrección de errores.</td>
</tr>
<tr>
<td><code>docs</code></td>
<td>Modificaciones de documentación.</td>
</tr>
<tr>
<td><code>style</code></td>
<td>Cambios de formato o estilo sin impacto en la lógica.</td>
</tr>
<tr>
<td><code>refactor</code></td>
<td>Mejoras internas del código sin añadir funcionalidades.</td>
</tr>
<tr>
<td><code>test</code></td>
<td>Creación o modificación de pruebas.</td>
</tr>
<tr>
<td><code>chore</code></td>
<td>Configuración o mantenimiento.</td>
</tr>
</table>


**Ejemplos adaptados al proyecto NodeSecure:**


text
feat(landing): add hero section
feat(pricing): add NodeSecure subscription plans
style(responsive): improve mobile layout
docs(chapter-05): update sprint 1 evidence


### 5.1.3. Source Code Style Guide & Conventions
Para garantizar coherencia, legibilidad y mantenibilidad en la Landing Page de NodeSecure, el equipo adopta convenciones de estilo para HTML, CSS y JavaScript. Los identificadores y comentarios del código se mantienen consistentes dentro del repositorio.


#### HTML & CSS
- Uso de minúsculas para nombres de elementos y atributos HTML.
- Uso de comillas dobles para los atributos.
- Indentación consistente de 2 espacios.
- Clases CSS con nomenclatura kebab-case, por ejemplo `pricing-card` o `hero-section`.
- Evitar estilos inline y centralizar los estilos en archivos CSS.
- Incluir el atributo `alt` en las imágenes para favorecer la accesibilidad.
- Aplicar media queries para adaptar la interfaz a desktop, tablet y mobile.


#### JavaScript
- Uso de `const` para variables que no se reasignan y `let` cuando el valor puede cambiar.
- Nombres de variables y funciones en camelCase.
- Nombres de clases y constructores en PascalCase cuando corresponda.
- Evitar el uso de `var`.
- Mantener funciones y eventos con responsabilidades claras.
- Usar punto y coma de manera consistente.


#### Gherkin (Acceptance Criteria)
- Uso de Given, When, Then y And en inglés.
- Una sola acción principal por paso When.
- Escenarios con nombres descriptivos del comportamiento esperado.
- Uso de tablas Gherkin cuando sea necesario representar datos de ejemplo.


#### Conventional Commits
Todos los mensajes de commit del proyecto deben seguir la especificación de Conventional Commits.


### 5.1.4. Software Deployment Configuration


Para AV1, el componente que debe estar implementado y desplegado es la primera versión de la Landing Page de NodeSecure. El repositorio utilizado para este componente es NodeSecure-Landing-Page y el despliegue se realiza mediante GitHub Pages, siempre que esta configuración corresponda al despliegue real del equipo.


#### Creación de la Landing Page


Se crea un repositorio desde la organización SecureZoneTeam.


<div align="center">
  <img src="images/cap 5/1.png" alt="repositorio">
</div>


Agregamos a los miembros del equipo.


Habilitamos GitHub Pages en la rama <code>main</code> y la ruta <code>/(root)</code>.


#### Configuración de despliegue


Para la entrega, NodeSecure cuenta con una Landing Page desplegada mediante GitHub Pages.


<table>
<tr>
<th>Componente</th>
<th>Repositorio</th>
<th>Tecnología</th>
<th>Entorno de despliegue</th>
<th>URL pública</th>
</tr>
<tr>
<td>Landing Page</td>
<td>NodeSecure-Landing-Page</td>
<td>HTML5, CSS, JS</td>
<td>GitHub Pages</td>
<td>https://securezoneteam.github.io/NodeSecure-Landing-Page/</td>
</tr>
</table>


## 5.2. Landing Page, Services & Applications Implementation


Esta sección registra y explica el proceso de implementación, pruebas y despliegue de los productos digitales de NodeSecure organizados por Sprint. Para AV1 se documenta el Sprint 1, cuyo objetivo es entregar la primera versión funcional de la Landing Page. La Landing Page constituye el primer punto de contacto del producto con los segmentos objetivo: dueños y administradores de PYMES, así como responsables de seguridad y operaciones.


### 5.2.1. Sprint 1


### 5.2.1.1. Sprint Planning 1


En esta sección se documenta el Sprint Planning Meeting correspondiente al **Sprint 1**, donde el equipo de NodeSecure estableció el objetivo del sprint, definió el alcance de trabajo y distribuyó las tareas necesarias para desarrollar la primera versión funcional de la Landing Page.


### Sprint Planning


<table>
<tr>
<th>Campo</th>
<th>Información</th>
</tr>
<tr>
<td>Sprint #</td>
<td>Sprint 1</td>
</tr>
<tr>
<td>Sprint Planning Background</td>
<td>Primera versión funcional de la Landing Page de NodeSecure</td>
</tr>
<tr>
<td>Date</td>
<td>2026-09-09</td>
</tr>
<tr>
<td>Time</td>
<td>03:30 PM</td>
</tr>
<tr>
<td>Location</td>
<td>Meet</td>
</tr>
<tr>
<td>Prepared By</td>
<td>Fernando Sebastián Pérez</td>
</tr>
</table>


### Sprint Goal & User Stories


El objetivo del Sprint 1 fue implementar y desplegar la primera versión funcional de la Landing Page de NodeSecure, permitiendo comunicar de manera clara la propuesta de valor del producto.


La Landing Page contempla la presentación de las principales características de NodeSecure, sus planes, testimonios, información del equipo, contenido audiovisual y medios de contacto.


<table>
<tr>
<th>Campo</th>
<th>Valor</th>
</tr>
<tr>
<td>Sprint 1 Goal</td>
<td>Implementar y desplegar la primera versión funcional de la Landing Page de NodeSecure.</td>
</tr>
<tr>
<td>Sprint 1 Velocity</td>
<td>4 horas</td>
</tr>
<tr>
<td>Sum of Estimation (Hours)</td>
<td>4 horas</td>
</tr>
</table>


### 5.2.1.2. Aspect Leaders and Collaborators


Para el Sprint 1 se establecieron los responsables y colaboradores para los diferentes aspectos relacionados con la implementación de la Landing Page de NodeSecure. Esta distribución permitió organizar las responsabilidades del equipo y coordinar el desarrollo de las diferentes secciones y actividades del sprint.


<table>
<tr>
<th>Team Member</th>
<th>GitHub Username</th>
<th>Hero & Navbar</th>
<th>Features & About</th>
<th>Pricing & Testimonials</th>
<th>Team & Contact</th>
<th>Deployment & QA</th>
</tr>
<tr>
<td>Fernando Sebastián Pérez Bellido</td>
<td>Fern.bellido22</td>
<td>L</td>
<td>L</td>
<td>L</td>
<td>L</td>
<td>L</td>
</tr>
<tr>
<td>Anahua Ancachi, Liz Maribel</td>
<td>lizzanahua-rgb</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
</tr>
<tr>
<td>Sandoval Aiquipa, Kelber Yamir</td>
<td>Kyesei</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
</tr>
<tr>
<td>Ravello Cárdenas, Luciana Angielina</td>
<td>Lucyrcar-ID</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
<td>C</td>
</tr>
</table>


Leyenda:


- L = Aspect Leader.
- C = Collaborator.


### 5.2.1.3. Sprint Backlog 1


El objetivo principal del Sprint 1 es implementar y desplegar la primera versión funcional de la Landing Page de NodeSecure. Para alcanzar este objetivo, las User Stories seleccionadas fueron descompuestas en Engineering Tasks relacionadas con la estructura, diseño, contenido, responsividad y despliegue de la Landing Page.


### Sprint Backlog


A continuación, se presenta el Sprint Backlog correspondiente al Sprint 1, incluyendo las User Stories seleccionadas, las tareas derivadas de cada una, su descripción, estimación, responsable y estado de ejecución.


> **Evidencia del Board:**  
> [INSERTAR CAPTURA DEL BOARD DEL SPRINT 1]


> **URL público del Board:**  
> [INSERTAR URL DEL BOARD DEL SPRINT 1]


<table>
<tr>
<th>Sprint #</th>
<th>User Story ID</th>
<th>User Story Title</th>
<th>Task ID</th>
<th>Task Title</th>
<th>Task Description</th>
<th>Estimation (Hours)</th>
<th>Assigned To</th>
<th>Status</th>
</tr>


<tr>
<td>Sprint 1</td>
<td>US21</td>
<td>Visualizar landing page</td>
<td>T01</td>
<td>Estructura HTML y entorno de desarrollo</td>
<td>Configurar el repositorio, definir la estructura semántica de HTML5 e implementar las variables globales CSS.</td>
<td>4</td>
<td>Anahua Ancachi, Liz Maribel</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US21</td>
<td>Visualizar landing page</td>
<td>T02</td>
<td>Implementación del Hero Section y Navbar</td>
<td>Codificar la barra de navegación responsiva y estructurar el Hero con la propuesta de valor de NodeSecure.</td>
<td>4</td>
<td>Anahua Ancachi, Liz Maribel</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US21</td>
<td>Visualizar landing page</td>
<td>T03</td>
<td>Desarrollo técnico de la sección Features</td>
<td>Maquetar el sistema de grid con CSS Grid/Flexbox para presentar las características principales de NodeSecure.</td>
<td>4</td>
<td>Fernando Sebastián Pérez Bellido</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US23</td>
<td>Visualizar información del equipo</td>
<td>T04</td>
<td>Maquetación del módulo About y Team</td>
<td>Desarrollar las tarjetas visuales del equipo y asegurar su adaptación a vistas móviles.</td>
<td>4</td>
<td>Fernando Sebastián Pérez Bellido</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US58</td>
<td>Ver planes y precios desde landing page</td>
<td>T05</td>
<td>Implementación de Pricing Cards</td>
<td>Construir las tarjetas comparativas de los planes definidos para NodeSecure con sus beneficios y llamados a la acción.</td>
<td>4</td>
<td>Fernando Sebastián Pérez Bellido</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US57</td>
<td>Visualizar testimonios de la comunidad</td>
<td>T06</td>
<td>Construcción del grid de Testimonials</td>
<td>Implementar la sección de testimonios con una cuadrícula adaptable, avatares y jerarquía tipográfica.</td>
<td>4</td>
<td>Fernando Sebastián Pérez Bellido</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US24</td>
<td>Contactar desde la landing page</td>
<td>T07</td>
<td>Desarrollo de Contacto y Footer</td>
<td>Implementar la sección de contacto y el footer corporativo con enlaces y canales de comunicación.</td>
<td>4</td>
<td>Sandoval Aiquipa, Kelber Yamir</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US22</td>
<td>Visualizar video del producto</td>
<td>T08</td>
<td>Integración de Video y Media</td>
<td>Integrar el video About-the-Product y optimizar la carga de los recursos estáticos.</td>
<td>4</td>
<td>Sandoval Aiquipa, Kelber Yamir</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US21</td>
<td>Visualizar landing page</td>
<td>T09</td>
<td>Refactorización de Media Queries</td>
<td>Realizar pruebas cross-browser y aplicar media queries (CSS) en toda la Landing Page para garantizar la vista mobile.</td>
<td>5</td>
<td>Ravello Cárdenas, Luciana Angielina</td>
<td>[ESTADO REAL]</td>
</tr>


<tr>
<td>Sprint 1</td>
<td>US21</td>
<td>Visualizar landing page</td>
<td>T10</td>
<td>Configuración de CI/CD en GitHub Pages</td>
<td>Configurar las acciones de despliegue, habilitar GitHub Pages sobre la rama main y validar rutas en producción.</td>
<td>5</td>
<td>Ravello Cárdenas, Luciana Angielina</td>
<td>[ESTADO REAL]</td>
</tr>


</table>


Leyenda del estado:


- To-do: tarea pendiente de iniciar.
- In-Process: tarea actualmente en desarrollo.
- To-Review: tarea terminada pendiente de revisión.
- Done: tarea completada y validada.


### 5.2.1.4. Development Evidence for Sprint Review


Durante el Sprint 1, el equipo trabajó colaborativamente en el repositorio **NodeSecure-Landing-Page**, aplicando GitFlow y utilizando la convención de Conventional Commits para registrar los cambios realizados durante la implementación de la Landing Page.


Los commits presentados a continuación corresponden a los cambios relacionados con la construcción, modificación, corrección y configuración de la Landing Page durante el Sprint 1. La información se presenta a partir del historial real de commits del repositorio.


<table>
<tr>
<th>Repository</th>
<th>Branch</th>
<th>Commit ID</th>
<th>Commit Message</th>
<th>Commit Message Body</th>
<th>Committed On (Date)</th>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>main</td>
<td>752da92</td>
<td>fix: se arregló caracteristicas de planes</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>main</td>
<td>571582a</td>
<td>Delete CNAME</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>main</td>
<td>7bff9d3</td>
<td>Create CNAME</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>2a5c484</td>
<td>feat: perfiles de los creadores</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>4fef969</td>
<td>fix: se arreglo tamaño para profiles photos</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>9971778</td>
<td>fix: adjust testimonial images</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>ebeef36</td>
<td>feat: implementacion de la seccion footer</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>201a1af</td>
<td>fear: implementacion de la seccion de contacto</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>7b671bd</td>
<td>feat: implementacion de testimonios</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>4fb63cf</td>
<td>feat: implementacion de la seccion del team</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>2df77df</td>
<td>On feature/landingpage-pricing: cambios team</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>902683c</td>
<td>index on feature/landingpage-pricing: 6233530 fix: se arregló estilos</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>6233530</td>
<td>fix: se arregló estilos</td>
<td>—</td>
<td>2026-09-11</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>5955457</td>
<td>Revert "Feature/landingpage pricing"</td>
<td>—</td>
<td>2026-09-10</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>14e59c9</td>
<td>feat: implementacion de los planes en la landing page</td>
<td>—</td>
<td>2026-09-10</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>d9c9916</td>
<td>feat: implementacion de la seccion de informacion en la landing page</td>
<td>—</td>
<td>2026-09-10</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>9eddac7</td>
<td>feat: implement landing page header and hero</td>
<td>—</td>
<td>2026-09-10</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>44a571f</td>
<td>feat: creacion inicial de la estructura de la landing page</td>
<td>—</td>
<td>2026-09-10</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>602656d</td>
<td>--INSERT-- ASDcrear</td>
<td>—</td>
<td>2026-09-09</td>
</tr>


<tr>
<td>NodeSecure-Landing-Page</td>
<td>develop</td>
<td>46cb562</td>
<td>chore: inicialización de la landing pae</td>
<td>—</td>
<td>2026-09-09</td>
</tr>


</table>


### Repository


- NodeSecure-Landing-Page: https://github.com/SecureZoneTeam/NodeSecure-Landing-Page


### 5.2.1.5. Execution Evidence for Sprint Review


Al concluir el Sprint 1, el equipo logró implementar y desplegar la primera versión funcional de la Landing Page de **NodeSecure**. La página presenta la propuesta de valor del producto y las principales secciones definidas en el Sprint Backlog, incluyendo Hero, Navbar, características de la solución, About, Team, Pricing, Testimonials, Contact y Footer.


A continuación, se presentan las evidencias de ejecución de las principales funcionalidades y secciones implementadas durante el Sprint 1.


#### Hero & Navbar


La siguiente evidencia muestra la sección inicial de la Landing Page, donde se presenta la propuesta de valor de NodeSecure junto con la barra de navegación.


<div align="center">
  <img src="images/cap 5/1.png" alt="repositorio">
</div>


Figura 1. Hero y Navbar de la Landing Page de NodeSecure.


#### Features & Solution


La siguiente evidencia muestra la sección de características y solución, donde se presentan las principales funcionalidades y beneficios de NodeSecure.


<div align="center">
  <img src="images/cap 5/2.png" alt="repositorio">
</div>


Figura 2. Sección de características de NodeSecure.


#### About


La siguiente evidencia muestra la sección About, donde se presenta información relacionada con NodeSecure y su propuesta de solución.


<div align="center">
  <img src="images/cap 5/2.png" alt="repositorio">
</div>


Figura 3. Sección About de NodeSecure.


#### Pricing


La siguiente evidencia muestra la sección de planes y precios disponibles para la solución NodeSecure.


<div align="center">
  <img src="images/cap 5/4.png" alt="repositorio">
</div>


Figura 4. Sección de planes y precios de NodeSecure.


#### Testimonials


La siguiente evidencia muestra la sección de testimonios incorporada en la Landing Page.


<div align="center">
  <img src="images/cap 5/5.png" alt="repositorio">
</div>


Figura 5. Sección de testimonios de NodeSecure.


#### Team


La siguiente evidencia muestra la sección correspondiente al equipo responsable del desarrollo de NodeSecure.


<div align="center">
  <img src="images/cap 5/3.png" alt="repositorio">
</div>


Figura 6. Sección Team de NodeSecure.


#### Contact


La siguiente evidencia muestra la sección de contacto, mediante la cual los visitantes pueden encontrar los canales disponibles para comunicarse con el equipo.


<div align="center">
  <img src="images/cap 5/6.png" alt="repositorio">
</div>


Figura 7. Sección de contacto de NodeSecure.


#### Footer


La siguiente evidencia muestra el Footer de la Landing Page, incluyendo los elementos y enlaces correspondientes.


<div align="center">
  <img src="images/cap 5/6.png" alt="repositorio">
</div>


Figura 8. Footer de la Landing Page de NodeSecure.


#### Responsive Design


La siguiente evidencia demuestra el comportamiento responsive de la Landing Page en dispositivos con diferentes tamaños de pantalla.


<div align="center">
  <img src="images/cap 5/7.png" alt="repositorio">
</div>


### 5.2.1.6. Services Documentation Evidence for Sprint Review


Durante el Sprint 1, el alcance de implementación se concentró en el desarrollo y despliegue de la primera versión funcional de la **Landing Page de NodeSecure**.


En este Sprint no se implementaron servicios REST asociados al backend del sistema, por lo que no se cuenta con endpoints desarrollados que requieran documentación mediante Swagger/OpenAPI.


La documentación de servicios REST será incorporada en los siguientes Sprints, cuando se implementen los componentes correspondientes del backend de NodeSecure.


### Services Documentation


<table>
<tr>
<th>Elemento</th>
<th>Estado en Sprint 1</th>
<th>Evidencia</th>
</tr>
<tr>
<td>RESTful Web Services</td>
<td>No implementados en Sprint 1</td>
<td>No aplica</td>
</tr>
<tr>
<td>Swagger / OpenAPI</td>
<td>No implementado en Sprint 1</td>
<td>No aplica</td>
</tr>
<tr>
<td>API Endpoints</td>
<td>No implementados en Sprint 1</td>
<td>No aplica</td>
</tr>
<tr>
<td>API Documentation</td>
<td>No aplica para este Sprint</td>
<td>No aplica</td>
</tr>
</table>


### 5.2.1.7. Software Deployment Evidence for Sprint Review


Durante el Sprint 1 se realizó el despliegue de la primera versión funcional de la **Landing Page de NodeSecure** mediante **GitHub Pages**.


El despliegue permite acceder públicamente a la Landing Page desde un navegador web, utilizando la versión estable disponible en la rama `main` del repositorio correspondiente.


### Deployment Configuration


<table>
<tr>
<th>Elemento</th>
<th>Configuración</th>
</tr>
<tr>
<td>Software Product</td>
<td>NodeSecure Landing Page</td>
</tr>
<tr>
<td>Repository</td>
<td>NodeSecure-Landing-Page</td>
</tr>
<tr>
<td>Deployment Platform</td>
<td>GitHub Pages</td>
</tr>
<tr>
<td>Deployment Branch</td>
<td>main</td>
</tr>
<tr>
<td>Public URL</td>
<td>https://securezoneteam.github.io/NodeSecure-Landing-Page/</td>
</tr>
</table>


### Deployment Evidence


La siguiente evidencia muestra la configuración del despliegue de la Landing Page mediante GitHub Pages.


<div align="center">
  <img src="images/cap 5/9.png" alt="repositorio">
</div>


Figura 10. Configuración del despliegue de NodeSecure Landing Page mediante GitHub Pages.


La siguiente evidencia muestra la Landing Page de NodeSecure disponible desde su URL pública después del despliegue.


<div align="center">
  <img src="images/cap 5/8.png" alt="repositorio">
</div>


Figura 11. Landing Page de NodeSecure desplegada y accesible públicamente.


### Public Access


La versión desplegada de la Landing Page puede ser consultada mediante el siguiente enlace:


NodeSecure Landing Page:  
https://securezoneteam.github.io/NodeSecure-Landing-Page/


El despliegue permite validar que la primera versión funcional desarrollada durante el Sprint 1 se encuentra disponible para consulta desde un navegador web.


### 5.2.1.8. Team Collaboration Insights during Sprint


Durante el Sprint 1, el equipo de NodeSecure trabajó de manera colaborativa para desarrollar la primera versión funcional de la Landing Page. La organización del trabajo se realizó mediante la distribución de responsabilidades entre los integrantes y el uso de GitHub como plataforma para gestionar el código fuente y coordinar la integración de los cambios.


El desarrollo de la Landing Page se realizó de manera incremental, asignando diferentes responsabilidades relacionadas con las principales secciones del producto, como Hero & Navbar, Features & About, Pricing & Testimonials, Team & Contact y Deployment & QA.


Asimismo, el equipo utilizó ramas de trabajo para desarrollar funcionalidades específicas y posteriormente integrar los cambios en las ramas correspondientes. Esta dinámica permitió mantener una separación entre las funcionalidades durante su desarrollo y facilitar su posterior integración.


Durante el Sprint también se utilizaron mensajes de commit para registrar los cambios realizados en el repositorio. Los commits permitieron mantener la trazabilidad de las funcionalidades implementadas y de las correcciones realizadas durante el desarrollo de la Landing Page.


### Collaboration Practices


<table>
<tr>
<th>Aspect</th>
<th>Collaboration Practice</th>
</tr>
<tr>
<td>Task Distribution</td>
<td>Las actividades del Sprint fueron distribuidas entre los integrantes de acuerdo con los aspectos definidos para la Landing Page.</td>
</tr>
<tr>
<td>Version Control</td>
<td>Se utilizó Git y GitHub para gestionar las diferentes versiones del código fuente.</td>
</tr>
<tr>
<td>Branching</td>
<td>Se utilizaron ramas para desarrollar funcionalidades específicas antes de integrarlas al flujo principal del proyecto.</td>
</tr> 
<tr>
<td>Commits</td>
<td>Se registraron los cambios mediante commits para mantener la trazabilidad del desarrollo.</td>
</tr>
<tr>
<td>Integration</td>
<td>Los cambios desarrollados fueron integrados mediante el flujo de trabajo establecido para el repositorio.</td>
</tr>
<tr>
<td>Deployment</td>
<td>El equipo coordinó la configuración y validación del despliegue de la Landing Page mediante GitHub Pages.</td>
</tr>
</table>

# Conclusiones

Al finalizar este primer avance (AV1) y el primer Sprint del proyecto SafeZone, el equipo ha llegado a las siguientes conclusiones fundamentales:
    
1. **Validación de la Problemática Logística:** A través de la investigación de mercado y el análisis de competidores, se ha confirmado que la "merma desconocida" y el "robo hormiga" representan puntos de dolor críticos y costosos para el sector comercial en el Perú. La dependencia de sistemas pasivos (como la revisión manual de CCTV) genera un desgaste operativo severo, lo que valida la necesidad de una solución como NodeSecure, capaz de integrar evidencia física IoT (sensores) con el registro digital de inventario en tiempo real.

2. **Efectividad del Enfoque Lean UX:** La aplicación del proceso Lean UX y el desarrollo de entrevistas (Needfinding) han sido determinantes para definir los segmentos objetivo. Al empatizar tanto con los dueños de PYMES (enfoque gerencial) como con los operarios de almacén (enfoque de campo), se logró estructurar un Product Backlog alineado a necesidades reales. Se determinó que el personal operativo requiere rapidez extrema en el registro (menos de 30 segundos), mientras que la gerencia exige auditoría basada en marcas de tiempo (*timestamps*) inalterables.

3. **Arquitectura de Información y Diseño B2B:** El diseño de la experiencia de usuario (UX) y la interfaz (UI) para la plataforma web y móvil ha demostrado que la adopción de un modelo B2B en "Dark Mode" no responde únicamente a una tendencia estética, sino a una necesidad operativa. Este esquema reduce la fatiga visual en entornos de monitoreo prolongado, mientras que el diseño responsivo basado en *bottom-sheets* y la estricta jerarquía de información previenen errores humanos al realizar tareas críticas, como la asignación de permisos y el control de discrepancias.

4. **Éxito del Despliegue Inicial (Sprint 1):** La adopción de GitFlow, el uso de Conventional Commits y las prácticas de configuración y despliegue continuo (CI/CD) han permitido al equipo trabajar de forma organizada y paralela. El resultado de este esfuerzo técnico se materializa en el despliegue exitoso de la Landing Page de NodeSecure en GitHub Pages, logrando comunicar eficientemente nuestra propuesta de valor al mercado y sentando una base tecnológica sólida para los próximos Sprints de desarrollo de la plataforma core.