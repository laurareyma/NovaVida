# NovaVida
Proyecto de Programación Aplicada - Corte 1

# Importamos las librerías necesarias
# NumPy nos ayuda a manejar arreglos (matrices, vectores, etc.)
# Pandas nos permite trabajar con tablas de datos (DataFrames), muy parecido a Excel
import numpy as np
import pandas as pd
from google.colab import files

# Subir archivo desde PC
uploaded = files.upload()

# Leer el archivo CSV
NovaLife = pd.read_csv("dataset_organizado.csv", sep=";") # Debido a que no estaba mostrando
# bien las columnas, se escribe sep=";" para decirl a pandas con qué símbolo están separadas
# las columnas en el archivo csv.
NovaLife.head()
