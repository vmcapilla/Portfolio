# Portfolio de Victor

## Proyectos en SQL
### [Proyecto 5: Alcala_FC_Stats](https://github.com/vmcapilla/Project-5_Alcala_FC_Stats)
- Todo el análisis en MySQL
- Unión de las diferentes bases de datos, elaboración del EER
- Todo tipo de consultas de goleadores y consultas de segundo grado
- Guardado en vistas de las consultas más típicas

<img src="https://github.com/vmcapilla/Project-5_Alcala_FC_Stats/blob/main/EER_diagram_alcala.png" width="400"/>

### [Proyecto 6: Expected Goals](https://github.com/vmcapilla/Project-6_Expected_Goals)
- Limpieza de datos en Excel y Análisis en BigQuery
- Unión de dos subconsultas para realizar una tabla general con datos de local y visitante
- Creación de tabla en BigQuery y guardado de consulta como nueva tabla para subconsultas
- Consultas sobre goles esperados tanto a favor como en contra. También tabla resumen de los partidos con partidos jugados, ganados, empatados y perdidos.

Output by Top 5 xGC_Ratio:
```
SELECT 
  Team, GC, xGC, ROUND(GC/xGC, 2) AS xGC_Ratio
FROM
  `wc2018_all_games_stats` 
ORDER BY
  xGC_Ratio
LIMIT 5
```

## Proyectos en R
### [Proyecto 1: Comparador de comportamiento en viajes. Usuarios vs Suscriptores](https://github.com/vmcapilla/Proyecto-1_Divvy_Analysis_R)
- Todo el análisis en R, paquetes principales: tidyverse, dplyr, ggplot2 y lubridate
- Unión de 12 bases de datos, limpieza de datos y formateo de tipos para su correcto análisis
- Análisis por semana, mes y estaciones de ~4.6M de registros, agrupando por tipo de usuario
- Resumen e indicaciones de las estaciones con más probabilidad de convertir usuarios en suscriptores.

<img src="https://github.com/vmcapilla/Proyecto-1_Divvy_Analysis_R/blob/2fea71dbba95febbb19b16ff91a525e364cb64a4/imagenes/trips_density_users.png" width="400"/>

### [Proyecto 2: Análisis reloj deportivo. Principales estadísticas (Sueño, Pasos, Actividad, BMI)](https://github.com/vmcapilla/Proyecto-2_Bellabeat_Analysis_R)
- Todo el análisis en R, paquetes principales: tidyverse, dplyr, tidyr, ggplot2, lubridate y scales
- Análisis de 4 bases de datos, limpieza de datos y formateo de tipos para su correcto análisis
- Análisis por característica (pasos, sueño, actividad y BMI)
- Elaboración de percentiles para su análisis por categoría

<img src="https://github.com/vmcapilla/Proyecto-2_Bellabeat_Analysis_R/blob/8c81de0755aae0946d85937c3990bd6e33612971/imagenes/activity_by_BMI.png" width="400"/>

### [Proyecto 3: Rey de Europa. Sistema de Clasificación del Boxeo en el fútbol](https://github.com/vmcapilla/Proyecto-3_European_King_R)
- Todo el análisis en R, paquetes principales: tidyverse, dplyr, tidyr, ggplot2, lubridate, forcats y viridis
- Análisis en una base de datos, limpieza de datos y formateo de tipos para su correcto análisis
- Elaboración de columna condicional autorepercutida para calcular campeón en cada partido
- Elaboración de columna de país de cada equipo aplicando la mayoría de partidos en determinado país como su país de procedencia

<img src="https://github.com/vmcapilla/Proyecto-3_European_King_R/blob/807f4fe87aedf983a9aa8f4ea497dbf2f6c6cc36/imagenes/mas_partidos_rey.png" width="400"/>

### [Proyecto 4: Winner Stays.European Football Analysis with Streaks and Countries](https://github.com/vmcapilla/Proyect-4_Winner_Stays)
- Todo el análisis en R, paquetes principales: tidyverse, dplyr, tidyr, ggplot2, lubridate, forcats y viridis
- Análisis en una base de datos, limpieza de datos y formateo de tipos para su correcto análisis
- Elaboración de columna condicional autorepercutida para calcular campeón en cada partido y las rachas si el campeón no cambia
- Elaboración de nuevas gráficas a modo de mapas con los datos obtenidos

<img src="https://github.com/vmcapilla/Project-4_Winner_Stays/blob/main/imagenes/fig.06.png" width="400" height='300'/>

