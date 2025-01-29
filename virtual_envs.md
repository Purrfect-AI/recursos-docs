
![banner PurrfectAI](purrfectAI_banner.png)


## Entornos virtuales



Para el desarrollo de los cursos (y la vida en general) recomendamos altamente el manejo de *entornos virtuales*, independientemente del sistema operativo que suelan usar. 
Un entorno virtual no es más que la instalación __aislada__ de Python (en nuestro caso) y sus librerías.  
Los entornos virtuales nos permiten independizarnos de las versiones de los paquetes de nuestro sistema operativo, es decir que podemos instalar, desinstalar, cambiar versiones e ir probando distintas librerías a nuestra conveniencia sin miedo a romper nada.


#### Opción 1: Conda (recomendada)
Conda es una poderosa herramienta open source de línea de comandos (CLI) que permite la gestión de entornos virtuales y sus librerías tanto en Linux, macOS y Windows. Esta es la opción recomendada por el equipo de Purrfect AI.
Con sólo un par de comandos, es posible crear un entorno e instalar los paquetes necesarios para tu proyecto.
Para instalar Conda, puedes usar [Miniconda](https://docs.anaconda.com/miniconda/). Esto te permitirá instalar Conda, Python y los paquetes de los que dependen ambos.
En el siguiente repositorio puedes ver un paso a paso de cómo instalar Conda usando [Miniconda by Jwackito](https://github.com/jwackito/conda-environments-tutorial/blob/main/Conda%20Environments.md).

#### Opción 2: Anaconda

Para quienes gusten de las interfaces gráficas, la opción disponible para la creación de entornos virtuales es [Anaconda Distribution](https://docs.anaconda.com/navigator/).
*Anaconda Distribution* cuenta con más de 300 paquetes pre-instalados de Data Science y Machine Learning, listos para ser usados. 
Además, la instalación incluye *Conda* y *Anaconda Navigator*, una aplicación de escritorio con una interfaz gráfica amigable que permite el manejo de entornos virtuales y sus librerías. 
Anaconda Navigator resulta muy útil cuando no estás familiarizado con el uso de terminales o línea de comandos. Mediante su interfaz gráfica podrás crear entornos virtuales y seleccionar los paquetes que desees instalar.
Desde la interfaz de Anaconda Navigator, además están disponibles diferentes IDEs y editores de código con los que puedes trabajar. 
![IDEs en Anaconda Navigator](navigator.png)

### Jupyter Notebooks

Por otro lado, está Jupyter Notebook. Ésta es una aplicación web de código abierto que permite crear y compartir documentos que contienen código, ecuaciones, visualizaciones y texto.
Los Jupyter notebooks estan divididos en celdas, cada celda puede usar un lenguaje distinto. Entre las opciones disponibles se encuentran: 
![Lenguajes disponibles en Jupyter Notebook](cell_options.png)

Los Jupyter Notebooks se pueden usar desde el navegador o en un IDE (por ejemplo Visual Studio Code).

Si te gusta trabajar desde el navegador, te recomendamos usar JupyterLab. En [ JupyterHub/Lab by Jwackito](https://github.com/jwackito/conda-environments-tutorial/blob/main/Conda%20Environments.md) sección _Configurando JupyterHub/Lab_ está disponible un paso a paso para que puedas usarlo. 

JupyterHub permite editar y correr kernels de Python (usando diferentes environments) desde el navegador. Además, tiene un Lab que permite administrar los notebooks en proyectos y administrar los kernels.

Si por el contrario, preferis trabajar con un IDE, el más usado es Visual Studio Code.
Dentro del IDE podes tener distintos repositorios o proyectos en los cuales trabajas de manera local. 

Trabajar con Jupyter Notebook en VS Code es tan simple como crear un archivo con extensión **.ipynb** dentro de tu proyecto.
*Nota: en VS Code, en la sección de Extensiones, podes instalar la extensión para Jupyter.*

En la siguiente imagen se puede ver un archivo llamado _test.ipynb_ con 2 celdas: una para ejecutar código Python y la otra Markdown. 

![Archivo con extension .ipynb](file_ipynb.png)

Para poder ejecutar código Python es necesario seleccionar el kernel (Python environments) con el que queremos trabajar. 
Los entornos virtuales creados con Conda (o Anaconda) serán los que aparezcan en la lista de Python environments. En este caso, hay 2: **base** creado por defecto y **prueba** que lo hemos creado nosotros.

![Entornos de Conda](conda_envs.png)

En la siguiente imagen se despliegan los kernels disponibles: **base** y **prueba**. 
Además, se visualizan las versiones de Python del sistema operativo. No es recomendable usarlos. 

![Lista de Python environments](list_python_envs.png)
