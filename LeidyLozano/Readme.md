Para dar solución al reto propuesto, me enfoque en el control y seguimiento de los indicadores entregados de los diferentes ejes (Seguridad, Salud, Ambiente, Abastecimiento) a través del diseño de un tablero de control de estadísticas descriptivas que permite identificar tendencias y comportamiento para apoyar la toma de decisiones en la ciudad de Bucaramanga y el área metropolitana. 

Construí dos vistas: Indicador por mes y comparativo histórico. Ambas vistas se encuentran terminadas y funcionales. Fueron desarrolladas utilizando la versión pública de Tableau, esta permite su utilización de forma gratuita pero los resultados son compartidos en repositorio de forma pública. Pueden acceder a ellas a través de la siguiente url: https://public.tableau.com/profile/leidy.alexandra#!/vizhome/Reto-BGA/Dashboard?publish=yes 

Elegí esta herramienta debido a la facilidad y rapidez que ofrece para realizar este tipo de proyectos dadas las condiciones que se tenían en el reto (tiempo y características). La información de la que se alimenta es el dataset entregado y los datos de casos reportados de COVID-19 publicada por el Instituto Nacional de Salud (INS). Esta información fue procesada y se encuentra en una base de datos en Excel.

Las técnicas de análisis utilizadas fueron: comparación de variables en el tiempo y relación de información que favorecen el análisis exploratorio dependiendo los intereses de los usuarios analistas.

La primera vista, indicador por mes, permite analizar el comportamiento de un indicador seleccionado durante todo un mes, esto nos facilita la identificación de patrones de comportamiento y variaciones  en el tiempo que pueden ser causadas por eventos independientes como las medidas de toque de queda o cuarentena dadas por los entes encargados. Por esta razón y teniendo en cuenta que el COVID-19 es el evento del cual queremos tener referencia, adicioné dicha información que facilita la interpretación o relación de los datos. 

Para la segunda vista, comparativo histórico, el tablero de control permite visualizar 1 o más indicadores a la vez, esto con el fin de encontrar relaciones causa-efecto, tendencias en el tiempo y comportamientos de los indicadores. Adicionalmente, se podría comparar diferentes municipios si fuese requerido y relevante.

El valor diferenciador de la solución propuesta es la rapidez con que se pueden realizar las visualizaciones para facilitar el análisis de los datos, adicionalmente, la interactividad que permite la herramienta para poder hacer un análisis más flexible dependiendo el interés de los analistas.

Para la implementación de una solución completa, yo realizaría:

-	Una fase inicial de levantamiento y definición de requerimientos que permita un entendimiento y conocimiento claro y preciso de las necesidades que se quieren resolver. (48 horas)
-	Una fase de análisis y diseño de la solución que a partir de la priorización de los requerimientos anteriormente definidos permitan elegir la mejor arquitectura y tecnología, definir los datos con los que se cuenta y los que se requieren conseguir, definir los tipos de análisis y las visualizaciones más adecuadas para presentar dicha información. (96 horas)
-	 Con base en los resultados de esas dos fases, procedería a realizar la implementación (frontend, backend y datos(ETL y modelos)) y pruebas empleando una metodología SCRUM que permita tener resultados parciales rápidos. (Interacciones de 48 o 96 horas  dependiendo las necesidades del proyecto).

#Nota: Si para la implementación de la solución que se desea realizar ya se tienen definidas las fases de levantamiento de requerimientos, análisis y diseño y procesamiento y se decidiera utilizar Tableau como herramienta de implementación, el tiempo que emplearía para el desarrollo variaría entre 8 y 16 horas por vista dependiendo de la complejidad de la vista y el proceso ETL de los datos que se requiera.
