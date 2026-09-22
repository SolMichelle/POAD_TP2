# POAD_TP2
El presente trabajo práctico tiene como finalidad trazar gráficos eficientes para la representación de datos.

## Conclusiones y hallazgos sobre el conjunto de datos
*1. ETL:*
Se logró unificar los orígenes de datos mediante un flujo ETL robusto en PySpark, homogeneizando la granularidad (30.000 registros de mercado vs. 2.000 encuestas a empleados) y estandarizando tipos de datos, escalas categóricas y variables continuas (como el trabajo remoto y el riesgo de automatización).

*2. Diagnóstico y calidad de los datos:*
Al evaluar las representaciones gráficas continuas y categóricas (como los diagramas de caja en Seaborn y los histogramas en Matplotlib), se evidenció una homogeneidad casi perfecta en las medianas, rangos intercuartílicos y frecuencias entre categorías aparentemente disímiles (por ejemplo: distribuciones salariales idénticas para niveles bajo, moderado y alto de impacto de IA). Este comportamiento estadístico confirma que los conjuntos de datos analizados corresponden a una generación sintética basada en distribuciones aleatorias uniformes. En consecuencia, las variables no presentan correlaciones reales ni sesgos propios del mercado laboral del mundo real.

*3. Representación visual eficiente:*
A pesar de la naturaleza aleatoria de la muestra sintética, las técnicas de agregación y las herramientas de visualización seleccionadas (Matplotlib con control dinamizado, Seaborn para análisis de dispersión/distribución y Plotly para la exploración interactiva punto a punto) demostraron ser eficientes para procesar volúmenes medianos/grandes de datos y comunicar de forma limpia la estructura del dataset consolidado.

## Fuente de los datasets
- https://www.kaggle.com/datasets/sahilislam007/ai-impact-on-job-market-20242030?resource=download
- https://www.kaggle.com/datasets/sumeakash/ai-impact-on-job-sector

