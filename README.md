# Proyecto de Segmentación de Hogares para Intervenciones Personalizadas

Este repositorio contiene el código, datos y resultados preliminares de un proyecto diseñado para segmentar hogares en Colombia y permitir la creación de intervenciones más personalizadas. Basado en el Estudio de Medición de Pobreza Monetaria y Desigualdad (DANE, 2023), el proyecto utilizará técnicas de clustering para identificar patrones en pobreza y desigualdad. La iniciativa culminará en el desarrollo de una herramienta analítica que proporcionará a CARE una interfaz intuitiva para explorar los datos segmentados, visualizar segmentos de hogares e individuos, analizar sus características específicas y de manera que CARE pueda generar recomendaciones basadas en datos para diseñar intervenciones personalizadas. La herramienta incluirá funcionalidades para la generación de informes en función de los patrones identificados en los datos.

## Estructura del Repositorio

El repositorio está organizado en las siguientes carpetas:

- **`data/`**: Contiene los archivos de datos utilizados en el proyecto. Incluye `df_hogares` y `df_personas` con información económica y social de los hogares e individuos.
- **`códe/`**: Contiene los scripts y notebooks que se utilizarán para el procesamiento de datos, la aplicación de algoritmos de clustering y el desarrollo de la herramienta analítica.
- **`docs/`**: Contiene la documentación del proyecto, incluyendo el informe final y cualquier otro documento relevante para la entrega del proyecto.

## Preprocesamiento de Datos

El preprocesamiento de datos se realiza a través de un Jupyter Notebook que se encuentra en la carpeta `códe/` llamado `analisis_data.ipynb`. En este notebook, se lleva a cabo el proceso de:

- **Carga de Datos**: Importación de los archivos `df_hogares` y `df_personas`.
- **Preprocesamiento**: Limpieza de datos y manejo de valores nulos.
- **Análisis Estadístico**: Exploración de estadísticas descriptivas y visualización de datos para entender mejor las características de los DataFrames.

El notebook proporciona documentación detallada y explicaciones sobre las técnicas empleadas para la limpieza de datos y el manejo de valores nulos. Puedes utilizar este notebook para replicar los análisis y comprender las decisiones tomadas en cada etapa del preprocesamiento.

## Cómo Ejecutar el Código

1. **Configurar el Entorno de Python**:

    - **En Windows**:
      1. Asegúrate de tener [Python](https://www.python.org/downloads/) instalado en tu sistema.
      2. Abre una terminal (Command Prompt o PowerShell) y navega al directorio del proyecto.
      3. Crea un entorno virtual con el siguiente comando:
         ```bash
         python -m venv env
         ```
      4. Activa el entorno virtual:
         ```bash
         .\env\Scripts\activate
         ```

    - **En macOS**:
      1. Asegúrate de tener [Python](https://www.python.org/downloads/) instalado en tu sistema.
      2. Abre una terminal y navega al directorio del proyecto.
      3. Crea un entorno virtual con el siguiente comando:
         ```bash
         python3 -m venv env
         ```
      4. Activa el entorno virtual:
         ```bash
         source env/bin/activate
         ```

2. **Instalar Dependencias**: Una vez que el entorno virtual esté activado, instala las dependencias necesarias utilizando el archivo `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

3. **Preprocesamiento de Datos**: Abre el Jupyter Notebook en la carpeta `código/` para cargar, preprocesar y analizar los datos.

## Contribuciones

Si deseas contribuir al proyecto, por favor abre un issue o envía un pull request con tus propuestas. Asegúrate de seguir las mejores prácticas y de documentar cualquier cambio realizado.

## Contacto

Para cualquier consulta relacionada con el proyecto, puedes contactar a los siguientes integrantes del equipo:

- **Sonia Olaya**: [sk.olaya@uniandes.edu.co](mailto:sk.olaya@uniandes.edu.co)
- **Kelly Niño Ramirez**: [k.nino@uniandes.edu.co](mailto:k.nino@uniandes.edu.co)
- **Guillermo Ariza**: [ga.ariza2@uniandes.edu.co](mailto:ga.ariza2@uniandes.edu.co)
- **Juan Carlos Acosta**: [jc.acosta12@uniandes.edu.co](mailto:jc.acosta12@uniandes.edu.co)
- **Laura Cristina Martinez**: [lc.martinezc1@uniandes.edu.co](mailto:lc.martinezc1@uniandes.edu.co)
