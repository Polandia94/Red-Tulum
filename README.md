# Red-Tulum
Archivos para la carga de datos de Red Tulum

Para la modificación del sistema de transporte de la Ciudad de San Juan fue necesario establecer un ID único y nombre a cada parada de colectivo de la provincia.
Así mismo se debía establecer un sistema que permitiera, al colocar el ID de la parada, marcada en un mapa, completara el resto de la parada.
Para esto se diseñaron 2 google sheets. Uno para cargar los datos de las paradas, llamado sectores, que colocando los numeros de Departamento, Seccion, Sector y parada genera el ID. Y Busca ese ID en una archivo de coordenadas que solo tiene parte de los datos para el ID,utilizando mecanismos de validación
Por otro lado se generó un archivo para la carga de lineas, que colocando esos mismos datos generé el ID, y los busque en los documentos de sectores, para mejorar la efectividad de la carga

Se presentan los documentos con pocas paradas cargadas, debido a que no poseen carácter público.
