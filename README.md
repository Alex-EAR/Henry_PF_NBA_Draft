# Henry_PF_NBA_Draft
Proyecto Final para curso DA en Henry

### Martes 29 de octubre
El equipo de trabajo recibe el dataset de parte del cliente orientado a la industria de los Deportes, más particularmente enfocado al Básquet, con el eje puesto en la NBA (National Básquet Asociation) de los Estados Unidos. La franquicia Sacramento Kings busca mejorar sus procesos de reclutamiento debido a sus malos desempeños anteriores.

### Jueves 31 de octubre
El equipo de trabajo eleva la propuesta "Análisis de datos del Draft de la NBA para la mejora en el reclutamiento de Sacramento Kings" centrada en apoyar a la franquicia en realizar selecciones más fundamentadas, minimizando el riesgo y maximizando el rendimiento futuro de sus plantillas.

El análisis está centrado en datos históricos y tendencias de desempeño en el Draft, a fin de mejorar su toma de decisiones en el reclutamiento, ya que el equipo se vio afectado en los últimos años por elecciones de draft que no ofrecieron los resultados esperados, algo que influyó en su competitividad en la liga.

Se espera como resultado previsible para Sacramento Kings: identificar perfiles de jugadores con alto potencial de rendimiento y factores que predicen éxito en la NBA, algo que permitirá a la franquicia optimizar sus decisiones y mejorar el proceso de selección en función de estadísticas clave y tendencias exitosas. En el largo plazo, esto contribuiría a elevar el nivel competitivo de los Kings, así como a generar una percepción positiva tanto en los fanáticos como en los patrocinadores, fortaleciendo la posición de la franquicia en la liga. 

Fuente de datos: NBA dataset ofrecido por el cliente desde kaggle.com, que cuenta con actualización regular, información de 30 equipos, +4800 jugadores, todos los juegos desde la inauguración de la NBA y +13 millones de jugadas registradas. Periodo de análisis: año 2000 en adelante. 

Flujo de trabajo: 1. Fase de Exploración de Datos. 2. Fase de Análisis. 3. Visualización y Reporte. 4. Ronda de Validación y Presentación. Tecnologías: SQL Server, Python (Numpy, Pandas, Matplotlib, Seaborn) y Power BI Copilot y ChatGPT.

### Viernes 1 de noviembre
La propuesta "Análisis de datos del Draft de la NBA para la mejora en el reclutamiento de Sacramento Kings" es aprobada por el cliente y el equipo de trabajo realiza su primera reunión para establecer el flujo de trabajo para las dos semanas estipuladas para el desarrollo.

### Sábado 2 de noviembre a martes 5 de noviembre

Se lleva adelante el proceso de ETL, atendiendo a las tareas especificadas en el Sprint 1: Identificación de entidades/tablas necesarias y definición de relaciones; Diseño de flujo de ingesta de datos inicial y normalización; Creación del repositorio y definición de permisos; Subida del Dataset y estructuración de la carpeta en la nube para el análisis; Creación del diseño y la estructura de la base de datos en el entorno de SQL; Creación el Diagrama de Entidad Relación (DER).

**Carpetas y archivos disponibles**: 

(Carpeta) Dataset Comprimido - (Subcarpeta) xlsx (con columnas formateadas) - Comprimido en partes. Es mas rápida la descarga y descompresión que la transformación de datos - Compresión en partes de las carpetas 'Filtrados' y 'Originales'. En la extracción usar la opción 'Extraer aquí' para que mantenga compatibilidad con scripts en el repositorio que accedan a archivos de estas ubicaciones - info_eventmsgtype.csv es una tabla con una descripción simple de los codigos de la columna 'eventmsgtype' en la tabla 'play_by_play' - 

(Carpeta) Limpieza y transformaciones: - .ipynb con 1er limpieza y filtro - .txt con descripción de la primer limpieza - .ipynb con transformación de los .csv filtrados a .xlsx (con columnas en formato adecuado) - .ipynb con exportación de los .csv filtrados a una BD vacia previamente creada en SQL Server

### Miércoles 6 de noviembre y jueves 7 de noviembre

Se define el método de automatización para la actualización de datos y se lleva adelante el proceso de EDA considerando los objetivos del proyecto y análisis estadístico inicial, avanzado y modelado, permitiendo identificar patrones clave que puedan ayudar a describir el rendimiento de los equipos y jugadores y correlaciones. Asimismo, se prepara la presentación de resultados para la Demo 1, considerando ejes del proyecto, ETL, EDA y Mockup.

### Viernes 8 de noviembre

Se realiza la presentación de resultados en la Demo 1, considerando ejes del proyecto, ETL, EDA y Mockup.