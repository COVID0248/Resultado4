# Aproximacion_4

Implementación de un modelo lineal mixto para medir el efecto de la aplicación de medidas sanitarias en países de la Unión Europea y Latinoamérica.

## Datos

Se cuenta a nivel país con datos:
  1. epidemiológicos
  2. medidas sanitarias
  3. socio-demográficos

La fuente original de los datos proviene de [Covid-19 Data Hub](https://covid19datahub.io/articles/data.html), enriquecido con información de [Our World in Data](https://ourworldindata.org/coronavirus), [PNUD](http://hdr.undp.org/en/content/human-development-report-office-statistical-data-api) y [World Bank](https://datos.bancomundial.org/)

para los países miembros de la Unión Europea, correspondiente al archivo `data/data_europa.xlsx`, y para Latinoamérica, correspondiente al archivo `data/data_la2.xlsx`.

## Códigos

Los modelos se ajustaron en `Stata`, por separado para la Unión Europea (`codes/codigo_europa.do`) y Latinoamérica (`codes/codigo_la.do`).

## Resultados e informe

El archivo `informe_modelos.pdf` reporta en detalle:

  1. la descripción de los datos y el outcome
  2. el proceso de ajuste del modelo y su interpretación
  3. las principales conclusiones
  4. Anexos y gráficos descriptivos de las medidas sanitarias.



