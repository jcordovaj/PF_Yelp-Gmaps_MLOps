<img src="src\images\logof.jpeg" width="171" height="47">

# Bienvenidos al Proyecto Final
**No hay plazo que no se venza, ni deuda que no se pague.**

## Índice de contenidos

**[Sobre Nosotros](#1)**
**[Contexto: Entendimiento y Síntesis del Problema](#2)**
**[Solución Propuesta](#3)**
**[KPI para el Modelo de Negocios](#4)**

## 1. Sobre Nosotros<a class="anchor" id="1"></a>

**Somos "Byte": soluciones soportadas por Ciencia de Datos**
Jota Cordova (Data Engineer & Analyst)
David Nocera (Data Analyst & Scientist)

**Nuestros Principios:** empatía, compromiso, metodicidad, confianza, trazabilidad, comunicación, adaptabilidad , ética.

**Nuestro Objetivo:** "Proporcionar Información Relevante y Valiosa a Nuestros Clientes para Respaldar y Enriquecer sus Decisiones Estratégicas y Operativas de Negocio."

[Volver - Índice](#0-0)

## 2. Contexto: Entendimiento y Síntesis del Problema<a class="anchor" id="1"></a>
Como consultores de datos, nuestro enfoque se concentra en el análisis de la información recopilada de plataformas de reseñas como Yelp y Google Maps. El objetivo primordial de nuestro análisis radica en descubrir patrones y tendencias en las opiniones de los usuarios, con el propósito de comprender sus experiencias, necesidades y expectativas en relación a diversos servicios. Este análisis de datos brindará un profundo entendimiento a partir de los datos proporcionados, permitiéndonos asesorar y ofrecer recomendaciones a posibles inversores interesados en el proyecto. Esto resulta de suma relevancia a la hora de tomar decisiones estratégicas y mejorar la imagen y reputación de nuestros clientes. Para lograr este cometido, aplicamos técnicas avanzadas de análisis de sentimientos y machine learning, con el fin de proporcionar a nuestros clientes un modelo de recomendación accesible y realista.

**Requerimientos**
Análisis de Sentimientos: Se solicita un análisis basado en sentimientos, cruzando la información de Yelp y Google Maps.
Predicciones: Usando la información de sentimientos, predecir qué rubros crecerán (trend analysis).
Zonificación: Determinar qué zonas son más atractivas para ubicar nuevos locales (zonificación basada en geolocalización).
Sistema de Recomendación: Basado en intereses y perfil del consumidor, recomendar experiencias similares.

[Volver - Índice](#0-0)

## 3. Solución Propuesta<a class="anchor" id="1"></a>

**Pet Care Market: Análisis de Mercado para Modelo de Negocios en la Industria de Mascotas y Afines**

### 3.1 Elección del modelo parametrizable<a class="anchor" id="1"></a>
En base a toda la data suministrada y a un exhaustivo estudio de mercado se establecieron criterios que permitan que nuestro producto sea escalable y parametrizable. Para ello, se establecieron criterios de selección de la data piloto: 
En primer medida, nos basamos en el análisis demográfico, que nos permitirá tener un tamaño muestral lo suficientemente representativo, estableciendo el ranking descendente de los estados con mayor densidad poblacional;
En segundo lugar, se tuvo en cuenta el marco sociocultural de distintas regiones territoriales de USA (diferencias en la prevalencia generacional, diversidad de etnias y culturas, clima, etc.), ya que permite tener una visión más global del comportamiento y hábitos de consumo de los clientes, así como proveer diferentes nichos para posibles oportunidades de negocio; 
En tercer lugar, se tuvo en cuenta el índice de criminalidad, ya que por el tipo de negocios abarcados en los datos brindados y las necesidades de nuestro cliente resulta una variable a considerar; por lo que se emplea el ranking descendiente de los estados más seguros; 
En base a estos criterios se seleccionaron los siguientes estados modelo para la prueba piloto: New Jersey, California y Florida.

[Volver - Índice](#0-0)

### 3.2 Objetivos específicos<a class="anchor" id="1"></a>
1. Asegurar la Disponibilidad de Datos Limpios y Estructurados: Recolectar,
depurar y disponer la información relevante de plataformas de reseñas
como Yelp y Google Maps. Esto asegurará la calidad y coherencia de los datos para
su análisis y aplicación en el proyecto.

1. Realizar un Análisis Exploratorio de las Reseñas de Usuarios: Identificar patrones,
tendencias y factores que influyen en la percepción de los usuarios sobre locales y
servicios, mediante el uso de las reseñas recopiladas de Yelp y Google Maps.

1. Desarrollar un Modelo Avanzado de Recomendación basado en Machine Learning: Construir un modelo que emplee técnicas de análisis de sentimientos para clasificar las reseñas y prever las preferencias de los usuarios.Esto brindará la capacidad de tomar decisiones certeras en calidad de empresario o inversionista.

2. Crear un Modelo Predictivo: Desarrollar un segundo modelo para presentar al empresario, que consistirá en un modelo de aprendizaje automático (Machine Learning) capaz de realizar predicciones sobre nuevas experiencias para los usuarios. Esto proporcionará la oportunidad de optimizar la experiencia del cliente y diseñar estrategias personalizadas.

3. Elaborar un Panel Interactivo (Dashboard): Construir una interfaz interactiva que permita visualizar y explorar los resultados del análisis de datos de las reseñas de usuarios. Proporcionará métricas, gráficos y estadísticas pertinentes para facilitar la toma de decisiones estratégicas y la identificación de oportunidades de mejora en los servicios ofrecidos.

[Volver - Índice](#0-0)

### 3.3 Ejes del Proyecto<a class="anchor" id="1"></a>

**Adaptabilidad y Validación Técnica:**
Ofrecemos una solución personalizada, paramétrica y escalable que se adapta a las necesidades específicas del cliente. Mediante la aplicación de la teoría de las restricciones, validamos la factibilidad técnica de esta propuesta y optamos por la ejecución de un modelo piloto. Esta decisión busca reducir los costos para el cliente, al mismo tiempo que garantiza la viabilidad y efectividad del proyecto.

**Geomarketing y Segmentación Avanzada:**
Haremos uso de datos georreferenciados para elaborar estrategias de marketing altamente efectivas. Esta estrategia se basa en una segmentación avanzada de consumidores según diversas variables. Para lograrlo, aplicaremos el concepto de mapeo por capas, categorizando los objetos de acuerdo a su pertinencia y relación con la estrategia en cuestión.

**Desarrollo de Producto Ágil:**
Nuestro enfoque ágil para el desarrollo de producto se divide en tres sprints definidos: En el Sprint 1 (S1), estableceremos el ambiente de desarrollo y definiremos el alcance y las pautas del proyecto. En el Sprint 2 (S2), construiremos un Modelo de Analytics sólido. Finalmente, en el Sprint 3 (S3), completaremos un Modelo de Machine Learning e integraremos las partes frontend ybackend del producto para presentar una solución completa y funcional.

**Gestión de Big Data:**
Enfrentamos el desafío de manejar más de 30 GB de archivos con diversas estructuras. Nuestra estrategia implica la "ingestión" de datos, seguida de la reducción y el filtrado de la información, priorizando los datos funcionales en línea con las necesidades del cliente. Esta optimización no solo cumple con los requerimientos del cliente, sino que también maximiza el rendimiento general y facilita la generación del modelo en producción.

**Machine Learning y Análisis de Sentimientos:**
Nuestro enfoque en Machine Learning se centrará en desarrollar un modelo basado en el análisis de sentimientos. Esto se logrará procesando las reseñas y comentarios de los usuarios para construir una matriz de resultados que permita realizar predicciones basadas en parámetros clave. Cabe destacar que este modelo estará específicamente orientado al mercado de "Pet Care".

**Visualización Efectiva:**
Optimizaremos la representación de datos y reduciremos la complejidad visual mediante el uso de técnicas adecuadas. Diseñaremos un story-board personalizado para este propósito. Utilizaremos Looker por su capacidad de integración en entornos web y, para la interacción en entorno local, emplearemos Plotty, aprovechando su versatilidad y funciones interactivas.

[Volver - Índice](#0-0)

## 4. KPI para el Modelo de Negocios<a class="anchor" id="1"></a>
Los indicadores clave de rendimiento (KPI) deben alinearse con los objetivos comerciales del destinatario y proporcionar información esencial para tomar decisiones fundamentadas. En consecuencia, los KPI pueden variar según el modelo de negocio y con mayor precisión, deben reflejar la estrategia y los objetivos específicos del análisis, teniendo en cuenta los criterios "SMART".

Es factible abordar la definición de KPI desde diferentes perspectivas:
Desde la perspectiva de un comerciante, resulta relevante medir aspectos como frecuencias, horarios y atributos clave. Esto implica investigar si existe alguna correlación entre los atributos y las evaluaciones, así como con el comportamiento de compra, las visitas al establecimiento, el crecimiento y el volumen, entre otros factores.

En contraste, desde la perspectiva de un inversionista, cobra importancia evaluar el atractivo del negocio. Esto implica comprender quiénes son los clientes, segmentarlos según sus características; También es relevante determinar el tamaño del mercado o del segmento. Cabe destacar que en este proyecto se proponen KPI innovadores, diferentes de los indicadores clásicos utilizados para evaluar la rentabilidad, como el ARPU, LTCV/CRM y la plusvalía, entre otros.

Esta estrategia de definir KPI desde múltiples enfoques permite abordar con precisión las necesidades y objetivos específicos del negocio, brindando una perspectiva holística y enriquecedora para la toma de decisiones informadas.

***KPI para Comerciantes***

**1. Impacto de Acciones en Reseñas Positivas:**
Este indicador mide el éxito de las acciones de marketing y su influencia en la obtención de reseñas positivas. El objetivo es lograr un aumento del 10% en las reseñas positivas durante el próximo trimestre. Se calcula como la diferencia entre la proporción actual de reseñas positivas (Pf) y la proporción de reseñas totales (Tf) respecto a tres meses atrás (Po/To), multiplicado por cien.
*Fórmula:* Impacto de Acciones en Reseñas Positivas (%) = [(Pf/Tf) - (Po/To)] * 100

**2. Índice de Satisfacción:**
Este indicador evalúa la satisfacción de los clientes a través de un aumento en las calificaciones promedio. El objetivo es lograr un incremento del 15% en el índice de satisfacción durante los próximos cuatro meses. Se calcula como la diferencia entre la calificación promedio actual (Rf) y la calificación promedio de hace cuatro meses (Ro), dividida por la calificación promedio de hace cuatro meses, multiplicada por cien.
*Fórmula:* Índice de Satisfacción (%) = ((Rf - Ro) / Ro) * 100

**3. Índice de Ingresos Potenciales:**
Este indicador busca medir el aumento en los ingresos potenciales a través de mejoras en las calificaciones. El objetivo es lograr un aumento de media unidad en la calificación promedio durante los próximos seis meses, equivalente a un incremento promedio del 3,5% en los ingresos. Se calcula como la diferencia entre la calificación promedio actual (Rf) y la calificación promedio de hace seis meses (Ro), multiplicada por siete.
*Fórmula:* Índice de Ingresos Potenciales (%) = (Rf - Ro) * 7

***KPI para Inversionistas***

**4. Tasa de Engagement de Usuarios Respecto a la Competencia:**
Este indicador evalúa el compromiso de los usuarios con respecto a la competencia, midiendo el aumento en el porcentaje de reseñas recibidas en comparación con el promedio de reseñas de negocios de la misma categoría durante seis meses. El objetivo es lograr un aumento del 20% en esta tasa de engagement durante los próximos seis meses. Se calcula como la diferencia entre el promedio de engagement logrado por un negocio (Px) y el engagement promedio del período anterior de seis meses (Po), multiplicado por cien.
*Fórmula:* Tasa de Engagement de Usuarios (%) = [(|Px - Pt| / Pt) - (|Po - Pto| / Pto)] * 100

Estos KPI's están diseñados para proporcionar información precisa y significativa para la toma de decisiones estratégicas en la industria de mascotas y sectores relacionados. Cada indicador se adapta a los objetivos específicos del análisis y refleja los intereses particulares de los comerciantes y los inversionistas. El análisis de datos y la inteligencia empresarial desempeñarán un papel crucial en el éxito de las operaciones y la toma de decisiones informadas en esta industria competitiva.

[Volver - Índice](#0-0)

## 5. Arquitectura del Proyecto<a class="anchor" id="1"></a>

**Implementación del Data Warehouse**

En el inicio de este proyecto, el primer paso consiste en cargar los datos en bruto proporcionados y almacenarlos en nuestro Data Warehouse. Un Data Warehouse es un sistema de almacenamiento de datos diseñado para almacenar grandes volúmenes de información en su formato original, eliminando la necesidad de una estructuración previa. Esto facilita un acceso rápido y flexible a los datos. En este caso, haremos uso de Google Cloud Storage para guardar los datos sin procesar provenientes de Google y Yelp.

Optamos por utilizar Azure Blob Storage / Google Cloud Services debido a su excepcional interfaz de usuario, altamente intuitiva y completa. Además, sus tarifas competitivas resultan un factor significativo en esta elección.

**Proceso de Transformación de Datos**

XXXXXXXXXXXXXXXXXXXXXXXXXXXX  FALTA XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXx

**Automatización a través de Cloud Functions**

Para gestionar la extracción, transformación y carga (ETL) de los datos, confiaremos en el servicio Google Cloud Functions y sus funciones. Esta tecnología nos permitirá automatizar el proceso ETL. Las funciones almacenadas en este servicio se vincularán a disparadores que detectan la incorporación de nuevos archivos en nuestro Data Lake. Una vez activados, las funciones de transformación trabajarán en la limpieza y el ajuste de los datos sin procesar. Posteriormente, los datos transformados serán almacenados en nuestro Data Warehouse.

Además, esta automatización simplificará la incorporación de nuevos datos. Una función específica se encargará de preparar y transformar los datos externos recién llegados, ejecutando seguidamente una consulta en Google BigQuery para actualizar nuestros registros actuales.

**Data Warehouse y su Impacto en el Análisis**

En este informe, explicaremos la implementación de un modelo de Data Warehouse para gestionar los datos de Google Maps y Yelp. Este proceso ETL, que implica extracción, transformación y carga, será detalladamente descrito. El enfoque de este modelo radica en su estructura basada en tablas relacionales predefinidas, lo que permitirá identificar conexiones y patrones en los datos, brindando una perspectiva integral y enriquecedora.

Utilizar este modelo favorece la toma de decisiones informadas y otorga una ventaja competitiva. El Data Warehouse nos provee de la capacidad para almacenar y analizar eficazmente volúmenes extensos de datos estructurados y semiestructurados. En paralelo, garantizamos la coherencia y calidad de los datos, así como la seguridad y el control de acceso. Este enfoque aporta la flexibilidad requerida para análisis exploratorios y la generación de informes. Adicionalmente, nos permite optimizar el rendimiento de consultas y análisis complejos. En resumen, la adopción de un modelo de Data Warehouse para los datos de Google Maps y Yelp refuerza nuestras capacidades de análisis, toma de decisiones y generación de informes en el contexto empresarial actual.

**Optimización de Análisis: Google BigQuery y Modelo Entidad-Relación**

En este proyecto, haremos uso de Google BigQuery como nuestro servicio de Data Warehouse para albergar y estructurar los datos procesados. Con Google SQL, seremos capaces de ejecutar consultas personalizadas, beneficiando tanto al equipo de Data Scientists como al equipo de Data Analytics al adaptar los datos a sus necesidades específicas.

Además, este Data Warehouse puede recibir actualizaciones continuas a medida que nuevos datos fluyen desde fuentes externas. Dentro de este proyecto, tenemos la intención de expandir nuestros datos mediante la extracción de información adicional a través de una API. Los detalles de este proceso se detallarán en la sección que aborda la API y su extracción.

**Modelo Entidad-Relación: Impulsando la Toma de Decisiones**

El Modelo Entidad-Relación (ER) despliega la estructura y las interacciones de los datos de Yelp y Google Maps. Incorpora entidades clave como "business," "User" y "Review", cada una con atributos pertinentes. Este modelo se revela esencial para la gestión de la reputación y la toma de decisiones estratégicas en inversiones rentables. Aporta claridad sobre la información esencial requerida para respaldar estas decisiones. La comprensión de la estructura de los datos nos empodera para implementar medidas efectivas para mejorar la reputación y optimizar la rentabilidad en la industria.

[Volver - Índice](#0-0)

## 5. Alcance del Proyecto<a class="anchor" id="1"></a>

**Alcance Temporal**
El proyecto se llevará a cabo en un período de seis semanas, divididas en tres Sprints, con una duración de dos semanas cada uno para segmentar las actividades. Durante las primeras cinco semanas, se completarán los hitos planificados, que incluyen la recolección de datos, análisis exploratorio y desarrollo de modelos de machine learning. La última semana se destinará a realizar ajustes, optimización y preparación de la presentación final.

**Alcance del Equipo**
El equipo está compuesto por dos miembros, cada uno asumiendo roles específicos de ingeniero de datos, científico de datos y analista de datos. Como ingenieros, nos encargamos de la recolección y depuración de datos; como científicos, desarrollamos modelos de machine learning orientados al análisis de sentimientos y sistemas de recomendación. Además, como analistas, llevamos a cabo el análisis exploratorio de los datos, extrayendo insights y datos relevantes para enriquecer el modelo de negocios. Cada miembro desempeñará funciones específicas para colaborar en todas las etapas. La comunicación y coordinación serán cruciales para integrar exitosamente los componentes del proyecto.

**Alcance Financiero**
El alcance financiero del proyecto se enfoca en la utilización de herramientas y recursos gratuitos, sin contar con un presupuesto asignado. El equipo buscará aprovechar opciones gratuitas para cumplir eficientemente con los objetivos del proyecto de la prueba piloto.

**Alcance de la Prueba Piloto**
Basándonos en la data suministrada y un minucioso estudio de mercado, se establecieron criterios para asegurar la escalabilidad y parametrización de nuestro producto. Para lograrlo, se consideraron tres parámetros clave. En primer lugar, se analizó el aspecto demográfico, estableciendo un tamaño de muestra representativo a través de un ranking descendente de los estados con mayor densidad poblacional. En segundo lugar, se evaluó el marco sociocultural de diferentes regiones territoriales de Estados Unidos, teniendo en cuenta la diversidad generacional, étnica, cultural y otros factores que influyen en los hábitos de consumo. Por último, se incorporó el índice de criminalidad como variable significativa, considerando los tipos de negocios involucrados y las necesidades del cliente. Se seleccionaron como estados modelo: New Jersey, California y Florida. El enfoque del proyecto se centrará en empresas relacionadas con la categoría 'Pets Care' y similares, estableciendo un modelo parametrizable en los Estados Unidos.

**Aspectos Excluidos del Alcance**

Con base en los criterios de selección muestral del proyecto y considerando su naturaleza escalable y parametrizable, hemos tomado la decisión de no incluir el análisis de datos provenientes de los 48 estados restantes, ni considerar categorías ajenas al mercado de "Pet Care".

Adicionalmente, se ha determinado que no se abordará el desarrollo de un tercer modelo de aprendizaje automático (Machine Learning) para presentar al empresario. Este modelo hipotético tendría la capacidad de realizar predicciones relacionadas con el crecimiento futuro o la ubicación óptima para nuevos negocios.

**Alcance de Impacto:**
El proyecto tiene como objetivo impactar tanto a empresarios como a clientes al proporcionar información valiosa sobre la percepción de los inversionistas y brindar recomendaciones personalizadas. Esto permitirá a los empresarios tomar decisiones estratégicas informadas y mejorar la experiencia del cliente. Mediante datos depurados, análisis exploratorio, modelos de machine learning y un dashboard interactivo, se optimizará la toma de decisiones, la experiencia del cliente y la relación entre ambas partes.

[Volver - Índice](#0-0)

**[Herramientas a usar](#)**:
1. Google Drive
2. MongoDB
3. Cosmos DB
4. Spark
5. SQLite 3
6. Azure (ABS, ADF, Functions)
7. DataBricks
8. Python
9. Visual Studio Code
10. Google Colab
11. Looker Studio

[Volver - Índice](#0-0)