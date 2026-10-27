# Evolución de la brecha en la edad de defunción entre hombres y mujeres en Costa Rica, 2005-2024

Autor: Mariano Morales Carvajal  
Curso: Herramientas de Ciencia de Datos I  
Universidad de Costa Rica  
Año: 2026

## Objetivo

Analizar la evolución de la brecha en la edad de defunción entre hombres y mujeres en Costa Rica durante el período 2005-2024.

## Datos

Se utilizan registros oficiales de defunciones del Instituto Nacional de Estadística y Censos (INEC).

## Estructura del proyecto

- cod/: código de R y Quarto.
- data/: datos originales utilizados en el análisis.
- info/: documentación y referencias.
- config/: archivos de configuración.
- res/: resultados, gráficos y reportes.

## Metodología

Se utiliza estadística descriptiva, regresión lineal con interacción entre sexo y año, e intervalos de confianza del 95 %.

También se realiza un análisis de sensibilidad excluyendo las defunciones de menores de un año.



## Cómo ejecutar el proyecto

1. Descargar o clonar este repositorio.
2. Abrir el archivo `Individual_Morales_HerramientasDatosI_2026.Rproj` en RStudio.
3. Verificar que estén instalados los paquetes de R utilizados en el análisis.
4. Abrir `cod/IndividualNano.qmd`.
5. Presionar `Render` para ejecutar el análisis y generar el PDF.
6. Consultar el reporte final en `res/IndividualNano.pdf`.

La base de datos se encuentra en `data/` y se utiliza una ruta relativa para acceder a ella. Cuando se genere una nueva versión del PDF, se debe copiar desde `cod/` hacia `res/`.
