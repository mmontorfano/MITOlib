# Demo librería MITO

MITO es una biblioteca de Python diseñada para simplificar la manipulación de dataframes, brindando una perspectiva similar a la de una hoja de cálculo. Esto facilita la exploración, limpieza y comprensión de los datos a través de herramientas interactivas.

En este material, aprenderemos a instalar MITO, configurar su utilización y emplear sus funciones principales. Además, exploraremos funciones en desarrollo que en un futuro facilitarán el proceso de limpieza y gestión de datos.

Las funciones generales de MITO incluyen:
- Edición interactiva de hojas de cálculo.
- Realización de análisis exploratorio de datos sin necesidad de escribir código.
- Generación automática de código Python a partir de las modificaciones realizadas.
- Utilización de inteligencia artificial para explorar y modificar dataframes.

Documentación de la librería en https://docs.trymito.io/

### Objetivo

El propósito de esta explicación sobre esta librería es introducir una herramienta novedosa e innovadora que simplifica la gestión, limpieza y análisis exploratorio de datos, labores a las que con frecuencia se enfrentan los científicos de datos.

Mediante el empleo de esta librería, es posible obtener un conjunto de datos depurado y explorado. Esto se logra a través de un proceso interactivo con una secuencia de instrucciones que simplifica la ejecución de tareas sin requerir la programación de códigos.

### Conceptos

- Librería: Una librería en Python es como una colección de herramientas especializadas que los programadores pueden usar en sus proyectos. Estas herramientas ya están hechas y listas para usar, lo que ahorra mucho tiempo y esfuerzo en la programación. Por ejemplo, si necesitas hacer cálculos matemáticos complicados, puedes usar una librería que ya tiene esas funciones listas. Es como tener un conjunto de herramientas listas para diferentes tipos de trabajo, pero en el mundo de la programación.
  
- Entorno virtual: Un entorno virtual en Python es como un espacio aislado donde puedes instalar y usar diferentes versiones de Python y sus bibliotecas para cada proyecto que estés trabajando. Esto es muy útil cuando tienes varios proyectos en curso y cada uno requiere configuraciones específicas. Imagina tener compartimentos separados para distintas herramientas, de esta manera cada proyecto tiene su propio espacio y no hay confusiones. Esto garantiza que un proyecto funcione de la misma manera sin importar en qué computadora se ejecute.
  
- Ventana de comandos: La ventana de comandos es como una herramienta de texto en la computadora donde puedes dar instrucciones directas al sistema operativo. En vez de usar clics de ratón, escribes comandos para hacer cosas como abrir programas, moverte por archivos o ejecutar programas.
  
### Requerimientos

- Python versión 3.6 o superior
    - Puedes verificar la versión de python mediante ventana comando
        ```sh
         python --version
         ```
- Requiere instalar Anaconda con versión python 3.6 o superior
    - Last release: https://www.anaconda.com/download
- Requiere el uso de Jupyter Lab 3.0 o superior
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

            import mitosheet
            mitosheet.sheet()

Al ser una herramienta gráfica de manejo de dataset, se genera código a medida que se va utilizando la librería, como resumen se entrega el código final de las modificaciones realizadas que se puede ver en el video adjunto.

Encontrarán código ejemplo  en la carpeta MITO_Titanic.ipynb


.-
