# database-control
En este repositorio se encuentran los archivos para controlar las bases de datos Oracle mediante notebooks python
El proyecto incluye pasar los scripts de health check y controles semanales


Para configurar el entorno de trabajo con jupyter y todas las herramientas necesarias para este curso, pueden ejecutar los siguientes comandos:

$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ bash Miniconda3-latest-Linux-x86_64.sh
$ conda create --name dbaremoto-ayv python=3.5 numpy scipy jupyter nb_conda
$ source activate dbaremoto-ayv

Una vez que hayan activado el environment y clonado este repositorio, en este mismo directorio pueden ejecutar jupyter para abrir las notebooks:

$ jupyter notebook

Las librerías que utilizaremos son:

matplotlib
numpy
pandas
seaborn
