 PROYECTO FINAL  
“AQUÍ ME UBICO” es un buscador que ayuda a las compañías a encontrar la ubicación óptima para abrir su centro logístico. Me he centrado en Andalucía y segmentado la comunidad por códigos postales. 
Objetivo: Crear un buscador, que ayude a las empresas a encontrar la ubicación para abrir su centro logístico. 

Pasos: 
-   Buscar información sobre los municipios de Andalucía. 
-   Scrapear datos del INE: Tabla censados, paro, empresas. 
-   Scrapear de Mndominio: Tabla precio. 
-   Limpiar y adaptar las tablas en Python (Proyecto_final). 
-   Crear conexiones en SQL. 
-   Pasar la información a Power BI, realizar las métricas y realizar buscador interactivo. 

Dataframe y Variables: 
-   Censado: personas censadas por municipio, segmentadas por sexo y edad. El registro de datos es desde 2012 a 2021. 
-   Paro: recopila el número de parados registrados desde 2012 a 2021, por mes, municipio, provincia, género, rango de edad y experiencia en sector empresarial.
-   Empresas: total de empresas registradas por municipio y provincia entre 2012 y 2021 y actividad económica. 
-   Precio: precio medio por metro cuadrado de venta y alquiler de cada municipio. 

Código y dashboard
-   Proyecto final ( Power BI): visualización de los datos. En las primeras pestañas aparece información general de cada municipio, todas ellas con interactivas y en la última pestaña tienes el modelo de buscador para encontrar el ubicación óptima. 
-   Proyecto Final (Python): limpieza y manipulación de datos para pasar a SQL y relacionar las tablas. 
