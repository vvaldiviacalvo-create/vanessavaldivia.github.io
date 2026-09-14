<style>
  header { display: none !important; }
  section { width: 100% !important; float: none !important; max-width: 980px !important; margin: 0 auto !important; }
  
  /* Estilo para las etiquetas/botones azules */
  .badge-btn {
    display: inline-block;
    background-color: #2b6cb0;
    color: #ffffff !important;
    padding: 7px 16px;
    margin: 4px 2px;
    font-size: 0.9em;
    font-weight: bold;
    text-transform: uppercase;
    text-decoration: none !important;
    border-radius: 4px;
    letter-spacing: 0.5px;
  }
</style>

<table style="width: 100%; border-collapse: collapse; border: none;">
<tr style="border: none;">

<!-- COLUMNA IZQUIERDA (Perfil) -->
<td style="width: 35%; vertical-align: top; border: none; padding-right: 25px;">

<div style="text-align: center;">

<h1 style="font-size: 2.7em; font-weight: bold; margin-bottom: 20px; color: #2b6cb0; line-height: 1.1;">Vanessa Valdivia</h1>

<img src="foto.jpg" alt="Vanessa Valdivia" style="width: 220px; height: 220px; border-radius: 50%; object-fit: cover; margin: 0 auto 20px; display: block;">

<p style="font-size: 1.15em; color: #374151; line-height: 1.5;">
¡Hola! Te doy la bienvenida a mi portafolio de proyectos de Análisis de Datos.
</p>

<p style="margin-top: 20px;">
<a href="https://github.com/vvaldiviacalvo-create" target="_blank" style="font-weight: bold; font-size: 1.15em; color: #2b6cb0;">View My GitHub Profile</a>
</p>

</div>

</td>

<!-- COLUMNA DERECHA (Contenido Principal) -->
<td style="width: 65%; vertical-align: top; border: none; padding-left: 15px; font-size: 1.15em; line-height: 1.6; color: #374151;">

<h1 style="font-size: 2.3em; font-weight: bold; color: #111827; margin-bottom: 12px; border-bottom: 2px solid #e5e7eb; padding-bottom: 6px;">Acerca de mí</h1>

<p>Analista de Business Intelligence con un trasfondo de más de una década ejecutando procesos técnicos, licitaciones y control de calidad. Utilizo SQL, Python, Power BI y Tableau para realizar limpieza rigurosa, modelado de datos y diseño de KPIs interactivos que optimizan la toma de decisiones y reducen riesgos operativos.</p>

<h2 style="font-size: 1.7em; font-weight: bold; color: #1f2937; margin-top: 25px; margin-bottom: 10px;">Habilidades tecnológicas</h2>

<ul style="margin-top: 5px; padding-left: 20px;">
  <li style="margin-bottom: 8px;">Análisis y gestión de datos utilizando <b>Excel / SQL / Python</b></li>
  <li>Visualización de datos y narración de historias usando <b>Power BI / Tableau</b></li>
</ul>

<h2 style="font-size: 1.7em; font-weight: bold; color: #1f2937; margin-top: 25px; margin-bottom: 10px;">Habilidades blandas</h2>

<p style="color: #4b5563; font-size: 1.05em;">Análisis de datos | Rigor y precisión técnica | Pensamiento estratégico y de negocio | Comunicación efectiva | Resolución de problemas complejos | Gestión de procesos | Atención al detalle | Colaboración interdisciplinaria | Adaptabilidad y resiliencia</p>

<br>

<h1 style="font-size: 2.3em; font-weight: bold; color: #111827; margin-top: 25px; margin-bottom: 12px; border-bottom: 2px solid #e5e7eb; padding-bottom: 6px;">Proyectos seleccionados</h1>
# 🛵 RappiPlus: Optimización de Negocio y Métricas de Ingresos

## 📌 Introducción
Este proyecto realiza una evaluación *end-to-end* del servicio **RappiPlus** para identificar oportunidades de crecimiento y eficiencia operativa. A través de la integración de fuentes de datos transaccionales, catálogo de productos, inversión publicitaria y analítica de producto, se analizan la rentabilidad unitaria, la conversión del usuario y la retención en la plataforma.

---

## ❓ Preguntas Clave de Negocio
1. **Calidad de Datos:** ¿Existen inconsistencias o valores atípicos en los registros de ventas que distorsionen los KPIs financieros?
2. **Rentabilidad:** ¿Cuáles son los canales de adquisición y mercados más rentables en términos de Margen Neto y CAC?
3. **Conversión y Retención:** ¿En qué etapas del embudo se concentran las mayores fugas de usuarios y cómo evoluciona la retención por cohortes a lo largo del tiempo?
4. **Experimentos A/B:** ¿El rediseño de la interfaz de Checkout genera un impacto estadísticamente significativo en la tasa de conversión?

---

## 🛠️ Metodología
- **Auditoría y Limpieza (Python):** Depuración de +25,000 registros transaccionales a 24,600 entradas válidas. Manejo de *outliers* mediante **Winsorización** al percentil 99 e imputación de nulos.
- **Análisis Financiero:** Integración de costos e inversión en marketing para calcular Margen Bruto, Ganancia Neta y CAC por canal y país.
- **Embudos y Cohortes (SQL/Python):** Mapeo de tasas de caída (*drop-off*) y matrices de retención mensual a 6 meses.
- **Validación Estadística:** Prueba de hipótesis ($\chi^2$ / tablas de contingencia) sobre el experimento A/B del flujo de Checkout.

---

## 📊 Visualizaciones Destacadas
*(Inserta aquí las capturas o GIFs de tus gráficos)*

| Dashboard de Performance (Power BI) | Matriz de Retención por Cohortes |
| :---: | :---: |
| `![Dashboard](URL_DE_TU_IMAGEN_1)` | `![Cohortes](URL_DE_TU_IMAGEN_2)` |

---

## 💡 Conclusiones y Recomendaciones

### Conclusiones
- **Integridad:** La depuración de precios base y la aplicación de descuentos reales corrigió sobreestimaciones en el volumen de ingresos totales.
- **Canales de Adquisición:** Se identificaron disparidades marcadas en el CAC entre canales orgánicos y pagados, afectando el margen neto global.
- **Impacto A/B:** *(Agrega tu hallazgo puntual, ej.: "El nuevo diseño del Checkout incrementó la conversión con significancia estadística, p-valor < 0.05").*

### Recomendaciones
- **Optimización de Presupuesto:** Reasignar inversión publicitaria de canales con alto *churn* hacia fuentes de adquisición de mayor LTV.
- **Implementación de UI:** Desplegar de forma definitiva la nueva interfaz de Checkout validada en la prueba A/B.
