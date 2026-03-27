# Almacenes_Mineria_Datos
Aquí se adjuntarán las tareas de Almacenes y mineria de datos.<br>
La tarea 1 se encuentra en la rama Tarea1.<br>
La tarea 2 se encuentra en la rama Tarea2, los pasos para ejecutar en quarto se encuentran al final de este README.<br>
<br>

## Los integrantes del equipo son:<br>
Cruz Campos José Eduardo - 319312087<br>
Martínez Hidalgo Paola Mildred - 319300217<br>
Trujillo Beltrán Zianya Nenetzi -  319210787<br>
Toporek Coca Eric - 314284987<br>

# Requisitos
Python >=3.11    

# Visualizar la página web:
1. Puedes ver el documento cargado a github.io con la siguiente url: https://zyant28.github.io/


# Pasos de instalación y ejecución de Quarto (para linux)
1. Descargar quarto desde la página oficial: https://quarto.org/docs/download/ 
2. Instalar con dpkg el paquete .deb, 
    ```bash
    $ sudo dpkg -i quarto-1.9.35-linux-amd64.deb    
3. Crear un entorno virtual de python para ejecutar el proyecto en quarto e instalar dependencias: <br>
    ```bash
    1.1 $ python -m venv .venv 
    2.1 $ source .venv/bin/activate 
    3.1 $ pip install -r requirements.txt
4. Ejecutar quarto desde la terminal y con el entorno activo,
    ```bash
    $ quarto render index.qmd
    $ quarto preview index.qmd


# Pasos de instalación y ejecución de Quarto (para windows)
1. Descargar quarto desde la página oficial: https://quarto.org/docs/download/ 
2. Hacer click derecho e instalar
3. Elegir la herramienta con la que se trabajará (VS Code, Jupyter, Neovin, Positrón, etc)
4. Instalar y configurar esa herramienta.
5. Integrar Quarto correctamente.
6. Renderizar tus documentos desde esa plataforma.
7. Crear un entorno virtual de python para ejecutar el proyecto en quarto: <br>
    ```bash
    1.1 $ python -m venv .venv
    2.1 $ .venv\Scripts\activate 
8. Instalar dependencias:
    ```bash
    $ pip install -r requirements.txt
9. En caso de que salga un erropr de que no encuentra Jupyter o TinyTex ejecutar dentro del entorno
    ```bash
    $pip install jupyter nbformat ipykernel    
10. Ejecutar quarto desde la terminal y con el entorno activo,
    ```bash
    $ quarto render Tarea2.qmd
    $ quarto preview Tarea2.qmd

Se deberan instalar dependencias y bibliotecas que quarto te pide con python, como: TinyTex,Jupyter.
Para verificar que quarto esta bien instalado se utiliza el comando:
    ```bash
    $ quarto check

**IMPORTANTE: verificar que estas utilizando el entorno virtual del proyecto y no otro que no tenga instaladas las dependencias, o que no tengas activada CONDA de python**


# Agregar cambios a la página web:
1. Puedes editar el archivo index.qmd que es básicamente el archivo en quarto, ubicado en la rama main.
2. Cargar los cambios renderizando quarto con:
    ```bash
    $ render quarto

3. Subir cambios al repositorio de github:
    ```bash
    $ git add .
    $ git commit -m "cambios n"    
    $ git push origin main
**Los cambios en la pagina tardan aprox 10 minutos en cargar.**