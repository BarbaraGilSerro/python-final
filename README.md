# Clase 11 Actividad en Python

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como `administrador en Window`
2. Creamos una carpeta o directorio: 
`mkdir python-final`
3. Entramos en ella: 
`cd python-final`
4. Iniciamos el repositorio:
`git init`
5. Creamos un archivo:
`touch finales.py`
6. Abrimos VSC:
`code .`
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
`python -V`
`python3 -V`
8. Creamos el entorno virtual en Python:
`python3 -m venv venv #Creamos el entorno virtual`
9. Activamos el entorno virtual:
`source venv/bin/activate #Activamos el entorno virtual en Linux`
`venv/scripts/activate #En windows`
10. Hacemos actualización del pip de Python
`python3 -m pip install --upgrade pip #Actualizamos el pip`
<sub>Resultado de la terminal</sub>

```sh
$ python -m pip install --upgrade pip
Requirement already satisfied: pip in c:\users\usr\appdata\local\programs\python\python312\lib\site-packages (24.0)
Collecting pip
  Downloading pip-24.1.1-py3-none-any.whl.metadata (3.6 kB)
Downloading pip-24.1.1-py3-none-any.whl (1.8 MB)
   ---------------------------------------- 1.8/1.8 MB 2.0 MB/s eta 0:00:00
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 24.0
    Uninstalling pip-24.0:
      Successfully uninstalled pip-24.0
Successfully installed pip-24.1.1
```

### 11. Investigar ¿Qué es el pip y porque lo actualizamos? 
>Pip es una herramienta que se utiliza junto con Python para instalar y administrar paquetes de software adicionales que no vienen incluidos con la instalación básica de Python. Los paquetes son conjuntos de código que se pueden reutilizar en diferentes proyectos de Python.

>Es importante actualizar pip regularmente para asegurarte de tener la última versión disponible. Las actualizaciones pueden incluir mejoras de seguridad, nuevas características y correcciones de errores. Esto garantiza que los paquetes que instales y las herramientas que uses en Python sean compatibles y estén optimizadas con las versiones más recientes de pip y de Python.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
