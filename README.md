# **Siniestros en CABA**
Proyecto de Análisis de Datos, en el que elaboro informe de los siniestros en la Ciudad Autónoma de Buenos Aires, para el Observatorio de Movilidad y Seguridad Vial.

## **Rol a Desarrollar**

El Observatorio de Movilidad y Seguridad Vial (OMSV), centro de estudios que se encuentra bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, me solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para ello, me disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. Este dataset se encuentra en formato xlsx y contiene dos hojas llamadas: hechos y víctimas. 


## **EDA**

El dataset brindado es un archivo excel, compuesto por la hoja 0 con datos sobre los hechos, hoja 1 un diccionario sobre hechos, hoja 2 con datos sobre las víctimas y hoja 3 con un diccionario sobre victimas. 
Mi primer paso es realizar un análisis exploratorio de datos, veo los valores nulos, duplicados y valores faltantes. Por lo que decido eliminar algunas filas y columnas. Luego busque outliers, pero teniendo en cuenta la temática que analizamos, no detecte ninguno.


## **Análisis de Datos**

En el dataset contamos con la información de los accidentes fatales, ocurridos en la Ciudad Autónoma de Buenos Aires en los años 2016, 2017, 2018, 2019, 2020 y 2021.

| Año | Muertes |
| ------ | ------ |
| 2016 | 146 |
| 2017 | 140 |
| 2018 | 149 |
| 2019 |104 |
| 2020 | 81 |
| 2021 | 97 |
| Total | 717 |


<img src="https://github.com/AngelicaBorda/Proyecto_Analisis_Datos_Siniestros/blob/main/evolucion_muertes.png">
</p>

#### Descenso de accidentes fatales en los Años 2019 y 2020.

Analizada la información, se desprende que en los años 2019 y 2020 hubo una significatuva disminución de los accidentes de tránsito con víctimas fatales. Se pudo corroborar que en el año 2019 esa baja se debió al Plan de Seguridad Vial Porteño, en las que se tomo ciertas medidas como campañas de educación y controles viales, que dieron por resultado alrededor de un 30% de reducción de fallecimientos. Por otro lado se pudo observar, que en el 2020 se volvió a reducir notoriamente el número de víctimas, pero en esta oportunidad se debió al confinamiento obligatorio en la ciudad.

Link Plan de Seguridad Vial Porteño [Link](https://www.lanacion.com.ar/sociedad/entre-2018-2019-bajaron-30-muertes-accidentes-nid2376375/)

### **Víctimas**

En cuanto al rango de edad de las víctimas, se oberva que el 46 % son adultos (entre 30 a 59 años) y que los siguen jóvenes con un 30 % (19 a 29 años) y ancianos con un 20.5% (60 en adelante).

Respecto del sexo, el 76.2 es masculino, mientras que el 23.8% femenino.

Rol de la Víctima: podemos obervar que el 42.9 % son motociclistas, seguido de 38.6 % de peatones.

Podemos concluir que la mayoría de víctimas fatales son hombres, adultos y jóvenes, los cuales en su mayoría son motociclistas y peatones.

### **Lugar del accidente**

La mayor cantidad de accidentes se producen en avenidas con el 61.6 %. Las comunas con mas accidentes fatales son las Comuna 1, 4 y 9.

### **Horario**

La franja horaria en que más accidentes ocurren es de noche  y madrugada con el 46.3 %.

## KPIs

    - *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*

De acuerdo al último censo nacional elaborado por el Instituto Nacional de Estadística y Censos en 2022, la Ciudad Autónoma de Buenos Aires
cuenta con 3.121.707 de habitantes [Link](https://www.argentina.gob.ar/caba/).

Las víctimas fatales en accidentes de tránsito en el segundo semestre de 2021 fueron 42, por lo que su tasa de homicidios fue del 1.34 por 100.000 habitantes, lo que implica que para cumplir con el KPI propuesto en el primer semestre del 2022, habría que reducir esa tasa en un 10% (0.13), lo que nos daría una *tasa de 1.21 por 100.000 habitantes para el primer semestre del 2022.* Lo que significa alrededor de *4.2 menos de víctimas fatales*.


    - *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*

Las víctimas Fatales en accidentes de motos en el año 2020 fueron 28 y en el 2021 fueron 46.
Por lo tanto la evolución en el año 2021 respecto del 2020 fue un aumento del 64.29 %
Se concluye entonces, que no se logró el objetivo propuesto.

   - *Reducir en un 10% en el año 2022, la cantidad de peatones como víctimas fatales, respecto al año 2021*

Los peatones, victimas fatales en el 2021 fueron un total de 33, por lo que para el año 2022, para cumplir con el objetivo propuesto se deberán reducir las victimás en un 3,3.

## **Dashboard**

<img src="https://github.com/AngelicaBorda/Proyecto_Analisis_Datos_Siniestros/blob/main/dashboard.png">

Descargalo aqui [Link] (https://drive.google.com/file/d/1EBCJUH6pQw4B1bux3P9wKdzi9Zeh8Rdf/view?usp=sharing/)