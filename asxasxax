<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CROODA — El trabajo en 2037 no desaparece: pierde definición</title>
<style>
  *{box-sizing:border-box;margin:0;padding:0}
  :root{
    --bg:#ffffff;--bg2:#f5f5f3;--bg3:#eeece8;
    --text:#1a1a1a;--text2:#555;--text3:#888;
    --border:rgba(0,0,0,0.12);--border2:rgba(0,0,0,0.2);
    --radius:8px;--radius-lg:12px;
    --font:system-ui,-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;
  }
  @media(prefers-color-scheme:dark){
    :root{
      --bg:#1c1c1e;--bg2:#2c2c2e;--bg3:#3a3a3c;
      --text:#f2f2f7;--text2:#aeaeb2;--text3:#636366;
      --border:rgba(255,255,255,0.1);--border2:rgba(255,255,255,0.2);
    }
    .tag-c{background:#083d2b!important;color:#5dcaa5!important}
    .tag-e{background:#2a2660!important;color:#afa9ec!important}
    .tag-i{background:#3d2800!important;color:#ef9f27!important}
  }
  body{font-family:var(--font);background:var(--bg);color:var(--text);line-height:1.6}
  .container{max-width:1200px;margin:0 auto;padding:2rem 1.5rem}
  .cover{text-align:center;padding:3rem 1rem 2rem;border-bottom:0.5px solid var(--border);margin-bottom:2rem}
  .cover-tag{font-size:11px;letter-spacing:.1em;color:var(--text3);text-transform:uppercase;margin-bottom:.6rem}
  .cover-title{font-size:26px;font-weight:500;color:var(--text);margin-bottom:.5rem}
  .cover-sub{font-size:15px;color:var(--text2)}
  .tabs{display:flex;gap:8px;border-bottom:0.5px solid var(--border);margin-bottom:2rem}
  .tab{padding:10px 18px;font-size:13px;cursor:pointer;border:none;background:none;color:var(--text2);border-bottom:2px solid transparent;margin-bottom:-0.5px;font-family:var(--font)}
  .tab.active{color:var(--text);border-bottom-color:var(--text);font-weight:500}
  .tab:hover:not(.active){color:var(--text)}
  .section{display:none}.section.active{display:block}

  /* tabla */
  .tbl-wrap{overflow-x:auto;border:0.5px solid var(--border);border-radius:var(--radius-lg)}
  table{width:100%;border-collapse:collapse;font-size:12px}
  th{background:var(--bg2);font-weight:500;font-size:11px;color:var(--text2);text-align:left;padding:10px 12px;white-space:nowrap;border-bottom:0.5px solid var(--border);position:sticky;top:0;z-index:1}
  td{padding:9px 12px;border-bottom:0.5px solid var(--border);vertical-align:top;color:var(--text);line-height:1.5;min-width:130px;max-width:210px}
  tr:last-child td{border-bottom:none}
  tr:hover td{background:var(--bg2)}
  .tag{display:inline-block;padding:2px 8px;border-radius:999px;font-size:11px;font-weight:500;white-space:nowrap}
  .tag-c{background:#E1F5EE;color:#0F6E56}
  .tag-e{background:#EEEDFE;color:#3C3489}
  .tag-i{background:#FAEEDA;color:#633806}
  .prob{font-size:11px;color:var(--text2)}
  .nota{font-size:11px;color:var(--text3);font-style:italic}
  .tema{font-weight:500;color:var(--text);min-width:170px}

  /* reporte */
  .rpt{max-width:700px;margin:0 auto}
  .section-num{font-size:11px;color:var(--text3);font-weight:500;margin-bottom:.25rem;letter-spacing:.05em}
  .sec-title{font-size:18px;font-weight:500;color:var(--text);margin-bottom:.6rem}
  .sec-body{font-size:14px;color:var(--text2);line-height:1.8;margin-bottom:1.75rem}
  .divider{border:none;border-top:0.5px solid var(--border);margin:1.75rem 0}
  .tensions{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px;margin:1rem 0 1.75rem}
  .tension-card{background:var(--bg2);border-radius:var(--radius);padding:.9rem 1rem}
  .tension-title{font-size:12px;font-weight:500;color:var(--text);margin-bottom:.3rem}
  .tension-body{font-size:12px;color:var(--text2);line-height:1.6}
  .shift-row{display:flex;gap:1rem;margin:1rem 0 1.75rem;align-items:flex-start;flex-wrap:wrap}
  .shift-box{flex:1;min-width:120px;background:var(--bg2);border-radius:var(--radius);padding:.8rem 1rem}
  .shift-label{font-size:10px;text-transform:uppercase;letter-spacing:.07em;color:var(--text3);margin-bottom:.5rem}
  .shift-item{font-size:13px;color:var(--text2);padding:2px 0}
  .arrow-mid{display:flex;align-items:center;font-size:22px;color:var(--text3);padding-top:1.8rem}
  .close-box{background:var(--bg2);border-radius:var(--radius-lg);padding:1.25rem 1.5rem;border-left:3px solid #7F77DD;margin-top:1rem}
  .close-q{font-size:14px;font-style:italic;color:var(--text);line-height:1.8}

  footer{text-align:center;padding:2rem 1rem;margin-top:3rem;border-top:0.5px solid var(--border);font-size:12px;color:var(--text3)}
</style>
</head>
<body>
<div class="container">

<div class="cover">
  <div class="cover-tag">CROODA — Señales del futuro del trabajo</div>
  <div class="cover-title">El trabajo en 2037 no desaparece: pierde definición</div>
  <div class="cover-sub">16 señales analizadas · Horizontes 0–24m / 2–5a / 5–10a</div>
</div>

<div class="tabs">
  <button class="tab active" onclick="showTab('tabla',this)">Tabla de señales</button>
  <button class="tab" onclick="showTab('reporte',this)">Reporte narrativo</button>
</div>

<div id="tabla" class="section active">
  <div class="tbl-wrap">
    <table>
      <thead>
        <tr>
          <th>Tema / señal</th><th>Estado</th><th>Dominio</th><th>Grado de madurez</th>
          <th>Evidencia observable</th><th>Calidad</th><th>Riesgo / fricción</th>
          <th>Potencial</th><th>Condiciones</th><th>Probabilidad</th>
          <th>Oportunidad 2ª capa</th><th>Nota CROODA</th>
        </tr>
      </thead>
      <tbody id="tbody"></tbody>
    </table>
  </div>
</div>

<div id="reporte" class="section">
  <div class="rpt">

    <div class="section-num">01</div>
    <div class="sec-title">Planteamiento inicial</div>
    <div class="sec-body">Cuando se habla de inteligencia artificial y trabajo, la conversación tiende a ir siempre al mismo lugar: que la IA va a reemplazar empleos. Esa idea tiene algo de verdad, pero se queda corta. No está mal; simplemente no alcanza a capturar lo que ya se está comenzando a observar. Porque si uno analiza cómo están cambiando los entornos de trabajo hoy, no es tanto que el trabajo desaparezca de un momento a otro, sino que sigue ahí... pero empieza a perder forma. Uno sigue trabajando, sigue produciendo, pero cada vez resulta menos claro qué parte del proceso depende realmente de uno. Ese matiz cambia completamente cómo se entiende la utilidad dentro del sistema.</div>

    <hr class="divider">

    <div class="section-num">02</div>
    <div class="sec-title">De tareas a flujos completos</div>
    <div class="sec-body">Antes, el trabajo estaba organizado en tareas relativamente claras: escribir un informe, analizar datos, responder correos, tomar decisiones específicas. Mejorar significaba hacer esas tareas más rápido o con mayor precisión. Pero ese esquema empieza a moverse. No es que la IA simplemente ayude con tareas puntuales; cada vez más interviene en flujos completos de trabajo: no solo ejecuta partes, sino que conecta pasos, anticipa resultados y entrega soluciones casi terminadas. Y ahí aparece una fricción que antes no era tan evidente: si se interviene, se pierde velocidad; si no se interviene, se pierde profundidad.</div>

    <hr class="divider">

    <div class="section-num">03</div>
    <div class="sec-title">La erosión del valor de la ejecución</div>
    <div class="sec-body">Históricamente, el valor profesional estaba muy ligado a la capacidad de ejecución: hacer más, hacer mejor, hacer más rápido. Pero cuando la ejecución se automatiza, deja de ser escasa. Y cuando algo deja de ser escaso, pierde valor relativo. El problema cambia de naturaleza: ya no es "¿cómo hago esto mejor?", sino algo más incómodo: ¿qué vale la pena hacer en primer lugar? Si una herramienta puede escribir un documento completo en segundos, el aporte ya no está en escribirlo, sino en decidir si ese documento tiene sentido, si está bien enfocado o si siquiera debía producirse.</div>

    <hr class="divider">

    <div class="section-num">04</div>
    <div class="sec-title">De asistencia a anticipación</div>
    <div class="sec-body">Otro cambio relevante es que la IA no solo ejecuta, sino que empieza a anticipar. Sugiere decisiones completas, recomienda acciones antes de que el usuario las solicite y reduce la necesidad de input explícito. Esto transforma la dinámica del trabajo: ya no se toman únicamente decisiones propias, sino que se reacciona a decisiones propuestas. Eso genera una tensión constante: aceptar la sugerencia implica eficiencia, pero también implica delegar criterio. La decisión no desaparece; se desplaza.</div>

    <hr class="divider">

    <div class="section-num">05</div>
    <div class="sec-title">Fragmentación del trabajo y pérdida de rol</div>
    <div class="sec-body">En paralelo, los roles tradicionales empiezan a fragmentarse. Es cada vez más común trabajar por proyectos, asumir múltiples funciones y operar en entornos menos definidos. Esto genera flexibilidad, pero también introduce incertidumbre. Porque sí, se pueden hacer más cosas que antes... pero eso no necesariamente implica ser más necesario. De hecho, puede ocurrir lo contrario: que cada contribución individual pese menos dentro del sistema. No se pierde capacidad; se pierde centralidad.</div>

    <hr class="divider">

    <div class="section-num">06</div>
    <div class="sec-title">Medición constante y presión estructural</div>
    <div class="sec-body">A esto se suma una capa adicional: la medición. Cada vez más, el trabajo es monitoreado, cuantificado y comparado —no solo entre personas, sino también frente a sistemas automatizados. Entonces ya no basta con cumplir funciones. Existe una presión constante por demostrar valor en términos medibles, lo que cambia la forma en que las personas se posicionan dentro de su propio trabajo. No es solo "hacer bien el trabajo"; es justificar continuamente por qué ese trabajo requiere intervención humana.</div>

    <hr class="divider">

    <div class="section-num">07</div>
    <div class="sec-title">La tensión central del sistema</div>
    <div class="tensions">
      <div class="tension-card"><div class="tension-title">Eficiencia vs. criterio</div><div class="tension-body">Delegar aumenta la velocidad, pero puede erosionar la capacidad de juicio.</div></div>
      <div class="tension-card"><div class="tension-title">Versatilidad vs. irrelevancia</div><div class="tension-body">Hacer de todo no garantiza que alguien dependa de uno.</div></div>
      <div class="tension-card"><div class="tension-title">Automatización vs. identidad</div><div class="tension-body">El rol deja de ser estable y se vuelve dinámico, o incluso difuso.</div></div>
    </div>

    <hr class="divider">

    <div class="section-num">08</div>
    <div class="sec-title">Desplazamiento del valor</div>
    <div class="shift-row">
      <div class="shift-box"><div class="shift-label">Antes</div><div class="shift-item">Ejecutar</div><div class="shift-item">Producir</div><div class="shift-item">Responder</div></div>
      <div class="arrow-mid">→</div>
      <div class="shift-box"><div class="shift-label">Ahora</div><div class="shift-item">Decidir</div><div class="shift-item">Priorizar</div><div class="shift-item">Definir problemas</div></div>
    </div>
    <div class="sec-body">El valor no desaparece, pero se desplaza. El obstáculo es que estas capacidades no son tan visibles ni tan fáciles de medir como la ejecución. Tampoco están completamente integradas en los sistemas de formación tradicionales.</div>

    <hr class="divider">

    <div class="section-num">09</div>
    <div class="sec-title">Implicación práctica</div>
    <div class="sec-body">Aprender a usar herramientas de IA es necesario, sí. Pero no constituye una ventaja diferencial; es una condición base. Es equivalente a dominar herramientas digitales en etapas anteriores: imprescindible, pero insuficiente. Lo que empieza a diferenciar es algo más difícil de capturar: qué se decide hacer, qué se decide ignorar, cuándo se interviene y cuándo no. Es decir, criterio aplicado en contexto.</div>

    <hr class="divider">

    <div class="section-num">10</div>
    <div class="sec-title">Cierre operativo</div>
    <div class="sec-body">El problema no es simplemente adaptarse a nuevas herramientas. Es entender cuál es la función real que se ocupa dentro de un sistema donde la mayoría de las acciones ya pueden ser ejecutadas o incluso sugeridas por otros medios. Porque si esa función no está clara, el sistema tiende a optimizar por eficiencia... no necesariamente por aporte humano significativo.</div>
    <div class="close-box">
      <div class="close-q">Si desaparece lo que se hace hoy —no solo la herramienta, sino el rol completo—, ¿qué parte del aporte sigue teniendo sentido dentro de ese entorno?<br><br>Ahí es donde realmente empieza a cambiar todo.</div>
    </div>

  </div>
</div>

<footer>CROODA · Reporte de señales · 2025</footer>

</div>
<script>
const DATA=[
  ["Copilotos de IA integrados en workflows laborales","Consolidado","Productividad / conocimiento","Adopción temprana (2022) → estándar en suites (2024–2026)","Integración en suites empresariales (Microsoft 365 Copilot, Google Workspace AI)","Alta","Dependencia tecnológica, reducción de habilidades base","Escala vía integración total en software de trabajo","Infraestructura cloud + adopción empresarial","Alta / Alta / Alta","Auditoría de decisiones asistidas","Hipótesis: degradación de habilidades base → medir rendimiento sin IA"],
  ["Automatización de flujos completos (no tareas)","Emergente","Operaciones / procesos","De automatización parcial a agentes que ejecutan pipelines completos","Casos de RPA + AI agents en empresas (UiPath, AutoGPT derivados)","Media","Fallos sistémicos, opacidad operativa","Escala con agentes autónomos coordinados","Interoperabilidad entre sistemas","Media / Alta / Alta","Orquestadores de agentes","Hipótesis: % de tareas humanas reducidas >50% en roles operativos"],
  ["Agentes autónomos con capacidad de decisión","Emergente","Toma de decisiones","De prototipos a despliegues controlados","Papers sobre agentic AI + implementaciones en entornos sandbox","Media","Riesgo legal, responsabilidad difusa","Sustitución parcial de decisiones humanas","Marcos regulatorios claros","Baja / Media / Alta","Supervisión de decisiones AI","Hipótesis: humanos pasan a rol de validación, no ejecución"],
  ["Interfaces predictivas (anticipación de tareas)","Emergente","UX / productividad","De recomendación a anticipación activa","Sistemas predictivos en CRM, IDEs, asistentes personales","Media","Pérdida de autonomía, sesgos","Reducción de fricción cognitiva","Datos masivos + modelos contextuales","Media / Alta / Alta","Diseño de intención humana","Hipótesis: reducción del input humano explícito"],
  ["Medición granular del desempeño","Emergente","Gestión / RRHH","De KPIs generales a seguimiento en tiempo real","Software de productivity tracking + analytics","Media","Rechazo social, vigilancia laboral","Optimización extrema del rendimiento","Aceptación cultural + regulación","Media / Alta / Alta","Mercado de reputación profesional","Hipótesis: scoring laboral continuo se normaliza"],
  ["Fragmentación del trabajo en microtareas","Emergente","Mercado laboral","De freelancing a economía basada en tareas","Plataformas gig en evolución","Media","Precarización, volatilidad de ingresos","Mayor liquidez del trabajo","Infraestructura de matching eficiente","Media / Alta / Alta","Brokers de tareas IA-humano","Hipótesis: roles fijos disminuyen significativamente"],
  ["Reducción de barreras de entrada a roles técnicos","Consolidado","Educación / empleo","Democratización vía herramientas AI","Uso de no-code, low-code, herramientas AI de programación","Alta","Saturación de mercado","Más competencia, menor diferenciación","Acceso a herramientas","Alta / Alta / Alta","Curadores de calidad","Hipótesis: aumento masivo de oferta → caída del valor promedio"],
  ["IA como primera capa de ejecución","Emergente","Operación","De asistente a ejecutor principal","Uso de LLMs para tareas completas","Media","Errores no detectados","Escala por eficiencia","Confiabilidad de modelos","Media / Alta / Alta","Validadores humanos especializados","Hipótesis: humanos intervienen solo en casos extremos"],
  ["Desplazamiento parcial de roles generalistas","Emergente","Empleo","De soporte a sustitución parcial","Reportes laborales (WEF Future of Jobs)","Media-Alta","Desempleo estructural","Reconfiguración de roles","Políticas de transición laboral","Media / Alta / Alta","Re-skilling acelerado","Hipótesis: desaparición de roles promedio"],
  ["Aumento del valor del criterio humano","Incipiente","Cognición / estrategia","De implícito a explícito","Discusión en literatura sobre toma de decisiones","Baja-Media","Difícil de medir","Diferenciación competitiva clave","Educación orientada al juicio","Baja / Media / Alta","Formación en pensamiento crítico aplicado","Hipótesis: el criterio supera la ejecución en valor económico"],
  ["Integración humano-IA como sistema híbrido","Emergente","Organización","De uso puntual a dependencia estructural","Casos empresariales híbridos","Media","Fallos de coordinación","Máxima eficiencia combinada","Diseño organizacional nuevo","Media / Alta / Alta","Arquitectos de sistemas humano-IA","Hipótesis: equipos híbridos superan a humanos o IA por separado"],
  ["Estandarización de herramientas de IA","Emergente","Tecnología","De fragmentación a consolidación","Dominancia de plataformas principales","Media","Monopolios","Escala global rápida","Regulación antimonopolio","Media / Alta / Alta","Capas middleware independientes","Hipótesis: pocas plataformas dominan el mercado"],
  ["Cambios en educación hacia habilidades meta","Incipiente","Educación","De contenido a habilidades","Reformas educativas incipientes","Baja","Inercia institucional","Adaptación lenta pero inevitable","Reformas estructurales","Baja / Media / Alta","Educación paralela privada","Hipótesis: la educación formal pierde relevancia"],
  ["Ansiedad e incertidumbre laboral creciente","Emergente","Social","De percepción a fenómeno estructural","Encuestas sobre percepción de la IA","Media","Impacto en salud mental","Cambios en comportamiento laboral","Reconocimiento institucional","Media / Alta / Alta","Industria de soporte psicológico laboral","Hipótesis: la ansiedad correlaciona con la automatización"],
  ["Transferencia de valor de ejecución a dirección","Incipiente","Economía","Cambio en cadena de valor","Observación en industrias creativas","Baja-Media","Difícil captura de valor","Nuevos modelos de negocio","Métricas nuevas","Baja / Media / Alta","Plataformas de dirección estratégica","Hipótesis: la dirección captura mayor margen"],
  ["Opacidad de sistemas AI complejos","Emergente","Tecnología / ética","De modelos interpretables a cajas negras","Literatura sobre explicabilidad","Alta","Riesgos regulatorios","Limitación en adopción crítica","Avances en interpretabilidad","Media / Alta / Alta","Auditoría algorítmica","Hipótesis: la regulación exige transparencia"],
];
const tagClass={Consolidado:"tag-c",Emergente:"tag-e",Incipiente:"tag-i"};
const tbody=document.getElementById("tbody");
DATA.forEach(r=>{
  const tr=document.createElement("tr");
  tr.innerHTML=`<td class="tema">${r[0]}</td><td><span class="tag ${tagClass[r[1]]||''}">${r[1]}</span></td><td>${r[2]}</td><td>${r[3]}</td><td>${r[4]}</td><td>${r[5]}</td><td>${r[6]}</td><td>${r[7]}</td><td>${r[8]}</td><td class="prob">${r[9]}</td><td>${r[10]}</td><td class="nota">${r[11]}</td>`;
  tbody.appendChild(tr);
});
function showTab(id,btn){
  document.querySelectorAll(".section").forEach(s=>s.classList.remove("active"));
  document.querySelectorAll(".tab").forEach(t=>t.classList.remove("active"));
  document.getElementById(id).classList.add("active");
  btn.classList.add("active");
}
</script>
</body>
</html>
