# Projet 8 - Réalisez un traitement dans un environnement Big Data sur le Cloud
Mise en place de PySpark en local, sur Windows 11 avec PyCharm

## Dataset
https://www.kaggle.com/datasets/moltean/fruits
Mihai Oltean, Fruits 360 dataset: new research directions, Technical report, 2021.

## Installation nécessaires
- Télécharger winutils: https://github.com/cdarlint/winutils
  - copier -> C:/hadoop-3.3.6/bin
  - env(HADOOP_HOME) = "C:\hadoop"
- Télécharger and installer Java JDK 17: https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
  - env(JAVA_HOME) = C:\Program Files\Java\jdk-17
- Télécharger and installer spark: https://spark.apache.org/downloads.html
  - env(PYSPARK_DRIVER_PYTHON) = C:\Users\chauv\.pyenv\pyenv-win\versions\3.10.11\python.exeC:\Users\chauv\.pyenv\pyenv-win\versions\3.10.11\python.exe
  - env(PYSPARK_HOME) = C:\Users\chauv\.pyenv\pyenv-win\versions\3.10.11\python.exe
  - env(PYSPARK_PYTHON) = C:\Users\chauv\.pyenv\pyenv-win\versions\3.10.11\python.exe
  - env(PYTHONPATH) = %SPARK_HOME%\python,%SPARK_HOME%\python\lib\py4j-0.10.9.7-src.zip;%PYTHONPATH%
  - env(SPARK_HOME) = C:\spark-3.5.4

## Poetry : Python Package Manager
* Python version = 3.10.11
* poetry install
* packages :
  * python = "3.10.11"
  * notebook = "^7.3.2"
  * jupyter = "^1.1.1"
  * pyspark = "^3.5.4"
  * pandas = "^2.2.3"
  * pyarrow = "^19.0.0"
  * pillow = "^11.1.0"
  * tensorflow-io = {version = "0.27.0", extras = ["tensorflow"]}
  * numpy = "^1.22"
  * scikit-learn = "^1.6.1"

## Notebook
- Utilisation de PyCharm, avec prise en charge de Jupyter
- Utilisation des CPUs uniquement
- Chemin : /P8_Notebook/
  - Notebook : /P8Fruits_local.ipynb
  - Images Test Data : /data/Test1 (importer les dossiers des images ici)
  - Spark Results : /Results


