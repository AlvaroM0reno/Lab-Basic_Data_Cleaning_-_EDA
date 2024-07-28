Laboratorio | Limpieza básica de datos y EDA
Para este laboratorio, utilizaremos el conjunto de datos del caso de negocio de análisis de clientes. Este conjunto de datos se puede encontrar en la files_for_labcarpeta.

Contexto
Una compañía de seguros de automóviles ha recopilado algunos datos sobre sus clientes, incluidos sus datos demográficos , educación , empleo , detalles de la póliza , información del vehículo sobre el que se aplica la póliza y montos de las reclamaciones . Ayudará a la alta gerencia con algunas preguntas comerciales que deberían ayudarlos a comprender mejor a sus clientes, mejorar sus servicios y mejorar la rentabilidad.

Algunos objetivos comerciales para el caso de estudio podrían ser :

Retener clientes,
Analizar datos relevantes de los clientes,
Desarrollar programas enfocados en retención de clientes.
Con base en el análisis, tome acciones específicas para aumentar la respuesta, la retención y el crecimiento rentables de los clientes.

Instrucciones
Importar las bibliotecas necesarias.
Cargar we_fn_use_c_marketing_customer_value_analysis.csven la variable customer_df(es decir customer_df = pd.readcsv(""))
Primero, veamos sus características principales ( head, shape, info).
Cambie el nombre de las columnas para que sigan el PE8 (caso de serpiente).
Corrija los tipos de datos de cualquier otra columna o columnas según lo considere necesario. Tenga en cuenta que, a veces, hay algunas características que podría querer usar como categóricas, pero Python las lee como numéricas (y viceversa). Por ejemplo, si hay una columna con valores de año como 2020, 2021, 2022, etc., Python podría leer esta columna como numérica, pero usted querría usar esa columna como datos categóricos. Sugerencia : una cosa que puede intentar es cambiar la columna de fecha al formato de fecha y hora.
Dibuje una matriz de correlación y comente lo que observe.
Grafica cada variable continua. Comenta lo que puedes ver en los gráficos.
Haz lo mismo con las variables categóricas (ten cuidado, ¡puede que necesites cambiar el tipo de gráfico a uno más adecuado para datos continuos!). Comenta lo que puedes ver en los gráficos. También debes eliminar la columna customer_idantes de poder intentar usar un bucle for en todas las columnas categóricas. Explica por qué es customer_idnecesario eliminar la columna. Sugerencia : usa gráficos de barras para representar gráficamente datos categóricos, con cada categoría única en la columna en el eje x y una medida apropiada en el eje y.
Busque valores atípicos en las variables continuas. ( Pista : ¡hay un buen gráfico para hacerlo!). En caso de que encuentre valores atípicos, comente qué hará con ellos.
Comprueba todas las columnas en busca de valores NaN . Decide qué necesitarás hacer con ellos (si es que necesitas hacer algo).
