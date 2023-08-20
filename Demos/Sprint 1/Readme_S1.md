<img src="src\images\logof.jpeg" width="171" height="47">

# Bienvenidos al Proyecto Final
**No hay plazo que no se venza, ni deuda que no se pague.**

## Acerca de Consultores Inc.

Como buen equipo para ciencia de datos, somos eclécticos, pero complementarios.
Tenemos la capacidad para conjugar distintas visiones técnicas y comerciales, al igual que hemos aprendido a conciliar la experiencia, con la impulsividad de las mentes más jóvenes, porque sabemos que son esenciales para encontrar soluciones que resuelvan los problemas del mundo en que vivimos, nadie es prescindible y todos tienen algo que aportar.
Los grandes equipos, a veces, no se escogen, pero se hacen fuertes por las circunstancias.

**Objetivo** 
"PROPORCIONAMOS INFORMACIÓN RELEVANTE Y VALIOSA A NUESTROS CLIENTES PARA RESPALDAR Y ENRIQUECER SUS DECISIONES ESTRATÉGICAS Y OPERATIVAS DE NEGOCIO."

## Descripción

A patir de las opiniones de los usuarios publicadas en plataformas como Google Maps y Yelp, se pretende realizar un analisis detallado para un conglomerado de empresas de restaurantes y afines, par tal fin; se almacenan, procesan y analizan los datos disponibles de las reseñas generadas en Estados Unidos, el peso aproximado de los datos iniciales es de 30gb, se usaran diferentes herramientas que permiten procesar grandes volumenes de datos.

**Herramientas a usar**:
1. Google Drive
2. MongoDB
3. Cosmos DB
4. Spark
5. SQLite 3
6. Azure (ABS, ADF, Functions)
7. DataBricks
8. Python
9. Visual Studio Code
10. Collab
11. Looker Studio

   

## Alcance

   Para efectos de este proyecto final se tomará una muestra de tres estados de USA, para la selección, se han considerado los siguientes parametros:
1. Densidad poblacional
2. Indice de criminalidad
3. Diversidad étnica
   
   De igual forma el proyecto se enfoca en un rubro.

## KPIs Merchant (Usamos merchant en forma genérica como cualquier proveedor de BBSS que tenga presencia en las plataformas digitales analizadas)

1. **“Impacto de acciones en reseñas positivas”:**   
   Frecuencia Trimestral, mide el incremento en el número de reseñas positivas, como consecuencia de las acciones de mkt. por quarter. El valor esperado es que sea >= 10%. Método de cálculo: Conteo total de reseñas positivas recibidas (valor absoluto) durante un período de 3 meses.

2. **“Índice de Satisfacción”:** 
   Frecuencia semestral, mide la satisfacción de los clientes a través del rating. El valor esperado para este indicador clave, es que se incremente en un 15 % en los siguientes 6 Meses. Método de Cálculo: Relación entre el rating actual promedio del último mes/trimestre sobre el rating promedio conseguido de los últimos 6 meses (valor relativo).
3. **“Índice de Insatisfacción”:** 
   Frecuencia semestral, mide la satisfacción de los clientes a través del rating. El valor esperado para este indicador clave, es que se incremente en un 15 % en los siguientes 6 Meses. Método de Cálculo: Relación entre el rating actual promedio del último mes/trimestre sobre el rating promedio conseguido de los últimos 6 meses (valor relativo). en un 15 % en 6 Meses: relación entre conteo total de reseñas negativas respecto al conteo total de reseñas  recibidas durante el período de 6 meses.

## KPIs Investor (Un investor o inversionista, persona que buscar rentabilizar capital)

1. **“Tasa de Engagement de usuarios respecto a la competencia”:** 
   La métrica asociada a este KPI se obtiene a partir de la relación entre cantidad de reseñas referidas a un determinado comercio respecto a la cantidad total de reseñas realizadas por dicho usuario en un periodo de 6 meses.
   
2. **“Índice de saturación de mercado”:**
   Estimar el número total de negocios para la categoría por cada 100.000 habitantes (por localidad o estado) siguiendo su evolución (crece, se mantiene o decrece) a lo largo de 12 meses. 
   
3. **“Promedio interanual de calificaciones por categoría respecto de la oferta”:**:
   Medir el promedio de calificaciones de reseñas para los negocios de cada categoría durante los últimos 5 años, nos provee un comparación del desempeño respecto a la Industria.