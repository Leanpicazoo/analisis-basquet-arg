# 📊 Proyecto de Data Science - Análisis de Básquet Argentino

Este proyecto analiza el rendimiento de los equipos de la Liga Nacional de Básquet de Argentina mediante un conjunto de datos con estadísticas de partidos. Se extraen insights sobre la relación entre puntos, rebotes, asistencias y otros indicadores clave de desempeño. También se evalúa la efectividad de los lanzamientos de tres puntos y el impacto de las pérdidas de balón en el rendimiento de los equipos.

📌 Contenido del Repositorio

ProyectoDSParteI_Picazo.ipynb: Notebook con el análisis y visualización de datos.

Dataset_de_B_squet_Argentino.csv: Dataset con estadísticas de partidos.


# 📂 Cómo Usar este Proyecto

🔹 Abrir en Google Colab

Puedes abrir la notebook directamente en Google Colab haciendo clic en el siguiente enlace:

https://colab.research.google.com/drive/1SALgmlix1MhOrtTb0t4bM15D2UuGZmhL#scrollTo=5239dd07

🔹 Cargar el Dataset

El dataset se carga automáticamente desde GitHub en la notebook usando:

import pandas as pd

# URL pública del archivo CSV en GitHub
csv_url = "https://raw.githubusercontent.com/Leanpicazoo/analisis-basquet-arg/refs/heads/main/Dataset_de_B_squet_Argentino.csv"

# Cargar el dataset directamente desde GitHub
df = pd.read_csv(csv_url)
df.head()

📊 Análisis Realizados

✅ Identificación de valores perdidos en el dataset.
✅ Exploración de preguntas clave, como:

¿Existe una correlación entre los triples encestados y la cantidad de puntos anotados?

¿Los equipos que toman más rebotes suelen ganar los partidos?

¿Qué relación hay entre las pérdidas y la cantidad de asistencias?

✅ Visualizaciones:

Relación entre triples encestados, puntos y rebotes.

Promedio de rebotes y asistencias por equipo ganador.

Relación entre pérdidas, asistencias y triples intentados.

🚀 Requisitos

Para ejecutar el código, necesitas las siguientes librerías:

pip install pandas numpy matplotlib seaborn

Si usas Google Colab, las librerías ya están preinstaladas.

📝 Autor

Este proyecto fue desarrollado por Lean Picazo, con el objetivo de aplicar técnicas de Análisis de Datos y Visualización en Python en el contexto deportivo.

📧 Contacto: https://www.linkedin.com/in/leandro-flavio-picazo-galeano/

