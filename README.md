<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Informe de Apps Web — UPC</title>
  <style>
    :root{
      --brand:#1565c0;
      --accent:#ff6f00;
      --text:#222;
      --muted:#666;
      --border:#e5e7eb;
      --bg:#fafafa;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif;
      line-height:1.6;
      color:var(--text);
      background:var(--bg);
    }
    .container{
      width:min(1100px, 92vw);
      margin:0 auto;
      padding:2rem 0 4rem;
    }
    header.cover{
      background:white;
      border:1px solid var(--border);
      border-radius:14px;
      padding:2rem;
      margin:2rem auto;
      box-shadow:0 6px 30px rgba(0,0,0,.05);
    }
    .upc{font-size:1.1rem; letter-spacing:.2px; color:var(--muted)}
    .title{
      margin:.5rem 0 0;
      font-size:1.75rem;
      font-weight:800;
      color:#111;
    }
    .meta{display:grid; gap:.5rem; margin-top:1rem; color:#111}
    .meta b{color:#111}
    .grid-2{display:grid; grid-template-columns:1fr 1fr; gap:1rem}
    .muted{color:var(--muted)}
    .pill{
      display:inline-block; background:rgba(21,101,192,.08);
      color:var(--brand); border:1px solid rgba(21,101,192,.2);
      font-weight:600; padding:.2rem .5rem; border-radius:999px;
    }
    .toc{
      background:white;
      border:1px solid var(--border);
      border-radius:14px;
      padding:1.25rem 1.25rem 1rem;
      margin:2rem 0;
    }
    .toc h2{margin:0 0 .5rem; font-size:1.15rem; color:#111}
    .toc ol{margin:.25rem 0 0 1rem; padding:0}
    .toc a{color:var(--brand); text-decoration:none}
    .toc a:hover{ text-decoration:underline }
    section{
      background:white;
      border:1px solid var(--border);
      border-radius:14px;
      padding:1.25rem 1.25rem 1rem;
      margin:1rem 0 1.25rem;
    }
    h2{margin:.2rem 0 1rem; font-size:1.35rem; color:#111}
    h3{margin:1rem 0 .25rem; font-size:1.1rem; color:#111}
    h4{margin:.75rem 0 .25rem; font-size:1rem; color:#111}
    ul,ol{margin:.25rem 0 .75rem 1.25rem}
    table{width:100%; border-collapse:collapse; margin:.5rem 0 .25rem}
    th,td{border:1px solid var(--border); padding:.6rem .5rem; vertical-align:top}
    th{background:#f5f7fb; text-align:left}
    footer{color:var(--muted); font-size:.9rem; margin-top:2rem; text-align:center}
    .placeholder{color:#9aa1ab; font-style:italic}
  </style>
</head>
<body>
  <div class="container">
    <header class="cover">
      <div class="upc">Universidad Peruana de Ciencias Aplicadas</div>
      <div class="title">Aplicaciones Web – 7432 <span class="pill">Ciclo 2025-02</span></div>
      <div class="meta grid-2">
        <div><b>Docente:</b> Villafuerte Bazán, Óscar Iván</div>
        <div><b>Fecha:</b> Septiembre, 2025</div>
        <div><b>Startup:</b> <span class="placeholder">[Nombre de la startup]</span></div>
        <div><b>Producto:</b> <span class="placeholder">[Nombre del producto]</span></div>
      </div>
      <div style="margin-top:1rem">
        <b>Integrantes:</b>
        <ul>
          <li class="placeholder">[Integrante 1]</li>
          <li class="placeholder">[Integrante 2]</li>
          <li class="placeholder">[Integrante 3]</li>
          <li class="placeholder">[Integrante 4]</li>
          <li>Córdova Valdivia Sebastián — U202111041</li>
        </ul>
      </div>
    </header>

    <nav class="toc" aria-label="Tabla de contenidos">
      <h2>Tabla de Contenidos</h2>
      <ol>
        <li><a href="#cap1">Capítulo I: Introducción</a>
          <ol>
            <li><a href="#1-1">1.1. Startup Profile</a>
              <ol>
                <li><a href="#1-1-1">1.1.1. Descripción de la Startup</a></li>
                <li><a href="#1-1-2">1.1.2. Perfiles de integrantes del equipo</a></li>
              </ol>
            </li>
            <li><a href="#1-2">1.2. Solution Profile</a>
              <ol>
                <li><a href="#1-2-1">1.2.1. Nombre del producto</a></li>
                <li><a href="#1-2-2">1.2.2. Antecedentes y problemática</a></li>
                <li><a href="#1-2-3">1.2.3. Lean UX Process</a>
                  <ol>
                    <li><a href="#1-2-3-1">1.2.3.1. Lean UX Problem Statements</a></li>
                    <li><a href="#1-2-3-2">1.2.3.2. Lean UX Assumptions</a></li>
                    <li><a href="#1-2-3-3">1.2.3.3. Lean UX Hypothesis Statements</a></li>
                    <li><a href="#1-2-3-4">1.2.3.4. Lean UX Canvas</a></li>
                  </ol>
                </li>
              </ol>
            </li>
            <li><a href="#1-3">1.3. Segmentos objetivo</a></li>
          </ol>
        </li>

        <li><a href="#cap2">Capítulo II: Requirements Elicitation &amp; Analysis</a>
          <ol>
            <li><a href="#2-1">2.1. Competidores</a>
              <ol>
                <li><a href="#2-1-1">2.1.1. Análisis competitivo</a></li>
                <li><a href="#2-1-2">2.1.2. Estrategias y tácticas frente a competidores</a></li>
              </ol>
            </li>
            <li><a href="#2-2">2.2. Entrevistas</a>
              <ol>
                <li><a href="#2-2-1">2.2.1. Diseño de entrevistas</a></li>
                <li><a href="#2-2-2">2.2.2. Registro de entrevistas</a></li>
                <li><a href="#2-2-3">2.2.3. Análisis de entrevistas</a></li>
              </ol>
            </li>
            <li><a href="#2-3">2.3. Needfinding</a>
              <ol>
                <li><a href="#2-3-1">2.3.1. User Personas</a></li>
                <li><a href="#2-3-2">2.3.2. User Task Matrix</a></li>
                <li><a href="#2-3-3">2.3.3. User Journey Mapping</a></li>
                <li><a href="#2-3-4">2.3.4. Empathy Mapping</a></li>
                <li><a href="#2-3-5">2.3.5. As-is Scenario Mapping</a></li>
              </ol>
            </li>
            <li><a href="#2-4">2.4. Ubiquitous Language</a></li>
          </ol>
        </li>

        <li><a href="#cap3">Capítulo III: Requirements Specification</a>
          <ol>
            <li><a href="#3-1">3.1. To-Be Scenario Mapping</a></li>
            <li><a href="#3-2">3.2. User Stories</a></li>
            <li><a href="#3-3">3.3. Impact Mapping</a></li>
            <li><a href="#3-4">3.4. Product Backlog</a></li>
          </ol>
        </li>

        <li><a href="#cap4">Capítulo IV: Product Design</a>
          <ol>
            <li><a href="#4-1">4.1. Style Guidelines</a>
              <ol>
                <li><a href="#4-1-1">4.1.1. General Style Guidelines</a></li>
                <li><a href="#4-1-2">4.1.2. Web Style Guidelines</a></li>
              </ol>
            </li>
            <li><a href="#4-2">4.2. Information Architecture</a>
              <ol>
                <li><a href="#4-2-1">4.2.1. Organization Systems</a></li>
                <li><a href="#4-2-2">4.2.2. Labeling Systems</a></li>
                <li><a href="#4-2-3">4.2.3. SEO Tags and Meta Tags</a></li>
                <li><a href="#4-2-4">4.2.4. Searching Systems</a></li>
                <li><a href="#4-2-5">4.2.5. Navigation Systems</a></li>
              </ol>
            </li>
            <li><a href="#4-3">4.3. Landing Page UI Design</a>
              <ol>
                <li><a href="#4-3-1">4.3.1. Landing Page Wireframe</a></li>
                <li><a href="#4-3-2">4.3.2. Landing Page Mock-up</a></li>
              </ol>
            </li>
            <li><a href="#4-4">4.4. Web Applications UX/UI Design</a>
              <ol>
                <li><a href="#4-4-1">4.4.1. Web Applications Wireframes</a></li>
                <li><a href="#4-4-2">4.4.2. Web Applications Wireflow Diagrams</a></li>
                <li><a href="#4-4-3">4.4.2. Web Applications Mock-ups</a></li>
                <li><a href="#4-4-4">4.4.3. Web Applications User Flow Diagrams</a></li>
              </ol>
            </li>
            <li><a href="#4-5">4.5. Web Applications Prototyping</a></li>
            <li><a href="#4-6">4.6. Domain-Driven Software Architecture</a>
              <ol>
                <li><a href="#4-6-1">4.6.1. Software Architecture Context Diagram</a></li>
                <li><a href="#4-6-2">4.6.2. Software Architecture Container Diagrams</a></li>
                <li><a href="#4-6-3">4.6.3. Software Architecture Components Diagrams</a></li>
              </ol>
            </li>
            <li><a href="#4-7">4.7. Software Object-Oriented Design</a>
              <ol>
                <li><a href="#4-7-1">4.7.1. Class Diagrams</a></li>
                <li><a href="#4-7-2">4.7.2. Class Dictionary</a></li>
              </ol>
            </li>
            <li><a href="#4-8">4.8. Database Design</a>
              <ol>
                <li><a href="#4-8-1">4.8.1. Database Diagram</a></li>
              </ol>
            </li>
          </ol>
        </li>

        <li><a href="#cap5">Capítulo V: Product Implementation, Validation &amp; Deployment</a>
          <ol>
            <li><a href="#5-1">5.1. Software Configuration Management</a>
              <ol>
                <li><a href="#5-1-1">5.1.1. Software Development Environment Configuration</a></li>
                <li><a href="#5-1-2">5.1.2. Source Code Management</a></li>
                <li><a href="#5-1-3">5.1.3. Source Code Style Guide &amp; Conventions</a></li>
                <li><a href="#5-1-4">5.1.4. Software Deployment Configuration</a></li>
              </ol>
            </li>
            <li><a href="#5-2">5.2. Landing Page, Services &amp; Applications Implementation</a>
              <ol>
                <li><a href="#5-2-x">5.2.X. Sprint n</a>
                  <ol>
                    <li><a href="#5-2-x-1">5.2.X.1. Sprint Planning n</a></li>
                    <li><a href="#5-2-x-2">5.2.X.2. Aspect Leaders and Collaborators</a></li>
                    <li><a href="#5-2-x-3">5.2.X.3. Sprint Backlog n</a></li>
                    <li><a href="#5-2-x-4">5.2.X.4. Development Evidence for Sprint Review</a></li>
                    <li><a href="#5-2-x-5">5.2.X.5. Execution Evidence for Sprint Review</a></li>
                    <li><a href="#5-2-x-6">5.2.X.6. Services Documentation Evidence for Sprint Review</a></li>
                    <li><a href="#5-2-x-7">5.2.X.7. Software Deployment Evidence for Sprint Review</a></li>
                    <li><a href="#5-2-x-8">5.2.X.8. Team Collaboration Insights during Sprint</a></li>
                  </ol>
                </li>
              </ol>
            </li>
          </ol>
        </li>
      </ol>
    </nav>

    <section id="cap1">
      <h2>Capítulo I: Introducción</h2>
      <section id="1-1">
        <h3>1.1. Startup Profile</h3>
        <section id="1-1-1"><h4>1.1.1. Descripción de la Startup</h4><p class="placeholder">[Describa la startup, su misión y propuesta de valor.]</p></section>
        <section id="1-1-2"><h4>1.1.2. Perfiles de integrantes del equipo</h4><p class="placeholder">[Roles, experiencia y responsabilidades de cada integrante.]</p></section>
      </section>
      <section id="1-2">
        <h3>1.2. Solution Profile</h3>
        <section id="1-2-1"><h4>1.2.1. Nombre del producto</h4><p class="placeholder">[Nombre y breve slogan.]</p></section>
        <section id="1-2-2"><h4>1.2.2. Antecedentes y problemática</h4><p class="placeholder">[Contexto, problema y evidencias.]</p></section>
        <section id="1-2-3">
          <h4>1.2.3. Lean UX Process</h4>
          <section id="1-2-3-1"><h4>1.2.3.1. Lean UX Problem Statements</h4><p class="placeholder">[Problemas clave del usuario]</p></section>
          <section id="1-2-3-2"><h4>1.2.3.2. Lean UX Assumptions</h4><p class="placeholder">[Suposiciones sobre usuarios, soluciones y resultados]</p></section>
          <section id="1-2-3-3"><h4>1.2.3.3. Lean UX Hypothesis Statements</h4><p class="placeholder">[Hipótesis medibles]</p></section>
          <section id="1-2-3-4"><h4>1.2.3.4. Lean UX Canvas</h4><p class="placeholder">[Canvas resumido]</p></section>
        </section>
      </section>
      <section id="1-3"><h3>1.3. Segmentos objetivo</h3><p class="placeholder">[Segmentación y perfiles de cliente objetivo]</p></section>
    </section>

    <section id="cap2">
      <h2>Capítulo II: Requirements Elicitation &amp; Analysis</h2>
      <section id="2-1">
        <h3>2.1. Competidores</h3>
        <section id="2-1-1"><h4>2.1.1. Análisis competitivo</h4><p class="placeholder">[Benchmarking y hallazgos]</p></section>
        <section id="2-1-2"><h4>2.1.2. Estrategias y tácticas frente a competidores</h4><p class="placeholder">[Estrategias de diferenciación]</p></section>
      </section>
      <section id="2-2">
        <h3>2.2. Entrevistas</h3>
        <section id="2-2-1"><h4>2.2.1. Diseño de entrevistas</h4><p class="placeholder">[Guión y objetivos]</p></section>
        <section id="2-2-2"><h4>2.2.2. Registro de entrevistas</h4><p class="placeholder">[Muestras y citas]</p></section>
        <section id="2-2-3"><h4>2.2.3. Análisis de entrevistas</h4><p class="placeholder">[Patrones, insights y oportunidades]</p></section>
      </section>
      <section id="2-3">
        <h3>2.3. Needfinding</h3>
        <section id="2-3-1"><h4>2.3.1. User Personas</h4><p class="placeholder">[Personas representativas]</p></section>
        <section id="2-3-2"><h4>2.3.2. User Task Matrix</h4><p class="placeholder">[Tareas vs. frecuencia/criticidad]</p></section>
        <section id="2-3-3"><h4>2.3.3. User Journey Mapping</h4><p class="placeholder">[Etapas y puntos de dolor]</p></section>
        <section id="2-3-4"><h4>2.3.4. Empathy Mapping</h4><p class="placeholder">[Dice, Piensa, Hace, Siente]</p></section>
        <section id="2-3-5"><h4>2.3.5. As-is Scenario Mapping</h4><p class="placeholder">[Flujo actual]</p></section>
      </section>
      <section id="2-4"><h3>2.4. Ubiquitous Language</h3><p class="placeholder">[Glosario común del dominio]</p></section>
    </section>

    <section id="cap3">
      <h2>Capítulo III: Requirements Specification</h2>
      <section id="3-1"><h3>3.1. To-Be Scenario Mapping</h3><p class="placeholder">[Flujo futuro]</p></section>
      <section id="3-2"><h3>3.2. User Stories</h3><p class="placeholder">[Historias en formato: Como &lt;rol&gt; quiero &lt;acción&gt; para &lt;beneficio&gt;]</p></section>
      <section id="3-3"><h3>3.3. Impact Mapping</h3><p class="placeholder">[Objetivo → Actores → Impactos → Entregables]</p></section>
      <section id="3-4"><h3>3.4. Product Backlog</h3><p class="placeholder">[Backlog priorizado]</p></section>
    </section>

    <section id="cap4">
      <h2>Capítulo IV: Product Design</h2>
      <section id="4-1">
        <h3>4.1. Style Guidelines</h3>
        <section id="4-1-1"><h4>4.1.1. General Style Guidelines</h4><p class="placeholder">[Tipografías, colores, espaciado]</p></section>
        <section id="4-1-2"><h4>4.1.2. Web Style Guidelines</h4><p class="placeholder">[Componentes, estados y accesibilidad]</p></section>
      </section>
      <section id="4-2">
        <h3>4.2. Information Architecture</h3>
        <section id="4-2-1"><h4>4.2.1. Organization Systems</h4><p class="placeholder">[Estructura de contenidos]</p></section>
        <section id="4-2-2"><h4>4.2.2. Labeling Systems</h4><p class="placeholder">[Nomenclatura]</p></section>
        <section id="4-2-3"><h4>4.2.3. SEO Tags and Meta Tags</h4><p class="placeholder">[Title, meta description, Open Graph]</p></section>
        <section id="4-2-4"><h4>4.2.4. Searching Systems</h4><p class="placeholder">[Estrategias de búsqueda]</p></section>
        <section id="4-2-5"><h4>4.2.5. Navigation Systems</h4><p class="placeholder">[Menús, migas, atajos]</p></section>
      </section>
      <section id="4-3">
        <h3>4.3. Landing Page UI Design</h3>
        <section id="4-3-1"><h4>4.3.1. Landing Page Wireframe</h4><p class="placeholder">[Wireframe de la landing]</p></section>
        <section id="4-3-2"><h4>4.3.2. Landing Page Mock-up</h4><p class="placeholder">[Mockups de alta fidelidad]</p></section>
      </section>
      <section id="4-4">
        <h3>4.4. Web Applications UX/UI Design</h3>
        <section id="4-4-1"><h4>4.4.1. Web Applications Wireframes</h4><p class="placeholder">[Wireframes por módulo]</p></section>
        <section id="4-4-2"><h4>4.4.2. Web Applications Wireflow Diagrams</h4><p class="placeholder">[Flujos con pantallas]</p></section>
        <section id="4-4-3"><h4>4.4.2. Web Applications Mock-ups</h4><p class="placeholder">[Mockups finales]</p></section>
        <section id="4-4-4"><h4>4.4.3. Web Applications User Flow Diagrams</h4><p class="placeholder">[Flujos de usuario]</p></section>
      </section>
      <section id="4-5"><h3>4.5. Web Applications Prototyping</h3><p class="placeholder">[Prototipo navegable]</p></section>
      <section id="4-6">
        <h3>4.6. Domain-Driven Software Architecture</h3>
        <section id="4-6-1"><h4>4.6.1. Software Architecture Context Diagram</h4><p class="placeholder">[Contexto del sistema]</p></section>
        <section id="4-6-2"><h4>4.6.2. Software Architecture Container Diagrams</h4><p class="placeholder">[Contenedores]</p></section>
        <section id="4-6-3"><h4>4.6.3. Software Architecture Components Diagrams</h4><p class="placeholder">[Componentes]</p></section>
      </section>
      <section id="4-7">
        <h3>4.7. Software Object-Oriented Design</h3>
        <section id="4-7-1"><h4>4.7.1. Class Diagrams</h4><p class="placeholder">[Diagrama de clases]</p></section>
        <section id="4-7-2"><h4>4.7.2. Class Dictionary</h4><p class="placeholder">[Diccionario de clases]</p></section>
      </section>
      <section id="4-8">
        <h3>4.8. Database Design</h3>
        <section id="4-8-1"><h4>4.8.1. Database Diagram</h4><p class="placeholder">[Modelo ER/Relacional]</p></section>
      </section>
    </section>

    <section id="cap5">
      <h2>Capítulo V: Product Implementation, Validation &amp; Deployment</h2>
      <section id="5-1">
        <h3>5.1. Software Configuration Management</h3>
        <section id="5-1-1"><h4>5.1.1. Software Development Environment Configuration</h4><p class="placeholder">[Stack, IDE, dependencias]</p></section>
        <section id="5-1-2"><h4>5.1.2. Source Code Management</h4><p class="placeholder">[Estrategia Git, ramas y PRs]</p></section>
        <section id="5-1-3"><h4>5.1.3. Source Code Style Guide &amp; Conventions</h4><p class="placeholder">[Linter, formateo y guías]</p></section>
        <section id="5-1-4"><h4>5.1.4. Software Deployment Configuration</h4><p class="placeholder">[CI/CD y ambientes]</p></section>
      </section>
      <section id="5-2">
        <h3>5.2. Landing Page, Services &amp; Applications Implementation</h3>
        <section id="5-2-x">
          <h4>5.2.X. Sprint n</h4>
          <section id="5-2-x-1"><h4>5.2.X.1. Sprint Planning n</h4><p class="placeholder">[Objetivos, alcance y capacidades]</p></section>
          <section id="5-2-x-2"><h4>5.2.X.2. Aspect Leaders and Collaborators</h4><p class="placeholder">[Responsables por aspecto]</p></section>
          <section id="5-2-x-3"><h4>5.2.X.3. Sprint Backlog n</h4><p class="placeholder">[Historias y tareas del sprint]</p></section>
          <section id="5-2-x-4"><h4>5.2.X.4. Development Evidence for Sprint Review</h4><p class="placeholder">[Commits, PRs, capturas]</p></section>
          <section id="5-2-x-5"><h4>5.2.X.5. Execution Evidence for Sprint Review</h4><p class="placeholder">[Evidencia de ejecución]</p></section>
          <section id="5-2-x-6"><h4>5.2.X.6. Services Documentation Evidence for Sprint Review</h4><p class="placeholder">[APIs/Servicios documentados]</p></section>
          <section id="5-2-x-7"><h4>5.2.X.7. Software Deployment Evidence for Sprint Review</h4><p class="placeholder">[Despliegues y releases]</p></section>
          <section id="5-2-x-8"><h4>5.2.X.8. Team Collaboration Insights during Sprint</h4><p class="placeholder">[Reflexiones y mejoras]</p></section>
        </section>
      </section>
    </section>

    <section id="student-outcome">
      <h2>STUDENT OUTCOME</h2>
      <table>
        <thead>
          <tr>
            <th>Criterio específico</th>
            <th>Acciones realizadas</th>
            <th>Conclusiones</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="placeholder">[Defina el criterio]</td>
            <td class="placeholder">[Acciones o evidencias]</td>
            <td class="placeholder">[Conclusiones y lecciones]</td>
          </tr>
        </tbody>
      </table>
    </section>

    <footer>Plantilla HTML generada a partir del documento original. Edite los campos <span class="placeholder">[entre corchetes]</span> para completar su informe.</footer>
  </div>
</body>
</html>