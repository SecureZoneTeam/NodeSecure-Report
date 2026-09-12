

















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
      <img src="images/liz-foto.png" width="150" alt="Foto de Liz">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Anahua Ancachi Liz Maribel[cite: 1]<br>
      <strong>Código:</strong> U202421123[cite: 1]<br>
      <strong>Carrera:</strong> Ingeniería de Software[cite: 1]<br><br>
      Estudiante de Ingeniería de Software en la UPC de quinto ciclo de la carrera[cite: 1]. Tengo conocimientos básicos en C++, SQL[cite: 1]. Me considero una persona responsable y empática a la hora de colaborar en equipo[cite: 1]. Además, me encanta el diseño y plantear soluciones creativas a los problemas para entregar el mejor resultado posible[cite: 1].
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/sebastian-foto.png" width="150" alt="Foto de Fernando">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Fernando Sebastián Pérez Bellido[cite: 1]<br>
      <strong>Código:</strong> U202410420[cite: 1]<br>
      <strong>Carrera:</strong> Ingeniería de Software[cite: 1]<br><br>
      Estudiante de Ingeniería de Software en la UPC con un enfoque en la creación de soluciones tecnológicas que generen impacto real[cite: 1]. Cuento con bases sólidas en C++, Python y un poco de conocimiento en React, complementadas con conocimientos en SQL y entornos cloud[cite: 1]. Me apasiona aplicar la lógica algorítmica para resolver problemas complejos[cite: 1].
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="images/luciana-foto.png" width="150" alt="Foto de Luciana">
    </td>
    <td>
      <strong>Nombres y Apellidos:</strong> Ravello Cárdenas Luciana Angielina[cite: 1]<br>
      <strong>Código:</strong> U20221F887[cite: 1]<br>
      <strong>Carrera:</strong> Ingeniería de Software[cite: 1]<br><br>
      Estudiante de Ingeniería de Software en la UPC cursando el quinto ciclo de la carrera[cite: 1]. Tengo conocimientos en C++, SQL y Figma[cite: 1]. Se me considera una persona amable y responsable, lo que ayuda a crear un buen ambiente en equipo[cite: 1]. Siempre estoy dispuesta a escuchar opiniones y sugerencias para mejorar la calidad de los trabajos entregados[cite: 1].
    </td>
  </tr>
</table>

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

