# Análisis de Datos para la mejora en el reclutamiento de Sacramento Kings 

A continuación, se detalla el contenido de cada carpeta y se ofrecen recomendaciones para navegar por el repositorio de manera eficiente.

## Estructura de Carpetas

### 1. **Dashboard**
   - **Imágenes**
     - `Mockup_v3.pdf`: Documento en formato PDF que contiene el diseño conceptual del dashboard en su versión.
     - `PF_Dashboard_Kings_v.0.7.pbix`: Archivo en formato `.pbix` correspondiente al dashboard de Power BI.
   - **Descripción**: Es ideal para quienes quieran ver la visualización final del proyecto o entender el concepto del diseño.

### 2. **Dataset**
   - **Filtrados**: Carpeta que contiene archivos con datos procesados o filtrados específicos para el análisis.
   - **Originales**: Carpeta con los datos originales obtenidos, sin modificaciones ni limpiezas.
   - **Descripción**: Esta carpeta es el repositorio de datos base del proyecto. Se pueden revisar tanto datos `Originales` como `Filtrados`.

### 3. **KNIME Workflow**
   - **Datadraft2**
     - `Credenciales.txt`: Archivo de texto que contiene las credenciales necesarias para la conexión de datos en KNIME.
     - `MANUAL DE USUARIO DEL KNIME...`: Documento con instrucciones sobre el uso del flujo de trabajo en KNIME.
   - **Descripción**: Contiene el flujo de trabajo y documentación de KNIME, orientado a la extracción y procesamiento de datos. 

### 4. **Limpieza y Transformaciones**
   - `DER NBA_Filtrado.png`: Diagrama de Entidad-Relación (DER) que representa la estructura de los datos después de la filtración.
   - `Proceso de limpieza.txt`: Archivo de texto que detalla el proceso de limpieza aplicado a los datos.
   - `Transformacion.ipynb`: Cuaderno de Jupyter que documenta los pasos de transformación de datos.
   - `csv's_a_sql.ipynb`: Cuaderno de Jupyter con conversiones de archivos CSV a SQL.
   - `csv's_a_xlsx.ipynb`: Cuaderno de Jupyter con conversiones archivos CSV a Excel.
   - **Descripción**: Incluye los recursos utilizados para limpiar y transformar los datos, así como guías para exportar datos a otros formatos. 

### 5. **Imágenes**
   - `Tablero_Scrum.png`: Imagen que muestra el tablero Scrum utilizado para la planificación y gestión de tareas del proyecto.
   - **Descripción**: Esta carpeta contiene imágenes relacionadas con la planificación y el desarrollo del proyecto, útil para obtener contexto sobre el progreso y organización del equipo.

### 6. **EDA**
   - `EDA.ipynb`: Cuaderno de Jupyter que contiene el Análisis Exploratorio de Datos (EDA).
   - `PI_EDA.docx`: Documento en formato Word con un informe detallado del EDA.
   

`README.md`: Este archivo README que contiene la descripción de todo el proyecto y sus componentes.
- **Descripción**: Aquí se encuentran los análisis y reportes que documentan la exploración inicial de los datos, ideales para entender los primeros hallazgos del proyecto.

## Recomendaciones de Navegación

1. **Inicio**: Revisa este archivo `README.md` para obtener una visión general del proyecto.
2. **Datos**: Comienza por la carpeta `Dataset` para entender los datos originales y luego revisa `Limpieza y Transformaciones`.
3. **Análisis**: Los archivos en `Archivos de Análisis` son útiles para comprender los hallazgos iniciales del proyecto.
4. **Dashboard**: Revisa `Dashboard` para ver el diseño y la versión actual del tablero de Power BI.
5. **KNIME Workflow**: Si deseas reproducir o analizar el flujo de trabajo de KNIME, visita esta carpeta y sigue las instrucciones del manual.
