# Andes Retail Group - Commercial & Operations Analysis 🛒📊

Este repositorio contiene un caso de estudio integral (End-to-End) de Inteligencia de Negocios y Analítica Comercial para **Andes Retail Group** enfocado en el periodo 2024-2025. El proyecto integra el procesamiento y validación previa de datos utilizando Python y el diseño de un ecosistema analítico interactivo de Diagnóstico de Causa Raíz en Tableau.

---

## 🎯 Contexto y Problema de Negocio
La alta dirección de Andes Retail Group requería auditar los factores subyacentes que impulsan o ralentizan la rentabilidad de la compañía en sus operaciones de Sudamérica. El negocio arrastra retos estructurales asociados a la variabilidad de la demanda a lo largo del año y la disparidad en los márgenes entregados por sus distintos tipos de consumidores.

Este análisis estratégico busca resolver tres preguntas de negocio:
1. ¿Qué tan severa es la dependencia cíclica de los ingresos respecto a las estaciones del año y a qué se deben las contracciones en los meses bajos?
2. ¿Qué segmentos de clientes justifican los esfuerzos de retención y cómo podemos activar los segmentos marginales sin destruir valor?
3. ¿Cómo se distribuye geográficamente el rendimiento comercial y dónde se localizan los focos rojos de la operación?

---

## 🛠️ Tecnologías y Herramientas Utilizadas
*   **Tableau Public:** Dashboard visual interactiva de dos niveles (Overview y Detalle Técnico) y mapeo geoespacial.
*   **Python (Pandas, NumPy):** Limpieza profunda, imputación de registros y validación de esquemas comerciales.
*   **Jupyter Notebook:** Entorno de documentación del procesamiento inicial de datos.

---

## 📊 Proceso de Análisis y Etapas del Proyecto

### 1. Preparación de Datos (Python)
*   Limpieza y unificación del histórico de transacciones comerciales para asegurar la consistencia del periodo 2024-2025.
*   Tratamiento de anomalías e imputación lógica de variables operativas clave para su posterior consumo en la herramienta de BI.

### 2. Diseño de Visualización e Interfaz de BI (Tableau)
*   **Estructura de Dos Niveles :** Diseño enfocado en la experiencia del usuario mediante una vista ejecutiva (*Overview*) para decisiones rápidas y una vista de desglose (*Detalle*) para auditorías profundas de causa raíz.
*   **Análisis Geoespacial y Estacional:** Mapeo de KPIs de rentabilidad distribuidos geográficamente en Sudamérica combinados con líneas de tendencia de series de tiempo.

---

## 📈 Hallazgos Clave y Conclusiones de Negocio

| Dimensión Analizada | Diagnóstico / Hallazgo | Implicación y Decisión Estratégica |
| :--- | :--- | :--- |
| **Ciclo Comercial y Estacionalidad** | Alta dependencia del **Verano** (con picos agresivos en Diciembre). Contracciones severas en Otoño y Primavera. | El estancamiento a mitad de año se debe **estrictamente a la caída en volumen de unidades vendidas** y no a ineficiencias en los costos de los productos. |
| **Rentabilidad por Segmento** | Los segmentos **Premium** y **Estándar** sostienen la utilidad final. El segmento **Económico** tiene un aporte marginal invisible. | Se descarta usar el segmento Económico como motor de margen directo. Se propone utilizarlo para promociones agresivas de volumen en temporadas bajas (Otoño/Primavera) para suavizar la curva de caída anual. |
| **Distribución Geográfica** | **Perú y Chile** lideran con comodidad el volumen absoluto de ingresos y utilidades. | **Colombia** se posiciona como el mercado con menor rendimiento relativo, marcando el foco de atención prioritario para reestructuraciones operativas. |

---

## 🚀 Recomendaciones Estratégicas
1. **Suavizado de la Curva Estacional:** Diseñar campañas agresivas de incentivos por volumen dirigidas exclusivamente al segmento de clientes *Económico* durante las estaciones de otoño y primavera. Esto estimulará la demanda en los meses de contracción comercial sin comprometer los márgenes saludables de los clientes *Premium*.
2. **Reestructuración de Mercado Focalizada:** Auditar las operaciones de la cadena de suministro y la estrategia de precios en *Colombia* para identificar las razones de su bajo rendimiento comparativo frente al éxito documentado en Perú y Chile.

---

## 🖼️ Interactividad y Acceso al Ecosistema

### 📊 Cuadro de Mando en Tableau Public
Haz clic en la insignia inferior para acceder directamente al dashboard interactivo, donde podrás manipular los filtros de estacionalidad, mapas regionales y desgloses analíticos:

[![Tableau](https://shields.io)](https://public.tableau.com/app/profile/victor.vazquez7571/viz/Andes_Retail_Group_analysis_pbix/Overview)

*(También puedes interactuar usando el [Enlace Directo a Tableau Public](https://public.tableau.com/app/profile/victor.vazquez7571/viz/Andes_Retail_Group_analysis_pbix/Overview))*

---

## 📂 Estructura del Repositorio
*   `Andes_Retail_Group_analysis.twb`: Libro de trabajo nativo de Tableau que contiene el modelo, las relaciones de datos y las dashboards visuales.
*   `Proyect_Sprint10_Andes_Retail.ipynb`: Jupyter Notebook que documenta el pipeline complementario de preparación y limpieza de datos en Python.
