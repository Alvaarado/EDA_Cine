# 📽️ Análisis Exploratorio de Datos (EDA) de las Películas Más Populares

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es llevar a cabo un Análisis Exploratorio de Datos (EDA) centrado en las películas más populares, con el fin de identificar patrones y tendencias clave dentro de la industria del cine. Este análisis se desarrollará a través de diversas características de las películas, proporcionando una visión detallada y profunda de diferentes aspectos que pueden influir en su éxito y popularidad. Los principales puntos de análisis serán los siguientes:

### 1. Relación entre el Género y la Valoración
Se examinará la distribución de las calificaciones que reciben las películas, evaluando cómo se relaciona ésta con el género de las mismas. Este análisis permitirá identificar si existe algún género predilecto entre el público.

### 2. Relación entre Presupuesto, Ingresos y Valoración
Se explorará cómo el presupuesto de la producción influye en los ingresos generados por las películas. Este análisis permitirá determinar si existe una correlación directa entre la cantidad de dinero invertido y la rentabilidad de la película, proporcionando un primer acercamiento a las estrategias de inversión más efectivas en la industria cinematográfica.

### 3. Relación entre la Duración y la Valoración
Se comparará la duración de las películas y su posible relación con la valoración recibida, con el fin de entender si entre la audiencia existe alguna preferencia clara en cuánto a la duración de los films.

## 📊 Datos

Los datasets utilizados han sido construidos accediendo a la databse de The Movie Database gracias a su API de libre acceso.

## 🔎 Metodología

- **Carga y Limpieza de Datos**: carga de datos y revisión de para asegurar consistencia. 
- **Análisis Descriptivo** : cálculo de estadísticas descriptivas para entender la distribución de los datos. 
- **Visualización de Datos**: creación de visualizaciones para identificar patrones y relaciones. 
- **Análisis de Correlación**: examen de la correlación entre variables para identificar posibles factores de riesgo. 
- **Conclusiones y Hallazgos**: resumen de las principales conclusiones y hallazgos.

## 📈 Conclusiones

A modo de síntesis, las conclusiones del análisis que hemos llevado a cabo quedan recogidas en el siguiente listado:

- **Género Predominante:** El género predominante en el top 1000 de películas es el drama, reflejando su capacidad para conectar con una audiencia amplia. Otros géneros como animación, comedia y acción, aunque populares, no alcanzan la misma representación que el drama, lo que puede reflejar preferencias cambiantes y el impacto cultural de cada género.

- **Valoraciones por Género:** El diagrama de cajas muestra que la distribución de las valoraciones es similar entre la mayoría de los géneros, con notable variabilidad dentro de cada uno. "Family" y "Music" tienen las valoraciones promedio más altas, mientras que "Western" y "War" muestran las más bajas.

- **Duración de las Películas:** La duración promedio de las películas es de aproximadamente 120 minutos. La duración más larga en géneros como histórico se debe a la escasez de películas, lo que afecta la media con valores extremos. Por el contrario, los géneros familiares y de animación tienden a tener una duración menor debido a su público objetivo.

- **Duración y Valoración:** No hay evidencia de una correlación entre la duración de las películas y la valoración que reciben por parte de la audiencia.

- **Presupuesto y Recaudación:** A pesar de la gran variabilidad, el gráfico de dispersión muestra una correlación positiva entre el presupuesto de una película y su recaudación en taquilla. Generalmente, las películas con mayores presupuestos tienden a recaudar más.

- **Valoración y Recaudación:** No se observa una correlación clara entre la valoración de una película y su rendimiento en taquilla. Las valoraciones muestran una gran variabilidad alrededor de recaudaciones relativamente bajas.

- **Ajuste por Inflación:** Es crucial ajustar los valores de presupuesto y recaudación a la inflación para realizar un análisis adecuado y justo de la industria cinematográfica a lo largo del tiempo. Sin este ajuste, los datos podrían estar sesgados por cambios en el poder adquisitivo del dinero.

## 📫 Contacto

Gracias por ver mi EDA. Para cualquier duda o comentario sobre este proyecto, por favor contactar a [ruizfdezalvaro@gmail.com].
