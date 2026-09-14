

















# NodeSecure-Report
## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

En el entorno logístico y empresarial actual, el control de inventarios y la seguridad de los almacenes enfrentan grandes desafíos, especialmente debido a las pérdidas por el "robo hormiga", accesos no autorizados y a un monitoreo deficiente en tiempo real. Los sistemas de seguridad tradicionales suelen ser puramente reactivos, limitándose a grabar incidentes sin ofrecer herramientas analíticas para prevenirlos de forma inmediata. Frente a este escenario, SafeZone emerge como una startup tecnológica enfocada en transformar la gestión de la seguridad industrial y comercial. Nuestra misión es ofrecer un ecosistema inteligente que permita a los negocios dejar atrás la vigilancia pasiva, otorgándoles un control activo y preventivo sobre sus activos más valiosos.

Para dar solución a esta problemática, SafeZone ha desarrollado NodeSecure, una plataforma inteligente de control de inventario potenciada por la trazabilidad de la tecnología IoT. NodeSecure va mucho más allá de ser un simple registro digital de productos o un hardware que controla puertas físicas; es un sistema web integral que relaciona directamente los movimientos operativos del inventario con los eventos físicos que suceden dentro de las instalaciones. La idea central que hace único a nuestro producto es que el software registra detalladamente lo que digitalmente debería ocurrir, mientras que los dispositivos IoT actúan como evidencia física para informar lo que realmente sucedió en el espacio.

El ecosistema de NodeSecure funciona utilizando dispositivos físicos simples, como sensores magnéticos, que reportan constantemente la actividad del entorno. Cuando la plataforma detecta un evento físico, como la apertura de un almacén, lo compara de forma automática con el historial de entradas y salidas registradas. Si se produce una acción física que no cuenta con un movimiento de inventario asociado que la justifique, el sistema identifica la discrepancia y genera una alerta inmediata. Gracias a un dashboard unificado, los administradores pueden supervisar múltiples áreas, auditar quién realizó cada operación y mantener una trazabilidad temporal exacta, facilitando respuestas rápidas ante cualquier irregularidad o desconexión.

La propuesta de valor de SafeZone está diseñada bajo un modelo altamente escalable, adaptándose tanto a dueños de PYMES que buscan soluciones accesibles para evitar mermas diarias, como a jefes de operaciones que requieren controlar redes complejas y auditar incidentes de forma rigurosa. El verdadero diferencial comercial de NodeSecure radica en brindar una visibilidad operativa total: permite a los usuarios saber con precisión qué mercancía salió, quién fue el responsable de registrarla, en qué momento exacto ocurrió y, lo más importante, advertir al instante si hubo alguna actividad física anómala que no cuadre con el registro oficial.


#### 1.1.2 Integrantes del equipo

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
</table>


### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

Hoy en día, la gestión logística y el sector retail enfrentan un desafío crítico que compromete directamente su rentabilidad: la pérdida sistemática de inventario. En Perú, estudios revelan que las mermas en el sector comercial peruano generan pérdidas de entre S/ 700 y S/ 1,000 millones anuales. Lo más preocupante es que cerca del 52% de estas pérdidas corresponde a la llamada "merma desconocida", una categoría conformada en su gran mayoría por hurtos, fraudes y el persistente "robo hormiga". Este último fenómeno, caracterizado por la sustracción de pequeñas cantidades de mercadería a lo largo del tiempo, resulta sumamente complejo de detectar mediante auditorías convencionales, acumulando daños financieros severos para las empresas (Conexión ESAN, 2026).

**<ins>5W + 2H de la problemática</ins>**

- **What? (¿Cuál es el problema?):** Pérdidas económicas significativas en los sectores de logística y retail debido a la "merma desconocida", específicamente por robos hormiga, hurtos y fraudes.

- **Who? (¿Quién lo sufre?):** Dueños de PYMES, gerentes de operaciones y jefes de seguridad en el sector retail, distribución y logística. 

- **Where? (¿Dónde ocurre?):** En almacenes, depósitos, bodegas y centros de distribución de empresas comerciales en Perú y en toda Latinoamérica.

- **When? (¿Cuándo ocurre?):** Durante la gestión diaria de inventarios, especialmente cuando los procesos de vigilancia son pasivos o reactivos y no permiten una detección inmediata de irregularidades.

- **Why? (¿Por qué ocurre?):** Por la desconexión operativa entre los registros digitales y la realidad física del almacén, sumado a que las empresas perciben la tecnología IoT preventiva comos costosa o compleja de implementar.

- **How? (¿Cómo se manifiesta?):** Mediante descuadres de inventario recurrentes, accesos físicos no detectados a tiempo (robo hormiga), revisiones manuales tardías y una pérdida total de trazabilidad operativa por la ausencia de sensores IoT que validen los registros digitales en tiempo real. 

- **How much? (¿Cuánto afecta?):**  Provoca continuas mermas económicas por falta de control físico, pérdida de inventario por "robos hormiga" y un elevado costo de oportunidad debido a la excesiva carga de tareas manuales al tener que auditar cámaras e incidentes de forma tardía.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statement

**El estado actual de** la gestión de inventario y seguridad operativa en almacenes **se ha enfocado principalmente en** el uso de sistemas de vigilancia estrictamente reactivos (como cámaras CCTV o candados) y en registros digitales aislados, obligando a las empresas a realizar auditorías manuales lentas y a depender de sistemas desconectados para investigar las mermas.

**Lo que los productos y servicios existentes no logran abordar es** la profunda desconexión entre los movimientos teóricos del sistema y los eventos físicos que realmente ocurren, sumado a la fuerte barrera económica que hace que las empresas rechacen tecnologías avanzadas al percibirlas como excesivamente costosas y complejas de implementar.

**Nuestro producto** (NodeSecure) **abordará esta brecha mediante** una plataforma web centralizada de control de inventario inteligente que permite monitorear los espacios, controlar accesos y gestionar la información en tiempo real, ya que utiliza tecnología IoT como fuente de evidencia física. El sistema valida y contrasta de forma automática las actividades registradas con cada apertura física realizada, identificando inconsistencias inmediatamente, optimizando la trazabilidad del inventario y enviando alertas en tiempo real.

**Nuestro enfoque inicial será** los dueños y administradores de PYMES, así como también los jefes de seguridad y operaciones del sector logístico.

**Sabremos que tenemos éxito cuando veamos** una alta tasa de retención en nuestros planes de suscripción, una adopción rápida de la plataforma sin necesidad de capacitaciones complejas, y una reducción comprobable en los tiempos de respuesta ante intrusiones y en las pérdidas originadas por robos internos en los almacenes de los clientes.



## Capítulo II: Requirements Elicitation & Analysis 
### 2.1. Competidores
#### 2.1.1. Análisis competitivo
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








##### 2.1.2. Estrategias y tácticas frente a competidores

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