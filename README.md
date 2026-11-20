<div align="center">

# David Figueroa

**Android Tech Lead · 18 años construyendo software que tiene que funcionar donde falla la señal**

Kotlin · Jetpack Compose · KMP · Node.js · AWS · Adopción de IA y agentes

[faro.net.ar](https://faro.net.ar) · [LinkedIn](https://www.linkedin.com/in/david-figueroa-mentor-faro-android-ia) · [CV](https://faro.net.ar/recursos) · [david@faro.net.ar](mailto:david@faro.net.ar)

</div>

---

**70+ proyectos · 14 organizaciones · 4 dominios regulados o críticos**
Fintech bajo norma BCRA · software clínico con CE, GDPR y CatSalut · logística de valores · operación de campo sin conectividad.

---

## Cómo leer este portfolio

Cada entrada declara **año** y **tipo de vínculo**. Es información que la mayoría de los portfolios omite y sin la cual "70 proyectos" no significa nada.

| | Vínculo |
|---|---|
| 🏢 | Trabajo para una organización, en relación de dependencia o prestación a dedicación completa |
| 🔦 | Cartera de FARO, mi consultoría independiente |
| 🚀 | Producto propio |

Cuando el trabajo llegó a través de un intermediario, figuran los dos: **quien contrató** y **el cliente final**.

---

## Casos destacados

### 🏢 Ncuenta · NaranjaX · 2021–2023
**Fintech regulada · equipo de 15 personas**

Una billetera virtual tenía que convertirse en una fintech regulada por el Banco Central. Eso significaba rehacer Onboarding, validación de identidad (KYC) y prevención de lavado (AML) sin perder a los usuarios en el camino: cada requisito regulatorio nuevo es un paso más donde alguien abandona.

Lideré la migración de CVU a CBU como Tech Lead Mobile, coordinando Android, Backend e iOS con Scrum of Scrum. **La conversión de usuarios pasó del 70% al 90%.**

Además incorporamos accesibilidad con TalkBack y su equivalente en iOS para audiencia no vidente, y mejoras antifraude con validación biométrica.

[Google Play](https://play.google.com/store/apps/details?id=com.tarjetanaranja.ncuenta)

---

### 🏢 Xsales · Apex Global Mobility | Grupo Mariposa · 2024–presente
**Fuerza de ventas para marcas Bia, PepsiCo y asociadas · 9 países · offline first**

Dos aplicaciones que conviven en un mismo monorepo. **Asesor** es la herramienta del vendedor: preventa, gestión de crédito, portafolio, productos, rutas, lealtad y servicios al cliente. **Líder** es la del supervisor que conduce a ese equipo de vendedores, y es el producto del que soy líder técnico desde agosto de 2026.

**Cumplimiento del roadmap por encima del 85% por trimestre**, un nivel que no se sostenía antes, con la operación en campo sin interrupciones.

Vendedores que trabajan en zonas sin señal, sincronizando cuando la encuentran. Todo el diseño gira alrededor de esa restricción.

**Consolidación en monorepo.** Era objetivo clave del período. Se estimó en dos meses y se entregó en uno. Definimos junto al equipo transversal los criterios de segregación de módulos comunes. **Sobre esa base se construyó Líder**, la tercera aplicación del ecosistema: la arquitectura no solo unificó lo existente, habilitó un producto nuevo. El costo real fue sincronizar releases, features y correcciones en curso a través de varias instancias; salió más barato un mecanismo para unificar versiones de librerías comunes sin afectación cruzada.

**Migración de Realm a Couchbase Lite.** Forzada por la discontinuación del SDK. Subestimamos la similitud entre ambos: hubo trabajo real en réplicas, escala, índices, optimización de consultas, drain y caché con Room. La operación en campo no se interrumpió.

**Adopción de IA.** Incorporé Claude, Gemini y Microsoft Copilot al ciclo de desarrollo del equipo.

---

### 🏢 Muvin · Bolsa de Comercio de Rosario, vía Alternativas Inteligentes (hoy SaiLO) · 2023–2024
**Agroindustria · 10 personas a cargo**

Plataforma de logística agrícola para cerdos, cereales y fertilizantes, con varias verticales atendidas por el mismo equipo.

El problema no era técnico al principio: cada entrega arrastraba **hasta tres correcciones de urgencia** y el equipo perdía medio sprint en retrabajo. Las personas estaban asignadas a dos y tres proyectos a la vez, sin foco ni prioridad.

Reorganicé el área en células con foco por proyecto, introduje Git Flow, entregas por tren de versiones y Scrum, y puse a QA como responsable de la validación. **Las entregas pasaron a salir limpias**, primero por sprint y después mensuales. Los cambios arrancaron en la segunda mitad del primer mes.

En paralelo conduje la migración arquitectónica y modular de la plataforma para mejorar performance, observabilidad y calidad, e inicié el pase a Node.js capacitando al equipo.

`Angular` `PWA` `microfrontends` `PHP` `Node.js` `MySQL` `SSO` `SAML`

---

### 🔦 wtswrng · Mangrana Ventures y Setfile, Barcelona · 2021–2024
**Software clínico en producción**

Aplicación de salud que genera diagnóstico presuntivo, en uso en clínicas privadas de Barcelona. Requisitos de **CE, GDPR y CatSalut** resueltos.

La accesibilidad no era una capa opcional: la interfaz es enteramente ilustrada, **sin palabras, sin género, sin idioma y sin edad**, para que funcione con cualquier paciente que la tenga delante.

Los conocí como cliente de CloudX y después continuaron la cuenta conmigo de forma directa durante tres años.

---

### 🏢 CloudX · 2020–2021
**Reducción de costos de infraestructura**

**−80% de costos cloud en AWS.** Tres frentes: desacople de recursos sobredimensionados, alineación de la escala a la demanda real del producto, y aprovechamiento de capas gratuitas y planes para startups. El remanente fijo tras todos los ajustes quedó en el 20%.

Implementé además SDUI y BFF con AWS Lambda, lo que permitió actualizar la interfaz sin nuevo despliegue.

Productos: Librology, red social de club de lectores y autores; y verificadores de síntomas.

---

### 🔦 BA Agentes, BA Móvil y Paradas de Colectivos · GCBA, vía Kwan Mobile · 2016–2019
**Civic tech a escala de ciudad**

Tres sistemas para el Gobierno de la Ciudad Autónoma de Buenos Aires: gestión de infracciones para agentes de tránsito en la calle, relevamiento de paradas de transporte público, y consulta ciudadana del estado del tránsito, vuelos e indicaciones de manejo.

Casi tres años de relación sostenida con el cliente final a través del contratante.

---

### 🏢 Genesis Mobile · Prosegur, vía Tecsol Group · 2021
**Logística de valores · Europa y América Latina**

Aplicaciones de manejo de efectivo y mercadería con escaneo intensivo de códigos de barra y QR en operación de calle.

**−30% en tiempos de escaneo**, por cambio de librería, mejora de componentes internos y ajustes en la comunicación con los demás dispositivos del flujo. **−25% en tiempos de comunicación con servidor.**

El trabajo de comparación de librerías que sostiene ese número está publicado como POC: ver **DemoScan**, hoy evolucionado a WhyScan.

---

## 🚀 Productos propios · FARO

| Producto | Estado | Qué valida |
|---|---|---|
| **WhyScan** | [Play Store](https://play.google.com/store/apps/details?id=ar.net.faro.whyscan) · publicado | Compose Multiplatform, offline first, accesibilidad y asistencia de agentes de IA. Sin cuenta, sin rastreo, sin telemetría. Evoluciona el POC DemoScan sobre Zxing, Quickie y Scandit |
| **Dynamic** | POC en curso | Kotlin, Compose y Material3 con BFF y SDUI para sistema de diseño |
| **Salto Inicial** | [Google Play](https://play.google.com/store/apps/details?id=com.boa.saltoinicial) | Todo el básquet de Mendoza: resultados en vivo, notas y entrevistas |
| **faro.net.ar** | En producción | Sitio propio en Astro. Código privado |

---

## Capacidades sostenidas

No son tecnologías que aprendí una vez. Son problemas que vengo resolviendo en organizaciones distintas a lo largo de los años.

**Operación sin conectividad** — Adecoagro 2013, control de acceso a campos rurales con escaneo QR y sincronización diferida · Prosegur 2021, escaneo en logística de valores · Apex Global Mobility | Grupo Mariposa 2024, fuerza de ventas en campo con Couchbase Lite · WhyScan 2026.

**Accesibilidad real** — wtswrng, interfaz sin dependencia de idioma ni alfabetización · NaranjaX, TalkBack y su equivalente en iOS · WhyScan, como objetivo explícito de producto.

**Cumplimiento regulatorio** — norma BCRA en fintech argentina · CE, GDPR y CatSalut en software clínico español.

**Adopción de IA con método** — especificaciones ejecutables, agentes con MCP y verificación de salidas. Comparando estimaciones de entrega con y sin asistencia en tres organizaciones, los trabajos se entregaron hasta 40% antes. La cifra es sobre estimaciones, no sobre throughput medido. Se sostiene con modelos económicos: la ganancia viene del método, no del gasto en tokens.

---

## Catálogo completo

### 🏢 Trabajo para organizaciones

| Años | Organización | Proyectos |
|---|---|---|
| 2024– | Apex Global Mobility \| Grupo Mariposa | Asesor · preventa, crédito, portafolio, rutas y lealtad para vendedores; Líder · supervisión de equipos de venta. Marcas Bia, PepsiCo y asociadas en 9 países |
| 2023–2024 | Alternativas Inteligentes (hoy SaiLO) | Muvin · Bolsa de Comercio de Rosario |
| 2021–2023 | NaranjaX | Ncuenta |
| 2021 | Prosegur, vía Tecsol Group | Genesis Mobile |
| 2020–2021 | CloudX | Librology · red social de club de lectores; verificadores de síntomas; Watchman · seguimiento para seguridad privada |
| 2020 | GlobalLogic | Fixed · relevamiento y preventa para Claro Argentina |
| 2019–2020 | Winecta | Padel Manager, Audioguía Oficial de Granada, Peep, Creatuaplicacion, gestión de escuelas |
| 2018–2019 | FTL | Infratrack · infracciones de tránsito en Lanús y Ezeiza |
| 2017–2018 | Streambe | BPN · promociones, sucursales, cajeros y homebanking; Ethic Compass · conflictos de interés, denuncias y encuestas; BK · gestión de solicitudes de bonos para bienes de capital; CoberMed · conexión de afiliados con obra social; portal generador de aplicaciones base |
| 2015–2017 | Tween, luego Vloom | Vloom · plataforma de envío masivo de SMS y push; Tarjeta Naranja; Tarjeta Nevada · migración de PHP 5 a 7, CodeIgniter 2 a 3 y Laravel 4 a 5 sobre sitio público, sitio seguro y panel de contenidos; Crypto · billetera móvil de bitcoins |
| 2013–2015 | Aconcagua Software Factory | Adecoagro, PCG · Pan American Energy, Sanatorio Finochietto, FriendBall, 4coronas, FácilMúsica |
| 2012–2013 | Rumaos | SGRRHH · RedMercosur, SGDOC, SGOP, DNI, ASEGH · gestión hospitalaria |
| 2009–2012 | Aconcagua Software Factory | Construpages, El Sol Online, Empretur, mendobytes |
| 2009 | BIG SA | Comproaccesorios · e-commerce para concesionaria Ford Meschini; portal de pasajes e información turística |
| 2008–2009 | MAIN Sistemas | ERP a medida para Dil Brands; Presenter · portal de presentaciones publicitarias; IVD · API de gestión de inventario; sitios web a medida |

### 🔦 Cartera de FARO

| Años | Cliente | Proyecto |
|---|---|---|
| 2021–2024 | wtswrng · Barcelona | App clínica de diagnóstico presuntivo |
| 2024 | Jacidi · Barcelona | Digital signage sobre Android TV y Chromecast para cadenas hoteleras y de gimnasios |
| 2023– | FUSAP → QuintoAndar | Mentoría técnica a equipos de desarrollo |
| 2019 | Me cubro | MeCubro · APIs de contratación de seguros de transporte y accidentes |
| 2019 | Inmoclick | Inmoclick e Inmoclick2 · proptech, migración de Java a Kotlin con MVVM y Clean |
| 2019 | Tuten IT | Cabbo · red social y navegación para usuarios de embarcaciones |
| 2019 | That Day in London | Sistemas de encuestadores y voluntarios en campo |
| 2018–2019 | iVelopment | Conectate · eficiencia energética y energías renovables |
| 2018–2019 | Ubykuo | Plan Américas · llamadas VoIP con tarjeta prepaga |
| 2017–2018 | WeChain, para Tween | Recompensas en criptomonedas con blockchain en Android |
| 2017–2018 | XRP | XRPSalesWork · catálogo, pedidos, rutas y cobranzas para preventistas |
| 2017 | FotoSprint | Catálogo de productos fotográficos con red de comercios adheridos |
| 2016–2019 | Kwan Mobile → GCBA | BA Agentes, BA Móvil, Paradas de Colectivos |
| 2016–2017 | Viewpoints | Servicio Meteorológico Nacional · visualización y pronóstico del clima; apps de turismo y marketing |
| 2016 | Software Factory | Sage · app para entrevistadores de campo |
| 2014–2015 | Goddy | Goody · red social que conecta deportistas con productos del rubro |
| varios | Desarrollos propios y prototipos | RentAtablet · gestión de invitados a eventos; Woman · acompañamiento a mujeres con proyección ejecutiva; Chapi, AjustAR y TraslatorChat · alfas |

---

## Dónde escribo

Los criterios con los que elijo arquitectura y evalúo código están publicados en abierto:

- [Arquitectura Android 2026: patrones que realmente sostienen](https://faro.net.ar/blog/arquitectura-android-2026)
- [Cómo evaluar la calidad del código como líder técnico](https://faro.net.ar/blog/calidad-codigo-lideres-tecnicos)

Servicios y casos en [faro.net.ar/portfolio](https://faro.net.ar/portfolio); CV y recursos en [faro.net.ar/recursos](https://faro.net.ar/recursos).

---

## Trabajemos juntos

Estoy abierto a oportunidades remotas o híbridas desde Mendoza, Argentina, y a proyectos de consultoría a través de FARO.

**[david@faro.net.ar](mailto:david@faro.net.ar)** · **[faro.net.ar](https://faro.net.ar)** · **[LinkedIn](https://www.linkedin.com/in/david-figueroa-mentor-faro-android-ia)**

<div align="right"><sub>Última revisión: 2026-11 · <a href="https://github.com/dgfigueroa29/portfolio_en">English version</a></sub></div>
