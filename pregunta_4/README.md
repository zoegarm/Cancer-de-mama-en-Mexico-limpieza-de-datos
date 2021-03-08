## 4. ¿Qué países han logrado manejar el problema de manera adecuada?

#### **Introducción**

El cáncer es una enfermedad que aqueja a todas las poblaciones del mundo, sin embargo, la incidencia de este padecimiento así como las estrategias para combatirlo son distintas en cada país. Es por ello que en este apartado revisaremos el gasto destinado a salud por los países miembros de la Organización para la Cooperación y el Desarrollo Económico (OCDE), del cual forma parte México. Asimismo, revisaremos indicadores sobre la incidencia del cáncer de mama en dichos países, con el fin de relacionar el gasto devengado en materia sanitaria con las estrategias para combatir el cáncer y sus resultados.

>_“Se prevé que la carga mundial de cáncer aumente a 30,2 millones de casos en 2040, casi un 50% más que en 2020. Las predicciones por Índice de Desarrollo Humano (IDH) muestran que los mayores aumentos relativos se producirán en los países clasificados con IDH bajo (Global Cancer Observatory, 2020).”_

El cáncer sigue siendo un importante reto sanitario en todos los países de la OCDE. Cada año se diagnostican más de 5 millones de nuevos casos en estos países, con una media de aproximadamente 261 casos por cada 100 000 personas. Ante este escenario, no todos los países  están haciendo lo necesario en su lucha contra el cáncer. Se estima que en un tercio de los casos, la enfermedad podría curarse si se detectara a tiempo y recibiera un tratamiento adecuado, y en otro tercio, podría prevenirse totalmente si se adoptaran más medidas de mayor profundidad en materia de salud pública (OCDE, 2013).

>_"La carga financiera asociada al cáncer también está aumentando. El impacto económico global de las muertes prematuras y la discapacidad causada por el cáncer es de alrededor de 900 000 millones de dólares, superando al de los infartos de miocardio (OCDE, 2013)."_

#### **Desarrollo**
Para poder responder a la inerrogante planteada, realizamos una búsqueda de fuentes de información que incluyeran indicadores de diferentes países en materia de salud y cáncer de mama, con el fin de realizar una comparación. Optamos por utilizar datos para los países miembros de la OCDE, ya que nuestro país forma parte dicha organización, misma que plantea cuenta con índices y estándares encaminados a lograr el objetivo del milenio de la Organización de las Naciones Unidas (ONU) en materia de cobertura de sanitaria universal.
Se encontraron dos conjuntos de datos, uno es la base de datos global de gastos en salud de la Organización Mundial de la Salud (OMS) y el segundo es el status del cancer en las estadísticas de salud de la OCDE. El procesamiento de datos se hizo de la siguiente forma:

1. Lectura de las bases de datos almacenadas en la carpeta DATA de este repositorio de Github.
2. Revisión de la estructura de los DataFrame.
3. Limpieza de las base de datos:
   - Renombrado de columnas,
   - Cambio del tipo de datos,
   - Cambio de índices, 
   - Conteo y eliminación de NaN,
   - Eliminación de columnas y filas.
4. Procesamiento y análisis exploratorio de datos:
   - Agregaciones,
   - Agrupamientos.

#### Referencias:
Global Cancer Observatory (2020). “Predicted Global Cancer Burden in 2040”, Cancer Tomorrow, Global Cancer Observatory. Recuperado de: https://infogram.com/globocan-2020-1h9j6qg7xdp8v4g?live

OCDE (2013), “Multilingual Summaries. Cancer Care. Assuring Quality to Improve Survival”, Paris: OECD Publishing. Recuperado de: https://www.oecd-ilibrary.org/docserver/9789264181052-sum-es.pdf?expires=1615176128&id=id&accname=guest&checksum=37764D7F6495F9BA44946F4EE818B4E2 

#### Bases de datos:
OCDE (1 de julio de 2020). “Health Status: Cancer”, OECD Statistics technology, Organización para la Cooperación y el Desarrollo Económico (OCDE). Recuperado de:
https://stats.oecd.org/index.aspx?queryid=30121#

OMS (2 de marzo de 2021). “Global Health Expenditure Database (GHED)”, Data Explorer, Organización Mundial de la Salud (OMS). Recuperado de: https://apps.who.int/nha/database/Select/Indicators/en 
