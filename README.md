# <h1 align="center">**` PROYECTO DE ANALISIS DE TELECOMUNICACIONES`**</h1>

![Foto de portada](Imagenes/portada.jpg)

El objetivo de este proyecto es hacer un análisis de los datos públicos brindados por ENACOM (Ente Nacional de Comunicaciones), sobre telecomunicaciones en Argentina.

## `Descripción`

Los datos recopilados en formato csv contienen informacion sobre accesos a internet por cada 100 hogares, penetracion de internet en el pais, velocidad, tecnologias que brindan internet, distribucion de los accesos, ingresos, entre otros datos. Los registros datan desde 2014 a 2022. 
- [datasets](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/tree/main/Datos_limpios)

## `Análisis exploratorio de datos (EDA)`
- [notebook general](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/eda_general.ipynb)
- [notebook principal](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/EDA.ipynb)

El analisis exploratorio lo dividi en dos partes. Primero realice un EDA general de los 16 dataset brindados, con el fin de conocer los datos, las variables y relaciones. Y en un segundo notebook realice un EDA con los 5 dataset que considere mas importantes ya que contenian la informacion mas relevante para describir el sector.

Los 5 conjuntos de datos pasaron por las siguientes etapas: 
- Analisis estadisticos y de reconociento de datos.
- Limpieza y transformaciónes(fueron pocas, ya que me asegure que los dataset seleccionados sean los mas completos).
- Visualización de los datos.

## `Contexto y rol a desarrollar`
En un contexto mundial predominado por las telecomunicaciones donde la transmisión de información a través de medios electrónicos, como la telefonía, televisión, radio y prinicipalmente el internet comunican a personas, organizaciones, dispositivos a largas distancias y en tiempo real. La empresa Connect Network prestadora de servicios de telecomunicaciones en  Argentina me encarga la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considerando que la principal actividad de la empresa es brindar acceso a internet.
La finalidad de este analisis sera orientar a la empresa para brindar una buena calidad de sus servicios, identificar oportunidades crecer y poder plantear soluciones personalizadas a sus posibles clientes.

## Dashboard

El dashboard cuenta con 1 portada donde se presentan preguntas que me ayudaron a orientar el trabajo y 5 paginas navegables con botenes de navegacion.

### En la primer pagina visualizamos:
- El aumento de la velocidad de Mbps a lo largo de los años.
- Velocidad minima, maxima, promedio general y medidor.
- Filtros para generar interactividad de los datos.

Tambien se presenta el primer KPI:
### Aumento en un 5% el promedio de la velocidad media de descarga del año anterior(2021). Podemos ver que en el año 2022 se cumplio el objetivo superandolo en un +17.91%.
![Logo](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/Imagenes/Captura%20de%20pantalla%20(5).png)

### En la cuarta pagina visualizamos:
- Graficos de barras agrupadas representando la aproximacion de penetracion del mercado, medido en el acceso por cada 100 hogares.
- El top 5 de provincias con mas accesos.
- Filtros interactivos para año y trimestre.

 ### KPI presentado, representa el progreso del objectivo de penetracion por provincia. Podemos notar que las provincias ubicadas a la derecha tienen un menor promedio de acceso cada 100 hogares. El objetivo sera que cada provincia tenga dentro de los proximos trimestres un promedio minimo de 65 accesos sobre 100 hogares.

![Logo](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/Imagenes/Captura%20de%20pantalla%20(2).png)
![Logo](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/Imagenes/Captura%20de%20pantalla%20(3).png)

### En la ultima pagina analizamos la evolucion de los ingresos con:
- Ingresos por trimestre.
- Filtros para año.
- Maximo de ingresos.
- Ingresos actuales vs ingresos del año anterior  y su evolucion en un grafico de lineas.
 ### El KPI presentado representa un aumento del 2% de los ingresos promedio del año anterior. Como los datos van hasta el 3er trimestre de 2022, no se logra superar el objetivo. 

 ![Logo](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/blob/main/Imagenes/Captura%20de%20pantalla%20(4).png)

## Informacion adicional
Podran visualizar el resto del analisis en:
- [imagenes](https://github.com/Clarisantillan/PI2_DA_telecomunicaciones/tree/main/Imagenes)
