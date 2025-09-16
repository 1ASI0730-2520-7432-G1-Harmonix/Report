# Capítulo IV: Product Design
## 4.1. Style Guidelines.

Harmonix es una plataforma digital orientada a la simplificación y el equilibrio en la gestión financiera del hogar. Mediante un sistema de cálculo proporcional basado en los ingresos, facilita la distribución justa de los gastos, promoviendo la transparencia, la colaboración y el control compartido. Su interfaz, de carácter moderno y minimalista, responde a las demandas de los hogares contemporáneos que requieren soluciones eficientes, accesibles y sostenibles en el tiempo.

La presente sección consolida una guía integral de estilo, en la cual se definen los elementos visuales y de diseño que sustentan la identidad de Harmonix. Se incorporan tipografías, paleta cromática —con predominio de negro, blanco y azul celeste—, íconos y componentes de interfaz, con el objetivo de asegurar una representación visual coherente, sobria y alineada con la visión tecnológica y funcional de la marca.

La estructura de las guías de estilo se organiza en tres bloques principales: General Style Guidelines, Web Style Guidelines y Mobile Style Guidelines. Esta división garantiza una experiencia uniforme, accesible y consistente en todos los dispositivos, fortaleciendo la navegabilidad, la confianza del usuario y la comunicación visual de los valores fundamentales de la plataforma: claridad, equilibrio y control.

### 4.1.1. General Style Guidelines.

Harmonix transmite una identidad visual moderna, clara y funcional, alineada con sus valores de transparencia, colaboración y equidad financiera. La marca se apoya en una base cromática oscura para reflejar profesionalismo y seriedad, mientras que el azul celeste se utiliza como color de acento para resaltar interacciones relevantes, aportando frescura y un carácter tecnológico.

El logotipo, de diseño simple y distintivo, asegura un reconocimiento inmediato en diferentes dispositivos y formatos. La tipografía, de estilo limpio y legible, contribuye a una navegación fluida y una experiencia coherente en todas las interfaces.

En conjunto, la estética de Harmonix busca transmitir control y confianza, reforzando el propósito de la plataforma: facilitar la organización financiera del hogar de manera justa, práctica y accesible.

#### Tipografía

La tipografía oficial de Harmonix es **Roboto**, seleccionada por su estilo moderno, alta legibilidad en fondos oscuros y flexibilidad en interfaces digitales. Se emplean las variantes Regular, Medium, Bold y Black para establecer jerarquías visuales claras.

- `h1` → 3em (48px)  
- `h2` → 2em (32px)  
- `h3` → 1em (16px)  
- **Texto general** → 1em (16px)

Esta estructura tipográfica garantiza consistencia visual y facilidad de lectura en todos los dispositivos.

#### Colores

La identidad visual se apoya en un esquema cromático que combina **sobriedad y modernidad**.  

- **Color base (fondo principal)**: `#000000` (negro)  
- **Primario**: `#1565C0` (azul oscuro)  
- **Secundario**: `#42A5F5` (celeste)  
- **Apoyo**: `#E3F2FD` (azul claro)  
- **Texto**: `#FFFFFF` (blanco)  

<p styles="align: left">
  <img src="../images/paleta.PNG" alt="paleta de colores" width="500">
</p>  

Esta combinación de colores refuerza la **claridad, accesibilidad y coherencia visual** de la plataforma.  

#### Espaciado  

La estructura de espaciado está diseñada para mantener un **orden visual armónico**:  

- **Botones**: `padding 1rem` (vertical), `2rem` (horizontal)  
- **Texto**: `margin-bottom: 1rem` en `h1`, `h2`, `p`, etc.  
- **Elementos**: `margin-bottom: 1.5rem` en tarjetas y componentes similares  
- **Secciones**: `padding: 2rem` en contenedores (ajustable a `6rem`)  

#### Iconografía  

Harmonix utiliza **Bootstrap Icons**, garantizando consistencia, escalabilidad y compatibilidad en diferentes resoluciones.  

**Íconos principales**  
- `bi-house-door-fill` → Inicio  
- `bi-info-circle-fill` → Información  
- `bi-gear-fill` → Servicios  
- `bi-question-circle-fill` → Guía de uso  
- `bi-currency-dollar` → Planes  
- `bi-chat-left-quote-fill` → Opiniones  
- `bi-envelope-fill` → Contacto  

**Íconos en servicios**  
- `bi-calculator` → Cálculo proporcional  
- `bi-pie-chart-fill` → Seguimiento de gastos  
- `bi-people-fill` → Colaboración  

**Íconos en flujo de uso**  
- `bi-person-plus-fill` → Registro  
- `bi-house-fill` → Crear hogar  
- `bi-cash-coin` → Aportes  
- `bi-bar-chart-fill` → Control financiero  

**Íconos en footer**
- Redes sociales: `bi-facebook`, `bi-instagram`, `bi-twitter`, `bi-linkedin`  
- Contacto: `bi-envelope-fill`  

El uso uniforme de iconos asegura **coherencia estética y usabilidad**.  

#### Tono de Comunicación y Lenguaje Aplicado

El tono de Harmonix es **claro, inclusivo y accesible**, diseñado para generar confianza y facilitar la adopción de la plataforma.  

**Características principales**:  
- **Amigable y cercano**: lenguaje directo y motivador  
- **Claridad funcional**: roles diferenciados  
  - **Representante**: crea y gestiona el hogar  
  - **Miembro**: se une mediante ID  
- **Proceso simplificado**: instrucciones breves y fáciles de seguir  
- **Empatía**: reconoce y aborda los desafíos de la gestión financiera en el hogar  
- **Acción inmediata**: llamadas directas como *“Crea tu hogar”* o *“Ingresa a tu hogar”*  
- **Accesibilidad**: redacción libre de tecnicismos innecesarios  

Este tono refuerza la **transparencia y cercanía** de la marca, asegurando que cada usuario se sienta acompañado en el control de sus finanzas compartidas.  

### 4.1.2. Web Style Guidelines.

Se utilizó la tendencia web de **funcionalismo minimalista** con un esquema de colores oscuros predominante (negro y gris oscuro) como fondo. Esto proporciona una experiencia visual suave, favoreciendo el contraste con elementos interactivos y textos claros.

<p styles="align: left">
  <img src="../images/imagen1.jpg" alt="imagen1" width="500">
</p>

Para enriquecer la estética y agregar dinamismo:

- Se emplearon íconos blancos con moderación.  
- El diseño se mantiene minimalista pero atractivo.  
- Los íconos, claramente visibles sobre el fondo oscuro, refuerzan una experiencia visual limpia y ordenada.

Este equilibrio entre funcionalidad y diseño moderno garantiza una interfaz eficaz y atractiva.

<p styles="align: left">
  <img src="../images/imagen2.PNG" alt="imagen2" width="500">
</p>

## 4.2. Information Architecture.
### 4.2.1. Organization Systems  

En la plataforma **Harmonix**, se aplican diferentes sistemas de organización del contenido para optimizar la **accesibilidad** y la **experiencia de usuario**, en función del tipo de información presentada.  
Estos sistemas garantizan una navegación intuitiva, clara y eficiente.  

#### Organización Visual del Contenido  

**Jerárquica (Visual Hierarchy):**  
Se utiliza en secciones que requieren una estructura clara de importancia y relevancia, como formularios de creación de hogar o asignación de aportes.  
Se aplican **variaciones tipográficas** y un **orden lógico de presentación** para resaltar los elementos más relevantes (botones de acción o campos requeridos), guiando al usuario de manera natural a través del flujo de la aplicación.  

**Secuencial (Step-by-Step):**  
En procesos que deben completarse paso a paso —como el registro de usuario o la creación de un hogar— se aplica un enfoque secuencial.  
Cada paso se presenta en una pantalla específica, lo que permite a los usuarios comprender y completar cada acción antes de avanzar, reduciendo errores y confusión.  

#### Esquemas de Categorización de Contenido  

**Por Audiencia (User Groups):**  
La plataforma distingue entre **representantes de hogar** y **miembros de hogar**:  
- **Representantes** → gestionan aportes y creación de hogar.  
- **Miembros** → consultan sus aportes y realizan seguimiento de gastos.  

Esta categorización asegura que cada tipo de usuario acceda únicamente a las funcionalidades que necesita, reforzando la simplicidad y eficiencia de la experiencia.  

**Por Tópicos:**  
En las secciones de ayuda y soporte, el contenido se organiza por categorías temáticas:  
- *Preguntas Frecuentes*  
- *Política de Privacidad*  
- *Centro de Ayuda*  

Esto facilita la búsqueda de información relevante y la resolución autónoma de dudas por parte del usuario.  

#### Implementación en la Interfaz  

La aplicación de estos sistemas se refleja en el diseño mediante:  
- **Navegación clara y estructurada** con menús desplegables.  
- **Botones con texto explicativo** que guían acciones.  
- **Flujos visibles paso a paso** en procesos clave.  
- **Íconos y etiquetas textuales** que refuerzan la comprensión del contenido.  

De esta manera, Harmonix asegura una experiencia de navegación **intuitiva, eficiente y adaptada** a cada perfil de usuario, manteniendo coherencia con su estilo visual minimalista y accesible.  

### 4.2.2. Labeling Systems.

La landing page de **Harmonix** emplea un sistema de etiquetado **directo, simple y orientado a la acción**, cuyo objetivo principal es facilitar la comprensión inmediata del contenido y garantizar una navegación fluida para distintos tipos de usuarios.  

El sistema de etiquetado se caracteriza por:  
- Uso de **términos cortos y claros**, evitando ambigüedades.  
- Refuerzo mediante **íconos visuales de Bootstrap Icons**, que optimizan la identificación de secciones.  
- Consistencia terminológica en todas las áreas de la interfaz, reforzando la coherencia comunicativa.  

#### Menú de navegación  

En el menú principal, ubicado en la parte superior de la landing page, se emplean etiquetas simples y directas, acompañadas de íconos para mejorar la comprensión visual:  

- **Home** (`bi-house-door-fill`)  
- **About** (`bi-info-circle-fill`)  
- **Services** (`bi-tools`)  
- **How does it work?** (`bi-lightbulb-fill`)  
- **Prices** (`bi-currency-dollar`)  
- **Reviews** (`bi-chat-dots-fill`)  
- **Contact us** (`bi-envelope-fill`)  

<p styles="align: left">
  <img src="../images/imagen3.jpg" alt="imagen3" width="500">  
</p>  

#### Botón principal (CTA)  

El botón principal de la landing page funciona como la **llamada a la acción (CTA)** más destacada:  

- **Register** → etiqueta clara y universal, válida tanto para miembros como para representantes.  

<p styles="align: left">
  <img src="../images/imagen1.jpg" alt="imagen4" width="500">  
</p>  

#### Sección *How does it work?* – Representantes  

Para los **representantes del hogar**, las etiquetas enfatizan acciones de gestión:  

- **Sign up** (`bi-person-plus-fill`)  
- **Create your home** (`bi-house-fill`)  
- **Assign contributions** (`bi-cash-coin`)  
- **Control your finances** (`bi-bar-chart-fill`)  

<p styles="align: left">
  <img src="../images/imagen4.jpg" alt="" width="500">  
</p>  

#### Sección *How does it work?* – Miembros  

Para los **miembros del hogar**, las etiquetas refuerzan su rol de participación:  

- **Sign up** (`bi-person-plus-fill`)  
- **Join a household** (`bi-key-fill`)  
- **Declare your income** (`bi-wallet-fill`)  
- **Monitor your contributions** (`bi-graph-up-arrow`)  

<p styles="align: left">
  <img src="../images/imagen5.jpg" alt="" width="500">  
</p>  


#### Footer  

El pie de página organiza el etiquetado en dos bloques principales:  

- **Enlaces legales:**  
  - Legal notice  
  - Privacy Policy  
  - Cookies Policy  

- **Soporte y ayuda:**  
  - Contact Support  
  - Help Center  
  - Frequently asked questions

Además, se incluyen **íconos de redes sociales** (Facebook, Instagram, Twitter, LinkedIn) que funcionan como accesos rápidos.  

<p styles="align: left">
  <img src="../images/imagen6.jpg" alt="" width="500">  
</p>  

### 4.2.3. SEO Tags and Meta Tags

En el desarrollo de la landing page de Harmonix, la correcta implementación de etiquetas SEO (Search Engine Optimization) y Meta Tags resulta fundamental para optimizar la visibilidad del sitio en motores de búsqueda y garantizar una adecuada indexación del contenido. Estas etiquetas permiten describir de manera precisa el propósito de la plataforma, los servicios ofrecidos y las palabras clave asociadas, favoreciendo que el proyecto sea fácilmente localizable por usuarios interesados en soluciones de gestión financiera compartida.

Asimismo, los Meta Tags proporcionan información esencial para la accesibilidad y la experiencia del usuario, ya que definen parámetros técnicos como la codificación de caracteres, la adaptación a distintos dispositivos y la atribución de autoría del proyecto. En conjunto, estos elementos no solo fortalecen el posicionamiento orgánico de Harmonix en buscadores, sino que también refuerzan su identidad digital, coherente con los valores de claridad, transparencia y equidad financiera que la marca transmite.

html
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>Hamonix - Control financiero justo para tu hogar</title>
    <meta name="description" content="Hamonix te ayuda a dividir los gastos del hogar de forma proporcional según los ingresos de cada miembro. Fácil, justo y transparente.">
    <meta name="keywords" content="Hamonix, finanzas compartidas, gastos del hogar, app de finanzas, control de gastos, división de pagos">
    <meta name="author" content="Equipo Hamonix">

    <!-- CSS & Icons -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
    <link rel="icon" href="/images/logo.PNG" alt="Logo">
</head>

### 4.2.4. Searching Systems.

En el caso de **Harmonix**, se implementará un sistema de búsqueda y filtros diseñado para que tanto los **miembros** como los **representantes del hogar** puedan acceder de manera rápida y sencilla a la información que necesitan.  
El sistema estará optimizado según el rol del usuario, garantizando una navegación fluida y eficiente dentro de la aplicación.

#### Filtros de búsqueda por entradas

**Miembros del hogar:**
- **Buscar por ID de hogar:** Permite unirse a un hogar ya creado ingresando el ID proporcionado por el representante.  
- **Filtrar por fecha de contribución:** Visualizar el historial de aportes organizados por periodos (semanal, mensual).  
- **Estado de los aportes:** Filtrar contribuciones por estado: `"Aportado"`, `"Pendiente"`, `"Excedente"`.  
- **Filtrar por tipo de gasto:** Clasificar los gastos en categorías como `"Alimentos"`, `"Servicios"`, `"Otros"`.  

**Representantes del hogar:**
- **Filtrar por estado de los aportes:** Consultar las contribuciones según estado o rango de fechas.  
- **Filtrar por miembros:** Buscar por nombre o ID de miembro para revisar su historial de aportes.  
- **Balance financiero:** Filtrar el balance general del hogar por periodo o tipo de gasto.  


#### Filtros de búsqueda por tabs

Para una mejor experiencia, la aplicación contará con **tabs interactivos** que agrupan la información de forma clara y ordenada.

**Miembros:**
- **Historial de aportes:** Resumen con filtros por fecha, monto y estado.  
- **Estado de gastos:** Visualización gráfica de la distribución de los gastos del hogar.  
- **Unirse a hogar (ID):** Asociación rápida al perfil vinculado mediante el ID del hogar.  

**Representantes:**
- **Gestión de aportes:** Vista completa de aportes de todos los miembros, filtrable por estado y fecha.  
- **Balance general:** Resumen financiero global con filtros por categorías y periodos.  


#### Flujo de búsqueda y filtros

El flujo será **intuitivo y dinámico**.  
En cada sección relevante (aportaciones, balances, gastos), se integrarán campos de búsqueda y filtros configurables.  
Los usuarios podrán aplicar o remover filtros con facilidad, garantizando una experiencia ágil, clara y sin fricciones.

### 4.2.5. Navigation Systems.

En **Harmonix**, la navegación está diseñada para ser **fluida, intuitiva y accesible**, garantizando una experiencia clara tanto en la **Landing Page** como en la **Web Application**.

#### 1. Navegación en la Landing Page

La **página principal** guía a nuevos usuarios de manera sencilla hacia el registro y la información clave del producto, combinando estética y usabilidad.

**Elementos principales de navegación:**
- **Menú de navegación superior (con iconos):**
  - *Home*  
  - *About*  
  - *Services*  
  - *How it works*  
  - *Plans & Pricing*  
  - *Reviews*  
  - *Contact us*
- **Call To Actions (CTAs):**
  - Ejemplo: *"Sign up now"*, *"Get started"*.
- **Desplazamiento fluido:**
  - Scroll natural por secciones sin necesidad de recargar la página. 

#### 2. Navegación en la Web Application

La navegación se adapta al **tipo de usuario** y sus funcionalidades más relevantes.

#### Para Representantes del Hogar:

**Menú lateral fijo con opciones:**
- Dashboard  
- Miembros del hogar  
- Gastos  
- Aportes  
- Configuración del hogar  

**Breadcrumbs (migas de pan):**  
Permiten volver fácilmente a secciones anteriores o más generales.

#### Para Miembros del Hogar:

**Menú superior simplificado con opciones:**
- Dashboard  
- Aportes  
- Estado del hogar  
- Unirse mediante ID de hogar  

**Accesos rápidos (botones flotantes):**
- Agregar aporte  
- Ver detalles del gasto  

#### Interacción con el sistema 

- **Accesibilidad:** Navegación clara, visible y con etiquetas comprensibles para todo tipo de usuarios.  
- **Navegación de búsqueda:** Accesos rápidos para filtrar por ID de hogar, estado de aportes o categorías de gastos.  
- **Soporte y ayuda:** Sección de tutoriales y guías interactivas paso a paso, integradas dentro de la aplicación.  

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level EventStorming.
### 4.6.2. Software Architecture Context Diagram.
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams