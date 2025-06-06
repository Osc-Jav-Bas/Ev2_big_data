
# Evaluación 2 - Big Data

Este proyecto corresponde a la **Evaluación 2** de la asignatura **Big Data**, basado en un caso de análisis de avistamientos de OVNIs. El trabajo fue desarrollado por Bastían González, Oscar Silva y Javiera Reyes, siguiendo las instrucciones del curso Google Skill Boost.

## Introducción

Este análisis explora un dataset de avistamientos de objetos voladores no identificados (OVNIs) para identificar patrones temporales, geográficos y tipológicos. Utilizando herramientas de big data en Google Cloud Platform, se procesaron datos históricos de avistamientos para generar insights mediante visualizaciones interactivas y análisis estadístico.

El objetivo principal es aplicar técnicas de análisis de grandes volúmenes de datos para descubrir tendencias y patrones en los reportes de avistamientos OVNI a nivel global.

## Herramientas utilizadas

- **Google cloud platform**: Plataforma principal de análisis
- **BigQuery**: Motor de consultas SQL para procesamiento de datos
- **Data studio**: Creación de visualizaciones y dashboards
- **Google skill boost**: Plataforma de desarrollo de laboratorios
- Visualizaciones en base a datasets públicos de avistamientos OVNI

## Metodología

El proceso de análisis siguió las siguientes etapas:

1. **Carga de datos**: Importación del dataset de avistamientos OVNI a BigQuery
2. **Limpieza de datos**: Normalización y validación de fechas, ubicaciones y descripciones
3. **Análisis exploratorio**: Consultas SQL para identificar patrones y tendencias
4. **Visualización**: Creación de gráficos interactivos en data studio
5. **Interpretación**: Análisis de resultados y generación de insights

Se aplicaron técnicas de análisis temporal, geográfico y categórico para examinar la distribución de avistamientos por año, ubicación geográfica, tipos de objetos reportados y duración de los eventos.

## Resultados

A continuación, se presentan los principales gráficos obtenidos durante el análisis:

*Cantidad de avistamientos por estado dentro de los Estados Unidos*
![Gráfico 1](images/Captura1.PNG)

*Cantidad de avistamientos por año*
![Gráfico 2](images/Captura2.PNG)

*Cantidad de avistamientos de las 5 formas de objetos más vistos*
![Gráfico 3](images/Captura3.PNG)

## Principales hallazgos

El análisis reveló varios patrones significativos:

- **Tendencia creciente**: Se observa un incremento sostenido en los reportes desde la década de 1990
- **Concentración geográfica**: Estados Unidos presenta la mayor densidad de avistamientos reportados
- **Estacionalidad**: Mayor concentración de reportes durante los meses de verano
- **Formas predominantes**: Las descripciones "luz", "disco" y "triángulo" son las más frecuentes
- **Duración típica**: La mayoría de avistamientos reportan duraciones entre 2-10 minutos
- **Patrones semanales**: Los fines de semana muestran mayor actividad de reportes

## Conclusiones

El análisis de big data aplicado al dataset de avistamientos OVNI ha permitido identificar patrones consistentes y tendencias significativas. El incremento temporal en los reportes puede estar relacionado con el mayor acceso a tecnologías de comunicación y plataformas de reporte.

La concentración geográfica y los patrones estacionales sugieren factores culturales, demográficos y ambientales que influyen en la observación y reporte de estos fenómenos. Las herramientas de google cloud platform demostraron ser efectivas para el procesamiento escalable de grandes volúmenes de datos y la generación de visualizaciones que facilitan la identificación de patrones complejos.

Este proyecto ilustra la aplicación práctica de técnicas de Big Data para el análisis exploratorio de datasets diversos, demostrando la capacidad de extraer insights valiosos mediante el uso de herramientas cloud modernas.

**Repositorio**: [https://github.com/Osc-Jav-Bas/Ev2_big_data](https://github.com/Osc-Jav-Bas/Ev2_big_data)  
**Sitio web**: [https://osc-jav-bas.github.io/Ev2_big_data/](https://osc-jav-bas.github.io/Ev2_big_data/)
