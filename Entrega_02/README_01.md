# Tamara Soto y Rosario Hono: Tenencia responsable

Primero se realizó una busqueda de datos obtenidos a través de encuestas realizadas con anterioridad. Buscamos interpretaciones y transferimos cada dato a un excel, donde se compararon con sus porcentajes de los resultados.

## Fuentes: 
- [Estudio de la Pontificia Universidad Católica de Chile](https://www.gob.cl/noticias/primer-estudio-de-poblacion-animal-en-chile-revela-que-hay-12-millones-de-perros-y-gatos-con-duenos-y-4-millones-sin-supervision/): Es un reporte lo más actual sobre la situación actual de animales callejeros en Chile y los que cuentan con un hogar.
- [CADEM](https://cadem.cl/wp-content/uploads/2022/05/Informe-Chile-que-Viene-Mar-2022-Mascotas.pdf): Esta es nuestra base más importante ya que cuenta con todos los datos que nos sirven para identificar una gran potencia en la conciencia de la tenencia responsable en Chile.
- [Registro Nacional de Mascotas](https://registratumascota.cl/inicio.xhtml): Nos ayuda a caracterizar la cantidad de animales en Chile.

## Preguntas:
- ¿Qué tan importante es una mascota para el chileno?
- ¿Qué tan bien cuidado es una mascota en Chile?
- ¿Cuánta conciencia se tiene respecto a una tenencia responsable?

[Vídeo de Youtube](https://youtu.be/sqecdgAtoqA)

import pandas as pd

import seaborn as sns

PROYECTO = sns.load_dataset('/content/drive/MyDrive/Colab Notebooks/base de datos proyecto/PROYECTO.csv')

PROYECTO.head()
