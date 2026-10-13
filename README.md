# Andes Retail Group Commercial Analysis – Sprint 10

Este repositorio contiene el análisis comercial y operativo realizado para la compañía **Andes Retail Group** durante el periodo 2024-2025. El proyecto se centra en el diseño e implementación de un sistema de Business Intelligence interactivo desarrollado en **Tableau** para la toma de decisiones estratégicas, complementado con un procesamiento y validación previa de datos en **Python**.

## Contenido del repositorio

* `Andes_Retail_Group_analysis.pbix.twb`: **[Archivo Principal]** Libro de trabajo nativo de Tableau que contiene la arquitectura del dashboard interactivo, el mapeo de KPIs financieros, la distribución geográfica del negocio y el desglose estacional.
* `S10 Proyecto_VersionEstudiante_Desempeno_C...`: Jupyter Notebook complementario que documenta el pipeline de preparación de datos.

## Cómo abrir el dashboard en Tableau Public

Para interactuar con los filtros, mapas y desgloses operativos de este tablero de control, haz clic en el siguiente enlace:

[![Tableau](https://shields.io)](https://public.tableau.com/app/profile/victor.vazquez7571/viz/Andes_Retail_Group_analysis_pbix/Overview)

O también puedes usar este enlace directo: [Abrir en Tableau Public](https://public.tableau.com/app/profile/victor.vazquez7571/viz/Andes_Retail_Group_analysis_pbix/Overview)

## Objetivo del análisis

* **Diseñar un Dashboard de Diagnóstico de Causa Raíz:** Construir una arquitectura visual interactiva de dos niveles (Overview y Detalle) para auditar qué factores impulsan o frenan la rentabilidad de la compañía en Sudamérica.
* **Analizar la Estacionalidad del Negocio:** Evaluar el comportamiento de los ingresos y la utilidad bruta a lo largo de las estaciones del año para determinar si el negocio depende críticamente de ciertos periodos cíclicos.
* **Evaluar el Desempeño Comercial por Segmentos:** Contrastar el aporte financiero de los diferentes tipos de clientes (Premium, Estándar y Económico) frente al volumen de unidades vendidas y el margen bruto generado en cada región.

## 📈 Hallazgos Estadísticos y Decisiones de Negocio (Findings)

### 1. Ciclo Comercial y Dependencia Estacional
* **Interpretación:** La operación muestra una altísima dependencia de la temporada de **Verano** (con picos navideños muy marcados en diciembre). Por el contrario, las temporadas de otoño y primavera presentan una contracción severa que estanca el rendimiento comercial en la mitad del año.
* **Implicación de Negocio:** El desglose operativo confirma que la caída financiera fuera de temporada se debe estrictamente a un **bajo volumen de unidades vendidas** y no a una ineficiencia en el costo unitario de los productos.

### 2. Aporte Financiero por Segmento de Cliente
* **Interpretación:** Los clientes de los segmentos **Premium y Estándar** sostienen la rentabilidad global del grupo y absorben la operación en casi todas las regiones geográficas. El segmento **Económico** aporta un valor marginal casi invisible en la utilidad final.
* **Implicación de Negocio:** Se descarta el uso del segmento Económico como motor de margen aislado. Se propone capitalizar este segmento para lanzar promociones agresivas de volumen dirigidas exclusivamente a las estaciones débiles (otoño y primavera), estimulando la demanda y suavizando la curva de caída anual sin comprometer el margen de los clientes Premium.

### 3. Distribución Geográfica del Ingreso
* **Interpretación:** **Perú y Chile** lideran con comodidad el volumen absoluto de ingresos y utilidades dentro de Sudamérica, mientras que el mercado de Colombia se posiciona como el de menor rendimiento relativo durante el periodo analizado.
