1) Crear un entorno de conda utilizando el archivo .yml que contiene las librerias a instalar:
  conda env create -f file.yml
2) Si la alternativa anterior no funciona crear un nuevo entorno como: 
conda create --name <nombre que quieran>
conda activate nombre_del_entorno
pip install -r requirements.txt  (Asegurense de tener el file requirements.txt en el folder en el directorio de trabajo actual)
