# Los picos de homicidios en Colombia se presentan en mayor medida en el segundo y cuarto trimestre del año.
Colombia es una país con altos indice de violencia, donde los homicidios es una problemática que se ha venido presentando durante muchos años, producto de muchos factores sociales, económicos y políticos.
## URL visualización:https://observablehq.com/@hpuentes/los-picos-de-homicidios-en-colombia-se-presentan-en-mayor-me
### Objetivo 
El principal objetivo es identificar si existe algún tipo de temporalidad respecto de los picos de homicidios en Colombia a lo largo de los años 2015 al 2019. Adicional lograr identificar como es el comportamiento de los homicidios a lo largo del tiempo por diferentes rangos de edad y por departamento.
### Alcance 
La visualización presenta una vista interactiva de la distribución anual de homicidios en Colombia por departamento, con respecto del año y el rango de edades objeto de análisis, donde es posible según la configuración seleccionada ver en orden los departamentos donde se presentan mayor cantidad de homicidios y por cada uno ver la distribución a lo largo del tiempo.
## Autor
Hermes Puentes Navarro https://www.linkedin.com/in/hermes-puentes-navarro-1898b2b3/
Combining code from Mike Bostock block https://observablehq.com/@d3/horizon-chart and Sarah Schöttler block https://observablehq.com/@sarah37/snapping-range-slider-with-d3-brush

### Fuente: Datos Abiertos 
### Entidad: Dirección General de la Policía Nacional - Dijin.
### Area o dependencia: Dirección de Investigación Criminal e INTERPOL. 
## Categorización de homicidios por año en Colombia.
* Homicidios 2019. https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-2019/un7w-gfis
* Homicidios 2018. https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-2018/pz7x-mkbs
* Homicidios 2017. https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-2017/mkw6-468s
* Homicidios 2016. https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-2016/umwz-bt8i
* Homicidios 2015. https://www.datos.gov.co/Seguridad-y-Defensa/Delito-Homicidios/cfga-dm6m

## Tarea Principal.
T1. Presentar la distribución dentro de un año de los eventos por homicidios.
(Present)-(Distribution)

### Tareas secundarias.
T2. Comparar por departamento la distribución dentro de un año de los eventos por homicidios.
(Compare)-(Extremes)

T3. Encontrar los picos dentro de la distribución anual de homicidios.
(Lookup)-(Outliers) 

T4. Buscar los rangos de edades sobre los cuales se tiene mayor variación en la distribución de los homicidios.
(Browse)-(Outliers) 

## WHAT?
### Attributes: 
* Fecha homicidio: Ordered, ordinal.
* Departamento: Categorical.
* Edad de persona muerta: Ordered, Quantitative sequential.

## WHY?
1. Presentar la distribución dentro de un año de los eventos por homicidios. (Present)-(Distribution)
2. Comparar por departamento la distribución dentro de un año de los eventos por homicidios. (Compare)-(Extremes)
3. Encontrar los picos dentro de la distribución anual de homicidios. (Lookup)-(Outliers) 
4. Buscar los rangos de edades sobre los cuales se tiene mayor variación en la distribución de los homicidios. (Browse)-(Outliers) 

## Distribución anual de Homicidios en Colombia por año (De 2015 a 2019) dentro del rango de edad seleccionado (De 0 a 100 años).
Debe seleccionar el año de distribución de anual de homicidios del combobox donde es posible seleccionar entre (2015 y 2019), adicional es posible seleccionar un rango de edades (0 - 100 por defecto) objeto de análisis arrastrando el limite inferior y superior para ajustarlo a la configuración deseada.

![Homicidios 2015-2019](https://github.com/hpuentes/homicidios-en-colombia/blob/master/homicidios%20Colombia%202015-2019.png)

## Conclusiones 
Existe una mayor densidad de homicidios en los departamentos Cauca, Antioquia y Bogotá, justificado en indices poblacionales y por ser regiones en donde se presentan altos niveles de problemática social. La distribución de los homicidios a lo largo de los años muestra que existe picos más altos a lo largo del segundo y cuarto semestre del año. Al identificar como es la distribución de los homicidios a lo largo del tiempo se entiende que la mayor variación se presenta para la población entre los 0 y 35 años, al seguir aumentando el rango de edad se ve que la distribución tiene mínimas variaciones, lo cual indica que la mayor cantidad de homicidios se presentan dentro del rango de edad de 0-35 años.

## Tecnologías usadas
* D3@5
* Javascript
* Despliegue en el sitio observablehq.
