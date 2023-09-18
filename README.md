# Demo librería MITO

MITO es una biblioteca de Python diseñada para simplificar la manipulación de dataframes, brindando una perspectiva similar a la de una hoja de cálculo. Esto facilita la exploración, limpieza y comprensión de los datos a través de herramientas interactivas.

En este material, aprenderemos a instalar MITO, configurar su utilización y emplear sus funciones principales. Además, exploraremos funciones en desarrollo que en un futuro facilitarán el proceso de limpieza y gestión de datos.

Las funciones generales de MITO incluyen:
- Edición interactiva de hojas de cálculo.
- Realización de análisis exploratorio de datos sin necesidad de escribir código.
- Generación automática de código Python a partir de las modificaciones realizadas.
- Utilización de inteligencia artificial para explorar y modificar dataframes.

Documentación de la librería en https://docs.trymito.io/

### Requerimientos

- Python versión 3.6 o superior
    - Puedes verificar la versión de python mediante ventana comando
        ```sh
         python --version
         ```
- Requiere instalar Anaconda con versión python 3.6 o superior
    - Last release: https://www.anaconda.com/download
- Requiere el uso de Jupyter Lab
    - Puedes instalar JupyterLab mediante ventana comando
        ```sh
            pip install jupyterlab
         ```
### Instalación

Usaremos la opción de instalación en un entorno virtual Anaconda Navigator, esto para evitar conflicto con otras librerías instaladas.

- Abrir Anaconda Navigator
- Seleccionar Entornos (Environments) en el menú de la izquierda
- Crear un nuevo entorno virtual con el botón "Create" en la zona inferior, lo llamaremos "MITOenv"
- Una vez creado el entorno, cambie a Inicio y seleccione el entorno MITOenv que acaba de crear.
- Luego de seleccionar el entorno, abrir Anaconda Prompt e instalar Mito con los siguientes comandos:

        python -m pip install mitoinstaller
        python -m mitoinstaller install
        
### Ejemplo

El ejemplo será utilizando dataset de kaggle de datos del Titanic. https://www.kaggle.com/datasets/brendan45774/test-file

Las funciones que se desarrollarán son:
- Importar datos
- Gráficas en Mitosheets
- Agrupar y filtrar
- Estadísticas resumen
- Cambios de formato de datos
- Uso de IA para modificar dataframe
- Entre otras funciones

Para ejecutar una hoja MitoSheets en jupyter Lab se utilizan las siguientes líneas:
        ```sh
            import mitosheet
            mitosheet.sheet()
         ```


Al ser una herramienta gráfica de manejo de dataset, se genera código a medida que se va utilizando la librería, como resumen se entrega el código final de las modificaciones realizadas que se puede ver en el video adjunto.

Encontrarán código ejemplo  en la carpeta MITO_Titanic.ipynb


.-
