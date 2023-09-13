# Readme del Proyecto de Análisis de Siniestros Viales en Buenos Aires

Este repositorio contiene los recursos y resultados del proyecto de análisis de siniestros viales en la ciudad de Buenos Aires, Argentina. El objetivo principal de este proyecto es analizar los datos de accidentes de tráfico en la ciudad y proporcionar información relevante sobre los actores viales, las comunas con mayor accidentalidad y los actores viales de estos incidentes.

## Datos

Los datos utilizados en este proyecto se obtuvieron del Observatorio de Movilidad y Seguridad Vial de la Ciudad de Buenos Aires. Estos datos se encuentran en un archivo de Excel que registra los accidentes que ocurrieron en la ciudad entre los años 2016 - 2021.

## Desarrollo

Todo el desarrollo descrito a continuación se realizó en Power BI:

- Se agregó una nueva columna llamada "rango etario" en la cual se filtraron las edades de las víctimas dentro de un rango de edad.

- Se creó una columna llamada "moto" con el valor 1 si la víctima del accidente era un conductor o pasajero de una motocicleta, con el fin de poder elaborar uno de nuestros KPIs.

- Se crearon seis medidas, que son las siguientes:
  - "accidentesmotoanioanteriores" y "accidentemotoanioultimoano": Estas medidas describen el número de accidentes mortales de motocicletas en años anteriores y el último año, respectivamente. Sirven de apoyo para la elaboración de nuestros KPI.
  - "accidentespeatonanioanteriores" y "accidentespeatonultimoano": Estas medidas describen el número de accidentes mortales de peatones en años anteriores y el último año, respectivamente. También son utilizadas en la elaboración de nuestros KPI.
  - "kpimoto" y "kpipeaton": Estas medidas describen la variación de siniestros mortales de motociclistas y peatones del año actual con respecto al año anterior.

## Conclusiones y Recomendaciones

En base a los análisis realizados en el dashboard de siniestros viales, las conclusiones más destacadas son las siguientes:

- Las víctimas más frecuentes de siniestros viales son los conductores o pasajeros de motos y los peatones.

- El rango de edad en el que una persona es más propensa a sufrir un accidente se encuentra entre los 20 y 29 años, seguido por las edades entre 30 y 39 años.

- Los hombres tienen más del doble de probabilidad de sufrir un accidente que las mujeres.

- El último trimestre del año es cuando ocurre la mayor cantidad de accidentes.

- Entre las 5 a 7 de la mañana es la franja horaria en la que se presenta el mayor número de siniestros viales.



## Consideraciones

- Para la elaboración de este proyecto, se consideró como fallecidas a aquellas personas en donde la columna de fecha de fallecimiento tenga un valor tipo fecha en sus filas.

- Se debe tener en cuenta que la edad mínima para tener una licencia de conducción en Argentina es de 17 años, y no existe una edad máxima para poseer una licencia de conducción.

- En el año 2020, se presentó la pandemia del COVID-19, por lo cual en Argentina, como en todo el planeta, hubo restricciones de movilidad y confinamiento. Se considera al 2020 como un año atípico para efectos de nuestros análisis y conclusiones.
