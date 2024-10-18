# Desarollo de Proyectos IA
Segunda Entrega del proyecto en Docker

### PROYECTO DE BUSCADOR DE PELÍCULAS SEMÁNTICAS
<hr>
Para el desarrollo de este proyecto fue necesario adquirir conocimientos sobre el manejo de algunas herramientas tales como :

*  Docker
*  Git
*  GitHub
*  Python 3.11

El proyecto consiste en un buscador semantico de peliculas, este proyecto funciona sobre un contenedor docker que contiene los archivos necesarios para su funcionamiento 

## COMO EJECUTAR ESTE PROYECTO?

# Requisitos
* Instalar Docker Desktop
* Python 3.11
* Libreria Pandas
* Libreria sentence_transformers
* IDE Visual Estudio Code

## Instrucciones

# clonar proyecto
* git clone https://github.com/hartor8019/IAdesarrolloproject
# Abrir una terminal dentro del proyecto(debe verse +/- asi) pero con el nombre IAdesarrolloproject
 ![image](https://github.com/user-attachments/assets/a9de3ca4-e0ed-486c-b093-24de501125ce)

# Crear una imagen docker de mi proyecto
Asegúrate de tener Docker Desktop abierto antes de ejecutar el siguiente comando:

* docker build -t IAdesarrolloproject . 

# Iniciar Imagen en docker
Para iniciar una imagen en Docker se usan los siguientes comandos.

* docker run -it IAdesarrolloproject   ó   docker run -d IAdesarrolloproject

Nota: Si lo prefiere puedes ir a la Interfaz grafica de Docker Desktop y ejecutarlo desde ahi, como se muestra en la siguiente grafica.

![image](https://github.com/user-attachments/assets/3f54115d-fe21-46c1-a624-c92879e92d5c)

Si vamos en el camino correcto deberias ver una pantalla como la siguiente:

![image](https://github.com/user-attachments/assets/1ebea1d0-e41b-406a-9384-aae6abc711c2)

## Pruebas Unitarias test_unit_search.py

Desde la consola del VSCODE del proyecto ejecutar el siguiente comando :
* python -m unittest discover -v test

El anterior comando ejecutar todas las pruebas que se encuentren dentro del directorio test y deberias ver algo como esto.

![image](https://github.com/user-attachments/assets/7e0f9048-d642-49a8-9d4f-793f8fa821d1)

La anterior imagen muestra que todos los escenarios de pruebas que se crearon fueron exitosos.

# Generacion de Reporte y Visualizacion Web de las pruebas
Con el fin de poder visualizar las pruebas en un entorno web debemos instalar la siguiente libreria:
pip install coverage 

coverage report (comando para guardar un reporte en el proyecto)
coverage html (esto creara un un directorio llamado htmlcov con archivo llamado index.html) el cual podras ejecutar en tu Navegador de preferencia. Si todo va bien debes ver algo como esto.

![image](https://github.com/user-attachments/assets/79d9d58f-cfca-4c7f-bfc7-fd08538ad748)

# Información adicional sobre la Entrega

En este proyecto se realizó un Análisis Exploratorio de Datos (EDA) al dataset llamado "IMDBtop1000.csv" con el fin de comprender mejor el conjunto de datos y extraer información clave de este. 

#Analisis Exploratorio de Datos (EDA)

* Nombre : EDA dataset_Peliculas.ipynb

El código resultante de este análisis y pruebas fue integrado en el archivo principal main_students.py, con el objetivo de mejorar su desempeño y funcionalidad en el contexto del proyecto.











