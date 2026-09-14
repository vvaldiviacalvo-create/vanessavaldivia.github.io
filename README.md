<style>
  header { display: none !important; }
  section { width: 100% !important; float: none !important; max-width: 950px !important; margin: 0 auto !important; }
  
  /* Estilo para las etiquetas/botones azules */
  .badge-btn {
    display: inline-block;
    background-color: #2b6cb0;
    color: #ffffff !important;
    padding: 6px 14px;
    margin: 3px 2px;
    font-size: 0.85em;
    font-weight: bold;
    text-transform: uppercase;
    text-decoration: none !important;
    border-radius: 3px;
    letter-spacing: 0.5px;
  }
</style>

<table style="width: 100%; border-collapse: collapse; border: none;">
<tr style="border: none;">
<!-- COLUMNA IZQUIERDA (Perfil) -->
<td style="width: 35%; vertical-align: top; border: none; padding-right: 25px;">
<div style="text-align: center;">
<h1 style="font-size: 2.5em; font-weight: bold; margin-bottom: 20px; color: #2b6cb0; line-height: 1.1;">Vanessa Valdivia</h1>
<img src="foto.jpg" alt="Vanessa Valdivia" style="width: 220px; height: 220px; border-radius: 50%; object-fit: cover; margin: 0 auto 20px; display: block;">
<p style="font-size: 1.05em; color: #4b5563; line-height: 1.5;">
¡Hola! Te doy la bienvenida a mi portafolio de proyectos de Análisis de Datos.</p>
<p style="margin-top: 20px;"><a href="https://github.com/vvaldiviacalvo-create" target="_blank" style="font-weight: bold; font-size: 1.05em; color: #2b6cb0;">View My GitHub Profile</a></p>
</div>
</td>

<!-- COLUMNA DERECHA (Contenido Principal) -->
<td style="width: 65%; vertical-align: top; border: none; padding-left: 15px; font-size: 1.05em; line-height: 1.6;">
<h1 style="font-size: 2.2em; font-weight: bold; color: #111827; margin-bottom: 12px; border-bottom: 2px solid #e5e7eb; padding-bottom: 6px;">Acerca de mí</h1>
<p>Profesional en análisis de datos con experiencia en ejecución de procesos técnicos, contractuales y de auditoría de calidad.</p>
<p>Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, estructurando datos complejos y validando hipótesis.</p>

<h2 style="font-size: 1.6em; font-weight: bold; color: #1f2937; margin-top: 25px; margin-bottom: 10px;">Habilidades tecnológicas</h2>
<ul style="margin-top: 5px; padding-left: 20px;">
  <li style="margin-bottom: 6px;">Análisis y gestión de datos utilizando <b>SQL / Python</b></li>
  <li>Visualización de datos y narración de historias usando <b>Power BI / Tableau</b></li>
</ul>

<h2 style="font-size: 1.6em; font-weight: bold; color: #1f2937; margin-top: 25px; margin-bottom: 10px;">Habilidades blandas</h2>
<p style="color: #4b5563; font-size: 0.98em;">Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos</p>

<br>
<h1 style="font-size: 2.2em; font-weight: bold; color: #111827; margin-top: 25px; margin-bottom: 12px; border-bottom: 2px solid #e5e7eb; padding-bottom: 6px;">Proyectos seleccionados</h1>

<!-- PROYECTO 1: RAPPIPLUS -->
<h2 style="font-size: 1.6em; font-weight: bold; color: #1f2937; margin-top: 20px; margin-bottom: 8px;">🛵 RappiPlus: Optimización de Negocio y Métricas de Ingresos</h2>
<p>Evaluación <i>end-to-end</i> del servicio <b>RappiPlus</b> para identificar oportunidades de crecimiento y eficiencia operativa mediante el análisis de rentabilidad unitaria, embudos de conversión y retención de usuarios.</p>

<p style="margin-top: 10px; margin-bottom: 4px;"><b>❓ Preguntas Clave:</b></p>
<ul style="margin-top: 0; padding-left: 20px; font-size: 0.95em;">
  <li>¿Existen inconsistencias en los registros de ventas que distorsionen los KPIs financieros?</li>
  <li>¿Cuáles canales y mercados generan mayor Margen Neto vs. el Costo de Adquisión de Clientes (CAC)?</li>
  <li>¿En qué etapas del embudo se pierden usuarios y cómo se comporta la retención por semana?</li>
  <li>¿El rediseño de la interfaz de Checkout genera un impacto estadísticamente significativo en la tasa de conversión?</li>
</ul>

<p style="margin-top: 10px; margin-bottom: 4px;"><b>🛠️ Metodología:</b></p>
<ul style="margin-top: 0; padding-left: 20px; font-size: 0.95em;">
  <li><b>Depuración:</b> Limpieza de +25k órdenes a 24,600 entradas válidas y Winsorización al p99 para outliers.</li>
  <li><b>Modelado Financiero:</b> Recálculo de Margen Bruto, Ganancia Neta y CAC por canal/país.</li>
  <li><b>Analítica de Retención:</b> Matrices de cohortes a 6 meses y embudos de conversión en SQL/Python.</li>
  <li><b>Pruebas A/B:</b> Validación estadística con prueba Chi-cuadrada en SciPy.</li>
  <li><b>Dashboarding Interactivo:</b> Diseño de un reporte en Power BI (Overview Ejecutivo y Desempeño) para el seguimiento de KPIs clave (Revenue, Profit, Gasto Marketing, Ticket Promedio) y análisis de concentración de   ventas por producto.</li>
</ul>

<p style="margin-top: 10px; margin-bottom: 4px;"><b>💡 Conclusiones:</b></p>
<ul style="margin-top: 0; padding-left: 20px; font-size: 0.95em;">
  <li>La corrección de precios base y descuentos reales evitó sobreestimaciones en el revenue.</li>
  <li>Se detectó alta fuga en canales de adquisición de pago respecto al tráfico orgánico.</li>
  <li><b>Prueba A/B en Checkout:</b> No se encontró evidencia estadística de que el cambio en la UI mejore la conversión, por lo que no se justifica su despliegue sin antes iterar el diseño.</li>
</ul>

<p style="margin-top: 10px; margin-bottom: 4px;"><b>🚀 Recomendaciones:</b></p>
<ul style="margin-top: 0; padding-left: 20px; font-size: 0.95em;">
  <li>Detener el despliegue de la nueva interfaz de pago. Se sugiere iterar la propuesta de diseño y reevaluar mediante un nuevo test antes de comprometer recursos de desarrollo.</li>
  <li>Priorizar la inversión publicitaria en canales orgánicos y de búsqueda de alta intención, reduciendo el gasto en campañas pagadas de baja retención para controlar el CAC y proteger el Margen Neto.</li>
  <li>Foco en productos de mayor margen y recurrencia (como electrónica y tecnología) mediante campañas de <i>cross-selling</i> dirigidas a frenar el <i>churn</i> a partir del segundo mes en la matriz de cohortes.</li>
  <li>Implementar reglas de validación en la capa de captura transaccional para evitar inconsistencias en precios base y asegurar un seguimiento financiero preciso en los dashboards de Power BI.</li>
</ul>

<div style="margin-top: 12px; margin-bottom: 15px;">
  <span class="badge-btn">PYTHON</span>
  <span class="badge-btn">SQL</span>
  <span class="badge-btn">POWER BI</span>
  <span class="badge-btn">SCIPY</span>
</div>

<p style="margin-bottom: 30px;"><a href="https://github.com/vvaldiviacalvo-create/TU_REPOSO_RAPPI" target="_blank" style="font-weight: bold; color: #2b6cb0;">👉 Ver código completo y documentación detallada en GitHub</a></p>

<hr style="border: 0; border-top: 1px solid #e5e7eb; margin: 25px 0;">

<p style="margin-top: 15px; margin-bottom: 8px;"><b>📊 Visualizaciones Destacadas:</b></p>

<table style="width: 100%; border-collapse: collapse; margin-bottom: 20px; border: none;">
  <tr style="border: none;">
    <!-- IMAGEN 1: Overview Ejecutivo -->
    <td style="width: 50%; vertical-align: top; padding-right: 10px; border: none;">
      <div style="text-align: center;">
        <p style="font-size: 0.9em; font-weight: bold; color: #1f2937; margin-bottom: 6px;">Overview Ejecutivo (Power BI)</p>
        <img src="overview_ejecutivo.png" alt="Overview Ejecutivo Power BI" style="width: 100%; border-radius: 6px; border: 1px solid #e5e7eb; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
      </div>
      <p style="font-size: 0.85em; color: #4b5563; margin-top: 8px; line-height: 1.4;">
        <b>Descripción:</b> Monitoreo general de KPIs financieros (Revenue, Profit, Gasto de Marketing y Ticket Promedio). Permite analizar la evolución temporal del margen neto e identificar variaciones mensuales aceleradas o desaceleradas.
      </p>
    </td>
    <!-- IMAGEN 2: Desempeño Comercial -->
    <td style="width: 50%; vertical-align: top; padding-left: 10px; border: none;">
      <div style="text-align: center;">
        <p style="font-size: 0.9em; font-weight: bold; color: #1f2937; margin-bottom: 6px;">Desempeño Comercial y Margen</p>
        <img src="desempeno_comercial.png" alt="Desempeño Comercial Power BI" style="width: 100%; border-radius: 6px; border: 1px solid #e5e7eb; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
      </div>
      <p style="font-size: 0.85em; color: #4b5563; margin-top: 8px; line-height: 1.4;">
        <b>Descripción:</b> Análisis de volumen de ventas y concentración del beneficio por categoría de producto. Incluye un detalle financiero desglosado por unidades vendidas, costos y ganancia total para respaldar la gestión del catálogo.
      </p>
    </td>
  </tr>
</table>

<!-- PROYECTO 2 -->
<h2 style="font-size: 1.6em; font-weight: bold; color: #1f2937; margin-top: 20px; margin-bottom: 10px;">Análisis de retención y conversión en E-commerce</h2>
<p>Identificación de factores clave en la conversión y comportamiento de retención mensual utilizando Common Table Expressions (CTEs) y funciones de ventana en SQL.</p>
<div style="margin-top: 10px;">
  <span class="badge-btn">SQL</span>
  <span class="badge-btn">POSTGRESQL</span>
  <span class="badge-btn">ANALYTICS</span>
</div>
</td>
</tr>
</table>
