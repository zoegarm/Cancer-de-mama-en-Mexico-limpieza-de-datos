## 2. ¿Cuál es la relación entre los gastos de salud y los resultados en su política en la lucha contra el cáncer?

#### **Introducción**
En este apartado revisaremos cual ha sido el actuar gubernamental en torno a la dotación de presupuesto para combatir esta enfermedad. Para ello, analizaremos dons conjuntos de datos. En primer lugar, la designación de presupuesto para la salud en México por estado de la República, la base de datos comprende el periodo 1993-2017. En segundo lugar, la tasa y números absolutos de mortalidad por cáncer de mama por estado de la República de 200 a 2015. La fuente de ambas bases de datos es la Secretaría de Salud (SSA).

#### **Contexto del estudio y su importancia**
El cáncer es un grupo de muchas enfermedades relacionadas que empiezan en las células cuando presentan daños. Normalmente las células crecen y se reproducen para generar más y mantener sano el cuerpo. Algunas veces este proceso ordenado se descontrola: nuevas células se siguen formando, aunque el cuerpo no las necesite y las viejas no mueren cuando deberían. 

>_"A nivel mundial, el cáncer es una enfermedad que va en aumento y es considerada como una de las principales causas de muerte (OMS, 2014)"._

Las células excesivas forman una masa de tejido que se llama tumor. No todos los tumores son cancerosos; pueden ser benignos o malignos (Infocancer, 2021).
1. Los benignos no son cancerosos. Generalmente se pueden extraer y, en la mayoría de los casos, no reaparecen.
2. Los malignos son cancerosos. Las células en los tumores malignos tienen anomalías y se dividen sin control y sin orden. Estas células cancerosas pueden invadir y destruir el tejido a su alrededor. Además, pueden desprenderse de un tumor maligno y entrar al torrente sanguíneo o al sistema linfático.

>_"La Sociedad Mexicana de Oncología (SMeO) considera que además las elevadas cifras de muertes por cáncer se deben a los diagnósticos tardíos. El 60% de los casos de cáncer en México es detectado en etapas avanzadas (SMeO, 2016)."_

Entre el 30% y el 50% de los padecimientos de cáncer se pueden evitar (Juntos contra el cáncer, 2021). Por ello es necesario:
- Reducir los factores de riesgo
- Aplicar estrategias preventivas con base científica
- - Detección oportuna
- - Tratamiento de los pacientes

En resumen, para poder combatir la incidencia y mortalidad del cáncer, se requiere por un lado, atender los factores desencadenantes y por el otro, aplicar una política pública que incluya la detección temprana y efectiva del cáncer así como su tratamiento. Para todo ello, se requieren recursos materiales y humanos enfocados en la salud. En esta sección indagaremos cual ha sido el presupuesto para salud por Estado de la República y lo relacionaremos con los indicadores de mortalidad por cancer de mama con el fin de dilucidar si la dotación de presupuesto para combatir esta enfermedad ha sido adecuada.

#### **Desarrollo**
En primer lugar, realizamos una búsqueda de información sobre el tema, con el fin conocer más a fondo la problemática e identificar bases de datos útiles para responder a la pregunta de investigación. En segundo lugar, obtuvimos las bases de datos y as almacenamos en el repositorio para su análisis. En tercer lugar, implementamos el tratamiento de los datos. A continuación se describe el procesamiento de datos aplicados. 

1. Lectura de las bases de datos almacenadas en la carpeta DATA de este repositorio de Github.
2. Revisión de la estructura de los DataFrame.
3. Limpieza de las base de datos:
- - Renombrado de columnas,
- - Cambio del tipo de datos,
- - Cambio de índices, 
- - Conteo y eliminación de NaN,
- - Eliminación de columnas y filas.
4. Análisis exploratorio de datos:
- - Agregaciones,
- - Agrupamientos.
